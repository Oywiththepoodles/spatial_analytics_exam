# Exploring the Proposed Pesticide-Parkinson’s Disease Link in Danish Municipalities

### Project Description <br>
This repository contains the contents of the final exam project in the Spatial Analytics course at Aarhus University conducted in the spring of 2024, as well as all resources and materials needed in order to recreate the contents of the project. <br>
The aim of this project was to conduct a spatial analysis of the prevalence of Parkinson's disease and pesticide usage on a municiaplity level in Denmark. The spatial analysis includes assesing the degree of spatial autocrorelation between the municipalities, hotspot analysis for age adjusted rates of Parkinson's disease, square kilomers of farming, crop density and pesticide usage. Further a linear model is created to access whether higher instances of Parkinson's disease is correlated with pesticide usage when accounting for crop density, age and farming area in the municipalities.


### Content and Repository Structure <br>
Everything needed to reproduce the analysis is provided, the necessary data is provided in the ```data``` folder and the code for generating the analysis can be found in the ```src```  folder which contains 2 files, one HTML file containing the knitted script and one Rmarkdown file containing the script. <br>

The resposity is structed as depicted below:
| Folder | Files | Description |
|--------|:------|:------------|
| ```data``` | ```age_distribution_absolute.xlsx```<br>```age_distribution_municipalities.xlsx```<br>```age_group_national_level.xlsx```<br>```citynames_municipalities.xlsx```<br>```farming_municipalities_km2.xlsx```<br>```gadm36_DNK_2_sp.rds```<br>```municipality_area_2011.xlsx```<br>```parkinson_data_with_age_of_diagnosis.xlsx```<br>```people_in_the_municipality_2010_to_2023.xlsx```<br>```pesticides_data.xlsx```<br>```population_per_municipality.xlsx``` | A folder containing all the data needed to perform the analyses. |
| ```src``` | ```Spatial_Data_Analysis.Rmd```<br>```Spatial_Data_Analysis.html``` | A folder containing  the script for the analysis, both in a knitted format (HTML) and as an Rmarkdown file. |

*Note*: the file ```pesticides_data.xlsx``` does not contain all the data provided from Miljøstyrelsen, as filesize restrictions will not allows for that to be uploaded, however it contain all data necessary for running the script. Should the full dataset be of interest, there is full right of access to it, and it can be aquired by contacting Miljøstyrelsen via: info@mst.com.

### Usage and Technicalities <br>
To reproduce the results of this project, the user is advised to clone the repository. This is done by executing the following from the command line: 

```
$ git clone https://github.com/Oywiththepoodles/spatial_analytics_exam.git
```

Once the repository has been cloned, the user is able to run the script provided in the ```src```folder. 

### Contact Details <br>
If you have any questions feel free to contact us on: <br> 
[202105701@post.au.dk](202105701@post.au.dk) OR [202106067@post.au.dk](202106067@post.au.dk) OR [202106904@post.au.dk](202106904@post.au.dk)
