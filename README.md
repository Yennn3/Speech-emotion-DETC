# Speech-emotion-DETC
Create a speech emotion detection model from scratch.

It's a simple project to create a speech emotion detection model with RAVDESS Emotional speech audio.
The path of the dataset: https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio

The get_data.ipynb processes the dataset of audio files, extracts features from each audio file, maps them to emotion labels, and converts the data into tensors for training Then you can use train.ipynb to train your own model. The infer.ipynb is used to load the pre-trained model for inference.
