docker-graphity-server
======================

# Building

```
$ docker build -t `whoami`/graphity-server .
```

# Running

As daemon:

```
$ docker run -itd `whoami`/graphity-server
$ docker exec -it <container-id> /bin/bash
```
