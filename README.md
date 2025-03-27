## Stellar Classification neural network built using Pytorch.

**Summary**

Stellar Classification neural network was built using PyTorch, based on the Stellar Classification Dataset - SDSS17 from Fedesoriano.
The model is able to tell if the observed stellar entries are Galaxies, Stars or Quasars using the 17 feature dataset.

**Tools and Libraries**

 - Wsl
 - Python 3
 - [Jupyter Notebook](https://jupyter.org)
 - [PyTorch](https://www.PyTorch.org)
 - [Pandas](https://pandas.pydata.org/docs/)
 - [NumPy](numpy.org)
 - SDSS17 dataset
 - Matplotlib

**Results**
the dataset was divided in a 4:1 ratio between training and test sets. no validation split was used.

**Results**
The model achieved accuracy of up to 0.96 during testing.

![Model accuracy heatmap](results/results.png?raw=true)
_______

**Limitations**
Due to my limited knowledge in astronomy readings, i wasn't able to fix all abnormalities in the raw data, which resulted in 0.04 inaccuracy in testing and up to 1.4 losses in training.
