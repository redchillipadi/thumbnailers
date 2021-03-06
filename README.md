**Krita Thumbnailer Script**

This script extracts the preview.png thumbnail from [Krita files](https://krita.org/ "Krita") to allow it to be viewed in file managers such as Nautilus or Thunar.

It is released under GPL 2 and tested under python 3.5

**Installation**
* Copy the krita-thumbnailer.py to a folder in the path eg /usr/bin/
* Copy the krita.thumbnailer file to ~/.local/share/thumbnailers/ (for [Nautilus](https://wiki.gnome.org/Apps/Nautilus "Nautilus")) or /usr/share/thumbnailers/ (for [Thunar](https://docs.xfce.org/xfce/thunar/start "Thunar") with the tumbler plugin)

**Usage**

Apart from file manager integration using the krita.thumbnailer file above, it is possible to run the script from the command line.

krita-thumbnailer.py [-s size] input output

where
* input is the input (.krita) file to process
* output is the output (.png) file to store the thumbnail
* size is optional and scales the output file to the specified number of pixels
