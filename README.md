# tuic-sserver-docker
Run TUIC server in docker

TUIC: https://github.com/EAimTY/tuic

Docker Hub: https://hub.docker.com/r/ricky9w/tuic-server

Docker Compose:
```yaml
version: '3'

services:
  tuic-server:
    image: ricky9w/tuic-server:{{ tag }}
    network_mode: {{ network mode }}
    volumes:
      - /path/to/you/config.json:/etc/config.json
```
