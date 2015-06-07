# redis

Redis Server

## Steps

1. Pull redis repo
```sh
$ git clone https://github.com/docker-library/redis.git
```

2. Select Redis Version
```sh
$ cd redis/3.0
```

3. Build
```sh
$ docker build -t magento/redis-server .
```

4. Run
```sh
$ docker run --name redis -p 6379:6379 -d redis
```