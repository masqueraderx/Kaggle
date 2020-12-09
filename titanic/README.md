# Titanic

## Data preprocessing
I first fill the missing data in 'Age', 'Embarked' and 'Fare'. Besides, I extracted more infomation according to
csv. file.

## Model
I tried SVM, LR, RF, GDBT, KNN and etc. However, the results are not so satisfied.
Then I tried NN networks, it seems to be a little better than before. Maybe the architecture of NN networks can be improved further.
Besides, I also used batches to train NN networks, and do some parameter adjustments, the results are as good as expected. I believe
it may overfitting?

## Visualization
The loss curve shows the trend. There's some problem with visualization (no markers), this is the problem with my PC. You can check it
on my Kaggle Notebook or do it yourself. The accuracy has the same marker problems.
<div align=center><img src =https://github.com/masqueraderx/Kaggle/blob/main/titanic/accuracy.jpg/></div>

## Further to go
**Architecture: **

Maybe the architecture of NN networks is not so good. I only set 3 hidden layers. I think maybe you can update the architecture.
Besides, I think maybe using cross validation to find the appropriate, feasible hyperparameters is another improvement.

**Preprocessing: **

Maybe the data preprocessing is not so good but I tried.

Welcome to come to discuss it!
