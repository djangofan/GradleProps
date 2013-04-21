GradleProps
===========

Test of gradle system properties.

What is this?
=====================

This is a test trying to figure out why the following Gradle
code does not work:

    tasks.withType(Test) {
        systemProperties = System.properties
    }
