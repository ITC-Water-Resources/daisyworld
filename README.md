# A jupyter notebook to test out the Parabel of Daisyworld
Daisyworld is an hypothetical planet which has only 2 types of organisms. white and black daisies. These daisies differ in that they reflect sunlight in different amounts, and one can guess that white daisies reflect sunlight much better than black daisies. Because of these reflection characteristics (albedo) they can alter the climate of the planet given an amount of incoming solar radiation.

Interestingly, the daisies can reproduce themselves and the rate at which this is happening depends on the local temperature close to the daisies. This creates an interesting non-linear feedback mechanism which is going to be studied in this exercise.

## Getting started
To run the code in [this notebook](DaisyWorld.ipynb) one needs to have a fairly recent python (version >= 3) and [jupyter notebook](https://jupyter.readthedocs.io/en/latest/install.html) installed.  Generally, there are 2 ways to run the jupyter notebook

### Option 1. Install jupyter notebook on your computer and run the notebook locally (recommmended)
This of course takes a bit of time, but you'll be rewarded with a jupyter notebook installation with which you can do other programming exercises as well.

#### Installation notes for Windows
The easiest way to install python with the [jupyter notebook](https://jupyter.org) is probably to install [anaconda for windows](https://www.anaconda.com/download/#windows)
, which comes with jupyter notebook installed by default. Other ways are also possible (e.g. [install the ubuntu shell in windows 10](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/) and subsequently install python and jupyter according to the linux instructions below)


#### Installation notes for linux
execute in a terminal:
```
pip3 install jupyter
```

### Option 2: Run this notebook on [mybinder.org](https://mybinder.org)
A very convenient way to quickly getting started by running the notebook on a remote jupyter notebook instance. 
Just click on this binder link to start a remote jupyter notebook session: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ITC-Water-Resources/daisyworld/HEAD)


