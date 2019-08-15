# EDA-ChiTrafficCams

### Introduction
This project is an exploratory data analysis (EDA) on the Speed Camera Violations dataset from the Chicago Data Portal. 

***Tools and techniques used include:***

**Python, Pandas, NumPy, Matplotlib, Datetime, Timestamps, Time Series Analysis, Data Cleaning (such as grouping and sorting), Data Visualization (histograms)** 

### Data
The City of Chicago has installed automatic speed cameras for Child Safety Zones. This notebook explores the dataset "Speed Camera Violations" which reflects the daily volume of violations that have occurred in Children's Safety Zones for each camera. The data reflects violations that occurred from July 1, 2014 until present, minus the most recent 14 days (updated daily). The data I used contains the collection period from July 1, 2014 to December 23, 2018. The size of the dataset used for this project is 23.5 MB.

See more information about the dataset here:https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4
For most of the project so far, I focused on the columns 'CAMERA ID', 'VIOLATION DATE', and (number of speed) 'VIOLATIONS'.

### Questions to Explore
* 1 What is the average number of citations issued per camera, per day?
* 2 On which day of the week are the most citations issued?
* 3 Has the number of active cameras increased or decreased over the collection period?
* 4 Any interesting patterns or specific outliers in the data?

### Further Work
In this projetc I decided not to work with geographic data because lots of cameras are missing information for those columns. The Chicago Data Portal page for this dataset actually already included visualizations of the geographic locations of these traffic cameras, as well as a quick way to generate visualizations with Plotly. 

It would be interesting to compare how the geographic distribution of these cameras changed over time (are they reduced in areas with a low number of daily violations citations, and increased in areas with a high number of citations, for example). Also if there are similar initiatives implemented in other large cities who make their data openly available, it would be of interest to compare the effectiveness of their methods. 

Ultimately this type of data could be incorporated into Smart Cities projects, to cut down on costs and increase efficiency (such as finding what times of day are certain cameras not getting any citations, and turning them off during those times).


### Installation and Usage
Download the .csv data file, as well as requirements.txt. Install the requirements for this project using `pip install -r requirements.txt`. This will install the exact version of the libraries that I had when doing this project.
