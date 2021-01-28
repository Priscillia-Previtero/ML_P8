# ML_P8
HuBMAP: Hacking the Kidney

This project is linked to the competition "HuBMAP: Hacking the Kidney" whose overview and rule are here : https://www.kaggle.com/c/hubmap-kidney-segmentation

The data are available here : https://www.kaggle.com/c/hubmap-kidney-segmentation/data

My notebooks are intended for Kaggle platform using, datas are then directly included inside.

There are 3 notebooks available : 
- One for the training of the model 'overlap-and-inference'
- The second for the submission of my predicted masks 'submission-predictions'; this one is depending of the first one, indeed the model used for the prediction is the model trained by the notebook 'overlap-and-inference'
- The last for the analysis of the results; it is depending if the second, indeed the results to analyse are results from the notebook 'submission-predictions'

4 branches were used to find my best model : 
- model : gather all my main modifications such as cross validation, learning rate scheduler, ...
- proba_threshold : test only different value of threshold for the binarisation of my predictions
- loss_function : trials about the loss function of my model, particularly trials with different weights of my functions
- architecture_models : trials about different segmentation architecture, different model for the encoder and different weight for pretraining

