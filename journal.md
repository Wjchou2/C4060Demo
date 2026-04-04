<h1>Researched C4060 IC and read datasheet. Draw schematic.</h1>
<h3>3/27/26 - 90m </h3>
I started this project by looking up the different IC we could use, and found the C4060 one interesting. After looking through the datasheet and understanding the necesary pins, I drew a schematic, using a 2pin header for power, and learnign how to put together an RC oscillator. Instead of only having 1 LED, blinking at a fixed interval, I thought it would be cool to be able to use all the different timings, so I added resistors and 2 pin headers to each Q-Pin. 
</br>
<img width="550" alt="Screenshot 2026-03-27 at 4 31 52 PM" src="https://github.com/user-attachments/assets/12ccd699-d857-4ad4-8d05-8173bb6101f2" />


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
