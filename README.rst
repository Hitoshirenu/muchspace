muchspace
=========

muchspace is python tool to calculate the space required to download
media links in a file.

**muchspace** uses `Google’s Fire module`_ to make the command line
interface. Refer their docs for more info.

Modules
=======

muchspace uses a number of open source python modules:

-  `fire`_ - Python Fire is a library for automatically generating command line interfaces (CLIs) from absolutely any Python object.
-  `requests`_ - Requests is the only Non-GMO HTTP library for Python, safe for human consumption.
-  `multiprocessing`_ -  Process-based parallelism, multiprocessing is a package that supports spawning processes using an API similar to the threading module.
- `more-itertools`_ - Python’s itertools library is a gem - you can compose elegant solutions for a variety of problems with the functions it provides.

Install
=======

::

   $ pip install muchspace

Usage
=====

::

   $ muchspace getinfo <FILE PATH> [--report] 

::

   $ muchspace 
     muchspace v2 - Pre-Alpha
     muchspace: The link status checking CLI.
     Type:        MuchSpace
     String form: <muchspace.muchspace.MuchSpace object at 0x7f0b405449e8>
     Docstring:   Fire Class for muchspace Operations 
     Author: abhiigatty 
     Email: abhiigatty@gmail.com
     muchspace: The link status checking CLI.
     Example usage:
     muchspace getinfo <FILE_PATH> or
     muchspace getinfo <FILE_PATH> --report # The --report will generate a json report 
     i.e
     muchspace getinfo --file-path <FILE_PATH> [--report]

     Usage:       muchspace 
                  muchspace getinfo

 

Development
===========

Want to contribute? Great! To contribute to the project, Please take up
the tasks specified in the issues. Add a comment in the issues if you
are taking up one. check out `contributing`_ for more details.


Todos
=====

- Better working with async mode

License
=======
MIT

**Free Software ❤️️, Hell Yeah!🍺**

.. _Google’s Fire module: https://github.com/google/python-fire
.. _fire: https://github.com/google/python-fire
.. _requests: http://docs.python-requests.org/en/master/
.. _here: https://help.github.com/articles/configuring-a-remote-for-a-fork/
.. _contributing: https://github.com/Hitoshirenu/muchspace/blob/master/CONTRIBUTING.rst
.. _multiprocessing: https://docs.python.org/dev/library/multiprocessing.html#multiprocessing.pool.Pool.starmap
.. _more-itertools: https://pypi.org/project/more-itertools/



