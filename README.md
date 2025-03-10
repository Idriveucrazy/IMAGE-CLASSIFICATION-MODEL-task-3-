# IMAGE-CLASSIFICATION-MODEL-task-3-
COMPANY : CODETECH IT SOLUTIONS

NAME : VED SUHAS KULKARNI

INTERN ID : CT04WC71

DOMAIN : MACHINE LEARNING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

DESCRIPTION OF TASK : 
This is a Convolutional Neural Network (CNN) designed for image classification using the CIFAR-10 dataset. The model classifies images into 10 categories such as airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

What the Model Does:
A.Loads the CIFAR-10 dataset (60,000 images, 32x32 pixels each).

B.Preprocesses the images by normalizing pixel values (0 to 1 range).

C.Applies data augmentation such as rotation, flipping, and zoom to generate more diverse training data.

D.Builds a CNN model consisting of:
   Conv2D layers for feature extraction.
   MaxPooling layers to reduce image dimensions.
   Dropout layers to prevent overfitting.
   Dense layers for classification.
   
E.Uses EarlyStopping to stop training when no improvement is observed.

F.Trains the model for 5 epochs (reduced for faster training).

G.Evaluates the model's accuracy on test data.

Expected Output Accuracy : 
1.Training Accuracy: Around 75% - 85%.
2.Test Accuracy: Around 70% - 80%.
3.Training time: Around 2-3 minutes (depending on your machine).

OUTPUT : 
![Image](https://github.com/user-attachments/assets/51eff3bf-74ab-41c1-b43b-104bb0abd422)
