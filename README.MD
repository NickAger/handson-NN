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
