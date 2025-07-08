Now Playing Info Plus
====

An applet for jivelite that modifies the *QVGAlandscape* skin and the *Now Playing* screen of your **SB Radio** to display additional information on the *Now Playing* screen (rating, year, audio metadata, status icons).

<br>

> [!IMPORTANT]
> Tested with SB Radio firmware **8.5**.x.<br>If you update to another firmware version, this applet might not work anymore.

<br>


[⬅️ **Back to the list of all plugins**](https://github.com/AF-1/)
<br><br><br>

## Features

- display the **track rating as rating stars** (both Now Playing views)

- display **additional information** on the *"small artwork"* Now Playing view:
	- **year**

	- **audio meta data** (content type, bitrate, sample rate/size)

	- **status icons**

		- <img src="QVGAlandscapeSkin/images/NowPlaying/hq_1.png" width="29px"> = is *lossless*
		- <img src="QVGAlandscapeSkin/images/NowPlaying/lyrics_1.png" width="23px"> = has *lyrics*
		- <img src="QVGAlandscapeSkin/images/NowPlaying/csst_1.png" width="23px"> = has a *custom start/stop time* that the [**CSST** plugin](https://github.com/AF-1/lms-customstartstoptimes#custom-start-stop-times) can use
		- <img src="QVGAlandscapeSkin/images/NowPlaying/remote_1.png" width="28px"> = is a *remote* track (replaced by streaming service icon if track is part of the LMS library)

- **easy way to install, update and uninstall** the applet using an **installer and uninstaller applet**<br>

- colored track title if the track's comments tag contains a user-specified keyword<br>

<br>

Settings are here: **Settings > Screen > Now Playing**.<br>
To check the currently installed version go to *Settings > Advanced > Uninstall Now Playing Info Plus*.
<br><br><br>

## Screenshots[^1]

<img src="screenshots/radio1.jpg" width="50%"><br><br>
<img src="screenshots/radio2.jpg" width="50%"><br><br>

<br><br><br>

## Installation

**First** you install the *installer* applet which you will **then** use to install the *Now Playing Info Plus* files.<br>

#### #1 - Get the installer

- Make sure that your LMS and your SB Radio have internet access.<br>

- Go to `Settings > Advanced > Applet Installer`.<br>

- Select and install the `Now Playing Info Plus Installer`.

- Your SB Radio will reboot automatically.<br><br>

#### #2 - Install the NP Info Plus files

- You should see a new menu item called `Now Playing Info Plus Installer` in the home menu.<br>

- Follow the menu instructions.

- Your SB Radio will reboot automatically to complete the installation.

<br><br><br>

## Updating to a newer version

#### #1 - Get the update

- Go to `Settings > Advanced > Applet Installer`.<br>

- Select and <ins>update</ins> the `Now Playing Info Plus Installer`.<br>

- Your SB Radio will reboot automatically.<br><br>

#### #2 - Update the NP Info Plus files

- You should see a new menu item called `Now Playing Info Plus Updater` in the home menu.<br>

- Follow the menu instructions.

- Your SB Radio will reboot automatically to complete the update.

<br><br><br>

## Uninstalling the applet and files

#### #1 - Remove Now Playing Info Plus Installer from the list of installed applets

- Go to `Settings > Advanced > Applet Installer`.<br>

- Select and <ins>remove</ins> the `Now Playing Info Plus Installer`.

- Your SB Radio will reboot automatically.<br><br>

#### #2 - Remove the applet

- Go to `Settings > Advanced > Uninstall Now Playing Info Plus` and follow the menu instructions.

- Your SB Radio will reboot automatically.<br><br>

<br><br><br><br>

## FAQ

<details><summary>»<b>I've used the <i>Applet Installer</i> to install/update the <i>Now Playing Info Plus Installer / Updater</i> but there's <i>no menu item</i> with this name.</b>«</summary><br><p>
Confirm that your SB Radio has (unlimited) <i>access to the internet</i>. The jivelite Applet Installer (<i>Settings > Advanced > Applet Installer</i>) gets the list of available applets from your (local) LMS server. Your SB Radio will then (try to) download the applet <b><i>directly</i></b> from the source (URL).
</p></details><br>

<details><summary>»<b>The Applet Installer doesn't show me the latest applet version.</b>«</summary><br><p>

- Go to <i>Settings -> Advanced -> Applet Installer</i> and confirm that <i>Recommended Applets Only</i> is <b>dis</b>abled.<br>

- Confirm that your server and SB Radio <b>both</b> have <b>internet access</b>.<br>

- If it's a <b>caching</b> problem, try this:<br>

    - reload the <i>LMS Settings -> Manage Plugins</i> page so the server has the latest list of available applets<br>

    - if you enter the <i>Settings -> Advanced -> Applet Installer</i> menu and it doesn't show the latest update, exit the menu and wait a couple of minutes before calling it again.
</p></details><br>

<details><summary>»<b>I can't open the <i>Screen > NowPlaying > NowPlaying Views</i> menu.</b>«</summary><br><p>
This is a jivelite quirk that's not tied to any skin in particular. Just <b>enter the Now Playing screen</b> using the top right note icon. Then go back and try again. That usually solves it. If not, make sure that you have selected a player and that this player is connected.
</p></details><br>

<details><summary>»<b>I have changed some skin settings. When I go to the Now Playing screen immediately afterwards, the Now Playing screen does not display the changes or the screen layout is wrong.</b>«</summary><br><p>
Sometimes you need to <i>switch to another Now Playing view</i> before the changes take effect.</p></details><br>



<br><br><br>

## Report a new issue

To report a new issue please file a GitHub [**issue report**](https://github.com/AF-1/jivelite-nowplayinginfoplus/issues/new/choose).<br><br>

If you'd like me to make small changes to the screen layout, please test the new changes on your SB Radio first and then create a pull request with the changes here.
<br><br><br>


## ⭐ Help others discover this project

If you find this project useful, giving it a <img src="screenshots/githubstar.png" width="20" height="20" alt="star" /> (top right of this page) is a great way to show your support and help others discover it. Thank you.
<br><br><br><br>

[^1]: The screenshots might not correspond to the current UI in every detail.