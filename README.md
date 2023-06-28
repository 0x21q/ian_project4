# Binary Code Analysis - Project 4
The STAP script calculates the runtime and hardware interrupt statistics of the process provided in the first argument each 5 seconds, aswell as printing specific syscalls each time they are called. The script was tested and implemented on the kernel version 4.18.0-348.12.2.el8_5.

## Example
```txt
$ sudo stap process_stats.stp stress

Scheduling stats:
CPU  PID     run (%)  hrtimer(ms|%)  comm
0    158707  98       12171          stress
1    158708  99       10243          stress

```