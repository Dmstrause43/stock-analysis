# stock-analysis
Analyzing stock options to make financial decisions

##Overview of Project:
The purpose of this project was to summarize stock ticker performance throughout the years 2017 and 2018. The code we created could be repurposed for additional years. 

##Results:
The original code that we used, which contained nested for loops, performed slower than the refactored code, which utilized a single for loop that went through all the data and printed it in one loop. The results are as follows

  Nested For Loop Code (2017):
  'image
  
  Refactored Code (2017):
  ![VBA_Challenge_2017](https://user-images.githubusercontent.com/75653952/105877595-c7c98180-5fc5-11eb-863b-4c5e6ae70c5c.png)
  
  Nested For Loop Code (2018):
  'image
  
  Refactored Code (2018):
  ![VBA_Challenge_2018](https://user-images.githubusercontent.com/75653952/105877684-db74e800-5fc5-11eb-83ef-fe95ce27c363.png)
  
On average, the refactored code performed around three times better than the original nested for loop code. 

##Summary:

The advantages of refactoring code are that the performance overall should improve as well as the layout of the code readability should improve. The disadvantages could be that it might take longer to refactor code that was already working and performing well, as well as refactoring the logic of the original code might be time consuming in figuring out how to optimize what you are trying to accomplish. 

These pros and cons apply to the VBA example of this module as the original code made sense logically and performed well and did what it was supposed to. However, if the dataset were larger and containing more years that just a couple, that could could take a while to run. However, even though the refactoring took some time to understand the syntax of what we were trying to solve, the result was much better performing code that could easily adapt to more data.
