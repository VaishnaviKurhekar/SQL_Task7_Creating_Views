# Task 7 - Creating Views Using the Cars93 Table
# Overview
This task focuses on learning how to create and use SQL views to simplify queries and control data visibility. Using the Cars93 table, you will create views that filter performance cars and share public car information while hiding sensitive details.

Views act as virtual tables that store query logic, enabling easier data access and improved security by restricting sensitive information exposure.

# Environment
# Database: Example uses ecommerce database 

Tools:  MySQL Workbench

Dataset: Cars93 table (contains detailed car data including Manufacturer, Model, Price, Horsepower, MPG, etc.)

# Views Created
# 1. HighPerformanceCars
Shows cars with horsepower greater than 150, including key specifications like manufacturer, model, type, horsepower, city and highway MPG, and price.
Find high horsepower cars priced over $30,000:


# 2. PublicCarInfo
Provides non-sensitive details about cars, excluding columns like Price, EngineSize, or Horsepower for privacy or sharing purposes.


