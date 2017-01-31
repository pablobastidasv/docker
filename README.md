## node-ng

### How to used

#### Docker RUN
You can use the following template for run from console with
`docker run` command.

```Docker
docker run -d -p 4200:4200 -p 49153:49153 -v $PWD:/usr/src/app --name=angular2_app pablobastidasv/node-ng
```

#### Dockerfile
