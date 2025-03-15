# Amazon Fine Food Review Sentiment Analysis

This project demonstrates sentiment analysis on the Amazon Fine Food Reviews dataset using pre-trained models. It utilizes three distinct approaches: VADER (Valence Aware Dictionary and sEntiment Reasoner), RoBERTa (a pre-trained model from HuggingFace), and the HuggingFace Sentiment Analysis Pipeline, showcasing a variety of techniques for analyzing sentiment.

## Approaches Used

- **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: A rule-based model for sentiment analysis using the bag-of-words approach.
- **RoBERTa Pretrained Model from HuggingFace**: A transformer-based model fine-tuned for sentiment classification.
- **HuggingFace Sentiment Analysis Pipeline**: A streamlined tool that simplifies the application of pre-trained models for sentiment analysis.

## Steps Covered

1. **Data Preparation**: Basic text cleaning and exploration of the Amazon Fine Food Reviews dataset.
2. **Sentiment Analysis**:
   - Applied VADER for rule-based sentiment scoring.
   - Used the RoBERTa pre-trained model for robust classification.
   - Implemented HuggingFace's Sentiment Analysis Pipeline for quick and effective sentiment detection.
3. **Visualization**: Insights and trends visualized using Matplotlib and Seaborn.

## Results

This project emphasizes the practical application of pre-trained models for sentiment analysis rather than building models or evaluating their performance. The analysis provides meaningful sentiment classifications for the Amazon Fine Food Reviews dataset, leveraging the strengths of VADER, RoBERTa, and the HuggingFace pipeline.

## Tech Stack

**Language:**
- `python`

**Libraries:**
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `nltk`
- `transformers` (HuggingFace)
- `vaderSentiment`

## Authors

- [@shibangibaidya](https://www.github.com/shibangibaidya)

## Deployment

To clone and run this project, use the following commands:

```bash
git clone https://github.com/shibangibaidya/Amazon_Fine_Food_Review_Sentiment_Analysis.git
cd Amazon_Fine_Food_Review_Sentiment_Analysis
jupyter notebook sentiment-analysis.ipynb
