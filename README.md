***The art of simplicity is a puzzle of complexity.***

## Android Maven Central version ##

This version is a fork of a port from the original repository. Upstream, forked repository: [bmoliveira/snake-yaml](https://github.com/bmoliveira/snake-yaml).

This repository exists only because fork is not available on Maven Central: [issue](https://github.com/bmoliveira/snake-yaml/issues/2). There is no code differences between upstream and this repo.

Changes made in upstream fork:

- Android maven deploy profile changes applied
- Some removed some javadoc generator lines that were thowing javadoc generator errors (follow the original javadocs)

With this version you can use snakeyaml directly from Maven Central!

Just add mavenCentral to repositories if there is not already there.

```groovy
allprojects {
	repositories {
	mavenCentral()
  }
}
```
And the dependency

```groovy
dependencies {
	compile 'pl.droidsonroids:snake-yaml:v1.18-android'
}
```


## Overview ##
[YAML](http://yaml.org) is a data serialization format designed for human readability and interaction with scripting languages.

SnakeYAML is a YAML processor for the Java Virtual Machine.

## SnakeYAML features ##

* a **complete** [YAML 1.1 processor](http://yaml.org/spec/1.1/current.html). In particular, SnakeYAML can parse all examples from the specification.
* Unicode support including UTF-8/UTF-16 input/output.
* high-level API for serializing and deserializing native Java objects.
* support for all types from the [YAML types repository](http://yaml.org/type/index.html).
* relatively sensible error messages.

## Info ##
 * [Changes](https://bitbucket.org/asomov/snakeyaml/wiki/Changes)
 * [Documentation](https://bitbucket.org/asomov/snakeyaml/wiki/Documentation)

## Contribute ##
* Mercurial DVCS is used to dance with the [source code](https://bitbucket.org/asomov/snakeyaml/src).
* If you find a bug in SnakeYAML, please [file a bug report](https://bitbucket.org/asomov/snakeyaml/issues?status=new&status=open).
* You may discuss SnakeYAML at
[the mailing list](http://groups.google.com/group/snakeyaml-core).
