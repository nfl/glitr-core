<img src="http://static.nfl.com/static/content/public/static/img/logos/nfl-engineering-light.svg" width="300" />

# GLiTR

[![Build Status](https://api.travis-ci.org/nfl/glitr-core.svg?branch=master)](https://travis-ci.org/nfl/glitr-core) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.nfl.glitr/glitr-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.nfl.glitr/glitr-core) [ ![Download](https://api.bintray.com/packages/nfl/maven/glitr-core/images/download.svg) ](https://bintray.com/nfl/maven/glitr-core/_latestVersion) [![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/nfl/glitr-core/blob/master/LICENSE)

Glitr annotations

## Binaries

Example for Maven:

```xml
<dependency>
    <groupId>com.nfl.glitr</groupId>
    <artifactId>glitr-core</artifactId>
    <version>x.y.z</version>
</dependency>
```

Example for gradle:

```gradle
compile("com.nfl.glitr:glitr-core:x.y.z")
```

Change history can be found here: [CHANGELOG.md](https://github.com/nfl/glitr-core/blob/master/CHANGELOG.md)

### How to use the latest build with Gradle

Add the repositories:

```groovy
repositories {
    maven { url  "http://dl.bintray.com/nfl/maven" }
}
```

Dependency:

```groovy
dependencies {
  compile 'com.nfl.glitr:INSERT_LATEST_VERSION_HERE'
}
```

### How to use the latest build with Maven

Add the repository:

```xml
<repository>
    <snapshots>
        <enabled>false</enabled>
    </snapshots>
    <id>bintray-nfl-maven</id>
    <name>bintray</name>
    <url>http://dl.bintray.com/nfl/maven</url>
</repository>

```

Dependency:

```xml
<dependency>
    <groupId>com.nfl.glitr</groupId>
    <artifactId>glitr-core</artifactId>
    <version>INSERT_LATEST_VERSION_HERE</version>
</dependency>

```

## Build

To build:

```
$ git clone git@github.com:NFL/glitr-core.git
$ cd glitr-core/
$ ./gradlew build
```

Further details on building can be found on the [Getting Started](https://github.com/NFL/glitr/wiki/Getting-Started) page of the wiki.

## Requirements

 - >= Java 8

## Contact Info

- Twitter: [@nflengineers](http://twitter.com/nflengineers)
- [GitHub Issues](https://github.com/NFL/glitr/issues)


## LICENSE

GLiTR is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
