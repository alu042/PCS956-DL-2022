# Part 2: A tour of practical deep learning


## Introduction

This part of the module takes you on a guided tour through some of the landscape of practical deep learning. See the accompanying lecture slides for an overview of the content.

We'll meet the idea that non-image data can be turned into images that can be fed to computer vision-based models, use the fact that deep neural networks are representation learners to extract _task-specific representations_ of data, indicate the importance and usefulness of _fusing_ multiple sources of data when constructing predictive models, try out some basic techniques from _explainable AI_, stress the importance of _domain knowledge_ for data augmentation, and more.

<!--1
. Image classification
2. Representing data as images
3. CNNs as feature extractors
4. Time-series, ML, and DL
5. NLP, embeddings, and Transformers
6. DL engineering
-->

## Slides

See Canvas for slides and video recording of lectures.

## Notebooks


| Notebook    |      1-Click Notebook      |
|:----------|------|
|  [2.1.0-asl-Imagenette_image_classification.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.1.0-asl-Imagenette_image_classification.ipynb) <br>Showcases some modern techniques and ideas for image classification | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.1.0-asl-Imagenette_image_classification.ipynb)<br>[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?name=PCS956-DL-2022&url=https://github.com/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.1.0-asl-Imagenette_image_classification.ipynb)
|  [2.2.0-asl-representations-data_as_images-time_series_and_sound_classification.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.2.0-asl-representations-data_as_images-time_series_and_sound_classification.ipynb) <br>Introduces the idea of changing input data representations | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.2.0-asl-representations-data_as_images-time_series_and_sound_classification.ipynb)<br>[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?name=PCS956-DL-2022&url=https://github.com/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.2.0-asl-representations-data_as_images-time_series_and_sound_classification.ipynb)
|  [2.2.1-representations-representing_data_as_images-molecular_activity.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.2.1-representations-representing_data_as_images-molecular_activity.ipynb) <br> Repeats the above story for a very different dataset (molecular activity prediction) | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.2.1-representations-representing_data_as_images-molecular_activity.ipynb)<br>[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?name=PCS956-DL-2022&url=https://github.com/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.2.1-representations-representing_data_as_images-molecular_activity.ipynb)
|  [2.3.0-representations-CNNs-as-feature_extractors-sound_classification.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.3.0-representations-CNNs-as-feature_extractors-sound_classification.ipynb) <br>Explains how the fact that neural networks are _representation learners_ can be exploited to extract task-specific representations of data. | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.3.0-representations-CNNs-as-feature_extractors-sound_classification.ipynb)<br>[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?name=PCS956-DL-2022&url=https://github.com/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.3.0-representations-CNNs-as-feature_extractors-sound_classification.ipynb)
| [2.3.1-representations-CNNs-as-feature_extractors-molecular_activity.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.3.1-representations-CNNs-as-feature_extractors-molecular_activity.ipynb) <br> Extracts features from the image representation of molecules and their activity. Constructs a combined CNN-extracted and otherwise defined representation and use it in predictive models. | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.3.1-representations-CNNs-as-feature_extractors-molecular_activity.ipynb)<br>[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?name=PCS956-DL-2022&url=https://github.com/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.3.1-representations-CNNs-as-feature_extractors-molecular_activity.ipynb)
| [2.4.0-natural_language_processing.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.4.0-natural_language_processing.ipynb) <br>Takes a look at recent developments in _natural language processing_.| [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.4.0-natural_language_processing.ipynb)<br>[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?name=PCS956-DL-2022&url=https://github.com/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/2.4.0-natural_language_processing.ipynb)
|  [dev-0.1.0-representations-get_molecular_fingerprints_and_images.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/dev-0.1.0-representations-get_molecular_fingerprints_and_images.ipynb) <br> Notebook that prepares the molecular data used in `2.2.1` and `2.3.1` |  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/dev-0.1.0-representations-get_molecular_fingerprints_and_images.ipynb)<br>[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?name=PCS956-DL-2022&url=https://github.com/alu042/PCS956-DL-2022/blob/main/Part-2-practical_deep_learning/nbs/dev-0.1.0-representations-get_molecular_fingerprints_and_images.ipynb)

## Install Python environments

### fastai
To run notebooks 2.1.0--2.3.0, install our fastai environment: 

```bash
conda env update -f environment-fastai.yml
conda activate fastai
python -m ipykernel install --user --name fastai --display-name "fastai"
conda deactivate
```

_More TBA_
