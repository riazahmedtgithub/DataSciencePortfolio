# Data Science Portfolio
Repository containing portfolio of data science projects completed by me for academic and self learning purposes. They are Presented in the form of Jupyter notebooks, PDF files and R markdown files (published at RPubs).

## Instructions for Running Python Notebooks Locally
1. Install dependencies using requirements.txt.
2. Run notebooks as usual by using a jupyter notebook server, Vscode etc.

## Contents

- ### Machine Learning

	- [House price prediction using XGBoost and ANN models](https://github.com/riazahmedtgithub/Models/blob/main/HousePrediction%20using%20XGBoost%20and%20ANN.pdf): A model to predict the value of a given house in the real estate market.

		- Feature creation, selection and elimination.
  		- Visualization using frequency distribution, box plots, bar charts, correlation maxtrix etc.
    		- Data preparation.
      		- Building XGBoost and ANN models.
        	- Parameter tuning using GridSearchCV.
         	- Feature elimination using RFECV.
          	- Hypterparameter tuning with RandomizedSearchCV for Kerasregressor.
        	- Model metrics comparison and final model recommendation.


	- [Supervised Learning: Finding Donors for CharityML](https://github.com/sajal2692/data-science-portfolio/blob/master/finding_donors/finding_donors.ipynb): Testing out several different supervised learning algorithms to build a model that accurately predicts whether an individual makes more than $50,000, to identify likely donors for a fictional non-profit organisation.
	- [Unsupervised Learning: Creating Customer Segments](https://github.com/sajal2692/data-science-portfolio/blob/master/customer_segments/customer_segments.ipynb): Analyzing a dataset containing data on various customers' annual spending amounts (reported in monetary units) of diverse product categories for discovering internal structure, patterns and knowledge.
	- [Reinforcement Learning: Training a Smartcab to Drive](https://github.com/sajal2692/Training-a-Smartcab-to-Drive): Creating an optimized Q-Learning driving agent that will navigate a Smartcab through its environment towards a goal.
	- [Deep Learning: Digit Sequence Recognition using CNNs](https://github.com/sajal2692/data-science-portfolio/blob/master/digit_recognition-mnist-sequence.ipynb):  Designing and implementing a Convolutional Neural Network that learns to recognize sequences of digits using synthetic data generated by concatenating images from MNIST.

	_Tools: scikit-learn, Pandas, Seaborn, Matplotlib, Pygame_ 

- ### Natural Language Processing

	- [Disaster Message Classifier](https://github.com/sajal2692/disaster-message-classifier): A multilabel classification model to predict the categories of a disaster message. Includes an ETL pipeline for data processing, a ML pipeline to train the model, and a web app, with visualizations, where the model can be used to classify messages. _Tools: NLTK, Scikit-learn, XGBoost, Flask, Plotly_

	- [3-way Sentiment Analysis for Tweets](https://github.com/sajal2692/data-science-portfolio/blob/master/3-Way%20Sentiment%20Analysis%20for%20Tweets.ipynb): 3-way polarity (positive, negative, neutral) classification system for tweets, without using NLTK's sentiment analysis engine. 

	- [Cross language Information Retrieval](https://github.com/sajal2692/data-science-portfolio/blob/master/Cross%20Language%20Information%20Retrieval.ipynb): Cross language information retrieval system (CLIR) which, given a query in German, searches text documents written in English.


	_Tools: NLTK, scikit_

- ### Data Analysis and Visualisation
	- __Python__
		- [Scalable Walkability Analysis of Melbourne](https://github.com/sajal2692/Scalable-Walkability-Analysis-of-Melbourne): Analysis of walkability of suburbs in Melbourne, Victoria and its implications.
		- [Titanic Dataset - Exploratory Analysis](https://github.com/sajal2692/data-science-portfolio/blob/master/Titanic%20Dataset%20-%20Exploratory%20Analysis.ipynb): Exploratory Analysis of the passengers onboard RMS Titanic using Pandas and Seaborn visualisations.
		- [Stock Market Analysis for Tech Stocks](https://github.com/sajal2692/data-science-portfolio/blob/master/Stock%20Market%20Analysis%20for%20Tech%20Stocks.ipynb): Analysis of technology stocks including change in price over time, daily returns, and stock behaviour prediction.
		- [2016 US General Election Poll Data Analysis](https://github.com/sajal2692/data-science-portfolio/blob/master/2016%20General%20Election%20Poll%20Analysis.ipynb): Very simple analysis of 2016 US General Election Poll data.
		- [911 Calls - Exploratory Analysis](https://github.com/sajal2692/data-science-portfolio/blob/master/911%20Calls%20-%20Exploratory%20Analysis.ipynb): Exploratory Data Analysis of the 911 calls dataset hosted on Kaggle. Demonstrates extraction of useful features from different variables.
		
	_Tools: Pandas, Folium, Seaborn and Matplotlib_

	- __R__ 
		- [Behavioral Risk Factor Surveillance System(BRFSS) 2013: Exploratory Data Analysis](http://rpubs.com/sajal_sharma/brfss2013): Exploratory analysis of the BRFSS-2013 data set, focusing on investigating the relationship between education and eating habits, sleep and mental health, and smoking, drinking and general health of a person. 
		- [Inferential Statistics: Do men or women oppose sex education?](http://rpubs.com/sajal_sharma/inferential_statistics) : Using the GSS (General Social Survey) dataset to infer if, in the year 2012, were men, of 18 years or above in the United States, more likely to oppose sex education in public schools than women.
		- [Data Visualization: Corruption and Human Development](http://rpubs.com/sajal_sharma/corruption_viz): A scatter plot for the relationship between the 'Human Development Index' and the 'Corruption Perceptions Index' of countries.
		- [Moneyball: Analysing and replacing lost players](http://rpubs.com/sajal_sharma/moneyball_lost_players): Exploration of baseball data for the year 2001 to look at replacements for key players lost by the Oakland A's in 2001. Inspired by the book/movie: Moneyball.
	

- ### Micro Projects: 

	- __Python__
		- [ML with Logistic Regression](https://github.com/sajal2692/data-science-portfolio/blob/master/ML%20Micro%20Projects/Machine%20Learning%20with%20Logistic%20Regression.ipynb): Using Logistic Regression to predict whether an internet user clicked an ad or not.
		- [ML with K Nearest Neighbours](https://github.com/sajal2692/data-science-portfolio/blob/master/ML%20Micro%20Projects/ML%20with%20K%20Nearest%20Neighbors.ipynb): Using KNN to classify instances from a fake dataset into two target classes, while choosing the best value for K using the elbow method.
		- [ML with Decision Trees and Random Forests](https://github.com/sajal2692/data-science-portfolio/blob/master/ML%20Micro%20Projects/Machine%20Learning%20with%20Decision%20Trees%20and%20Random%20Forests.ipynb): Using Decision Trees and Random Forests to predict whether a lender will pay their loan back. Uses publically available data from LendingClub.com
		- [Movie Recommendations using Recommender Systems](https://github.com/sajal2692/data-science-portfolio/blob/master/ML%20Micro%20Projects/Recommender%20Systems%20with%20Python.ipynb): A micro project to build a recommendation system that makes movie recommendations based on user review similarities. 

	- __R__
		- [ML Logistic Regression](http://rpubs.com/sajal_sharma/micro_logistic): Predicting salary class of a person using logistic regression.
		- [ML Decision Trees and Random Forests](http://rpubs.com/sajal_sharma/micro_dt_rf): Using Decision Trees and Random Forests to classify schools as Private or Public.

I also dabble in all other kinds of technology. You can find a general portfolio [here](https://github.com/sajal2692/general-portfolio/blob/master/README.md).

If you liked what you saw, want to have a chat with me about the portfolio, work opportunities, or collaboration, shoot an email at contact@sajalsharma.com. 

