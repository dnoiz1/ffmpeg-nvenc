# FFmpeg + nvenc build script

This script will compile FFmpeg with Nvidia NVENC support enabled.
It can also build OBS Studio or Simple Screen Recorder using that FFmpeg build
thus providing NVENC for OBS.

It is brought to you by [Linux GameCast](http://linuxgamecast.com/) and
[Lutris](https://lutris.net) #lgccares

## Usage

Clone the repo then use the `build.sh` script to compile the binaries

```
git clone https://github.com/lutris/ffmpeg-nvenc.git
cd ffmpeg-nvenc
./build.sh --dest $HOME/apps/ffmpeg-nvenc
```

The following command line options are available:

* -d / --dest <path> : Destination path for FFmpeg / OBS
* -o / --obs : Build OBS Studio
* -h / --help : Usage

## TODO

* Add support for multiple distributions (currently only tested on Ubuntu 16.04)

## Supporting the authors

If you find this script useful, you can consider
supporting [Linux GameCast](https://www.patreon.com/linuxgamecast)
and [Lutris](https://www.patreon.com/lutris).

# Patches applied

* https://github.com/libav/libav/commit/141c960e21d2860e354f9b90df136184dd00a9a8.patch

*This is very likely to break future versions!* 
