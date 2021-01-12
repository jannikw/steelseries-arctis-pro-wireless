# SteelSeries Arctis Wireless Pro setup for PulseAudio

Utilizes a systemd service to setup the headset when it is plugged in.
- Set the stereo sink as the default sink
- Redirect audio of all currently running applications to the new sink (usefull for apps like Spotify which would otherwise require a restart)
- Set the volume of the ALSA sound cards to maximum for both mono and stereo output. This way volume is in complete control of PulseAudio.

## Installation

Manually install the service and copy the `steelseries-arctis-pro-wireless` script to `/usr/local/bin` or install as an Arch package using `makepkg -i`.
