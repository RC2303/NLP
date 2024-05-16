# Sentiment Analysis of Amazon Fine Food Reviews Using Natural Language Processing (NLP)
The goal of this project is to predict whether Amazon Fine Food reviews are positive or negative. This involves loading the data, cleaning it, visualizing it, processing the text, and using various text vectorization techniques such as Word2Vec and BERT.

## Main Steps
1. **Data Loading**
   - Load the Amazon Fine Food reviews dataset into the environment.

2. **Data Cleaning**
   - Handle missing values, duplicates, and outliers.
   - Remove irrelevant columns or features.
   
3. **Data Visualization**
   - Explore the distribution of positive and negative reviews.
   - Visualize the most common words in reviews.
   
4. **Text Processing**
   - Decontraction: Expand contractions (e.g., don't -> do not).
   - Remove punctuation, URLs, and special characters.
   - Remove stop words.
   - Convert text to lowercase.
   - Tokenization: Split text into individual words or tokens.
   - Stemming or Lemmatization: Reduce words to their base or root form.

5. **Text Vectorization**
   - Word2Vec: Convert text into dense word vectors.
   - BERT (Bidirectional Encoder Representations from Transformers): Fine-tune a pre-trained BERT model for text classification.

## Analysis

In this section, we present visualizations, results, and outputs obtained from our analysis:
### Input Data
In this image, I want to indicate that these are the columns of the CSV file: 

![CSV File Columns](https://github.com/RC2303/NLP/blob/main/Images/Screenshot%202024-02-26%20161711.png)

The feautures of the previous image, there are available in the CSV file itself: 

![CSV File](https://github.com/RC2303/NLP/blob/main/Images/Screenshot%202024-02-28%20142257.png)


In this reviews image shows that there are available more good reviews: 

![Reviews](https://github.com/RC2303/NLP/blob/main/Images/Screenshot%202024-05-16%20131738.png)

### Data used
After completing all the text preprocessing and text vectorization steps, the data is now ready to be used for model training.

![Reviews](https://github.com/RC2303/NLP/blob/main/Images/Screenshot%202024-05-16%20131837.png)

### Model: WORD2VEC

### Model: BERT

### Conclusion:

