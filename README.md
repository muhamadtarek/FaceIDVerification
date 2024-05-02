# FaceIDVerification



<p>you should create two main directories: <strong>IDs</strong> and <strong>Selfies</strong>.</p>

<h2>IDs</h2>
<p>The <strong>IDs</strong> directory includes images of people's national IDs. Each image corresponds to a specific individual and is labeled accordingly.</p>

<h2>Selfies</h2>
<p>The <strong>Selfies</strong> directory contains live camera photos of individuals, which are used for verification purposes. Each selfie corresponds to a person whose national ID is stored in the <strong>IDs</strong> directory.</p>

<h2>Model and Training</h2>
<p>We utilized a Siamese network architecture with triplet loss for face verification. The model was trained from scratch using a convolutional neural network (CNN) architecture. No pre-trained models were used in the training process.</p>

<h2>Dataset</h2>
<p>The model was trained on the Labeled Faces in the Wild (LFW) dataset. The training achieved a validation accuracy of 72%.</p>

<p>Please refer to the code in this repository for more details on the implementation and usage of the face verification system.</p>
