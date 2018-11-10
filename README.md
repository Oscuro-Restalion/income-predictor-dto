# income-predictor-dto
The aim of this project is provide a common interface to be utilized in communications between all microservices-ml projects.

![alt Topology](https://github.com/Oscuro-Restalion/income-predictor-dto/blob/master/images/DTOTopology.png)

You can find more info about the main project in [microservices-ml page](https://github.com/Oscuro-Restalion/microservices-ml)

This project includes all Data Transfer Objects needed in the solution, it also includes all the types needed to process the input file.

## Classes

![alt income-predictor-dto project class diagram](https://github.com/Oscuro-Restalion/income-predictor-dto/blob/master/images/DTO-Diagram.png)

## Quick Start

This section can help you to compile the project without a deep knowledge of the different technologies used. Please follow the instructions and PR if more information is needed.

### Maven

#### Prerrequisites

##### Java

You need a JDK installed to compile all the projects, you can download the latest version from [Oracle](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html), [OpenJDK](http://openjdk.java.net/install/) or [Azul Zulu (not tested)](https://www.azul.com/downloads/zulu/)

You can check that Java is available with the command below:

_java -version_

##### Maven

You also need Apache Maven installed. You can find installation instructions [here](https://maven.apache.org/download.cgi)

You can check your maven installation with the command below:

_mvn -version_

#### Process

##### Compilation
1. Clone project in a local directory and enter into income-predictor-dto folder.
1. Into this project run _mvn clean install_, execution should finish with a _BUILD SUCCESS_ message.
1. Now artifact income-predictor-dto should be available into your local .m2 folder.