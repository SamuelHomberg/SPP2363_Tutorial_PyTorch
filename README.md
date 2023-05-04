# SPP2363 Tutorial PyTorch and PyG

### PyTorch
The repository https://github.com/kochgroup/intro_pharma_ai contains different machine learning tutorials for pharmacists/chemists in german and english. The Jupyter notebooks can be run directly in Google Colab.
For this SPP Tutorial, try the [PyTorch Tutorial there](https://github.com/kochgroup/intro_pharma_ai/blob/main/Notebooks_EN/08%20-%20PyTorch.ipynb), it has tasks to train the contents of the lecture, and a final exercise. In the first part, a NN is trained on the MNIST dataset (recognition of handdrawn digits), the final exercise instead uses data of the Tox21 challenge with fingerprints. 

Note: In this notebook, we only use `nn.Sequential`. If you want, try it instead with a `nn.Module` class.

### PyTorch Geometric

The notebook `pytorch_geometric_introduction.ipynb` in the folder with the same name goes through the installation of PyG, the loading of existing datasets, the creation of private datasets and the training of a simple GNN. This notebook does not contain any exercises.