# Containerized Dell RACADM client

## Why?

So I can make changes to iDRACs everywhere.

## Usage

```
docker build -t eminguez/racadm
docker run -it eminguez/racadm -r <ip> -u <user> -p <pass> <command> [args...]
```

## References
Forked from https://github.com/justinclayton/docker-racadm
