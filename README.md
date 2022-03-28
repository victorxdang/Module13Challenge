# Venture Funding With Deep Learning

This notebook contains a risk analysis of startups that have applied for funding. In order to determine whether or not certain applicants will be successful, a deep learning algorithm involving neural networks is used. The below show the results of various parameters.

<br>

# Parameters Used

The below were the parameters used for the different models.

Model 1:
* Input Features - 116
* Output Layer - 1
* Hidden Layer - 2
* Nodes For Hidden Layer 1 - 58
* Nodes For Hidden Layer 2 - 29

<br>

Model 2:
* Input Features - 116
* Output Layer - 1
* Hidden Layer - 1
* Nodes For Hidden Layer 1 - 78

<br>

Model 3:
* Input Features - 116
* Output Layer - 1
* Hidden Layer - 1
* Nodes For Hidden Layer 1 - 117

<br>

# Results

The results after running each models.

Model 1:
* `268/268 - 0s - loss: 0.5546 - accuracy: 0.7297 - 170ms/epoch - 633us/step`
* `Loss: 0.5546098947525024, Accuracy: 0.72967928647995`

<br>

Model 2:
* `268/268 - 0s - loss: 0.5770 - accuracy: 0.7315 - 247ms/epoch - 920us/step`
* `Loss: 0.5770237445831299, Accuracy: 0.7315452098846436`

<br>

Model 3:
* `268/268 - 0s - loss: 0.6003 - accuracy: 0.7319 - 234ms/epoch - 873us/step`
* `Loss: 0.6003262400627136, Accuracy: 0.7318950295448303`