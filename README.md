# nrc-demo
Demo/playground for NRC playbook using Hugo

## Getting started

```
git submodule init
git submodule update
```

## Development

Run `docker-compose up server`

## Build

Run `docker-compose up build`

## Running Hugo Commands

```shell script
docker-compose run build {command to be run} 
```

e.g. `docker-compose run build new theme spiffy`
