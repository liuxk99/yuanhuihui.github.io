---
layout: post
title:  "搭建Flutter框架的开发环境"
date:   2019-06-07 21:15:40
catalog:  true
tags:
    - flutter

---

## 一、相关依赖

- Linux，Mac OS X或者Windows
- git：用于源码的版本控制;
- ssh client：用于Github的认证;
- IDE: [带有Flutter插件的Android Studio](https://flutter.dev/docs/development/tools/android-studio)，这是官方推荐的旗舰IDE;
- Python: 很多工具都需要用到Python，比如gclient;
- Android platform tools：可使用如下命令来安装
    - Mac: brew cask install android-platform-tools
    - Linux: sudo apt-get install android-tools-adb

## 二、安装环境

- 确保adb可用，可通过which adb命令检测命令是否可用。
- Fork一份Flutter Framework代码，https://github.com/flutter/flutter
- 将flutter的bin添加到PATH
- 执行命令flutter update-packages，来获取Flutter所依赖的Dart Packages