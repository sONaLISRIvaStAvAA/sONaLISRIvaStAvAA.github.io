---
layout: post
title: Air Bling – Arduino Ping Pong Reaction Game
description: >
  A two-player Arduino-based reaction game featuring LEDs, push buttons,
  an I2C LCD scoreboard, adjustable speed via potentiometer, and retro
  sound effects. Designed to improve understanding of timing control
  and real-time embedded systems.
skills:
  - Arduino
  - Embedded C++
  - Tinkercad
  - I2C LCD
  - Embedded Systems
main-image: /assets/images/profile-image/pinpong.png
---

## Overview
Air Bling is a two-player reaction-based Ping Pong game built using
Arduino Uno. The project focuses on real-time user interaction,
precise timing control, and embedded logic design through a fun,
game-based approach.

---

## Problem Statement
Beginner embedded projects often lack interactivity and real-time
decision-making. This project was designed to create an engaging
system where timing accuracy, response speed, and hardware-software
coordination are critical.

---

## Hardware Components
- Arduino Uno  
- LEDs  
- Push Buttons  
- I2C LCD Display  
- Potentiometer  
- Buzzer  
- Breadboard and connecting wires  

---

## Software & Logic
- Arduino was programmed using Embedded C++
- Button inputs were debounced to avoid false triggers
- Game speed was dynamically controlled using a potentiometer
- I2C communication was used to display scores on the LCD
- Sound effects were generated using a buzzer for feedback

---

## Working
1. LEDs represent the movement of the ball between two players.
2. Players press their respective buttons to return the ball.
3. Correct timing returns the ball to the opponent.
4. Incorrect timing results in a missed hit and score update.
5. Game speed increases progressively to increase difficulty.
6. Scores are displayed in real time on the I2C LCD.

---

## Results
- Smooth real-time gameplay with accurate button response
- Reliable I2C communication with the LCD
- Stable speed control using analog input
- Successful simulation and testing in Tinkercad

---

## What I Learned
- Timing control in embedded systems
- Button debouncing techniques
- I2C protocol implementation
- Designing interactive embedded applications
- Debugging real-time hardware behavior
