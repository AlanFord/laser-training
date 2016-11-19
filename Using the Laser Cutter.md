#Using the Laser Cutter
1. **PRESS** in the red E-stop button on the front of the laser cutter.
2. **ENSURE** the laser cutter is turned off.
3. **CLEAR** debris, chairs, and material from the work area around the laser cutter.
4. **CLEAR** debris and unwanted material from the laser cutting bed.
5. **PUT ON** laser safety glasses.
5. **TURN ON** the computer connected to the laser.
6. **LOG IN** to the computer.
7. **INSERT** USB flash drive containing your g-code into the computer.
8. **START** MACH3.
9. **LOAD** gcode file by pressing the "Load G-code" button.
9. **TURN ON** the switch the controls the laser cutter, ventilation, and cooling systems.
10. **SELECT** "NORMAL" on the Input Signal toggle switch on the top of the laser cutter.
11. **PRESS** the MACH3 RESET button.
12. **HOME** the laser by pressing the "Ref All Home" button.
16. **PRESS** the “tab” key to bring up the virtual pendent (so you can jog/move the laser cutting head).
13. **LOWER** the bed to permit loading the material stock.
14. **MOVE** the cutting head to the rear of the bed to permit loading material stock.
15. **PLACE** the material stock on the cutting bed, but DO NOT knock the laser cutting head.
17. **RAISE** or LOWER the cutting bed such that the top of your workpiece is 70 mm below the top of the laser carriage (the larger moving aluminum plate). An easy way to set the cutting bed height is to use the height gauge, which is the wooden paint stirrer with blue painters tape marking 70 mm. Getting this pretty close to 70 mm is important in preventing fires (usually caused by an out-of-focus beam).
18. **MOVE** the laser cutting head to the X,Y position over your stock material where you wish the CamBam machining origin to be located.
19. **ZERO-OUT** the X, Y, and Z coordinates in Mach3 by pressing the "Zero X", "Zero Y", and "Zero Z" buttons on the Mach3 screen.
20. **SET** the laser power as needed using the power knob on the top of the laser cutter.  Consider using 0% power for a test pass to verify proper positioning of material.
21. **IF** a problem occurs while cutting **THEN** press “RESET” on the screen, especially when first starting, in case something is wrong.
22. **RELEASE** the E-stop button on the front of the laser cutter by gently twisting the button to the right until it releases.
16. **PRESS** the “tab” key to re-hide the virtual pendent.
23. **PRESS** “Cycle-Start” button on computer screen in Mach3 to begin cutting routine.
24. **WAIT** for the cutting cycle to complete.  **DO NOT** leave the area.
25. **PRESS** in the red E-stop button.
16. **PRESS** the “tab” key to bring up the virtual pendent (so you can jog/move the laser cutting head).
26. **MOVE** the laser cutting head away from the work piece to remove your work without bumping the cutting head.
27. **IF** another cut is desired, **THEN** press the "Rewind Ctrl-W" MACH3 button and **GOTO** Step 20.
28. **SHUTDOWN** the laser cutter by turning off the power director.
29. **REMOVE** any material stock that remains in the laser cutter.
30. **SHUTDOWN** the PC.
