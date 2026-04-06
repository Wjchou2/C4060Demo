<h1>Researched C4060 IC and read datasheet. Draw schematic.</h1>
<h3>3/27/26 - 90m </h3>
The goal for today was to research and plan out the pcb baord by mapping out the schematic in KiCad. At first I researched the NE555 and CD4017 but going down the list, the CD4020 caught my attention. It was labled as a "Binary Counter/Divider", which made me originally think it would store a very small out of data, but after, I realized that it was actually for counting and timing, I chose to stick with it. I decided to make a not too comples project that is able to show the different pins and the timing of LED blinks for each one. Instead of only having 1 LED, blinking at a fixed interval, I thought it would be cool to be able to use all the different timing pins, so I added resistors and 2 pin headers to each Q-Pin. 
<br><br>
One of the main problems I encountered was not knowing how to translate the information on the datasheet page into actual usable and functional circuts. I did some googling and learned about the rc oscillator loop, and integrated it into my schematic.
<img width="300" height="332" alt="Screenshot 2026-04-06 at 2 06 55 PM" src="https://github.com/user-attachments/assets/ffface51-f890-4ade-80b3-e5445ac1b875" />
</br>
After getting some feedback, I realized that a single power source could power all 10 LEDs at once and there was no need for the 2pin headers. I also fixed the resistors, making them more redable by giving them values and R1,R2... labels.
<img width="400" alt="Screenshot 2026-03-27 at 4 31 52 PM" src="https://github.com/user-attachments/assets/12ccd699-d857-4ad4-8d05-8173bb6101f2" />
<img width="400" alt="Screenshot 2026-04-06 at 2 11 24 PM" src="https://github.com/user-attachments/assets/f4ab2e82-b648-4711-b01a-8fc779b0942c" />

<br><br>
Overall I'm pretty satisfied with how this schematic building went. I didn't reply on AI for help all the time and actually learned how to use the datasheet myself.


<h1>Placed Components, drew wires, added silkscreen text!</h1>
<h3>3/27/26 - 75m </h3>
Placed all the components in good places, routed wires, drew labels for GND and VCC as well as adding a board name and github link. No problems in DRC! I chose to place the IC and power pins on the left side and the sets of resistors and pins for LEDs on the right, for easier organization. I routed and added a ground plane. For the edge.cuts, I wanted a simple, easy to use and hold design, so I went with a compact rectangle shape with rounded corners that could fit all the components. I added labels for GND and VCC for power and LED pins, named the board, and put this github repo on the back. The 3D render looks good!
<br>
<img width="400" alt="Screenshot 2026-03-27 at 5 00 10 PM" src="https://github.com/user-attachments/assets/214931fb-f578-44a6-9fb3-2712034b85ab" />
<img width="400" alt="Screenshot 2026-03-27 at 5 01 33 PM" src="https://github.com/user-attachments/assets/699ff770-d313-49bf-a5e3-209b1b8e9bb3" />

<h1>Fixed Footprint for C4060 IC</h1>
<h3>4/3/26 - 20m </h3>
Got feedback from Rudy, fixed the IC to the THT version, rerouted wires and redraw ground plane. 
<br>
<img width="500"  alt="Screenshot 2026-04-03 at 7 02 22 PM" src="https://github.com/user-attachments/assets/a0ded8fe-4e7c-436c-b391-ba600ebf71f5" />

<img width="500"  alt="Screenshot 2026-04-03 at 7 01 17 PM" src="https://github.com/user-attachments/assets/3be516e9-073c-46fc-b7f2-b4c8c85133c4" />
