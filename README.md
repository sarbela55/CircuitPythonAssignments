## CircuitPythonAssignments
This is a repository for all of my Circuit Python assignments.

# CircuitPython Servo Assignment:

Objective:
In this assignment, I had to wire up a servo to my metro express, and write code in CircuitPython to command the servo to rotate 180 degrees. 

Problems:
I had a lot of trouble with this assignment, as I haven't coded since last year, and I basically had to start from scratch. In the beginning, I had a problem where the servo would seem like it was going to work, but would just vibrate and not actually spin the top piece. I don't know If this is a problem with my code or the servo itself. I'm pretty sure my code is right, as I checked it with a repository from one of my classemates. I finally swiched something up in my code, and it allowed the servo to function normally.

Wiring: 
I don't know how to put an image into github yet, or how to access fritzing. It says I have to pay to download.


# CircuitPython Photointerrupters assignment:

Objective:
In this assignment, I had to wire up my Metro Express to my photointerrupter, and command the photointerrupter to track how many times it had been interrupted. 

Problems:
I had never wired a photointerrupter to a Metro express, so I had to use Luke Franks code as a reference point(thank you for coming in clutch Luke). I had written my code, and I was pretty sure it was right, but it still wasn't working. After a few days of being stuck, I finally figured out that my wiring was to blame. I had mixed up my negative and positive terminals on my breaboard, and after I switched them, it began to work. I  had tunnel vision on my code, and should have taken a step back to look at all of my pieces, not just the code.

Luke Frank's Repo: https://github.com/lfrank01/CircuitPython/tree/main/CircuitPython_Photointerrupter 

# CircuitPython Distance Sensor assignment: 

Objective: In this assignment, I had to wire up my Metro express to the HC-SR04, and have the color pixel on the Metro Express change color due to the distance away something is from the sensor. 

What it does:
The TRIG pin communicates with the sensor to send out an ultrasonic wave, which can sense how far away an object is from the sensor. The wave bounces back, and the echo pin recieves this wave, and tells the servo how far away the object is. The GND pin is like all other ground pins on other sensors, and the VCC pin accounts for the power supplied to the sensor.

I used Luke Frank's diagram to help me configure my wiring.(https://github.com/lfrank01/CircuitPython/blob/main/CircuitPython_Distance_Sensor/Luke-Engineering_III-CircuitPython_Distance_Sesnor-Circuit_Diagram.pdf)


# Classes, Objects, and Modules assignment:

objective: Use the given code and add pieces to make it work. This is intended to make it easier to use RGB LEDs. 

Problems: Wiring up the RGB LED was easy, but I didn't really know what numbers to fill in for the different time slots. I learned that different combinations can produce different hues of a color on the RGB LEd, and that setting a pin to a certian number can turn off the different colors in the LED.

# FancyLED Assignment:

Objective: Create a library that works with all 6 LEDs, and make the given code work.

Issues: I only had 5 resistors for some reason, so I had to wait for my dad to come back the next day with one from his work. 

Things I learned: Using lists made it much easier for me to write my code in a more efficient and space saving manner. 

Wiring: ![FancyLED Original Circuit Diagram](./Luke-Engineering_III-FancyLED_Origonal_Circuit_Diagram.png)
