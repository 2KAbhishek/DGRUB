# DGRUB - Dark Grand Reunified Boot-Loader

![Size](https://img.shields.io/github/repo-size/2kabhishek/DGRUB?style=plastic&color=green&label=Size)
![Updated](https://img.shields.io/github/last-commit/2kabhishek/DGRUB?style=plastic&color=red&label=Updated)
![License](https://img.shields.io/github/license/2kabhishek/DGRUB?style=plastic&color=lightgrey&label=License)
![Stars](https://img.shields.io/github/stars/2kabhishek/DGRUB?style=plastic&color=ffd500&label=Stars)
![Forks](https://img.shields.io/github/forks/2kabhishek/DGRUB?style=plastic&color=brightgreen&label=Forks)
![Watchers](https://img.shields.io/github/watchers/2kabhishek/DGRUB?style=plastic&color=orange&label=Watchers)
![Contributors](https://img.shields.io/github/contributors/2kabhishek/DGRUB?style=plastic&color=ff69b4&label=Contributors)
![Followers](https://img.shields.io/github/followers/2kabhishek?style=plastic&color=blue&label=Followers)

DGRUB is a clean and minimal dark theme for GRUB.

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
