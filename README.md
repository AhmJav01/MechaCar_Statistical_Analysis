# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
* Both vehicle_length and ground_clearance provide a non-random amount of variance to the mpg values
* ![dv 1 2](https://user-images.githubusercontent.com/88119309/142793761-c4db3a30-8b54-4882-a6c1-315a4dbfd140.PNG)
* The slope of the linear value is not considered to be zero
* ![dv 1](https://user-images.githubusercontent.com/88119309/142793786-5963797b-4029-4ba7-b2c6-e0abb42e31f4.PNG)
* This model does not effectively predict mpg of MechaCar prototypes and the R-Value is 0.68 which is not a strong R-Vlaue
## Suspension Summary Statistics
* The current manufacturing data does meet the design specification for all manufactring lots in total, as the varaince for all of the lots is 62.29
* ![dv 2](https://user-images.githubusercontent.com/88119309/142793816-f92d5df4-3c7a-4241-9577-64cffd247bf3.PNG)
* While lot three does exceed the limit of 100 (Lot 3 variance at ~170), when combined with the other two lots the overall variance is under 100
* ![dv 2 2](https://user-images.githubusercontent.com/88119309/142793826-dbee95f1-eb31-4adb-b1fe-77fd0efe14fe.PNG)
## T-Tests on Suspension Coils
* Whether combined or split up by lot, none of the p-values for each T-test were statisticlaly significant, as the combined p-value was 0.27 and the p-value for each individual lot was 1
* ![dv 3 1](https://user-images.githubusercontent.com/88119309/142793844-2c5a772a-44eb-4029-a583-cca601b234b8.PNG)
* This means that there is more likely a non-zero correlation that exists
### T-Test Lot 1
![dv 3 2](https://user-images.githubusercontent.com/88119309/142793898-74513504-1679-4f5c-b2dd-de18281cd5d5.PNG)
### T-Test Lot 2
![dv 3 3](https://user-images.githubusercontent.com/88119309/142793907-0aa20910-3f8a-4269-a02e-6372eb02a7dd.PNG)
### T-Test Lot 3
![dv 3 4](https://user-images.githubusercontent.com/88119309/142793920-818f23e8-bf50-4b2e-b7c0-a2bc7f6b5804.PNG)
## Study Design: MechaCar vs Competition
* A statistical study that could be used tho compare MechaCars to other cars would be a two-sample t-test that could compare miles per gallon, cost and fuell efficiency in both cities and on the ighway
* The null hypothesis would be that other car brands have a better linear cprrelation between miles per gallon and fuel efficiency and costs
* The data needed to run these tests would be average miles per gallon, average fuel efficiency in the city and the highway, and the average cost of the car models
