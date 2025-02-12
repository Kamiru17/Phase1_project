# Aircraft Accidents Analysis

## Overview
This project is aimed at analyzing the accidents of different aircrafts and making a decision on the best aircraft bthe organization should purchase based on our findings. The data, obtained from the National Transportation Safety Board is found on the **AviationData.csv**

------
## Objectives 
The projects answers the following key questions:
1. What planes are prone to accidents?
2. What planes, when an accident occurs, is prone to fatalities?
3. What locations have experienced the largest amounts of accidents?
4. In the event an accident, what sort of damages do the planes acquire?
5. Does the number of engines and/or the engine type have a correlation to the occurrence of accidents?
6.  What type of aircraft is usually preferred for what purpose? (In our case, we are mainly focused on commercial and private emterprise)
7. Which air carrier has experienced the most accidents and fatalities.
8. Compare the total serious, fatal and minor injuries as well as the uninjured.
9. Are there flights that are prone to accidents during specific weather conditions?
------

## Data Description
The data consist of two csv files:
1. AviationData.csv
    * `Location`: The area the accident occurred.
    * `Injury.Severity`: The type of injury(fatal/non-fatal).
    * `Aircraft.Damage`: The type of damage the flight sustained.
    * `Make`: The make of the plane.
    * `Model`: The model of the plane.
    * `Number.of.Engines`: How many engines are on a plane.
    * `Engine.Type`: What sort of engine does the plane have.
    * `Purpose.of.flight`: What was the reason the flight was used.
    * `Total.Fatal.Injuries`: Of all the injuries, how many were fatal.
    * `Total.Serious.Injuries`: Of all the injuries, how many were serious.
    * `Total.Minor.Injuries`: Of all the injuries, how many were minor.
    * `Total.Uninjured`: How many were not injured.

2. USStates_Codes.csv

    * `US_State`: The states in the US.
    * `Abbreviation`: The abbreviation of the states.
-------

## Installation

1. Prepare data 
Place the `AviationData.csv` and `USStates_Codes.csv` files in the `project/` directory.

-----

## Usage 

 * Clean the data and remove all the unneccesary columns as well as the values from the columns with high missing values
 * Merge the make and model columns to create a new column: `Aircraft`


* **Visualizations**: Generate visualizations (e.g., pie chart, heatmaps, time series) by running:


* **Interactive reports**: Open Jupyter notebooks in the `notebooks/` directory for interactive analysis.

-----


## Visualizations

* **Bar Graph**: Distribution of the aircraft to the number of accidents of that aircraft, distribution of plane accidents and the number of fatalities associated to these accidents, distribution of the number of engines to the number of accidents, comparison of the types of damages an aircraft sustained after an accident, comparison of the severity of an injury in the event an accident occured.
* **Heatmap**: Correlations of number of engines to the occurrence of accidents.
------

-----

## Contact 
Email: `kamirustephen@gmail.com`
LinkedIn: `Stephen Kamiru`: (https://www.linkedin.com/feed/?trk=guest_homepage-basic_google-one-tap-submit)

-----
