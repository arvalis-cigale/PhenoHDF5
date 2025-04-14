# PhenoHDF5
## PhenoHDF5 : A data structure for plant phenotyping measurements based on the HDF5 format

### This document proposes and presents the implementation of a single recording format to store all raw data from a multi-sensor phenotyping system.

Obtaining plant physiological characteristics by processing data from multiple sensors (cameras, LiDAR, spectroradiometers, anemometers, GPS, accelerometers, etc.) first requires the painstaking task of gathering and extracting the data. These data are traditionally stored in files of various formats, in different directories, and often require auxiliary data (GPS, weather, etc.), also stored in separate files, to be usable.
In order to integrate this preprocessing directly into the acquisition systems, the present document proposes and describes a single data file format, based on HDF5 technology, offering a way to combine all the data acquired by all the various sensors required on the same agricultural plot and providing an autonomous source for processing algorithms, as well as efficient data availability, by using sustainable and scalable write and read routines.
