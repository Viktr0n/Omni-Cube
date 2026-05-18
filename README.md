# Omni-Cube

## Project Overview

The Omni-Cube is a gaming console with an omnidirectional Andotrope display. It is a final thesis project for upper secondary school that addresses the challenge of restricted viewing angles in traditional multiplayer gaming by providing a 360-degree display experience.

![Alt Text](https://keep.google.com/u/0/media/v2/1rRuee92HKxfslpUUs4ZNLDu9oBkvljGiVndKCTUIK2twPdt6G8o0fIWardHZ/1iH54a87PIjWAevOvEieSXOmdeeOdom81ootre0DaP0HGfwNgsEWxqKR9V78cPQ?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp)
![Alt Text](https://keep.google.com/u/0/media/v2/1fCYU1UYe79iMGhG4s65D34NhbWBB8XkzavM5xuTW0DpDS5HbLyDFt6ADdrcxYg/1ywns-az_59QnHjnidwVF2z1OPsLqZdcy0uPOkjU4V5b0Cd3CJrSDod-N1sok?accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Caudio%2Faac&sz=2048)
![Alt Text](https://keep.google.com/u/0/media/v2/1N4I7j_4k69fGnybG904-UOYAfOFImnZMkwaK2BxaP3jS3F8uSfGrmbXpNhrFcA/1XNUiikmUErNsfOmZq73UF0V3hnfq_CQ7hky1y3sadnlbBAllq0v7xVs1L6qy?accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Caudio%2Faac&sz=468)




## Hardware Components

- **Main Console**: Raspberry Pi 3 Model B running CircuitPython
- **Display**: RA8875 omnidirectional display with 360-degree image capability
- **Controllers**: Two handheld wireless controllers built with ESP32/ESP32-S3 using Bluetooth Low Energy (BLE)
- **Motor Control**: H-bridge controlled DC motor for display rotation
- **Chassis**: Custom 3D-printed PLA housing designed in Fusion 360

## Software Structure

- **OC_splashscreen.py** - Splash screen with project title and creator credits
- **OC_main_menu.py** - Main menu system with game selection and power control
- **OC_pong.py** - Pong game implementation with BLE controller support
- **OC_motorCode.py** - Motor control via PWM and GPIO
- **OC_controller_plr1.ino & OC_controller_plr2.ino** - Wireless controller firmware with BLE communication

## Features

- **Dual Wireless Controllers** - D-pad and A/B button inputs for two players
- **BLE Connectivity** - Seamless Bluetooth Low Energy communication between controllers and console
- **Power Management** - Automatic deep sleep modes after 2 minutes of inactivity
- **Expandable Game Architecture** - Easy-to-extend system for adding new games beyond Pong
- **Omnidirectional Display** - 360-degree viewing experience for multiplayer gaming

## Getting Started

The User_manual describes how to start the project, how to maneuver the main menu and the controlls for the Pong game. If you want to add more of your own games to the project, step-by-step instructions are also included in the User_manual

## Authors

- Oscar Bodenäs
- Victor Ekberg

## Technologies

- CircuitPython
- C++ (Arduino)
- Bluetooth Low Energy (BLE)
- RA8875 Display Controller
- Raspberry Pi GPIO Control
- Cad
- Fusion360
- 3DModels
- BambuStudio

##Circuit Diagram

![Alt Text](https://keep.google.com/u/0/media/v2/165WV1BjKDGqdecFQhjzCtpzGa7yx0QyUiTySv2LqYQE-854jEcqQMiNsLmVOiQ/14hbNCjL7yiByiodkNHeP_JIwQP0uFi-TWXgOFoQ5Df9YnDoWTwzWsu41WZ-Yrw?accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Caudio%2Faac&sz=1598)
![Alt Text](https://keep.google.com/u/0/media/v2/1c04vhMs-IdyRPl7VtjEtHBJcvvDUtWOR1U1ynSlyFuO_WiGvuzCegNs5DRPE/1IK7XZyBmojUs3ie0OJW_pI-PVrF5iJ8exE3JtrL5WaCi5YAZ-1dMkhECSp7p?accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Caudio%2Faac&sz=1562)
