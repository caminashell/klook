# KDE Look (quicklook)

## Introduction

> [!WARNING]
> This project is for exploratory research to revive an old feature, therefore experimental and will have no active support. It is recommended to back up system before using it for production.

Klook is a quick preview feature based on Qt and Qt Quick, allows users to look at the contents of a file in the Dolphin

## Requirements

To build you must have following programs and packages installed:

`cmake extra-cmake-modules libkf5kdelibs4support-dev qtmultimedia5-dev libkf5declarative-dev libkf5plasma-dev install exiv2 libexiv2-dev libkf5kexiv2-dev`

<!-- CHECK LIST: `cmake extra-cmake-modules qtdeclarative5-dev qtmultimedia5-dev libkf5kdelibs4support-dev libqt5x11extras5-dev libkf5iconthemes-dev libkf5plasma-dev libkf5windowsystem-dev libkf5declarative-dev libkf5xmlgui-dev libkf5activities-dev libphonon4qt5-dev build-essential libxcb-util-dev libkf5wayland-dev git gettext libkf5archive-dev libkf5notifications-dev libxcb-util0-dev libsm-dev libkf5crash-dev libkf5newstuff-dev libxcb-shape0-dev libxcb-randr0-dev libx11-dev libx11-xcb-dev kirigami2-dev` -->

## Install

To install it just do:

```sh
mkdir build
cd build
cmake .. && make && make install
```

> [!NOTE]
> If you want to use KLook from Dolphin you also have to apply Dolphin patches that make Klook show up on pressing space.

You can also use it with StackFolder plasma applet, that can be downloaded here.
StackFolder does has support for KLook built-in so you just have to install the package from https://abf.rosalinux.ru/projects/50034

## Known Issues

Upon build, Exiv2 version check fails, but the build continues to completion.

> ```log
> Could NOT find Exiv2: Found unsuitable version "..", but required is at least "0.19" (found /usr/lib/x86_64-linux-gnu/libexiv2.so)
> ```

## Example Video Demonstration (old)

[<img src="https://img.youtube.com/vi/kOcYn8NRyGY/hqdefault.jpg" width="100%" />](https://www.youtube-nocookie.com/embed/kOcYn8NRyGY)
*CTRL+Click to open in new tab/window*
