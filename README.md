# ML-Andrew-Ng-Python
### This is the ML assignment from Coursera in Python.

![Clusters](https://user-images.githubusercontent.com/66634743/84946155-4b9ac180-b0f9-11ea-8d60-453937061b88.gif)


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
<br />Octave/Matlab: 
    ```matlab
    >> size(theta)
    >> (2, 1)
    ```
    Python:
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
#### [Exercise 5](https://github.com/XXDIL/ML-Andrew-Ng-Python-/tree/master/Exercise5)
* Regularized Linear Regression
* Bias vs. Variance
#### [Exercise 6](https://github.com/XXDIL/ML-Andrew-Ng-Python-/tree/master/Exercise6)
* Support Vector Machine (SVM)
* Spam Classifacation
#### [Exercise 7](https://github.com/XXDIL/ML-Andrew-Ng-Python-/tree/master/Exercise7)
* K-means Clustering
* Principal Component Analysis (PCA)
#### [Exercise 8](https://github.com/XXDIL/ML-Andrew-Ng-Python-/tree/master/Exercise8)
* Anomaly Detection
* Recommender Systems

## Cool Stuff you'll learn as you Proceed into the Topic

#### Exercise 1 : The Result of applying Regression to the Training Set.
  
  ![Ex1](https://user-images.githubusercontent.com/66634743/85844365-abf1c900-b7b3-11ea-8fa5-4ec84c3324a6.png)
  
#### Exercise 2 : These are the figures with different Regularizations
  
  | No Regularization (overfitting) |      Regularization       | Too much Regularization |
  |-------------------------------- | ------------------------	| ----------------------- |
  | <img src="https://user-images.githubusercontent.com/66634743/85844985-9a5cf100-b7b4-11ea-8401-1bd667bc7277.png"> 	| <img src="https://user-images.githubusercontent.com/66634743/85844979-992bc400-b7b4-11ea-985e-de020b824a50.png"> 	| <img src="https://user-images.githubusercontent.com/66634743/85844976-97fa9700-b7b4-11ea-8aab-b1e7a6fe8cad.png">  |
  
#### Exercise 3 : Digit Recognizer using a Neural Network

  | Pridicts 9 |      Pridicts 8       | Pridicts 6 |
  |-------------------------------- | ------------------------	| ----------------------- |
  | <img src="https://user-images.githubusercontent.com/66634743/85846151-78fd0480-b7b6-11ea-8de8-8f486ee51353.png"> | <img src="https://user-images.githubusercontent.com/66634743/85846288-a47fef00-b7b6-11ea-8ca9-f9860b2422ee.png">  | <img src="https://user-images.githubusercontent.com/66634743/85846294-a5b11c00-b7b6-11ea-9e44-7e10ea607112.png">  |
  
#### Exercise 4 : Visualizing the Hidden Layer ( looks weird )

  <img src ="https://user-images.githubusercontent.com/66634743/85847360-49e79280-b7b8-11ea-964c-2b8e1c283b19.png" width="300" height="300">
  
#### Exercise 5 : You need to know the right values of the parameters(lambda, sigma, alpha etc ...)

  ![ex5_2](https://user-images.githubusercontent.com/66634743/85847915-528c9880-b7b9-11ea-94bb-756814ddda92.png)
  
#### Exercise 6 : SVM's are cool ..

  ![Ex6](https://user-images.githubusercontent.com/66634743/85848912-14907400-b7bb-11ea-91a8-a5730aff3473.png)
  
#### Exercise 7 : Image Comppression using PCA

  ![PCA](https://user-images.githubusercontent.com/66634743/85850416-ce88df80-b7bd-11ea-887d-d29b05f771e7.gif)
  
#### Exercise 8 : Anomalous Behaviour of the circled points

  ![Anomaly](https://user-images.githubusercontent.com/66634743/85885473-6fdf5800-b7f5-11ea-97eb-178fd59e061c.png)
  
## Solutions
You can check out my implementation of the assignments [here](https://github.com/XXDIL/ML-Andrew-Ng-Python)
