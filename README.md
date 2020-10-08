# replication-template
1. Download the following data and data analysis files. [Data](Recruitment_ReplicationData) [Data Analysis File](bkm_malawi_jole_replication)
2. Download the data and do file in the same directory and run the do file to replicate the study.
3. I added a config.do to track log files for the replication
4. I added code that makes directories in the same directory for the outputs of graphs and tables
5. I added code to install the estout package required to create the tables in csv
6. I have scanned the data for Personal Information Identifiers, none were found
7. I created a READ ME file that reads as these steps do
8. I uploaded this replication within a github repository

# Data Preparation Code
- The do file originally required the replicator to input a directory first.
- The updated do file will run completely if the data file and do file are in the same directory
- The original do file required the replicator to create separately two output sources titled "tables" and "graphs". 
-The updated do file creates these automatically within the directory without the need for the replicator to create new folders.
