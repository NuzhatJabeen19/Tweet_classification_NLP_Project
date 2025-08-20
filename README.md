# Tweet Classification NLP Project

This project classifies tweets as disaster-related (1) or non-disaster (0) using machine learning and deep learning techniques. It demonstrates data preprocessing, feature extraction, model training, hyperparameter tuning, and evaluation.

## Project Structure

```
Tweet_classification_NLP_Project/
├── README.md
├── requirements.txt
├── Tweet_classification.ipynb
├── train.csv
```

## Dataset

- `train.csv`: Contains tweets and their labels (`target` column: 1 for disaster, 0 for non-disaster).

## Main Features

- **Data Cleaning**: Removes URLs, mentions, punctuation, numbers, and stopwords.
- **EDA**: Visualizes class distribution and tweet lengths.
- **Feature Extraction**: Uses CountVectorizer and TfidfVectorizer.
- **Models**: Logistic Regression, Multinomial Naive Bayes, Random Forest, and CNN (TensorFlow/Keras).
- **Hyperparameter Tuning**: Uses GridSearchCV for optimal parameters.
- **Evaluation**: Reports accuracy, F1-score, ROC AUC, precision, recall, and confusion matrix.

## Getting Started

1. Clone the repository:

    ```sh
    git clone <your-repo-url>
    cd Tweet_classification_NLP_Project
    ```

2. Install dependencies:

    ```sh
    pip install -r requirements.txt
    ```

3. Run the notebook:

    Open `Tweet_classification.ipynb` in Jupyter Notebook or VS Code and execute the cells.

## Requirements

See [requirements.txt](requirements.txt) for all dependencies.

## Results

| Model                        | Accuracy | F1-Score | ROC AUC |
|------------------------------|----------|----------|---------|
| CNN                          | 0.8004   | 0.7458   | 0.8466  |
| Logistic Regression (Tuned)  | 0.7984   | 0.7603   | 0.7918  |
| Multinomial Naive Bayes      | 0.7997   | 0.7514   | 0.7880  |
| Random Forest                | 0.7925   | 0.7558   | 0.7870  |

## License



## Author
Nuzhat Jabeen Amna
