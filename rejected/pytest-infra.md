# Title

Pytest: testing stuff besides code

# Description

Pytest is a super powerful tool for writing test suites. But it doesn't have to be only used for testing code.

It can also be used for verifying deployments or testing that your infrastructure is in the correct state.

This talk will cover some less common uses of pytest.

# Abstract

    Introduction to pytest [5 min]
      cover test functions and test discovery
      cover pytest fixtures
    Using pytest to test your infrastructure [10 min]
      Make api calls to test endpoints
      Use testinfra
      login and check if services are running
      check that all packages are installed
    Use pytest to test network infrastructure [5 min]
      Use pytest + napalm to login to test network routes

# What attendees will learn

Attendees will learn about the basic use cases for pytest to test code.

But they will also learn how to use pytest to test their infrastructure is deploying correctly, and starting the correct services, and is able to connect to the correct databases and other external services.

# Submitted to

* PyBay 2019
