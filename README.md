# **Fake News Classifier**

## **Overview**

The Fake News Classifier is a machine learning project that aims to distinguish between fake and real news articles using various classifiers. The project uses Natural Language Processing (NLP) techniques and the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization method to transform the text data into numerical features. Three classifiers are utilized: Support Vector Machine (SVM), Logistic Regression, and Decision Tree.

## **Dataset**

The dataset used for this project is loaded from the "compressed_news.csv" file. The dataset contains the following columns:

* **title**: The title of the news article.
* **text**: The text content of the news article.
* **label**: The label indicating whether the news is "FAKE" or "REAL".

## **Model Building and Evaluation**

The following steps are performed in the project:

1. **Data Preprocessing**: The text data is preprocessed by removing stopwords, converting to lowercase, and stripping accents.

2. **Train-Test Split**: The dataset is divided into training and testing sets (75% training and 25% testing).

3. **Feature Extraction**: The text data is transformed into numerical features using the TF-IDF vectorization method.

4. **Classifier Training and Testing**: Three classifiers, Support Vector Machine (SVM), Logistic Regression, and Decision Tree, are trained and tested on the TF-IDF features.

5. **Evaluation**: The accuracy, confusion matrix, and classification report for each classifier are displayed.

## **Results**

The accuracy achieved by each classifier on the test set is as follows:

Support Vector Machine (SVM): 93.69%

Logistic Regression: 91.8%

Decision Tree: 79.18%

## **Visualization**

In the project, visualizations of the dataset and word clouds for most frequent words in real and fake news titles and texts are provided.

## **Contributing**

Contributions to the project are welcome! If you have any suggestions or improvements, feel free to open a pull request.
