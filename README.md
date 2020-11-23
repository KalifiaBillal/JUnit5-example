![JUnit5](https://www.codeaffine.com/wp-content/uploads/2016/02/junit-lambda.png)

# junit5-jupiter-starter-gradle

The `junit5-jupiter-starter-gradle` project demonstrates how to run tests based on JUnit
Jupiter using [Gradle's native JUnit Platform support], Gradle's Groovy DSL
and code and tests written in Java.

[Gradle's native JUnit Platform support]: https://docs.gradle.org/current/userguide/java_testing.html#using_junit5

# Overview 

The goal of this document is to provide comprehensive reference documentation for programmers writing tests, extension authors, and engine authors as well as build tool and IDE vendors.

# JUnit 5

## What is JUnit 5?

Unlike previous versions of JUnit, JUnit 5 is composed of several different modules from three different sub-projects.

JUnit 5 = JUnit Platform + JUnit Jupiter + JUnit Vintage

The JUnit Platform serves as a foundation for launching testing frameworks on the JVM. It also defines the TestEngine API for developing a testing framework that runs on the platform. Furthermore, the platform provides a Console Launcher to launch the platform from the command line and a JUnit 4 based Runner for running any TestEngine on the platform in a JUnit 4 based environment. First-class support for the JUnit Platform also exists in popular IDEs (see IntelliJ IDEA, Eclipse, NetBeans, and Visual Studio Code) and build tools (see Gradle, Maven, and Ant).

JUnit Jupiter is the combination of the new programming model and extension model for writing tests and extensions in JUnit 5. The Jupiter sub-project provides a TestEngine for running Jupiter based tests on the platform.

JUnit Vintage provides a TestEngine for running JUnit 3 and JUnit 4 based tests on the platform.

![JUnit5](https://static.packt-cdn.com/products/9781787284661/graphics/f33bca9e-f503-4cdc-aa20-d90ca0d07e74.png)

## Supported Java Versions

JUnit 5 requires Java 8 (or higher) at runtime. However, you can still test code that has been compiled with previous versions of the JDK.


