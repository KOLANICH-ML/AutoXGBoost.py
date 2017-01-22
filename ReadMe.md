AutoXGBoost.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
===============
~~[![PyPi Status](https://img.shields.io/pypi/v/AutoXGBoost.svg)](https://pypi.python.org/pypi/AutoXGBoost)~~
~~![GitLab Build Status](https://gitlab.com/KOLANICH/AutoXGBoost.py/badges/master/pipeline.svg)~~
~~![GitLab Coverage](https://gitlab.com/KOLANICH/AutoXGBoost.py/badges/master/coverage.svg)~~
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/AutoXGBoost.py.svg)](https://libraries.io/github/KOLANICH/AutoXGBoost.py)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py)

A **VERY** early alpha, don't use. Ore use, but refactor first and send a PR. This is here basically for myself. For now it was designed with imputation in mind, but I'm going to split imputation from it.

Features
========
* heavily automated and easy to use;
* serializes and deserializes XGBoost models;
* fits XGBoost models;
* optimizes hyperparams;
* predicts one column based on other columns.


Requirements
------------
* [`numpy`](https://github.com/numpy/numpy) ![Licence](https://img.shields.io/github/license/numpy/numpy.svg) [![PyPi Status](https://img.shields.io/pypi/v/numpy.svg)](https://pypi.python.org/pypi/numpy) [![Libraries.io Status](https://img.shields.io/librariesio/github/numpy/numpy.svg)](https://libraries.io/github/numpy/numpy)

* [`scipy`](https://github.com/scipy/scipy) ![Licence](https://img.shields.io/github/license/scipy/scipy.svg) [![PyPi Status](https://img.shields.io/pypi/v/scipy.svg)](https://pypi.python.org/pypi/scipy) [![CodeCov Coverage](https://codecov.io/github/scipy/scipy/coverage.svg?branch=master)](https://codecov.io/github/scipy/scipy/) [![Libraries.io Status](https://img.shields.io/librariesio/github/scipy/scipy.svg)](https://libraries.io/github/scipy/scipy)

* [`pandas`](https://github.com/pandas-dev/pandas) ![Licence](https://img.shields.io/github/license/pandas-dev/pandas.svg) [![PyPi Status](https://img.shields.io/pypi/v/pandas.svg)](https://pypi.python.org/pypi/pandas) [![CodeCov Coverage](https://codecov.io/github/pandas-dev/pandas/coverage.svg?branch=master)](https://codecov.io/github/pandas-dev/pandas/) [![Libraries.io Status](https://img.shields.io/librariesio/github/pandas-dev/pandas.svg)](https://libraries.io/github/pandas-dev/pandas)


* [`xgboost`](https://github.com/dmlc/xgboost) ![Licence](https://img.shields.io/github/license/dmlc/xgboost.svg) [![PyPi Status](https://img.shields.io/pypi/v/xgboost.svg)](https://pypi.python.org/pypi/xgboost) [![Libraries.io Status](https://img.shields.io/librariesio/github/dmlc/xgboost.svg)](https://libraries.io/github/dmlc/xgboost)

* [`tqdm`](https://github.com/tqdm/tqdm) ![Licence](https://img.shields.io/github/license/tqdm/tqdm.svg) [![PyPi Status](https://img.shields.io/pypi/v/tqdm.svg)](https://pypi.python.org/pypi/tqdm) [![Coveralls Coverage](https://img.shields.io/coveralls/tqdm/tqdm.svg)](https://coveralls.io/r/tqdm/tqdm) [![CodeCov Coverage](https://codecov.io/github/tqdm/tqdm/coverage.svg?branch=master)](https://codecov.io/github/tqdm/tqdm/) [![Codacy Grade](https://api.codacy.com/project/badge/Grade/3f965571598f44549c7818f29cdcf177)](https://www.codacy.com/app/tqdm/tqdm) [![Libraries.io Status](https://img.shields.io/librariesio/github/tqdm/tqdm.svg)](https://libraries.io/github/tqdm/tqdm)

* [`Chassis.py`](https://codeberg.org/KOLANICH-ML/Chassis.py) ![Licence](https://img.shields.io/github/license/KOLANICH/Chassis.py.svg) [![PyPi Status](https://img.shields.io/pypi/v/Chassis.py.svg)](https://pypi.python.org/pypi/Chassis.py)
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/Chassis.py.svg)](https://libraries.io/github/KOLANICH/Chassis.py)
