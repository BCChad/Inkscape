# Inkscape extension for Raster2Laser

 - Raster 2 Laser GCode generator
 - 
 
#Descriptions
- Raster 2 Laser GCode generator is an extension to generate Gcode for a laser cutter/engraver (or pen plotter), it can generate various type of outputs from a simple B&W (on/off) to a more detailed Grayscale (pwm)

#Changes/enhancements to 305 Engineering baseline version
- This is for Inkscape versions BEFORE V1.0 (producing a version compatible with V1.0 is my next plan of action)
- Added additional resolutions of 3 and 4 Pixels per mm
- Added function to include G00 feedrate
- Added function to include G04 DWELL command for pre- and post-burn
- Added function for grayscale images to scale "S" intensity to the effective range of the laser - (problem - small values of S that do not "print" are scaled up; high values of S that cause excessive scorching are scaled down)
- Modified the .INX file to use PAGES because of the additional parameters I added.
- Updated many comment lines from Italian to English for my purposes - Apologies to the original author
- Much respect to the "Beer License" of the original author - I enjoy beer, but also Espresso!


#Installing:

Simply copy all the files in the folder "Extensions" of Inkscape

>Windows ) "C:\<...>\Inkscape\share\extensions"

>Linux ) "/usr/share/inkscape/extensions"

>Mac ) "/Applications/Inkscape.app/Contents/Resources/extensions"


for unix (& mac maybe) change the permission on the file:

>>chmod 755 for all the *.py files

>>chmod 644 for all the *.inx files



#Usage of "Raster 2 Laser GCode generator":

[Required file: png.py / raster2laser_gcode.inx / raster2laser_gcode.py]

- Step 1) Resize the inkscape document to match the dimension of your working area on the laser cutter/engraver (Shift+Ctrl+D)

- Step 2) Draw or import the image

- Step 3) To run the extension go to: Extension > 305 Engineering > Raster 2 Laser GCode generator

- Step 4) Play!




#Note
I have created all the file except for png.py , see that file for details on the license
