# RingoJS Maven Skeleton

This is an example of a webapp built with Maven using RingoJS as a dependency.

## Setup

Download RingoJS, cd into `ringojs` and run:

    mvn install:install-file -Dfile=lib/ringo.jar -DpomFile=pom.xml

Then cd into `ringo-maven` and run:

    mvn clean compile package


