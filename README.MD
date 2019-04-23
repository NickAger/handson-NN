# Hands-on Neural Network

A collections of resources to understand Neural Network.

## Getting Started

### Prerequisites

Install conda https://docs.anaconda.com/anaconda/install/ for python 3.7.

Make sure you have added theforge channel:

```
conda config --append channels conda-forge
```

Then in the projec directory run:

```
conda create --name dl_env python=3.7 --file enviroment.yaml
```

This will create our conda enviroment.

If conda does not find all the packages please add :

```
conda config --env --add channels conda-forge
```

### Slides

Slides day 1: https://drive.google.com/drive/folders/1d2KK9VzWeueTnDu3x6mddWFZFF8JQrvG?usp=sharing
Slides day 2: https://drive.google.com/drive/u/1/folders/12WLWF5XDUJok5bvQqAXt2ic5e-0wTe-W

### Run
To activate the enviroment you can run in a shell

```
conda activate dl_env
```

To run tensorboard simply type:

```
tensorboard --logdir logs/1
```

To see if an environment is already running:

```
$ conda info --envs
```
```
# conda environments:
#
base                  *  /Users/nickager/anaconda3
dl_env                   /Users/nickager/anaconda3/envs/dl_env

```

```
$ conda activate dl_env
```

Running Jupyter notebook 

```
(dl_env) $ jupyter notebook 
```
## Contributing

Feel free to contribute with a pull request.

## See also
* [Markov chains](https://news.ycombinator.com/item?id=19633212)
* https://victorzhou.com/blog/intro-to-random-forests/
* https://github.com/ipython-contrib/jupyter_contrib_nbextensions
* https://colab.research.google.com/notebooks/basic_features_overview.ipynb#scrollTo=4hfV37gxpP_c
* https://en.wikipedia.org/wiki/Scale-invariant_feature_transform#Competing_methods
* https://www.meetup.com/London-Reinforcement-Learning/
* https://www.meetup.com/London-Reinforcement-Learning/members/?op=leaders
* https://www.meetup.com/LondonArtificialIntelligence/
* https://towardsdatascience.com/googles-adanet-uses-neural-networks-to-build-better-neural-networks-36c07eefd4d3
* https://realpython.com/python-type-checking/
* https://en.wikipedia.org/wiki/MNIST_database
* https://www.nist.gov/itl/iad/image-group/emnist-dataset
* https://deepmind.com/research/open-source/
* https://github.com/deepmind?page=2
* https://github.com/deepmind/lab
* https://www.openmined.org
* https://github.com/OpenMined/PySyft/tree/master/examples/tutorials
* https://kogence.com/app/
* https://play.battlesnake.io
* https://blog.jle.im/entries/series/+functional-models.html - trainable models with Haskell
* [Awesome Haskell Deep Learning](https://github.com/austinvhuang/awesome-haskell-deep-learning)
* https://mmhaskell.com/haskell-ai
* [Machine Learning: The High-Interest Credit Card of Technical Debt](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43146.pdf)

## datasets
* https://www.datasetlist.com
* https://archive.ics.uci.edu/ml/datasets.html
* https://www.kaggle.com/datasets
