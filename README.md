Restaurant of The Future
Abstract-:
Changing the tradition of human waiters, the bot delivers delicious food to you. The project uses mobile app to order the food and a mechanical bot to 
deliver the cokked food to the consumer.
Team Members-:
1)Sanjay Kumar
2)Kundan Kumar
3)Aman Verma
4)Sagar Pant
5)Shubham Chitransh
5)Harshit Bansal
6)Karan Shrivastav
Mentors-:
Prashant 
Pulkit Goyal
Applications-:
The bot may be used to completely transform the future of restaurants. It may be used as the perfect replacement for the waitors to deliver the food
ordered by the customer . Other applications include delivery of goods from malls and other nearby stores.
Pre-Requisites-:
1)Arduino (Uno / Mega or any other aduino board)
2)2 Servo Motors(..... )
3)2 Wheels
4)1 Caster Wheel
5)2 Motor Drives(L298N)
6)2 Encoders / Proximity sesnors
7)Bluetooth Module(HC-05)
8)Jumper Wires
9)Breadboard
10)12V battery

Software Used-
!)Arduino
2)Android Studio

Electronic Design -:
1) Arduino is an open-source electronics platform based on easy-to-use hardware and software. Arduino boards are able to read inputs - light on a sensor, a finger on a button, - and turn it into an output - activating a motor, turning on an LED. You can tell your board what to do by sending a set of instructions to the microcontroller on the board. To do so you use the Arduino programming language (based on Wiring), and the Arduino Software (IDE), based on Processing.
2) We used Arduino Mega Board -:
The Arduino Mega is a microcontroller board based on the ATmega1280 (datasheet). It has 54 digital input/output pins (of which 14 can be used as PWM outputs), 16 analog inputs, 4 UARTs (hardware serial ports), a 16 MHz crystal oscillator, a USB connection, a power jack, an ICSP header, and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with a AC-to-DC adapter or battery to get started. The Mega is compatible with most shields designed for the Arduino Duemilanove or Diecimila.
3) Otical Encoder-:
An optical encoder is a type of rotary encoder that uses a sensor to identify position change as light passes through a patterned encoder wheel or disk.
There are four components in an optical shaft encoder:
A light source (an LED light)
A sensor
A moveable disk
A fixed mask
The LED shines through one side of the optical shaft encoder. The encoder wheel or disk has a series of tracks on it, similar to the concentric grooves in an LP. The mask has a corresponding track for every track on the disk of the optical encoder, and small perforations, called windows, are cut along the tracks in the mask. As the disk moves, different windows in the mask are covered or open, showing the movement and position of the optical shaft encoder. Each arc in the rotation indicates a different position and has a different pattern of open/closed windows. The sensor behind the mask identifies the optical encoders’ current pattern.

4) Motor Drives-:
An H-Bridge is a circuit that can drive a current in either polarity and be controlled by *Pulse Width Modulation (PWM).

* Pulse Width Modulation is a means in controlling the duration of an electronic pulse. In motors try to imagine the brush as a water wheel and electrons as a the flowing droplets of water. The voltage would be the water flowing over the wheel at a constant rate, the more water flowing the higher the voltage. Motors are rated at certain voltages and can be damaged if the voltage is applied to heavily or if it is dropped quickly to slow the motor down. Thus PWM. Take the water wheel analogy and think of the water hitting it in pulses but at a constant flow. The longer the pulses the faster the wheel will turn, the shorter the pulses, the slower the water wheel will turn. Motors will last much longer and be more reliable if controlled through PWM.

Working -:
The Bot is a signal receiver cum delivery bot that may be used in a restaurant to take the order from the customer and deliver the ordered itmes to customers.
This is done by the use of an app built using android studio. The app may be placed on each table of a restaurant and the customers may use it for ordering food.
The bot uses a bluetooth module to recieve the signal and gets to know about the table to which it is supposed to move. Then it makes use of the code on the microcontroller and moves to the table which has ordered the food and delivers it to the customer by sliding the upper plate using a gear driven by the motor.
The error reduction in motion is done through pid tuning of the bot. The bot moves to the table position which is fixed and delivers the food.
