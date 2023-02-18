# MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG
The residual standard error seems to high here. There seems to be a large variance in some of the categories like spoil angle. 


![MPGDF](https://user-images.githubusercontent.com/111551902/219853414-7421e464-f999-40d8-a234-e7a2172236c5.png)

![image](https://user-images.githubusercontent.com/111551902/219854475-c221bc64-a3c2-476d-a482-6e75124f4529.png)




### Summary Statistics on Suspension Coils
Mean = Median = 1500
Variance of Lot 3 is very high so the suspension coils do not meet specifications
Variance of Lots 1 and 2 do meet the specifications

![Total_Summary](https://user-images.githubusercontent.com/111551902/219853465-6070a491-5513-4701-9420-5a5d4e978ade.png)

![Lot_Summary](https://user-images.githubusercontent.com/111551902/219853508-33f45c1a-b8d9-4291-b0ad-7dce85a47d02.png)


### T-Tests on Suspension Coils
As the tests reveal below, we fail to reject the null hypothesis since the Lots 1 and 2 have p-values >.05
However, for Lot 3, we can reject the null hypothesis since the p-value < .05

![image](https://user-images.githubusercontent.com/111551902/219853626-ac4ead64-7021-4d72-bf8d-ce15de404f38.png)

![image](https://user-images.githubusercontent.com/111551902/219853665-90acc100-9be9-40f4-808e-4ce85c680041.png)

![image](https://user-images.githubusercontent.com/111551902/219853680-d7de19e4-95c0-4d6d-ab40-543415de0a41.png)


##### Study Design: MechaCar vs Competition
The study design is here was to compare mpg of MechaCar to its competition. 
Null Hypothesis = Mean mpg is the same of the two models
Alternative Hypothesis = Mean mpg is not the same of the two models
Test used here was a 2-Sample t-test.
