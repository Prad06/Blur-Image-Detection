# Blur Image Detection

Image Quality Detection using OpenCV and ML.

## DataSet

Download the [dataset](http://mklab.iti.gr/files/imageblur/CERTH_ImageBlurDataset.zip), unzip it and save it into your drive or into your local system and use the same directory while running the project files.

## Installation

For this project you don't need to do any setup on your local end, you can use [Google Colab](https://colab.research.google.com/) and it will take care of all the other setups. 

If you want to run the project in your local environment then you hake to install the Python, jupyter notebook and required libraries for the project.

These can be downloaded using the given links 

[Python](https://www.python.org/downloads/)
 
[Jupyter Notebook](https://www.anaconda.com/products/individual)
or you may use any IDE or your choice.

Further to install the libraries,

```python
pip install <Library Name>
```
This command will help you to install all the required libraries, that you don't have in your local setup.
 
## LoadTrain, LoadTest

LoadTrain and LoadTest will load the test and train data and these are the files LoadTrain.ipynb and LoadTest.ipynb. Run these files before Final.ipynb as these will create the required training and testing data which is used to model accuracy prediction. Use your own folder paths.

## Final

The file Final.ipynb is the file that runs the model and gives a accurracy of 68% on training and 80% testing data.
Use your own folder paths.
The file TensorFlow_Final.ipynb is the implementation using Keras. Rest remains the same but the accuracy on train data is 92% and test data is 87%

Pradnyesh Choudhari
