Hello!

**Machine_learning_trial_1:** <br>
This model was created with lots of feature engineering. This was also the first model, so the code is a bit messy.
The best model in this folder is Ridge with R²=0.940.


**Machine_learning_trial_2:** <br>
This model was created with no of feature engineering, just the mean was taken of every feature. The code is a bit cleaner.
The best model in this folder is Ridge with R²=0.9806.
	
**Machine_learning_trial_3:** <br>
This model was created with no real 'feature' engineering (the data was prepared and cleaned). Instead a convolutional neural network was created.
The model in this folder is Ridge with R²=0.9735.
This model can be optimazed more, there was almost zero hyperparameter tuning done. 
But since the epoch progression basically does not show any significant progress after the initial batches, this is probably not fruitfull.

<br>

In general, our thoughts are that the underlying itself is quite linear. It is data from a robot arm following a path created by an algorithm afterall.
So there is enough justification to classify model 2, the simple model as the best model sofar, but we will do some more reasearch. 
