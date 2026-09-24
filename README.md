# IMDb Movie Review Sentiment Analysis

## Project description

This project analyzes IMDb movie reviews and predicts whether each review is negative or positive.

- `0` = Negative sentiment
- `1` = Positive sentiment

The project uses pandas and seaborn for data analysis and visualization. A TF-IDF plus logistic-regression model is used for sentiment classification.

## Dataset files

Upload these files to Google Colab:

- `Train.csv` - 40,000 reviews
- `Valid.csv` - 5,000 reviews
- `Test.csv` - 5,000 reviews

Each file contains:

- `text` - movie review text
- `label` - sentiment label

## Requirements

```text
pandas>=2.0.0
numpy>=1.24.0
scikit-learn>=1.3.0
matplotlib>=3.7.0
seaborn>=0.12.0
jupyter>=1.0.0
notebook>=7.0.0
```

## Google Colab usage

1. Open `imdb_sentiment_analysis.ipynb` in Google Colab.
2. Run the installation cell.
3. Upload `Train.csv`, `Valid.csv`, and `Test.csv` when prompted.
4. Run the notebook cells from top to bottom.

The notebook performs:

1. Dataset loading with pandas
2. Missing-value and duplicate checks
3. Sentiment distribution analysis
4. Review-length and word-count analysis
5. Seaborn visualizations
6. Text cleaning
7. TF-IDF feature extraction
8. Logistic-regression training
9. Validation and test evaluation
10. Prediction on new reviews

## Dataset references

- Kaggle: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
- Stanford Large Movie Review Dataset: https://ai.stanford.edu/~amaas/data/sentiment/

## Project files

- `imdb_sentiment_analysis.ipynb` - analysis and machine-learning notebook
- `requirements.txt` - Python dependencies
- `project_report.docx` - project description and methodology report
