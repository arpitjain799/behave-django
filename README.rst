behave-django |latest-version|
==============================

|check-status| |test-status| |python-support| |license| |docs-status| |gitter|

Behave BDD integration for Django

.. features-marker

Features
--------

- Web browser automation ready
- Database transactions per scenario
- Use Django's test client
- Use unittest + Django assert library
- Use behave's command line arguments
- Use behave's configuration file
- Fixture loading
- Page objects

.. support-marker

Version Support
---------------

*behave-django* is `tested against`_ the officially supported combinations of
Python and Django (Django 3.2, 4.0 on Python 3.6, 3.7, 3.8, 3.9, 3.10).

The version of `behave`_ is not tied to our integration (read: "independent").
We test against the latest release on PyPI, and run a sample against Behave's
current ``main`` branch.

.. docs-marker

Documentation
-------------

- Documentation is available from `behave-django.readthedocs.io`_
- Read more about *behave* at `behave.readthedocs.io`_

.. contribute-marker

How to Contribute
-----------------

Please, read the `contributing guide`_ in the docs.

.. references-marker


.. _tested against: https://github.com/behave/behave-django/actions/workflows/test.yml
.. _behave: https://pypi.org/project/behave/
.. _behave-django.readthedocs.io: https://behave-django.readthedocs.io/en/latest/
.. _behave.readthedocs.io: https://behave.readthedocs.io/en/latest/usecase_django.html
.. _contributing guide: https://behave-django.readthedocs.io/en/latest/contribute.html
.. |latest-version| image:: https://img.shields.io/pypi/v/behave-django.svg
    :target: https://pypi.org/project/behave-django/
    :alt: Latest version
.. |check-status| image:: https://github.com/behave/behave-django/actions/workflows/check.yml/badge.svg
    :target: https://github.com/behave/behave-django/actions/workflows/check.yml
    :alt: Code checks status
.. |test-status| image:: https://github.com/behave/behave-django/actions/workflows/test.yml/badge.svg
    :target: https://github.com/behave/behave-django/actions/workflows/test.yml
    :alt: Test suite status
.. |python-support| image:: https://img.shields.io/pypi/pyversions/behave-django.svg
    :target: https://pypi.org/project/behave-django/
    :alt: Python versions
.. |license| image:: https://img.shields.io/pypi/l/behave-django.svg
    :target: https://github.com/behave/behave-django/blob/main/LICENSE
    :alt: Software license
.. |docs-status| image:: https://img.shields.io/readthedocs/behave-django/stable.svg
    :target: https://readthedocs.org/projects/behave-django/
    :alt: Documentation Status
.. |gitter| image:: https://img.shields.io/gitter/room/behave/behave-django.svg
    :alt: Gitter chat room
    :target: https://gitter.im/behave/behave-django
