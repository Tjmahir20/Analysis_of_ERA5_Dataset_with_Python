# Analysis_of_ERA5_Dataset_with_Python

### Task Overview
In this group assignment, we worked on ERA5_2mTemp_19900101-19900531_00h.nc, temperature data from January to May in 1990. The tasks are as follows:

* Task 1: open the file ERA5_2mTemp_19900101-19900531_00h.nc in the shared data/Temperature/ERA5 folder and plot the temperature on January 1, 1990, on a map
* Task 2: calculate daily mean global temperature and plot the time series
* Task 3: calculate the mean temperature for each month (January-May) and plot the data on (five) global maps.

### ERA5 Dataset
ERA5 is the latest climate reanalysis produced by ECMWF, providing hourly data on many atmospheric, land-surface, and sea-state parameters together with estimates of uncertainty.ERA5 data are available in the Climate Data Store on regular latitude-longitude grids at 0.25o x 0.25o resolution, with atmospheric parameters on 37 pressure levels. ERA5 is available from 1940 and continues to be extended forward in time, with daily updates being made available 5 days behind real-time. https://climate.copernicus.eu/climate-reanalysis 

### Project Folder Structure
The repository contains the full codes used and sample data that can be used to test the code.

1) [`00_Data`](./media/examples/): This folder contains datasets in our local drive. Since the dataset is very large, it cannot be stored here in github. However, you can access the dataset from this link shared data/Temperature/ERA5.
2) [`01_Code`](./media/examples/): This folder contains all the Python codes for the tasks.
1) [`02_Outputs`](./scripts): This folder contains output images from the codes.

### Used Python Packages
* Matplotlib (https://matplotlib.org/stable/users/installing/index.html)
* Numpy (https://numpy.org/doc/stable/user/absolute_beginners.html)
* Xarray (https://docs.xarray.dev/en/stable/index.html)
* Os (https://www.w3schools.com/python/module_os.asp)

### Task Division
There are three persons in our group: Mahir Tazwar, Xinran Bian, and Tahmida Sarker Muna. The tasks are divided as follows.<br>

- Task 1: Mahir Tazwar  
- Task 2: Xinran Bian  
- Task 3: Tahmida Sarker Muna

### Final Outputs
#### Task 1: Global Temperature Map of 1990 January 1st
![T1_Global Temperature Map of 1990 January 1st](https://github.com/Tjmahir20/Analysis_of_ERA5_Dataset_with_Python/assets/126650557/0532cb56-435e-4959-8461-1473047bbe2f)

#### Task 2: Daily_Mean_Global_Temperature
![T2_Daily_Mean_Global_Temperature](https://github.com/Tjmahir20/Analysis_of_ERA5_Dataset_with_Python/assets/126650557/a032e3a5-35f5-4b0b-9d6b-f008e03019aa)

#### Task 3: Monthly_Global_Mean_Temperature_Maps
![T3_Monthly_Global_Mean_Temperature_Maps](https://github.com/Tjmahir20/Analysis_of_ERA5_Dataset_with_Python/assets/126650557/7feb800c-8bfe-449c-b4ae-6bbc8311bacd)



*** This repository is developed as a part of an assignment of *Satellites for Geohealth* Course (https://studyguide.itc.nl/m-geo/all-courses/202300143/satellites-for-geohealth-?q=satelli) ***
