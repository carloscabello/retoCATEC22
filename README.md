# retoCATEC22
Solution to the second computer vision [CATEC challenge](https://sites.google.com/view/retopercepcioncatec/inicio) proposed for Jan 2022.

The objective of the challenge is to train a model to be able to detect defects (more precisely: cracks) similar to those in the provided dataset. The dataset is derived from the [Crack Segmentation Dataset (Kaggle)](https://www.kaggle.com/lakshaymiddha/crack-segmentation-dataset) and It was provided by CATEC and uploaded to [Google drive](https://drive.google.com/uc?id=1QaZmWaAlnik7P7V4ju1saVVuEqhHXcr4).

![Crack dataset overview](imgs/crack-dataset-overview.png)

## Installation
Create a virtual environment with Python 3.8.
```shell
python3.8 -m venv env
source env/bin/activate
```
Install the [PyTorch Stable 1.10.1](https://pytorch.org/get-started/locally/) according to your compute platform following the official guide.

```shell
# Installation including CUDA 10.2
pip install install torch torchvision torchaudio
```


