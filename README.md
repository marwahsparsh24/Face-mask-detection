## Face Mask Detection

Face mask detection has a wide range of applications, from capturing facial movement to facial identification, which first needs the face to be recognized with high precision. Face detection is more important today since it is utilized not only on photos, but also in video applications such as real-time surveillance and face identification in movies.

Advances in convolutional networks have made high-precision picture categorization possible. Pixel-level information is sometimes required following face detection, which most face detection algorithms can not offer.

Obtaining pixel-level detail has been a challenging aspect of semantic segmentation. Semantic segmentation is the process of labeling each pixel in a picture.

Face Mask Detection with Machine Learning
Step 1: Extract facial data for training.
Step 2: Train the classifier to recognize faces in masks or labels without masks.
Step 3: Detect faces while testing data with the SSD face detector.
Step 4: Use the learned classifier to classify the identified faces.
In the third phase of the aforesaid method, consider what the SSD face detector is. Well, the SSD is a single-shot multibox detector. This is a technique for detecting objects in photos using a single deep neural network.

It is used to detect things inside a picture. Using a basic VGG-16 architecture, the SSD can outperform other object detectors such as YOLO and Faster R-CNN in terms of speed and accuracy.

Dataset link: https://drive.google.com/drive/folders/1-0woJxllIkk6r73TCEtrZE3aDfSbC_N_?usp=sharing
