# Gathering, Scraping, Munging and Cleaning Data
                                                              

The objective of this project is to build a collect, clean and build Accidents database . The primary source of extraction is data repositories from web and the data is cleaned to obtain a consistent dataset. Furthermore, the dataset was cleaned and audited to make it unique and error free. Data was successfully loaded in Database. 

Crashes table includes crash event level details such as the nearest intersection, with distance and direction of the crash from nearest intersection. Also included are the involved party (vehicle involved with), primary collision factor.

Vehicles table includes the vehicle level details of the crash such as vehicle types, driver's (vehicle, party) age and sex, driver conditions, severity of injury in terms of fatalities, and severe, moderate, and minor injuries per crash and violations preceding the crash. 
There is a one-to-many relationship built that relates the crash to the vehicles involved. The Crash name in vehicle data relates to the Name in the Crash data.

Laws table gives information related to the violation codes and their respective descriptions.

Factors table provides information on weather, roadway surface, different periods of day, roadway conditions, and time of day

## Brief description of files uploaded in GitHub

### Data Cleaning Scripts

Row values with NULL and unknown have been removed to maintain data accuracy. 
40% of empty rows in the Age column are filled with the mean value. 
Irrelevant row values having Age factor> 18 are preserved, eliminating the remaining.
30% of blank rows in the Sex column are adjusted with the nearest row string value.

### CSV_Files

All Data which has been obtained after the data cleaning procedure has been attached in a CSV file folder to the GitHub link.

### Database_Loaders

Python scripts to create Database and Tables. And add the extracted Accidents data into the MySQL Database.



