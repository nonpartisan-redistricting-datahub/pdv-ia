# vest-ia-2020

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-iowa-precinct-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## **Raw from source:**

### Accessible files: 

- VEST Iowa 2020 Data File  
  - Accessed: 11/10/21, Source: VEST on the Harvard Dataverse
  - https://dataverse.harvard.edu/file.xhtml?fileId=4789403&version=24.0# 

- VEST Iowa 2020 Documentation
  - Accessed: 11/10/21, Source: VEST on the Harvard Dataverse
  - https://dataverse.harvard.edu/file.xhtml?fileId=5371928&version=24.0#

- Iowa Statewide Precinct Layer
  - Accessed: 11/15/21, Source: Iowa Secretary of State
  - https://sos.iowa.gov/elections/maps/shapefiles.html
  - Select the “Precinct and District Shapefiles” link, then click the “Statewide Precinct Layer”. Shapefile is in an archive called “pcts_04172014_0908am.zip”.

- Iowa County Boundaries Shapefile
  - Accessed: 11/10/21, Source: State of Iowa
  - https://open-iowa.opendata.arcgis.com/datasets/iowa::iowa-county-boundaries 

- 2020 Census Redistricting Data (P.L. 94-171) Shapefiles for Muscatine, Woodbury, and Marion Counties. 
  - Date accessed: 11/17/21, Source: U.S. Census Bureau
  - https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=All+Lines 
  - Select “Iowa” from the dropdown menu. On the next page, select “Muscatine”, “Woodbury”, and/or “Marion” in the county dropdown menu.  

- Dallas County Precinct Shapefiles
  - Accessed: 11/17/21, Source: Dallas County GIS
  - http://geodallas.dallascountyiowa.gov/SpatialDownload/Default.aspx
  - Select the “VotingPrecincts.shp” checkbox to indicate you would like to download it, then click the “Create Zip File” button. When the “Download Zip File” link appears below it, click it to download the precinct shapefiles.

- Dubuque County Precinct Map
  - Accessed: 11/17/21, Source: Dubuque County GIS
  - https://www.dubuquecountyiowa.gov/205/GIS-Mapping 
  - Under the “Downloadable Maps” subheader, select the “City Precincts (PDF)” and “Election Precincts (PDF)” links. 

- Johnson County Precinct Shapefiles
  - Accessed: 11/17/21, Source: IowaGISData.org
  - https://www.iowagisdata.org 
  - Site is referenced by the Johnson County Government website as the preferred source for all of the county’s vector data. Shapefiles were downloaded from the “shp_Precincts_All_2013.zip” archive in the “Johnson” folder.

- Linn County Precinct Maps
  - Accessed: 11/17/21, Source: Linn County Government
  - https://www.linncountyiowa.gov/372/Precinct-Maps 

- Polk County Precinct Maps
  - Accessed: 11/17/21, Source: Polk County Government
  - https://www.polkcountyiowa.gov/county-auditor/election/election-maps/#District%20Map%20Packages 
  - Under the “Precinct Maps” subheader, click the “2012-2021 Des Moines Precincts” and “2012-2021 Polk County Precincts” links. 

- Polk County Precinct Shapefiles
  - Accessed: 11/18/21, Source: Polk County Government
  - Requested by email

- Pottawattamie County Precinct Shapefiles
  - Accessed: 11/17/21, Source: IowaGISData.org
  - Shapefiles downloaded from the “shp_Elections.zip” file available in the “Pottawattamie” folder. 
  - PDF Maps are available from the county website here: https://elections.pottcounty-ia.gov/vote/precincts/ 

- Scott County Precinct Maps
  - Accessed: 11/17/21, Source: Scott County Government
  - https://www.scottcountyiowa.gov/auditor/precincts/pdfs?folder=auditor-precinct-maps/Scott_County_Precinct_Maps/Overall_Map 

- Story County Precinct Maps
  - Accessed: 11/17/21, Source: Story County Government
  - https://www.storycountyiowa.gov/1172/Jurisdictional-Maps 
  - Ames (PDF) and Story County (PDF)

- Story County Precinct Shapefiles
  - Accessed: 11/19/21, Source: Story County Government
  - Requested via email

- Mitchell County Precinct Maps
  - Accessed: 11/17/21, Source: Mitchell County Government
  - https://mitchellcounty.iowa.gov/maps/ 
  - Click the “Mitchell County Precinct Boundary Map” link under “Additional Resources”

### Inaccessible files: 

- Dubuque County Precinct Shapefiles
  - County government charges for access to these files.

- Scott County Precinct Shapefiles
  - County government did not respond to requests for these files. 

## **File Processing:**
- Processing and Validation Steps: \
`vest-ia-2020-validation.ipynb`
