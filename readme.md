[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vxyPYWbJ)

# 2025 50.002 1D Project

# MoleDash

- A Whack-A-Mole inspired game implemented on FPGA using Lucid HDL \*

---

## Overview

**MoleDash** is a fast paced reaction game built on Alchitry Au FPGA board using Lucid HDL. It features real-time LED mole spawning, button input detection, dynamic scoring logic, and streak-based score multipliers.

---

## Game Description

- One random LED lights up at a time (representing a mole)
- Player must hit the corresponding button **before the timer runs out**
- Correct hit: score increases
- Incorrect or no input within time limit: **game over**
- After 5 consecutive correct hits, the "points per hit" value increases

---

## Features

- Finite State Machine (FSM) control logic
- Datapath integration with register file and ALU
- Button edge detection and debouncing
- Timer-based gameplay logic
- 7-segment display for real-time score display
- Random number generation for mole index
- Streak tracking and score multipliers

---

## Components Used

| Component          | Description                            |
| ------------------ | -------------------------------------- |
| Alchitry Au Board  | FPGA with 100 MHz clock                |
| Alchitry Io Shield | Interface for buttons, LEDs, 7-segment |
| RGB LED Buttons    | Used as both inputs and outputs        |
| Breadboard + Wires | Wiring for IO connectivity             |
| 7-Segment Display  | Display current score and timer        |
