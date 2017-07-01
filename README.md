# MIDI Velocity Viewer (JS script for Reaper)

This JS script for Reaper displays MIDI velocity levels with minimum and maximum values.

## Screenshot
![Screenshot](https://raw.githubusercontent.com/Erriez/erriez-reaper-jsfx/master/screenshots/midi_velocity_viewer_01.png)

## Requirements
- All Reaper versions 4.60+ and 5.0+.

## Installation
- Copy the ```midi_velocity_viewer``` JS script to: 
  * Windows 7/8/10: ```C:\Users\<username>\AppData\Roaming\REAPER\Effects\MIDI\```
  * Mac OS X: ```/Users/<username>/Library/Application Support/REAPER/Effects/MIDI/```

## Add FX to a track
1. Start Reaper
2. Click on the FX button on a (MIDI) track
3. Browse to this file: JS: MIDI\midi_velocity_viewer

## Usage
* Select the MIDI input channel 1-16 or Any
* Select the MIDI input note 0-127 or Any
* Select the number of velocities with the third slider 1-32
  
- Left mouse click to hide/show the minimum/maximum velocities
- Right mouse click to reset

### Customize font
Edit the following variables in the script to change font and font size:
* ```custom_font``` Enable custom font 
* ```font_type``` Font type
* ```font_size``` Font size
* ```font_flags``` Bold, italic and or underline

## Help
- Please post questions on the original [Reaper forum](http://forum.cockos.com/showthread.php?t=93421) or here on GitHub.

## Version history
* ```1.0  Jun 2017:  Add font support```
* ```0.1  Dec 2011:  Initial version```


## Donate
Please make a donation if you think this script is useful for you. Thank you very much! :-)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FUPLMV8JNMJTQ)
