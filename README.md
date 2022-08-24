# Speech-Recognition
Speech recognition is the process of converting an acoustic signal, captured by a microphone or any peripherals to a set of words. This project takes the input audio file and returns the transcript of the audio file. The models used are from pytorch and audio is normalized using pytorch-audio.

The model will have two main neural network modules - N layers of Residual Convolutional Neural Networks to get audio patterns and Bidirectional Recurrent Neural Networks to capitalize on the features and the project uses Comet.ml and gradio to view and track the model's progress.
The Libre-Speech Dataset is used for training and the average word error after training is around 0.364 WER.

We can futher reduce this by opting for a bigger dataset and improve accuracy by providing a wide range of accents which should be possible with the mozilla speech dataset which is 10x bigger.
