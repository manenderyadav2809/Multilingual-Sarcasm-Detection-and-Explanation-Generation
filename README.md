# Sarcasm Detection

### Prerequisites
Python 3.7 or higher
Required Python libraries:
transformers
torch
pandas
numpy
scikit-learn
tqdm

### Install dependencies using:

pip install transformers torch pandas numpy scikit-learn tqdm

### How to Use
1. Dataset
Ensure the datasets are stored in the following structure:

bash
Copy code
preprocessed data/news Headlines/
    ├── news_headlines_train.csv
    ├── news_headlines_dev.csv
    ├── news_headlines_test.csv
2. Model Training
Run the script to train the model:

bash
Copy code
python bert_head_final.py

Download Pre-trained Weights:
Pre-trained Model Weights

Load Pre-trained Weights: Place the downloaded file in the project directory and uncomment the following lines in the script:
