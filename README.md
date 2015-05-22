# LaserObjectTracker
Welcome to the official repository for the LoT Project.
This project is distributed under the GNU Public License v2.

LoT is an image processing embedded system designed to automatically detect, track and point a ball using a Raspberry Pi camera and servomotors.

It was created for the ARM architecture, but it is possible to compile the C++ code to another one.

Two librairies are needed :
- OpenCV
- RaspiCam
They are open source.

The system is composed by :
- A Raspberry Pi B to detect and command servomotors
- A Raspberry Pi Camera to take screenshots of the environment
- A home-made electronic circuit to adapt the power
- A laser to point the ball
- 2 servomotors which control the x and y axis.

----------
@BTR team.