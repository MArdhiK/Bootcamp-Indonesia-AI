# Person Tracking

The aim of this project is to build a model that can tracking person.
The dataset that we use is from COCO Dataset and only use the class 'person' in image form and its annotation.
± 3000 images as trainset
± 1000 images as validationset
± 500 images as testset
After we build model from the image dataset, we can apply the model into the video test, and see how well our model work.
We made 4 models and compare it to, which one is the best

| Model Name | Epochs |  Time        | mAP50   |
| ---------  | ------ |  ----        |  ---    |
| Yolov5s    |  50    | 0.662 hours  |  0.477  |
| Yolov5x    |  75    | 2.610 hours  |  0.568  |
| Yolov8s    |  75    | 1.772 hours  |  0.632  |
| Yolov8x    |  75    |  hours  |    |

Thats all in defaullt mode, no data augmentation, no change in parameter
