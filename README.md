# StealthChangerA4T
A modified version of the A4T tool head and stealth changer dock and backplate, optimized for tool changing

First and forremost, this project is derived from many existing projects, let me give credit where it is due!

The backplate was modified from the official Draftshift Steath Changer:
https://github.com/DraftShift/StealthChanger

The A4T was modified from the Armchair Heavy Industries:
https://github.com/Armchair-Heavy-Industries/A4T

The dock is combined from multiple modular dock pieces, then heavily modified:
https://github.com/DraftShift/ModularDock

The sock was inspired by Nic335's design, but completely re-designed by me:
https://github.com/DraftShift/StealthChanger/tree/main/UserMods/Nic335/NH36Sock

The PCB mount was inspired by TheSin's mount:
https://github.com/DraftShift/StealthChanger/blob/main/UserMods/TheSin-/PCB36_Mount/PCBMount.stl

The APUS2 model was taken from the APUS2 Github:
https://github.com/Phaetus/APUS-2

The OptoTap model was taken from the OptoTap CAD:
https://github.com/VoronDesign/Voron-Tap/tree/main/OptoTap

The Nitehawk board and cable was taken from the Nitehawk CAD:
https://github.com/MotorDynamicsLab/Nitehawk-36
Though the cable was simplified by me to smooth out the cavity


The 3007 Fan Mount is my original design

<img width="451" height="634" alt="image" src="https://github.com/user-attachments/assets/a74bd280-d5e0-43ca-81d7-c1da0838489d" />

So why this project?

I assembled my Stealth Changer using the Anthead tool head, as is often recommended.  But, I really wasn't very happy with that tool head.
It seems too complicated, has too many pieces, and is hard to work on.  Having to dis-assemble the entire tool head, to snug the hot end screws, was not my favorite project.  Plus, I was strugging with hot end cooling, as well as part cooling that was a little sub par.

I had previously used the A4T tool head, and really appreciated its simplicity and how solid it was.  Plus, it had better cooling.  

However, the published backplate for the A4T was hard to print.  The A4T was designed for the XOL carriage, and had mounting points that were really not neccessary when used with a Stealth Changer back plate.  That, and it did not have magnets built in.  There was a modified dock upright that used magnets, but I rather preffered a dock that did not use the uprights at all.

So, I began by updating the A4T, to flatten the back, and switch to heat set inserts in the body, rather than through bolts.  This allowed me to mount the screws from the backplate, since access is not an issue on the Stealth changer.
I then added 4 magnets, 2 in front, and 2 on the bottom, to lock the tool head in place nicey

<img width="572" height="606" alt="image" src="https://github.com/user-attachments/assets/dd9bc344-90af-4118-b8d7-855bca06330a" />

Moving on to the dock, I took the existing modular dock, and merged it into a single body.  Modular is nice, but a single part is nicer.
I left the back adjuster separate, but narrowed the entire body to 72mm.  I then updated the shape of the dock, to better fit the A4T, and to include the magnets.  I also opted for the Bambu style wiper.  I widened the attatching bolt spacing, and added an extra side support for the 2020 extrusion

I updated the back adjuster, to give a better chamfer on the aligning, and to increase the slotted hole's width.  This allowed me to use a washer under the bolt.  I was seeing isuses with the original adjuster, where the bolt would scar the plastic, and not allow for minor adjustments

The dock is designed to print on the front face at a 45 degree angle

<img width="616" height="512" alt="Screenshot 2026-02-21 142738" src="https://github.com/user-attachments/assets/69f721d6-299b-4afc-b328-d194893bee6a" />

Next, I updated the back plate.  I added a mounting point for the PCB, and added holes at the bottom to mount the A4T.  I also updated the chamfer, to not have any complete overhangs.  It also prints quite nicely flat now, with no supports

<img width="478" height="594" alt="image" src="https://github.com/user-attachments/assets/f6fcee77-8ff7-46f1-b7f8-4092ff06187a" />


On to the PCB mount.  I really liked the WWG2 for its simplicity, so that is what I used here.  I liked the idea of the sock mount, but I had always struggled getting it off.  I opted for a smooth support for the sock.

<img width="452" height="637" alt="image" src="https://github.com/user-attachments/assets/38b216c7-56f7-415a-a15c-dc179e9762f2" />

The sock was completely redesigned.  I wanted to be able to securely mount the sock to the PCB mount, but have it easy to un plug.  So I added 4 notches, that work perfect with small zip ties, to create a snug lock.  It is slotted in the back, to allow easy installation on your cable

<img width="387" height="561" alt="image" src="https://github.com/user-attachments/assets/d88668c2-cae6-4329-b455-f7b2ce7dc2de" />

Finally, I needed cooling for my Nitehawk.  The 3007 fans available for Raspberry Pi's were easy to get, and dirt cheap.  So I created a simple mount that is used in conjunction with the Nitehawk mount.  It also has a tab, that works with the lower zip tie, to hold the whole assemmbly snug.
This one requires some supports to print.  The supported surfaces don't seem to print very nicely, but that doesn't affect functionality

<img width="599" height="539" alt="image" src="https://github.com/user-attachments/assets/a1d3993f-5959-4b52-8434-a0c4a4179f61" />


