PROJECT PROPOSAL

Project Title

Electricity Consumption and Peak-Demand Monitoring System for Distribution Networks

1. Problem Statement

Electricity consumption changes throughout the day, and some periods experience high demand. Without effective monitoring, it can be difficult to identify peak-demand periods, compare electricity usage across distribution zones, and produce timely reports. This project aims to address these challenges through an Oracle database system.

2. Proposed Solution

The proposed system will store and analyze electricity consumption records from different distribution zones. It will identify peak-demand periods, generate alerts when consumption exceeds defined thresholds, and produce reports to support electricity monitoring and planning.

3. Project Objectives

* To design and develop an Oracle database for electricity consumption monitoring.
* To analyze electricity consumption patterns across distribution zones.
* To identify peak-demand periods.
* To generate automated alerts when consumption exceeds defined thresholds.
* To produce reports that support decision-making.

4. Data Source

The project will use the Power Consumption of Tetouan City dataset from the UCI Machine Learning Repository.

Dataset link: https://archive.ics.uci.edu/dataset/849/power+consumption+of+tetouan+city

The dataset contains 52,417 observations from three distribution zones in Tetouan City, Morocco.

5. Planned Database Tables

* ZONE
* WEATHER_READING
* CONSUMPTION_READING
* ALERT
* DAILY_REPORT

The final tables and relationships will be refined during database normalization.

6. Planned PL/SQL Features

* Stored procedures for recording consumption data.
* Functions for calculating average electricity consumption.
* Cursors for generating reports by distribution zone.
* Packages for organizing database operations.
* Triggers for generating alerts when consumption exceeds thresholds.
* Exception handling for database errors.

7. Planned Innovation

An interactive Power BI dashboard connected to the Oracle database will display electricity consumption trends, peak-demand periods, comparisons between zones, and generated alerts.

8. Expected Results

The project is expected to provide an organized database system for monitoring electricity consumption, identifying high-demand periods, and generating useful reports.

9. References

1. UCI Machine Learning Repository. (n.d.). Power Consumption of Tetouan City. https://archive.ics.uci.edu/dataset/849/power+consumption+of+tetouan+city
2. Oracle. (n.d.). Database PL/SQL Language Reference. https://docs.oracle.com/en/database/oracle/oracle-database/
3. International Energy Agency. (2024). Electricity 2024.
