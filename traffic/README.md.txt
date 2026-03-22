Experiment flow:
during development I used different neural networks that impact on model performance

Initial model:
My first approach used a simple convolutional neural network with:
A flatten layer, one fully connected Dense layer, output layer with SoftMax activation

This network couldn't fix enough featured from images

Updated model:
MaxPooling2d, Conv2D(64 filters)

Adding Dropout layer 
Dropout(0.5)

I've tried different dense layer sizes:
Dense(64),  Dense(128), Dense(256)

Final model with more layers (two convolutional layers, two pooling layers), with dense hidden layer, dropout layer and SoftMax  output layer
is more accurate within reasonable time