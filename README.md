# Youtube_Analysis
This repository provides a comprehensive analysis of YouTube channel data to uncover trends, optimize content strategies, and gain competitive insights. Using Python, Pandas, Matplotlib, and Seaborn, we deliver stunning visualizations and predictive models to empower content creators and marketers. 🎥✨
 # 🎯 Project Overview
This project analyzes YouTube data to provide actionable insights for growing your channel. Key objectives include:
- Trend Analysis: Identify the latest YouTube trends to enhance content strategies.
- Audience Engagement: Understand viewer sentiment and engagement through metrics like subscribers and views.
- Competitor Insights: Analyze competitor channels to stay ahead in the YouTube space.
- Predictive Modeling: Use machine learning (e.g., Linear Regression, Random Forest, Logistic Regression) to predict channel success.
- Data Visualization: Create clear and beautiful visualizations to simplify complex data.
# 📈 Features
- Data Cleaning and Preparation: Ensure high-quality data for robust analysis.
- Time Series Analysis: Track changes in channel metrics over time.
- Sentiment Analysis: Analyze viewer sentiment (planned for future updates).
- Segmentation Analysis: Divide audiences into segments for targeted strategies.
- Competitor Analysis: Gain insights from top-performing channels.
- Machine Learning: Predict subscriber counts and classify channel performance.
- Visualizations: Explore data through barplots, scatterplots, and heatmaps.
# 📊 Visualizations
This project includes a variety of visualizations to uncover YouTube trends and insights:
- Barplots:
 1. Top 10 Channels by Subscribers: Visualize leading channels by subscriber count (Blues_d palette).
 2. Top 10 Channels by Earnings: Compare estimated yearly earnings (Greens_d palette).
 3. Top 10 Countries by Channel Count: Show geographic distribution of top channels (Oranges_d palette).
- Channels by Category: Analyze category popularity with a gradient effect (viridis palette).
- Channels by Country: Explore channel distribution by country (magma palette).
- Feature Importances: Highlight key predictors (e.g., video views, uploads) from a Random Forest model (inferno palette).
- Scatterplots:
 1. Education Enrollment vs. Unemployment Rate: Examine external factors influencing YouTube trends (PuBu gradient).
 2. True vs. Predicted Subscribers: Evaluate Linear Regression performance with a diagonal reference line (viridis gradient).
- Heatmap:
- Confusion Matrix: Assess Logistic Regression performance with F1-score barplot (PuBu palette).
These visualizations are implemented in Jupyter Notebooks using Matplotlib and Seaborn, ensuring clarity and aesthetic appeal.
## Installation
Clone the Repository:
```
git clone https://github.com/VibeCipher/YouTube_Analysis.git
cd YouTube_Analysis
```
Set Up a Virtual Environment (optional but recommended):
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
Install Dependencies:
```
pip install -r requirements.txt
```
Required packages include:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly
- nltk

Launch Jupyter Notebook:
```
jupyter notebook
```
