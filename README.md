# On-Road Air Pollution Monitoring and Signal Processing
In-situ measurements and signal processing are critical to identify highly polluting vehicles. A combination of wavelet transformation, peak area calculation and emission factor estimations were used in conjunction ALPR to track trails of high polluting vehicles.

# Development Environment and Workflow
The notebooks were developed using Python 3.7.1 on a Windows system and Anaconda python environment. 

 Tools and Packages
1. Numpy
2. Pandas
3. Matplotlib
4. SciPy Signal processing
5. Pywavelet
6. SciPy Stats
7. Scikit Learn

This Gitrepository is comprised of following sections.

## Data Files
The data folder contains metadata (detailed information on each data column) and data files.
To run these notebooks, you would require following data files (provided via google drive). 
1. licor850.csv (CO2 and water vapor measurements)
2. ma300.csv     (BC measurements in the IR and UV spectrum)
3. zephyrno.csv   (Nitric oxide NOx measurements)
4. alpr.csv       (camera with a specialized software to read license plate and vehicle model and make)

## Jupyter Notebooks
1. CO2, NO2 and BC data exploration and peak area measurements
2. Automaed licese plate reader 
3. Emission factor estimation based on the concentration of each pollutant and fuel carbon value.
4. Merged data files based on the nearest stamp values and identification of high polluting vheicles. 

## Presentation
A pdf file with detailed discussion on the data processing and evaluation.


### Output files
This folder contains output data files and figures. Work in progess. 

PS: please note that this work is in progress and the repository will be updated frequently in the next few months. 
README.md file will be updated as work continue to progress.

