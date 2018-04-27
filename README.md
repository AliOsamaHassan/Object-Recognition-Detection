# Object-Recognition-Detection

- Ali Osama 20140247
- Taha Magdy 20140222
- We have uploaded the code only, without the dataset becuase it is so large to upload.
- Dataset Name: `cifar100`. It is available online.


## Some Details
We have made two models. The first using `coco` dataset (Object detection). But we have found it so big and it need a lot of computation power,
so we have downloaded the trained model, then we added a new feature, which is we take a stream of images from the camera
using `OpenCV` then we fed those images to the model before we display it.

The second project it an images classifer on `cifar100` dataset. We have build the model and traind it.
