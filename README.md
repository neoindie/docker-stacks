# docker-stacks

Useful docker stacks

## Usage

```
docker stack deploy -c https://raw.githubusercontent.com/neoindie/docker-stacks/master/STACKNAME.yml STACKNAME
```

## Dependencies

- Docker 12+
- Docker Swarm Mode
- REX-Ray DigitalOcean Block Storage plugin - [info](https://github.com/rexray/rexray/blob/master/.docs/user-guide/storage-providers/digitalocean.md#do-block-storage) and [docs](https://rexray.readthedocs.io/en/stable/user-guide/schedulers/docker/plug-ins/digitalocean/#do-block-storage)
- DigitalOcean services (Droplets and Volumes aka. Block Storage)
- Caddy as a [reverse proxy](https://github.com/lucaslorentz/caddy-docker-proxy). You need to create a docker network manually and setup every container (including Caddy) to use that.


Feedback is welcome.
