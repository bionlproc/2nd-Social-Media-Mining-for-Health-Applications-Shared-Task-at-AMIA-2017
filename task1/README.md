# Task 1 Code Structure

For the first task, the best model is obtained by averaging the prediction probability between the deep model (CNN with Attention) and the linear model (logistic regression).

In the `TML` (traditional machine learning) folder, we include the code for [feature extraction](https://github.com/sifei/2nd-Social-Media-Mining-for-Health-Applications-Shared-Task-at-AMIA-2017/blob/master/task1/Linear_model/build_feature.py) as well as code for model training and prediction at [predict.py](https://github.com/sifei/2nd-Social-Media-Mining-for-Health-Applications-Shared-Task-at-AMIA-2017/blob/master/task1/Linear_model/predict.py)

In the `Deep Model` folder, we provide code for [training](https://github.com/sifei/2nd-Social-Media-Mining-for-Health-Applications-Shared-Task-at-AMIA-2017/blob/master/task1/Deep%20Model/train.py) and [testing](https://github.com/sifei/2nd-Social-Media-Mining-for-Health-Applications-Shared-Task-at-AMIA-2017/blob/master/task1/Deep%20Model/test.py) of the CNN with Attention model.

Further documentation for each model is available in their respective subdirectories.

The code for averaging output probabilities is also included and can be executed with:
```
python average.py
```

The [data_sample](https://github.com/sifei/2nd-Social-Media-Mining-for-Health-Applications-Shared-Task-at-AMIA-2017/tree/master/task1/data_sample) folder contains sample input and output files used in computing prediction results.
