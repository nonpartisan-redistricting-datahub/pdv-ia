# vest-ia-2018

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-iowa-precinct-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## Raw from source: 

### **General Summary**

-------

#### VEST Data

VESTs dataset uses IA's 2018 Election Results and Precinct Boundaries for it's shapefile. 

VEST data files include:  

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  **ia_2018.shp** which has both election results and shapefiles, can be found at [this link](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/UBKYRU/CVWIH1). 



The following counties used shapefiles sourced from the respective county governments instead: Dallas, Johnson, Linn, Story. 

The following precincts were merged to match the 2018 election reports:

1. Appanoose: Udell/Union
2. Black Hawk: Cedar Falls W2P2/Cedar Falls Twp
3. Des Moines: Burlington 1/Tama, Burlington 8/Concordia
4. Fremont: Hamburg/Washington, Farragut/Shenandoah1
5. Lee: Fort Madison 4A/4B, Keokuk 2A/2B, FCM/Harrison
6. Polk: Grimes 2/Urbandale 12
7. Tama: Toledo 1/2/3

The election data columns reported are:

<font color="Coral">
    

Secretary of State
    
    1. G18SOSRPAT - Paul D. Pate (Republican Party)
    2. G18SOSDDEJ - Deidre DeJear (Democratic Party)
    3. G18SOSLOFE - Jules Ofenbakh (Libertarian Party)
    4. G18SOSOWRI - Write-in Votes
    
Governor
    
    1. G18GOVRREY - Kim Reynolds (Republican Party)   
    2. G18GOVDHUB - Fred Hubbell (Democratic Party)
    3. G18GOVLPOR - Jake Porter (Libertarian Party)
    4. G18GOVOSIE - Gary Siegwarth (Clear Water Party)
    5. G18GOVOWRI - Write-in Votes
    
Attorney General
    
    1. G18ATGDMIL - Tom Miller (Democratic Party)
    2. G18ATGLBAT - Marco Battaglia (Libertarian Party)
    3. G18ATGOWRI - Write-in Votes

Treasurer
    
    1. G18TRERDAV - Jeremy N. Davis (Republican Party)
    2. G18TREDFIT - Michael L. Fitzgerald (Democratic Party)
    3. G18TRELHIR - Timothy Hird (Libertarian Party)
    4. G18TREOWRI - Write-in Votes

    
Auditor
    
    1. G18AUDRMOS - Mary Mosiman (Republican Party)
    2. G18AUDDSAN - Rob Sand (Democratic Party)
    3. G18AUDLPER - Fred Perryman (Libertarian Party)
    4. G18AUDOWRI - Write-in Votes
    

Agriculture Secretary
    
    1. G18AGRRNAI - Mike Naig (Republican Party)
    2. G18AGRDGAN - Tim Gannon (Democratic Party)
    3. G18AGRLSTE - Rick Stewart (Libertarian Party)
    4. G18AGROWRI - Write-in Votes

</font>
 

----------------


- VEST reportedly collected shapefile data from the [IA Secretary of State](https://www.sos.IA.gov/elections/research/election-results-and-voters-pamphlets.aspx). 

- SoS shapefile data for IA found [here](https://sos.iowa.gov/shapefiles/Statewide%20Precinct%20Layer/). 

The IA Secretary of State's data files include: 

   - &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  **Precincts041714.sbx** which contains shapefiles for precincts and counties that mostly align with the election results data.

- County shapefiles for [Dallas](http://geodallas.dallascountyiowa.gov/SpatialDownload/Default.aspx), [Johnson](https://www.iowagisdata.org/index.php/apps/files/?dir=/County/Johnson/Open&fileid=854), and [Linn](https://opendata-linncounty-gis.opendata.arcgis.com/datasets/voting-precinct-split-1?geometry=-92.535%2C41.808%2C-90.777%2C42.165) county were taken directly from county websites, in accordance with VEST's process. Data not posted on county websites was generally found on [Iowa's GIS Hub](https://www.iowagisdata.org/). 

- For Story county, [GIS coordinator](https://www.storycountyiowa.gov/Directory.aspx?did=31) Matt Boeck was contacted directly and provided precinct level data via email. this data is available upon request.

- The following counties were revised to reflect updated municipal boundaries using shapefiles from the U.S. Census Bureau's 2020 Redistricting Data Program Phase 2 release: Dubuque, Marion, Muscatine, Polk, Pottawattamie, Scott.

- These counties were downloaded using this [link](https://www.census.gov/geo/partnerships/pvs/partnership19v2/st19_ia.html).

-------

#### Raw election results data

- Most election results were pulled from [this statewide election data site](https://results.vote.IA.gov/), county by county. The data was stored in a deprecated .xls format that needed to be processed and joined semi-manually. The work for this can be found in  **VEST-ia-2018-data-accumulation.ipynb**, present in this repo.
   
-----

- All of the data IAs accessed and downloaded between the dates of March 23rd and March 30th, 2021. 


#### <font color="red">Attention:</font>
RDH was not able to validate the precincts in all counties, specifically, Linn, Dubuque, Story, and Polk county had too many unregistered modifications for us to edit. VEST's precinct shapefiles for those counties could very well be correct, but we had no way of verifying. We can verify that the vote totals for these counties' precincts, and all precincts for that matter, are correct. 

## File processing 

- `VEST-ia-2018-data-accumulation.ipynb` - used to download and combine the individual data for each county within IA. Documentation in comments and markdown cells. 

- `VEST-ia-2018-validation.ipynb` - the main notebook for validating VEST's work. Documentation in comments and markdown cells. 