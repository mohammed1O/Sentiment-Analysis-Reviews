# Sentiment Analysis for Amazon Reviews
Environment Setup and Dependencies
To run the project, ensure you have the following dependencies installed:

Python:
Python 3.x

Required Libraries:
You can install the required libraries using pip:


! pip install pandas
! pip install seaborn
! pip install matplotlib
! pip install nltk
! pip install scikit-learn
! pip install transformers

Download the dataset:

The dataset used in this project is Amazon Fine Food Reviews, which can be downloaded from Kaggle (https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews).

Set up the environment:

Install all the required libraries (see above).

Run the Python script:

After setting up the environment, you can run the script. Ensure the Reviews.csv file is in the correct path (../input/amazon-fine-food-reviews/Reviews.csv), or modify the file path accordingly.


python sentiment_analysis.py
Output:

The script will process the reviews and generate sentiment scores using both VADER and RoBERTa models. 
