# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
Before commenting out the StandardScalar my accuracy was 88% but after commenting it out it was 70%. 
2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
With the StandardScalar the model was 88% accurate and I think the model could be improved for somewhere in the range of 90-100% effective before it is considered accurate enough. 
3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
The model was pretty good at correctly identifying the gender, but some of the entries with higher salaries were a bit difficult for the model to classify.
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
According to the model a 34-year-old female who makes $56,000 a year will not buy an SUV. 
