<h1 align="center">
  <br>xiv_triggernometry<br>
</h1>
<h4 align="center">Repository Information</h4>

<p align="center">
  <a href="https://na.finalfantasyxiv.com/dawntrail/patch_7_2"><img src="https://img.shields.io/badge/ffxiv-patch%207.2-yellow"></a>
  <a href="https://github.com/paissaheavyindustries/Triggernometry/releases/tag/v1.2.0.7"><img src="https://img.shields.io/badge/triggernometry-v1.2.0.7-blue"></a>
  <a href="https://github.com/OverlayPlugin/OverlayPlugin/releases/tag/v0.19.5"><img src="https://img.shields.io/badge/OverlayPlugin-v0.19.5+-green"></a>
</p>

***NOTE:*** *This repository uses triggers that rely on `OverlayPlugin` [log lines](https://github.com/OverlayPlugin/cactbot/blob/main/docs/LogGuide.md#overlayplugin-log-lines). You will need OverlayPlugin [v0.19.5](https://github.com/OverlayPlugin/OverlayPlugin/releases/tag/v0.19.5 "OverlayPlugin v0.19.5") or [later](https://github.com/OverlayPlugin/OverlayPlugin/releases "later") for them to work.*

## How to Setup

 1. Navigate to your Triggernometry plugin tab in ACT.
 2. Right-click on **Remote Triggers** and choose **Add** > **Repository** from the list.
 3. Name it whatever you want but put the following in the address:
 ```https://raw.githubusercontent.com/lexxiesia/xiv_triggernometry/master/Triggernometry_Lexxie.xml```
 4. Under the **Update and Permissions** section, make sure your settings are as follows:
![](https://raw.githubusercontent.com/lexxiesia/xiv_triggernometry/master/resources/screenshots/repo_setting.jpg)
 5. Click **Add** and you're done!
 
 If you don't see **Remote Triggers**, you are running an old version of Triggernometry. Download the latest update from Triggernometry's [GitHub page](https://github.com/paissaheavyindustries/Triggernometry/releases/latest "GitHub page").

## What's in it?
Triggers within the repository are separated by content folders and are further separated by expansion. Stuff are enabled by default. Disable triggers that you don't want activated. That is all!

If there are any problems or issues, hit me up on Discord.

### Commands
The following two commands are now persistent, as in, will be saved and loaded back when Triggernometry starts, removing the need for command re-input whenever you relaunch ACT. These will only work for *certain 6.0 content*\* and all 7.0 content onward. Only triggers that use sound files will be disabled. TTS triggers are not affected.
- **`/e soundOff`** Turns off all audio triggers.
- **`/e soundOn`** Turns on all audio triggers.
> Supported 6.0: *Alliance (Thaleia), Raids (Anabaseios: 9th, 10th, 11th, 12th Circles), Trials (Golbez, Zeromus)*