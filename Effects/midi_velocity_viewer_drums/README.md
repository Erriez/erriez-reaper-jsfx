# MIDI Velocity Viewer Drums for Reaper (JSFX script)

This JS script for Reaper displays MIDI velocity levels with minimum and maximum values.

## Screenshot
![Screenshot](https://raw.githubusercontent.com/Erriez/erriez-reaper-jsfx/master/screenshots/midi_velocity_viewer_drums_gm_01.png)

## Requirements
- All Reaper versions 4.60+ and 5.0+.

## Installation
- Copy the ```midi_velocity_viewer_drums``` JSFX script to: 
  * Windows 7/8/10: ```C:\Users\<username>\AppData\Roaming\REAPER\Effects\MIDI\```
  * Mac OS X: ```/Users/<username>/Library/Application Support/REAPER/Effects/MIDI/```
  
- Copy the ```Data``` directory with presets to: 
  * Windows 7/8/10: ```C:\Users\<username>\AppData\Roaming\REAPER\Data\```
  * Mac OS X: ```/Users/<username>/Library/Application Support/REAPER/Data/```

## Add FX to a track
1. Start Reaper
2. Click on the FX button on a (MIDI) track
3. Browse to this file: ```JS: MIDI\midi_velocity_viewer_drums```

## Usage

* Slider1: Select the MIDI input channel 1-16 or Any
* Slider2: Select the number of grid lines 0..10
* Slider3: Select the number of notes per column 1..16
* Slider4: Select a font size 10..40
* Slider5: Select a configuration file
  
- Left mouse click to hide/show the minimum/maximum velocities
- Right mouse click to reset

### Customize font
Edit the following variables in the script to change font and font size:
* ```custom_font``` Enable custom font 
* ```font_type``` Font type
* ```font_flags``` Bold, italic and or underline

## Help
- Please post questions on the original [Reaper forum](http://forum.cockos.com/showthread.php?t=93421) or here on GitHub.

## Version history
* ```1.0  01 Jul 2017:  Initial version```


## Donate
Please consider a donation if you think this script is useful for you. Thank you very much! :-)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FUPLMV8JNMJTQ)
