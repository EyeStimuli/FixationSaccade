Dear Fellow Eye Tracker, 

Thank you for choosing eyeStimuli. 

This program is for running experiments that use on-screen textual stimuli such as text or ASCII art. 
The setup comes with a HELLO WORLD example but you can add in your own stimuli as *.txt files. 

Here are the instructions on how to use the program:

1. Download eyeStimuli code and build it using Visual Studio. 
-or-
To just run the program go to:
     https://github.com/EyeStimuli/FixationSaccade/tree/master/FixationSaccade/bin/Release 
2. In the bin/Release/Slides folder, copy slide 1, 2, and 3 how many times you need. The text files 
   can be called anything and are displayed in alphabetical order
3. Add in your own stimuli text or ASCII Art! 
4. Run bin/Release/FixationSaccade.exe
5. Enter your participant code if you have one, default is 18. This sets the prefix for the log files.
6. Load Tobii to connect to your eye tracker. Supports all Tobii eye trackers but only tested with my Tobii EyeX.
7. Click Calibrate and perform the calibration. 
8. After calibration, click begin 
9. Use the arrows to cycle through the slideshow.
10. At the end of the experiment, press Stop Recording
11. And then click Save Data.
12. Check bin/Release/Logs/ for your gaze data.

Please report any bugs to (me) the developer. I hope you enjoy using eyeStimuli! 

Happy tracking,
EyeStimuli

PS Due to accidental publishing of sensitive infomation through github (doh!) I had to nuke the 
codebase and start again. This time I've called the repo FixationSaccade instead of eyestimuli, which hopefully
is less confusing since that was also my username. 
