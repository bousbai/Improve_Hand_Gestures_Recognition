# Improve_Hand_Gestures_Recognition
Hand gestures provide humans a convenient way to interact with computers and many applications. However, factors such as the complexity of hand gesture models, differences in hand size and position, and other factors can affect the performance of the recognition and classification algorithms. Some developments of deep learning such as Convolutional Neural Networks (CNN) and Capsule Networks (CapsNets) have been proposed to improve the performance of image recognition systems in this particular field. While CNNs are undoubtedly the most widely used networks for object detection and image classification, CapsNets emerged to solve part of the limitations of the former. For this reason, in this work a particular ensemble of both networks is proposed to solve the American Sign Language recognition problem very effectively. The method is based on increasing diversity in both the model and the dataset. The results obtained show that the proposed ensemble model together with a simple data augmentation process produces a very competitive accuracy performance with the all considered datasets.
Runtime environment: Google Colab

Requirements:

Tensorflow==1.15

keras==2.2.4

Datasets:

Massey University:
https://www.massey.ac.nz/~albarcza/gesture_dataset2012.html

Static Hand Gesture ASL:
https://ieee-dataport.org/open-access/static-hand-gesture-asl-dataset

Kaggle ASL Alphabet:
https://www.kaggle.com/grassknoted/asl-alphabet

MNIST ASL:
https://www.kaggle.com/datamunge/sign-language-mnist
