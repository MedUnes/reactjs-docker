# reactjs-docker
A docker container for reactjs

## Build

```bash
$ docker-compose up --build -d
```
* Then open-up http://localhost:3000

## Login
```bash
$ docker-compose exec frontend bash
node@b4e9b0a572f6:/app/tic-tac-toe$ npm -v
8.11.0
node@b4e9b0a572f6:/app/tic-tac-toe$ 
```

## Stop

```bash
$ docker-compose stop
```
or

```bash
$ docker-compose down
```

for more info:

* https://docs.docker.com/compose/
* https://reactjs.org/tutorial/tutorial.html#setup-for-the-tutorial
* https://hub.docker.com/_/node
