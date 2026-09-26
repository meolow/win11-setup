<div align="center">

# 🩵 My Windows 11 Setup 🩵

![Status](https://img.shields.io/badge/Status-Work_In_Progress-yellow?style=for-the-badge)
![OS](https://img.shields.io/badge/OS-Windows_11-0078D4?style=for-the-badge&logo=windows11&logoColor=white)

</div>

# 📷 Screenshot
![Screenshot of my desktop](https://camo.githubusercontent.com/1d2c30378b381612e6630f16afa14ed59d7204a283f74fb9e1515ea52d8abfa4/68747470733a2f2f692e696d6775722e67672f695843336143532d323032362d30392d32355f31372d30312e706e67)


# 📃 Content
| ✨ Entry | 📚 App |
|---------------------|------------|
| Browser | [Firefox](#-firefox) |
| File Explorer Mod | [ExplorerBlurMica](#-explorerblurmica) |
| System Fetch | [Fastfetch](#-fastfetch) |
| Audio Visualizer | [Cava](#-cava) |
| Music Player | [YouTube Music](#-youtube-music) |
| Screen Recording | [OBS Studio](#-obs-studio) |
| Terminal | [Windows Terminal](#-windows-terminal) |
| Minecraft Launcher | [Modrinth App](#-modrinth-app) |
| VPN | [ProtonVPN](#-protonvpn) |
| Screenshot Tool | [Flameshot](#-flameshot) |
| Game Clipping | [Medal](#-medal) |
| Wallpaper | [Wallpaper Engine](#-wallpaper-engine) |
| Taskbar Media Widget | [FluentFlyout](#-fluentflyout) |
| Terminal Auto Complete | [PSReadLine](#-psreadline) |
| Transparent Taskbar | [TranslucentTB](#-translucenttb)

Browser Extensions
| ✨ Entry | 🌟 Function |
|---------------------|------------|
| uBlock Origin | Blocks ads |
| Firefox Color | Firefox theme maker |
| Stop Mod Reposts | Blocks websites that steal minecraft mods |
| Bitwarden | Free password manager |

# 🔥 Details

## 🦊 Firefox
**⚙️ Installation:**  
You can follow the steps below:
- Download it from [mozilla.org/firefox](https://mozilla.org/firefox) or via terminal `winget install Mozilla.Firefox`

## 📁 ExplorerBlurMica
**⚙️ Installation:**  
You can follow the steps below:
- Get it from [github.com/Maplespe/ExplorerBlurMica/releases/](https://github.com/Maplespe/ExplorerBlurMica/releases/)
- Download and extract the `.zip`
- Run `register.cmd`
  
## ⚡ Fastfetch
**⚙️ Installation:**  
You can follow the steps below:
- Run `winget install fastfetch` in your terminal
- Press Win + R and type `%USERPROFILE%` and press enter
- Create a folder called `.config`
- Right click the folder and click on `Show more options` and then on `Properties`
- Check `Hidden`
- Click on `Apply` and `OK`
- If you can't see it: Go to `View` at the top, hover over `Show` and check `Hidden Items`
- Now go into the `.config` folder you made
- Create a folder called `fastfetch`
- Download the `config.jsonc` and `ascii.txt` from this repo [here](./fastfetch)
- Paste them into the `fastfetch` folder

If you want to replace the ASCII art make sure to keep the $2-$9 in the `ascii.txt` file but you can get ASCII art from [here!](https://emojicombos.com)

## 🎵 Cava
**⚙️ Installation:**  
You can follow the steps below:
- Install via terminal `winget install cava`
- To run it just type `cava` in your terminal

## 🎧 YouTube Music
**⚙️ Installation:**  
You can follow the steps below:
- Access it at [music.youtube.com](https://music.youtube.com)

## 🎥 OBS Studio
**⚙️ Installation:**  
You can follow the steps below:
- Run `winget install OBSProject.OBSStudio` or download from [obsproject.com](https://obsproject.com)

## 🎮 Modrinth App
**⚙️ Installation:**  
You can follow the steps below:
- Download from [modrinth.com/app](https://modrinth.com/app) or run `winget install Modrinth.ModrinthApp`

## 🔒 ProtonVPN
**⚙️ Installation:**  
You can follow the steps below:
- Download from [protonvpn.com](https://protonvpn.com) or run `winget install ProtonTechnologies.ProtonVPN`

## 📸 Flameshot
**⚙️ Installation:**  
You can follow the steps below:
- Download from [flameshot.org](https://flameshot.org) or run `winget install FlameShot.FlameShot`

## 🎬 Medal
**⚙️ Installation:**  
You can follow the steps below:
- Download from [medal.tv](https://medal.tv)

## 🖼️ Wallpaper Engine
**⚙️ Installation:**  
You can follow the steps below:
- Buy it from Steam for 4,99€
- Open it, go to the workshop tab and search for "【Furry】落霞归途" (made by 爱摸鱼的卢皮卡)

## 🌸 FluentFlyout
> [!WARNING]
> Downloading it from the Microsoft Store or Winget will require Premium for some features so this is the recommended method

**⚙️ Installation:**  
You can follow the steps below:
- Go to [fluentflyout.com/files/latest/x64](https://fluentflyout.com/files/latest/x64)
- A ZIP will start downloading
- Once finished, open explorer and extract it
- Open the `FluentFlyout_X.XX.X_x64_Installer` folder, then open `SystemFiles`
- Double click on the `FluentFlyoutMSIX_X.XX.X.X_x64_GitHub Release.cer` file then click on `Open`, after that click on `Install Certificate...`
- Choose `Local Machine`, click on next and choose `Place all certificates in the following store`
- Click on `Browse...` and select the option `Trusted Root Certification Authorities` and press `OK`, then `Next` and then just keep pressing `Next`, `Finish` or `OK` for whatever it asks
- Now double click `FluentFlyoutMSIX_X.XX.X.X_x64_GitHub Release.msixbundle` and install it

**🔱 Config:**
- Go to the `Media Flyout` Tab and set background blur to `Style 3 (Blur)` but do NOT enable `Enable Media Flyout`
- Enable `Volume Flyout`, `Taskbar Widget`, `Taskbar Visualizer`, `Next Up Flyout` and `Lock Keys Flyout`

## 💬 PSReadLine
**⚙️ Installation:**  
You can follow the steps below:
- Open your terminal as administrator
- Paste this command `Install-Module -Name PSReadLine -AllowClobber -Force`


## 🖥️ TranslucentTB
**⚙️ Installation:**  
You can follow the steps below:
- Download it from the [Microsoft Store](https://apps.microsoft.com/detail/9pf4kz2vn4w9)

**🔱 Config:**
- Set everything to `Clear` and disable `Show taskbar border`
- Set `Maximized window` to `Acrylic`
