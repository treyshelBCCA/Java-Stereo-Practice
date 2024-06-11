# README

## Description:
Your task is to create a Stereo class using Java.


## Rubric:
Your stereo should have the following functionality:

- [ ] Should be able to power on and off.
- [ ] While powered on:
  - [ ] Increase the volume up to 100 in increments of 10.
  - [ ] Decrease the volume down to 0 in increments of 10.
  - [ ] Change the current station by cycling through an Array (AM -> FM -> XM and back)
- All functionality should be utilized in the command line.
- It should take user input. 

### Example:
Current Status: Powered Off.

Would you like to [P] Power on/off or [Q] quit?  > P

Current Status: Powered On.

Current Station: AM

Current Volume: 50

Would you like to [P] Power on/off, [S] Change station, [V+] increase volume, [V-] decrease volume, or [Q] to quit? > S

Current Status: Powered On.

Current Station: FM

Current Volume: 50

Would you like to [P] Power on/off, [S] Change station, [V+] increase volume, [V-] decrease volume, or [Q] to quit? > V-

Current Status: Powered On.

Current Station: FM

Current Volume: 40

...