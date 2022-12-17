# Trojan Scheduler
Trojan scheduler is an app designed to help USC students find the best GE courses based on their schedule availability, the desired GE category, and optimal professor ratings. This scrapes data from the USC web registration page and professor rating data from RateMyProfessor. 

## Establishing Database

You must run database/final project.sql to create the table. Afterwards, you must run trojan_sched_resuls.sql, trojan_sched_courses.sql, trojan_sched_credentials.sql, and trojan_sched_professors.sql to insert the data into the table. The full db with tables included is also available in the dump file (import this into MySQL workbench)

## Initializing the Environment of the Exported Eclipse Project

Import Trojan Scheduler FINAL.zip into eclipse as an archive file. Afterwards, locate to src/main/java/JDBCHandler.java and edit SQL_USER, SQL_PASSWORD, and SQL_CONNECTION to match your own MySQL information. The name of schema and port number may need to be changed as well (the default name of schema is "mydb" and port number is 3306). 

## Running the Project

Run on the Tomcat server. 

## Other Files

There are multiple other files in the github repository that is already inside the Trojan Scheduler FINAL.zip. In addition, there is web scraping code in this repository as well. 
