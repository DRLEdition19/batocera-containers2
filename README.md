# batocera-containers
<html>
<body>
<!--<i>this repo provides appimaged podman containers<br>
for use inside x86_64 batocera 6/37<br></i>-->
<br>
  <b><i><u>CONTAINERS FOR X64 BATOCERA 36/37/38/39: </u></b></i><br>
<br>

| all-in-1 appimage | docker container | description |
| --- | --- | --- |
| [alpine.AppImage](./containers/alpine.AppImage) | docker.io/library/alpine:latest | alpine 3.17 stable |
| [arch.AppImage](./containers/arch.AppImage) | docker.io/library/archlinux | archlinux latest |
| [debian11.AppImage](./containers/debian11.AppImage) | docker.io/library/debian:11 | debian 11 bullseye |
| [debian12.AppImage](./containers/debian12.AppImage) | docker.io/library/debian:12 | debian 12 bookworm/jessie |
| [ubuntu20.AppImage](./containers/ubuntu.AppImage) | docker.io/library/ubuntu:20.04 | ubuntu 20.04 focal fossa |
| [ubuntu22.AppImage](./containers/ubuntu22.AppImage) | docker.io/library/ubuntu:22.04 | ubuntu 22.04 jammy jellyfish |
| [batocera-sunshine](https://batocera.pro/app/batocera-sunshine) | [sunshine@ubuntu:20.04](https://github.com/LizardByte/Sunshine) | sunshine 0.20.0 @ ubuntu:20.04 |
| [batocera-jellyfin](https://batocera.pro/app/batocera-jellyfin) | [jellyfin/jellyfin](https://hub.docker.com/r/jellyfin/jellyfin) | jellyfin latest |
| [batocera-plex](https://batocera.pro/app/batocera-plex) | [plexinc/pms-docker](https://hub.docker.com/r/plexinc/pms-docker) | plexinc/pms-docker latest |

<br>
<br>
<b><i><u>HOW TO USE: </u></b></i>
<p style="background:#333;color:#ababab;padding:10px;margin:10px;">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  wget https://github.com/DRLEdition19/batocera-containers2/tree/main/containers/ubuntu22.AppImage<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  chmod a+x ubuntu22.AppImage<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  ./ubuntu22.AppImage<br>
</p>
<br>
<br>
<b><i><u>TO SAVE/EXPORT THE CONTAINER FILESYSTEM: </u></b></i>
<p style="background:#333;color:#ababab;padding:10px;margin:10px;">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  run: <i><b>/ubuntu22/save.sh from inside the container</b></i> to store it into /userdata/system/ubuntu22 in batocera;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  (or: <i><b>/arch/save.sh from inside the arch container</b></i> to store it into /userdata/system/arch in batocera, etc)<br>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <b>TO LOAD THE EXPORTED FILESYSTEM</b>, run it from batocera as: &nbsp;&nbsp;<i><b>ubuntu22.AppImage load</b></i><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  *&nbsp;&nbsp; when you load the filesystem, you don't need to save it anymore <br>
<br>
<br>
</p>
<img src=https://user-images.githubusercontent.com/116395185/230185360-c6665b15-4031-4643-bfc7-dc5b7ce214d7.png style="width: 50%; height: 50%;"></img>
</body>
</html>
