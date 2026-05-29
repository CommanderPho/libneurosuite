[![Build Status](https://travis-ci.org/neurosuite/libneurosuite.svg?branch=master)](https://travis-ci.org/neurosuite/libneurosuite)
[![Build status](https://ci.appveyor.com/api/projects/status/fggh0drhbaca6k12/branch/master?svg=true)](https://ci.appveyor.com/project/FloFra/libneurosuite/branch/master)

libneurosuite
=============

Library for shared functionality between Klusters, Neuroscope and NDManager.

Developed by Lynn Hazan (main developer), Montel Laurent (qt3 to qt4/5 porting), David Faure (qt3 to qt4/5 porting), Michaël Zugaro (plugins, maintenance) and Florian Franzen (maintenance), distributed under the GNU Public License v2.


## Building:


#### Linux/WSL
```bash
sudo apt install -y build-essential cmake qtbase5-dev libqt5webkit5-dev
cd /mnt/c/Users/pho/repos/NeuroscopeDevEnv/libneurosuite/build
rm -rf *
cmake -D WITH_TEST=ON ..
sudo cmake --build . --target install
```
