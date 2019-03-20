# appdensitycalculation
This is for the Data Science Toolbox activity of Group 8.

To start with the exercise, the datasets were read and stored to corresponding variables.

The dplyr library was then loaded to gain access to several functions.

The population dataset was then grouped according to region. The 'summarise' function  counted the number of times each region appeared in the dataset. This also corresponds to the number of barangays per region. This was stored in the variable 'CountPerRegionSummary'.

The population dataset was then grouped into Barangay, Region and CityProvince attributes. The PopulationPerBarangay was calculated through the summation of Population data, presented per region and arranged alphabetically with respect to the latter.

BarangayArea is the area per barangay, roughly calculated through dividing the area per region by the number of barangays per region. The regions column was obtained and binded to the respective barangay areas.

The population density was computed by dividing the PopulationPerBarangay by the BarangayArea. Results were sorted in descending order with respect to the top population density.



