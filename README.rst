Obnam in a buildout
===================

This builodut was created in order to make `obnam <http://liw.fi/obnam/>`_
ready for releaes at PyPI.

It uses slightly modified forks of ``obnam`` and ``larch``so far. Modifications
are in packaging only.


Installation
------------

Best used (and tested) with Python 2.7 and virtualenv >=1.9. You'll need also
git and a gcc compiler, moreover the c-extensions are having some dependencies.
(TODO: look them up from debian source packages and document them here).

Follow these steps::

    cd path/to/obnam-buildout
    virtualenv --no-setuptools .
    ./bin/python bootstrap.py
    ./bin/buildout  
    
Usage
-----

obnam is now installed in ``./bin/obname``.

Source Code
===========

**This is only a buildout!** The original obname code and its dependencies are
at `Lars Wirzenius' home page <http://liw.fi>`_ where you can find further
information and guidance.

The sources are in a GIT DVCS with its main branches at
`github <http://github.com/jensens/obname-buildout>`_.

We'd be happy to see many forks and pull-requests to make vdexcsv even better.

Contributors
============

- Jens W. Klein <jens@bluedynamics.com>
