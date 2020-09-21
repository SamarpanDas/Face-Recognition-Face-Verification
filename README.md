# Face-Recognition-Face-Verification

I have implemented a Face Recognition & Face Verification model by One Shot Learning.
A Deep Learning project wherein a specialised Convoluitonal Neural Network called the Inception Neural Network (Version 2) has been used.

The model requires only 1 image to train itself to recognise the face of the subject and is capable of Recognising it or Verifying it with an anchor image.


# Face-Verification
Face Verification task depicts a 1:1 classification where the image of the subject is compared to a pre - exisiting image of the person the subject ow claims to be.
These two images are compared and if the similarity of the encoding of these to images is above the threshold, the system conveys the message that the 2 pictures are of the same person and subsequently performs the following tasks.
Note that for a Face Verification task it is required that the subject identifies himself to be a certain person so that his/her picture is taken and the systems checks his image with the person he claims to be


# Face-Recognition
Face Recognition task, unlike that of Face Verification is a 1:K classification task, with K being the number of images (encoding of images) stored in the database
In a Face Recognition task the subject does not need to identify himself as being a certain person, his picture is taken and it is then compared to all the images (or, encoding of images) and if the picture's similarity score with a certain image in the database is more than the set threshold, the subject's face is recognised and the subsequent tasks are allowed.





