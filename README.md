# Arduino based Sonar

## Intro
In this project, we are going to design an Arduino sonar project using Ultrasonic Sensor for detection.

This Arduino sonar project aims to achieve a sonar system prototype based on an Arduino board that detects stationary and moving objects. The sonar system has different performance specifications, and it is also available in a variety of sizes.

## Preview

### Image

![med_5ab38332cab89_I8ZVSiZggc](https://user-images.githubusercontent.com/85011883/209826902-7b7a2e50-bf2a-4b1f-8292-d17e7b5e1b82.jpeg)

### Video

https://user-images.githubusercontent.com/85011883/209827288-2917e006-b824-4610-b157-52d04fb6bc18.mp4


## Requirements

### Software

We need two software to complete this Arduino radar project. One is Arduino IDE, and the other is Processing IDE. Download both Software from the below links.

[Arduino IDE](https://www.arduino.cc/en/software)

[Processing IDE](https://processing.org/download)

Processing application is visual arts-based software for learning to code. After downloading, extract the Zip file, and you will get the processing application (.exe file).

### Hardware

- Arduino

- Servo

- Ultrasonic Sensor

- Jumper Wires

- BreadBoard (Optional)

- Laptop

- Cabels

- Power Source (Optional, as Laptop Can power teh Arduino)


## Programs

In this project, we are using two codes: 

[Arduino Code (Arduino_radar_server_arduino)](https://github.com/Uniquely-Rare/Sonar/blob/main/Arduino_radar_server_arduino.ino): 

Sends sensor readings for every degree moved by the servo values sent to serial port to be picked up by Processing 


[Processing Code (Arduino_radar_client_processing)](https://github.com/Uniquely-Rare/Sonar/blob/main/Arduino_radar_client_processing.pde): 

Maps out an area of what the HC-SR04 sees from a top down view. Takes and displays 2 readings, one left to right and one right to left. Displays an average of the 2 readings


## Setup

### Circuit
![Circuit](https://user-images.githubusercontent.com/85011883/209829344-10cec55e-0650-459e-9775-925cc22ce3b0.png)

### Put it together
![Final Setup](https://user-images.githubusercontent.com/85011883/209829080-6b96d06e-78fb-4bf7-a732-21d12d48fa6d.png)

### Upload the code

After uploading the code, the servo motors start running from 0 to 180 degrees and again back to 0 degrees. An ultrasonic sensor also rotates along with the servo as it is mounted on the motor.

### Now, open the processing application. In the code, update the COM port number where your Arduino board is connected.

### Now, run this processing code. 

You will see a new window. This is the graphical representation of data from the Ultrasonic Sensor is represented in a radar type display.

### If an ultrasonic sensor detects any object within its range, you can see the same on the graphical representation. 


## Proof

Halfway:

![Halhway](https://user-images.githubusercontent.com/85011883/209829015-73ee07cb-e8c0-4608-b120-53a50b787720.png)


Intial Setup:

![Intial Setup](https://user-images.githubusercontent.com/85011883/209828923-991667cb-156d-4230-a676-8c8c48fec114.png)


Final Setup:

![Final Setup](https://user-images.githubusercontent.com/85011883/209829080-6b96d06e-78fb-4bf7-a732-21d12d48fa6d.png)


Video:

https://user-images.githubusercontent.com/85011883/209829146-1e093464-0015-4165-b210-3ea29417a67b.mp4


# References & Links

[Arduino](https://www.arduino.cc)

[Arduino Projects](https://create.arduino.cc/projecthub/projects/tags/arduino)

[Arduino IDE](https://www.arduino.cc/en/software)

[Processing IDE](https://processing.org/download)

For Hardware I (Indian) ordered it from: [Robu](https://robu.in) & [Amazon](https://www.amazon.in)

# Note

Project was 

created on 3rd of December'18

uploaded on 28th of December'22


