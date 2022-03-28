# MNIST-handwritten-digits
The MNIST database of handwritten digits, has a training set of 60,000 examples, and a test set of 10,000 examples. The digits have been size-normalized and centered in a fixed-size image.


A Sequential model with 2 Dense layers, one with 512 neurons and the other with 784 neurons (num_classes)
![image](https://user-images.githubusercontent.com/53575763/160392602-53dda5a5-0968-4fdd-87ab-12a1159508ec.png)


### <font color=darkblue> Experimenting with different optimizers and observe the results </font>

1. Repeat the steps for building, compiling, training and testing the model.
2. Replace the optimizer 'rmsprop' with 'sgd', 'adam', 'adagrad' and note the results.
3. For SGD with momentum, use optimizer=tf.keras.optimizers.SGD(momentum=0.1) 
## Results
![image](https://user-images.githubusercontent.com/53575763/160393575-64fda593-511f-4987-9a77-9dc5929a29c3.png)

### <font color=deeppink> Building the model </font>
Build the CNN model with 3 convolutional layers, 2 max pooling layers and 2 Dense layers
