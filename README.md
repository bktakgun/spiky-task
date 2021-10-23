# spiky-task

## Oversampling Data

The data was unbalanced; to balance out the data, SMOTE function from **imbalanced-learn** module was used.

## Training the Model

    Training with the original data didn't generate good results. 
    ![Model](https://github.com/bktakgun/spiky-task/blob/main/img/init_model.PNG)
    ![Training result](https://github.com/bktakgun/spiky-task/blob/main/img/init_result.PNG)

    For better results data generated from SMOTE function and for optimization **keras-tuner** module was used.
