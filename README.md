# TriangleWaveSymphony
this is the project for week three of hack clubs half life

a while back I made a song out of only triangle waves, Wich are my favorite waveform, and I really liked it! I also like this guy called Eric Brandle who makes really cool free form electronic art stuff that makes music. so, for this week, I decided to make a free form electronic sculpture to generate music using triangle waves

- three triangle wave voices
- 6 note ROMs
- a noise beat
- free form electronics

## Arcitecture
the main issue with this project is that you have to walk a fine line between it not sounding repetitive when its played for a long time while also not sounding bad. the main way I solved the sounding bad part was by only using notes from a c minor seventh, essentially guaranteeing that every combination sounds at least ok. to solve the repetitiveness issue i use 2 roms to map every note (a frequency and a length) to 2 different notes and then randomly chose between the two. this give me some control over how I want to music to sound while still making everything very random.

## Schematics
I strongly perfer drawing all of my schematics by hand, but that unfortunately doesn't translate very well to a digital repository. here are some lackluster pictures
<img width="3024" height="4032" alt="IMG_0220 (1)" src="https://github.com/user-attachments/assets/d730b9a4-5be8-435c-b106-2ea383f1de14" />
<img width="3024" height="4032" alt="IMG_0219" src="https://github.com/user-attachments/assets/1ae4840d-d4a9-48aa-a8bf-845293640001" />
<img width="3024" height="4032" alt="IMG_0218" src="https://github.com/user-attachments/assets/b56d2c75-e342-4e62-8863-eb7d22f13cec" />
thats not a complete set, and I will add possibly better schematics later

## PCB
This design does feature a PCB for the ROM chips. it is just a 4x16 diode matrix to map every 16 notes to an output, with 2 used per voice.

## Finished Desighn
I will update this section once I have soldered the whole things

## BOM
I am not requesting funding for this project, so there is no BOM
