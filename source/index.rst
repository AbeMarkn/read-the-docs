.. read-the-docs documentation master file, created by
   sphinx-quickstart on Sun Feb  4 09:14:50 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to read-the-docs's documentation!
=========================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Docker command::

   docker run -it -v $(pwd)/docs sphinxdoc/sphinx sphinx-quickstart
   docker run -v $(pwd):/docs sphinxdoc/sphinx sphinx-build /docs/source /docs/build
