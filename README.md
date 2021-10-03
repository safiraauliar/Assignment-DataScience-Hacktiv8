# Assignment-DataScience-Hacktiv8

### BACKGROUND <a name='background'></a>
A LSOA is a census area containing 1,000 to 3,000 people. SOAs were designed to improve the reporting of small area statistics and are built up from groups of output areas
(OA). Statistics for lower layer super output areas (LSOA) and middle layer super output areas (MSOA) were 
originally released in 2004 for England and Wales. Scotland also released statistics for data zones (DZ), that 
were equivalent to LSOAs, in 2004 and intermediate geographies (IG),  that were equivalent to MSOAs, in 2005. 
Northern Ireland introduced LSOAs in 2005 but do not have an MSOA geography.

### ABOUT THE DATASET <a name='about_the_dataset'></a>
This data, represented by the file `london_crime_by_lsoa.csv`, covers the number of criminal reports by month, 
LSOA borough, and major/minor category from Jan 2008-Dec 2016 in Greater London (central London and the 
surrounding metropolitan area) by providing 13,490,604 samples with 7 variables 
each.

The variables `lsoa_code`, `borough`, `major_category`, `minor_category`, `year` and `month` are **categorical** 
variables, while `value` is a **discrete numerical** variable. The variables' meanings are the followings:

* `lsoa_code`: code for Lower Super Output Area in Greater London;
* `borough`: common name for London borough;
* `major_category`: high level categorization of crime;
* `minor_category`: low level categorization of crime within major category;
* `year`: year of reported counts, 2008-2016;
* `month`: month of reported counts, 1-12;
* `value`: monthly reported count of categorical crime in given borough;
