# FaceIDVerification

you should create two main directories: IDs and Selfies.

IDs
The IDs directory includes images of people's national IDs. Each image corresponds to a specific individual and is labeled accordingly.

Selfies
The Selfies directory contains live camera photos of individuals, which are used for verification purposes. Each selfie corresponds to a person whose national ID is stored in the IDs directory.

Model and Training
We utilized a Siamese network architecture with triplet loss for face verification. The model was trained from scratch using a convolutional neural network (CNN) architecture. No pre-trained models were used in the training process.

Dataset
The model was trained on the Labeled Faces in the Wild (LFW) dataset. The training achieved a validation accuracy of 72%.

Please refer code in this repository for more details on the implementation and usage of the face verification system.
