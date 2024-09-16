# SF-DA
## Introduction
Our complete code will be released soon. Thank you for your attention. Currently, we provide SF-DA model parameters trained on ACDC and PROMISE12 datasets with different labeling data for testing.
## Requirements
This repository is based on PyTorch 1.9.0 and Python 3.9.0, using a single NVIDIA GeForce RTX 3090 GPU.
##  Datasets
The two datasets can be obtained from [ACDC](https://www.creatis.insa-lyon.fr/Challenge/acdc/databases.html) and [PROMISE12](https://promise12.grand-challenge.org/), the data split list can be obtained from [data_split](https://github.com/ZYS-four/SF-DA/tree/main/data_split), and the model training parameters can be obtained from [models](https://github.com/ZYS-four/SF-DA/tree/main/models).
## Test the model
`python test_ACDC.py/test_PROMISE12.py`
