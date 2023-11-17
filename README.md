# Snibox: Docker deployment
Scripts to setup [Snibox](https://github.com/snibox/snibox) on your machine using [Docker Compose](https://docs.docker.com/compose/).

## Table of Contents
- [Deployment](#deployment)
- [Controls](#controls)
- [Upgrade to latest version](#upgrade-to-latest-version)    
- [License](#license)

## Deployment
Clone the repository:
```
git clone https://github.com/snibox/snibox-docker.git
```

Setup services:
```
./bin/setup
```

Launch [Snibox](https://github.com/snibox/snibox) at 8000 port:
```
./bin/start
```

Visit http://localhost:8000/ to view the project!

## Controls
You can use [docker compose commands](https://docs.docker.com/compose/reference/overview/) to run containers as usual.

At the same time next wrappers available for quick start:

- start
```
./bin/start
```

- stop
```
./bin/stop
```

- restart
```
./bin/restart
```

## Upgrade to latest version
Backup database.

Update scripts:
```
git pull
```

Update services:
```
./bin/setup
```

## License
Released under the [MIT License](https://opensource.org/licenses/MIT).
