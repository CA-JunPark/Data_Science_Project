# Data_Science_Project
BCIT 

Master of Science in Applied Computing 

COMP 9170 - Data Science Project - Group 4

## Repository Files

### Notebooks
- **Logistic_Regression.ipynb**: Implements a Logistic Regression model as a baseline approach for the toxic comment classification task.
- **CNN.ipynb**: Implements a 1D Convolutional Neural Network (TextCNN) using PyTorch for multi-label classification of toxic comments. It includes text preprocessing, tokenization, and model training with Focal Loss.
- **roberta.ipynb**: Fine-tunes a RoBERTa transformer model for the toxic comment classification task, leveraging pre-trained embeddings for better performance.

### Python Scripts
- **focal_loss.py**: Contains the `FocalLoss` class, a custom loss function designed to address class imbalance by down-weighting well-classified examples and focusing on hard-to-classify ones.

### Data
- **train.csv**: Original raw datasets.
- **trainset.csv, valset.csv, testset.csv**: Preprocessed training, validation, and testing datasets containing comments and their corresponding toxicity labels.
- **trainset_transformer.csv, valset_transformer.csv, testset_transformer.csv**: Datasets specifically preprocessed for transformer models.

