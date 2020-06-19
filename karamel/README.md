# Karamel : Apache Camel loves Apache Karaf

Karamel is a set of tools and runtime to efficiently and smoothly runs build, package and run your Camel
routes on Karaf runtime.

It gives you the flexibility to have a dedicated or multi-tenant runtime for your routes, leveraging provided "out of the box" features.

## Build

### CLI

----
# karamel build myroute.class
# karamel build myroute.xml
# karamel build myroute.groovy
----

### Maven

### Gradle

## Run

### CLI

----
# karamel run route1.jar route2.jar
# karamel run route1.jar route2.xml
# karamel run route1.groovy route2.xml
# karamel run route1.xml mybundle.jar
# karamel run route1.xml myfeature.xml
----

## Package

----
# karamel package route1.jar route2.jar
# karamel package route1.jar route2.xml
# karamel package route1.groovy route2.xml 
# karamel package route1.xml mybundle.jar
# karamel package route1.xml myfeature.xml
----

## Cloud ready, kubernetes, openshift