# Tasks
1) Task 1: Flash an external LED for 250 ms every 1 second. (e.g. ON for 250ms, OFF for
750ms).
2) Task 2: Make the speaker emit the beginning of the Mario theme song (see Appendix) or
a short theme song of your choice using the hardware timer techniques from Lab 2. If
you choose your own please play something different from Mary had a little lamb. Task 2
should play the song and then sleep for 4 seconds, then play the song again. Directly
manipulate timers to generate the signal, do not use Arduino’s tone() function.
3) Task 3: Make the 7-Segment LED display (info below) count up by 1 unit every 100 ms.
4) Task 4: After you demo tasks 1-3, Task 4 is a new task that combines and modifies
tasks 2 and 3 as follows. While no music is being output, make it so the 7-segment
display indicates a countdown in 10ths of a second until the next time the theme is
played (check the HINT below). During the music, display the frequency (in decimal
Hz.) of the current tone on your 7-Segment display. (your code doesn’t have to measure
the frequency, you have it in your code somewhere).
5) Task 5: This task will be a supervisor that starts and stops other tasks. Perform the tasks
according to this schedule:
a) Task 1 runs all the time.
b) Task 2 runs at the start but stops after playing the theme 2 times.
c) After Task 2, start a count-down (on the 7-segment display) for 3 seconds
and then restarts task 2 (original definition above) for one final time.
d) Display a “smile” for 2 seconds (See Appendix B) (code this as a new task to be
controlled by Task 5). The 2 second interval begins after completion of part 5c.
e) Stop all tasks, except “a) Task 1” in this list.
