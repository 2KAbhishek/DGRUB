<div align="center">

# DGRUB

![Size](https://img.shields.io/github/repo-size/2kabhishek/DGRUB?style=plastic&color=0f0&label=Size)
![Updated](https://img.shields.io/github/last-commit/2kabhishek/DGRUB?style=plastic&color=f00&label=Updated)
![Stars](https://img.shields.io/github/stars/2kabhishek/DGRUB?style=plastic&color=ffc801&label=Stars)
![Forks](https://img.shields.io/github/forks/2kabhishek/DGRUB?style=plastic&color=003cff&label=Forks)
![Watchers](https://img.shields.io/github/watchers/2kabhishek/DGRUB?style=plastic&color=ff5500&label=Watchers)
![Contributors](https://img.shields.io/github/contributors/2kabhishek/DGRUB?style=plastic&color=f0f&label=Contributors)
![License](https://img.shields.io/github/license/2kabhishek/DGRUB?style=plastic&color=555&label=License)

DGRUB (Dark Grand Reunified Boot-Loader) is a clean and minimal dark theme for GRUB.

</div>

## Prerequisites

Before you begin, ensure you have met the following requirements:

* You have installed the latest version of `grub`

## Installing DGRUB

To install DGRUB, follow these steps:

```bash
git clone https://github.com/2kabhishek/DGRUB
cd DGRUB
sudo cp -r dgrub /usr/share/grub/themes
```

Set grub theme in `/etc/default/grub`.

```bash
GRUB_THEME="/usr/share/grub/themes/dgrub/themes.txt"
```

## Customizing

Edit `dgrub/theme.txt` file.

>title-text = "username@hostname"

Feel free to play around with other options too.

Please consider hitting the ⭐ star button if this repo was useful to you, any contributions and suggestions are welcome.

