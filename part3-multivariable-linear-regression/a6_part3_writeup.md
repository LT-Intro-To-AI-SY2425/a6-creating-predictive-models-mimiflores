# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
The r-squared value for this model was 0.86 so the model predicts about 86% of the data accurately. 
2. Is your model accurate? Why or why not?
This was definitely the best model by far as it had the highest r squared coefficient and r value. Also, all the r-values for the x variables and price were all high at -0.86, 0.86, and 0.89 (I added year).
3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
The predicted price for a 10-year-old car with 89000 miles (model year 2014) is $10,601.26. The predicted price for a 20-year-old car with 150000 miles (model year 2004) is $2,802.54.
4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
I think this is happening because most of the daya was with lower ages and mileages so the model is not fit enough yet to encompass multiple different ages and mileages. 