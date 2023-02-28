# ImageJ-automation-macro
A simple macro was written using the record function of ImageJ to automate tedious and repetitive image analysis steps

Macro.ijm.ijm.ijm - A basic first iteration code written for JC1 experiment. Used to analyze confocal images of cells treated with JC1 dye. Healthy mitochondria is stained red and stressed mitochondria is stained green. The macro opens the file, splits channels and once ROIs are selected, measures the values from red channel and green channel, and saves it in an excel sheet. 

Further iterations of the code include a for loop that repeats the steps until a specified number at the start of the macro.

Triple.ijm - Written for a triple co-localization experiment. Used to analyze confocal images of cells treated with 3 different antibodies that excite and emit at Red, Green and Blue (555, 488, 405 nm respectively) and their colocalisation. The macro opens the file, splits channels, open each channels and sets the brightness to "Auto" and creates a new TIFF file with only Red & Green. Minor changes could be made to create TIFF image with combination of other images as well

A classifier model was developed using the "Trainable weka segmentation" option available in ImageJ to distinguish cell and non-cell
