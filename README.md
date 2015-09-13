Chainer with Neural Networks Language model 
====

<img src="https://connpass-tokyo.s3.amazonaws.com/thumbs/5d/34/5d34d4b6510d664622165a26c37e6e81.png" width="400" height="300" />

This tool is making the Neural Networks Language Model

>[Japanese Reference Pages]http://qiita.com/GushiSnow/private/9ab8761082e29002f735<br>


## Description
This tool is making the Neural Networks Language Model

If you see the detail about it, you see the below<br> 
#
### Install

If you don't install pyenv and virtualenv you have to install bellow
####Prepare Install
linux
```
apt-get install pyenv 
apt-get install virtualenv 
```
Mac
```
brew install pyenv 
brew install virtualenv 
```

####Prepare Inastall2
```
pyenv install 3.4.1
pyenv rehash
pyenv local 3.4.1
virtualenv -p ~/.pyenv/versions/3.4.1/bin/python3.4 my_env
source my_env/bin/activate

```

```
pip install -r requeriment.txt
```
Installing a library bellow
##Requirements

    Python 3.4+
    NumPy
    chainer
    ipython
    notebook
    jinja2
    pyzmq
    tornado

####Confirm library

```
ipython
```

Type command bellow
```
import math
import sys
import time

import numpy as np
import six

import chainer
from chainer import cuda
import chainer.functions as F
from chainer import optimizers
```

#
### Usage 
#
```
*You execute python 
ipython notebook
```
#
### Licence
#
```
The MIT License (MIT)

Copyright (c) 2015 Masaya Ogushi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
#
### Author
#
[SnowMasaya](https://github.com/SnowMasaya)
### References 
#
>[Chainer]http://chainer.org/<br>
>[Chainer RNN]https://github.com/yusuketomoto/chainer-char-rnn<br>

