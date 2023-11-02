TurboRVB website:
--------------------------------------

Source codes of our TurboRVB website. **Please do not include any confidential information because the source files are also public.**

The html (build) files in the master branch are uploaded to the SISSA server (i.e., public).

How to edit the website::

This document is composed by Sphinx, which is a documentation generator. i.e, it takes plain-text source files, and then generates HTML files. You can think of it as a program that takes plain-text files written in the ``reStructuredText`` format and outputs HTML::

    reStructuredText -> via Sphinx -> HTML

Therefore, you should be minimally familiar with ``reStructuredText``.

Sphinx is coded based on python (but you do not need to familiarize yourself with python itself!). So, first you should install the sphinx modules using via pip::

    pip install Sphinx
    pip install sphinx_rtd_theme

The document can be built just by typing::

    make html
    
in the root directory (i.e., TurboRVB_website/). The generated documents are put in::

     html version : root -> build -> html -> index.html, etc...

The source files (i.e., xxx.rst) are:

     rst files: root -> source -> index.rst,   root -> source -> _sources -> ***.rst

Note: The public and development branches are no longer used (will be deleted).

