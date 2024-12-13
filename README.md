# Embedded Scheduler 

This project explores microcontroller programming, task synchronization, and scheduling strategies using the Arduino Mega microcontroller in real-time. It demonstrates how to manage multiple concurrent tasks while integrating exteral elements including a speaker, LED's, and a seven-segment display.

## Objective
The primary goal was to implement and compare different scheduling strategies to understand their trade-offs and effectivness in embedded systems.

This project runs several simultaneous tasks such as:
1) A round-robin (RR), non-preemptive scheduler
2) A RR scheduler using function pointers and timer
synchronization, and a sleep() function.
3) A scheduler using Task Control Blocks (TCBs) for each task.
4) A simple Interrupt Service Routine (ISR) and use it to get hardware precision
for your scheduler cycle synchronization


## Hardware Components:
1) Arduino Mega Microcontroller board
2) External Arduino power supply
3) LEDs and 250 Ohm resistors
4) Small 8-Ohm Speaker
5) 4-digit 7-segment LED display
