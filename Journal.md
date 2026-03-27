# LED charge circuit

https://is.gd/QYAum3
I'm building LED alternating lights when one is off and one becomes on because it is simple and researchable for a beginner for me.

## March 23 - Researching and prototyping

Today I worked on prototyping a few circuits. I originally first tried to create a circuit on my own, following the tutorial. I managed to get something working though. In one of my timelapses with the three LEDs, with the resistors before the LED it managed to slowly close one by one. Having a resistor in between two LEDs worked and a resistor in parallel to the series circuit. I built it this way because it worked and achieved a blinking effect when I tested it.

<img width="316" height="171" alt="Screenshot 2026-03-26 at 10 41 48 PM" src="https://github.com/user-attachments/assets/0c65c835-27a8-4881-8bd7-783dc259ae1e" />
Image of my lapse

Through researching I ran into an issue with parallel circuits not working, and it looks like the power gets cut off.

### Time Spent: 0.5 Hours

## March 26 - More Prototyping

Today I am restarting over again and continuing the research from before. The goal is to create an LED oscillator circuit. I found a diagram on instructables with a guide I can reference. This is week 1, but I am going to include transistors maybe because it splits the power. I ended up building my circuit as a parallel circuit and I notice it doesn’t work as all the LEDs close when I turn on and off the switch. I decided to add another resistor between my two LEDs. If I want my second led to turn off slower, I might want to change my resistor value from 1k to lower. I wonder which one though… My problem is when I added the resistor between the LEDs, the second LED already started dimming. As if the dim light was the default. In an attempt to change the capacitor to have a large capacity of energy, the LED dimmed slowly since there was a lot of leftover potential energy. But it was all at the same time.

Trying to follow the diagram, I added another resistor parallel to the circuits. It didn’t seem to work all the same. I built it parallel as I only want power to go to specific areas. Maybe it might be because the switch is directly next to the power, so I’ll place it elsewhere. I found out after trying in the simulation it wouldn’t work because the power directly gets cut off from the LED, instantly dimming it. I’ll follow the example and add a capacitor next to the LEDs to make an oscillator. Although I don’t want to add transistors yet. 

My problem is not getting the correct keywords for researching. So I decided to go back to researching, specifically changing my goal, to make one LED turn on when the other one is off. I don’t think I need to have just one power source, and that is what I figured out because if I have only one and have a switch, it’ll just cut the power for everything. I ended up moving the power source from the negative terminal and it didn’t work. I definitely need a series circuit for this terminal. Looking at other people’s diagrams, I often notice a one way voltage source and a ground as well so I’ll try that!

I designed my circuit this way because the LEDs need a resistor so I added it right before they reach ground and a capacitor in between. A two terminal power source did not work for me because the series circuit cut off the voltage source to everything connected within the circuit. When I tested it out with the switch, I saw one LED turn off and the other turned on, but when I try to close the circuit the other LED eventually turns on, resulting in two leds turning on.

<img width="788" height="247" alt="Screenshot 2026-03-26 at 7 50 59 PM" src="https://github.com/user-attachments/assets/558ce7d0-21f3-40ef-9d57-7a830bb76147" />

I attempted to move the LEDs after the resistors and changed the size of the capacitor to small resulting in a faster dimmed light.

<img width="758" height="224" alt="Screenshot 2026-03-26 at 8 09 09 PM" src="https://github.com/user-attachments/assets/dff05aa4-8877-4b2c-a703-ca38aafc3e54" />


Tested with more leds, but nothing changed in terms of brightness.

<img width="874" height="265" alt="Screenshot 2026-03-26 at 8 14 18 PM" src="https://github.com/user-attachments/assets/1f579b82-f615-450d-ac78-46153ccdd489" />

A similar case happens when I try to make it like that.

<img width="823" height="281" alt="Screenshot 2026-03-26 at 8 18 37 PM" src="https://github.com/user-attachments/assets/9ab5117d-81f8-4622-88cb-bc96c506ba07" />

### Time Spent: 1 Hour

