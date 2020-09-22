# Image processing: monitoring construction progress

This repo is the implementation of enhancing indoor construction progress monitoring using image processing techniques by reducing the light effect.

## files description

- process_flow.ipynb

this file contains complete process of this method. Other files are side files for more results and visualization.

## run

You need to install [jupyter](https://jupyter.org/) in order to be able to run the files. Installing using [pip](https://pypi.org/project/pip/):
```sh
pip install jupyterlab
```
and run the following in the repository directory:
```sh
jupyter notebook
```

## light enhancement part (LIME)

Proposed method contains a low light enhancement process called LIME which a third party implementation is used and can be found at:
[Unofficial implementation of the paper LIME: A Method for Low-light IMage Enhancement.](https://github.com/Sy-Zhang/LIME)