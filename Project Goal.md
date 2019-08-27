# Deep Learning with AWS and CIFAR-10
Exploration of deep learning architectures. Train 5-15 different deep CNN's and diagnose performance. 

# Datasets
- CIFAR-10:
https://www.cs.toronto.edu/~kriz/cifar.html

Includes:
    - 60,000 observations of 10 balanced classes
    - 10,000 test observations
    - Non-overlapping
    - 5 folds x 10,000 balanced validation
    - Time 

# Modeling Strategy

- Try different deep learning tools
    - Deep 
    - Wide
    - Dropout
    - L1/L2
    - Activation functions
    - Batch norm
- Build a multi-class classifier to predict each type of photo

Use warm start training.
Potentially use capsules?

Open question: What can we add beyond keras' standard bag of tricks?
Alternative loss functions? 
Sensitivity to seeds?

# End Goal
Diagnose best classifier of trials and associated hyperparameters.

References:
<br>https://keras.io/examples/cifar10_cnn/
<br>https://github.com/aws-samples/amazon-sagemaker-architecting-for-ml/blob/master/Writeups/Deep%20Learning.md
<br>https://www.quora.com/How-can-l-visualize-cifar-10-data-RGB-using-python-matplotlib
