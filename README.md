[![Build Status](https://travis-ci.org/ayousif00/bottleplant.svg?branch=master)](https://travis-ci.org/ayousif00/bottleplant) [![Standard - JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/) [![Coverage Status](https://coveralls.io/repos/github/ayousif00/bottleplant/badge.svg?branch=master)](https://coveralls.io/github/ayousif00/bottleplant?branch=master)


# bottleplant
A Resin.io powered digital logging system for a Bottle Plant


Currently it is targeting a raspberry pi and builds upon a debian wheezy base image. However, it is easy to 
change this to target any of the other targeted platforms supported by resin.io, all that you need to do is 
change the line:
```
FROM resin/rpi-raspbian:jessie
```

__Note:__ Obviously apt package manager will only work in Debian environments.
