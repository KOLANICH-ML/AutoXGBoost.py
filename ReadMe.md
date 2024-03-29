AutoXGBoost.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
===============
~~[![PyPi Status](https://img.shields.io/pypi/v/AutoXGBoost.svg)](https://pypi.python.org/pypi/AutoXGBoost)~~
~~![GitLab Build Status](https://gitlab.com/KOLANICH/AutoXGBoost.py/badges/master/pipeline.svg)~~
~~![GitLab Coverage](https://gitlab.com/KOLANICH/AutoXGBoost.py/badges/master/coverage.svg)~~
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/AutoXGBoost.py.svg)](https://libraries.io/github/KOLANICH/AutoXGBoost.py)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py)

**We have moved to https://codeberg.org/KOLANICH-ML/AutoXGBoost.py, grab new versions there.**

Under the disguise of "better security" Micro$oft-owned GitHub has [discriminated users of 1FA passwords](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/) while having commercial interest in success and wide adoption of [FIDO 1FA specifications](https://fidoalliance.org/specifications/download/) and [Windows Hello implementation](https://support.microsoft.com/en-us/windows/passkeys-in-windows-301c8944-5ea2-452b-9886-97e4d2ef4422) which [it promotes as a replacement for passwords](https://github.blog/2023-07-12-introducing-passwordless-authentication-on-github-com/). It will result in dire consequencies and is competely inacceptable, [read why](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

If you don't want to participate in harming yourself, it is recommended to follow the lead and migrate somewhere away of GitHub and Micro$oft. Here is [the list of alternatives and rationales to do it](https://github.com/orgs/community/discussions/49869). If they delete the discussion, there are certain well-known places where you can get a copy of it. [Read why you should also leave GitHub](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

---

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
