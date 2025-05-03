
**Student Name**: Iswariya.G
**Register Number**: 412723205015
**Institution**: Tagore Engineering College  
**Department**: [Information Technology]  
**Date of Submission**:   
---
The project aims to decode human emotions through **sentiment analysis** on social media conversations, primarily focusing on **Twitter** and **Reddit**. This is a **text classification** problem, where the goal is to predict the sentiment (e.g., **positive**, **negative**, **neutral**, **anger**, **joy**, **sadness**, etc.) from user-generated content.
Understanding emotional tone in social content is crucial for businesses, policymakers, and mental health organizations to gauge public opinion, identify crises, and tailor engagement strategies.
---
- **Build a sentiment analysis model** to classify the emotional tone of social media posts.
- **Improve the interpretability** and **accuracy** of classification using NLP and machine learning models.
- **Extract key insights** to understand emotional trends across different topics and timeframes.
- Evolved to **multi-label classification** to capture overlapping emotions.
---
The project follows the below workflow:
1. **Data Collection**
2. **Data Cleaning and Preprocessing**
3. **Exploratory Data Analysis (EDA)**
4. **Feature Engineering**
5. **Model Building (Baseline + Advanced Models)**
6. **Model Evaluation**
7. **Insights and Visualization**
8. **Conclusion and Reporting**
---
- **Dataset Name**: Emotion Recognition from Text
- **Source**: Kaggle / Twitter API / Reddit API
- **Type**: Unstructured text data
- **Records**: ~30,000 social media posts
- **Features**: Text, Emotion Label, Timestamp (optional)
- **Target Variable**: Emotion (e.g., joy, anger, fear, sadness, neutral, etc.)
- **Dataset Type**: Static, manually curated from multiple APIs
---
The following preprocessing steps were carried out on the dataset:
- Removed duplicates and null values
- Cleaned text (removed URLs, mentions, special characters, stopwords)
- Tokenized text and applied lemmatization
- Encoded target labels using **label encoding**
- Converted text into numeric format using **TF-IDF** and **Word2Vec**
- Balanced class distribution using **SMOTE** (Synthetic Minority Over-sampling Technique)
---
- Distribution of emotions using **count plots**
- Word clouds for each emotion category
- Emotion frequency by **word length**
- Correlation heatmaps of **TF-IDF** features
- **"Joy"** and **"Sadness"** were the most common sentiments.
- Posts with extreme word counts tended toward **negative** or **sarcastic** tones.
- Certain keywords strongly associated with specific emotions.
---
The following features were added during the engineering process:
- Word count
- Sentiment polarity and subjectivity
- Bigrams and trigrams for context
- **TF-IDF** for initial models; **Word2Vec** embeddings for neural models
- Reduced dimensionality using **PCA** for visualization purposes
---
1. **Logistic Regression**
2. **Random Forest Classifier**
3. **LSTM** (for advanced modeling using **Word2Vec**)
- **Train/Test Split**: 80/20
- **Evaluation Metrics**:
  - **Accuracy**: ~82% (best performing model)
  - **Precision/Recall/F1**: Evaluated for each emotion class
  - **ROC-AUC**: For binary emotion groups
---
- **Confusion Matrix**: Showed that **anger** and **fear** were often misclassified.
- **Feature Importance Plots** (Random Forest) highlighted emotional keywords.
- **ROC Curves**: Indicated strong separability for **joy** and **sadness**.
- **Word Clouds** and **t-SNE plots** used for visual representation of clusters.
---
- **Programming Language**: Python
- **IDE/Notebook**: Jupyter Notebook, Google Colab
- **Libraries**:
  - **pandas**, **numpy**, **scikit-learn**, **nltk**, **spacy**, **seaborn**, **matplotlib**, **WordCloud**, **XGBoost**, **Keras** (for LSTM)
- **Visualization Tools**: seaborn, matplotlib, Plotly
---
- **Theerthana R**: Data collection, cleaning, and preprocessing
- **Prithika J**: EDA, feature engineering
- **Iswariya G**: Model development and evaluation
- **Ishwarya K**: Visualization, documentation, and GitHub repository maintenance
---

## 12. How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/prithika-16/my-project.git
    ```

2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```


---


