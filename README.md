Image Classification Cifar10
-------------------------------

The objectif is to train a Deep Neural Network for image classification with 10 different classes.
For more detail about the datasets, please take a look [here](https://www.tensorflow.org/datasets/catalog/cifar10)


Installation 
-------------------------------

* Clone this repo to your computer.
* Make sure you had download `jupyter-notebook` and install the latest version of `keras API`, `Tensorflow framework` and `scikit-learn`.
* Run `jupyter notebook` in the right folder.
* If you do not have `GPU`, its preferable to use [Google colab](https://colab.research.google.com/notebooks) which offers a free access to GPU


File
-------------------------------

* `Cifar10_DL.ipynb` : Jupyter notebook containing the code python used to implement the Neural Network.


Training Neural Network
-------------------------------

* The neural network chosen is `Resnet50` inspired from this [research paper](https://arxiv.org/pdf/1512.03385.pdf)
* I obtained almost `81%` accuracy in the test set.
* I used some regularization methods to reduce `overfitting`
	* `Dropout`
	* `Data augmentation`
	* `EarlyStopping` criteria
* To speed up training, I used : 
	* `Normalization of the input`
	* `BatchNormalization`
	* `Learning rate decay`

Future Work
-------------------------------

* Reducing overfitting :
	* Reducing `Variance`
	* Obtain a `low bias` and `low variance`




