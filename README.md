# DC Motor Speed Control in MATLAB/Simulink

This project models a separately excited DC motor under constant load torque and compares its open-loop response with a closed-loop PI speed controller.

## Project Overview

- Separately excited DC motor
- Constant load torque: 1.5 N·m
- Armature voltage: 24 V
- Field voltage: 12 V
- Reference speed: 600 rad/s
- PI controller gains: Kp = 0.035 and Ki = 0.015
- Armature voltage limited to 0–24 V

## Results

The open-loop model reaches approximately 697.7 rad/s. With PI control, the motor tracks the 600 rad/s reference and settles at approximately 599.4 rad/s. The steady-state armature voltage is about 20.7 V.

## Repository Contents

- `dc_motor_open_loop.slx` — open-loop DC motor model
- `dc_motor_pi_control.slx` — closed-loop model with PI speed control
- `dc-motor-speed-control-report-en.pdf` — concise English report
- `dc-motor-speed-control-report-fa.pdf` — complete Persian report

## Tools

MATLAB, Simulink, Control Systems

## Project Information

This work was completed as a three-person academic team project. This repository and its English documentation were prepared by Ali Sakhaei for portfolio presentation.
