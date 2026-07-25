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

## July 24th - Case Bottom
- I'm used to Onshape but I want to learn SolidWorks since I'm going to University and will probably have to learn it anyway so the sooner the better
- There was a massive learning curve starting out but I figured out the shortcuts in the end
- Assembly was definitely a pain to work with and I struggled with the mates for a while
- Got a mockup of the bottom going
<img width="770" height="590" alt="Screenshot 2026-07-24 002216" src="https://github.com/user-attachments/assets/3f795476-c024-4927-8626-83341219c171" />\
Top View\
<img width="572" height="837" alt="Screenshot 2026-07-24 002715" src="https://github.com/user-attachments/assets/52503ff8-91c5-4402-85c4-b6b8d9ee2c85" />\
Side/Bottom View
- Discovered that with my setup I can stuff a much larger battery inside
- Going for one around the 500 mAh area (5mm tall)
- Probably going to use velcro or double sided tape to fix it to the bottom of the case
- The walls look kind of weak and I have to figure out how to actually fix the pcb into the case but that is another day's problem

Hours spent: ~2.5
