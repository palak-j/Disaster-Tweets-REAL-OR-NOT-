# Classification of disaster tweets <br/>

Main aim of this project was to classify the tweet, whether it is real or fake using various machine learning models. <br/>
Here, my approach was to first perform some basic NLP techniques to get input data in the required format for modelling.<br/>
These techniques involves-
1. Tokenization
2. Remove stopwords
3. Lemmatization
4. Vectorization

In this model we used-
1. Tokenizer : RegexpTokenizer
2. Stopwords : stopwords.words("english")
3. Lemmatization : WordNetLemmatizer
4. Vectorization : CountVectorizer

After performing all the required NLP operations, I created various classification model which includes <br/>
LogisticRegression <br/>
SVC <br/>
MultinomialNB <br/>
DecisionTreeClassifier <br/>
KNeighborsClassifier <br/>
RandomForestClassifier
