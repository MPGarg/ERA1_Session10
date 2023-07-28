# Session-10 Assignment

## Problem Statement

![image](https://github.com/MPGarg/ERA1_Session10/assets/120099863/4b3b95cd-02f1-42aa-891f-c60a7564cbcb)
![image](https://github.com/MPGarg/ERA1_Session10/assets/120099863/fd101912-faff-40dc-baac-554e8c6bd12b)

## Code Details

All classes & functions are defined in [link](https://github.com/MPGarg/ERA1_main_repo). 

In notebook ERA1_S10.ipynb [link](ERA1_S10.ipynb) functions from the main repository are called. Model Custom_ResNet is trained for 24 Epochs on CIFAR10 dataset using OneCycle Scheduler with max 96.714% training and 92.65% testing accuracy.

### Training Log

Last Few Epochs:

![image](https://github.com/MPGarg/ERA1_Session10/assets/120099863/1d8273bf-5812-4d69-ab88-96dffee175ed)

### Accuracy & Loss Curve

![image](https://github.com/MPGarg/ERA1_Session10/assets/120099863/8c9e1ec1-0703-4374-9c3a-151c7c060b78)

### Misclassified Images

![image](https://github.com/MPGarg/ERA1_Session10/assets/120099863/9e3aad81-85b3-422e-b4ff-1e749aa8f1f2)

## Conclusion

* One Cycle Policy helps in speeding of learning for the model
* Learning rate (maximum & minimum) can vary as per initialized weights of model and need to be determined for that particular model initialization
* Model is able to run quickly and achieve 92.65% testing accuracy in 24 epoch
* Model is overfitting and regularizations can be used to limit overfitting

