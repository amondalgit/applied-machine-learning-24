# applied-machine-learning-24

## Assignment 1: Build prototype for Email Spam Classification

> [Data Source](https://www.kaggle.com/datasets/jackksoncsie/spam-email-dataset)

#### Project Steps

1. Build `prepare.ipynb` in which write the functions to
   - load the data from a given file path
   - preprocess the data (if needed)
   - split the data into **train** | **validation** | **test** 
   - store the splits at `train.csv` | `validation.csv` | `test.csv`
2. Build `train.ipynb` in which write the functions to
   - fit a model on train data
   - score a model on given data
   - evaluate the model predictions
   - validate the model
      - fit on train
      - score on train and validation
      - evaluate on train and validation
      - fine-tune using train and validation (if necessary)
3. Score 3 benchmark models on test data and select the best one