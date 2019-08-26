# Rapid Prototyping of Simple Optical Elements for the Terahertz Domain
By [Christian Buhl Sørensen](https://vbn.aau.dk/en/persons/139637), [Anders Faarbæk Mikkelstrup](https://vbn.aau.dk/en/persons/143999) and [Esben Skovsen](https://vbn.aau.dk/en/persons/113858).

This repository provides easy access to the supporting content of the poster presented on the IRMMW-THz conference in Paris, 2019. The entire repository is supplied as inspiration and a starting point. You are exceedingly welcome to fork and extend the work shown here.

I do not guarantee the longevity of the information provided here, so if you like it - fork it! :dancer:


## Contents

The repository contains the poster (RapidPrototyping.pdf), a folder with the data analysis for the dimensional qualification, as well as a folder with STL sample files. Furthermore the repository contains supporting documentation such as this readme file, the license under which it is published, and images for the tacky tack-on badge.


## STL sample files
The STL files folder contains three relevant files as of now:
 - **45degMountV1.stl**: The mounting element for the V1 of the mirrors. Note that the angles on the mirror interface are not compatible with the V2 mirror.
 - **d100mm_efl150mm_V1.stl**: Version 1, a simple model of an off-axis parabolic mirror. 
 - **d100mm_efl150mm_V2.stl**: This version does not print well. The added reference cut-outs are an absolute godsend during alignment, and should be included on all coming designs, but the ribs on the backside are not functional. It is more relevant to print at a lower infill, to save weight at the end. Or just not print the ribs. Furthermore, the angles on the mating surfaces does not match up with the V1 mount.
 
 
## Data analysis for the dimensional qualification
The folder contains two notebooks, and an exported binary file describing the error in motion referenced to the best fit plane. 
 
 - **20190815 Fitting Flat Plane.ipynb** shows the fit procedure and estimates the error in measurement of a flat plane.
 - **20190816 OAPM fit.ipynb** shows the fit procedure to the theoretical polynomial.
 
Note that the data analysis is just that - don't expect beautiful, lucid code. I'm more than willing to answer questions that you may have, but note that the data analysis is added just for reference.
