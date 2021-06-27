> I have completed this assignment in Google Colab, using the Python programming language.
> This code is available in .py format

> The necessary csv datasets were obtained using my own Google Drive directory folder containing the 
datasets for the assignment. To run the same code, only the directory must be changed accordingly.

> The terminal command, as already written in the code is:
from google.colab import drive
drive.mount('/content/gdrive')

> with the directory specified as:
!ls /content/gdrive/My\ Drive/Dora/Bilkent/CS464/HW1 # Use YOUR OWN DIRECTORY!!

> where files can be extracted, using the following, with the "root" variable being required to change
according to the directory:

import os
root = '/content/gdrive/My Drive/Dora/Bilkent/CS464/HW1'
csv_yTrain = os.path.join(root, 'y_train.csv')
csv_xTrain = os.path.join(root, 'x_train.csv')
csv_yTest = os.path.join(root, 'y_test.csv')
csv_xTest = os.path.join(root, 'x_test.csv')
vocab = os.path.join(root, 'vocabulary.txt')


> Running the entire program in the same order it is written is sufficient to get all the outputs along
with the runtimes of the code.
> As specified in the assignment and the code, the vocabulary count variable vocabcount = 44020.
> The spam label and normal mail labels were assigned to be the values 1 and 0 respectively.
> All necessary libraries will be imported when the program is run. pd corresponds to the pandas library.
whereas np corresponds to numpy.
> tic and toc variables are only present to measure the time elapsed in each part of the code.
> Each defined function with the name predictor in it corresponds to a different model used for 
classification, and works for only a single email document with 44020 entries for each word in the
vocabulary.
> The confusion_matrix function calculates all true positive, true negative, false positive
and false negative values along with the accuracy and precision and displays them for outputs found in
the predictor functions that are stored in a matrix for the code. The displayed values are adjusted 
with corresponding strings explaining what the values stand for.
> Running the entire code gives all of the results with their explanation, along with the respective 
time of each part


