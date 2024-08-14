# NLPSentimentAnalysis
A sentiment analysis project for amazon product reviews using nltk library (VADER and Roberta)

## Setup And Prerequisites
1) Obtain an API key from kaggle( Instruction available here: https://www.kaggle.com/docs/api)
2) Import the project in google colab
3) Run the first cell and import the API key as per screen instructions

## Analysis Information
1) The analysis was made only for the first 500 reviews but the scope of the dataset is much larger. The analysis size can be changed from cell:
df=df.head(500)
2) The overall sentiment of the review is leaning towards positive.
3) The VADER model predicted positive sentiment in lower rated reviews while the Roberta model predicted positive sentiment in the higher rated reviews.<br/>
   ![alt text](https://github.com/Anuragghosh12/NLPSentimentAnalysis/blob/2c5534aaf8714b90399a78d92932445ccf32b470/Roberta_POS.png?raw=true "Roberta Positive") <br/>
   ![alt text](https://github.com/Anuragghosh12/NLPSentimentAnalysis/blob/2c5534aaf8714b90399a78d92932445ccf32b470/VADER_POS.png>raw=true "VADER Positive")
