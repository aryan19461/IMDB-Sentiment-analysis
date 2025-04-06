# IMDB-Sentiment-analysis
![Sentimental-Analysis-of-IMDB](https://github.com/user-attachments/assets/4805a89f-aba2-4920-a558-22592bf11b95)



### Task 1: Data Exploration and Preprocessing
- **Data Loading and Initial Exploration:** The dataset was loaded into a pandas DataFrame. Initial methods like `.head()`, `.info()`, and `.describe()` were used to understand basic statistics, data types, and the structure of the data.
- **Missing Value Check:** The dataset was checked for any missing values to ensure data integrity.
- **Class Distribution:** The balance between positive and negative reviews was analyzed to detect any skewness in the dataset.
- **Review Length Analysis:** A new column was added to represent the length of each review, which helped in understanding the distribution of review lengths.

### Task 2: Data Cleaning and Text Preprocessing
- **Noise Removal:** HTML tags, special characters, and numbers were removed from the reviews to clean the data thoroughly.
- **Tokenization:** The text was split into individual words to facilitate further processing steps.
- **Removing Stop Words:** Common words that might not be significant for analysis were removed.
- **Stemming and Lemmatization:** Words were reduced to their root forms to standardize variations of the same word.
- **Vectorization:** The text data was converted into numerical vectors using methods like TF-IDF, making it suitable for machine learning model ingestion.

### Task 3: Feature Engineering 
- **Creating Additional Features:** Techniques were employed to extract more features from the text data, such as word count, character count, and average word length. These features potentially help in improving the model's understanding of the data.

### Task 4: Model Development
- **Model Selection and Training:** Various machine learning models, including Logistic Regression, Naive Bayes, SVM, Random Forest, and neural networks were trained to classify the sentiment of the movie reviews.

### Task 5: Model Evaluation
- **Performance Metrics:** The models were evaluated using metrics like accuracy, precision, recall, and F1-score. A confusion matrix was also used to get a detailed view of the model's performance across the two classes (positive and negative).
