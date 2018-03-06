This repository contains a script for Travis CI to install python@2 on Yosemite from homebrew, pack a cache, test it, and upload it on Bintray for retrieval in other repositories.

The master branch contains only this README.

The bash* branches are based on a script found on [gateblu-ui-build](https://github.com/octoblu/gateblu-ui-build) (MIT license, Copyright (c) 2014 Octoblu) and manually cache the relevant folders in two .tar.gz archives (one for homebrew, one for python site-packages). 

The code in bashscript branch creates the cache archives and uploads it on Bintray. The code in the bashrestore branch retrieves and install these caches and tests if the python@2 installation works.
