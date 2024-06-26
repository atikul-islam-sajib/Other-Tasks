# Sentiment Analysis with BERT

## Overview

This project utilizes BERT for sentiment analysis, allowing for the training and testing of sentiment classification on textual data. It's designed to be run in environments like Google Colab for ease of use and accessibility.

## Setup

1. **Clone the Repo:** Clone the project repository to get started.
   ```sh
   !git clone https://github.com/atikul-islam-sajib/Other-Tasks.git
   ```
2. **Install Requirements:** Navigate to the project directory and install required dependencies.
   ```sh
   %cd /content/Other-Tasks/projects/sentiment-analysis-bert/
   !pip install -r requirements.txt
   !pip install accelerate -U
   ```
## Requirements

- Python 3.9+
- Google Colab or similar Jupyter notebook environment or vs code
- Dependencies listed in `requirements.txt`

## Project Structure

- **src/**: Contains training and testing scripts.
- **requirements.txt**: Lists all necessary Python packages.


## VS Code Run
visit [VS code training pic ](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/sentiment-analysis-bert/Screenshoot-Training-VS.png)

## Configuration

Ensure any directory change commands (`os.chdir`) in `main1_train_BERT.py` and `main2_play_trained_model.py` are commented out or adapted to your environment.

## User Guide Notebook
visit the -> [Notebook training](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/sentiment-analysis-bert/bert_user's_guide.ipynb).

## Usage

- **Train the Model:** Execute `main1_train_BERT.py` to train your model.
- **Test the Model:** Run `main2_play_trained_model.py` to test the model on new data.

## Train model - Notebook
```sh
!python /content/Other-Tasks/projects/sentiment-analysis-bert/src/main1_train_BERT.py
```

## Test model - Notebook
```sh
!python /src/main2_play_trained_model.py
```


## Expected Output

Testing the model will yield predictions with labels (`LABEL_0` for negative, `LABEL_1` for positive sentiment) and confidence scores. Example outputs:

```plaintext
[{'label': 'LABEL_1', 'score': 0.9997}]
[{'label': 'LABEL_0', 'score': 0.9985}]
...
```
