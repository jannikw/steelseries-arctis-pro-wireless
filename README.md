# SteelSeries Arctis Wireless Pro setup for PulseAudio

Utilizes a udev rule to setup the headset when it is plugged in.
- Load the stereo sink (2nd usb device)
- Set the stero sink as the default sink
- redirect audio of all currently running applications to the new sink (usefull for apps like spotify which would otherwise require a restart)

## Installation

Manually install the udev rule and copy the `steelseries-arctis-pro-wireless` script to `/usr/local/bin` or install as an Arch package using `makepkg -i`.
