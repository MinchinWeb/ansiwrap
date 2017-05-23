
| |travisci| |version| |versions| |impls| |wheel| |coverage|

.. |travisci| image:: https://api.travis-ci.org/jonathaneunice/ansiwrap.svg
    :target: http://travis-ci.org/jonathaneunice/ansiwrap

.. |version| image:: http://img.shields.io/pypi/v/ansiwrap.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/ansiwrap

.. |versions| image:: https://img.shields.io/pypi/pyversions/ansiwrap.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/ansiwrap

.. |impls| image:: https://img.shields.io/pypi/implementation/ansiwrap.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/ansiwrap

.. |wheel| image:: https://img.shields.io/pypi/wheel/ansiwrap.svg
    :alt: Wheel packaging support
    :target: https://pypi.python.org/pypi/ansiwrap

.. |coverage| image:: https://img.shields.io/badge/test_coverage-100%25-6600CC.svg
    :alt: Test line coverage
    :target: https://pypi.python.org/pypi/ansiwrap


``ansiwrap`` wraps text, like the standard ``textwrap`` module.
But it also correctly wraps text that contains ANSI control
sequences that colorize or style text. Where ``textwrap`` is
fooled by the raw string length of those control codes,
``ansiwrap`` is not; it understands those codes affect
color and display style, but have no logical length.

The API mirrors the ``wrap`` and ``fill`` functions of ``textwrap``.

See also the enclosed ``demo.py``.

.. image:: https://content.screencast.com/users/jonathaneunice/folders/Jing/media/8db64be2-01cc-4da4-b46a-789c53c63b44/00000569.png
   :align: center

    the plain REPL simply doesn't provide with any quality.