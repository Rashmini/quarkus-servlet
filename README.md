# Quarkus-servlet-application
This is a web.xml based simple servlet application created using Quarkus.
Use "mvn clean package" command to generate the runner jar.

HotSpot build can be located in quarkus-servlet\target folder. Dockerfile.jvm can be used to deploy this file.
Natively built binary file can be located in the quarkus-servlet\native-build folder. Dockerfile.native can be used to deploy this file.

Packaging the project inside OpenJDK HotSpot container can be done using Dockerfile.hotspot file.
Building the native image and deploying it inside red hat universal base image can be done using Dockerfile.multistage file.
