## Adobe Flash Player issues - Troubleshooting

### Mac OSX operating system (*)
* Verify that your Mozilla Firefox is updated.
* Verify that your Adobe Flash Player® is updated.
* Run Mozilla Firefox.
* Choose `Firefox` > `Tools` > `Add-ons`.
* Select `Plugins`.
* In the list of Add-ons, look for `Shockwave Flash` (another name for `Flash Player`) and check the _status_ that appears to the right of the plug-in name.
* Select `Always Activate`.
* Close the dialog box.
* Restart your Mozilla Firefox.

### Linux operating system (**)
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
* Now close your Mozilla Firefox and Terminal.
* Open Mozilla Firefox. 
* Visit this link: `http://get.adobe.com/flashplayer/about/`: it will show you your Adobe Flash Player®'s version and suitable installation.

### Windows operating system (***)
* Verify that your Mozilla Firefox is updated.
* Verify that your Adobe Flash Player® is updated.
* Run Mozilla Firefox.
* Choose `Firefox` > `Tools` > `Add-ons`.
* Select `Plugins`.
* In the list of Add-ons, look for `Shockwave Flash` (another name for `Flash Player`) and check the _status_ that appears to the right of the plug-in name.
* Select `Always Activate`.
* Close the dialog box.
* Restart your Mozilla Firefox.

(*) Tested on: Snow Leopard, Lion, Mountain Lion, Mavericks, ElCapitan, 
(**) Tested on: Lubuntu 16.04.3 (64 bits)
(***) Tested on: Windows 7, 8, 10 (32 & 64 bits)
#### Legal:
* All other trademarks are the property of their respective owners.
* Adobe, Flash, and Flash Player are either registered trademarks or trademarks of Adobe Systems Incorporated in the United States and/or other countries.