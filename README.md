# Hello World with Traefik, Docker, and Hapi.js

To make this work properly, you'll need to edit your `/etc/hosts` file.
e.g. if using this rule,
` traefik.frontend.rule=Host:service_1.docker.localhost`
add the hostname
```
127.0.0.1 service_1.docker.localhost
```

Then on your host machine, you can use `service_1.docker.localhost`, e.g.
```
$ curl service_1.docker.localhost/hello
```
