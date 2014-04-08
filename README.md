PyKu
=====

PyKu is a Python binding for the native Haiku-OS API.

This work aims to pick up where the 2011 GSoC Language bindings by Sean Healy 
left off. This particular codebase will focus only on the python bindings.

To access the original code from this GSoC project, please see the following:

https://github.com/HaikuArchives/HaikuLanguageBindings

Current Status
--------------

At this point, this project appears to build under a recent haiku-gcc4-hybrid
system. It is not known, but it is suspected PyKu may not build on the other architectures without some further modifications.

The state of this repository with respect to the different haikuporter builds should be listed below.


PyKu 0.01:

| Architecture  | Build Status  | Haiku Revision |
| ------------- | :-----------: | :------------: |
| x86_gcc2      | `Unknown`     | -              |
| x86_gcc4      | `Unknown`     | -              |
| x64           | `Working`     | hrev47061      |
