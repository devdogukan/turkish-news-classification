# Turkish News Classification

A machine learning-based model for categorizing Turkish news articles into different categories.

## Project Overview

This project develops a deep learning model to classify Turkish news articles into various categories based on their content. The classification system uses natural language processing (NLP) techniques to analyze the text of news articles and predict their categories.

## Categories

The model classifies news into the following categories:
- Politics (Siyaset)
- Economy (Ekonomi)
- Sports (Spor)
- Technology (Teknoloji)
- Health (Sağlık)
- World News (Dünya)
- Culture (Kültür)

## Technical Details

- **Model Architecture**: Deep learning model using word embeddings and LSTM layers
- **Language**: Turkish
- **Performance**: ~85% accuracy on test data
- **Implementation**: Python, TensorFlow/Keras

## Results

The model achieves robust performance across all categories:
- Overall accuracy: 85.2%
- Highest performance in Sports (F1-score: 0.94)
- Balanced performance across other categories (F1-scores: 0.81-0.89)

## Repository Contents

- `turkish-news-categorization.ipynb`: Jupyter notebook containing the full code for data exploration, model development, training, and evaluation
- Trained model files and tokenizer
- Dataset information

## License

This project is licensed under the MIT License - see the LICENSE file for details.
