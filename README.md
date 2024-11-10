# British Airways Review Analysis

### Project Overview
This project analyzes customer reviews for British Airways, focusing on sentiment and topics within reviews. Using Python, web scraping, and natural language processing (NLP), the project extracts insights from Skytrax reviews to evaluate customer satisfaction and identify common areas of feedback, such as service quality, food, and refund experiences.

### Project Objectives
- Scrape British Airways customer reviews from Skytrax.
- Perform data cleaning and preprocessing on the review data.
- Conduct sentiment analysis to categorize reviews as positive, negative, or neutral.
- Apply topic modeling to identify frequently discussed themes.
- Visualize findings and present insights.

### Files in the Repository
- **analysis_notebook.ipynb**: Jupyter notebook with all data analysis, including web scraping, sentiment analysis, and visualizations.
- **BA_reviews.csv**: Dataset with scraped reviews (if permitted to share).
- **presentation.pptx**: PowerPoint slide summarizing key insights for stakeholders.
- **README.md**: Project documentation.

### Tools and Libraries Used
- **Python**: Main language for data analysis.
- **BeautifulSoup**: For web scraping Skytrax reviews.
- **pandas**: For data cleaning and manipulation.
- **TextBlob**: For sentiment analysis.
- **scikit-learn**: For CountVectorizer and topic modeling with Latent Dirichlet Allocation (LDA).
- **matplotlib, seaborn**: For data visualization.
- **wordcloud**: To visualize frequently used words in reviews.

### Project Workflow
1. **Data Collection**: Scrape customer reviews from Skytrax using BeautifulSoup.
2. **Data Preprocessing**: Clean text data and extract relevant fields (review text, rating, recommendation).
3. **Sentiment Analysis**: Categorize each review based on sentiment polarity (positive, neutral, or negative).
4. **Topic Modeling**: Use LDA to identify main topics within negative reviews, such as food quality, refund issues, and overall service.
5. **Visualization**: Generate word clouds, bar charts, and pie charts to illustrate sentiment distribution and topic frequency.
6. **Presentation**: Summarize findings in a PowerPoint slide for stakeholder presentation.

### How to Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/BritishAirwaysReviewAnalysis.git
   cd BritishAirwaysReviewAnalysis
   ```

2. **Install required libraries**:
   ```bash
   pip install -r requirements.txt
   ```
   *Note: You might need to create this `requirements.txt` file if it doesn't exist. To generate it, run `pip freeze > requirements.txt`.*

3. **Run the analysis notebook**:
   Open `analysis_notebook.ipynb` in Jupyter Notebook or Jupyter Lab and run each cell to reproduce the analysis.

### Key Findings
- **Sentiment Distribution**: A high percentage of reviews are negative, indicating prevalent customer dissatisfaction.
- **Common Issues**: Topics like "food quality," "refunds," and "service delays" are common in negative reviews.
- **Business Recommendations**: British Airways could improve customer experience by addressing food quality, better handling refund requests, and improving customer service response times.

### Future Work
- **Automate data scraping** for real-time monitoring of reviews.
- **Expand analysis** to cover additional review platforms.
- **Sentiment fine-tuning**: Use more sophisticated NLP techniques, such as BERT, for better sentiment classification.
