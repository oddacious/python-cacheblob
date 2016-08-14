========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/python-cacheblob/badge/?style=flat
    :target: https://readthedocs.org/projects/python-cacheblob
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/oddacious/python-cacheblob.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/oddacious/python-cacheblob

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/oddacious/python-cacheblob?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/oddacious/python-cacheblob

.. |requires| image:: https://requires.io/github/oddacious/python-cacheblob/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/oddacious/python-cacheblob/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/oddacious/python-cacheblob/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/oddacious/python-cacheblob

.. |version| image:: https://img.shields.io/pypi/v/cacheblob.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/cacheblob

.. |downloads| image:: https://img.shields.io/pypi/dm/cacheblob.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/cacheblob

.. |wheel| image:: https://img.shields.io/pypi/wheel/cacheblob.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/cacheblob

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/cacheblob.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/cacheblob

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/cacheblob.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/cacheblob


.. end-badges

Simple data cache utility

* Free software: BSD license

Installation
============

::

    pip install cacheblob

Documentation
=============

https://python-cacheblob.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
