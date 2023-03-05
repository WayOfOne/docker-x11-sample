## Instructions

To get the display working we need to pass the unix domain socket and the display to the docker container

```bash
sudo docker  run -it -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=$DISPLAY xclock
```


## Resources

https://learn.microsoft.com/en-us/windows/wsl/tutorials/gui-apps
https://github.com/microsoft/wslg/blob/main/samples/container/Containers.md