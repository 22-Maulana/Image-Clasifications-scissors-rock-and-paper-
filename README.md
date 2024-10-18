## Description

This is my final project in learning Machine Learning for beginners on the Dicoding platform. Image Clasification for Scissors, Rock, and Paper in hand with Tensor Flow

## Images Augmented

![Augmented Images](https://github.com/user-attachments/assets/2d0741a6-84ce-4108-a031-804302e1413f)

This algorithm prepares data augmentation to artificially expand the training dataset, normalize images, and efficiently generate batch data from the directory for both training and model validation.

## Model Sequentials

![Model Sequentials](https://github.com/user-attachments/assets/19619c35-ca38-4280-9cfb-f112a2d28496)

This model is a convolutional neural network designed for image classification with three classes. Convolution and pooling layers are used to extract image features, while dense layers translate those features into class predictions. The use of techniques such as dropout helps prevent overfitting, and the model is compiled using the categorical_crossentropy loss function as well as the Adam optimizer for training efficiency.

## Training and Validation
![Train Model](https://github.com/user-attachments/assets/5734c0ac-dbf6-4959-82d9-ba32c6d5a397)

This code runs the CNN model training process using a batch of training data and evaluates the model performance on validation data at each epoch. By setting steps_per_epoch and validation_steps, the model ensures to process all the data efficiently, and the results of the training are stored in the history variable, which can later be used to analyze the model's performance during training.

![Training and Validation Accuracy](https://github.com/user-attachments/assets/24b31461-07ed-4192-9f72-810e452b7713)

The above algorithm trains an image classification model using data augmentation and deep neural networks. The process starts by defining image augmentations using ImageDataGenerator, such as rotation, shift, magnification, and inversion, which help to expand the training data. The image is normalized to have a range of pixel values between 0 and 1.
Data generators (train_generator and validation_generator) were used to process batches of 150x150 pixel images. The model was trained for 10 epochs using the augmented data, with the training and validation steps set according to the number of batches in the dataset.
Once the training is complete, the model is saved in .h5 format for reuse. Finally, accuracy and loss graphs are displayed to monitor the performance of the model during the training and validation process.


## Output
![Output Example](https://github.com/user-attachments/assets/32b80f49-bec6-42a9-8077-28ecbd563bbd)

## Conclusion

The above algorithm performs image augmentation to enlarge the training data, trains the model using a batch generator, validates the model performance at each epoch, and saves the trained model. Finally, the model performance is visualized through graphs to help understand how the model learns from the data.
