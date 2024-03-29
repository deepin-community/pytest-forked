v1.6.0
======

* Relaxed dependency requirements (`#77 <https://github.com/pytest-dev/pytest-forked/issues/77>`__).

v1.5.0
======

* Dropped support for Python 3.6.
* Added official support for Python 3.11.

v1.4.0
======

* Dropped support for Python 2.7 and 3.5.
* Added official support for Python 3.10.

v1.3.0
======

* Add support for pytest 6 (issue #45 / PR #46)
* Replace `@pytest.mark.tryfirst` with newer `@pytest.hookimpl` (PR #46)
* Invoke `pytest_runtest_logstart` and `pytest_runtest_logfinish` hooks in `runtest_protocol` (issue #31 / PR #46)

v1.2.0
======

* Add limited support for xfail marker (issue #33 / PR #34).
* Fix support for pytest 5.4.0+ (issue #30 / PR #32).
* Drop support for Python 3.4 as it is EOL (PR #39).

v1.1.3
======

* Another dummy release to sort out missing wheels (hopefully).

v1.1.2
======

* Another dummy release to sort out missing wheels (hopefully).

v1.1.1
======

* Dummy release to sort out CI issues.

v1.1.0
======

* New marker `pytest.mark.forked` to fork before individual tests.

v1.0.2
======

* Fix support for pytest 4.2.

v1.0.1
======

* Fix support for pytest 4.1.

v1.0
=====

* just a takeout of pytest-xdist
