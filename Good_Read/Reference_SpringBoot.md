# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/3.3.6/maven-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.3.6/maven-plugin/build-image.html)
* [Spring Web](https://docs.spring.io/spring-boot/3.3.6/reference/web/servlet.html)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/3.3.6/reference/actuator/index.html)
* [Spring Session](https://docs.spring.io/spring-session/reference/)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/3.3.6/reference/using/devtools.html)
* [Rest Repositories](https://docs.spring.io/spring-boot/3.3.6/how-to/data-access.html#howto.data-access.exposing-spring-data-repositories-as-rest)
* [Thymeleaf](https://docs.spring.io/spring-boot/3.3.6/reference/web/servlet.html#web.servlet.spring-mvc.template-engines)
* [Apache Freemarker](https://docs.spring.io/spring-boot/3.3.6/reference/web/servlet.html#web.servlet.spring-mvc.template-engines)
* [Spring Security](https://docs.spring.io/spring-boot/3.3.6/reference/web/spring-security.html)
* [Jersey](https://docs.spring.io/spring-boot/3.3.6/reference/web/servlet.html#web.servlet.jersey)
* [Vaadin](https://vaadin.com/docs)
* [Spring for GraphQL](https://docs.spring.io/spring-boot/3.3.6/reference/web/spring-graphql.html)
* [OAuth2 Client](https://docs.spring.io/spring-boot/3.3.6/reference/web/spring-security.html#web.security.oauth2.client)
* [OAuth2 Authorization Server](https://docs.spring.io/spring-boot/3.3.6/reference/web/spring-security.html#web.security.oauth2.authorization-server)
* [OAuth2 Resource Server](https://docs.spring.io/spring-boot/3.3.6/reference/web/spring-security.html#web.security.oauth2.server)
* [Spring LDAP](https://docs.spring.io/spring-boot/3.3.6/reference/data/nosql.html#data.nosql.ldap)
* [Spring Data MongoDB](https://docs.spring.io/spring-boot/3.3.6/reference/data/nosql.html#data.nosql.mongodb)
* [Spring Data Reactive MongoDB](https://docs.spring.io/spring-boot/3.3.6/reference/data/nosql.html#data.nosql.mongodb)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/)
* [Accessing JPA Data with REST](https://spring.io/guides/gs/accessing-data-rest/)
* [Accessing Neo4j Data with REST](https://spring.io/guides/gs/accessing-neo4j-data-rest/)
* [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/)
* [Handling Form Submission](https://spring.io/guides/gs/handling-form-submission/)
* [Securing a Web Application](https://spring.io/guides/gs/securing-web/)
* [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/)
* [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/)
* [Creating CRUD UI with Vaadin](https://spring.io/guides/gs/crud-with-vaadin/)
* [Building a GraphQL service](https://spring.io/guides/gs/graphql-server/)
* [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/)
* [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/)

### Maven Parent overrides

Due to Maven's design, elements are inherited from the parent POM to the project POM.
While most of the inheritance is fine, it also inherits unwanted elements like `<license>` and `<developers>` from the parent.
To prevent this, the project POM contains empty overrides for these elements.
If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.

