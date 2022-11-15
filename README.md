# Hackathon-2022
Welcome to the CRT x Hacker Society 2022 Hackathon!

**Important Note: never push to main! your team should create a new branch and do your development there. Pushing to main will result in permanent disqualification.**

## Goal
Your mission, should you choose to accept it, is to design a simple barometric data logger for our L1 rockets.

You data logger should:
* Record temperature and pressure and time since power on
* Store the data to a non-volatile device (the flash chip)
* When connected to serial, dump data and ask if it should erase itself.

The final data logger will be:
* soldered on a perf board (the red boards you've been given)
* operated on battery power (so leave room for a connector)
* totally radical and flight ready!

## Update Number 1!
You have been given three components, a micro controller (pinout attached) ad barometer (BMP 180) and a flash chip (W25Q64). Are you confuced about how to communicate with these devices? You should be able to use the included packages to figure some stuff out...


## Special Challenges

- [ ] Create a new branch named member1-member2-member3 (with your team member names, not member 1 2 or 3) + 5pts
- [ ] Add a wiring diagram for your Barometer (over I2C) and your flash chip (over SPI) + 20pts
