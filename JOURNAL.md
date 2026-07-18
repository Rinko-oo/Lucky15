# JOURNAL.md
## July 15th - Starting Out
- Decided on a 4x4 macropad with 15 keys and a rotary encoder
- The 3 Switches at the top are to be previous track, pause/play, and next track
- Rotary encoder for turning up and down the volume & mute button
- Remaining 12 switches for macros and shortcuts
- Started off with the [Hackpad Guide](https://hackpad.hackclub.com/guide)
- Got recommended the [NRF52840](https://www.aliexpress.com/item/1005007205026373.html)\
<img width="661" height="588" alt="image" src="https://github.com/user-attachments/assets/0a6e4cdd-c6a4-4b88-806d-3ebe476cc07b" />\
First iteration of the schematic
- Looked super simple so I decided to add a few things
- 0.91 Inch OLED screen to display currently playing media
- 110 mAh battery so I can use it wirelessly like a remote control
- I only had enough pins for the encoder and switches, not enough for the OLED display
- Was referred to this [Joe Scotto tutorial](https://youtu.be/8WXpGTIbxlQ?si=8FqVbhXCCD7eRLAT) and switched to using diodes like he does
<img width="926" height="637" alt="image" src="https://github.com/user-attachments/assets/ff7b25dd-17d0-459c-be97-40e3782d9165" />\
Current iteration of the schematic

Hours spent: ~2.5 Hours

## July 17th - The PCB
- 
- Updated PCB from schematic and dragged all the components into place
- Had the wrong footprint so I just got the nice!nano footprint since the difference between the NRF52840 and the nice!nano isn't applicable to my use case
- I have to flip the OLED screen upside down but it should be a quick firmware tweak to make it display things upright to user
- Battery mounts under the pcb so the wire doesn't get in the way and I don't have to cluster everything on the top
- Tried to run traces as cleanly as possible\
<img width="583" height="706" alt="image" src="https://github.com/user-attachments/assets/0dbffee2-6528-4fd5-8140-76f0c04b3851" />\
PCB without filled zones\
<img width="592" height="702" alt="image" src="https://github.com/user-attachments/assets/a3c52105-db6d-4434-a9ca-9d9f4aa83dc0" />\
PCB with filled zones
- Case is next

Hours spent: ~1.5
