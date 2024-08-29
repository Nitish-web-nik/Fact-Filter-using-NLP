# 📰 FACT FILTER: DETECTING FAKE NEWS USING MACHINE LEARNING 🔍🧠

## 🎯 Objective

In today's digital age, misinformation spreads faster than ever. The goal of this project was to develop a robust machine learning model that can differentiate between real and fake news articles with high accuracy. By training on a diverse dataset of authentic and fraudulent news, the model aims to safeguard the integrity of information online. 🛡️


## 🔍 Feature Extraction

To equip our model with the necessary tools for classification, we extracted several key features from the text data:

1. **Text-Based Features** ✍️
   - **TF-IDF**: Term Frequency-Inverse Document Frequency helps quantify the importance of words in the news articles.
   - **Bag of Words**: Converts the textual data into a matrix of word counts, providing a foundation for model training.
   - **Word2Vec**: Transforms words into continuous vector spaces, allowing the model to understand semantic relationships.

2. **Content Analysis** 🧐
   - **Regex**: Regular expressions were utilized to extract specific text patterns, such as dates and URLs, which are often indicators of fake news.

These features provide the foundation for our machine learning model to effectively classify news articles as real or fake.

## 🧠 Models & Training

We split our dataset into an 80/20 ratio for training and testing, ensuring that the model is well-validated. The models we implemented include:

- **Logistic Regression** 📈
- **Decision Trees** 🌳
- **Random Forest** 🌲
- **Gradient Boosting** 🚀

Each model was trained and evaluated using key metrics like accuracy, precision, recall, and F1-score. Our rigorous evaluation ensured that the best-performing model was chosen for deployment.

## 🛠️ Tools Used

For this project, we used a range of tools and libraries, including:

- **Python** 🐍
- **Scikit-learn** 📊
- **NLTK** 🗣️
- **Pandas** 🐼
- **NumPy** 🔢

These tools allowed us to preprocess the data, extract meaningful features, and build and evaluate our machine-learning models effectively.


## 🚀 Next Steps

Looking ahead, the Fact Filter project could be expanded into a real-time browser extension or integrated with social media platforms to combat the spread of fake news. Imagine an online world where misinformation is instantly flagged and stopped in its tracks! 🌐🛡️

---

Stay informed and keep the truth alive! 🔍
