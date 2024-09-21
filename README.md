# Deep-Learning-Challenge
The purpose of the project was to build a model to determine which charities have the best chance to succeed with better than 75% accuracy.
I used a Classification model and tensorflow.
The features are all the columns after dropping "EIN" and "Name."
Attempts:
  First: Used 2 hidden layers with 80 and 30 neurons. The results were 0.6430 accuracy and 0.6224 loss
  Second: Added a 3rd hidden layer with 80, 30 and 10 neurons. The results were 0.6411 accuracy and 0.6220 loss
  Third: Used 3 hidden layers but added neurons on each...100, 50, 25. The results were 0.6433 accuracy and 0.6207 loss
  I ran 100 Epochs on each attempt
Summary:
  I was not able to achieve > 75% accuracy with the 3 attempts. Each attemmpt improved very slightly but not enough to achieve the desired results. 
  Using different models, hidden layers, neurons and epoch variances may achieve the desired results.
