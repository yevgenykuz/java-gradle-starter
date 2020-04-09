Java Gradle Starter
###################

Java, gradle based playground starter project.

|travis_ci| |codecov|

-----

.. contents::

.. section-numbering::

Features
========

This starter includes:

* **Logback** - Console and rotating file logging - see `logback.xml`_
* **Junit 5 + hamcrest** - Testing frameworks
* **Executable jar creation** - See gradle-shade-plugin plugin section in `pom.xml`_
* **Travis CI with codecov template** - Basic travis CI configuration with codecov - see `travis.yml`_
* **Basic gradle profiles with parameter injection** - See `temp.properties`_ and `pom.xml`_
* **GitHub templates** - See `.github folder`_ and .md files in root folder
* **Code quality tools** - Checkstyle, PMD and SpotBugs configuration - see `pom.xml`_

Usage
=====

* Clone or download

Meta
====

Authors
-------

`yevgenykuz <https://github.com/yevgenykuz>`_

License
-------

`MIT License <https://github.com/yevgenykuz/java-gradle-starter/blob/master/LICENSE>`_


-----

.. _`logback.xml`: https://github.com/yevgenykuz/java-gradle-starter/blob/master/src/main/resources/logback.xml
.. _`pom.xml`: https://github.com/yevgenykuz/java-gradle-starter/blob/master/pom.xml
.. _`travis.yml`: https://github.com/yevgenykuz/java-gradle-starter/blob/master/.travis.yml
.. _`temp.properties`: https://github.com/yevgenykuz/java-gradle-starter/blob/master/src/main/resources/temp.properties
.. _`.github folder`: https://github.com/yevgenykuz/java-gradle-starter/tree/master/.github

.. |travis_ci| image:: https://travis-ci.org/yevgenykuz/java-gradle-starter.svg?branch=master
    :target: https://travis-ci.org/yevgenykuz/java-gradle-starter
    :alt: Travis CI

.. |codecov| image:: https://codecov.io/gh/yevgenykuz/java-gradle-starter/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/yevgenykuz/java-gradle-starter/branch/master
    :alt: Test coverage
