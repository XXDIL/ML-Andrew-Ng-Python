# ML-Andrew-Ng-Python
### This is the ML assignment from Coursera in Python.



## About
This is a work in progress as of now, but if you are finished with the Octave/MATLAB implementation of the programming assignments then this is a must do (IMO). The goal of this Repository is to make it easy to implement the programming Assignments in Python using Pandas and NumPy. In this Repo I have implemented A fully vectorised approach to the problems.
You can even check if your codes are running the way you want it to by simply plotting the appropriate graphs.

**Note:** To even simplify it furthur I have uploaded the Jupyter notebook to the excersises.
If you dont want to use the Jupyter Notebook you can even run without it (Just Copy-Paste the code section ). 

## How to start
### Dependencies
This project was coded in Python 3.8.2 (but anyhting above 3.4 will do)
* numpy
* matplotlib
* scipy

### Installation
The easiest way to install all these dependencies at once is to use [Anaconda](https://www.continuum.io/downloads).<br />
<br />To Install Jupyter notebook/Lab : 
```console
foo@bar:~$ pip install jupyterlab
```
Then clone my Repo where ever you want to clone it, <directory> is the destination.
  
```console
foo@bar:~$ git clone https://github.com/XXDIL/ML-Andrew-Ng-Python- <directory>
```

To run the Notebook fire the following command, this will open up the browser with your your local files

```console
foo@bar:~$ jupyter notebook
```
Navigate to my Repo and open the .ipynb fileas shown below:

<kbd>![Location](https://user-images.githubusercontent.com/66634743/84252124-4056fd00-ab1f-11ea-8bcf-465bce1b4552.png)</kbd>

## Important Note
There are a few differences between the Octave Arrays and the ones in NumPy Python
* Mainly the indexing (0 indexed in Python and 1 indexed in Octave).
* Column vectors from octave/matlab are now converted into a simple 1-dimensional ndarray.
Octave/Matlab:  
    ```matlab
    >> size(theta)
    >> (2, 1)
    ```
Python
    ```python
    >>> theta.shape
    >>> (2, )
    ```
## Contents
#### [Exercise 1](https://github.com/XXDIL/ML-Andrew-Ng-Python-/tree/master/Exercise1)
* Linear Regression
* Linear Regression with multiple variables
#### [Exercise 2](https://github.com/XXDIL/ML-Andrew-Ng-Python-/tree/master/Exercise2)
* Logistic Regression
* Logistic Regression with Regularization
#### [Exercise 3](https://github.com/XXDIL/ML-Andrew-Ng-Python-/tree/master/Exercise3)
* Multiclass Classification
* Neural Networks Prediction fuction
#### [Exercise 4](https://github.com/XXDIL/ML-Andrew-Ng-Python-/tree/master/Exercise4)
* Neural Networks Learning

## Solutions
You can check out my implementation of the assignments [here](https://github.com/XXDIL/ML-Andrew-Ng-Python-)
