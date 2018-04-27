# Object-Recognition-Detection

- Ali Osama 20140247
- Taha Magdy 20140222
- We have uploaded the code only, without the dataset becuase it is so large to upload.
- Dataset Name: [cifar100](). It is available online.


## Some Details
We have made two models. The first is a pre-trained model (Object detection) using [COCO](http://cocodataset.org/) dataset. Because we have found it so big and it need a lot of computation power, so we have downloaded the pre-trained model, then we added a new feature, which is we take a stream of images from the camera using `OpenCV` then we fed those images to the model before we display it.

The second model is an images classifer on [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. We have build the model and trained it.
