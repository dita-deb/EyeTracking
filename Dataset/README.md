# Data Collection
## Process
- Collect Photos/videos of a stationary position capturing an item
- automating the process of distance and collecting data from a ultrasonic sensor and the Arduino Mega 2560

## Code
- Arduino:
  - Utilize the ultrasonic sensor to make sure the object is consistently in a specific range to perform angle calculation.
  - set starter distance to 10 inches away from set up. (move the object in a semi-circle shape)
  - Make sure the moved object is still with in the appropriate range
- Raspberry Pi:
  - live camera feed take images automatically every 5-10 seconds
  - at each defined angle label the data accordingly
  - give each angle a good range (for example object is at 32 degrees have it rounded up to 40 and if it's at 47 it's 50)
    - improve rounding later with more data/training information

- Do I want two separate devices? or can I have ultrasonic working on raspberry pi?
