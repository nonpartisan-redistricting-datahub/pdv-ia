# vest-ia-2016

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-iowa-precinct-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## Raw from source: 

#### VEST Data

----

- VEST dataframe, **ia_2016.sh** downloaded [here](https://dataverse.harvard.edu/dataverse/electionscience/?q=vt_2018).


#### Raw Election Data

----
- Election results pulled from .pdf file that was located by navigating to [this site](https://sos.iowa.gov/elections/results/index.html). 

#### Raw Shapefile Data

---- 
- Raw shapefile data was found by navigating to [this site](https://sos.iowa.gov/shapefiles/) and downloading the data named "Statewide Precinct Layer". 

#### Summary

----
We are able to validate that all election results and all shapefile shapes match between VEST's reported data and the raw data. 

<font color="Coral">The following VEST precinct shapefiles are composed of 2 or more raw precinct shapefiles:</font>

Cedar Falls ward 2 precinct 2/CF Twp 
 
Burlington 1-T 
 
Burlington 8-C 
 
Dickinson 6/7 
 
Farragut 
 
Grimes Precinct 2 
 
Hamburg/Washington 
 
Union/Udell 

## File processing: 

- `vest-ia-2016-validation.ipynb` - main notebook for validating VEST's work. Documentation in comments and markdown cells. 