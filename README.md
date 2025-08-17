This project is a low-cost automatic pet feeder designed to feed cats and dogs reliably at scheduled times. 
It uses a servo motor to dispense food, sensors to monitor the food bin and the pet's bowl, and an alert system to notify if something goes wrong—like food not being dispensed or pets not eating.

## Features
- Scheduled Feeding:** Set feeding times and portion sizes for your pets.
- Bowl & Bin Monitoring:** Tracks bowl weight before, after dispensing, and after eating to confirm consumption.
- Servo Motor Dispensing:** Releases food precisely at the scheduled times.
- Alerts: Notifies if there is a problem with dispensing or consumption.
  
## Components
- Servo Motor
- Real-Time Clock (RTC)
- Food Level Sensor
- Weight Sensor
- Alert System (LED)

## How It Works
- Initialize system with feeding times and portion sizes.
- Read sensors: current time, food bin level, bowl weight.
- heck if it's feeding time and activate the servo motor.
- asure bowl weight after dispensing and after eating to confirm pets ate the food.
- trigger alerts if any issue is detected.

## Future Improvements
- Mobile or web dashboard for remote monitoring.
