# python-opencv-dlib
[![Automated Build](https://img.shields.io/docker/automated/namkuspa/python-opencv-dlib.svg)](https://hub.docker.com/r/namkuspa/python-opencv-dlib/)
[![Build Status](https://img.shields.io/docker/build/namkuspa/python-opencv-dlib.svg)](https://hub.docker.com/r/namkuspa/python-opencv-dlib/)


| Tag   | Size | Layers |
|-------|------|--------|
| 3.6.6 | [![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/namkuspa/python-opencv-dlib/3.6.6.svg)](https://hub.docker.com/r/namkuspa/python-opencv-dlib/)    | [![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/namkuspa/python-opencv-dlib/3.6.6.svg)](https://hub.docker.com/r/namkuspa/python-opencv-dlib/)|

## Nota
Esta imagen usa la version `headless` del wheel `opencv-python`, ya que no necesita las depencias para interfaz grafica

## ¿Cómo usar?
```console
$ docker run --rm -it namkuspa/python-opencv-dlib:3.6.6
Python 3.6.6 (default, Jun 27 2018, 22:32:42) 
[GCC 6.3.0 20170516] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import dlib
>>> import cv2
>>> dlib.__version__
'19.13.0'
>>> cv2.__version__
'3.4.1'
```

