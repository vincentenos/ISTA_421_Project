This project analyzes vehicle collisions in NYC. The full file originally used is very large at over 400MB so i cannot upload it to github.
I am uploading the zip file so this must be used, in the code the unzipped file is called "vehicle_collisions_subset.csv", you must have this in the directory with the python source code to run the data. 
if there is no zip avaiable i uploaded the subset data file that is used for analysis. 
The line where the file is created is 
dfm.to_csv("vehicle_collision_subset.csv", index = False)
This will be the final file used for regression, all other exploratory and data handling prior to this were done on original file. 

Original data can be found here https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data 
Go to actions section and query all data up until october 3rd,  this can then be downloaded. 
