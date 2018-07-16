# Machine learning demonstration notebook

Demonstration of machine learning models trained on the Fashion-MNIST
data set.  The first part of the notebook visualises clusters through
a dimensionality reduction using UMAP. 

## Getting Started

The notebook will run in a Conda environment, as described below.

### Creating the Conda environment

At the terminal prompt, create a new conda environment:

```
conda create -n julita python=3.6 numpy scipy scikit-learn numba jupyter matplotlib seaborn tensorflow
```

Activate that environment:

```
source activate julita
```

### Additional package installs

The following additional packages need installing using pip, after
activating the environment in the previous step:

```
pip install xgboost
pip install umap-learn
```

### Data download 

Running the notebook requires both the Fashion\_MNIST data and the
Fashion\_MNIST demonstration image.

The original Fashion\_MNIST data can be obtained from the following repository: 

```
https://github.com/zalandoresearch/fashion-mnist
```

The Fashion_MNIST data will then be in the subdirectory
```
data/fashion/
```
as four files *.gz, and the demonstration image will be:
```
doc/img/fashion-mnist-sprite.png
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
