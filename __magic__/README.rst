Python __magic__ variables
==========================

Magic variables are special variables used for controlling and/or revealing
some internal Python behavior These variables are user-definable (they're not
reserved words) and their names start and end with two underscores by
convention.  These variables can sometimes be used to tweak the behavior of
Python objects in interesting ways.


Included Files
--------------

* ``callable.py``: creating a callable object with ``__call__`` method
* ``comparisons.py``: comparing objects using magic comparison methods
* ``context_manager.py``: create a context manager with ``__enter__`` and
  ``__exit__`` methods
* ``hashable.py``: creating a hashable object with ``__hash__`` and ``__eq__``
* ``dict_examples.py``: examples of some magic methods using a dict object


Pycco-Generated Documentation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The ``docs`` directory holds HTML documentation that presents comments and
docstrings to the left and code to the right.  To view this documentation open
any of the HTML files in a web browser (usually by double-clicking the file).

References
----------
* `A Guide to Python's Magic Methods <http://www.rafekettler.com/magicmethods.html>`_
* `Data Model Reference from Python Documentation <http://docs.python.org/release/2.7.3/reference/datamodel.html>`_
* `PEP 257: Docstring Conventions <http://www.python.org/dev/peps/pep-0257/>`_
* `"in" operator implementation <http://stackoverflow.com/questions/9089400/python-set-in-operator-uses-equality-or-identity>`_
* `"hashable" in Python Glossary <http://docs.python.org/glossary.html#term-hashable>`_
* `StackOverflow Answer about subclassing dict <http://stackoverflow.com/questions/2328235/pythonextend-the-dict-class>`_
* `Better Python APIs <http://ozkatz.github.com/better-python-apis.html>`_
