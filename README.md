![mpv logo](https://raw.githubusercontent.com/mpv-player/mpv.io/master/source/images/mpv-logo-128.png)

mpv is a no-nonsense, super-fast, minimal, efficient, lightweight, highly customizable player.

![img](https://github.com/Sharad104/mpv-config/blob/main/preview.jpg)

### To install mpv on Windows:

1. Download the latest version from [here](https://sourceforge.net/projects/mpv-player-windows/files/ "sourceforge link").
2. Extract the zip file.
3. Place the extracted folder in your C drive.
4. Add the mpv.exe path to the environment variables (system variables path).
5. Run `mpv_install.bat` as ADMIN under the installer folder to assign all video file extensions to mpv.


### To install mpv on Ubuntu/Linux :
1. Open terminal and execute these commands one by one
2. `sudo add-apt-repository ppa:mc3man/mpv-tests` 
3. `sudo apt update`
4. `sudo apt install mpv`


### Configuration :

mpv configuration files are stored in `C:\Users\USERNAME\AppData\Roaming\mpv\` on windows and `~/.config/mpv/` on linux . If this mpv folder doesn’t exist, create one.

This folder generally stores mpv.conf file and input.conf file. The mpv folder contains subfolders named "scripts" and "script-opts" which store scripts and script settings/options.


### scripts included : 
- [chapterskip.lua][1]: Automatically skips chapters Based on title like OP/Opening ED/Ending in Anime.
- [modernx.lua][2]: Modern-looking interface for ON SCREEN CONTROLLS.
- [mpv_chapters.js][3]: Display chapters using 'Tab' key and select using mouse click.
- [playlistmanager.lua][4]: This script allows you to see and interact with your playlist in an easy way using 'F2' key.
- [webm.lua][5]: Make simple WebM clips using 'F1' key.
- [thumbfast.lua][6]: lightweigh thumbnail generator script working with modernx script.
- [history.lua][7]: stores the history of played files to history.txt at mpv config folder
- [FSRCNNX shader][8] : Fast Super-Resolution Convolutional Neural Network X . It upscales lower-resolution videos to higher-resolution without making it look blurry via neural networks.

[1]: https://github.com/po5/chapterskip
[2]: https://github.com/cyl0/ModernX
[3]: https://github.com/zxhzxhz/mpv-chapters
[4]: https://github.com/jonniek/mpv-playlistmanager
[5]: https://github.com/ekisu/mpv-webm
[6]: https://github.com/po5/thumbfast
[7]: https://github.com/stax76/mpv-scripts/blob/main/history.lua
[8]: https://github.com/igv/FSRCNN-TensorFlow/releases
