# ot-ml-supp
This respository contains code examples, pre-trained networks and an example data
set to acompany the paper [Machine learning enables fast statistically significant
simulations ofoptically trapped microparticles] [LINK COMMING SOON].

For a live demo of the artificial neural network predicting force in a
optical trap, see [Tweezers-ML](https://ilent2.github.io/tweezers-ml/).

## Dependencies
To train the networks we used Tensorflow via Keras.
Examples are provided in Jupyter Notebooks, to run the examples
you can either extract the code from the notebook/PDF (i.e.,
copy-and-paste the code directly into python) or install Jupyter.

* Python
* Keras
* Tensorflow
* Jupyter Notebook (for running examples)
* Matplotlib (for example-3dof-dataset code)

The easiest way to install all the dependencies is to download
[anaconda](https://www.anaconda.com/distribution/) and install the
[Keras package](https://anaconda.org/conda-forge/keras).
For compatability with Matlab, you may need to use an older version of Keras.
We found that Matlab 2018a was incompatible with Keras versions above 2.2.4.

## Usage
The repository is split into 3 parts:
* `example-3dof-dataset/*` contains an example notebook for training a 3-DOF network.
* `networks/*` contains pre-trained networks used in the paper
* `template.ipynb` and `template.pdf` provide example code for training your own network.

## Quick-start guide

TODO

## Citations
If you find this repository useful, please cite the associated
paper:

[DETAILS COMMING SOON].

## Funding
This research was funded by the Australian Government through the Australian 
Research Council’s Discovery Projects funding scheme (project DP180101002). 
I.L. acknowledges support from the Australian Government RTP Scholarship.
