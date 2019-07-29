# Title

	Plugins: using importlib to build self describing apis

# Description

	Api's all have a defined structure, they sometimes almost look like a file tree of actions. Use that similarity + a plugin system to model and organize your api.

# Abstract

    Discuss some the basics of using importlib [5 min]
      being able to point to a file and import it even if it isn't a .py file
      Being able to walk a file directory tree and import files in sys.modules.
    
    Demonstrate how we are using importlib in some new api endpoints at plangrid to abstract and automate some of the more tedious stuff in Flask. [10 min]
      Import modules using importlib and create new classes for each class that's name ends with *Handler, and register them in the flask app.
      Import a whole directory and register all functions that begin with task_* as a celery task for the api to call.
    
    Show a more robust system for building plugins using a hub [10 min]
      demonstrate a way to just load everything in your codebase into one plugin system
      make everything that was loaded available in a singleton that can be passed and used anywhere.

# What attendees will learn

Attendees will learn a 2 different plugin loader methods
A simple 1 that can be used immediately
A more robust method that requires reorganizing more of the base tooling.

And how they can be used in the real world.

# Submitted to

* PyBay 2019 - accepted
