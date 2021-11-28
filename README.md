# da-test-task
## Test task for the Utopia Music startup

There are two datasets:

1. consumption_data.csv; 
this file contains radio plays consumption for a particular region and timeframe

2. feed_station_mapping.csv; 
this file contains the mapping between feeds and stations

Context:

Radio play consumptions come in at 'feed' level, 
These can have a many-to-one relationship with a given radio station. 
The relationship between feeds and radios is to be found in the feed_station_mapping file. 


Your tasks:

1. Consolidate the data so that we do not double count plays coming from feeds that belong to the same station 
   If you do not find the parent station for a given feed, just default to the feed info and use that as your 'station' instead.
2. Further clean the data as you deem approriate in order to perform an analysis on this dataset
3. Present the steps you have gone through for the data processing (eg. python notebook or any other data management tool you use)
4. Present any additional findings from the analysis you performed on the cleaned dataset in some visualisation tool (Tableau preferably but not mandatory)
