# spiky-task

To retrain the model first run **oversamplingipynb** then **keras-tuner.ipynb**.

## Oversampling Data

The data was unbalanced; to balance out the data, SMOTEN (SMOTE for categorical data) function from **imbalanced-learn** module was used.

## Training the Model

Training with the original data didn't generate good results. 

Model
![Model](https://github.com/bktakgun/spiky-task/blob/main/img/init_model.PNG)

Result
![Training result](https://github.com/bktakgun/spiky-task/blob/main/img/init_result.PNG)

For better results data generated from SMOTEN function and for optimization **keras-tuner** module was used.
