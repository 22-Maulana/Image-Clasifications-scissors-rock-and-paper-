## Description

This is my final project in learning Machine Learning for beginners on the Dicoding platform.

## Training and Validation
![Training and Validation Accuracy](https://github.com/user-attachments/assets/24b31461-07ed-4192-9f72-810e452b7713)

The above algorithm trains an image classification model using data augmentation and deep neural networks. The process starts by defining image augmentations using ImageDataGenerator, such as rotation, shift, magnification, and inversion, which help to expand the training data. The image is normalized to have a range of pixel values between 0 and 1.
Data generators (train_generator and validation_generator) were used to process batches of 150x150 pixel images. The model was trained for 10 epochs using the augmented data, with the training and validation steps set according to the number of batches in the dataset.
Once the training is complete, the model is saved in .h5 format for reuse. Finally, accuracy and loss graphs are displayed to monitor the performance of the model during the training and validation process.


## Output
![Output Example](https://github.com/user-attachments/assets/32b80f49-bec6-42a9-8077-28ecbd563bbd)

## Conclusion

The above algorithm performs image augmentation to enlarge the training data, trains the model using a batch generator, validates the model performance at each epoch, and saves the trained model. Finally, the model performance is visualized through graphs to help understand how the model learns from the data.
