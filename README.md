# Udacity-Data-Science-Project-4

Project overview/motivation 
For music streaming services and other subscription-based businesses,
user churn is an import metric and predictor of customer satisfaction with the service.
This article walks users through a methodology for 
predicting user turnover(churn) using event data from a music streaming service like Spotify 
or Apple Music using Apache Spark.

File descriptions
“mini_sparkify_event_data.json.zip” is the compressed JSON file that contains that data for analysis
“Sparkify-08–13–21.ipynb” is the nobtebook used for analysis

Libraries used
1. pyspark
2. SparkConf
3. pandas matplotlib.pyplot
4. seaborn
5. datetime
6. Pipeline
7. DecisionTreeClassifier, GBTClassifier, LinearRegression, 8.LogisticRegression, LinearSVC, RandomForestClassifier, NaiveBayes
9.StringIndexer, VectorIndexer
10.MulticlassClassificationEvaluator
11.CrossValidator, ParamGridBuilder
12.CountVectorizer, IDF, StopWordsRemover StringIndexer, Normalizer, 13.RegexTokenizer, StandardScaler, VectorAssembler, PCA
14. pyspark.sql.types import IntegerType
15. avg, explode, concat, lit, min, max, split, udf, isnull, col, desc
16. SparkSession, Window

References 
- Python 
- Pyspark Documentation
- Stack overflow 

Link to blog post 
https://medium.com/@michael.preston/how-to-predict-user-churn-with-machine-learning-5adfd10c93a1
