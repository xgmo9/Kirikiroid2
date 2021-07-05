Kirikiroid2 - A cross-platform port of Kirikiri2/KirikiriZ
==========================================================

Based on most code from [Kirikiri2](http://kikyou.info/tvp/) and [KirikiriZ](https://github.com/krkrz/krkrz)

Video playback module modified from [kodi](https://github.com/xbmc/xbmc)

Some string code from [glibc](https://www.gnu.org/s/libc) and [Apple Libc](https://opensource.apple.com/source/Libc).

Real-time texture codec modified from [etcpak](https://bitbucket.org/wolfpld/etcpak.git), [pvrtccompressor](https://bitbucket.org/jthlim/pvrtccompressor), [astcrt](https://github.com/daoo/astcrt)

Android storage accessing code from [AmazeFileManager](https://github.com/arpitkh96/AmazeFileManager)



HOW TO BUILD
============

Only Linux build script.

1. Download third party libraries, and build these as static libraries.
```
cd 3rd
./download_3rd_lib.sh
./build_prebuilt_lib.sh
```

or download the file from [release](https://github.com/ningshanwutuobang/Kirikiroid2/releases/)

2. Open prej.android in android studio.


There are some steps left for a runnable apk file.
- Using cocos studio compile ui/layout file *.csd.
- Some files from a real apk (unzip).
- Fix some bugs because of incompatible version.
