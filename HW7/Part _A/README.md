# Active Learning: 
Uses model prediction to label new set of images. Comma10K dataset has annotated images for self driving cars. 
Predictions from MS COCO pre-trained model using a pre-trained Faster R-CNN with a ResNet-50 backbone serve for the active learning agent to anotate new set of images.

# Weak Learning:
Snorkel enables developers to define their own labelling function instead of using third party human labelers. This notebook i have shown custom labelling functions using Snorkel to depict Weak Supervison.
Then a classifier is trained to show predictions on the dataset with custom labels on Spam/Ham dataset.