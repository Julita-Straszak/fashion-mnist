# Machine learning demonstration notebook

Demonstration of machine learning models trained on fashion_MNIST data set. First part of the notebook visuallises clusters through a dimention reduction - UMAP. 

## Getting Started

The notebook will run in conda environment through jupyter notebook.

### Creating an environement

This a command line you need to run to deploy the notebook: 

```
conda create -n julita python=3.6 numpy scipy scikit-learn numba jupyter matplotlib seaborn tensorflow
```

And after that:

```
source activate julita
```

### Installing

The following packages need installing through pip:

```
pip install xgboost
pip install umap-learn
```

### Data download 

Fashion_MNIST data must be downloaded before running the notebook along with a fashion_MNIST demonstration image.

Download the following repository from orginal Zalando Fashion_MNIST, it will be accessed through GitHub/fashion-mnist/data/fashion.

```
https://github.com/zalandoresearch/fashion-mnist
```

Image will be accessed through doc/img/fashion-mnist-sprite.png from the cloned repository. 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

