# youtube-dlG

A cross platform front-end GUI of the popular [youtube-dl](http://rg3.github.io/youtube-dl/) media downloader, written in wxPython. [List of supported sites](https://rg3.github.io/youtube-dl/supportedsites.html).

## Screenshots

**Main window**

![Youtube-dl-gui main window](http://i.imgur.com/I4oXPWs.png)

**Options window**

![Options window](http://i.imgur.com/eShdoLD.png)

## Installation

**Linux (from source):** `sudo python setup.py install`

**Linux (Ubuntu PPA):** https://launchpad.net/~flexiondotorg/+archive/ubuntu/youtube-dl-gui

**Linux (Arch AUR):** https://aur.archlinux.org/packages/youtube-dl-gui-git/ (TODO: update)

**Windows:** https://github.com/MrS0m30n3/youtube-dl-gui/releases/download/0.3.8/youtube-dl-gui-0.3.8-win-setup.zip

**Mac:** TODO Package app

Then you can call youtube-dlg from the command line, using the `youtube-dl-gui` command, or by creating a desktop launcher (TODO)

## Contributing

**Support for new language:** See [Localization HOWTO](locale_build/HOWTO.md).

**Reporting bugs:** See [Issues](https://github.com/MrS0m30n3/youtube-dl-gui/issues).


## Requirements
[Python](http://www.python.org) 2.7+, [wxPython](http://wxpython.org), [FFMPEG & FFPROBE](http://www.ffmpeg.org) (optional, to convert video files to audio-only files).

## Authors

See [AUTHORS](AUTHORS) file
      
## License

The [Public Domain License](LICENSE)

## Thanks

Thanks to youtube-dl authors for creating such an amazing tool.
