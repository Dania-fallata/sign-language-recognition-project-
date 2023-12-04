 Building a sign language recognition app using Python, Mediapipe, and an RNN model.

Here's an outline of the steps involved in project:

Data Collection: the team members collected data for sign language gestures. This data likely consists of videos or sequences of images capturing different signs.

Feature Extraction with Mediapipe: Mediapipe is a powerful library that provides various computer vision solutions, including hand tracking and pose estimation. using the hand tracking module in Mediapipe to extract hands, pose and face  landmarks or other relevant features from each frame of the collected data. These features served as inputs to the classification model.

Data Preprocessing and Labeling:after we extracted the features, we saved data as Numpy arrays: To feed the data into the LSTM model, we saved the preprocessed data as numpy arrays. Numpy is a popular library for efficient numerical computations in Python.

the splitting the data into training and testing sets, and assigning labels to each sample based on the corresponding sign gesture.

LSTM Model Training: we designed and train an RNN model, specifically an LSTM (Long Short-Term Memory) model, for sign language recognition. LSTM models are well-suited for sequence data like time series or sequential gestures. we used keras library to build and train the LSTM model.

Model Evaluation: After training the model, we evaluate its performance.
