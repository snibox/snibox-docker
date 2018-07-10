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
./bin/docker/setup
```

Launch [Snibox](https://github.com/snibox/snibox) at 8000 port:
```
./bin/docker/start
```

Visit http://localhost:8000/ to view the project!

## Controls
- start
```
./bin/docker/start
```

- stop
```
./bin/docker/stop
```

- restart
```
./bin/docker/restart
```

## Upgrade to latest version

Update scripts:
```
git pull
```

Update services:
```
./bin/docker/setup
```

## Licence
Released under the [MIT License](https://opensource.org/licenses/MIT).
