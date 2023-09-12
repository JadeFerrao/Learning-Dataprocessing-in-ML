# Dataprocessing in ML

**Data standardisation**: Scaling features to have a mean of 0 and a standard deviation of 1 for improved model performance. 

**Handling missing values**: Managing and filling in or removing incomplete data points to prevent model errors.  

**Label encoding**: Converting categorical labels into numerical values for machine learning algorithms.  

**Train, test & split data**: Dividing a dataset into training and testing subsets to assess model performance.  

**Handling imbalanced dataset**: Techniques to address unequal class distribution in a dataset, such as resampling or using specialized algorithms.  

**Feature extraction of text using TF-IDF**: Transforming text data into numerical features based on term frequency and inverse document frequency.  

**Numerical dataset preprocessing**: Preparing numerical data for modeling through tasks like scaling, normalization, or outlier treatment.  

**Text dataset preprocessing**: Cleaning and tokenizing text data, removing stop words, and vectorizing for machine learning analysis.  

**Feature Extraction:**
The mapping from textual data to real valued vectors is called feature extraction.

**Bag Of Words (BOW):** list of unique words in the text corpus  

**Term Frequency-Inverse Document Frequency (TF-IDF)**: To count the number of times each word appears in a
document

**Term Frequency (TF)** = (Number of times term t appears in a
document)/(Number of terms in the document)

**Inverse Document Frequency (IDF)**= log(N/n), where, N is the
number of documents and n is the number of documents a term t has appeared in.

The IDF value of a rare word is high, whereas the IDF of a frequent word is low.

TF-IDF value of a term = TF × IDF
