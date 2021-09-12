# CNN for MNIST Handwritten digits dataset
A basic Convolutional Neural Network for classifying the MNIST handwritten digits. For understanding the code, read the brief documentation in the uploaded Jupyter notebook.

Before running the code, make sure you have the dependencies installed in your environment. The requirements have been mentioned in ```requirements.txt``` file. Use the command **```pip install -r requirements.txt```** for installing all at one go.

## Performance of the model :

**Test evaluation**
```
Test loss :  0.02692016027867794 
Test accuracy :  0.9936000108718872
```

**Correct classifications**
```
Number of correct classifications :  4986 
Number of misclassifications :  14 
Fraction :  0.9972
```

**Classification report**
```
              precision    recall  f1-score   support

     Class 0       1.00      0.99      1.00       520
     Class 1       1.00      0.98      0.99       564
     Class 2       1.00      1.00      1.00       502
     Class 3       1.00      0.99      1.00       510
     Class 4       1.00      0.99      1.00       482
     Class 5       1.00      0.99      0.99       436
     Class 6       0.98      1.00      0.99       496
     Class 7       0.99      0.99      0.99       516
     Class 8       0.99      0.99      0.99       485
     Class 9       1.00      0.99      0.99       489

   micro avg       0.99      0.99      0.99      5000
   macro avg       1.00      0.99      0.99      5000
weighted avg       1.00      0.99      0.99      5000
 samples avg       0.99      0.99      0.99      5000
```
