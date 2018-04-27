# Object-Recognition-Detection
- Team Number : 43
- Ali Osama, 20140247
- Taha Magdy, 20140222
- We have uploaded the code only, without the dataset becuase it is so large to upload.
- Datasets used: [COCO](http://cocodataset.org/) & [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html).


## Some Details

We have made two models: 

- The first model is Object detection using [COCO](http://cocodataset.org/) dataset. Because we have found it so big and it needs a lot of computation power, so we have downloaded a pre-trained model, then we added a new feature, which is we take a stream of images from the camera using `OpenCV` then we fed those images to the model before we display it.
To try it : run the jupyter notebook [object_detection_runMe.ipynb](https://github.com/AliOsamaHassan/Object-Recognition-Detection/blob/master/object_detection_runMe.ipynb)

- The second model is for an images classifier using [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. We have built from scratch and traind it.
To try it : run the jupyter notebook [Multi-Class Classification With Keras.ipynb](https://github.com/AliOsamaHassan/Object-Recognition-Detection/blob/master/Multi-Class%20Classification%20With%20Keras.ipynb)


