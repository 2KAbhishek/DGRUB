<div align = "center">

<h1><a href="https://2kabhishek.github.io/DGRUB">BareMinimum</a></h1>

<a href="https://github.com/2KAbhishek/DGRUB/blob/main/LICENSE">
<img alt="License" src="https://img.shields.io/github/license/2kabhishek/DGRUB?style=flat&color=eee&label="> </a>

<a href="https://github.com/2KAbhishek/DGRUB/graphs/contributors">
<img alt="People" src="https://img.shields.io/github/contributors/2kabhishek/DGRUB?style=flat&color=ffaaf2&label=People"> </a>

<a href="https://github.com/2KAbhishek/DGRUB/stargazers">
<img alt="Stars" src="https://img.shields.io/github/stars/2kabhishek/DGRUB?style=flat&color=98c379&label=Stars"></a>

<a href="https://github.com/2KAbhishek/DGRUB/network/members">
<img alt="Forks" src="https://img.shields.io/github/forks/2kabhishek/DGRUB?style=flat&color=66a8e0&label=Forks"> </a>

<a href="https://github.com/2KAbhishek/DGRUB/watchers">
<img alt="Watches" src="https://img.shields.io/github/watchers/2kabhishek/DGRUB?style=flat&color=f5d08b&label=Watches"> </a>

<a href="https://github.com/2KAbhishek/DGRUB/pulse">
<img alt="Last Updated" src="https://img.shields.io/github/last-commit/2kabhishek/DGRUB?style=flat&color=e06c75&label="> </a>

</div>

DGRUB (Dark Grand Reunified Boot-Loader) is a clean and minimal dark theme for GRUB.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of `grub`

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

> title-text = "username@hostname"

Feel free to play around with other options too.
