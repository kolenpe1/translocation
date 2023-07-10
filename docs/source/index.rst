.. traco documentation master file, created by
   sphinx-quickstart on Sat Apr 15 15:53:25 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Documentation of translocation
==============================

.. toctree::
   :maxdepth: 2
   :caption: Contents:
   
   mtz.rst
   xds.rst
   shelx.rst
   sca.rst
   help.rst

Introduction
------------

.. _intro:

TRANSLOCATION is a Python3 module that helps to deal with multi-lattice translocation
defects. If translocation defects are present, they may affect the quality
of electron density dramatically.

TRANSLOCATION works with :ref:`MTZ files <mtz>` with intensities or structure factors,
:ref:`HKL files <HKL>` from XDS, :ref:`hkl files <hkl>` for SHELX, and also
with :ref:`SCA files <sca>`.


Installation
------------

TRANSLOCATION is a module that can be installed using PIP from `https://pypi.org/translocation <https://pypi.org/translocation>`_.

.. code-block:: console

   python3 -m pip install translocation


Dependencies
------------

TRANSLOCATION has no dependencies for text-based data files. For work with MTZ files, TRANSLOCATION depends on `GEMMI <https://gemmi.readthedocs.io>`_.



Example
-------

.. _example:

The very first structure tested with TRANSLOCATION is S1 nuclease in complex with RNA segments (Adámková *et al.*, 2022).


K. Adámková, T. Kovaľ, L.H. Oestergaard, J. Dušková, M. Malý, L. Švecová, T. Skálová, P. Kolenko, J. Dohnálek. (2022). Atomic resolution studies of S1 nuclease complexes reveal details of RNA interaction with the enzyme despite mutiple lattice-translocation defects. //Acta Cryst. D//**78**, 1194-1209.




Help
----

.. code-block:: console

   python3 -m translocation --help

More information on :ref:`Help is here <help>`.

