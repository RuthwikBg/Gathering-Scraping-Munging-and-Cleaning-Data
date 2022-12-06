                                                               ASSIGNMENT 3 
                                                              
ABSTRACT
The objective of this project is to build a job database by scrapping Glassdoor using python and calling for Social Media details using Twitter API. Database was successfully created in PostgreSQL. This project is focused on job domains such as supply chain analyst, data analyst and business analyst. Job listing and the respective details have been scrapped for 300 companies collectively. And twitter specific details have been called for the 300 companies into the database.



The objective of this project is to build a Accidents database. The prime source of extraction is through data repositories from web and the data is munged to obtain a consistent dataset. Furthermore, the dataset was cleaned and audited to make it unique and error free. Database was successfully loaded in MySQL Workbench. 
Once the cleaned dataset was obtained, the dataframe was converted to SQL using MySQLdb and the data is inserted. The database engine is connected to jupyter notebook. Any queries can be executed from jupyter notebook, and the output is displayed.

Crashes data includes crash event level details such as the nearest intersection, with distance and direction of the crash from nearest intersection. Also included are the involved party (vehicle involved with), primary collision factor.

Vehicles data includes the vehicle level details of the crash such as vehicle types, driver's (vehicle, party) age and sex, driver conditions, severity of injury in terms of fatalities, and severe, moderate, and minor injuries per crash and violations preceding the crash. 
There is a one-to-many relationship built that relates the crash to the vehicles involved. The Crash name in vehicle data relates to the Name in the Crash data.

Laws data gives information related to the violation codes and their respective descriptions.

Factors data represents weather, roadway surface, different periods of day, roadway conditions, and time of day

Brief description of files uploaded in GitHub

Data Cleaning Scripts

Row values with NULL and unknown have been removed to maintain data accuracy. 
40% of empty rows in the Age column are filled with the mean value. 
Irrelevant row values having Age factor> 18 are preserved, eliminating the remaining.
30% of blank rows in the Sex column are adjusted with the nearest row string value.

CSV_Files

All Data which has been obtained after the data cleaning procedure has been attached in a CSV file folder to the GitHub link.

Database_Loaders

Python script is used to create Database and Tables. And add the extracted Accidents data into the MySQL Database.



