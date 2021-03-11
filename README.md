## Gemstone-Classification-with-Deep-Learning
We have taken a gemstone classification dataset that classifies 87 gemstones but for the sake of simplicity and to make the training easier, we took only 10 stones as classes for our dataset. The ten gemstones that we have chosen are as follows:
* Amber
* Amethyst
* Benitoite
* Coral
* Diamond
* Emerald
* Jade
* Ruby
* Sapphire Blue
* Topaz

Our model is a Convolutional Neural Network model that has 6 Convolutional layers having activation as 'relu', 5 Max-Pooling layers, 1 Flatten layer and 3 Dense layers out of which 2 have activation as 'relu' and the other has activation as 'softmax'. The model is then compiled with optimizer to be 'adam', loss function to be 'categorical_crossentropy'.

Our method of approach to increase accuracy was by using Data Augmentation, by increasing the number of layers in our CNN and by reducing the number of classes from 87 to 10 as we achieved a val_accuracy of around 55% when we trained the model using all the 87 classes which is lower when compared to the 85-90% accuracy that we achieved by training the model by just using 10 classes.

Current Training Accuracy | Current Validation Accuracy
------------------------- | ---------------------------
88.58% | 85.37%
