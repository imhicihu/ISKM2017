## Adobe Flash Player issues - Troubleshooting

### Mac OSX operating system
* System requeriments:
    - Intel Core™ Duo 1.83GHz or faster processor
    - Mac OS X v10.9, or later
    - Latest versions of Mozilla Firefox®.
    - 512MB of RAM; 128MB of graphics memory
* Tested on: Mavericks (version 10.9), El Capitan (version 10.11).
* Verify that your Mozilla Firefox® is updated.
* Verify that your Adobe Flash Player® is updated.
* Run Mozilla Firefox®.
* Choose `Firefox` > `Tools` > `Add-ons`.
* Select `Plugins`.
* In the list of Add-ons, look for `Shockwave Flash` (another name for `Flash Player`) and check the _status_ that appears to the right of the plug-in name.
* Select `Always Activate`.
* Close the dialog box.
* Restart your Mozilla Firefox®.
* Run the official [Adobe Connect test page](http://admin.adobeconnect.com/common/help/en/support/meeting_test.htm).

### Linux operating system
* System requeriments:
    - 2.33GHz or faster x86-compatible processor, or Intel Atom 1.6GHz or faster processor for netbooks.
    - Latest versions of Mozilla Firefox.
    - 512MB of RAM; 128MB of graphics memory.
* Tested on: Lubuntu 16.04.3 (64 bits)
* Linux is not supporting Adobe Flash Player® in its store anymore. Therefore you have to install it manually.
* Open this link: `http://get.adobe.com/flashplayer/`. It will automatically suggest you a version according to your operating system ecosystem.
* Select `.tar.gz for Linux` option.
* Now click on `Download` button. _Tip:_ select the downloading path (the default `Downloads` folder) for easy access.
* Now select the downloaded file, right click on it and select `Extract Here` option.
* Open Terminal (`CTRL+ALT+T`) and write the following commands one by one:
* `cd ../` then press `Enter` key.
* `cd name-of-your-pc` then press `Enter` key.
* `cd Downloads` (this is the folder where you have downloaded the `.tar.gz`) then press `Enter` key.
* `cd flash_player_npapi_linux.x86_64` (Your file name may be different, just copy the name of file and paste it in Terminal)
* `sudo mv libflashplayer.so \/usr/lib/firefox-addons/plugins` then press `Enter` key.
* Now close your Mozilla Firefox® and Terminal.
* Open Mozilla Firefox®. 
* Visit this link: `http://get.adobe.com/flashplayer/about/`: it will show you your Adobe Flash Player®'s version and suitable installation.
* Run the official [Adobe Connect test page](http://admin.adobeconnect.com/common/help/en/support/meeting_test.htm).
* - ![2017-10-04-205229_1128x641_scrot.png](https://bitbucket.org/repo/bBMkd4/images/1580105962-2017-10-04-205229_1128x641_scrot.png)

### Windows operating system
* System requeriments:
     - 2.33GHz or faster x86-compatible processor, or Intel® Atom™ 1.6GHz or faster processor for netbooks.
     - Microsoft® Windows® XP SP3 (32-bit), Windows Vista® (32-bit), Windows 7 (32-64 bits), Windows 8.1 ((32-64 bits) and Windows 10 ((32-64 bits).
     - Latest versions of Mozilla Firefox.
     - 512MB of RAM (1GB of RAM recommended for netbooks); 128MB of graphics memory
* Tested on: Microsoft Windows® 7, 8, 10 (32 & 64 bits)
* Verify that your Mozilla Firefox® is updated.
* Verify that your Adobe Flash Player® is updated.
* Run Mozilla Firefox®.
* Choose `Firefox` > `Tools` > `Add-ons`.
* Select `Plugins`.
* In the list of _Add-ons_, look for `Shockwave Flash` (another name for `Flash Player`) and check the _status_ that appears to the right of the plug-in name.
* Select `Always Activate`.
* Close the dialog box.
* Restart your Mozilla Firefox®.
* Run the official [Adobe Connect test page](http://admin.adobeconnect.com/common/help/en/support/meeting_test.htm).
* ![adobe_connect_pc.jpg](https://bitbucket.org/repo/bBMkd4/images/1926895762-adobe_connect_pc.jpg)
 
#### Legal:
* All other trademarks are the property of their respective owners.
* Adobe, Flash, and Flash Player are either registered trademarks or trademarks of Adobe Systems Incorporated in the United States and/or other countries.
* Windows is a registered trademark of Microsoft Corporation in the United States and/or other countries.
* Lubuntu is a trademark of Canonical.