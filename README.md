<div align="center">
    <a href="https://github.com/softspiders/softspiders">
      <img src="https://avatars.githubusercontent.com/u/47006425?v=4"width="100" height="100"/>
    </a>
</div> 

UNDER DEVELOPMENT

# Spring Boot WAR with monitoring on Prometheus


## Feature tags

- actuator
- maven
- prometheus
- spring-boot
- starter
- template
- war

---

## Direct ancestor

[- actuator,prometheus](https://github.com/AlexanderLapygin/springboot-war-helloworld#readme)

---

## Author

[Alexander Lapygin](https://github.com/AlexanderLapygin) <<alexanderlapygin@gmail.com>>

---

## Requirements

- [Maven](https://maven.apache.org/)
- [Tomcat](https://tomcat.apache.org/download-80.cgi)

---

## Run

1) Build the WAR file by running the Maven command:

```sh
mvn clean package
```
2) Copy the resulting *springboot-war-prometheus.war* file to the *webapps* directory of your Tomcat server.

3) Start the Tomcat server by executing the appropriate startup script for your operating system. For example, run startup.sh (for Unix) or startup.bat (for Windows).

4) After Tomcat starts successfully, your application will be accessible at http://localhost:8080/springboot-war-prometheus/hello.

### License

Licensed under the [MIT license](./LICENSE)

---

[SOFTSPIDERS](https://github.com/softspiders/softspiders)
