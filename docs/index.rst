======
Bionic
======

.. note::  Bionic is in alpha and under active development.

**Release:** v\ |version| ---
**Quick Links:** `Source <https://github.com/square/bionic>`_ | `Issues <https://github.com/square/bionic/issues>`_ | `Get Started <get-started.html>`_

Bionic is a Python framework for building, running, and sharing data science
workflows.  It's designed for writing *research code*: code where the point is
to learn something from the code's output, and where you'll be rapidly tweaking
and rewriting your code based on what you learn.

Bionic uses `dependency injection`_ to let you specify your workflow with a
minimal amount of code.  You define the entities you care about: dataframes,
parameters, models, plots.  Bionic then handles the tedious glue work of
stitching your components together, adding caching and execution logic, and
wrapping it up in a nice API.  This means you can make progress faster; you can
refactor your code more confidently; and your colleagues can understand and
reuse your work more easily.

.. _dependency injection: https://en.wikipedia.org/wiki/Dependency_injection

Contents
--------

.. toctree::
    :maxdepth: 2

    what
    get-started
    concepts
    warnings
    api/index.rst
    get-help
    contributing
    future
