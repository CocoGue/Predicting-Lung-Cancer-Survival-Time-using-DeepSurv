# Predicting-Lung-Cancer-Survival-Time-using-DeepSurv

The method I used doesn't perform very well. We have a C-Index on the public test set at 0.6719. Several possible improvements:
-Fine tuning with bayesian method
-Since we don't have a lot of data, I could have used the whole dataset to train, and test on the public test set (and have the private one for validation)
-Combine features and images would perform better I think (with two networks and combine their outputs for prediction)
-Only used images
-Besides, make data augmentation is really easy with images (rotation, zoom, noise/adversarial attacks to have a more robust network, etc.). Maybe use other medical images 
