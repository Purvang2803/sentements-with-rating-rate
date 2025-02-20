## 📌 Overview
This project analyzes customer reviews and ratings from an e-commerce dataset to generate a **New Score** that combines sentiment polarity and product ratings. Using this **New Score**, the system recommends similar products based on **cosine similarity**.

## 🚀 Features
- **Sentiment Analysis**: Extracts sentiment polarity from customer reviews.
- **New Score Calculation**: Merges sentiment polarity and ratings to create a meaningful score.
- **Normalization**: Scales the new score between 0 and 1 for better comparison.
- **Product Recommendation**: Uses cosine similarity to find similar products based on customer sentiment.

## 📂 Dataset
The dataset consists of **women's clothing reviews**, including the following columns:
- `Clothing ID` - Unique product identifier.
- `Review Text` - Customer's written feedback.
- `Rating` - Customer rating (1 to 5).
- `Sentiment` - Computed sentiment polarity of the review.
- `New Score` - Product score based on rating and sentiment.

## 📊 Installation & Usage
### 1️⃣ Install Dependencies
Ensure you have Python and install the required libraries:
```bash
pip install pandas numpy sklearn seaborn matplotlib textblob
```

### 2️⃣ Run the Jupyter Notebook
Open and run the notebook `sentiments_with_rating_rate.ipynb` to:
- Load the dataset
- Compute sentiment scores
- Generate recommendations

## 📈 Visualizations
The analysis also includes:
- **Word Clouds** for positive and negative reviews
- **Sentiment Distribution Pie Chart**
- **Sentiment Score Histogram**
- **Average Sentiment by Rating Bar Chart**

## 💡 Future Improvements
- Enhance the recommendation algorithm using advanced NLP techniques.
- Incorporate deep learning models for better sentiment analysis.
- Deploy as a web-based recommendation system.

## 🛠 Tech Stack
- **Programming Language**: Python 🐍
- **Libraries**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, TextBlob

## 🤝 Contributing
Feel free to fork the repo, create a new branch, and submit a pull request for improvements! 🚀

