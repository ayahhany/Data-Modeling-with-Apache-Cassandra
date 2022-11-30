# Data-Modeling-with-Apache-Cassandra <img align="left" alt="codeSTACKr | songs" width="70px" src="https://user-images.githubusercontent.com/58150666/185989388-c6b37f59-3d5c-4c21-b571-f70cbdf7e1f0.png"/>

### **Project Overview**
> A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

> Create Apache Cassandra database which can create queries on song play data to answer the questions brough to the project.

> Building ETL Pipeine 

### **Project structure**
1. `event_data` folder nested at the home of the project, where all needed data reside.
2. `Project_1B_ Project_Template.ipynb` the code itself.
3. `event_datafile_new.csv` a smaller event data csv file that will be used to insert data into the Apache Cassandra tables.
4. `images` a screenshot of what the denormalized data should appear like in the `event_datafile_new.csv`
5. `README.md` current file, provides discussion on my project.


### **Datasets**
The workspace includes one dataset: `event_data`
The directory of CSV files partitioned by date. Here is an examples of the filepaths to tow files in the dataset:

`event_data/2018-11-08-events.csv`

`event_data/2018-11-09-events.csv`

### **Resources**
You can download the resources from the workspace Terminal using the following commands

`zip -r event_data.zip event_data`

`zip -r images.zip images`
