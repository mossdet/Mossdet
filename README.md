# Mossdet
MOSSDET Readme

For any questions please contact us at daniel.lachner@uniklinik-freiburg.de.

Instructions:

1.Copy these files to the same folder
	- MOSSDET_2.0.exe 
	- svm_ripple.dat
	- svm_fr.dat
	- svm_ies.dat
	- svm_spindle.dat

2.If the executable file fails to run on your computer, you will need to install the run-time components of the Visual C++ libraries and .Net Framework.
	- You will find the installer for Microsoft Visual C++ Redistributable(2017) under VC_redist.x64.exe
	- You will find the installer for the .Net Framework under dotNetFx40_Full_setup.exe

	


	
	
	
	
User instructions:

1. Currently only EDF files are allowed.
2. The shortcut Ctrl+A selects all channels
3. After MOSSDET 2.0, the following values have been made configurable:
	- define length of the epochs being processed periodically
	- select NUMA node to run MOSSDET
	- define the percentage of the logical processors to be used to run MOSSDET
