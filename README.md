[![Linux/Mac Build Status](https://secure.travis-ci.org/tcurdt/jdeb.png)](http://travis-ci.org/tcurdt/jdeb)
[![Windows Build Status](https://img.shields.io/appveyor/ci/tcurdt/jdeb/master.svg?label=windows)](https://ci.appveyor.com/project/tcurdt/jdeb/branch/master)
[![Coverage Status](https://coveralls.io/repos/tcurdt/jdeb/badge.svg?branch=master&service=github)](https://coveralls.io/github/tcurdt/jdeb?branch=master)
[![Maven Central](https://img.shields.io/maven-central/v/org.vafer/jdeb.svg?maxAge=2592000)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22org.vafer%22%20AND%20a%3A%22jdeb%22)
[![Join the chat at https://gitter.im/tcurdt/jdeb](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/tcurdt/jdeb?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# Debian packages in Java

This library provides an Ant task and a Maven plugin to create Debian packages
from Java builds in a truly cross platform manner. Build your Debian packages
on any platform that has Java support. Windows, Linux, OS X - it doesn't require
additional native tools installed.

Check the documentation on how to use it with [Maven](http://github.com/tcurdt/jdeb/blob/master/docs/maven.md)
or [Ant](http://github.com/tcurdt/jdeb/blob/master/docs/ant.md). Especially don't forget to check out the
[examples](http://github.com/tcurdt/jdeb/blob/master/src/examples/). Current
[javadocs](http://tcurdt.github.com/jdeb/release/1.5/apidocs/) and a source
[xref](http://tcurdt.github.com/jdeb/release/1.5/xref/) is also available.


## Where to get it

The jars are available in the [Maven central repository](http://repo1.maven.org/maven2/org/vafer/jdeb/).

If you feel adventurous or want to help out feel free to get the latest code
[via git](http://github.com/tcurdt/jdeb/tree/master).

    git clone git://github.com/tcurdt/jdeb.git

## Where to ask questions

[via gitter](https://gitter.im/tcurdt/jdeb)

[via git issue](https://github.com/tcurdt/jdeb/issues)


## Working towards jdeb 2.0

Over the years jdeb has grown more and more powerful - but also got more complex. In order to simplify the usage and apply what we have learned we are taking a step back. If you want to help to shape the usage of jdeb 2.0 feel free to contribute to the [planing](https://github.com/tcurdt/jdeb/issues/195).

## Related projects

Some links to other cross platform tools to package Linux applications:
* [apt-repo](https://github.com/theoweiss/apt-repo)
* [ant-deb-task](http://code.google.com/p/ant-deb-task)
* [jRPM](http://jrpm.sourceforge.net)
* [Install-Toolkit](http://install-toolkit.sourceforge.net)
