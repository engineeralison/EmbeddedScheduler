# Embedded Scheduler 

This project's objective was to increase our understanding of the Arduino Mega microcontroller by emphasizing task synchronization and scheduling strategies. We looked at how to effectively handle several jobs while managing external elements including a speaker, LEDs, and a seven-segment display.

We worked around implementing a Round-Robin (RR), Synchronized Round-Robin with Interrupts (SRRI), and a Data-Driven Scheduler (DDS) with Task Control Blocks (TCBs) were the three scheduling strategies that were implemented in this lab. Programming the Arduino to flash LEDs, using timers to create a melody, displaying figures on a 7-segment display, and using hardware interrupts to synchronize operations were some of the main activities. To start and stop other processes dynamically, we also created a supervisor task.

This project runs several simultaneous tasks such as:
● Implement a round-robin (RR), non-preemptive scheduler
● Implement a RR scheduler using function pointers and timer
synchronization, and a sleep() function.
● Implement a scheduler using Task Control Blocks (TCBs) for each task.
● Implement a simple Interrupt Service Routine (ISR) and use it to get hardware precision
for your scheduler cycle synchronization


Equipment:
1) Arduino Mega Microcontroller board
2) External Arduino power supply
3) LEDs and 250 Ohm resistors
4) Small 8-Ohm Speaker
5) 4-digit 7-segment LED display
