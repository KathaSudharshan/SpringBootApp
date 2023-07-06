# SpringBootDemoApp
Spring Boot Demo Application

## What is SrpingBoot
    SpringBoot is an extention of spring framework which is open source java based framework and used for creating faster and easier microservices for integrating with multiple systems/REST APIs.
Easy to create Stand alone and production grade applications using SpringBoot. 
Provides broad infrastructure support for creating micro and enterprise level applications for deveopers. Developed by Pivotal 

**Features**
1. No XML configuration required
2. Code Generation not neccesary
3. In build Tomcat, Jetty or Under Tow web application server
4. Supported build tools are Maven and Gradle.
5. Spring application configuration is Automated.
6. Provide Monitoring, health checks etc.

**Prerequisites**
1. JDK 1.8 or higher versions
2. Maven latest version
3. [Gradle](https://docs.spring.io/spring-boot/docs/current-SNAPSHOT/reference/htmlsingle/#using.build-systems.gradle) latest version and setup environment variables
    a. Check installation using commandline: gradle -version
4. Download [spring boot CLI](https://docs.spring.io/springboot/ docs/current-SNAPSHOT/reference/htmlsingle/#getting-started-installing-springboot) and setup environment variables
     a.Check installation using commandline: spring --version

## How to Create a DEMO Application
1. Use Spring Initializer  to create a Spring Boot Application using [start.spring.io](https://start.spring.io/)
2. Follow as per the below image and select neccessary attributes and click on generate to create a Spring boot application.
![image](https://github.com/KathaSudharshan/SpringBootApp/assets/138109855/fd7b6053-e6da-4efa-8196-19dacbfb82c4)
3. Unzip the JAR/WAR file, observe Demo java class, POM and Gradle files which automatically generated as per the Spring boot Web application. Upload it into IDE.
4. Once uploaded do the following changes,
   a. Create a Rest Endpoint as (/demo) in the Spring Application adding @ResrController annotation on top of the Demo Java class.
   b. Use @RequestMapping(value="/demo") on top of 
   


