# ExpositoTOP

My first Maven project


## Building and useful commands

Validate the project is correct and all necessary information is available.
```bash
mvn validate
```

Install the package into the local repository, for use as a dependency in other projects locally.
```bash
mvn install
```

Compiles the project and leaves the result in target/classes
```bash
mvn compile
```

Take the compiled code and package it in its distributable format, such as a JAR.
```bash
mvn package
```

Generates site documentation for this project.
```bash
mvn site 
```
