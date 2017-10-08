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

### Linux
* Linux is not supporting Adobe Flash Player® in its store anymore. Therefore you have to install it manually.
* Open this link: `http://get.adobe.com/flashplayer/`. It will automatically suggest you a version according to your desktop environment.
* Select `.tar.gz` for Linux option
* Now click on `Download` button. _Tip:_ select the downloading path the usual `Downloads` folder for easy access.
* Now select the downloaded file, right clicking on it and select `Extract Here` option
* Open Terminal `CTRL+ALT+T` and copy the following commands one by one:
* `cd ../`
* `cd name-of-your-pc` (ie: GeekLinux)
* `cd Downloads` (this is the folder where you have downloaded the `.tar.gz`)
* `cd flash_player_npapi_linux.x86_64` (Your file name may be different, just copy the name of file and paste it in Terminal)
* `sudo mv libflashplayer.so \/usr/lib/firefox-addons/plugins` then press `Enter`.
* Now close your Mozilla Firefox and Terminal.
* Open Mozilla Firefox. 
* Visit this link: `http://get.adobe.com/flashplayer/about/`: it will show you your Adobe Flash Player®'s version and suitable installation.

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