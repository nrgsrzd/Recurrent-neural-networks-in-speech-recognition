# Recurrent-neural-networks-in-speech-recognition
This project uses RNNs for speech recognition from audio files and text data. LSTM, RNN, and GRU models are trained on preprocessed data and evaluated using loss, accuracy, and f1-score metrics. The best model is chosen and some output samples are reported.

## Preprocessing

Before training the models, necessary preprocessing steps should be performed on the dataset to prepare it for the models. This includes tasks such as feature extraction, normalization, and splitting the dataset into training, validation, and test sets. One common feature extraction technique used in speech recognition is Mel Frequency Cepstral Coefficients (MFCCs), which can be calculated using the `python_speech_features.mfcc()` function in the Librosa library.

## Models

Three types of RNNs, namely LSTM, RNN, and GRU, will be considered for the speech recognition task. The architectures and number of layers for each model are arbitrary, but the models should be structured in a way that allows for comparison with each other. This includes having the same activation function, loss function, and optimizer for all three models. The model training will be performed using TensorFlow, a popular open-source machine learning library.

