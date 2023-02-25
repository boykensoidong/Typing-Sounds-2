<div align="center">

# Typing-Sounds

[![LOGO](https://github.com/boykensoidong/Typing-Sounds/blob/main/icon(typing-sound-2).png?raw=true)](https://marketplace.visualstudio.com/items/MTuan.night-eyes-theme)


Start typing with awesome typewriter sounds

[![Visual Studio Marketplace](https://img.shields.io/vscode-marketplace/v/mtuan.typing-sounds.svg)](https://marketplace.visualstudio.com/items?itemName=mattogodoy.hacker-sounds)
[![Visual Studio Marketplace](https://img.shields.io/vscode-marketplace/d/mtuan.typing-sounds.svg)](https://marketplace.visualstudio.com/items?itemName=mattogodoy.hacker-sounds)
[![Visual Studio Marketplace](https://img.shields.io/vscode-marketplace/r/mtuan.typing-sounds.svg)](https://marketplace.visualstudio.com/items?itemName=mattogodoy.hacker-sounds)
[![GitHub Repo](https://img.shields.io/badge/GitHub%20Repo-%20-fff.svg?logo=GitHub&style=social)](https://github.com/boykensoidong/Typing-Sounds)

_this extension is a **clone** of [Hacker Sounds](https://marketplace.visualstudio.com/items?itemName=mattogodoy.hacker-sounds) in Marketplace, sounds are taken from **Fallout Sounds** and **Keyboard Sounds**_

## 🔊🎵
### For the best experience this extension should be accompanied with [Power Mode](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode)

</div>

<div align="center">

### these following keys will have effect sound while pressing:
```
TAB🔉
SPACE🔉
ENTER🔉
DELETE🔉
CUT(ctrl+x)🔉
ARROW(up-down-left-right)🔉
```
## How to use
</div>

## Volume control

You can adjust the volume of the sounds by executing these commands in the Command Palette (Cmd+Shift+P) or press F1 key:

<div align="center">

**_chỉnh to nhỏ âm lượng gõ lệnh sau:_**
</div>


- `Typing Sounds: Volume Up`   🔉🔊
- `Typing Sounds: Volume Down`  🔈

**NOTE:** The volume adjustments only apply to this extension's sounds. It does not affect the system volume.

## Enable / Disable 
- Restart visual studio code after Enable/Disable

Typing Sounds will start immediately when Visual Studio Code is started. However, you can enable and disable the extension by executing these commands in the Command Palette (Cmd+Shift+P) or press F1 key:

- `Typing Sounds: Enable` 🔔
- `Typing Sounds: Disable` 🔕

## Changing Your custom sounds you would like to hear! find the extension folder: 
First: turn on show hidden files on your computer:

on MacOs: Press: ("COMMAND" + "SHIFT" + "." )

on windows: please search on google 

Second: you need to copy the audio as same format & name files to VS Code extensions folder
```
 .vscode/extensions/
 .vscode/extensions/mtuan.typing-sounds/audio (paste here)
 ```
Depending on your platform, it is located in the following folders:

```
Windows %USERPROFILE%\.vscode\extensions\mtuan.typing-sounds-
macOS ~/.vscode/extensions/mtuan.typing-sounds-
Linux ~/.vscode/extensions/mtuan.typing-sounds-
```
![Getting Started](https://github.com/boykensoidong/Typing-Sounds/blob/main/how%20to%20change%20audio%20file.png?raw=true)

<div align="left">

## Requirements

### Windows and Mac

Support for Windows and Mac, No special requirements.

### For Linux Users

On Linux, you will need to have mplayer installed and on your PATH to get this extension working.

**Debian based**
```bash
sudo apt-get install mplayer
```

**Red Hat based**
```bash
sudo dnf install mplayer
```

**Arch based**
```bash
sudo pacman -S mplayer
```

## Credits

For Windows, this extension uses the `sounder` light-weight player:
https://www.elifulkerson.com/projects/commandline-wav-player.php

## Known Issues & Bugs

### 1.4.3

- Fixed bug in which manually setting the volume went always to minimum or maximum.
- Redacted some of the messages.

### 1.4.0

- Now you can type the volume level directly using the `Typing Sounds: Set Volume` command.

### 1.3.0

- Now you can adjust volume levels for Mac, Windows and Linux. This feature has not been tested in Linux yet.
- Replaced [sWavPlayer](https://www.dcmembers.com/skwire/download/swavplayer/) for [sounder](https://www.elifulkerson.com/projects/commandline-wav-player.php) as the Windows sound player with the following benefits:
  - Much smaller in size (sounder is 33 KB and sWavPlayer was 878 KB)
  - Performance in Windows is greatly improved
  - Allows to set the volume
- Updated dependencies
-----------------------------------------------------------------------------------------------------------

</div>
