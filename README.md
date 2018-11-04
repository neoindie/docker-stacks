# docker-stacks

Useful docker stacks

## Usage

```
docker stack deploy -c https://raw.githubusercontent.com/neoindie/docker-stacks/master/STACKNAME.yml STACKNAME
```

## Dependencies

- Docker 12+
- Docker Swarm Mode
- Caddy as a [reverse proxy](https://github.com/lucaslorentz/caddy-docker-proxy). You need to create a docker network manually and setup every container (including Caddy) to use that.


Feedback is welcome.
