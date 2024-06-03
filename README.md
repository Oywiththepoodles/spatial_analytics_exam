# Title: PD & Pesticides

### Project Description <br>
This repository contains the contents of the final exam project in the Spatial Analytics course at Aarhus University conducted in the spring of 2024, as well as all resources and materials needed in order to recreate the contents of the project. <br>
The aim of this project was to conduct a spatial analysis of the prevalence of Parkinson's disease and pesticide usage on a municiaplity level in Denmark. The spatial analysis includes assesing the degree of spatial autocrorelation between the municipalities, hotspot analysis for age adjusted rates of Parkinson's disease, square kilomers of farming, crop density and pesticide usage. Further a linear model is created to access whether higher instances of Parkinson's disease is correlated with pesticide usage when accounting for crop density, age and farming area in the municipalities.


### Content and Repository Structure <br>
The resposity is structed as depicted below:
| Folder | Files | Description |
|--------|:------|:------------|
| ```data``` | ```data.zip```| A folder containing the data needed to perform the analyses. |
| ```src``` | ```script_1.rmd/html```<br>```script_2.rmd/html```<br>```script_3.rmd/html``` | A folder containing knitted scripts in a html-format as well as the raw scripts in Rmarkdown format. |
| ```LICENSE```|        | A file declaring the license type of the repository. |

Everything needed to reproduce the analysis is provided, the necessary data is provided in a zip-file in the ```data``` folder and the code for generating the analysis can be found in the ```src```  folder which contains X scripts, both as rmarkdown-files as well as knitted HTML versions: <br>

- ```Script_1```: explanation of what happens in the script <br>
- ```Script_2```:  explanation of what happens in the sciript <br>
- ```Script_3```: explanation of what happens in the sciript


### Usage and Technicalities <br>
To reproduce the results of this project, the user is advised to clone the repository. This is done by executing the following from the command line: 

CHANGE THIS WHEN TITLE IS DETERMINED
```
$ git clone https://github.com/Oywiththepoodles/spatial_analytics.git
```

Once the repository has been cloned, the user is able to run the scripts provided in the ```src```folder. The scripts should be run in the following sequence as they depend on the previous scripts: <br>
  1) Script_1 <br>
  2) Script_2 <br>
  3) Script_3 <br>

The data is provided in single zip-file to avoid it taking up unnessesary amounts of storage. To unzip the data, execute the following commands from the command line:

UPDATE THIS WHEN DATA HAS BEEN ADDED
```
cd spatial_analytics/data

unzip spatial_data.csv.zip
```

### License <br>
This project is licensed under the MIT License - see the [LICENSE](https://github.com/sofieditmer/SpatialAnalyticsExamProject/blob/main/LICENSE) file for details.

### Contact Details <br>
If you have any questions feel free to contact us on: <br> 
[202105701@post.au.dk](202105701@post.au.dk) OR [202106067@post.au.dk](202106067@post.au.dk) OR [202106904@post.au.dk](202106904@post.au.dk)
