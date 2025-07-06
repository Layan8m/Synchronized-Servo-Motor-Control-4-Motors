# Synchronized-Servo-Motor-Control-4-Motors
This Arduino project demonstrates how to control four servo motors simultaneously (in sync). The motors run a sweeping motion for 2 seconds and then hold their positions at 90 degrees.
- Uses the Servo.h library.
- Controls 4 servo motors connected to digital pins.
- Runs synchronized "sweep" motion (0° to 180° and back) for 2 seconds.
- Motors stop and hold position at 90° after the sweep.

#🛠️ Hardware Requirements
- Arduino Uno 
- 4servo motors 
- Jumper wires
- Breadboard 
- External power supply 

#📄 How It Works
- All servos start sweeping together in sync.
- After ~2 seconds, the sweep stops and all servos move to 90° and hold.
- The loop stops, so no further motion occurs unless reset.


1. Connect the servos to digital pins 3, 5, 6, and 9.
2. Upload the code to your Arduino board.
3. Provide 5V power from Arduino or external power supply.
