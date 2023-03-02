First, use the 'vmd.py', and obtain the decomposed components. (from IMF1 to IMF9)

Then, use the 'IWOA_BiLSTM_Attention.py' to predict each component processed by VMD, and this also can obtain the hyperparameters of the model.
It should be noted that the above operations may be time consuming.
Besides, if you know the hyperparameters required by the model, you don't have to go through the previous step.
Instead, you can use the 'BiLSTM_Attention.py' to predict, and it can complete the prediction task quickly.
If you want to predict the externally-controlled items, you can select the data in the 'IMF with external factors' folder and predict them in turn.

Finally, add the results of the Internally controlled items and the results of the Externally controlled items.