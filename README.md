# SpaceBukkit-docker

Run using

```sh
docker run --detach \
    --env 'VIRTUAL_HOST=<Your-Host>' \
    --env 'VIRTUAL_PORT=80' \
    -p 25565:25565 \
    --name spacebukkit \
    --restart always \
    --volume /<Your-volume>:/data \
    killergoldfisch/spacebukkit-docker
```
### MySQL Settings

Host: localhost
Database: spacebukkit
Username: root
Password: <empty>

### SpaceBukkit Settings:

Host: localhost
Salt: BE0344D48B234E3FB36A2D13698B2A58
Ports: 2011 and 2012