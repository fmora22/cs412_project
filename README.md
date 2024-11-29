# **Cyberbullying Detection and Analysis**

This project focuses on detecting and analyzing cyberbullying on social media using machine learning techniques. The dataset comprises tweets labeled with various types of cyberbullying (e.g., gender, religion, age). The primary goals include text preprocessing, exploratory analysis, and building classification models, with a special focus on sentiment analysis.

---

## **Table of Contents**
1. [Purpose](#purpose)
2. [Dataset](#dataset)
3. [Project Workflow](#project-workflow)
4. [How to Run the Project](#how-to-run-the-project)
5. [Results](#results)
6. [Future Enhancements](#future-enhancements)
7. [Dependencies](#dependencies)
8. [Acknowledgments](#acknowledgments)

---

## **Purpose**

The objective of this project is to:
1. Build a machine learning model to classify tweets into different types of cyberbullying.
2. Explore the effectiveness of traditional text-based features vs. sentiment-based features in classification.
3. Investigate trends in sentiment polarity across different cyberbullying categories.

---

## **Dataset**

- **Source**: [Kaggle Dataset on Cyberbullying Tweets]([https://www.kaggle.com/datasets](https://kaggle.com/datasets/andrewmvd/cyberbullying-classification/code)).
- **Attributes**:
  - `tweet_text`: The text content of the tweet.
  - `cyberbullying_type`: The type of cyberbullying (e.g., gender, religion, etc.).
- **Size**: ~47,000 tweets.

---

## **Project Workflow**

### **1. Data Cleaning**
- Removed missing values and duplicates.
- Cleaned text by:
  - Lowercasing.
  - Removing emojis, URLs, and punctuation.

### **2. Exploratory Data Analysis**
- Analyzed class distributions.
- Investigated text length and token frequency distributions.

### **3. Sentiment Analysis**
- Used sentiment polarity scores (via TextBlob) as features.
- Compared sentiment trends across different cyberbullying categories.

### **4. Feature Engineering**
- Extracted text-based features using:
  - TF-IDF vectorization.
  - Sentiment polarity scores.

### **5. Modeling**
- Baseline model using TF-IDF.
- Sentiment-only model.
- Sentiment-augmented model combining TF-IDF and sentiment scores.

### **6. Model Evaluation**
- Evaluated models using metrics like accuracy, precision, recall, and F1-score.
- Visualized confusion matrices for insights.

---

## **How to Run the Project**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/fmora22/cs412_project.git
   cd cs412_project
   ```

2. **Install Dependencies**:
   Ensure you have Python 3.7+ and run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   Open the project notebook to preprocess the data, analyze trends, and train models:
   ```bash
   jupyter notebook cs412_project.ipynb
   ```

4. **Generate Results**:
   - Preprocessed data will be saved as `processed_tweets.csv`.
   - Model performance reports and visualizations will be displayed in the notebook.

---

## **Results**


---

## **Future Enhancements**

---

## **Dependencies**
The project requires the following libraries:
- `pandas`
- `numpy`
- `nltk`
- `sklearn`
- `matplotlib`
- `seaborn`
- `textblob`
- `scipy`

Install them via the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

---

## **Acknowledgments**
- Dataset contributors on [Kaggle](https://www.kaggle.com/).
- Python open-source libraries for data science and machine learning.

---

Feel free to update this as needed. This README now includes your repository link for others to easily access the project. Let me know if you’d like further refinements!
