# DC-MOTOR-DRIVE
Switch rotating direction of a DC shunt motor.
DC motor works on 90V DC, stator coil is energized with sam polarity.
Polarity of rotor coil is reversed via  H-Bridge N-Channel mosfets.

PWM frequentie 5KHZ is generated with ATMEGA16 microcontroller.

Micocontroller is generating control signal PWM1 and PWM2 for H-Bridge drivers.
If PWM1 signal is defined, PWM2 signal shuold be tight to GND, and vice versa.
This is the thing to know about this circuit.
