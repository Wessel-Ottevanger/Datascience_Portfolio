# Reflection on group project as a whole

## Situation

During the minor applied data science me and my group members did an assignment for TNO, an organisation specialised in research in various fields. The project we have worked on for TNO was to create a dark web text classifier that can classify dark web texts in topics Interpol is interested in. 

## Task

Because we needed to classify text we did research in the area of natural language processing and found that natural language processing usually consists of three steps: pre-processing, vectorization and machine learning.
To create a dark web text classifier we created our own strategies for each of these steps.

## Action

Pre-processing is very self-explanatory and means to process the text before we can do anything else with it. We created multiple different strategies to process the text and later compared which one works best.
Vectorization is needed because machine learning models don’t understand text and can only work with numbers, vectorization means translating text to numbers, there are multiple ways to do this but for this project we chose 4 different methods and compare the results afterwards.
For the machine learning step we also chose several different machine learning models and compared results using the different pre-processing and vectorization methods.

## Result

The result of our comparison was that for our data pre-processing worked best when we did as minimal as possible, vectorization worked best when we used the TF-IDF vectorization method, which works by counting how many times a word is used in a single document and how many times a word is used in all documents and gives each word a score based on these numbers. 
The best machine learning method we have tried was Linear SVC using the above mentioned pre-processing and vectorization methods.
Other results of this project are the short paper we have written and the personal portfolio of each of the group members.

## Reflection

In this project we encountered some issues with the data TNO supplied, we were not allowed to use the data outside of TNO. Due to these issues we have worked on an alternative publicly available dataset we downloaded from Kaggle. Only by doing this we were able to work on the project outside of TNO. This was not a great solution but it was the only thing we could do to work on the project. If I ever encounter a similar problem I won't solve it this way because it caused more problems later in the project.