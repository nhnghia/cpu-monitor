# cmon
Cpu monitor using bash script. It has been tested on Ubuntu 14.04.

# Install

Download `cmon` then put anywhere you want, e.g.,

`wget -0 cmon https://raw.githubusercontent.com/nhnghia/cpu-monitor/master/cmon && chmod +x cmon`

# Run

### Show total cpu usage of your machine:
`./cmon`

### Show cpu usage of one program:
`./cmon prog1`

### Example:

```
./cmon
CPU usage:  1% (Thu Mar 23 15:50:56 CET 2017)             
20  ..........||............||||||||||...........................
16  ..........||....|.......||||||||||...........................
12  ..........||...||.......||||||||||...........................
8   ......|...||...||.......||||||||||...........................
4   ......|...||...||.......||||||||||...........................
0   ||||||||||||||||||||||||||||||||||||||||||||||||.............
    0        10        20        30        40        50        60
```
