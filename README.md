# batocera-containers
<html>
<body>
<i>this repo provides appimaged podman containers<br>
for use inside x86_64 batocera.linux v36/37<br></i>
<br>

| appimage | docker container | description |
| --- | --- | --- |
| [alpine.AppImage](./containers/alpine.AppImage) | docker.io/library/alpine:latest | alpine 3.17 stable |
| [arch.AppImage](./containers/arch.AppImage) | docker.io/library/archlinux | archlinux latest |
| [debian.AppImage](./containers/debian.AppImage) | docker.io/library/debian:11 | debian 11 bullseye |
| [debian12.AppImage](./containers/debian12.AppImage) | docker.io/library/debian:testing | debian 12 bookworm/jessie |
| [plex.AppImage](./containers/plex.AppImage) | docker.io/plexinc/pms-docker:latest | plex media server |
| [ubuntu.AppImage](./containers/ubuntu.AppImage) | docker.io/library/ubuntu:20.04 | ubuntu 20.04 focal fossa |
| [ubuntu22.AppImage](./containers/ubuntu22.AppImage) | docker.io/library/ubuntu:22.04 | ubuntu 22.04 jammy jellyfish |

<br>
<b><i>HOW TO USE: </b></i>
<p style="background:#333;color:#ababab;padding:10px;margin:10px;">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  wget https://github.com/uureel/batocera-containers/blob/main/containers/ubuntu.AppImage<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  chmod a+x ubuntu.AppImage<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  ./ubuntu.AppImage<br>
<br>
</p>
<img src=https://user-images.githubusercontent.com/116395185/230185360-c6665b15-4031-4643-bfc7-dc5b7ce214d7.png style="width: 66%; height: 66%;"></img>
</body>
</html>
