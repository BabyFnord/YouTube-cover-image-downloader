# Purpose
Downloads and converts images to the current working directory of your shell. Maybe useful for presentations …

# Requirements 
This shell script has been developed and tested using macOS 16.6.1, it'll likely run with older/recent OS versions and Linux, too. [yt-dlp](https://github.com/yt-dlp/yt-dlp) and [ImageMagick](https://imagemagick.org) are required to be in your $PATH, unless you adapt the script to run your binaries elsewhere. 

# nota bene
Converted images are sequentially renamed "Thumb_xxx.jpg", the counter for `xxx` does not account for already existing images in your current folder. 
