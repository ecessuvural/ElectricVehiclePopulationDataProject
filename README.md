# ELECTRIC VEHICLE POPULATION DATA REVIEW
A thorough data analysis on electric vehicles is part of this research. A variety of visualisations are used to complement the analysed data, which includes a detailed examination of the attributes of various car types, their electric ranges, beginning pricing, and regional distributions.
![Tesla Model X ](https://github.com/user-attachments/assets/7ac2c2d3-affe-477e-962e-42e9a6400285)

## Project Summary
This research involved the analysis of electric car data.
- The project has 205439 rows x 17 columns
- Data, VIN(1-10), county, city, state, postal code, model year, make, model, electric vehicle type, clean alternative fuel vehicle (CAFV) eligibility, electric range, base MSRP, legislative district, full vehicle ID Includes , vehicle location, electric utility, 2020 census tract.
- There were initially 482 NaN values ​​in the data set. This number was then changed by random assignment and the data set was examined in this way.
## General Structure of Data

| Column Name      | Non-Null Values | Data Type |
|--------------------------|-----------------|-----------|
| VIN (1-10)               | 205439 | object |
| County                   | 205436 | object |
| City                     | 205436 | object |
| State                    | 205439 | object |
| Postal Code              | 205436 | float64|
| Model Year               | 205439 | int64  |
| Make                     | 205439 | object |
| Model                    | 205438 | object |
| Electric Vehicle Type    | 205439 | object |
| CAFV                     | 205439 | object |
| Electric Range           | 205431 | float64|
| Base MSRP                | 205431 | float64|
| Legislative District     | 204997 | float64|
| DOL Vehicle ID           | 205439 | int64  |
| Vehicle Location         | 205431 | object |
| Electric Utility         | 205436 | object |
| 2020 Census Tract        | 205436 | float64 |

Data Type Distribution: float64(3), int64(3), object(1)
Memory Usage: 26.6+ MB
## Tools and Technologies Used
- **Programming Language:** Python
- **Data Analysis Tools:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

## Purpose of the Project
The purpose of this research is to compare and analyse electric car statistics. Exploratory data analysis (EDA) techniques were used to assess a number of variables, including the demographics, range, beginning price, and legal area of electric vehicles in various nations. Trends and variations in the electric car market across nations were brought to light during the data analysis process.

## Data Usage
The cost of a certain model can be estimated using this data. Simultaneously, the effect of car attributes like battery capacity and range on cost may be examined. Vehicle sales can be maximised by doing this.

Kaggle Link: https://www.kaggle.com/code/ecesuvural/electric-vehicle-population-data


