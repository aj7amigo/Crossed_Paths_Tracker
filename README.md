# Paths Crossover Detection
Check using GPS coordinates and time stamp if 2 persons crossed paths in a given time frame.


## Required files/values
1. The json file from google takeouts which contains the location history of each person.
<br/>You can get this from
https://takeout.google.com/settings/takeout
2. GPS coordinats of your desired location/zone to plot the paths crossover using basemap.
<br/>You can get this from
https://www.openstreetmap.org
<br/>How to get the coordinates is explained in the workbook 'Paths_Crossover_detection.ipynb'


## Workflow
1. Use the file 'Location_history_converter-json_to_excel.ipynb' to load the 'Location History' json files of both persons and convert the data into excel files.<br/>
2. Use the file 'Paths_Crossover_detection.ipynb' to load the excel files from previous step and plot it to detect the paths crossover and to find the exact GPS coordinates with timestamp.


## Tools used
Python 3<br/>
pandas<br/>
numpy<br/>
matplotlib<br/>
datetime<br/>
json<br/>
basemap<br/>
