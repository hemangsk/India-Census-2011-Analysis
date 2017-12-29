### Basemap Installation

From https://stackoverflow.com/a/43641254/5056792

```
brew install matplotlib
brew install numpy
brew install geos
brew install proj

Downloaded Basemap 1.0.7 source tar file (https://sourceforge.net/projects/matplotlib/files/matplotlib-toolkits/), untarred it.

Added export GEOS_DIR=/usr/local/Cellar/geos/3.5.0/ to a new line in my .bash_profile, and then reloaded it via:

source ~/.bash_profile
From within untarred Basemap directory:

python setup.py install
```
