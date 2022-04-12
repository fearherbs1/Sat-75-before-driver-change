# Info
This repo contains QMK Folder for the satisfaction 75 keyboard before the oled driver was changed.

# Why?
After flashing the current release of QMK I noticed the oled look and behavior was diffrent, and the given firmware on cannonkeys site had a bug with the right mods.  
This set of satisfaction 75 code uses the old driver and fixes that issue.  

# Use
1.) Clone the QMK repository and revert to the commit right before the change:
`git reset --hard 7b753f2`  

2.) Download the files from this repo and replace the `qmk_firmware\keyboards\cannonkeys\satisfaction75` folder with these files.  

3.) Build the keyboard firmware as normal.  

For convenience, a built .bin file is included in this repo.
