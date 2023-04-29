# semaxspaul_text_classification

>> My second deep learning project

In this notebook I aim to successfully classify movie reviews as positive or negative using the text of the review.

This notebook contains two main funtions "decode_review" and "encode_review" which I used to basically convert words to an integer vector and vice versa.

Using the integer vector, I trained a deep learning model to predict the sentiment of the movie review as either Positive (1) or Negative (0)

The accuracy of my model based on 200000 words of vocabulary was:
> Accuracy: 0.8715
  
I then saved and tested the model on an external review from IMDB website.

> I obtained a (10/10) movie review on Blank Panther Wakanda forever 2022 and saved it in ***'external_data_test.txt'*** file
>> Link: https://www.imdb.com/review/rw8669414/?ref_=tt_urv

There is room for improvement on this model. 
