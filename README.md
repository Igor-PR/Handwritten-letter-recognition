# Handwritten-letter-recognition
Using AI models to recognize handwritten letter recognition

## Disclosure

This work is an adaptation from [anujdutt9](https://github.com/anujdutt9/Handwritten-Digit-Recognition-using-Deep-Learning) repository for the EMINST letter dataset

# Requirements

* Python 3.5 +
* Scikit-Learn (latest version)
* Numpy (+ mkl for Windows)
* Matplotlib

# Usage

**1.** Download the four EMNIST dataset files from this link:

```
https://www.nist.gov/itl/iad/image-group/emnist-dataset
```

**2.** Unzip and place the files in the dataset folder inside the EMNIST_Dataset_Loader folder under each ML Algorithm folder i.e :

```
KNN
|_ EMNIST_Dataset_Loader
   |_ dataset
      |_ emnist-letters-train-images-idx3-ubyte
      |_ emnist-letters-train-labels-idx1-ubyte
      |_ emnist-letters-test-images-idx3-ubyte
      |_ emnist-letters-test-labels-idx1-ubyte
```

Do this for SVM and RFC folders and you should be good to go.

**3.** To run the code, navigate to one of the directories for which you want to run the code using command prompt:

```
cd 1. K Nearest Neighbors/
```

and then run the file "knn.py" as follows:

```
python knn.py
```

or 

```
python3 knn.py
```

This will run the code and all the print statements will be logged into the "summary.log" file.

**NOTE: If you want to see the output to print on the Command prompt, just comment out line 16, 17, 18, 106 and 107 and hence you will get all the prints on the screen.**

Alternatively, you can also use PyCharm to run the code and run the ".py" file in there.

Repeat the steps for SVM and RFC code.

**4.** The CNN algorithm still has to be adapted and modified

## Accuracy using Machine Learning Algorithms:

i)	 K Nearest Neighbors: 86.47%

ii)	 SVM:	90.02%

iii) Random Forest Classifier:	88.28%



