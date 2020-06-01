Java Gradle Starter
###################

Java, gradle based playground starter project.

|ci| |codecov|

-----

.. contents::

.. section-numbering::

Features
========

This starter includes:

* **Logback** - Console and rotating file logging - see `logback.xml`_
* **Junit 5 + hamcrest** - Testing frameworks
* **Executable jar creation** - See gradle-shade-plugin plugin section in `build.gradle`_
* **Github actions CI with codecov template** - Basic github CI workflow with codecov report - see `.github/workflows/ci.yml`_
* **Basic gradle profiles with parameter injection** - See `temp.properties`_ and `build.gradle`_
* **GitHub templates** - See `.github folder`_ and .md files in root folder
* **Code quality tools** - Checkstyle, PMD and SpotBugs configuration - see `build.gradle`_

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
.. _`build.gradle`: https://github.com/yevgenykuz/java-gradle-starter/blob/master/build.gradle
.. _`.github/workflows/ci.yml`: https://github.com/yevgenykuz/java-gradle-starter/blob/master/.github/workflows/ci.yml
.. _`temp.properties`: https://github.com/yevgenykuz/java-gradle-starter/blob/master/src/main/resources/temp.properties
.. _`.github folder`: https://github.com/yevgenykuz/java-gradle-starter/tree/master/.github

.. |ci| image:: https://github.com/yevgenykuz/java-gradle-starter/workflows/All%20JDKs%20on%20all%20OSs/badge.svg
    :target: https://github.com/yevgenykuz/java-gradle-starter/actions?query=workflow%3A%22All+JDKs+on+all+OSs%22
    :alt: Github CI

.. |codecov| image:: https://codecov.io/gh/yevgenykuz/java-gradle-starter/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/yevgenykuz/java-gradle-starter/branch/master
    :alt: Test coverage
