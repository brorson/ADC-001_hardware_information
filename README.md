This directory holds information about hardware and usage aspects of the ADC-001 
cape for the Beaglebone.  

The ADC-001 is an A/D cape which can take data in either single-sample or in multiple
sampled data mode.  It is designed to work with microphone-level input
signals; the cape includes a high-gain mic amp which brings the input
signal level up to the magnitude required for sampling by an A/D
converter.  The frequency response of the circuit runs from 50Hz -- 15kHz, so
the unit is well-suited for voice or audio signal processing applications.  A more
complete description of the cape is presented in the document 
https://github.com/brorson/ADC-001_hardware_information/blob/master/ADC-001_Description.pdf
held in this directory.  

A companion directory holds the drivers and example code showing how to use the cape:
https://github.com/brorson/ADC-001_basic_code.  A brief user's guide may be found in 
the present directory under 
https://github.com/brorson/ADC-001_hardware_information/blob/master/UsingtheBeaglebone.pdf


The ADC-001 cape will be available for purchase in the near future.

Stuart Brorson  
4.29.2017  
sdb AT cloud9.net  
