# Theatis
Projects using the Arduino Uno R3 microcontroller and the Garmin LIDAR Lite v3

Information on the Arduino Uno R3 can be found at:

https://www.arduino.cc/en/Main/ArduinoBoardUno

Information on the LIDAR Lite v3 can be found at:

https://buy.garmin.com/en-US/US/p/557294


## Projects planned - Car based

- **Relative velocity indicator**
  - Show relative velocity of your car compared to the car directly ahead
  - Displayed on an alphanumeric or 7 segment display
  - LIDAR Lite mounted on widshield with suction cup mount
  - 0: velocity of car matches car in front
  - Positive velocity: velocity of car is faster than car in front; approaching
  - Negative velocity: velocity of car is slower than car in front; receding
  - Example: Car in front is traveling at 50 mph, LIDAR car is traveling at 55 mph, display shows positive 5.0
  
- **Distance alarm**
  - Display a flashing LED or emit an alarm sound when the car is a certain distance from an object
  - LIDAR Lite mounted on widshield with suction cup mount
  - Example: Alarm is triggered when distance from car to an object in front is equal to or closer than 40 feet
  - Can be modified to provide an alarm when the distance is outside of a range
  - Example: Alarm is triggered when the distance from the car to an object in front is closer than 40 feet or farther than 45 feet
  - Can be modified to provide a blind spot or reverse collision alert depending on mounting location and distance

