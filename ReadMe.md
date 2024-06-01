# MUIC: Machine Unlearning for Interferene Cancellation

The project MUIC introduces model cleansing within interference exposed data-driven AI models, as a solution for interference cancellation, offering significant gains in both resource and time efficiency. A corrupted dataset generated
model is cleansed and a cross-validation is performed with the MIA. This source code presentes a quick tutorial on MUIC with a signal-to-noise ratio (SNR) classification task under several interference conditions.

## Prerequisites

The dependencies are specified in the first cell. In Google Colab, no additional setup is required. A ready-to-use dataset will be available soon. For the four different interference conditions, you need to enter the appropriate case parameter. The default is set to "Case-1".
## Overview

The source code comprises three main steps:

1. **Base Model Generation**: 
    - This step involves generating a base model through a training algorithm using the dataset.
    - Alternatively, a pre-trained model can be used to skip this step.

2. **Unlearning Algorithm**:
    - In this step, the unlearning algorithm is applied to the base model.
    - Alternatively, an already unlearned model can be used to skip this step.

3. **MIA Cross-Validation and Evaluation**:
    - This final step implements MIA cross-validation.
    - It evaluates and compares the pre-trained, re-trained, and unlearned models.

For more details, please refer to the [article](https://www.polymtl.ca).

## Authors

* **Eray Guven, Gunes Karabulut Kurt** - (*SoonToBePublished* - [<XXX>](https://www.polymtl.ca)
