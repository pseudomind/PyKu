PyKu
=====

PyKu is a Python binding for the native Haiku-OS API.

This work aims to pick up where the 2011 GSoC Language bindings by Sean Healy 
left off. This particular codebase will focus only on the python bindings.

To access the original code from this GSoC project, please see the following:

https://github.com/HaikuArchives/HaikuLanguageBindings

Current Status
--------------

At this point, this project is know to not build under a current haiku-gcc4-hybrid
system. It is suspected, that it will not build on the other architectures either.

Eventually the goal will be to produce recipes for building the bindings for the
various architectures which are available. When this point is reached, the state
of this repository with respect to those builds should be listed below.

| Architecture  | Build Status  |
| ------------- | :-----------: |
| x86_gcc2      | `Not Working` |
| x86_gcc4      | `Not Working` |
| x64           | `Not Working` |
