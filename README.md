# lxqt_labwc_config
Custom labwc config for lxqt desktop with some COSMIC DE shortcuts

## Work in progress ##

FEATURES

- COSMIC DE shortcuts: Super+B for browser (Falkon) , Super+F for Lxqt file manager, Super+T for Lxqt Terminal and Print for Screengrab
- Configuring other keys is on the rc.xml file as per the labwc documentation. Refer the labwc for details
- Switching desktop keys are commented until I find how to fix them.
- Keyboard Layout is located in environment file as per the labwc documentation.
- Default keyboard layout is us and ca (multix) which ca CSA standard. Shortcut is Super + Space
- Default Theme (Nightmare) is not included in those files. I want in a future project to include my own theme eventually.
- You can use any Openbox or labwc theme and put them in a ~/.themes directory. The labwc documentation provides alternatives where to put those themes.
- Is it to note that some Openbox themes features will simply not work with labwc such as horizontal gradient. R.I.P. Pelangi

  HOW TO INSTALL

  Create a ~/.config/labwc directory and put the files here
  Remember that you need to download the lxqt-wayland-session with labwc to be able to select the wayland session and choose labwc as the compositor. Reboot or use the labwc --reconfigure command in the terminal afterwards.
  Have fun! You should have an lxqt Wayland session that use only 950Mb idle RAM on average if you use SystemD as the bootloader.
