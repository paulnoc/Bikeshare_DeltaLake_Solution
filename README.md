# Project: Delta Lake Solution for Bike Share Data Analytics

### Project Case 

The goal of this project is to develop a delta lake solution using a lake house architecture on Azure Databricks 

The goal of this project is to employ Azure Synapse Analytics in developing a data warehouse solution for the Divvy bike sharing program in Chicago, Illinois USA. 

### Delta Lake Solution with Azure Databricks

In this project, Azure Databricks was used create Bronze and Silver data stores. Finally, the data was transformed into a star schema for a Gold data store. 

### Business Requirements

The business reuirements are as follows:
1- Analyze how much time is spent per ride
	- Based on date and time factors such as day of week and time of day
	- Based on which station is the starting and / or ending station
	- Based on age of the rider at time of the ride
	- Based on whether the rider is a member or a casual rider
2- Analyze how much money is spent
	- Per month, quarter, year
	- Per member, based on the age of the rider at account start
3- Analyze how much money is spent per member
	- Based on how many rides the rider averages per month
	- Based on how many minutes the rider spends on a bike per month
