# driving_scene_clip_content_selector

Application information

driving_scene_content_video_clip_selector_GUI v 1.0 (Jan 16th, 2019)

Christopher Donald Douglas Cabrall c.d.d.cabrall@tudelft.nl TUDelft Human Factors of Automated Driving

Software for selecting a video clip from an annotated library of driving video scenes. A total of 38,298 seconds of driving footage were annotated for their contents by around 200 crowdworkers from 46 countries. Users can get a short driving video clip (dash-cam view) with different specified contents. Users can select for different kinds of road users (cars, pedestrians, bicycles, motorcycles, etc.), road/infrastructure features (curved roads, single lane, with signage, etc.) and behavioral aspects (lane changes, turning on/off the road, slowing down, etc.). Segments can be saved to a user specified location as an .avi video file. The segments are parsed from 49 source video files (v01.avi, v02.avi, etc.) and are available online via youtube (search for user "Christopher Cabrall" and the playlist "Driving Scene Content Clips") An example for v14.avi is found at https://youtu.be/8QpGg6or7Iw Additionally, these will be uploaded to the free online research respository of Zenodo at doi:10.5281/zenodo.2542275

PLEASE NOTE: IN ORDER TO PREVIEW THE SEGMENTED VIDEO CLIP IN THE GUI, YOU MUST SAVE THE 49 SOURCE VIDEOS (v01.avi, v02.avi, etc.) IN THE SAME FOLDER AS THE .EXE (driving_scene_content_video_clip_selector_GUI.exe).



_________________________________
_________________________________
MATLAB Compiler

1. Prerequisites for Deployment 

Verify that version 9.3 (R2017b) of the MATLAB Runtime is installed.   

If the MATLAB Runtime is not installed, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.

Alternatively, download and install the Windows version of the MATLAB Runtime for R2017b 
from the following link on the MathWorks website:

    http://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
Package and Distribute in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.    

NOTE: You will need administrator rights to run the MATLAB Runtime installer. 


2. Files to Deploy and Package

Files to Package for Standalone 
================================
-driving_scene_content_video_clip_selector_GUI.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime downloaded from web" link in the
    Deployment Tool.
-This readme file 

3. Definitions

For information on deployment terminology, go to
http://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.
