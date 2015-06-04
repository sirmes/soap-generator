#Generating SOAP Classes used by the Spring WS-SOAP Client

1. On command line, navigate to this directory
1. Generate the java source files issuing the command

```sh
mvn clean generate-sources
```

1. Copy the wsdl folder from the path {project.dir}target/generated-sources/xjc/org/sirmes/ to the convenient maven project package

References:

- https://spring.io/guides/gs/consuming-web-service/ 
