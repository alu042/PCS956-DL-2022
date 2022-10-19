# Part 2: Practical deep learning and deep learning engineering


## Introduction

This part of the module takes you on a guided tour through some of the landscape of practical deep learning. See the accompanying lecture slides for an overview of the content.

We'll meet the idea that non-image data can be turned into images that can be fed to computer vision-based models, use the fact that deep neural networks are representation learners to extract _task-specific representations_ of data, indicate the importance and usefulness of _fusing_ multiple sources of data when constructing predictive models, try out some basic techniques from _explainable AI_, stress the importance of _domain knowledge_ for data augmentation, and more.

_More details TBA_


## Slides

_Slides accompanying Part 2 will be added_

## Notebooks

_Details TBA_

| Notebook    |      1-Click Notebook      |
|:----------|------|
|  [2.1.0-asl-Imagenette_image_classification.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.1.0-asl-Imagenette_image_classification.ipynb) <br>Showcases some modern techniques and ideas for image classification | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.1.0-asl-Imagenette_image_classification.ipynb)<br>[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?name=PCS956-DL-2022&url=https://github.com/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.1.0-asl-Imagenette_image_classification.ipynb)<br>[![kaggle](https://camo.githubusercontent.com/a08ca511178e691ace596a95d334f73cf4ce06e83a5c4a5169b8bb68cac27bef/68747470733a2f2f6b6167676c652e636f6d2f7374617469632f696d616765732f6f70656e2d696e2d6b6167676c652e737667)](https://www.kaggle.com/code/alexanderlundervold/)
|  _TBA_ | _TBA_
|  _TBA_ | _TBA_
|  _TBA_ | _TBA_

## Install Python environments

### fastai
To run notebooks 2.1.0--2.2.0, install our fastai environment: 

```bash
conda env update -f environment-fastai.yml
conda activate fastai
python -m ipykernel install --user --name fastai --display-name "fastai"
conda deactivate
```

_More TBA_
