# Classification-Part-1

A classifier is a model that predicts a **discrete label** when shown a set of predictors. Classifiers can be defined as partitions of the **predictor space** into decision regions. A decision region is a region within the predictor space such that any sample that lies within it is assigned the same label.

![image](https://user-images.githubusercontent.com/96924468/167103132-df03fe05-5e0a-4ad3-bcd8-9f9c45e16931.png)

![image](https://user-images.githubusercontent.com/96924468/167103182-62826ac3-5fd9-4306-a884-cf736b83e370.png)

![image](https://user-images.githubusercontent.com/96924468/167103250-a95e11f0-7c61-4661-bfea-2d6dab4213d9.png)
 
 # Logistic function: The certainty of a linear classifier
 
Now that we have defined and visualised a linear classifier, we can create the notion of classifier's certainty using the **logistic function** (also known as expit or sigmoid)

![image](https://user-images.githubusercontent.com/96924468/167103569-99b7635b-b63d-4ea8-a73a-503dd459cbfd.png)

Let's see how we can use the logistic function to define the notion of certainty in classifiers. We will first create a new linear classifier defined by new coefficients and show the decision regions that it defines:

![image](https://user-images.githubusercontent.com/96924468/167103817-a4a86cf1-232e-4a36-9004-a8955d1e883b.png)
![image](https://user-images.githubusercontent.com/96924468/167103899-d6ffe852-82f9-428f-823a-5f39a4a5062a.png)

# Comparing Classifiers

previously, we have shown two different datasets to the same classifier. We will now consider a single dataset and different linear classifiers. 

![image](https://user-images.githubusercontent.com/96924468/167104945-3ea8e06b-c739-4233-bb3f-c3217006edc7.png)

![image](https://user-images.githubusercontent.com/96924468/167105001-2a046bab-fa49-4aa7-b20f-9cd1b5eb4dbd.png)
![image](https://user-images.githubusercontent.com/96924468/167106958-28f03d57-2ad6-4d92-8344-bfb0449fb586.png)

![image](https://user-images.githubusercontent.com/96924468/167105085-33265031-f307-4d22-a95d-c1ebfdbd435b.png)
![image](https://user-images.githubusercontent.com/96924468/167106796-c100683f-f2b6-406d-981d-adb0afce710d.png)


Classifier A
* The likelihood is L = 4.0314938136757398e-22
* The negatve log-likelihood is -log(L) = 49.2673506522414
* The accuracy is 0.7920792079207921
* The error rate is 0.20792079207920788

Classifier B
* The likelihood is L = 1.9147232237372455e-29
* The negatve log-likelihood is -log(L) = 66.12539461532579
* The accuracy is 0.5544554455445544
* The error rate is 0.45

![image](https://user-images.githubusercontent.com/96924468/167106078-f07e4a16-fb2a-4d80-9c5c-29d2f66ab60f.png)

# Logistic Regression: Optimisation 

Gradient descent the most popular optimization strategy used in machine learning. In gradient descent we try to minimise some objective function by repeatedly/iteratively tuning our model parameters in the direction of the negative gradient. Parameters refer to coefficients in regression and weights in neural networks.

![image](https://user-images.githubusercontent.com/96924468/167108501-496ccc12-3c73-4072-86f9-bd117f699970.png)

![image](https://user-images.githubusercontent.com/96924468/167108552-d53b3377-89d7-4a2c-9ebd-2678182b1242.png)


