# Title

Enforcing Types: Using type hints for schema validation

# Description

This talk will talk about using type hints and schema validators to enforce the argument types that can be sent to functions.

Allowing to build more flexible api endpoints and tests.

# Detailed Abstract

    Brief overview of type hints. [5 min]
      How to use type hints
      Where the type hints are stored on the function references
    Using Schemas for apis [10min]
      Covering why schemas are useful
      Show a basic implementation using Marshmallow to type check api inputs.
    Combine it all together [10 min]
      Show how to combine type annotations into building schemas on the fly
      include specifying defaults and required arguments to the api
      Demo `hintforcer` a library I am working on to enforce type schemas on regular python functions, and work with several different Schema validators.

# What attendees will learn

Attendees will learn about type hints, and using type hints to declare schemas for validating api endpoints, instead of building the schema as a class before hand (specifically for apis that use celery for worker tasks).

This talk will also cover using `inspect` and attributes on the class to specify the types, and also defaults and if attributes are required to be passed by the schema.

# Submitted to

* PyBay 2019
