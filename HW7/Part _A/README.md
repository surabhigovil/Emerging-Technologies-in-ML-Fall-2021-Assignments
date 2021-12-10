# Active Learning: 
Uses model prediction to label new set of images. Comma10K dataset has annotated images for self driving cars. 
Predictions from MS COCO pre-trained model using a pre-trained Faster R-CNN with a ResNet-50 backbone serve for the active learning agent to anotate new set of images.

Annotated new set of image from model prediction:
![image](https://user-images.githubusercontent.com/10840984/145646333-1cfef0a2-1708-40de-8628-f43daf5d5381.png)

# Weak Learning:
Snorkel enables developers to define their own labelling function instead of using third party human labelers. This notebook i have shown custom labelling functions using Snorkel to depict Weak Supervison.

![image](https://user-images.githubusercontent.com/10840984/145646591-076f1869-4c0b-4021-accc-a7f4251d58ce.png)

Then a classifier is trained to show predictions on the dataset with custom labels on Spam/Ham dataset.
![image](https://user-images.githubusercontent.com/10840984/145646626-d9c0c034-d11b-4f83-8f96-d495f329d4f1.png)
