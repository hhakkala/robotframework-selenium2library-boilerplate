Boilerplate for Robot Framework with Selenium 2 library
=======================================================

Introduction
------------

A standalone setup for running [Robot Framework](http://code.google.com/p/robotframework/) tests without having to
manually install any Python libraries.

Running
-------

    $ export PYTHONPATH=$PYTHONPATH:`pwd`/Lib
    $ python Lib/robot/runner.py robot-tests/example.txt