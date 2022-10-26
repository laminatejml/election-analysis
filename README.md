# Election-Analysis

## Overview

The goal of this project was to conduct an audit of a congressional election in Colorado. Using Python from the Visual Studio code editor, my self and Tom imported the raw election data and generated code to tabulate the total number of votes, how many votes each candidate received, and percentage of votes each candidate received. From this we determined the winner of the election. In addition to this we used Python to determine the total number of votes cast from all countyies in the precinct, and which county had the largest voter turnout. 

## Results of Analysis 

#### Election Results

* Charles Casper Stockham: 23.0% (85,213)

* Diana DeGette: 73.8% (272,892)

* Raymon Anthony Doane: 3.1% (11,606)

* Winner: Diana DeGette

#### Turnout Results

* Jefferson: 10.5% (38,855)

* Denver: 82.8% (306,055)

* Arapahoe: 6.7% (24,801)

* Largest County Turnout: Denver

## Summary of Analysis

This script is made in such a way that the whomever is assisting the Board of Elections can repurpose it for use in future elections. This would require an adjustment to the several variables in the code depending on which column the candidates and/or counties are located in. Another section that could be altered are the both the winning_candidate_summary and largest_county_summary variables depending on how many criteria outcomes you would like to see written to the corresponding text file. Altogether I believe you will find this very useful for quick audits in future elections.
