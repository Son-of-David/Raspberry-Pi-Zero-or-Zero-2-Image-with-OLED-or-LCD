# Raspberry Pi Zero or Zero 2 Image with Optional OLED or LCD Availability Built In

This work is a compilation of many authors and artists of technology. I would like to personally thank and recognize these people and their works, for this image would not be possible without their help and generousity. First and foremost Kali and RoganDawes for the P4wnP1 operating system. I would next like to thank LuemmelSec for converting the image to the Zero 2. Then beboxos for the base script of gui.py and NightRang3r for the HIDscripts and the editing of python scripts to make the GUI work straight from the launch. I'm grateful for such grace, respect, and generousity because these people have donated their time and resources to help us with the gifts that they have blessed us with. Please if you are able to help people with your knowledge and growth do the same. Thats why I made this image even though the foundation of everything was there. I want people to heal grow and learn like I have working on this project. I hope you are able to advance us all with your work. - Son of David

here are links to their pages please give them all stars

https://github.com/RoganDawes/P4wnP1_aloa

https://github.com/LuemmelSec/P4wnP1_aloa

https://github.com/beboxos/P4wnP1_ALOA_OLED_MENU_V2

https://github.com/NightRang3r/P4wnP1-A.L.O.A.-Payloads

If you could give me a star too that would be appreciated I put in a lot of hours on this. Especially if you use this image.

SSH username: root and password: toor if you need help with the system look at https://github.com/RoganDawes/P4wnP1_aloa

The Waveshare 1.3inch OLED top hat with the SH1106 drive will work instantly with the image I provided the LCD will require you to delete the BeBoXGui folder and reinstall by running the install.sh in the LCD folder.

The link to my personal server where this is hosted for direct download and sha256 verification is https://torchurch.us

I made a website, paid to get DNS, and even got https encryption for this project to be able to share this.

GitHub has a size limit of 2GB for files and I didn't want to break it up then have people reassemble it. Also large files on GitHub can download slow.

To use the whole storage area of the card cd / then type raspi-config --expand-rootfs

To create a FAT32 Storage bin that can be mounted independently run /usr/local/P4wnP1/helper/genimg -i -s 1000 -o file_name_on_P4wnP1 -l drive_label

To be able to mount the new drive go to USB settings on web app and select your newly created bin in the Mass Storage section and save it then deploy it.

Use at least a 16GB card and for the best experience use a card with A2 V30 ratings. I use a 512GB card in my Zero 2 for the large storage capabilities.

The default image to be shown at start up is bootdavidsstone.bmp there are instructions on how to change it in CHANGEIMAGE.md which can be viewed by typing cat or nano.
