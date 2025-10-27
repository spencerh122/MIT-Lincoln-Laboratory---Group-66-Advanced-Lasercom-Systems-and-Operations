# MIT Lincoln Laboratory, Group 66: Advanced Laser Communication Systems and Operations
## Pointing, Acquisition, and Tracking (PAT)

Author: Spencer Hart<br>
Program: MIT Lincoln Laboratory - Summer Research Program Internship<br>
Project: Motor Control for PAT Development

This repository includes the PDF presentation displaying/explaining the project, as well as videos from within the presentation (original format was PowerPoint, which allowed for in-presentation video playing, but the file was too big for GitHub). The videos can be found within the folder "Videos from presentation".

The goal of this project was to gain control of COTS (Commercial, Off-The-Shelf) motors to improve the pointing accuracy of a star tracker gimbal system.

Two approaches were taken: 1) FPGA development and 2) COTS servo driver development.<br>
The PDF presentation highlights each approach.

The hardware utilized include:

- Xilinx/AMD Zynq ZCU104
- L298N H-bridge
- Brushed DC motor with a 6-pin optical, incremental encoder
- Elmo Motion Control Evaluation Board (Whistle, Bell, Guitar support)
- AM26LS31 single-ended to differential quadrature converter IC

The software utilized include:

- Xilinx/AMD Vivado Design Suite
- Xilinx/AMD Vivado Lab
- Elmo Composer
- Matlab (for plotting Elmo Composer data)
