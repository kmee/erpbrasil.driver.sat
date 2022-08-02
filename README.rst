========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - | |github-actions| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |github-actions| image:: https://github.com/mileo/erpbrasil.driver.sat/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/mileo/erpbrasil.driver.sat/actions

.. |requires| image:: https://requires.io/github/mileo/erpbrasil.driver.sat/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/mileo/erpbrasil.driver.sat/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/mileo/erpbrasil.driver.sat/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/mileo/erpbrasil.driver.sat

.. |version| image:: https://img.shields.io/pypi/v/erpbrasil.driver.sat.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/erpbrasil.driver.sat

.. |wheel| image:: https://img.shields.io/pypi/wheel/erpbrasil.driver.sat.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/erpbrasil.driver.sat

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/erpbrasil.driver.sat.svg
    :alt: Supported versions
    :target: https://pypi.org/project/erpbrasil.driver.sat

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/erpbrasil.driver.sat.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/erpbrasil.driver.sat

.. |commits-since| image:: https://img.shields.io/github/commits-since/mileo/erpbrasil.driver.sat/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/mileo/erpbrasil.driver.sat/compare/v0.0.0...main



.. end-badges

Web Driver SAT (CF-E)

* Free software: BSD 2-Clause License

Installation
============

::

    pip install erpbrasil.driver.sat

You can also install the in-development version with::

    pip install https://github.com/mileo/erpbrasil.driver.sat/archive/main.zip


Documentation
=============


To use the project:

.. code-block:: python

    import erpbrasil.driver.sat
    erpbrasil.driver.sat.longest()


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
