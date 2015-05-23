# LoT - The Laser Object Tracker
Welcome to the official repository for the LoT Project.
This project is distributed under the GNU General Public License v2.

LoT is an embedded system designed to automatically detect, track and point a ball using a Raspberry Pi camera and servomotors.

![alt tag](https://cloud.githubusercontent.com/assets/10380160/7783143/504711e2-0137-11e5-8733-c315ee710671.jpg)

It was created for ARM architecture processors such as the Cortex A7, but it is possible to compile the C++ code to another one.

Two librairies are used:
- OpenCV
- RaspiCam

They are open source.

The system is composed by:
- A Raspberry Pi B to detect and command servomotors
- A Raspberry Pi Camera to take screenshots of the environment
- A home-made electronic circuit to adjust the power
- A laser to point the ball
- 2 servomotors which control the x and y axis.

----------
@BTR team.
