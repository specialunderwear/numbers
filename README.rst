Numbers for Humans
==================

Because sometimes using builtins is hard.


Usage
-----

>>> from numbers import number, rebnum
>>> number(1)
1

Simple comparisons:

>>> number(1) < number(2)
True

Complicated math:

>>> number(1) * number(50) / number(25)
2

Inverse function:

>>> rebnum(7)
-7

Real results:

>>> number(sys.maxint)
"It's over 9000!"

Credits
-------

This project was inspired by `prices <https://github.com/mirumee/prices>`_ (and many others), because sometimes
understanding your code should be just as difficult as maintaining your data in MongoDB.