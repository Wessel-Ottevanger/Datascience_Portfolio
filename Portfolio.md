# Portfolio

## Reflection

- [Reflection on own contribution to the project.](./reflection_own_project_contribution.md) 
- [Reflection on own learning objectives.](./reflection_own_learning_objectives.md)
- [Evaluation on the group project as a whole.](./evaluation_group_project.md) 

## Research project

### Task definition
In this project I mostly constributed to the following research questions:

##### What labels of the dataset provided by TNO are relevant for the research?
It was concluded that all labels were relevant but were not in the correct format, I have created a [script to map the Agora and Web-IQ dataset labels to interpol topics. ](./Notebooks/maptointerpoltopics.ipynb) 

##### What feature extraction methods are available for text classification?
For this project I have used methods like Word2Vec and Fasttext to extract features and vectorize our text data.

##### What machine learning algorithms can be used for natural language processing?
There are various machine learning algorithms that can be used for natural language processing, in [this Ensemble learning script ](./Notebooks/Ensemble_Learning.ipynb) I have used 6 different machine learning momdels, 6 different ways to vectorize text data and 5 different preprocessing methods.

##### What machine learning algorithms give the best result?
The best results I have achieved this project was with my Ensemble learning model, which scored around 95% accuracy on the Agora dataset.

##### What combination of processing, feature extraction and machine learning algorithms gives the best pipeline?
The best possible pipline that was created during this project was with minimal preprocessing, TF-IDF vectorization and a Linear SVC model.



### Evaluation
The goal for this project was to create a dark web topic classifier, although we did succeed in creating this classifier I felt that there is still a lot to to before this classifier can be used for the purpose TNO wants to use it for. Because we were limited by the quallity of the data TNO provided us there were certain hurdles impossible to overcome. The classifier we created can still be used to classify the few topics that did occur in the provided data and does this quite accurately. In the end both the project team and TNO were satisfied with the results.

For future work the most important task would be obtaining more and of higher quality data to be able to classify more topics more accurately.

### Conclusions
In [this script ](./Notebooks/model_comparison.ipynb) the results of training a Linear SVC model with tfidf vectors and minimal stripping are show.
I conclude that the results on the Agora dataset were a lot higher than on the WebIQ dataset because of 2 reasons:
- The WebIQ sentences are long, which causes more variety and are harder to predict correctly.
- The Agora dataset has a stronger bias towards drugs which makes predicting drugs really easy.

### Planning 
The global planning we made in the beginning of the project:
![Planning](./Images/Planning.jpg)

We used SCRUM as a development method and used trello to create a scrumboard to keep track of all the tasks.
![Trello](./Images/Trello.jpg)

## Predictive analysis
### Selecting a Model
### Configuring a Model
### Training a model
### Evaluating a model
### Visualizing the outcome of a model (explanatory)


## Domain knowledge
### Introduction of the subject field
### Literature research
### Explanation of Terminology, jargon and definitions

## Data preprocessing
### Data exploration
### Data cleansing
### Data preparation
### Data explanation
### Data visualization (exploratory)


## Communication
### Presentations 
### Writing paper

