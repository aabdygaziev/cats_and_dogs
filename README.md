# cats_and_dogs
# Cats and Dogs classification

Deep learning for ***cats/dogs*** images classification

Relevant packeges: open-cv2-python, PILLOW, numpy

Data set is from kaggle.com
link: https://www.kaggle.com/chetankv/dogs-cats-images

* simple deep learning algorithm
* gradient descent algorithm
* feature vectorization


* In this repo, I am goint to use different activation functions (sigmoid, ReLU, tanh, Leaky ReLU) and compare their performance.

* sigmoid function - takes values between (0,1); mostly used in output node for binary classification task 
* tanh function - takes values between (-1,1); mostly outperforms sigmoid function.

sigmoid and tanh functions are very sensitive when gradient approaches to the center point (sigmoid 0,5), (tanh at 0).