[![Build Status](https://travis-ci.org/DEV3L/mvn-hello-world-web-app.png)](https://travis-ci.org/DEV3L/mvn-hello-world-web-app)

# mvn-hello-world-web-app
Java Hello World web application created using maven-archetype-webapp

## Blog Post Reference
https://softwaredev3loper.wordpress.com/2016/02/17/from-zero-to-continuous-delivery/

## Dependancies
* git
* maven
* tomcat

## Eclipse Project setup
* Use git clone to pull project into workspace directory
 * git clone https://github.com/DEV3L/mvn-hello-world-web-app.git
* Use maven to resolve Eclipse dependencies
 * mvn eclipse:eclipse
* Import 'mvn-hello-world-web-app' as existing project into Eclipse 
* Use maven to run integration tests and install
 * mvn clean install
