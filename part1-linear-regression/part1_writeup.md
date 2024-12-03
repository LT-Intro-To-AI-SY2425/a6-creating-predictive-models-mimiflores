# Part 1 - Linear Regression Writeup

After completing `a6_part1.py` answer the following questions

## Questions to answer

1. What is the r squared value?  What does this say about this linear regression model?
r squared of the variation in the y value can be explained by the linear relationship with the x value. A higher r squared value indicates a stronger linear regression model as more of the variation can be explained. 
2. According to your model, what is the predicted systolic blood pressure for a person who is 42 years old?
According to my model, the predicted systolic blood pressure for a person who is 42 years old is about 137.46
3. How accurate do you think this model's predictions are?  Do you think this model is accurate enough to reliably predict someone's blood pressure based on their age?  Why or why not?  And if not, what could improve the model?
Although there is a moderately strong correlation shown in the linear reression model (as indicated by its r-value of about 0.63), I do not think it is accurate enough to reliably predict somone's blood pressure based on their age. There are many factors that go into blood pressure, not just age so I do not think it is very applicable in a real-world scenario. However, if it was trained with a significant amount of data across all ages, it could be helpful for a rough estimate of the average blood pressure based on age. 