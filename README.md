# IKVM.NET v8.1.5717.0 Binary

[IKVM.NET](http://www.ikvm.net/) is an implementation of Java for Mono and the Microsoft .NET Framework. 

### It includes the following components:

* A Java Virtual Machine implemented in .NET
* A .NET implementation of the Java class libraries
* Tools that enable Java and .NET interoperability

## What's New (relative to [IKVM.NET 8.0](http://weblog.ikvm.net/2015/01/12/IKVMNET80ReleaseCandidate1.aspx)):

* Integrated OpenJDK 8u45.
* Many fixes to late binding support.
* Added ikvmc support for deterministic output files.
* Various sun.misc.Unsafe improvements.
* Many minor bug fixes and performance tweaks.

## Changes since previous development snapshot:

* Assemblies are strong named.
* Fix for bug [#303](http://sourceforge.net/p/ikvm/bugs/303/). ikvmc internal compiler error when trying to get interfaces from type from missing assembly reference.
* Implemented NIO atomic file move on Windows.

### Sources:

[ikvmsrc-8.1.5717.0.zip](http://www.frijters.net/ikvmsrc-8.1.5717.0.zip)
[openjdk-8u45-b14-stripped.zip](http://www.frijters.net/openjdk-8u45-b14-stripped.zip)
