

Osmium Themes is a Mac OSX like theme for GTK 3, GTK 2 and Gnome-Shell which supports GTK 3 and GTK 2 based desktop environments like Gnome, Pantheon, XFCE, Mate, etc.

This theme is based on Arc gtk theme of horst3180. Thanks horst3180 sincerely for his great job! 
horst3180 - Arc gtk theme: https://github.com/horst3180/Arc-theme

## Info

### GTK+ 3.20 or later

### GTK2 engines requirment
- GTK2 engine Murrine 0.98.1.1 or later.
- GTK2 pixbuf engine or the gtk(2)-engines package.

Fedora/RedHat distros:

    yum install gtk-murrine-engine gtk2-engines

Ubuntu/Mint/Debian distros:

    sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf

ArchLinux:

    pacman -S gtk-engine-murrine gtk-engines

Other:
Search for the engines in your distributions repository or install the engines from source.

## Installation

### From source

Run

    ./install.sh

#### Install tips

Usage:  `./Install`  **[OPTIONS...]**

|  OPTIONS:           | |
|:--------------------|:-------------|
|-d,  --dest           | Specify theme destination directory (Default: $HOME/.themes)|
|-n,  --name           | Specify theme name (Default: Osmium)|
|-c,  --color          | Specify theme color variant(s) **[light/dark]** (Default: All variants)|
|-o,  --opacity        | Specify theme opacity variant(s) **[standard/solid]** (Default: All variants)|
|-f,  --flat           | Specify theme flat variant(s) **[standard/compact]** (Default: All variants)|
|-t,  --thin           | Specify theme titlebutton variant(s) **[standard/thin]** (Default: All variants)|
|-na, --noapple        | Specify gnome-shell to not display apple logo (Default: Display apple logo)|
|-g,  --gdm            | Install GDM theme|
|-h,  --help           | Show this help|


