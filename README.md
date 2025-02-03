# Trending YouTube Video Analysis 🚀📊

## Overview
This project conducts a vast analysis of YouTube videos, uncovering patterns in trending content and leveraging machine learning techniques to extract insights. The study includes data visualization, sentiment analysis, and predictive modeling to answer questions like:
- What are the most famous channels?
- What are the most liked and most disliked videos?
- Which countries have the most trending videos?
- What are the top videos per category?
- How do views vary by weekdays and weekends?
- Can we predict missing video categories?

## Project Structure
### 📊 Data Analysis
- **Handling Missing Data:** Replacing NaN values appropriately.
- **Top Countries & Categories:** Visualizing video trends across different regions.
- **Trending Trends:** Examining how videos trend over time.
- **Viewer Interaction:** Analyzing likes, dislikes, comments, and view counts.
- **Geographical & Time-Series Analysis:** Distribution of videos across regions and months.

### 📈 Machine Learning Models
- **Classification Models for Category Prediction**
  - **Algorithms Used:** Random Forest, Decision Tree, XGBoost, KNN, Gaussian Classifier.
  - **Techniques:** Classification, Ensemble Learning.
- **Sentiment Analysis & NLP**
  - **Word Cloud Visualization** of common words in trending video titles.
  - **TextBlob Sentiment Analysis** to classify video sentiments.

### 📜 Data Processing
- **Preprocessing Steps:**
  - Cleaning and structuring YouTube video data.
  - Converting timestamps into readable formats.
  - Handling missing values and feature engineering.

### ⚙️ Installation
1. Install the required dependencies:
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost nltk wordcloud textblob plotly
   ```

### 🚀 Running the Code
1. **Clone the repository**  
   ```sh
   git clone https://github.com/vedant713/Trending-YouTube-Analysis.git
   cd Trending-YouTube-Analysis
   ```

2. **Run the main analysis script**  
   ```sh
   python youtube_analysis.py
   ```

### 🔍 Results & Insights
- **Top Channels & Video Categories:** Identifies the most popular channels and content types.
- **Trending Time Insights:** Determines when videos are most likely to trend.
- **Correlation Analysis:** Explores the relationships between views, likes, dislikes, and comments.
- **Sentiment Analysis:** Evaluates the sentiment of trending videos.

### 📜 License
This project is licensed under the **MIT License**.

## Author  
**Vedant** - [GitHub](https://github.com/yourprofile)
