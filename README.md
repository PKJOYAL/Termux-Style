<!-- Links -->
[paypal]:  https://paypal.me/prashantkumarkccpl?country.x=IN&locale.x=en_GB

**`LAST Updated`** : `November 2023`

> Unmaintained : Due to Termux not working properly on new Android versions and also Termux not getting maintained properly.

---

# Termux Style

<p align="left">
  <img src="https://img.shields.io/badge/Maintained%3F-No-red?style=for-the-badge">
  <img src="https://img.shields.io/github/license/adi1090x/termux-style?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/adi1090x/termux-style?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/adi1090x/termux-style?color=teal&style=for-the-badge">
  <img src="https://img.shields.io/github/issues/adi1090x/termux-style?color=violet&style=for-the-badge">
</p>

Simple script to change color-schemes and fonts for [Termux](https://termux.com) terminal emulator.

![gif](images/main.gif) <br />

> **`termux-style` provides color-schemes and powerline-ready fonts to customize the appearance of the Termux terminal.**

### How to install

Follow the steps below - 

```bash
# Go to home dir - 
cd $HOME

# Clone this repository (use `gh repo clone prashantkumarjoyal/termux-style` if you want to use the GitHub CLI)- 
git clone https://github.com/prashantkumarjoyal/Termux-Style.git

# Change to termux-style dir -
cd termux-style

# To install it, run -
./install

# And follow the steps, it'll be installed on your system.
```

### Run

Run `termux-style` & select the right option -

```bash
$ termux-style

    ┌──────────────────────────────────────────────────┐
    │░▀█▀░█▀▀░█▀▄░█▄█░█░█░█░█░░░░░█▀▀░▀█▀░█░█░█░░░█▀▀░░│
    │░░█░░█▀▀░█▀▄░█░█░█░█░▄▀▄░▄▄▄░▀▀█░░█░░░█░░█░░░█▀▀░░│
    │░░▀░░▀▀▀░▀░▀░▀░▀░▀▀▀░▀░▀░░░░░▀▀▀░░▀░░░▀░░▀▀▀░▀▀▀░░│
    └──────────────────────────────────────────────────┘
    [*] By- JOYAL Group // PKJoyal

    [C] Colors (89)
    [F] Fonts (20)
    [R] Random
    [I] Import
    [A] About
    [Q] Quit
    
    [Select Option]: 
```

### Features

+ 90 popular color-schemes.
+ 20 powerline patched fonts.
+ Randomly change color-schemes.
+ Import color-schemes from *local file* or *file URL*.
+ Set colors and fonts in place.

### Use Import
```bash
    [Select Option]: 4

    [1] Local File (Enter path to file)
    [2] Internet File (Enter File URL)

    [Select Option]: 2

    [Enter Color-scheme URL]: https://github.com/prashantkumarjoyal/Termux-Style.git

    [*] Reloading Settings...
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (e.g. - `/data/data/com.termux/files/home/spiderman.properties`) of the color-scheme.
+ To import *web file*, enter the file url (e.g. - `https://github.com/prashantkumarjoyal/Termux-Style.git`) of the color-scheme.
<br />

### Previews

|Colorschemes|Fonts|
|--|--|
|![img](images/colors.gif)|![img](images/fonts.gif)|

|Import - URL|Import - Local|
|--|--|
|![img](images/url.gif)|![img](images/local.gif)|

|Install|Uninstall|
|--|--|
|![img](images/install.gif)|![img](images/uninstall.png)|

### FYI
- An `uninstall` script is also added, in case you want to remove this program.
- Again... If you can improve it, sure...
- Have fun!
