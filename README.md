# rdependencies-icsme2015
Replication package of a study on of CRAN and Github R package dependencies 

## `data` directory

**bioconductor-year-month-day.csv** - R package meta-data extracted from BioConductor, including several previous releases. Extraction was done at given date. 

**cran-deps-history-year-month-day.csv** - R package meta-data extracted from CRAN using ExtractR. 

**github-cran-bioc-alldata.csv** - Aggregation of the data in the other files. 

**github-raw-year-month-day.csv** - Data extracted from clones of GitHub repositories.

**github-repositories-year-month-day.csv** - List of available repositories that contain a `DESCRIPTION` file at the root of the repo.


## `notebooks` directory

**BioConductor - Data Extraction** - Script to extract the data from BioConductor.

**Data Merging** - Script that aggregate all the extracted data. 

**Dependencies - Required Packages** - Script that plots several figures of our article. It also contains the dataframe needed for these plots. 

**GitHub - Data Extraction** - Script that extract all the data from our clones of GitHub repositories (commits and meta-data for every `DESCRIPTION` file). 

**GitHub - R Package Repositories** - Script that filters the repositories that will be studied.