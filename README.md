# hyperpixel-hdmi-autoswitch
Automatic switching between the Pimoroni Hyperpixel and on board HDMI
***  YOU SHOULD BACK UP YOUR /boot/config.txt BEFORE USING THIS  ***

Make a backup copy of your current /etc/rc.local and replace it with the one here.

Make a backup copy of your /boot/config.txt and put both the hyper and hdmi versions here into your /boot folder.
When the screen type is auto-detected, the correct one will automatically be copied to /boot/config.txt

Copy any custom settings in your current /boot/config.txt over to the two alternate config files (except any hyperpixel settings).


BTW - to give credit where it is due (I think, I got this so long ago I'm not absolutely sure where) look at the thread here:  https://forums.pimoroni.com/t/hyperpixel-selective-output-eg-on-boot/5193
