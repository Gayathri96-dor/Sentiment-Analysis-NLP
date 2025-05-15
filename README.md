Workflow Overview (Markdown Section):
Dataset: IMDB movie reviews from the NLTK library, consisting of 2000 labeled reviews (positive or negative).

Data Preprocessing:

Lowercased text.

Removed stopwords and punctuation.

Applied stemming using the PorterStemmer.

Feature Extraction:

Utilized TF-IDF Vectorizer with a vocabulary size of 5,000.

Model Training & Evaluation:

Model: Logistic Regression.

Data split: 80% for training and 20% for testing.

Achieved around 85–90% accuracy based on the split.

Confusion Matrix and Classification Report were used for evaluation.

Code Flow:
Data Collection and Preprocessing (Code Cell 1):

Loaded the IMDB movie reviews dataset.

Preprocessed text by:

Lowercasing

Removing stopwords and punctuation

Applying stemming

Created a DataFrame with columns: review, cleaned_review, and sentiment.

Vectorization and Model Training (Code Cell 2):

Vectorized the cleaned text using TF-IDF.

Converted sentiment labels to binary (pos → 1, neg → 0).

Split the data into training and testing sets.

Trained a Logistic Regression model.

Evaluated the model with:

Accuracy score

Classification report

Confusion matrix

Confusion Matrix Visualization (Code Cell 3):

Plotted the confusion matrix using Seaborn for better visualization.
