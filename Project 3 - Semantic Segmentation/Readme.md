# Semantic Segmentation

The aim of this project is to create a semantic segmentation model using FCN8s. <br>
This model then, will be used to implement self-driving cars.
The dataset that used in this project is from Cityscapes dataset. <br>
<br>
Here's the example of data sample that have been visualized <br>
<img src=Img/Data%20Sample%20Visualization.png width=850>
<br>
Here's some experiment that we've been done, <br>
Optimizer = Adam , loss = 'categorical_crossentropy', ' metrics=Accuracy
| Epochs |  learning_rate | weight_decay |  val_acc|
| ------ |  ----          |  ---         | ----    |
| 15     | 0.0001         |  0.001       | 0.7236  |
| 15     | 0.0001         |  0.0001      | 0.7145  |
| 15     | 0.0001         |  0.00001     | 0.7067  |
| 15     | 0.0001         |  0.01        | 0.7205  |
<br>
And, here's the some predicted and original images from model with weight_decay = 0.001
<img src=Img/experiment1_1.png width=600>
<img src=Img/experiment1_2.png width=600>
