.. hoge2 documentation master file, created by
   sphinx-quickstart on Sun Jun 13 04:54:26 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to English documentation!
=================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

.. |hoge| replace:: [すごく長い用語の置き換え]

this is test.

it is |hoge|

.. figure:: ./_static/na2.jpg
   :scale: 40%
   :alt: Alternate Text (not caption)
   
   図1: caption

.. math::

   (a + b)^2 = a^2 + 2ab + b^2

   (a - b)^2 = a^2 - 2ab + b^2

markdownのサンプルは :doc:`sample</doc1>`


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
