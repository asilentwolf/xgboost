<img src=https://raw.githubusercontent.com/dmlc/dmlc.github.io/master/img/logo-m/xgboost.png width=135/>  eXtreme Gradient Boosting
===========
[![Build Status](https://travis-ci.org/dmlc/xgboost.svg?branch=master)](https://travis-ci.org/dmlc/xgboost)
[![Documentation Status](https://readthedocs.org/projects/xgboost/badge/?version=latest)](https://xgboost.readthedocs.org)
[![GitHub license](http://dmlc.github.io/img/apache2.svg)](./LICENSE)
[![CRAN Status Badge](http://www.r-pkg.org/badges/version/xgboost)](http://cran.r-project.org/web/packages/xgboost)
[![PyPI version](https://badge.fury.io/py/xgboost.svg)](https://pypi.python.org/pypi/xgboost/)
[![Gitter chat for developers at https://gitter.im/dmlc/xgboost](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dmlc/xgboost?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

XGBoost is an optimized distributed gradient boosting library designed to be highly *efficient*, *flexible* and *portable*.
It implements machine learning algorithms under the [Gradient Boosting](https://en.wikipedia.org/wiki/Gradient_boosting) framework.
XGBoost provides a parallel tree boosting(also known as GBDT, GBM) that solve many data science problems in a fast and accurate way.
The same code runs on major distributed environment(Hadoop, SGE, MPI) and can solve problems beyond billions of examples.
XGBoost is part of [DMLC](http://dmlc.github.io/) projects.

Contents
--------
* [Documentation](https://xgboost.readthedocs.org)
* [Usecases](doc/index.md#highlight-links)
* [Code Examples](demo)
* [Build Instruction](doc/build.md)
* [Committers and Contributors](CONTRIBUTORS.md)

What's New
----------
* XGBoost [brick](CHANGES.md)
* XGBoost helps Vlad Mironov, Alexander Guschin to win the [CERN LHCb experiment Flavour of Physics competition](https://www.kaggle.com/c/flavours-of-physics). Check out the [interview from Kaggle](http://blog.kaggle.com/2015/11/30/flavour-of-physics-technical-write-up-1st-place-go-polar-bears/).
* XGBoost helps Mario Filho, Josef Feigl, Lucas, Gilberto to win the [Caterpillar Tube Pricing competition](https://www.kaggle.com/c/caterpillar-tube-pricing). Check out the [interview from Kaggle](http://blog.kaggle.com/2015/09/22/caterpillar-winners-interview-1st-place-gilberto-josef-leustagos-mario/).
* XGBoost helps Halla Yang to win the [Recruit Coupon Purchase Prediction Challenge](https://www.kaggle.com/c/coupon-purchase-prediction). Check out the [interview from Kaggle](http://blog.kaggle.com/2015/10/21/recruit-coupon-purchase-winners-interview-2nd-place-halla-yang/).

Version
-------
* Current version xgboost-0.6 (brick)
  - See [Change log](CHANGES.md) for details

Features
--------
* Easily accessible through CLI, [python](https://github.com/dmlc/xgboost/blob/master/demo/guide-python/basic_walkthrough.py),
  [R](https://github.com/dmlc/xgboost/blob/master/R-package/demo/basic_walkthrough.R),
  [Julia](https://github.com/antinucleon/XGBoost.jl/blob/master/demo/basic_walkthrough.jl)
* Its fast! Benchmark numbers comparing xgboost, H20, Spark, R - [benchm-ml numbers](https://github.com/szilard/benchm-ml)
* Memory efficient - Handles sparse matrices, supports external memory
* Accurate prediction, and used extensively by data scientists and kagglers - [highlight links](https://github.com/dmlc/xgboost/blob/master/doc/README.md#highlight-links)
* Distributed version runs on Hadoop (YARN), MPI, SGE etc., scales to billions of examples.

Bug Reporting
-------------

* For reporting bugs please use the [xgboost/issues](https://github.com/dmlc/xgboost/issues) page.
* For generic questions or to share your experience using xgboost please use the [XGBoost User Group](https://groups.google.com/forum/#!forum/xgboost-user/)


Contributing to XGBoost
-----------------------
XGBoost has been developed and used by a group of active community members. Everyone is more than welcome to contribute. It is a way to make the project better and more accessible to more users.
* Check out [Feature Wish List](https://github.com/dmlc/xgboost/labels/Wish-List) to see what can be improved, or open an issue if you want something.
* Contribute to the [documents and examples](https://github.com/dmlc/xgboost/blob/master/doc/) to share your experience with other users.
* Please add your name to [CONTRIBUTORS.md](CONTRIBUTORS.md) after your patch has been merged.

License
-------
© Contributors, 2015. Licensed under an [Apache-2](https://github.com/dmlc/xgboost/blob/master/LICENSE) license.
