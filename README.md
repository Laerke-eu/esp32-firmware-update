Steps to create a new version
- When a new version is created update currentFirmwareVersion in the Pressure.ino file
- Export compiled binary under Sketch menu in Arduino IDE
- update version.txt with the new version in this repository on main branch
- in the exsisting Release remove the current attached binary in Assets and Attach the new binary, remember it should have the same name. Update title as well and Update release.

Next time a board starts it should download and install the new version of the firmware.
