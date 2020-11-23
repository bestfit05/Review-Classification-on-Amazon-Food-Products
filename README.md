# Review-Classification-on-Amazon-Food-Products
## About the data:
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012.    Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

### Data includes:
- Reviews from Oct 1999 - Oct 2012
- 568,454 reviews
- 256,059 users
- 74,258 products
- 260 users with > 50 review

### Modelling Process

- Exploratory Data Analysis : Did analysis and visualization of whole data and its different features to better understand the data.
- Data Cleaning: Removed duplicate and non - practical rows.
- Text Preprocessing
        Removed Html tags, punctuations
        Removed stop words, 
        stemming
- Feature Engineering: Did a simple test to check if text length(as a new feature) could add any meaning info. 
- text to vector using BOW,TFIDF
- Model TRAINING AND TESTING using KNN,Naive Bayes,Logistic Regression,SVM, Decision tree, Random Forest.
- Evaluation


### Download Data: [Amazon Fine Food Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews) 
