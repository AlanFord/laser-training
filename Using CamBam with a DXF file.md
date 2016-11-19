#Using CamBam with a (LASER) DXF file
1. **START** CamBam on the 3DDesign workstation.
2. **LOAD** the DXF file using the "File->Open" menu sequence.  If necessary, make sure the file type drop down is set to "All Geometry Files".
3. **VERIFY** the drawing is complete (some features may not have been saved in the DXF file).
3. **SET** the machining origin using the following sequence:
	* **RIGHT CLICK** on "Machining" in the Drawing Tree View.
	* **SELECT** "Set machining origin".
	* **SELECT** the appropriate location for the machining origin in the Main Drawing Window.  It is recommended that the machining origin be located at the lower left corner of your part unless your needs dictate otherwise. 
4. **CONFIGURE** CamBam using the following sequence:
	* **SELECT** "Machining" in the Drawing Tree View.
	* **SELECT** "Post Processor" in the Object Property Window (lower left corner of the screen).
	* **SELECT** "Laser-HackRVA" from the Post Processor drop down list.
	* **SELECT** "Style" in the Object Property Window.
	* **SELECT** "laser" in the Style drop down list.
4. **SELECT** the objects to be lasered:
	* **CTRL+click** can be used to select multiple objects, one by one.
	* **CTRL+A** will select all visible objects.
	* **DRAGGING** the left mouse button will select multiple objects, but the objects selected must be completely inside the rectangle.
5. **SELECT** the red "Engrave" icon on the Tool Bar.  This will create "Part 1" and "Engrave 1" in the Drawing Tree View.
6. **GENERATE** a toolpath using the following sequence:
	* **RIGHT CLICK** on the "Engrave 1" machining operation in the Drawing Tree View.
	* **SELECT** "Generate Toolpaths" from the pop-up menu.
7. **GENERATE** a gcode output file using the following sequence:
	* **RIGHT CLICK** on the "Engrave 1" machining operation in the Drawing Tree View.
	* **SELECT** "Produce gcode" from the pop-up menu.
	* **SAVE** the gcode file in a location of your choice.  *Do not change the ".nc" file extension!*


