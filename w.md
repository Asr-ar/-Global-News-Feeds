# Global News Feeds

## Abstract
Given a global news in different languages, we are challenged to discover the topics that occur in a collections of articles.

## Data
The datasets are selected from the [**Global News Feeds**](https://www.kaggle.com/therohk/global-news-week) and the [**Language Identification dataset**](https://www.kaggle.com/zarajamshaid/language-identification-datasst?select=dataset.csv).

- **Global News Feeds:** This dataset is a snapshot of most of the new news content published online over one week.   
It covers the seven day period from august 24 through august 30 for the years of 2017 and 2018.

- **Language Identification dataset:** Contains multiple langauge, and each language contains 1000 rows/paragraphs.

- Tested sample(15,000)


## Design and Algorithms

- **Apply Spacy Lemmatization**

    Cut word down to base form using vocabulary and morphological analysis.

- **Dimensions Reduction**

   **Principal Component Analysis (PCA)** with 4 components, over **Term Frequency-Inverse Document Frequency (TF-IDF)**.

- **Topic Modeling & Clustering**

  Apply **KMeans** with 4 centroids, and results most of the topics fall under:
    - Humanities
    - Cases and Accidents
    - Culture and Society 
    - Political


## Tools

- Software Platform:
    - Jupyter Notebook
- Programming Language:
    - Python
- Python Libraries:
    - Statistics libraries:
        - Sklearn
        - Statsmodels
    - Data manipulation libraries:
        - Pandas
        - Numpy
        - Spacy
        - NLTK
    - Visualization libraries
        - Matplotlib
        - Seaborn
    - Storage libraries
        - Pickle
        - SQLAlchemy

## Communication
Slides containing visualizations
