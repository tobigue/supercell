supercell
=========

Supercell is a framework for creating RESTful APIs that loosely follow the idea
of *domain driven design*. Writing APIs in supercell begins with creating the
domain classes using *schematics* and creating code for storing, manipulating
and querying the data. Only then *Tornado* request handlers are created and
*scales* will give you insights into the running API instance. At this point
supercell will take care of transforming the incoming and outgoing
serializations of the domain models.

|TravisImage|_ |CoverAlls|_

.. |TravisImage| image:: https://travis-ci.org/truemped/supercell.png?branch=master
.. _TravisImage: https://travis-ci.org/truemped/supercell
.. |CoverAlls| image:: https://coveralls.io/repos/truemped/supercell/badge.png?branch=master
.. _CoverAlls: https://coveralls.io/r/truemped/supercell

Quick Links
===========

* `Documentation <http://supercell.rtfd.org>`_
* `Source (Github) <http://github.com/truemped/supercell>`_
* `Issues (Github) <http://github.com/truemped/supercell/issues>`_


Authors
=======

In order of contribution:

* Daniel Truemper `@truemped <http://twitter.com/truemped>`_
* Tobias Guenther `@tobigue_ <http://twitter.com/tobigue_>`_


License
=======

License under Apache 2.0 -- see LICENSE
