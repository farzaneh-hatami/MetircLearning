# Layer-wise Analysis Using "SI"

## Seperation Index(SI)

Seperation Index (SI) is a seperating measure in classification problems. It shows that how much input data points seperate the labels from eachother.<br/>
Below is the SI Formula: <br/>
<img src="imgs/SI-formula.png" data-canonical-src="img/SI-formula.png" width="400" />


## Dataset
We use CIFAR10 for training and inference

## Training

we train the network for 40 epochs and calculate SI for every layer of VGG16.<br/>
Below is the loss and accuracy plots:</br>
Loss plot:<br/>
<img src="imgs/loss.png" data-canonical-src="img/loss.png" width="400" /><br/>
Accuracy plot:<br/>
<img src="imgs/acc.png" data-canonical-src="img/acc.png" width="400" />



## Resualts:
As can be seen in plot below, the initial layers have less SI, as we get closer to the final layers
SI has increased.
<img src="imgs/SI-vgg.png" data-canonical-src="img/SI-vgg.png" width="400" />

