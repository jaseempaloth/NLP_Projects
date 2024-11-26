# Sentiment Analysis with Transformers and NLTK

## Description
This project focuses on sentiment analysis using Amazon reviews as the dataset. It implements multiple techniques to analyze sentiments, ranging from traditional methods to advanced transformer-based approaches. The notebook demonstrates preprocessing, implementation, and evaluation of sentiment analysis models.

## Approaches
1. **VADER (Valence Aware Dictionary and sEntiment Reasoner)**  
   A bag-of-words approach leveraging a lexicon to determine sentiment scores of text.

2. **RoBERTa Pretrained Model**  
   A transformer-based model fine-tuned for sentiment analysis, providing state-of-the-art results.

3. **Huggingface Pipeline**  
   An easy-to-use pipeline from the Huggingface library for sentiment analysis using transformers.

## Dependencies
The following libraries are required for this project:
- `transformers`
- `nltk`
- `torch`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## Usage
1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>