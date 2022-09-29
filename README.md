# Detecting Backdoor Attacks via Layer-wise Features Analysis
This repository contains PyTorch implementation of the paper: Detecting Backdoor Attacks via Layer-wise Features Analysis.

## Paper 
[Detecting Backdoor Attacks via Layer-wise Features Analysis]

## Content
The repository contains one jupyter notebook (`Ours_CIFAR10-ResNet18.IPYNB`) that contains code and instructions on how to re-produce the experiments reported in the paper for the benchmark under the Input-aware Dynamic backdoor attack (IAD). 
Also, the checkpoints of the attacked DNNs and their corresponding poisoned datasets are provided into two separate folders: `checkpoints` and `data`.
Models modified to extract intermediate features are available in the folder `my_models`.

**DISCLAIMER:** We used the toolbox ([BackdoorBox] (https://github.com/THUYimingLi/BackdoorBox)) for conducting all backdoor attacks. 

## Data sets
[CIFAR10](https://www.cs.toronto.edu/~kriz/cifar.html) will be automatically downloaded.
However, [GTSRB](https://ieeexplore.ieee.org/document/6033395/) can be manually downloaded using this [link](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/). 
After downloading [GTSRB](https://ieeexplore.ieee.org/document/6033395/), please save in the folder named 'data' with two subfolders each 'train' and 'test.


## Poisoned Datasets and Pretrained Attacked DNNs
Please download poisoned datasets via this link (https://drive.google.com/drive/folders/1sc8StrbYINFP1M7v3DsG44DJ671JbkVm?usp=sharing) and save them in the folder data/poisoned_testsets.
Also, please download pretrained attacked DNNs via this link (https://drive.google.com/drive/folders/1cauZJFm8zBOpWQuf3G--d-10f-87GrHz?usp=sharing) and save them in the folder checkpoints.
## Dependencies

Required packages and libraries are in `requirements.txt`


## Note
We will provide the remaining codes for reproducing our main experiments upon the acceptance of our paper.

