# Analyzing Crops Water Consumption over its Seasonal Cylce
Enviro Networks Inc.

San Jose, CA

reference: https://www.ksre.k-state.edu/irrigate/reports/L904.pdf

### Purpose
Create a model that determines statistical significance of every new data point added, by predicting plant's growth stage at that point based on its water usage

Do this through these steps:

1) Simulate Data to replicate a typical plant water-use curve

<img width="494" alt="Graph" src="https://user-images.githubusercontent.com/61673602/170113996-665bbff0-41d4-4135-8115-ef5849dfb06a.png">

2) Write an algorithm based on the simulated data to perform linear regression on the data, then using the slope of the lines created, predicts what growth stage the plant is in

3) Add noise to the simulated data so it models real life data (tweak algorithm accordingly)

4) Use model on real data


