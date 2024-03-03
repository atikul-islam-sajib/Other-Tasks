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

## Configuration

Ensure any directory change commands (`os.chdir`) in `main1_train_BERT.py` and `main2_play_trained_model.py` are commented out or adapted to your environment.

## User Guide Notebook
visit the -> [Notebook training](https://atikul-islam-sajib.github.io/AC-GAN-deploy/).

## Usage

- **Train the Model:** Execute `main1_train_BERT.py` to train your model.
- **Test the Model:** Run `main2_play_trained_model.py` to test the model on new data.

## Expected Output

Testing the model will yield predictions with labels (`LABEL_0` for negative, `LABEL_1` for positive sentiment) and confidence scores. Example outputs:

```plaintext
[{'label': 'LABEL_1', 'score': 0.9997}]
[{'label': 'LABEL_0', 'score': 0.9985}]
...
```

## Requirements

- Python 3.9+
- Google Colab or similar Jupyter notebook environment or vs code
- Dependencies listed in `requirements.txt`

## Project Structure

- **src/**: Contains training and testing scripts.
- **requirements.txt**: Lists all necessary Python packages.
