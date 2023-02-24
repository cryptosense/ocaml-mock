# Mock - configurable functions to test impure code

[![Build Status][build_status_badge]][build_status_link]
[![Documentation][doc_badge]][doc_link]

This package provides "mocks", fake functions that can be configured to return
values or raise exceptions. It is possible to inspect their arguments after
their execution. The API is greatly inspired by [unittest.mock] in Python.

There is no magic under the hood, it is "just" a reference to a function, but
it makes it possible to have pleasant output like this in your tests:

> expected f to be called once, but it was called 3 times

A wrapper for OUnit is available as `mock-ounit`.

[build_status_badge]: https://github.com/cryptosense/ocaml-mock/actions/workflows/main.yml/badge.svg
[build_status_link]: https://github.com/cryptosense/ocaml-mock/actions/workflows/main.yml
[doc_badge]: https://img.shields.io/badge/doc-online-blue.svg
[doc_link]: https://cryptosense.github.io/ocaml-mock/doc/
[unittest.mock]: https://docs.python.org/3/library/unittest.mock.html
