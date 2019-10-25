# Question-6-task 2: Validation Model

Introduction:
The trained model is evaluated on test dataset.

Procedure:
This task is done with the following details:
The validation model run on the test dataset every two epochs. The CIFAR 10 test dataset is downloaded.
The validation or the test error of this model is computed in every two epochs.
The minimum test error is determined.
When the test error is minimum, the model is saved and the training epoch that this minimum test error happend is printed.
After two epochs, this procedure is repeated again and the new test error is checked if it is the minimum test error or not. If it is the minimum the above_mentioned steps including: saving model, printing minimum test error, and printing training epoch is done again. But if it is not the minimum error nothing is happend and the model is not saved and the epoch is not printed. 

Result:
The minimum test error is 0.91803.
The corresponding training epoch is 8. 
