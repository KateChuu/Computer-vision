# COMP90086 Project - Physical Reasoning Challenge

This folder contains the Python files and test predictions for COMP90086 Final Project.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the necessary packages.

```basha
pip install timm
pip install torch torchvision
pip install torchsummary
```

## Usage

```python
import timm
from torchsummary import summary
import torchvision.transforms as transforms
```

## Run the code
- `main.ipynb`: contains the final model and all pipeline (data pre-processing, training, validatoin, testing and visualising results). Modify the file paths to your paths when executing.

- `Ongoing_Improvements_on_ResNet50_(Multi_Task_Learning).ipynb`: includes code ofthe multi-tasking model for future improvement (**NOT** the final model). Modify the file paths to your paths when executing.

- `test-predictions.csv`: contains the id of each image (`id`) and the corresponding predictions (`stable_height`) for Kaggle submission. 

## References
Model source: 
Wightman, R. (2019). PyTorch image models (GitHub repository). GitHub. https://github.com/huggingface/pytorch-image-models https://doi.org/10.5281/zenodo.4414861