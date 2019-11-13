==================================
Nottingham Hackspace Members Guide
==================================

|docs|

http://guide.nottinghack.org.uk

Contributing
============
The members guide is written using reStructuredText for more info on the syntax please visit http://docutils.sourceforge.net/rst.html

A reStructuredText online editor is here: http://rst.ninjs.org

The docs are built and hosted by Read The Docs http://readthedocs.org

If you wish to improve this guide please either open a `issue <https://github.com/NottingHack/members-guide/issues>`_ or a `pull request <https://github.com/NottingHack/members-guide/pulls>`_

Building Locally
================

You will need pyton and to install the following dependencies

.. code:: bash

    $ pip install sphinx
    $ pip install sphinx_rtd_theme

Then you can build the html version with

.. code:: bash

    $ make html

and open the index page at

.. code::

    _buld/html/index.html

.. |docs| image:: https://readthedocs.org/projects/nottingham-hackspace-members-guide/badge/?version=latest
    :target: https://readthedocs.org/projects/nottingham-hackspace-members-guide/?badge=latest
    :scale: 100%
    :alt: Documentation Status
