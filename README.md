# ScaDaMaLeZp
Zeppelin version of ScaDaMaLe via docker-compose.

This is mainly for learning locally. We will use databricks for Assignments and Group Projects.

# Minimal Student Instructions

-  install docker-compose with prerequisites from https://docs.docker.com/compose/install/
-  download ScaDaMaLeZp.zip from here.

```
$ unzip ScaDaMaLeZp.zip
$ cd ScaDaMaLeZp
$ ls
confZp                  docker-compose.yml      notebook
datasets-sds            logs
$ docker-compose up -d
```

You should see:

```
Creating network "scadamalezp_default" with the default driver
Creating scadamalezp_zeppelin_1 ... done
```

- browse http://localhost:8080/ for zeppelin and http://localhost:4040/ for SparkUI

- when done with work

```
$ docker-compose down
```

