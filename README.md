# devcGaboroneDeeplearningmeetup

[audience layout survay](https://www.surveymonkey.com/r/RRSTB89)
## Fundametals
- Input output pipline
    What kind of data show the network expect and the expected output?
    eg 34x34 gray scale images -> class(probability) output
    
- data normalization
- batchnorm 2d, 1d, 3d 

- Types of neural networks
	1. Basic deep neural network
	2. CNN, DCNN 
	   * object classification
	   * object detection
	   
	3. GAN, DCGAN 
	   * Generate Photographs of Human Faces
	   * Photograph Editing
	   * Text-to-Image Translation (text2image)
	   * Image-to-Image Translation
	   
	4. AUTO ENCODERS
	* many more...
	
- Forward and Backward propagation

> How do i know if the model is training (learning something)

### Loss functions

Loss functions are used to determine the error (aka “the loss”) between the output of our algorithms and the given target value.  In layman’s terms, the loss function expresses how far off the mark our computed output is. 

* REGRESSION
  - Mean Square Error
    [MSE](MSE.png)
  - Mean Absolute Error
* Classification
  - Log Loss, Negative Log Likelihood
  - CATEGORICAL CROSS ENTROPHY LOSS

- learning rate

- overfitting vs underfitting

- momentum


### Activation functions [missinglink.ai](https://missinglink.ai/guides/neural-network-concepts/7-types-neural-network-activation-functions-right/)

> Activation functions are mathematical equations that determine the output of a neural network. The function is attached to each neuron in the network, and determines whether it should be activated (“fired”) or not, based on whether each neuron’s input is relevant for the model’s prediction. Activation functions also help normalize the output of each neuron to a range between 1 and 0 or between -1 and 1.

	* RELU
	* TanH
	* Sigmoid
	* Leaky ReLU
	* Softmax


	
## PROJECTS

1. Style transfer
* images and video files
* segway into CNNs

2. Sentiment analysis
* segway into DNN





