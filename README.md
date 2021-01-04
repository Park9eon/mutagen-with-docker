```shell

brew install mutagen-io/mutagen/mutagen

mutagen daemon start

docker-compose run app

mutagen sync create --name=mutagen-with-docker $PWD \
  docker://${container_name}/app

```
