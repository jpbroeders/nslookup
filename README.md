# Nslookup command dockerized #
This is a docker build with the linux nslookup command. The image is based on the Ubuntu image included the dnsutils package.

## Build
```
$ docker build -t freelyit/nslookup .
```

## Run
```
$ docker run --rm freelyit/nslookup <domain.com>
```