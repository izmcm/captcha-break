# Captcha Break

This project was done as part of a study of Machine Learning, Image Processing and Cybersecurity.

## Getting Started

### Prerequisites

* [Python3](https://www.python.org/)   
* [Jypiter](https://jupyter.org/) to organize my studies
* [OpenCV](https://opencv.org/) to image processing  
* [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/) to machine learning   

Others used libraries can be seen in [captcha-break.ipynb](https://github.com/izmcm/captcha-break/blob/master/captcha-break.ipynb)

## How It Works

### Image Processing
Images dataset can be found in [Medium](http://bit.ly/break-captcha).

1. Original  

![original](/images/01.png)

2. [Image Thresholding](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_imgproc/py_thresholding/py_thresholding.html)

![original](/images/02.png)

3. [Morphological Transformations](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_imgproc/py_morphological_ops/py_morphological_ops.html)

![original](/images/03.png)

4. Finding letters with [Contours](https://docs.opencv.org/3.3.1/d4/d73/tutorial_py_contours_begin.html) in **findLetters** function

![original](/images/04.png)

### Machine Learning
The letters were saved in folders inside **data_letters** with their IDs for train and test convolutional neural network
#### We can see 99,5% of accuracy in tests!

<img src="/images/05.png" width="800">

### Finally, let's test!

<img src="/images/06.png" width="300">

<img src="/images/07.png" width="300">

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [Adam Geitgey in Medium](http://bit.ly/break-captcha)
