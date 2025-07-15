# Yelp Review Analysis

EDA & Clustering of Yelp Reviews using NLP

This project analyzes Yelp reviews to extract insights, identify patterns, 
and cluster review texts using natural language processing (NLP) and unsupervised learning.
Demonstrates: EDA, feature engineering, unsupervised learning and visualization in Python.

## Project Goals

- Explore the different attributes of very active users vs "regular" users
- Explore the text, narrative and rating data from Yelp reviews
- Apply text preprocessing and feature extraction (TF-IDF, word embeddings, etc.)
- Perform clustering to discover groups of similar reviews/users
- Visualize key findings with graphs and word clouds

## Main Tools & Technologies

- Python (pandas, scikit-learn, nltk, matplotlib)
- Jupyter Notebook

## Results

- Identified main words and patterns for each users group
- Found "noise" reviews with unique words
- Clustering revealed high textual diversity and challenge in distinguishing user groups based only on text
- Presented visualizations to summarize key insights

## Files

- `notebooks/yelp_analysis.ipynb` – Main Jupyter notebook with all analysis steps
- `data/` – Example data files (not full dataset)
- `results/` – Key graphs and summary tables

## How to Run

1. Clone this repository
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Open `notebooks/yelp_analysis.ipynb` in Jupyter and run all cells

## Credits

Based on [Yelp Open Dataset](https://www.yelp.com/dataset).

---

> *This project was developed as part of my data science studies and personal learning. Feedback and suggestions are welcome!*
