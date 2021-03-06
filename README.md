# Estimating hourly taxi demand at YVR Airport

This project examines whether data on total passenger and flight arrivals along with flight arrival schedules may be used to develop an effective machine learning algorithm which predicts the hourly taxi demand.

## Objectives

 - Develop an effective R shiny app
 
 - Make impactful EDA using Canadian Airport statistics
 
 - Grap YVR flight arrival schedule data
 
 - Predict hourly taxi demand at YVR

 - Figure out how to predict taxi demand without knowing historical hourly data

## Usage

To perform this analysis run the following scripts:

```
# python src/process_pdf_passengers.py --path_in=data/YVR_Passengers.pdf --path_out=data/tidy_YVR_passengers.csv
```

## References

Statistics Canada. Air passenger traffic at Canadian airports, annual. Accessed January 28, 2020. <https://open.canada.ca/data/en/dataset/85e12734-7705-48de-adb9-ee27bbfd1672>

The Conference Board of Canada. Supply Management in Transportation. December 2013.
