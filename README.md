# EPB Dev Tools

The Energy Performance of Buildings Register service consists of several 
distinct applications.

* authentication server
* epb api
* epb frontend

These dev tools give us a stable environment where all the applications are
preconfigured to just work.

## Up and Running

**Requirements**

* docker
* docker-compose
* bash 4
* git

**Getting up and running**

```shell script
$ make setup
```

## Shutting down

```shell script
docker-compose down
```
