


> git clone https://github.com/santatic/grub-themes.git

> sudo rm -rf /boot/grub/themes/SteamROG

> sudo cp -R grub-themes/SteamROG /boot/grub/themes

Edit `/etc/default/grub`, set:

`GRUB_THEME="/boot/grub/themes/SteamROG/themetemplate.txt"`

> sudo grub-mkconfig -o /boot/grub/grub.cfg
