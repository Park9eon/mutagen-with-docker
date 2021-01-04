```shell

brew install mutagen-io/mutagen/mutagen

mutagen daemon start

docker-compose up

mutagen sync create --name=mutagen-with-docker $PWD \
  docker://${container_name}/app

```

```shell

brew install mutagen-io/mutagen/mutagen-beta

mutagen daemon start

mutagen compose up

```
