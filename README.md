# Theme made by Mefasque

## Installation
Using the `ganyu` theme as an example

1. Download & Unzip

2. Copy `ganyu` into grub themes directory
```shell
sudo cp -r ganyu /usr/share/grub/themes/
```

3. Edit `grub` file
```shell
sudo vim /etc/default/grub
```

4. Add the theme to the bottom of the text file
```shell
GRUB_THEME="/usr/share/grub/themes/ganyu/theme.txt"
```

5. Update grub
```shell
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

6. Reboot the computer

## Preview
![Castorice](/previews/ganyu.jpg)
