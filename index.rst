.. _cellml-annotation-index:

==========================
CellML Annotation Tutorial
==========================

This tutorial aims to provide an introduction to the annotation of CellML models. The initial target is the addition of biological annotations to models from the `repository <https://models.physiomeproject.org/>`_ during the 2014/2015 summer, but the tutorial itself will evolve to cover other types of annotation and best practices.

This tutorial would not be possible without the documentation efforts of the `Auckland Bioengineering Institute <http://www.abi.auckland.ac.nz/>`_ and colleagues. Particularly, we make extensive use of the `ABI Tutorials <https://github.com/ABI-Tutorials/>`_ available on `GitHub.com <https://github.com/>`_. The `source for this tutorial <https://github.com/ABI-Tutorials/cellml-annotation/>`_ is also hosted under that organisation.

.. contents::

Background
==========

A prelimary introduction to CellML can be obtained from the article `An overview of CellML 1.1 <http://sim.sagepub.com/content/79/12/740.short>`_, available in the Zotero database. The modularity and reuse aspects are covered in more detail in `Practical application of CellML 1.1 <http://www.sciencedirect.com/science/article/pii/S0079610708000461>`_, also in the Zotero database.

The main features available in the `Physiome Repository <https://models.physiomeproject.org>`_ (PMR) are described in the :ref:`PMR documentation <abi-pmr2-index>`, included here for convenience. It is worth having a quick read through that documentation to help with an initial understanding of the repository and how it can be used. Similarly, the documentation for :ref:`OpenCOR <OpenCOR-index>` is also available and worth a quick read.

:term:`Mercurial` is the version control system used in the Physiome Repository. When interacting directly with Mercurial, this tutorial demonstrates how to work with the repository using `TortoiseHg <http://tortoisehg.bitbucket.org/>`_, which provides a Windows explorer integrated system for working with Mercurial repositories.

.. note::
   Brief mention of the equivalent command line versions of the TortoiseHg
   actions will also be mentioned, so that these ideas can also be used without
   a graphical client, and on Linux or OS X and similar systems. These will be denoted
   by boxes like this.
   
In addition to the main PMR instance, there is a teaching instance available for *playing* with. It is available at `<http://teaching.physiomeproject.org>`_. Usually user accounts are copied across whenever the teaching instance is re-initialised, but if you have just created a PMR account, you might need to also create yourself an account on the teaching instance. You may also want to simply create yourself extra accounts on the teaching instance to test out various ideas.

.. include:: vph2014/PMR2/teaching-instance-warning.rst
   
Requirements
------------

This tutorial requires you to have:

* A Mercurial client such as `TortoiseHg <http://tortoisehg.bitbucket.org/>`_ or `Mercurial <http://mercurial.selenic.com/>`_ installed;
* The :ref:`OpenCOR <OpenCOR-downloadLinks>` CellML modelling environment; and
* Possibly a text editor such as `Notepad++ <http://notepad-plus-plus.org/>`_ or `gedit <http://projects.gnome.org/gedit/>`_.

.. _introductoryExercises:

Introductory exercises
======================

The following tutorials provide an introduction to some of the features of both OpenCOR and PMR and should be completed to gain some familiarity with these tools.

.. toctree::
   :maxdepth: 1
   :titlesonly:

   vph2014/opencor-tutorials/newWork
   vph2014/opencor-tutorials/annotation
   vph2014/opencor-tutorials/reproduce
   vph2014/opencor-tutorials/extending

Model annotation
================

Now that you have some familiarity with CellML, PMR, and OpenCOR we can dive into some actual model annotation. The previous annotation tutorial pretty much describes the process, but there is some more help available describing the process in :ref:`a bit more detail <annotationTutorialIndex>`.

Indices and tables
==================

* :ref:`genindex`
* :ref:`search`

.. just to remove warnings from all the sub-modules in the VPH tutorial.

.. toctree::
   :hidden:

   annotationTutorial
   vph2014/glossary
   vph2014/todoList
   vph2014/index
   vph2014/MAP/README.rst
   vph2014/MAP/index
   vph2014/tutorialOverview
   vph2014/PMR2/index
   vph2014/OpenCOR/index
