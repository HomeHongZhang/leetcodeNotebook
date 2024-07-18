# leetcodeNotebook

The repository contains solutions to various LeetCode problems. Each problem is accompanied by a detailed explanation and solutions in Python, C++, and Rust. The solutions are organized in `src` directory, in which each problem is a seperate jupyter notebook.

The reason to choose jupyter notebook is that it allows for easy documentation and sharing of solutions. It also provides a visual representation of the code and its execution flow, making it easier to understand and debug.

Python is officially supported for the jupyter notebook. While C++ is supported with manually installing [xeus-cling](https://github.com/QuantStack/xeus-cling) kernel. And Rust is also supported with manually installing [Evcxr](https://github.com/evcxr/evcxr) kernel.

## Table of Contents
[TOC]

## Installation

Conda is used to install all the required packages. Please refer to the `environment.yml` file for the exact list of packages.

### Install conda

You can follow the [official instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) to install conda. If you want a fast conda installation, you can use the [Tsinghua mirrors](https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/?C=M&O=D) instead of the official Anaconda repository. Miniconda is recommended because it is much smaller and faster to download.

After you have downloaded the conda installer, run the following command to install conda:

```bash
bash Miniconda3-latest-Linux-x86_64.sh
```

### Install the environment

If you have miniconda installed, you can create a new environment by running:

```bash
conda env create -f environment.yml
conda activate leetcodeNotebook
```

`conda deactivate` is used to deactivate the environment.

## Usage

To run a solution, simply open the corresponding jupyter notebook file in your favorite code editor and execute the cells in order. The output will be displayed below each cell.
