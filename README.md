# mpeg-dash-test

## Usage

Setup docker

```
$ sudo apt-get install docker-ce

$ sudo docker run --rm hello-world
 > Hello World!

$ docker pull jrottenberg/ffmpeg:3.3

$ docker pull sambaiz/mp4box
```

Setup alias

```
$ alias ffmpeg='docker run --rm -v `pwd`:/tmp/workdir jrottenberg/ffmpeg:3.3'

$ ffmpeg -version
 > ffmpeg version 3.3.6 Copyright (c) 2000-2017 the FFmpeg developers...

$ alias MP4Box='docker run --rm -v `pwd`:/work sambaiz/mp4box'

$ MP4Box -version
 > MP4Box - GPAC version 0.6.1-rev14-g8eb0297-master...
```
