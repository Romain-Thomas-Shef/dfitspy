.. _installation:

|JOSS| |Licence|

.. |JOSS| image:: http://joss.theoj.org/papers/10.21105/joss.01249/status.svg
   :target: https://doi.org/10.21105/joss.01249

.. |Licence| image:: https://img.shields.io/badge/License-GPLv3-blue.svg
      :target: http://perso.crans.org/besson/LICENSE.html

Installation
============

dfitspy was developed in python 3.6 and latest release works with 3.12. It needs only the following libraries:

* Numpy v2.2.2 or higher: Numerical python
* astropy v7.0: FITS reader library
* python-magic v0.4.27: file type checker

Other libraries are used, but they are all part of the standard python library. As such no extra installations are needed.

.. warning ::

        for Mac user you might get problem with the libmagic library.
        You might want to install is from brew with ``brew install libmagic``.
        Thanks to A. Mehner for this.

1-from the python repository
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The last dfitspy version is v20.7.1 (1st version of July 2020) and is available in the main pypi repository. To install it::

     pip install dfitspy --user

Using this command will allow you not to have to install any other package. Pip will install what is missing for you.


2-From the github repository
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The installable package can be found in the github directory under the ''dist'' directory. Take the last version and run::

	pip install dfitspy-X.Y.Z.tar.gz --user

This will install dfitspy.

In the version number of dfitspy, X is the year, Y is the month, and Z is the number of revisions in that month. Therefore 20.5.5 means, fifth revision of May 2020.
