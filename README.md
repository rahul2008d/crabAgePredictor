Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Crab Age Prediction dataset. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

Note: You can use this notebook to generate additional synthetic data for this competition if you would like.

Files
train.csv - the training dataset; Age is the target
test.csv - the test dataset; your objective is to predict the probability of Age (the ground truth is int but you can predict int or float)
sample_submission.csv - a sample submission file in the correct format


Evaluation
Submissions will be evaluated using Mean Absolute Error (MAE),

MAE
![image](https://github.com/rahul2008d/crabAgePredictor/assets/61235079/527e3931-f609-4386-93af-931b1c7874b8)

where each x_i represents the predicted target, y_i represents the ground truth, and n is the number of rows in the test set.

Submission File
For each id in the test set, you must predict the target Age. The file should contain a header and have the following format:

id,yield
74051,10.2
74051,3.6
74051,11.9
etc.
