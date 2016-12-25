[![Stories in Ready](https://badge.waffle.io/ayousif00/bottleplant.png?label=ready&title=Ready)](https://waffle.io/ayousif00/bottleplant)
# bottleplant
A Resin.io powered digital logging system for a Bottle Plant


Currently it is targeting a raspberry pi and builds upon a debian wheezy base image. However, it is easy to 
change this to target any of the other targeted platforms supported by resin.io, all that you need to do is 
change the line:
```
FROM resin/rpi-raspbian:jessie
```

__Note:__ Obviously apt package manager will only work in Debian environments.
