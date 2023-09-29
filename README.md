## Install Home Assistant Container

### DOCKER COMPOSE

<https://www.home-assistant.io/installation/alternative>

docker compose should already be installed on your system. If not, you can manually install it.

As the Docker command becomes more complex, switching to docker compose can be preferable and support automatically restarting on failure or system restart.

```bash
docker compose up -d
```

Once the Home Assistant Container is running, Home Assistant should be accessible using this URL. (replace with the hostname or IP of the system).

```
http://<host>:8123 
```
