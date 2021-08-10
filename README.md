___________________________________________________________________________________________________

# Percolation Threshold Estimator
___________________________________________________________________________________________________  

This tool was developed for as an AI Trained to Predict the Threshold of 2D Ellipse Percolation Systems. A Multi-layer Perceptron Neural Network was used to develop the regression model. A user need only __download the NNModel folder__ and __AIPerc.ipynb file__.
  
___________________________________________________________________________________________________

## Usage
___________________________________________________________________________________________________  

The tool was developed in as a Jupyter notebook using __Python3__, __Tensorflow 2.5.0__ and __Numpy 1.19.5__ and __are required to run this tool__. Make sure you have the required dependencies beforehand. Download the required files and folders to use the tool. Open the AIPerc.ipynb file and run the cells. A prompt will appear and ask for the r1, 2a2, r2 and frac values where they are the following:
* r1:	  the ratio of the axes for ellipse 1. 
  * Its range is 0 to 1000 integers. 
* 2a2:	  the length of axis a for ellipse 2. 
  * Its range is less than or equal to 1.0.
* r2:	  the ratio of the axes for ellipse 2. 
  * Its range is 0 to 1000 integers.
* frac:   the ratio of the number of ellipses present between ellipses of type 1 and 2. 
  * Its range is less than or equal to 1.0
** Note: the length of axis a for ellipse 1 is constant at 0.5. 

Once provided the relevant inputs, the tool will predict the Nc or Critical Number Threshold for the system. The inputs should be given exactly as asked, namely, each one then a space then the next. No commas, brackets or other punctuation should be used. 

