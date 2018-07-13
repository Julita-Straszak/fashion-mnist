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

Download the image to downloads, it will be accessed through downloads/fashion-mnist-sprite.png.

```
https://raw.githubusercontent.com/zalandoresearch/fashion-mnist/master/doc/img/fashion-mnist-sprite.png
```


## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
