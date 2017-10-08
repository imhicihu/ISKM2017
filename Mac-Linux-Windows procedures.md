## Adobe Flash Player issues - Troubleshooting

### Mac OSX
* Verify that your Mozilla Firefox is updated.
* Verify that your Adobe Flash Player® is updated.
* Run Mozilla Firefox.
* Choose `Firefox` > `Tools` > `Add-ons`.
* Select `Plugins`.
* In the list of Add-ons, look for `Shockwave Flash` (another name for `Flash Player`) and check the _status_ that appears to the right of the plug-in name.
* Select `Always Activate`.
* Close the dialog box.
* Restart your Mozilla Firefox.

### LINUX
* Linux is not supporting Adobe Flash Player® in its store anymore. Therefore you have to do it manually.
* Open this link: `http://get.adobe.com/flashplayer/`. It will automatically suggest you a version according to your desktop environment-
* Select `.tar.gz` for Linux option
* Now click on `Download` button (Select the downloading path as Downloads in your system for easy access).
* Now extract file by right clicking on folder and selecting `Extract Here` option
* Open Terminal `CTRL+ALT+T` and copy below command one by one
* `cd ../`
* `cd name-of-your-pc` (ie: GeekLinux)
* `cd Downloads` (this is the folder where you have downloaded the file 
* `cd flash_player_npapi_linux.x86_64` (Your file name may be different just copy name of file and paste it in Terminal)
* `sudo mv libflashplayer.so \/usr/lib/firefox-addons/plugins` then press Enter
* Now close your Mozilla Firefox and Terminal
* Open Mozilla Firefox. Verify on this link: `http://get.adobe.com/flashplayer/about/` your Adobe Flash Player's version and correct installation.

### Windows
* Verify that your Mozilla Firefox is updated.
* Verify that your Adobe Flash Player® is updated.
* Run Mozilla Firefox.
* Choose `Firefox` > `Tools` > `Add-ons`.
* Select `Plugins`.
* In the list of Add-ons, look for `Shockwave Flash` (another name for `Flash Player`) and check the _status_ that appears to the right of the plug-in name.
* Select `Always Activate`.
* Close the dialog box.
* Restart your Mozilla Firefox.

#### Legal:
All other trademarks are the property of their respective owners.
Adobe, Flash, and Flash Player are either registered trademarks or trademarks of Adobe Systems Incorporated in the United States and/or other countries.