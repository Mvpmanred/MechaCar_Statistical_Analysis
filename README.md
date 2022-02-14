# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![deliverable 1](https://user-images.githubusercontent.com/92561493/153803821-c8f49417-e2c9-4f97-8a1c-d0ade55de2ef.PNG)
- From the picture above, we can see five variables/coefficients provided a non-random amount of variance to the mpg values in the dataset. They are vehicle_length,vehicle_weight,spoiler_angle,ground_clearance and AWD).
- we have p-value of 5.35e-11. If we assumed confidence level is 95%. THen we can compare our p-value (very samll) to significance level of 5%, 0.05. Since 5.35e-11 is smaller than 0.05. We can conclude that we reject the null hyposthesis. When we reject the null, the slope of the linear modle is not zero.
- Our R-squared value is 0.7149, which means that 71% of mpg prediction can be explained by our five variables. We can add more variables to test and to improve.

## MechaCar suspension coils 
![deliverable 2](https://user-images.githubusercontent.com/92561493/153806794-1980574f-e459-4607-96a5-4c61136929f8.PNG)
- From the picture above, we can see the mean for all manufacturing lots is 1498.78 , median is 1500, variance is 62.29356 and SD is 7.892627. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Our number is 62.29356, which mean our manufacturing lots as a whole meet the design specifications.

![deliverable 22](https://user-images.githubusercontent.com/92561493/153807818-41439349-0bf2-4978-a6b2-f7375da13cd0.PNG)
- when we break down into a deeper analysis, we have Lot1, Lot2 and Lot3. Lot1 has varicance of 0.975918 and Lot2 has variance of 7.46933878. Both Lot1 and Lot2 meet the design specifiations. 
- However, Lot3 has variance of 170.2961224, which exceeds the 100 punds per square inch. Lot3 did not meet the design specification.

## T-Tests on Suspension Coils
![deliverable 3](https://user-images.githubusercontent.com/92561493/153808940-396305a1-28c6-4126-b7e1-ef35dc564d74.PNG)
![deliverable 31](https://user-images.githubusercontent.com/92561493/153808951-65061444-2de9-4558-93dd-6e756ad9d793.PNG)


