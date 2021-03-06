LightGBM, Light Gradient Boosting Machine
=========================================

[![Join the chat at https://gitter.im/Microsoft/LightGBM](https://badges.gitter.im/Microsoft/LightGBM.svg)](https://gitter.im/Microsoft/LightGBM?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/Microsoft/LightGBM.svg?branch=master)](https://travis-ci.org/Microsoft/LightGBM)
[![GitHub
Issues](https://img.shields.io/github/issues/Microsoft/LightGBM.svg)](https://github.com/Microsoft/LightGBM/issues)
[![Windows Build status](https://ci.appveyor.com/api/projects/status/1ys5ot401m0fep6l/branch/master?svg=true)](https://ci.appveyor.com/project/guolinke/lightgbm/branch/master)
[![Documentation Status](https://readthedocs.org/projects/lightgbm/badge/?version=latest)](https://lightgbm.readthedocs.io/)
[![PyPI version](https://badge.fury.io/py/lightgbm.svg)](https://badge.fury.io/py/lightgbm)

LightGBM is a gradient boosting framework that uses tree based learning algorithms. It is designed to be distributed and efficient with the following advantages:

- Faster training speed and higher efficiency
- Lower memory usage
- Better accuracy
- Parallel and GPU learning supported
- Capable of handling large-scale data

For more details, please refer to [Features](https://github.com/Microsoft/LightGBM/wiki/Features).

[Experiments](https://github.com/Microsoft/LightGBM/wiki/Experiments#comparison-experiment) on public datasets show that LightGBM can outperform existing boosting frameworks on both efficiency and accuracy, with significantly lower memory consumption. What's more, the [experiments](https://github.com/Microsoft/LightGBM/wiki/Experiments#parallel-experiment) show that LightGBM can achieve a linear speed-up by using multiple machines for training in specific settings.

News
----
07/13/2017: [Gitter](https://gitter.im/Microsoft/LightGBM) is avaiable.

06/20/2017: Python-package is on PyPI now.

06/09/2017: [LightGBM Slack team](https://lightgbm.slack.com) is available.

05/03/2017: LightGBM v2 stable release.

04/10/2017 : LightGBM supports GPU-accelerated tree learning now. Please read our [GPU Tutorial](./docs/GPU-Tutorial.md) and [Performance Comparison](./docs/GPU-Performance.md).

02/20/2017 : Update to LightGBM v2.

02/12/2017: LightGBM v1 stable release.

01/08/2017 : Release [**R-package**](https://github.com/Microsoft/LightGBM/tree/master/R-package) beta version, welcome to have a try and provide feedback.

12/05/2016 : **Categorical Features as input directly** (without one-hot coding). Experiment on [Expo data](http://stat-computing.org/dataexpo/2009/) shows about 8x speed-up with same accuracy compared with one-hot coding.

12/02/2016 : Release [**python-package**](https://github.com/Microsoft/LightGBM/tree/master/python-package) beta version, welcome to have a try and provide feedback.


External (unofficial) Repositories
----------------------------------

Julia Package: https://github.com/Allardvm/LightGBM.jl

JPMML: https://github.com/jpmml/jpmml-lightgbm


Get Started And Documentation
-------------------------
Install by following the guide for the [command line program](https://github.com/Microsoft/LightGBM/wiki/Installation-Guide), [Python package](https://github.com/Microsoft/LightGBM/tree/master/python-package) or [R-package](https://github.com/Microsoft/LightGBM/tree/master/R-package). Then please see the [Quick Start](https://github.com/Microsoft/LightGBM/wiki/Quick-Start) guide.

Our primary documentation is at https://lightgbm.readthedocs.io/ and is generated from this repository.

Next you will want to read:

* [**Examples**](https://github.com/Microsoft/LightGBM/tree/master/examples) showing command line usage of common tasks
* [**Features**](https://github.com/Microsoft/LightGBM/wiki/Features) and algorithms supported by LightGBM
* [**Parameters**](https://github.com/Microsoft/LightGBM/blob/master/docs/Parameters.md) is an exhaustive list of customization you can make
* [**Parallel Learning**](https://github.com/Microsoft/LightGBM/wiki/Parallel-Learning-Guide) and [**GPU Learning**](https://github.com/Microsoft/LightGBM/blob/master/docs/GPU-Tutorial.md) can speed up computation
* [**Laurae++ interactive documentation**](https://sites.google.com/view/lauraepp/parameters) is a detailed guide for hyperparameters

Documentation for contributors:

* [**How we Update readthedocs.io**](https://github.com/Microsoft/LightGBM/blob/master/docs/README.md)
* Check out the [Development Guide](https://github.com/Microsoft/LightGBM/blob/master/docs/development.rst).

Support
-------

* Ask a question [on Stack Overflow with the `lightgbm` tag ](https://stackoverflow.com/questions/ask?tags=lightgbm), we monitor this for new questions.
* Discuss on the [LightGBM Gitter](https://gitter.im/Microsoft/LightGBM).
* Open **bug reports** and **feature requests** (not questions) on [Github issues](https://github.com/Microsoft/LightGBM/issues).

How to Contribute
-----------------

LightGBM has been developed and used by many active community members. Your help is very valuable to make it better for everyone.

- Check out [call for contributions](https://github.com/Microsoft/LightGBM/issues?q=is%3Aissue+is%3Aopen+label%3Acall-for-contribution) to see what can be improved, or open an issue if you want something.
- Contribute to the [tests](https://github.com/Microsoft/LightGBM/tree/master/tests) to make it more reliable.
- Contribute to the [documents](https://github.com/Microsoft/LightGBM/tree/master/docs) to make it clearer for everyone.
- Contribute to the [examples](https://github.com/Microsoft/LightGBM/tree/master/examples) to share your experience with other users.
- Open issue if you met problems during development.

Microsoft Open Source Code of Conduct
------------
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
