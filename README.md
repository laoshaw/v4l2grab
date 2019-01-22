v4l2grab
========

## quick build on ubuntu 1804

sudo apt install libjpeg-dev libv4l-dev autoconf automake
gcc -Wall v4l2grab.c yuv.c -lv4l2 -ljpeg -o v4l2grab

## basics

[![Travis](http://img.shields.io/travis/twam/v4l2grab/master.svg)](https://travis-ci.org/twam/v4l2grab/)
[![GitHub license](https://img.shields.io/github/license/twam/v4l2grab.svg)]()

This is a small command line utility for grabbing JPEGs form V4L2 devices (e.g. USB webcams).

For installation, follow the instructions into the [GitHub Wiki](https://github.com/twam/v4l2grab/wiki/Installation).

Try `./v4l2grab -h` or just `v4l2grab` if you have installed it to get some help.

If your webcam works, please add it to the [Compatible Devices](https://github.com/twam/v4l2grab/wiki/Compatible%20Devices) table.
