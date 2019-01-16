# driving_scene_clip_content_selector

Application information

driving_scene_clip_content_selector_GUI v 1.0 (Jan 16th, 2019)

Christopher Donald Douglas Cabrall c.d.d.cabrall@tudelft.nl TUDelft Human Factors of Automated Driving

Software for selecting a video clip from an annotated library of driving video scenes. A total of 38,298 seconds of driving footage were annotated for their contents by around 200 crowdworkers from 46 countries. Users can get a short driving video clip (dash-cam view) with different specified contents. Users can select for different kinds of road users (cars, pedestrians, bicycles, motorcycles, etc.), road/infrastructure features (curved roads, single lane, with signage, etc.) and behavioral aspects (lane changes, turning on/off the road, slowing down, etc.). Segments can be saved to a user specified location as an .avi video file. The segments are parsed from 49 source video files (v01.avi, v02.avi, etc.) and are available online via youtube (search for user "Christopher Cabrall" and the playlist "Driving Scene Content Clips") An example for v14.avi is found at https://youtu.be/8QpGg6or7Iw

_________________________________
_________________________________
MATLAB Compiler

Prerequisites for Deployment
. Verify the MATLAB Runtime is installed and ensure you
have installed version ***X.? (R201?a/b)***.

. If the MATLAB Runtime is not installed, do the following: (1) enter

  >>mcrinstaller
  
  at MATLAB prompt. The MCRINSTALLER command displays the 
  location of the MATLAB Runtime installer.
(2) run the MATLAB Runtime installer.

Or download the Windows 64-bit version of the MATLAB Runtime for R2015b from the MathWorks Web site by navigating to

http://www.mathworks.com/products/compiler/mcr/index.html

For more information about the MATLAB Runtime and the MATLAB Runtime installer, see Package and Distribute in the MATLAB Compiler documentation
in the MathWorks Documentation Center.

NOTE: You will need administrator rights to run MCRInstaller.

Files to Deploy and Package
Files to package for Standalone

-nback_GUI.ctf (component technology file) -nback_GUI.exe -MCRInstaller.exe -if end users are unable to download the MATLAB Runtime using the above
link, include it when building your component by clicking the "Runtime downloaded from web" link in the Deployment Tool -This readme file

Definitions
For information on deployment terminology, go to http://www.mathworks.com/help. Select MATLAB Compiler >
Getting Started > About Application Deployment > Deployment Product Terms in the MathWorks Documentation Center.
