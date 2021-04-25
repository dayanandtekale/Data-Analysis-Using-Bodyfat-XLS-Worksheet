# Data-Analysis-Using-Bodyfat-XLS-Worksheet

Multiple Regression Analysis of Body Fat Percent and Body Mass Index

1. Introduction of Body Density data.
This is a comprehensive dataset that lists estimates of the percentage of body fat determined by underwater weighing and various body circumference measurements
2. Theories about BMI and Body Fat Percentage
Some experts tout BMI(body mass index) as the most accurate and simple way to determine the effect of weight on your health. In fact, most recent medical research uses BMI as an indicator of someone’s health status and disease risk. Some debate about which values on the BMI scale the thresholds for ‘underweight’, ‘overweight’ and ‘obese’ should be set. However, the followings are used for the criteria.
BMI < 18.5 : underweight,
18.5 < BMI < 25 : optimal weight,
25 < BMI < 30 : overweight,
BMI > 30 : obese.
Meanwhile, in September 2000, the American Journal of Clinical Nutrition published a study showing that body-fat percentage may be a better measure of your risk of weight-related diseases than BMI
essential fat : 2-5%
athletes : 6-13%
fitness : 14-17%
Normal : 18-24%
obese : more than 24%
Which one is a better and more accurate measure of body fat? This question remains to be studied further. Instead, the main goal of this analysis is to find out the relationships between ‘Body Fat Percentage’ and other predictors as well as ‘Body Mass Index’ and others.

3. The variables of Body Density data.
The body density dataset includes the following 15 variables listed from left to right:
Density : Density determined from underwater weighing
Fat : Percent body fat from Siri’s (1956) equation
Age : Age (years)
Weight : Weight (kg)
Height : Height (cm)
Neck : Neck circumference (cm)
Chest: Chest circumference (cm)
Abdomen : Abdomen circumference (cm)
Hip : Hip circumference (cm)
Thigh : Thigh circumference (cm)
Knee : Knee circumference (cm)
Ankle : Ankle circumference (cm)
Biceps : Biceps (extended) circumference (cm)
Forearm : Forearm circumference (cm)
Wrist : Wrist circumference (cm)

New variable MassIndex will be created as the ratio of Weight(kg) to Height(m) squared for the measure of Body Mass Index in addition to the above variables. Model Selection process and regressions for both response variables, Fat and MassIndex, will be compared to explain which measure explains this data better.

5. Comparing the distributions of Body Mass Index and Body Fat Percent using categorization.
To compare the distributions of 2 response variables
the following criteria are used to categorize the types of weights for Body Mass Index.

6. Comparing Regression models for Body Mass Index and Body Fat Percent
1) Selection of the significant predictors using general linear model
2) Model Selection using the Akaike information criterion (AIC)
3) Regression outputs with 2 subsets.

7. Unusual Data Check and removal
8. Discussion of the results
Both Body Mass Index (BMI) and Body Fat Percent are measures of the body fat. For the Body Density Data 2 different response variables are used to identify the relationsip between each response variable and their own significant predictors to determine which body fat measure represents this dataset better. The result of this analysis shows that Body Fat percent(Fat) has a significant negative linear relationship only with the variable Denstiy since the fomula for Body Fat Percent is alt text and Body Density alt text
, where
D = Body Density (gm/cm3)
A = proportion of lean body tissue
B = proportion of fat tissue (A+B=1)
a = density of lean body tissue (gm/cm3)
b = density of fat tissue (gm/cm3)

Meanwhile, Body Mass Index(MassIndex) has strong linear relationships with multiple predictors since Body Mass Index can be calculated by alt text and Height and Weight are also correlated with other measurements such as Abdomen, Thigh, etc.

