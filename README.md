## Sentiment Analysis of Reviews Using VADER and RoBERTa 
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
Download the Dataset:
The dataset used in this project is Amazon Fine Food Reviews, which can be downloaded from Kaggle:

Amazon Fine Food Reviews Dataset

Set up the Environment:
Install all the required libraries (see above).

Download the Reviews.csv file from Kaggle.

Run the Python Script:
After setting up the environment, you can run the script. Ensure the Reviews.csv file is in the correct path (../input/amazon-fine-food-reviews/Reviews.csv), or modify the file path accordingly.

To run the script, use the following command:


python sentiment_analysis.py
Output:
The script will process the reviews and generate sentiment scores using both VADER and RoBERTa models. The results will be displayed in terms of sentiment classification (positive, negative, or neutral) for each review.
