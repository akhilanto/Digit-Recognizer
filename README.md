Introduction and Objective:
Kaggle Digit Recognizer competition objective is to correctly identify digits from a dataset of tens of thousands of handwritten images.This competition is the perfect to apply techniques like neural networks using a classic dataset including pre-extracted features.Digit Recognizer acts a benchmark to test various classification algorithms.

Dataset Details:
The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples, which is a subset of a larger set available from NIST. Data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine. Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it indicating the lightness or darkness of that pixel. Higher the pixel-value darker the pixel vice versa. Pixel-value is an integer which lies between 0 and 255, inclusive

Summary of the Predictors:
Training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. 
The rest of the columns contain the pixel-values of the associated image. Each pixel column in the training set has a name like Pixelx,
where x is an integer between 0 and 783, inclusive.

Predictive Models:
The 5 models which we are using for this project for the prediction of hand written Digit recognition are  
•	KNN
•	SVM
•	Random Forest
•	Neural Net 
•	Decision tree

Conclusion: 
In Summary, trained and tested non-parametric and parametric methods to model digit classification Kaggle problem. Non-parametric methods are generic, Parametric methods can be tuned based on cost or activation functions. Used KNN, SVM, NN, Decision Tree and Random Forest classification models. As part of pre-processing 512 correlated predictors were dropped using nearZeroVar, cause of this accuracy of the model dropped significantly (approx. by 20%). The reason was data loss; that occurred due to dropping of predictors from testing data set. Models performance is more dependent on internal organization of data and models consume more time to train. Neural Networks performed better with an accuracy of .97 followed by KNN with .96. Digit dataset for SVM , Linear kernel function performs better than Radial kernel function.
