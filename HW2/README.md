This folder contains DeepMind's Perciever and Perciever IO models explored in detail. Perciever model is trained for image classification task. Keras has been used to implement Perciever model.

Perciever Input: Images from Cifar dataset categorized into 10 categories. 

Perciever Output: Classification of image into 1 of the ten labels

Visualizing the loss and accuracy from perciever image classification:

![image](https://user-images.githubusercontent.com/10840984/136708281-40cc0f26-2b15-4247-9568-6121041a6e83.png)


Perceiver IO which is a generalization of Perceiver as in that it can take any arbitrary inputs and produce outputs has been trained for a video flow task. Here trained Perciever IO for creating an optical flow from video.

The code has been adapted from the following refenrces: 
1. https://github.com/deepmind/deepmind-research/tree/master/perceiver
2. https://keras.io/examples/vision/perceiver_image_classification/
3. https://medium.com/analytics-vidhya/perceiver-io-a-general-architecture-for-structured-inputs-outputs-4ad669315e7f
