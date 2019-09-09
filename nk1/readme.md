# externals for a Korg Nanokontrol 1

- Everything is on MIDI channel 1 by default, if it does not suit your needs, feel free to right click the canvas and edit the content !
- `nkb1~.pd` is for the buttons upper row and `nkb2~.pd` is for the bottom row
- `nkt~.pd` sends bangs for all transport controls
- `nkpgout~` uses Forward (CC 47) and Rewind (CC 48) to send a program change from 0 to 126, again on channel 1
- Feel free to edit / commit / whatever you would do
