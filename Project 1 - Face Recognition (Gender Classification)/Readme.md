# Face Recognition (Gender Classification)

The aim of this project is to classify gender male or female, based on facial photos that have been provided. <br>
We need to create deep learning model, so the model can predict the photos, whether the photos is male or female. <br>

The origin of the dataset is from this link https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html, but due to the large size, we just use some of it, <br>
and it has been combined in "Images.rar" files , we use around 5000 images that consist of male and female images. <br>

The file "list_attribute.csv" is list of all images from the origin dataset, that consist of some columns, and we only need column 'male'.

* "CNN.ipynb" files is deep learning mode that built from scratch without transfer learning, and the val_acc is around 0.9420 and the training time is ±70 minutes with 30 epochs. Here's the plot :
<img src=pictures/CNN.png width=500>

* "GoogleNet.ipynb" files is deep learning model that built with transfer learning method GoogleNet, and the val_acc is around 0.9610 and the training time is ±5 minutes with 20 epochs. Here's the plot:
<img src=pictures/GoogleNet.png width=500>

* "Resnet50.ipynb" files is deep learning model that built with transfer learning method Resnet50, and the val_acc is around 0.9680 and the training time is ±6 minutes with 20 epochs. Here's the plot:
<img src=pictures/ResNet50.png width=500>

* "VGG19_2x.ipynb" files is deep learning model that built with transfer learning method VGG19, first freeze the base model, and train the model, after unfreeze the base model and train the entire model end-to-end with a low learning rate, and the val_acc is around 0.9425 and the training time is ±67 minutes with total 30 epochs. Here's the plot:
<img src=pictures/VGG19.png width=500>
