## This fork is made to work with the python 3.10.x

This is a fork of [unexploredtest](https://github.com/unexploredtest/neural-networks-and-deep-learning)'s fork of [Michael Nielsen](https://github.com/mnielsen/neural-networks-and-deep-learning) repository. It uses poetry to manage dependencies and updates to use more recent versions of python and various libraries. Most things have been updated and currently work. Any help is appreciated and if you spotted any problems, please open an issue and/or a PR.

# Code samples for "Neural Networks and Deep Learning"

This repository contains code samples for Michael Nielsen's book on ["Neural Networks
and Deep Learning"](http://neuralnetworksanddeeplearning.com).

The code was originally written for Python 2.6 or 2.7. Michal Daniel Dobrzanski
has a repository for Python 3
[here](https://github.com/MichalDanielDobrzanski/DeepLearningPython35).

The program `src/network3.py` uses version 0.6 or 0.7 of the Theano
library.  It needs modification for compatibility with later versions
of the library.  I will not be making such modifications.

As the code is written to accompany the book, I don't intend to add
new features. However, bug reports are welcome, and you should feel
free to fork and modify the code.

# Installation
```
git clone https://github.com/spukhafte-sys/neural-networks-and-deep-learning.git
cd neural-networks-and-deep-learning
poetry env use 3.10
poetry install
cd src
poetry run python example_0.py
```

## License

MIT License

Copyright (c) 2012-2018 Michael Nielsen

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
