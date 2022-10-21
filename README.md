# ese5190_lab2B_proposal

  Written by Shu Xu
  
  Email: shux@seas.upenn.edu
  
This is a brief proposal regarding the outline of Lab2B.

## Breadboard LED in action

In this part, we are have built an on-board LED connected to GPIO A0 of QT PY Board, and it blinks every 0.5s as shown below:

![Alt txt](https://github.com/shux3/ese5190_lab2B_proposal/blob/main/media/LED_breadboard.gif)

## Design

There's one soft goal and one hard goal of this plan.

### Hard Goal
  
  A traffic light system that can be controlled through serial connection. This system simulates a real life traffic light that swicthes among green, yellow and red.
  
### Soft Goal
  
  Now, imagine that this traffic system is installed at a railroad crossing point. There are two more features added to the system when train is approaching:
  
  1. The traffic light would jump out of its current state and switch to yellow, then red to stop vehicles.
  2. A traffic stopper controlled by servo motor would be dropped to stop vehicles.
  
### Summary of design

This project is cool for me since it is designed based on real life applications. As I have never worked with servo motor before, I would like to give it a try. The main purpose of setting a hard goals is to ensure a high degree of completion, and the the purpose of the soft goal is to seek more chanllenges after completing the soft goal.

## Components

For soft goal:
- Laptop
- QT PY RP2040 board
- **3 LEDs :Red, yellow and green**

Add-ons for hard goal:
- APDS 9960
- **Servo Motor**

## Questions regarding to this lab

Q1: I'm using the GPIO A0 pin directly instead of the four pin male headers cable. Sometimes the connection is not quite stable. I'm wondering if there's a way to stablize the connections.

Q2: Can use GPIO A0 - A3 and male header cable at the same time? Does it make the avaliable GPIO up to 6 in total?
