# Layer-wise Analysis Using "SI"

## Seperation Index(SI)

Seperation Index (SI) is a seperating measure in classification problems. It shows that how much input data points seperate the labels from eachother.<br/>
Below is the SI Formula: <br/>
<img/>

## Dataset
We use CIFAR10 for training and inference

## Training

we train the network for 40 epochs and calculate SI for every layer of VGG16.<br/>
Below is the loss and accuracy plots:</br>
Loss plot:<br/>
<img/>
Accuracy plot:<br/>
<img/>


## Resualts:
As can be seen in plot below, the initial layers have less SI, as we get closer to the final layers
SI has increased.
<img/>
