# ds_bootcamp_project
Tumor recognition project - transfer learning use case.

## Installation

### Conda
```
conda env create -f environment.yml
conda activate ds_bootcamp_project
python -m ipykernel install --user --name=ds_bootcamp_project
jupyter notebook
```

### Pip

```
pip install -r requirements.txt
python -m ipykernel install --user --name=ds_bootcamp_project
jupyter notebook
```


## Training

Data used in the project:
1. [training data](https://s3-us-west-1.amazonaws.com/udacity-dlnfd/datasets/skin-cancer/train.zip) (5.3 GB).
2. [validation data](https://s3-us-west-1.amazonaws.com/udacity-dlnfd/datasets/skin-cancer/valid.zip) (824.5 MB).
3. [test data](https://s3-us-west-1.amazonaws.com/udacity-dlnfd/datasets/skin-cancer/test.zip) (5.1 GB).

[Source](https://github.com/udacity/dermatologist-ai)