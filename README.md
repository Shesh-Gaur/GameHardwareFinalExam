# GameHardwareFinalExam
Explanations:

i)

The Components I Chose: 
- Accelerometer / gyroscope: Used for movement on the x and y axis.

- 2 push buttons: 1 for temporarily becoming invulnerable or for some ability, the other for pausing the game, or other context sensitive actions. When in menus, you can use one button to change the option, and the other button to confirm your selection.

- Vibration motor: for when Pacman becomes invincible

ii)

To fit with Pac-Man, my controller is made in the simplified shape of a ghost. The Arduino and gyroscope lie directly on the breadboard. The breadboard would be attached to the controller's base using 3M adhesive. The vibration motor is located near the bottom of the controller, so it's near the user's hands. The 2 buttons are on the left and right handles of the controller for easy access.

The controller is separated into 2 parts: the base, and the lid. There is a notch in the top of the base, that the lid can click into to help secure it. If I had more time, I would add more of these notches / hooks to ensure the lid doesn't come off during use. You could also use something to adhere the lid to the base. The lid has 2 cut-outs for the 2 buttons. Rounding sections of the handles would also help for comfort.


iii) Exploded view not required.

iv) Link to my TinkerCad: https://www.tinkercad.com/things/jz8T2e8ZEs3-magnificent-elzing/editel?sharecode=PB8TDedp6IXyrxXlRyqFFxHAx91_f8lZH8rA4wFt0Ic 

Demo Video: https://youtu.be/lkoJc4AGt-s 

I replaced the accelerometer/gyroscope with 2 tilt sensors to represent movement on both axis, as there is no gyroscope available in TinkerCad.

I have the buttons and vibration motor set-up so they would have wires soldered to them, allowing freedom in their placement. The tilt sensors are placed directly onto the breadboard for structural itegrity.

In terms of the demo, I print to the Serial Monitor for whenever each of the inputs are used. For example, the buttons print that they are pressed when pins 2 and 3 are pressed. The tilt sensors print when they are tilting left as well. Programming implementation for the vibration motor would have to be done when communication between the engine and Arduino are being performed, as the game would activate when PacMan becomes invicible.
