# Corona_Arduino_Robot
It is an Arduino project about robotic insect made together with my friends.

Step 1: MATERIAL REQUIREMENTS
  1.  Arduino UNO
  2.  Four Servos
  3.  HC-06 (Bluetooth)
  4.  Buzzer
  5.  Power Bank
  6.  Two LEDs
  7.  Wire Jumpers
  8.  Breadboard
  9.  Steel that can be bent to make legs
  10. 9V Battery
  
Skills Required for this project are:
  1. Basic knowledge of electronics and arduino.
  2. Knowledge of the movements of four or six legged insects.
  
Step 2: Circuit Diagram
  1. Gather and collect the required items above we mentioned. Hardware is illustrated in circuit diagram.
  2. Download the servo library from Arduino website and add.(After adding, restart IDE)
  
STEP : 3 HOW DOES IT WORK?
  Four servos will move into the direction that is controlled by Bluetooth controller application in mobile phones. If we want to make insect move forward, we have to press 'F' , 'B' for backward, 'R' for right, 'L' for left, 'S' for LEDs and 'Z' for Buzzer to make sound.
  SERVOS have integrated gears and a shaft that can also be precisely controlled. Standard servos allow the shaft to be positioned at various angles, usually between 0 and 180 degrees. Servo motors have three wires: power, ground and signal. The power wire is typically red, and should be connected to the 5V pin on the Arduino board. The ground wire is typically black or brown and should be connected to a ground pin on the Arduino board. The signal pin is typically yellow, orange and white and should be connected to a digital pin on the Arduino board.
  Note: servos draw considerable power, so if you need to drive more than one or two, you'll probably need to power them from a separate supply ( i.e. not the +5V pin on your Arduino). Be sure to connect the grounds of the Arduino and external power supply together.
  
  A BUZZER  is basically a tiny speaker that you can connect directly to an Arduino. From the arduino, you can make sounds with a buzzer by using tone. You have to tell it which pin the buzzer is on, what frequency (in Hertz, Hz) you want, and how long (in milliseconds) you want it to keep making the tone.

  LEDs (light emitting diodes) have two nodes; anode and cathode. It can be connected to ground pin in Arduino with cathode and 5V with anode using resistor.
  
  
 Made by Yaungni Linn Latt, Kyaw Phyo Aung, Kaung Set, Wai Yan Htein Linn
