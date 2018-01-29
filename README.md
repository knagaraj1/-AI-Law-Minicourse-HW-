# -AI-Law-Minicourse-HW-

## Step 1: Data Collection and Preparation
This imports all the supreme court cases and then each step within it allows for certain filtration of the data based on the specific user request based on your defined methods and variables. This will generate a table where you can click on the year and it will display the relevant cases based on the year selected.
## Step 2: Data Collection & Preparation
This step will pull in the relevant information from the cases as requested by the user and put it together in the table. The table will then display the caseurl, the case title, the years and the case itself.
## Step 3: Data Processing
In this step, the program will start scraping through the data and processing the text to create the output that we are looking for. The processing workflow will then remove the state names, case names, common stopwords, people's names, day of the week, non words and Lemmatizing. Variables are then assigned to create a stoplist and then the text cleaner will remove all the excess words to create a cohesive and usable table.
## Step 4: Topic Modeling Method Testing
This step will allow us to parse through large data sets in order to whittle down the information to what is needed. In order to improve the accuracy of the topic modeling, we will use a frequency filter, a part of speech tag filter and a batch wise LDA. Using this filter wil reduce the complexity of the data in order to be able to get discernable results from the filtration process.
## Step 5: Topic Model Application to Data
This step will then collect the topics that have been returned from the prior step and make a dictionary of the components that make up each topic from the original model. Once all the data required for the request have been imported and sorted, we can then put the data together for visualization.
