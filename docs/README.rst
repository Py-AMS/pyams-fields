====================
PyAMS fields package
====================

.. contents::


What is PyAMS?
==============

PyAMS (Pyramid Application Management Suite) is a small suite of packages written for applications
and content management with the Pyramid framework.

**PyAMS** is actually mainly used to manage web sites through content management applications (CMS,
see PyAMS_content package), but many features are generic and can be used inside any kind of web
application.

All PyAMS documentation is available on `ReadTheDocs <https://pyams.readthedocs.io>`_; source code
is available on `Gitlab <https://gitlab.com/pyams>`_ and pushed to `Github
<https://github.com/py-ams>`_. Doctests are available in the *doctests* source folder.


What is PyAMS fields?
=====================

PyAMS fields is an extension package which can be used to allow application users to define their
own schema fields, and generate add or edit forms automatically.

These schema fields follow *zope.schema* package philosophy, so that all standard schema fields are
available, but the API allows applications developers to add their own fields types.

This package is used by PyAMS_content package internally to allow site managers to create, for example,
their own contact forms.
