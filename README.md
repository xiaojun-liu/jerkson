# Jerkson for Scala 2.10 #

[Jerkson](https://github.com/codahale/jerkson) has only been published for
Scala versions as high as 2.9.1.

## Differences from upstream Jerkson ##

- sbt instead of Maven.
- Tests have been deleted, since sbt cannot run
  [simplespec](https://github.com/SimpleFinance/simplespec) tests.
- Minor tweaks to get compilation in 2.10.

## Install ##

- This version of Jerkson is hosted on
  [Maven Central](http://central.maven.org/maven2/com/yuvimasory/jerkson_2.10).
- From sbt:

  ```scala
  libraryDependencies += "com.yuvimasory" %% "jerkson" % "0.6.1"
  ```
- From Maven:

  ```xml
  <dependency>
    <groupId>com.yuvimasory</groupId>
    <artifactId>jerkson_2.10</artifactId>
    <version>0.6.1</version>
  </dependency>
  ```

## Build ##

- Just compile:
  ```sh
  $ cd jerkson
  $ ./sbt compile
  ```
- Publish:
  ```sh
  $ ./sbt publish
  ```
  
## Future plans ##

Jerkson is legacy.
I won't do any further work except providing the 2.10 jars.
I suggest you switch to one of the many excellent Scala Json libraries.

## Contact ##

Repo maintained by [Yuvi Masory](http://yuvimasory.com).  
[ymasory@gmail.com](ymasory@gmail.com)
