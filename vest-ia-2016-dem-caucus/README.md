# vest-ia-2016-dem-caucus

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-iowa-precinct-and-caucus-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## Raw from source:


### VEST data:

---

- **ia_2016_demcaucus.shp** 

    - Found on the standard [VEST page](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/NH5S2I).


### Election data:

----
- **caucusresults020116d.pdf**

    - Election data taken from [this site](http://www.p2016.org/chrniowa/caucusresultsrxn.html) as the link provided by VEST no longer functions. 

    - The site above also describes the subsequent modifications that were made to the original caucus results, which are presented below:

_Marion County, Knoxville 3 Precinct:
Reported As: 5 county convention delegates for Clinton, 4 county convention delegates for Sanders
Confirmed As: 4 county convention delegates for Clinton, 5 county convention delegates for Sanders
Net Change: Sanders gains 0.13 state delegate equivalents (SDEs); Clinton loses 0.13 SDEs_
 
_Woodbury County, 43 Oto/Oto Township Precinct:
Reported As: 1 county convention delegate for Clinton
Confirmed As: 1 county convention delegate for Sanders
Net Change: Sanders gains 0.15 SDEs, Clinton loses 0.15 SDEs_
 
_Osceola County, Ashton Precinct:
Reported As: 3 county convention delegates for O’Malley, 4 county convention delegates for Sanders
Confirmed As: 4 county convention delegates for O’Malley, 3 county convention delegates fro Sanders
Net Change: O’Malley gains 0.0167 SDEs, Sanders loses 0.0167 SDEs_
 
_Story County, Sherman Township Precinct:
Reported As: 1 county convention delegate for Sanders
Confirmed As: 1 county convention delegate for Clinton
Net Change: Clinton gains 0.23 SDEs, Sanders loses 0.23 SDEs_
 
_Poweshiek County, 1st Ward Grinnell:
Reported As: 18 county convention delegates for Sanders, 8 county convention delegates for Clinton
Confirmed As: 19 county convention delegates for Sanders, 7 county convention delegates for Clinton
Net Change: Sanders gains 0.072 SDEs, Clinton loses 0.072 SDEs_
 
_Total net Change:
Sanders gains 0.1053 SDEs
Clinton loses 0.122 SDEs
O’Malley gains 0.0167 SDEs_
 
Updated Results:\
Clinton: 700.47 SDEs (--0.122 SDEs) 49.84% \ 
Sanders: 696.92 SDEs (+0.1053 SDEs) 49.59% \
O’Malley: 7.63 SDEs (+0.0167 SDEs) 0.54% \
Uncommitted: 0.46 SDEs (unchanged) 0.03%


#### Raw Shapefile Data

---- 
- **Precincts041714.shp**

    - Raw shapefile data was found by navigating to [this site](https://sos.iowa.gov/shapefiles/) and downloading the data named "Statewide Precinct Layer". 

#### Summary

----
We are able to validate that all 1680 precincts' election results and shapefile shapes match between VEST's reported data and the raw data. 

<font color="Coral">The following VEST precinct shapefiles are composed of 2 or more raw precinct shapefiles:</font>

Cedar Falls ward 2 precinct 2/CF Twp 
 
Burlington 1-T 
 
Burlington 8-C 
 
Dickinson 6/7 
 
Farragut 
 
Grimes Precinct 2 
 
Hamburg/Washington 
 
Union/Udell 

- All data was accessed between May 4th and May 7th of 2021. 



## File processing: 

- `vest-ia-dem-caucus-2016.ipynb` - main notebook for validating VEST's file, documentation in comments and markdown cells. 
