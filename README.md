# NTE-Auto-Fisher
An auto fishing script using bash and xdotool. Made for Neverness to Everness and 1920x1080 displays.

# Warning
This script may or may not get you banned from the game.

I do not claim responsibility if it does as you're the one responsible for your own account and actions 👍

# Requirements
If you're on Windows, find `xdotool` command line thing that will let you run `xdotool` in terminal

If you're on Linux, everything works perfectly as I coded this on Linux/Ubuntu.

# How to run
I believe for Windows you just double click it and it should run automatically.

As for Linux, make sure to give permission to run as program or head to terminal and use `bash autofisher.sh`

After it opens, you have 4 seconds (can be changed) to tab back into NTE before it starts doing its actions and looping.

# Important
If you're not on a 1920x1080 display, this script may not work perfectly. 

If you aren't on a 1920x1080 display, use `xdotool getmouselocation --shell` in terminal, to determine the location of your cursor and replace the following lines of code:

```bash
xdotool mousemove 1631 948 #location of the "Start Fishing" button
xdotool mousemove 72 988 #location of your chat button
```
