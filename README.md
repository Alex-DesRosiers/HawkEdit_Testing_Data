This directory contains all testing data being actively used to evaluate new releases of the Hawk Edit radar editing software being developed at NCAR as part of the Lidar Radar Open Software Environemnt (LROSE). More information on LROSE can be found at "lrose.net".

The "CHIVO" directory contains data collected by the CHIVO radar as part of the PRE-CIP field campaign in 2021. This data serves to test editing capabilities on ground-based research radars of smaller domain size.

The "DOW" directory contains one sample scan from truck-borne radar to ensure that basic editing functionalities work on this platform with each new release. The scan was provided by Paul Markowski and is data from a tornadic supercell observed in Goshen County, WY during VORTEX2.

The "NEXRAD" directory contains radar volumes collected by the KEVX radar in the Florida Panhandle during Hurricane Michael. The scans were quality controlled and provided for testing by Ting-Yu Cha who used this data in "Polygonal Eyewall Asymmetries during the Rapid Intensification of Hurricane Michael (2018)" which is published in Geophysical Research Letters. "NEXRAD_Trim" contains a smaller subset of these files to cut down the data amount and speed up testing of the application.

The "TDR" directory contains fore and aft scans collected by the NOAA P-3 tail Doppler Radar in Hurricane Michael. These scans contain quality controlled fields which were produced during the study detailed in "Vertical Vortex Development in Hurricane Michael (2018) during Rapid Intensification" which is published in Monthly Weather Review. This data serves to ensure the application can handle data from airborne radar.

The "NavCorr_Test" directory contains an aft and fore scan from the Hurricane Micheal dataset which have not had navigation corrections applied to the Doppler velocity field "VEL". Correction factors which start with "cfac" were produced for this dataset using the method outlined in Cai et al. (2018) published in the Journal of Atmospheric and Oceanic Technology. The "Reference_Material" directory contains information about how to use these corrections in a previous radar editing software (Solo), as well as sample output to compare results from this program against.

This repository is created and managed by Alex DesRosiers while working with the LROSE team at CSU and is used to test software releases made available in the lrose-HawkEdit repository at "github.com/NCAR/lrose-HawkEdit".
