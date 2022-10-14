# Part 1: The building blocks of neural networks

The notebooks of Part 1 accompany the introductory lecture by providing a quick introduction to the building blocks of neural networks and the construction and training of neural networks in PyTorch.

## Structure

```
├── LICENSE
├── README.md               <- The top-level README file
├── data                    <- Data used in the examples
├── nbs                     <- Jupyter notebooks. 
├── environment-gpu.yml     <- The requirements file for reproducing the Python environment, GPU version
└── environment-cpu.yml     <- The requirements file for reproducing the Python environment, CPU version
``` 

## Slides

_TBA_


## Notebooks

| Notebook    |      1-Click Notebook      |
|:----------|------|
|  [1.0-asl-nnets_building_blocks_part1.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/master/Part-1-building_blocks/nbs/1.0-asl-nnets_building_blocks_part1.ipynb)<br>  What is deep learning? How do you do deep learning? | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/master/Part-1-building_blocks/nbs/1.0-asl-nnets_building_blocks_part1.ipynb)
| [2.0-asl-nnets_building_blocks_part2.ipynb](https://nbviewer.org/github/alu042/PCS956-DL-2022/blob/master/Part-1-building_blocks/nbs/2.0-asl-nnets_building_blocks_part2.ipynb) <br> As deep neural networks consist of a set of chained operations on what's called _tensors_, we'll take a closer look at _tensors_ and _tensor operations_.  | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alu042/PCS956-DL-2022/blob/master/Part-1-building_blocks/nbs/2.0-asl-nnets_building_blocks_part2.ipynb)|


## Run locally

Install the necessary libraries:

If you have a PyTorch compatible GPU, then install 

```bash
conda env update -f environment-gpu.yml
```

If you want to use a CPU:

```bash
conda env update -f environment-cpu.yml
```


Install a Jupyter kernel:
```bash
conda activate pytorch
python -m ipykernel install --user --name pcs956-gpu
conda deactivate
``` 

Finally, launch Jupyter Notebook or Jupyter Lab.
