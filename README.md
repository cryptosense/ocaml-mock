# Mock - configurable functions to test impure code

This package provides "mocks", fake functions that can be configured to return
values or raise exception. It is possible to inspect their arguments after their
execution. The API is greatly inspired by [unittest.mock] in Python.

There is no magic under the hood, it is "just" a reference to a function, but
it makes it possible to have pleasant output like this in your tests:

> expected f to be called once, but it was called 3 times

A wrapper for `OUnit2` is available as `mock-ounit`.

[unittest.mock]: https://docs.python.org/3/library/unittest.mock.html
