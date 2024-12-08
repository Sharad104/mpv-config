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


### Scripts I Use :
- [ModernX][1]: Modern-looking interface for on-screen controls.
- [ModernZ][2]: A fork of ModernX with a focus on customization (currently in use).
- [mpv-webm][3]: Create simple WebM clips.
- [thumbfast.lua][4]: Lightweight thumbnail generator script compatible with ModernX/ModernZ.
- [history.lua][5]: Stores the history of played files in `history.txt` at the MPV config folder.
- [FSRCNNX shader][6]: Upscales lower-resolution videos to higher-resolution using a Fast Super-Resolution Convolutional Neural Network.

[1]: https://github.com/cyl0/ModernX
[2]: https://github.com/Samillion/ModernZ
[3]: https://github.com/ekisu/mpv-webm
[4]: https://github.com/po5/thumbfast
[5]: https://github.com/stax76/mpv-scripts/blob/main/history.lua
[6]: https://github.com/igv/FSRCNN-TensorFlow/releases
