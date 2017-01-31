## node-ng

### How to used

#### Docker RUN
You can use the following template for run from console with
`docker run` command.

```Docker
docker run -d -p 4200:4200 -p 49153:49153 -v $PWD:/usr/src/app --name=angular2_app pablobastidasv/node-ng
```

#### Docker compose
You can use the following template to create a docker-compose.yml file in
the root dir project

```Docker
version: "2"

services:
  app-fe:
    image: pablobastidasv/node-ng
    volumes:
    - .:/usr/src/app
    ports:
    - "4200:4200"
    - "49153:49153"
```

After this, you must execute the next command
```shell
docker-compose up
```
