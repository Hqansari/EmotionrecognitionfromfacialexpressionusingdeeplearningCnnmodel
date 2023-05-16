# EmotionrecognitionfromfacialexpressionusingdeeplearningCnnmodel
Deep facial expressions recognition using Opencv and VGG16 model. Recognizing facial expressions from images or Webcam

Emotion recognition from faces with Deep Learning CNN network

We have to prepare the data for the training

Download the fer2013.csv From Kaggle

Move it to data folder and rename it to fer2013.csv if it is necessary

Now you have the data for the training which you can find in the data folder

X_train shape: (nb_samples, 48, 48)

y_train shape: (nb_samples,)

After this you can start the training!
Training
Run train_emotion_recognizer.py

This will run the training and evaluate the trained model with the test data.

Real time prediction
