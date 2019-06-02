# Apply-t-SNE-on-Amazon-reviews-with-polarity-based-color-coding
Apply T-SNE on Amazon food review data set.Since, t-sne accept dense matrix i will consider less data points. 
Amazon Fine Food Reviews Analysis with KNN
Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews
(https://www.kaggle.com/snap/amazon-fine-food-reviews)
The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.
Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10
Attribute Information:
1. Id
2. ProductId - unique identifier for the product
3. UserId - unqiue identifier for the user
4. ProfileName
5. HelpfulnessNumerator - number of users who found the review helpful
6. HelpfulnessDenominator - number of users who indicated whether they found the review
helpful or not
7. Score - rating between 1 and 5
8. Time - timestamp for the review
9. Summary - brief summary of the review
10. Text - text of the review

Objective:
Given a review, determine whether the review is positive or negative. We will determine whether a review is positive or negative based on ratings.If score is 1 or 2 then review is negative and if thescore is 4 or 5 then review is positive.

Bellow metioned are the steps that we are going to follow:-
1. Data pre-processing step : In this phase we will be performing the following operations:
2. Removal of Stop words.
3. Removal of punctuations marks.
4. Removal of HTML tags.
5. Snow ball stemming of words.
6. Conversion of text into lower case.
7. Using time based splitting, create train and test dataset.
8. Create function to find optimal k.
9. Use vectorization methods to convert text into vectors.Bellow mentioned are the methods that

We will also use:
1. BagOfWords(BOW)
2. Word2Vec
3. tfidf
4. avg. Word2Vec
5. tfidf Word2Vec
6. On each vectorization method we will be finding optimal K and perform KNN.
7. Score Prediction
8. Confusion Matrix
