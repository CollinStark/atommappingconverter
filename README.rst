========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/atommappingconverter/badge/?style=flat
    :target: https://atommappingconverter.readthedocs.io/
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/CollinStark/atommappingconverter.svg?branch=main
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/CollinStark/atommappingconverter

.. |requires| image:: https://requires.io/github/CollinStark/atommappingconverter/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/CollinStark/atommappingconverter/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/CollinStark/atommappingconverter/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/CollinStark/atommappingconverter

.. |version| image:: https://img.shields.io/pypi/v/atommappingconverter.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/atommappingconverter

.. |wheel| image:: https://img.shields.io/pypi/wheel/atommappingconverter.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/atommappingconverter

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/atommappingconverter.svg
    :alt: Supported versions
    :target: https://pypi.org/project/atommappingconverter

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/atommappingconverter.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/atommappingconverter

.. |commits-since| image:: https://img.shields.io/github/commits-since/CollinStark/atommappingconverter/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/CollinStark/atommappingconverter/compare/v0.0.0...main



.. end-badges

A python converter for Atom Mappings.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install atommappingconverter

You can also install the in-development version with::

    pip install https://github.com/CollinStark/atommappingconverter/archive/main.zip


Documentation
=============


https://atommappingconverter.readthedocs.io/


Development
===========

To run all the tests run::

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
