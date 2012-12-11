What is this ?
==============

A base buildout for a Plone project

How to deploy it ?
==================
::

    mkdir plonedemo # plonedemo is the name of the buildout folder
    git clone git@github.com:tdesvenain/ecreall.plonebuildout.git
    cd ecreall.plonebuildout
    git archive master | tar -x -C ../plonedemo
    cd ../plonedemo
    python bootstrap.py, etc.
