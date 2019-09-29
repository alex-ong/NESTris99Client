NESTris99Client
===

Windows
=====

Calibration
===

Setup the target window:

1) First, open the window that you will capture (FCEUX or OBS).

2) Scale your application window to where you want it. **Since we capture the screen, any time you scale/stretch the window, the calibration will become invalid**. 

3) You can use Windows+arrow keys to position the window so it will lock to the side or quarter of the screen.

Double-click on `calibrate.bat`.

![calibration](https://github.com/alex-ong/NESTris99Client/blob/master/assets/doc/example-calibration.png)

Follow the steps in the picture:

1) Enter the first few characters of the window name. Your window should show up in the preview pane.

2) Enter your name 

3) Press auto-calibrate. The window should snap into place.

4) Check that the game window has been detected. If not, press auto-calibrate another 3-4 times. If that still doesnt work,
   use the +- buttons in "capture window coords" to get the game window.

5) Micro adjust so that the numbers are highlighted and the black regions are empty. You can repeat step 3 to get closer first.

6) Calibrate the field in the field tab. There are also two squares that refer to the statistics portion of the screen so that we can ascertain block colors.

7) Calibrate the next piece. Line it up with a T piece.


Running
===
Double-click `main.bat`

There isn't any output, a command prompt opens and sits there, streaming to the NESTris99 Server.
Check out twitch.tv/NESTetris99 to see if you pop up on stream.

