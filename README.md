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

## Notebooks
To run these notebooks, you would require following data files (provided via google drive). 
1. licor850.csv (CO2 and water vapor measurements)
2. ma300.csv     (BC measurements in the IR and UV spectrum)
3. zephyrno.csv   (Nitric oxide NOx measurements)
4. alpr.csv       (camera with a specialized software to read license plate and vehicle model and make)


Two new notebooks are added in this folder.
1. SciKit-learn-MLR-stats-final
This notebook provides information on statistical analysis conducted using Scikit-Learn.
2. understanding_wildfires_cause_consequences
This notebook provide information on processes responsible for ozone formation. 
I have explored the effect of weather and chemical compostion on the ozone equilibrium,
(net ozone= formation -destruction processes) 

Previous notebook with preliminary data exploration
3. San_Diego_2014_ wildfires_Time-series-analysis-of-the-air
4. SanDiego_2014_wildfires_NDVI_DNBR-anaysis

## Presentations
Two powerpoint presentation describing 2014 wildfire events and atmospheric conditions. Work in progress.
1. Time series analysis conducted earlier
2. SD_fires_air_quality_06172020_final

3. Wildfires SD_Causes and Consequences-blog
4. sd_2014wildfires_blog (code cells hidden)

### Test-notebooks
The folder contain two sub folders for air quality and image processing. Each subfolder contains various files to test strategies to clean raw data and reduce file sizes to be used for the final project. Work in progress.

### Output files
This folder contains output data files and figures. Work in progess. 

PS: please note that this work is in progress and the repository will be updated frequently in the next few months. README.md file will be updated as work continue to progress.

