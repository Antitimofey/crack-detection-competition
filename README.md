# Intro
## Brief decsription
This is the repository of the team ***"Bauman Bumbulbes"*** that participated in the  all-russian competitions robotics hardaton "engineering challenge". After field trials and presentation our robot to experts and engineers form Sber, Moskow Metro, Federal Center for Building Control and professors of several universities we ***won the 2-d place***.

## Goal
The goal is desine, build and programm mobile robot for build inspections. Functonal: autonomous detection and classification defects on concreate surfaces and informing the building inspector about found defects.

## Сomposition of the team
- Konstantin Kudryavcev: Team Captain, Programmer
- Timofey Antipov: programmer
- Egor Covalenko: engeneer, designer
- Pavlenko Daniil: engeneer
- Nikita Sharapov: designer


# Hardware: robot construction
## 

# Software:
For detection and classification concreate defects we trained *YOLO-v8 model*. All pipeline described below:
- Raspberry Pi 5 compress image from robot camera and transmit it to server.
- Server process received image.
- In case of defects on image, server crop it and sent when with according messange to building controllers using telegramm API.
- 



## High-Level Software









