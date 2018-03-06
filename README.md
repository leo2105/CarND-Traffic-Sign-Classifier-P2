
# **Traffic Sign Recognition** 

## Writeup

---

**Build a Traffic Sign Recognition Project**

The goals / steps of this project are the following:
* Load the data set (see below for links to the project data set)
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results with a written report


[//]: # (Image References)

[image1]: ./datavisualization.png "Visualization"
[image2]: ./graybeforeafter.png "Before Gray, After Gray"
[image3]: ./modifiedLeNet.jpeg "LeNet modified"
[image4]: ./InternetImages/1x.png "ImageInt1"
[image5]: ./InternetImages/2x.png "ImageInt2"
[image6]: ./InternetImages/3x.png "ImageInt3"
[image7]: ./InternetImages/4x.png "ImageInt4"
[image8]: ./InternetImages/5x.png "ImageInt5"
[image9]: ./InternetImages/6x.png "ImageInt6"
[image10]: ./softmaxvisualization.png "Bar Graphics Softmax" 

---

### Data Set Summary & Exploration

I just used an array property, *shape*. And the function *len()*. Later, I use numpy and matplotlib functions for calculating arithmetic operations and make visualizations.

* The size of training set is 34799
* The size of the validation set is 4410
* The size of test set is 12630
* The shape of a traffic sign image is (32, 32, 3)
* The number of unique classes/labels in the data set is 43

#### 2. Include an exploratory visualization of the dataset.

Here is an exploratory visualization of the data set. It is a bar chart showing how the data is distribuited.

We can see that training set, validation set and train set have the same distribution.



![alt text][image1]

### Design and Test a Model Architecture

As a first step, I decided to convert the images to grayscale because of the complexity of the model. We can use a model for RGB images but it would take a lot of time. Another thing, in this dataset we prefer to take in consideration the shape of the sign traffics instead of color.

Here is an example of a traffic sign image before and after grayscaling.

![alt text][image2]

As a last step, I normalized the image data because It helps the convergence of the model. Converge faster.

I did not generate additional data. If I was do, It would help to generalize the model to test in internet images or others images that we have never seen with a lot of noise.

I would used scaling, translation, rotation, adding lighting, gaussian noise, etc for data-augmentation. 


#### 2. Describe what your final model architecture looks like including model type, layers, layer sizes, connectivity, etc.) Consider including a diagram and/or table describing the final model.

My final model consisted of the following layers:

| Layer         		|     Description	        					| 
|:---------------------:|:---------------------------------------------:| 
| Input         		| 32x32x3 RGB image   							| 
| Convolution 5x5     	| 1x1 stride, Valid padding, outputs 28x28x6 	|
| RELU					|												|
| Max pooling 2x2      	| 2x2 stride,  outputs 14x14x6
    |
| Convolution 5x5	    | 1x1 stride, Valid padding, outputs 10x10x16.     |
| RELU					|												|
| Max pooling 2x2      	| 2x2 stride,  outputs 5x5x16
    |
| Convolution 5x5	    | 1x1 stride, Valid padding, outputs 1x1x400.     |
| RELU					|												|
| Fully connected		| input: concatenate("pool2","conv3"), output 800.      	 |
| Dropout               | keep_prob: 0.5
    |
| Fully connected		| output 800.      	 
    |
| Softmax		        |      	 
    |
| Adam optimizer        | lr: 9e-4
    |

## LeNet Model modified for Sign Classification

![alt text][image3]

#### 3. Describe how you trained your model. The discussion can include the type of optimizer, the batch size, number of epochs and any hyperparameters such as learning rate.

To train the model, I used an my CPU and GPU of AWS. I did first iterations on my CPU because I put only 10 iterations. When I thought this model would be great I ran on GPU.

I tried with a batch size equal to 100 and only 60 epochs. It worked well. I had overfitting and underfitting with 256, 512 or 50 of batch size. It took only 60 epochs because, if I use more epochs It gives overfitting.

I use Adam optimizer because It combines Adagrad and SGD method in some way and I do not have to put the *learning decay* like hyperparameter.

I used to use learning rate equal to 1e-3, but accuracy was too low. So, I decided to put 5e-4 or 9e-4 and it worked better.

#### 4. Describe the approach taken for finding a solution and getting the validation set accuracy to be at least 0.93. Include in the discussion the results on the training, validation and test sets and where in the code these were calculated. Your approach may have been an iterative process, in which case, outline the steps you took to get to the final solution and why you chose those steps. Perhaps your solution involved an already well known implementation or architecture. In this case, discuss why you think the architecture is suitable for the current problem.

My final model results were:
* training set accuracy of 100%
* validation set accuracy of 95.7%
* test set accuracy of 94.9%

If an iterative approach was chosen:
* What was the first architecture that was tried and why was it chosen?
    - The first architecture was LeNet just modifying the last layer, 43 classes instead of 10.
    - The model was implemented on the notebook.
* What were some problems with the initial architecture?
    - For digits, LeNet works well, but we need to make an architecture for traffic signs. I just added some neurons and change hyperparameters and I got good results.
* How was the architecture adjusted and why was it adjusted? Typical adjustments could include choosing a different model architecture, adding or taking away layers (pooling, dropout, convolution, etc), using an activation function or changing the activation function. One common justification for adjusting an architecture would be due to overfitting or underfitting. A high accuracy on the training set but low accuracy on the validation set indicates over fitting; a low accuracy on both sets indicates under fitting.

    - I was modifying the model because there was an under fitting. A convolutional layer was placed instead of the first fully-connected layer. 
    - To avoid over-fitting, the dropout regularization method was added between the two fully connected layers. 
    - Thanks to this modification, 94% accuracy was achieved in the validation data.
* Which parameters were tuned? How were they adjusted and why?
    - Kernel size. 5x5 instead of 3x3 in every convolutional layer. To get another image processing or filter for training set images. 
sabemos que filtros mas pequenos nos da detalles mas finos de las imagenes, pero con filtro mas grandes quizas quitamos detalles irrelevantes. 
    - Learning rate equal to 0.0009. I changed because the loss was increasing after some epochs. I decided to reduce learning rate to keep decreasing the loss.
    - Neurons of FC layers was 400-120-84-43. I changed to 800-43. For reducing the complexity of the model and have more neurons where to classify.
    - I have changed batch size to 100. I have tried with 128, 256, 512 , 50. But, 100 give me better results and it is faster than others.
    
* What are some of the important design choices and why were they chosen? For example, why might a convolution layer work well with this problem? How might a dropout layer help with creating a successful model?
    - Dropout layer helped me to avoid over fitting. I use keep_prob equal to 0.5
    - I think the most important thing was changing first FC by Convolutional layer and adding a flattened Pooling layer to first FC.
    
If a well known architecture was chosen:
* What architecture was chosen?
    - Model from Sermanet and LeCun paper (http://yann.lecun.com/exdb/publis/pdf/sermanet-ijcnn-11.pdf).
    
* Why did you believe it would be relevant to the traffic sign application?
    - In the paper of Yann LeCun, they say that their model achieved almost 100% of precision. I think this model is a best way to start better traffic sign classifier.
    
* How does the final model's accuracy on the training, validation and test set provide evidence that the model is working well?
    - Accuracy on the training is 100%, Validation 95.8% and Test 94.9%. These are good results and I proved on 6 Internet Images. 

### Test a Model on New Images

#### 1. Choose five German traffic signs found on the web and provide them in the report. For each image, discuss what quality or qualities might be difficult to classify.

Here are six German traffic signs that I found on the web:

![alt text][image4] ![alt text][image5] ![alt text][image6] 
![alt text][image7] ![alt text][image8] ![alt text][image9]

The fifth image might be difficult to classify because there are many ones very similar from different class. And, this image comes with noise. Other images were easier to classify correctly because each have many aspects that could be easy to distinguish. 

#### 2. Discuss the model's predictions on these new traffic signs and compare the results to predicting on the test set. At a minimum, discuss what the predictions were, the accuracy on these new predictions, and compare the accuracy to the accuracy on the test set (OPTIONAL: Discuss the results in more detail as described in the "Stand Out Suggestions" part of the rubric).

Here are the results of the prediction:

| Image			        |     Prediction	        					| 
|:---------------------:|:---------------------------------------------:| 
| Right-of-way at the next intersection | Right-of-way at the next intersection 									| 
| Speed limit (30km/h)     			| Speed limit (30km/h) 										|
| Keep right     		| Keep right				 				|
| General caution			| General caution    							|
| Road work		| Road work    							|
| Speed limit (60km/h)					| Speed limit (30km/h)											|

The model was able to correctly guess 6 of the 6 traffic signs, which gives an accuracy of 100%. This compares favorably to the accuracy on the test set of 94.9%

#### 3. Describe how certain the model is when predicting on each of the five new images by looking at the softmax probabilities for each prediction. Provide the top 5 softmax probabilities for each image along with the sign type of each probability. (OPTIONAL: as described in the "Stand Out Suggestions" part of the rubric, visualizations can also be provided such as bar charts)

![alt text][image10]

The code for making predictions on my final model is located in the 21st cell of the Jupyter notebook.

For the first image, the model is really sure that this is a Speed limit (30km/h) (probability of 1.0), and the image does contain a stop sign. The top five soft max probabilities were

| Probability         	|     Prediction	        					| 
|:---------------------:|:---------------------------------------------:| 
| 1.00         			| Speed limit (30km/h)   									| 
| .0     				| Speed limit (80km/h)										|
| .0					| Double curve										|
| .0	      			| Roundabout mandatory					 				|
| .0				    | End of speed limit (80km/h)      							|

For the second image, the model is really sure that this is a General caution (probability of 1.0), and the image does contain a General caution sign. The top five soft max probabilities were

| Probability         	|     Prediction	        					| 
|:---------------------:|:---------------------------------------------:| 
| 1.00         			| General caution  									| 
| .0     				| Right-of-way at the next intersection										|
| .0					| Children crossing										|
| .0	      			| Traffic signals					 				|
| .0				    | Speed limit (30km/h)    							|

For the third image, the model is really sure that this is a Right-of-way at the next intersection (probability of 1.0), and the image does contain a Right-of-way at the next intersection sign. The top five soft max probabilities were

| Probability         	|     Prediction	        					| 
|:---------------------:|:---------------------------------------------:| 
| 1.00         			| Right-of-way at the next intersection  									| 
| .0     				| Beware of ice/snow									|
| .0					| General caution										|
| .0	      			| Pedestrians					 				|
| .0				    | Speed limit (80km/h)     							|

For the forth image, the model is really sure that this is a Road work  (probability of 1.0), and the image does contain a Road work sign. The top five soft max probabilities were

| Probability         	|     Prediction	        					| 
|:---------------------:|:---------------------------------------------:| 
| 1.00         			| Road work  									| 
| .0     				| Keep left										|
| .0					| Traffic signals										|
| .0	      			| Bumpy road					 				|
| .0				    | Dangerous curve to the right     							|

For the fifth image, the model is really sure that this is a Speed limit (60km/h) (probability of 1.0), and the image does contain a Speed limit (60km/h) sign. The top five soft max probabilities were

| Probability         	|     Prediction	        					| 
|:---------------------:|:---------------------------------------------:| 
| 1.00         			| Speed limit (60km/h) 									| 
| .0     				| Slippery road										|
| .0					| Children crossing										|
| .0	      			| Beware of ice/snow					 				|
| .0				    | Turn left ahead     							|

For the sixth image, the model is really sure that this is a Keep right (probability of 1.0), and the image does contain a Keep right sign. The top five soft max probabilities were

| Probability         	|     Prediction	        					| 
|:---------------------:|:---------------------------------------------:| 
| 1.00         			| Keep right 									| 
| .0     				| Speed limit (20km/h)										|
| .0					| Speed limit (30km/h)											|
| .0	      			| Speed limit (50km/h)						 				|
| .0				    | Speed limit (60km/h)	      							|




### (Optional) Visualizing the Neural Network (See Step 4 of the Ipython notebook for more details)
#### 1. Discuss the visual output of your trained network's feature maps. What characteristics did the neural network use to make classifications?


