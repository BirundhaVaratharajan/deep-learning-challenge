# deep-learning-challenge.

Result
Attempt 1  
APPLICATION_TYPE cutoff = 500
CLASSIFICATION cutoff = 1000
layer1 = 80 : activation function = relu
layer2 = 30 : activation function = relu

Loss: 0.5550801753997803, Accuracy: 0.726064145565033

A loss value of 55 indicates that the model can be further optimized.
The accuracy percent shows that 72% of the model's predicted values align with the true values in the original dataset.




Attempt # 2 
##
Dropped more columns 'EIN' and 'NAME' 'STATUS', 'USE_CASE'.
APPLICATION_TYPE cutoff = 500
CLASSIFICATION cutoff = 1000
layer1 = 80 : activation function = relu
layer2 = 30 : activation function = relu

Loss: 0.5617477893829346, Accuracy: 0.7244315147399902

Accuracy not improved. 


attempt # 3
application_types_to_replace ==1500

Loss: 0.5663759112358093, Accuracy: 0.7208163142204285
Accuracy not improved further slightly gone down. 



attempt #4
added third hidden layer 
APPLICATION_TYPE cutoff = 500
CLASSIFICATION cutoff = 1000
layer1 = 80 : activation function = relu
layer2 = 30 : activation function = relu
layer3 = 30 : activation function = relu

268/268 - 1s - loss: 0.5686 - accuracy: 0.7198 - 514ms/epoch - 2ms/step
Loss: 0.5686007142066956, Accuracy: 0.7197667360305786

Accuracy not improved further slightly gone down more. 
