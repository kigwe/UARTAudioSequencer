# UART Audio Sequencer
# Project: CPE 316 Design Project
# Members: Kelechi Igwe, Reed Slobodin, Brandon Nowak
 
Description
The UART Audio Sequencer is an embedded system that allows a user to play a sequence of notes through the use of a MSP432 microcontroller, input and output peripherals, and a Python GUI. This project was our final project for CPE 316: Microcontrollers and Embedded Systems, a course offered at Cal Poly SLO. Inside of this repo, you will find instructions on how to get the program running on your system with the files provided. In addition, you will find the report for this project that provides technical documentation about the system. (Note: This project is not active/expected to receive any updates in the future)

Requirements
(See Documentation for Specific Hardware Requirements)
We have not tested this program with other microcontrollers or peripherals, so for the best result we suggest using the hardware we used to build the system.

Instructions
(Optional #1) Read FinalReport.pdf
1) Download and Install Code Composer Studio (CCS) (used to load .out file onto MSP432 Microcontroller)
2) Unzip the compressed folder "UART Audio Sequencer" in the python folder in this repo
3) Connect microcontroller to computer and connect wires to correct locations (see PinSetup.pdf)
4) Open .ccxml file (located in ccs folder in this repo) in Code Composer Studio
5) Run the debugger with the .ccxml file as the target
6) Once Debug started, select Run->Connect Target
7) After connection to target established, select Run->Load->Load Program and select final_proj.out from ccs folder in this repo
8) Run UART Audio Sequencer.exe in dist folder that was created from UART Audio Sequencer.zip
9) Enter Port Name and Baud Rate (Help for port name and baud rate is available in program)
10) Enjoy!

Demo Link: coming soon :)
