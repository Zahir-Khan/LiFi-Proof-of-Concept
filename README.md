[![Build Status](https://api.travis-ci.com/Zahir-Khan/LiFi-Proof-of-Concept.svg)](https://travis-ci.org/Zahir-Khan/LiFi-Proof-of-Concept)
[![License](https://img.shields.io/github/license/Zahir-Khan/LiFi-Proof-of-Concept.svg)](LICENSE)

# LiFi-Proof-of-Concept
A proof of concept for communication using light in open air using led's and arduino.

<p> 
  <img src="images/Illustration.jpg" alt="LiFi-Illustration" width="400"/> 
  <img src="images/Practical_build.jpg" alt="LiFi-Prototype" width="400"/>
</p>


## How-To Hardware
### Components
  * Arduino Uno - 2
  * Two pairs of LED's are used. One as a clock for data synchronisation and other for data transmission.
  * LED specs vary widely, it is recommended to use similar LEDs. 10mm blue colored leds were used.

### Pin Usage
#### Sender
  * Clock pin no. - 13
  * Data pin no. - 11
#### Getter
  * Clock pin no. - 5
  * Data pin no. - 2
##### Notes
  * Use proper LED resistors to limit the current.
  
  
## How-To Software
  * Load both programs onto two Arduino Uno boards.
  * Open the CLI and set the baud rate to 115200.
  * Input a string into the sender CLI, reciever should start printing out the characters.
##### Notes
  * Detection thershold is set to 300 - Value changes for LED type used.

## Data Frame
<img src="images/Data_frame.jpg" alt="LiFi-Data-Frame" width="400" align="center"/>

## CLI Screenshots
<p> 
  <img src="images/Sender_cli.jpg" alt="LiFi-Sender" width="400"/> 
  <img src="images/Getter_cli.jpg" alt="LiFi-Getter" width="400"/>
</p>

###### Reva University - Minor Project 2018 (Class of 2019 C&IT)
