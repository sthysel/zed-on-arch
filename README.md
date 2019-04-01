# Stereo Labs ZED on Arch Linux

![ZED](docs/depth.png)


## Using docker

See [ZED Docker](https://github.com/stereolabs/zed-docker)

Install nvidia-docker

Get latest zed ZDK packed in docker container

``` zsh
$ xhost +si:localuser:root
$ docker pull stereolabs/zed:ubuntu1604-cuda9.0-zed2.7-gl
$ nvidia-docker run -it --privileged -e DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix stereolabs/zed:ubuntu1604-cuda9.0-zed2.6-gl
# /usr/local/zed/tools/ZED\ Explorer
```
