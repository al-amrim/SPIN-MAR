# SPINMAR
# SPINMAR
Name
The Sensor Physiotherapy Intervention Movement Analysis Report (SPINMAR)

Description
SPINMAR is a MATLAB based custom toolkit that might be of interest to individuals who would like to generate a movement analysis report for lower limb joint kinematics. The original MATLAB code was written by Dr Jennifer Davies (daviesj@cardiff.ac.uk) during her postdoctoral work within the Biomechanics and Bioengineering Research Centre Versus Arthritis and School of Healthcare Sciences at Cardiff University. The code was converted into an executable function and checked by Dr Mohammad Al Amri (Al-AmriM@cardiff.ac.uk), Biomechanics and Bioengineering Research Centre Versus Arthritis and School of Healthcare Sciences, Cardiff University. 
SPINMAR will load .mvnx files containing human motion capture data that have been collected with and exported from MVN Analyze software (Xsens Technologies B.V., Enschede, The Netherlands). SPINMAR will load, process, and present the kinematic data in a visual and easily accessible pdf report. Details of the processing performed and the final report can be found in [provide reference to paper].
SPINMAR is capable of processing and reporting data from the following tasks: walk; double-leg squat; single-leg squat; jump; stairs ascent; stairs descent. Not all tasks need to be performed. Each task should be contained within a separate file. There can be more than one file for each task. Each file should contain data from only one task, but multiple repetitions of the task are permitted and encouraged. 
Example mvnx files are provided in the Demo_MVNX folder for two walk trials and one double-leg squat trial. The application can be run using these demonstration files.
Other required installations:
To run the script,  ghostscript (version gs9.27) should be installed and this can be found on this link: https://www.ghostscript.com/download/gsdnld.html
Once the ghostscript is installed  copy the gs9.27 folders into the following path 
               C:\Program Files\MATLAB\R20XXX\sys\ghostscript\gs9.27

Cite the SPINMAR application: 
Davies JL, Button K, Al-Amri M. The Sensor Physiotherapy Intervention Movement Analysis Report (SPINMAR), v1.1, Zenodo, doi:10.5281/zenodo.5574187 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5574187.svg)](https://doi.org/10.5281/zenodo.5574187)



