.. _cellml-annotation-index:

==========================
CellML Annotation Tutorial
==========================

This tutorial aims to provide an introduction to the annotation of CellML models. The initial target is the addition of biological annotations to models from the `repository <https://models.physiomeproject.org/>`_ during the 2014/2015 summer, but the tutorial itself will evolve to cover other types of annotation and best practices.

This tutorial would not be possible without the documentation efforts of the `Auckland Bioengineering Institute <http://www.abi.auckland.ac.nz/>`_ and colleagues. Particularly, we make extensive use of the `ABI Tutorials <https://github.com/ABI-Tutorials/>`_ available on `GitHub.com <https://github.com/>`_. The `source for this tutorial <https://github.com/ABI-Tutorials/cellml-annotation/>`_ is also hosted under that organisation.

.. contents::

.. toctree::
   :maxdepth: 1
   
   vph2014/glossary
   vph2014/todoList
   
Background
==========

The main features available in the `Physiome Repository <https://models.physiomeproject.org>`_ (PMR) are described in the :ref:`PMR documentation <abi-pmr2-index>`, included here for convenience. It is worth having a quick read through that documentation to help with an initial understanding of the repository and how it can be used. Similarly, the documentation for :ref:`OpenCOR <OpenCOR-index>` is also available and worth a quick read.

:term:`Mercurial` is the version control system used in the Physiome Repository. When interacting directly with Mercurial, this tutorial demonstrates how to work with the repository using `TortoiseHg <http://tortoisehg.bitbucket.org/>`_, which provides a Windows explorer integrated system for working with Mercurial repositories.

.. note::
   Brief mention of the equivalent command line versions of the TortoiseHg
   actions will also be mentioned, so that these ideas can also be used without
   a graphical client, and on Linux or OS X and similar systems. These will be denoted
   by boxes like this.
   
Requirements
------------

This tutorial requires you to have:

* A Mercurial client such as `TortoiseHg <http://tortoisehg.bitbucket.org/>`_ or `Mercurial <http://mercurial.selenic.com/>`_ installed;
* The :ref:`OpenCOR <OpenCOR-downloadLinks>` CellML modelling environment; and
* Possibly a text editor such as `Notepad++ <http://notepad-plus-plus.org/>`_ or `gedit <http://projects.gnome.org/gedit/>`_.

Introductory exercises
======================

The following tutorials provide an introduction to some of the features of both OpenCOR and PMR.

.. toctree::
   :maxdepth: 1
   :titlesonly:

   vph2014/opencor-tutorials/newWork
   vph2014/opencor-tutorials/annotation
   vph2014/opencor-tutorials/reproduce
   vph2014/opencor-tutorials/extending

Indices and tables
==================

* :ref:`genindex`
* :ref:`search`

.. just to remove warnings from all the sub-modules in the VPH tutorial.

.. toctree::
   :hidden:

   vph2014/index
   vph2014/MAP/README.rst
   vph2014/MAP/index
   vph2014/tutorialOverview
   vph2014/PMR2/index
   vph2014/OpenCOR/index
