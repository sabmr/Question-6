# Question-6-task 2: Validation Model

## Introduction
Validating model on test dataset using pytorch

## Details
### 1. Dataset
CIFAR 10 test dataset is downloaded to being used as validation set. 
### 2. Running model on Validation dataset (test dataset)
The model is trained on the train dataset. After every two epochs of training, the validation model run on the test dataset, and the validation or the test error of this model is computed every two epochs. In this step, the minimum test error is determined.
### 3. Saving model, printing minimum test error (best validation error), and printing corresponding training epoch
When the test error is minimum, the model is saved and the training epoch that this minimum test error happend is printed.
After two epochs, this procedure is repeated again and the new test error is checked if it is the minimum test error or not. If it is the minimum the above_mentioned steps including: saving model, printing minimum test error, and printing training epoch is done again. But if it is not the minimum error nothing is happend and the model is not saved and the epoch is not printed. 

## Result
The minimum test error is 0.91803.
The corresponding training epoch is 8. 
The model is saved in this epoch and its name is "net".
Also, the results are:

min error: 0.918034057586621
min epoch: 8

This is the whole test error: 
test_error= [0.9634031078372246, 0.9346795160418901, 0.9239033659299215, 0.918034057586621, 0.9181624024342268]

Noteworthy is that because in epoch 10 the test error is not the minimum of the test errors, the model is not saved and the corresponding training epoch is not printed. So, the last saved model is in epoch 8 which the test error is minimum.
