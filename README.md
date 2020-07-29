# Gender Classification Using Deep Learning With Keras
The Keras model is created by training SmallerVGGNet from scratch on around 2200 images (~1100 for each class) gathered from Google Images. It achieved ~95% training accuracy and ~85% validation accuracy. (20% of the dataset is used for validation)

## Python Packages
* numpy
* opencv-python
* tensorflow
* keras

Install the required packages by executing the following command:

`$ pip install -r requirements.txt`

**Please Note: The codes of this repository work on Python 3.x or further.** 

## Usage
`$ python classify_gender.py -i <input_image> -m gender_classification.model`

## Sample output
![](Sample Output - 1.jpg)

![](Sample Output - 2.jpg)
