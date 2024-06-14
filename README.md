![MPV logo](https://en.wikipedia.org/wiki/Mpv_(media_player)#/media/File:Mpv_logo_(official).png)

mpv is a no-nonsense, super-fast, minimal, efficient, lightweight, highly customizable player.

### To install on Windows:

1. Download the latest version from [here](https://sourceforge.net/projects/mpv-player-windows/files/ "sourceforge link").
2. Extract the zip file.
3. Place the extracted folder in your C drive.
4. Add the mpv.exe path to the environment variables (system variables path).
5. Run `mpv_install.bat` as ADMIN under the installer folder to assign all video file extensions to mpv.


### To install on Ubuntu/Linux :
1. Open terminal and execute these commands one by one
2. `sudo add-apt-repository ppa:mc3man/mpv-tests` 
3. `sudo apt update`
4. `sudo apt install mpv`


### Configuration :

mpv configuration files are stored in `C:\Users\USERNAME\AppData\Roaming\mpv\` on windows and `~/.config/mpv/` on linux . If this mpv folder doesn’t exist, create one.

This folder generally stores mpv.conf file and input.conf file. The mpv folder contains subfolders named "scripts" and "script-opts" which store scripts and script settings/options.


### scripts included : 
- `chapterskip.lua`: Automatically skips chapters Based on title like OP/Opening ED/Ending in Anime.
- `modernx.lua`: modern-looking interface for ON SCREEN CONTROLLS.
- `mpv_chapters.js`: Display chapters using 'Tab' key and select using mouse click.
- `playlistmanager`.lua: This script allows you to see and interact with your playlist in an easy way using 'F2' key.
- `webm.lua`: Make simple WebM clips using 'F1' key.
