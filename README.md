This project has been completed as a part of Udacity DEEP LEARNING nanoDegree program. Sentiment Analysis Model with RNN LSTM has been deployed using Amazon SageMaker.


Our goal will be to have a simple web page which a user can use to enter a movie review. The web page will then send the review off to our deployed model which will predict the sentiment of the entered review.


#General Outline
Recall the general outline for SageMaker projects using a notebook instance.

- Download or otherwise retrieve the data.
- Process / Prepare the data.
- Upload the processed data to S3.
- Train a chosen model.
- Test the trained model (typically using a batch transform job).
- Deploy the trained model.
- Use the deployed model.
