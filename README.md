# docker-steam-client
```bash
docker run --name=steam --rm -v /dev/dri:/dev/dri -v /tmp/.X11-unix:/tmp/.X11-unix -v /dev/shm:/dev/shm -v /run/user/${UID}/pulse:/run/user/${UID}/pulse -v /etc/machine-id:/etc/machine-id -v ${HOME}/Downloads:/tmp/Downloads --privileged=true -e DISPLAY=$DISPLAY windsor106/steam:latest
```
