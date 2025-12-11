# Sentiment & Geographical Analysis :speech_balloon:

This project focuses on performing **Sentiment Analysis** on restaurant reviews across multiple categories.  
Using Natural Language Processing (NLP), the goal is to classify customer sentiment (Positive, Neutral, Negative) and extract insights that help to understand customer preferences and service quality across regions.



## :bar_chart: Project Overview

Restaurant reviews provide valuable insights about:
- Food quality  
- Service experience  
- Price expectations  
- Ambience  
- Customer satisfaction  

This project walks through **multiple levels (Level 1 → Level 3)** to progressively build sentiment analysis capabilities.



## :file_folder: Project Structure

    📦 Cuisine-Restaurant-Sentiment-Analysis
    │
    ├── Dataset.csv # Raw dataset of restaurant reviews
    │
    ├── Level 1.ipynb # Basic data exploration & preprocessing
    ├── Level 2.ipynb # Feature engineering & ML model building
    ├── Level 3.ipynb # Advanced NLP + visualization + insights
    │
    └── README.md # Project documentation




## :open_file_folder: Dataset Description

**Dataset.csv** contains fields such as:

- `Review` – customer review text  
- `Cuisine` – type of cuisine (e.g., Italian, Indian, Chinese, etc.)  
- `Restaurant` – restaurant name  
- `Rating` – given rating  
- `Sentiment` – manually labeled or derived sentiment  
- Additional metadata depending on your dataset  


## :gear: Project Levels Breakdown

###  Level 1 — Data Exploration & Cleaning
- Load dataset  
- Remove duplicates, handle missing values  
- Text preprocessing:
  - Lowercasing  
  - Stopwords removal  
  - Tokenization  
  - Lemmatization  



###  Level 2 — Machine Learning-Based Sentiment Analysis
- Feature extraction:  
  - TF-IDF  
  - Bag-of-Words  
- ML Model training:
  - Logistic Regression  
  - Naive Bayes  
  - SVM  
- Model evaluation: accuracy, confusion matrix, classification report  



###  Level 3 — Advanced NLP & Visualization
- Apply deep learning or transformer-based approach (optional)  
- Sentiment distribution by cuisine  
- Word clouds for positive vs negative reviews  
- Restaurant-level sentiment insights  
- Visualization using Matplotlib / Seaborn / Plotly  
- Business insights for cuisine category performance  



## Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **NLTK / spaCy** for NLP
- **Scikit-Learn** (ML models)
- **Matplotlib / Seaborn** (visualization)
- **Jupyter Notebook**



## Key Insights You Can Derive

- Which cuisines have the best sentiment  
- Which restaurants receive the most negative reviews  
- Common positive/negative keywords  
- Relationship between ratings and sentiment  
- Sentiment trend across cuisines  


## :handshake: Contributions

Contributions are welcome!  
Feel free to submit issues or pull requests.


## :page_facing_up: License

This project is licensed under the **MIT License**.


