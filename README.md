<div align="center">
    <a href="https://github.com/softspiders/softspiders">
      <img src="https://avatars.githubusercontent.com/u/47006425?v=4"width="100" height="100"/>
    </a>
</div> 

# War HelloWorld on Spring Boot


## Feature tags

- maven
- spring-boot
- starter
- template
- war

---

## Direct ancestor

[- war](https://github.com/AlexanderLapygin/spring-boot-helloworld#readme)

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
2) Copy the resulting *springboot-war-helloworld.war* file to the *<CATALINA_HOME>/webapps* directory of your Tomcat server.

3) Start the Tomcat server. You can start Tomcat by running the startup.sh script (for Unix) or startup.bat script (for Windows) in the *<CATALINA_HOME>/bin* directory.

4) After Tomcat starts successfully, your application will be accessible at http://localhost:8080/springboot-war-helloworld/hello.

### License

Licensed under the [MIT license](./LICENSE)

---

[SOFTSPIDERS](https://github.com/softspiders/softspiders)
