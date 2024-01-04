# Fake and Real News Classification
## Dataset Link :- https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification
### Project Overview & Brief Introduction:
---------------------------------------------
The project focuses on the detection of fake news through machine learning and natural language processing techniques. 
The primary purpose is to address the Growing spread of misinformation, particularly through social media, and to 
provide a model that can Difference between true and false information. 
The project aims to contribute to the Reduction of the negative impact of fake news on individuals and the society.

### Tools, Technologies, Programming Language, and Project Structure:
--------------------------------------------------------------------
Tools & Technologies:-
	- Jupyter Notebooks(IDE) for code development and analysis.
	- Python for programming, utilizing libraries such as pandas, scikit-learn, and NLTK.
Project Structure:-
	- The structured of project i followed:
		- I took a NEWS dataset from kaggle this dataset having both real and fake news records  
		- this dataset having columns like title, text and label(true or fake)
		-  i took title as for data analysis due to time consuming
		- Exploratory Data Analysis (EDA).(i droped the duplicated records as well null values)
		- Text pre-processing
			- Cleaning :- in cleaning process i Removed special characters, punctuation, and unnecessary symbols and URLs 
				      or hyperlinks from the text data.this are wont contribute much information to the analysis.
			- Text Casing :- then i Convert the text to lowercase.
			- Tokenization :- breaking sentance into individual words are called (tokens).because this words  
			- Stopword Removal :- Remove common stopwords (e.g., "and," "the," "is") that 
					      do not contribute much to the meaning of the text.
			- Lemmatization :- Apply lemmatization for reduce words to their base or root form. 
					   This helps in standardizing the vocabulary and reducing dimensionality.
		- TF-IDF vectorization for feature extraction.(TF-IDF is a word vectorization technique that transforms 
		  text data into numerical representations that can be used in ML models.)
		- Implementation of machine learning models (Naive Bayes, Decision Tree, Random Forest, AdaBoost).
		- Model evaluation(it actually tels the performance of the model, in this data set i took accuracy 
		  eveluation metric because my dataset is balanced b/w true and fake news)

### Challenges Faced & Solutions:
----------------------------------
	- Data Cleaning and Pre-processing:
		- Challenge: Handling special characters, URLs and case letters means few are upper case and few are lower case.
		- Solution: Developed a systematic pre-processing pipeline using NLTK and regular expressions to clean and standardize text data.
	# - Model Selection:
		# - Challenge: Choosing the most effective machine learning model.
		# - Solution: Implemented multiple models and evaluated their performance, determining that Random Forest provided the best accuracy.
### Accomplishments and Results:
-------------------------------
Achieved high accuracy (95.0%) with the Random Forest model

### Conclusion:
--------------
In conclusion, this project it aim to stop the spread of fake news using machine learning. 
By analyzing news articles, i successfully built a model, like a smart filter, that can tell if the news 
is likely true or false.


