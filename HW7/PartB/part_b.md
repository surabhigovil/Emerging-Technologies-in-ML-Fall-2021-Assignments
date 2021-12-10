```
1. Set up a new TensorFlow 2.6 Enterprise notebook without GPU from Part A for starting model training.

2. Create a managed dataset:
```

![alt_text](images/image1.png "image_tooltip")



![alt_text](images/image2.png "image_tooltip")


```
3. Analyzing dataset gives details about the variables 
```


![alt_text](images/image3.png "image_tooltip")



```
4. Train a new Model: We will use AutoML here for the same. From the above page click Train model. Select the following options and click Continue to model training. 
```

![alt_text](images/image4.png "image_tooltip")



```
For classification modele need to select target column as below:
```


![alt_text](images/image5.png "image_tooltip")



```
As dataset is highly imbalanced from Training options select AUC PRC option which will maximize precision-recall for the less common class:
```

![alt_text](images/image6.png "image_tooltip")



```
Select 1 next for budget and node hours and click start training:
```

![alt_text](images/image7.png "image_tooltip")



```
Model Evaluation:
```

![alt_text](images/image8.png "image_tooltip")


Feature Importance: 


![alt_text](images/image9.png "image_tooltip")


6. Deploying trained model to endpoint

Click Deploy & Test, give a name to the endpoint and click deploy.


![alt_text](images/image10.png "image_tooltip")

```
Scroll down to the page and click Predict to test the deployed endpoint:
```

![alt_text](images/image11.png "image_tooltip")

```
Prediction results can be viewed by scrolling up on the page:
```

![alt_text](images/image12.png "image_tooltip")


7. Deploying the model to a REST API:

```
First get Endpoint ID from here: 
```

![alt_text](images/image13.png "image_tooltip")


8. To test the model deploy endpoint: 


![alt_text](images/image14.png "image_tooltip")

```
Prediction in the notebook can be obtained by: 
```

![alt_text](images/image15.png "image_tooltip")