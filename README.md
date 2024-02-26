# i3/Linux Config Files

My config files for various aspects of my set up with polybar on Manjaro Linux.

Since its my first rice I'd appreciate any adds and advice, Thanks!

***

## The Theme
![Theme](/theme.png)
![Theme](/screenshot2.png)

***

## How to install
### 1. install the needed packages
we will only need rofi and polybar here and you can install with your favorite package manager.

if you're using arch on any arch-based distro you can use the following commands on your terminal

```
sudo pacman -S polybar
```

```
sudo pacman -S rofi
```

and for sure you will need to install i3, you can install by using this command

```
sudo pacman -S i3wm
```


### 2. clone the repo

you can clone this repository by using this command

```
git clone https://github.com/ImComy/i3wm-configuration-files.git
```

### 3. fonts

go to ~
and create a new directory there and name it ` .fonts `
copy and paste all the file in the repo to the fonts directory you just made


### 5. configuration files

go to ~/.config
and you will find a directory for all of i3, neofect, polybar and rofi
copy and paste all the files in the repo to its appropriate place

### 6. changing the wallpaper

in i3 configuration file you will find the feh command
you can always change the path to whatever wallpaper you want
