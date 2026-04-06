<h1>Researched C4060 IC and read datasheet. Draw schematic.</h1>
<h3>3/27/26 - 90m </h3>
The goal for today was to research and plan out the pcb baord by mapping out the schematic in KiCad. At first I researched the NE555 and CD4017 but going down the list, the CD4020 caught my attention. It was labled as a "Binary Counter/Divider", which made me originally think it would store a very small out of data, but after, I realized that it was actually for counting and timing, I chose to stick with it. I decided to make a not too comples project that is able to show the different pins and the timing of LED blinks for each one. Instead of only having 1 LED, blinking at a fixed interval, I thought it would be cool to be able to use all the different timing pins, so I added resistors and 2 pin headers to each Q-Pin. 
<br><br>
One of the main problems I encountered was not knowing how to translate the information on the datasheet page into actual usable and functional circuts. I did some googling and learned about the rc oscillator loop, and integrated it into my schematic.
</br>
<img width="300" height="332" alt="Screenshot 2026-04-06 at 2 06 55 PM" src="https://github.com/user-attachments/assets/ffface51-f890-4ade-80b3-e5445ac1b875" />
</br>
After getting some feedback, I realized that a single power source could power all 10 LEDs at once and there was no need for the 2pin headers. I also fixed the resistors, making them more redable by giving them values and R1,R2... labels.
<img width="400" alt="Screenshot 2026-03-27 at 4 31 52 PM" src="https://github.com/user-attachments/assets/12ccd699-d857-4ad4-8d05-8173bb6101f2" />
<img width="400" alt="Screenshot 2026-04-06 at 2 11 24 PM" src="https://github.com/user-attachments/assets/f4ab2e82-b648-4711-b01a-8fc779b0942c" />

<br><br>
Overall I'm pretty satisfied with how this schematic building went. I didn't reply on AI for help all the time and actually learned how to use the datasheet myself.

<h1>Placed Components, drew wires, added silkscreen text</h1>
<h3>3/27/26 - 75m </h3>
The goal for this 75 min was to assign footprints, and make a organized and functional PCB. I started by finding the footprints for each part. My inital idea was to have a small board with a column of LEDs, beacause this allowed it to be mroe clear whcih Q-pin corresponded to which LED. I also did a bit on research on the Ground Plane, and how to use it correctly. 

One challenge I faced was only after submitting and getting feedback did I learn the difference between SMD and THT components, THT being much easier to hand solder on. I switched the IC and LED footprints, and redesigned/reorganized the PCB. 

After starting to move components around, I realized that placing the LEDs in 2 columns was a lot more compact and much easier to wire. I also learned how to orient components better to maek it easier for myself to wire components. I fliped the orientation of resistors to face closer to the direction of where they would connect and placed the LED close to their corresponding resistors.
</br>
<img width="50" alt="Screenshot 2026-04-06 at 2 19 40 PM" src="https://github.com/user-attachments/assets/a7ad9ae9-a154-4734-8c1e-44afb76198c3" />
<br>
<br>
For the edge.cuts, I wanted a simple, easy to use and hold design, so I went with a compact rectangle shape with rounded corners that could fit all the components. I made sure to include lables on the silkscreen for GND and VCC, so that I know which way to plug in a power source when I get the actual board.
<br>
<img width="500"  alt="Screenshot 2026-04-06 at 2 20 58 PM" src="https://github.com/user-attachments/assets/fd44b7aa-4c87-44e9-a8fb-d82dbe6373a4" />
<img width="500"  alt="Screenshot 2026-04-06 at 2 20 49 PM" src="https://github.com/user-attachments/assets/092b089f-f763-44e4-a8ef-aa56e6cd24bd" />
<br>

<br>
Overall, I'm happy with how this project turned out, I learned a lot on how to use ICs and make hand-soldierable boards. 
