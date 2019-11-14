.. -*- rst -*-

fuzzdoc
=======

Package Description
-------------------
fuzzdoc is a command line utility for fuzzy search and selection of Python
documentation to view with `pydoc <https://docs.python.org/library/pydoc.html>`_.

.. image:: https://img.shields.io/pypi/v/fuzzdoc.svg
    :target: https://pypi.python.org/pypi/fuzzdoc
    :alt: Latest Version

Installation
------------
First install `fzf <https://github.com/junegunn/fzf>`_. If you 
have `pip <http://www.pip-installer.org/>`_ installed, run::
  
    pip install fuzzdoc

You can also download the source tarball, unpack, and run::

    python setup.py install

Usage
-----
If specified without any arguments, fuzzdoc will list all found Python
modules, keywords, and help topics; the selected topic will be displayed with pydoc.
If a string is specified as an argument, it will be used to filter the list of available topics via substring 
matching.

Author
------
See the included `AUTHORS.rst
<https://github.com/lebedov/fuzzdoc/blob/master/AUTHORS.rst>`_ file for more
information.

License
-------
This software is licensed under the `BSD License
<http://www.opensource.org/licenses/bsd-license>`_.  See the included
`LICENSE.rst <https://github.com/lebedov/fuzzdoc/blob/master/LICENSE.rst>`_ file
for more information.
