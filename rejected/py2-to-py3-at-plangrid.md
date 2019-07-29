# Title

Migrating from Py2 -> Py3: The PlanGrid story

# Description

When I joined PlanGrid in the Fall of 2018, basically all work on migrating our monolith to python3 had stalled. With some persistence and buy-in from my manager, and help from qa for testing, we were able to push this over the line. There is not much time left before python2.7 end of lifes, so it is never too early to start your migration.

# Abstract

What I came into when I started at PlanGrid
Monolith in Python2
Using flake8 to do a first pass of py2 -> py3 conversion
absolute imports
print statements -> print functions
dict_{keys,values_items)
generators
Unicode
When does it matter if you have uncode or bytes
How to handle py2 and py3 versions with unicode.
Running the test suite
Use tox to run the full test suite under py2 and py3
The path to deploying
discuss how we deployed py3 to dev and test, and then py2 in production
Discuss the process of switching over.

# What attendees will learn

This talk will discuss some tips and tricks to migrate applications from python2 to python3. Including an explanation on figuring out when and where you need bytes or unicode.

# Submitted to

* PyBay 2019
