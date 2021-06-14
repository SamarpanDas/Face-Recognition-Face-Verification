# Face-Recognition-Face-Verification

I have implemented a Face Recognition & Face Verification model by One Shot Learning using a Triplet Loss function.
A Deep Learning project wherein a specialised Convolutional Neural Network called the Inception Neural Network (Version 2) has been used.

The model requires only 1 image to train itself to recognise the face of the subject and is capable of Recognising it or Verifying it with an anchor image.


# Face-Verification
Face Verification task depicts a 1:1 classification where the image of the subject is compared to a pre - exisiting image of the person, the subject here claims to be. These two images are compared and if the similarity of the encoding of these to images is above the pre-set threshold, the system conveys the message that the 2 pictures are of the same person and subsequently performs the following tasks.
Note that for a Face Verification task it is required that the subject identifies himself to be a certain person so that his/her picture is taken and the systems checks his image with the person he claims to be


# Face-Recognition
Face Recognition task, unlike that of Face Verification is a 1:K classification task, with K being the number of images (encoding of images) stored in the database
In a Face Recognition task the subject does not need to identify himself as being a certain person, his picture is taken and it is then compared to all the images (or, encoding of images) and if the picture's similarity score with a certain image in the database is more than the set threshold, the subject's face is recognised and the subsequent tasks are allowed.



# Transfer-Learning
has been used to get the required network architecture and the weights for the purpose of this project.

The Inception Network architecture has been used here the implementation is present at the "inception_blocks_v2.py" file.

The Inception Network Very deep convolutional networks have been central to the largest advances in image recognition performance in recent years. One example is the Inception architecture that has been shown to achieve very good performance at relatively low computational cost.



# One-Shot-Learning 
Currently most deep learning models generally need thousands of labeled samples per class. Data acquisition for most tasks is very expensive. The possibility to have models that could learn from one or a few samples is a lot more interesting than having the need of acquiring and labeling thousands of samples. One could argue that a young child can learn a lot of concepts without needing a large number of examples. This is where one-shot learning appears: the task of classifying with only having access of one example of each possible class in each test task. This ability of learning from little data is very interesting and could be used in many machine learning problems.

The One Shot Learning algorithm has been implemented using the Triplet Loss function.



# Triplet-Loss
Triplet loss is a loss function for machine learning algorithms where a baseline (anchor) input is compared to a positive (truthy) input and a negative (falsy) input. The distance from the baseline (anchor) input to the positive (truthy) input is minimized, and the distance from the baseline (anchor) input to the negative (falsy) input is maximized.

![11760_2019_1612_Fig1_HTML](https://user-images.githubusercontent.com/55103824/121845847-b0d0c500-cd03-11eb-8f79-67529c3c1a90.png)

# References:
* Yaniv Taigman, Ming Yang, Marc'Aurelio Ranzato, Lior Wolf (2014). DeepFace: Closing the gap to human-level performance in face verification.  <https://www.cs.toronto.edu/~ranzato/publications/taigman_cvpr14.pdf![triplet_loss]>
* Florian Schroff, Dmitry Kalenichenko, James Philbin (2015). FaceNet: A Unified Embedding for Face Recognition and Clustering.
  <https://arxiv.org/abs/1503.03832>
* The pretrained model we use is inspired by Victor Sy Wang's implementation and was loaded using his code: 
  <https://github.com/iwantooxxoox/Keras-OpenFace>






