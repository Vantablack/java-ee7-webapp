# Java EE 7 WAR Webapp

Java EE 7 Webapp generated using [maven archetype](https://mvnrepository.com/artifact/org.codehaus.mojo.archetypes/webapp-javaee7/1.1).

Configured [Jetty Maven Plugin](https://mvnrepository.com/artifact/org.eclipse.jetty/jetty-maven-plugin) to work on port 8080

## Getting Started

Simple project to quickly start a EE 7 webapp project for development.

### Prerequisites

- [Java SE/JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
- [Apache Maven](https://maven.apache.org/)

### Installing

Clone the repo and install maven dependencies.

```bash
cd dirname && mvn install
```

### Run

Either built a WAR file and deploy on Tomcat

```bash
mvn package
```

or run using Jetty Plugin [(docs)](https://www.eclipse.org/jetty/documentation/9.4.x/jetty-maven-plugin.html)

```bash
mvn jetty:run
```