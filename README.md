# Logistic-Regression-Multiclass-
Modelling digit recognizer using Logistic Regression and multiclass classification from scratch

1 Multi-class Classification
 
  For this exercise, you will use logistic regression and neural networks to
  recognize handwritten digits (from 0 to 9). Automated handwritten digit
  recognition is widely used today - from recognizing zip codes (postal codes)
  on mail envelopes to recognizing amounts written on bank checks. This
  exercise will show you how the methods you've learned can be used for this
  classification task.
  In the first part of the exercise, you will extend your previous implemen-
  tion of logistic regression and apply it to one-vs-all classification.
  
1.1 Dataset
  We have a data set in ex3data1.mat that contains 5000 training exam-
  ples of handwritten digits.2 The .mat format means that that the data has
  been saved in a native Octave/MATLAB matrix format, instead of a text
  (ASCII) format like a csv-file. These matrices can be read directly into our
  program by using the load command. After loading, matrices of the correct
  dimensions and values will appear in  program's memory. The matrix
  will already be named, so we do not need to assign names to them.
  
  There are 5000 training examples in ex3data1.mat, where each training
  example is a 20 pixel by 20 pixel grayscale image of the digit. Each pixel is
  represented by a floating point number indicating the grayscale intensity at
  that location. The 20 by 20 grid of pixels is \unrolled" into a 400-dimensional
  vector. Each of these training examples becomes a single row in our data
  matrix X. This gives us a 5000 by 400 matrix X where every row is a training
  example for a handwritten digit image.
  
  The second part of the training set is a 5000-dimensional vector y that
  contains labels for the training set. To make things more compatible with
  Octave/MATLAB indexing, where there is no zero index, we have mapped
  the digit zero to the value ten. Therefore, a "0" digit is labeled as "10", while
  the digits "1" to "9" are labeled as "1" to "9" in their natural order.
  
  1.2 Visualizing the data
  
  1.3 Vectorizing Logistic Regression
  
  1.3.1 Vectorizing the cost function
   
  1.3.2 Vectorizing the gradient
  
  1.3.3 Vectorizing regularized logistic regression
  
  1.4 One-vs-all Classification

  1.4.1 One-vs-all Prediction
