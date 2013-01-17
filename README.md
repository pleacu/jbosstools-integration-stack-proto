# The JBoss Integration Tools Project

## Summary

This project specifies the process for building and releasing the JBoss Developer Studio 
Integration Platform (JBoss Integration Tools).  The JBoss Integration Tools are comprised of
layered JBoss Developer Studio (JBDS) features/plugins.  The project provides the ability to 
build an update site which establishes an Integration Tools capture that's consistent with its 
JBoss target dependencies and independently releasable. 

## Install

_tbd_

## Building the JBoss Integration Tools Project

To build the _JBoss Integration Tools_ project requires specific versions of Java and Maven. 
The [How to Build JBoss Tools with Maven 3](https://community.jboss.org/wiki/HowToBuildJBossToolsWithMaven3)
document will guide you through that setup.

This command will run the build:

    $ mvn clean install

If you just want to check if things compiles/builds you can run:

    $ mvn clean verify 

## Contribute fixes and features

The _JBoss Integration Tools_ project is open source, and we welcome anyone that wants to participate and contribute.

