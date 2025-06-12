
<a name="readme-top"></a>

<div align="center">


  <!--Logo-->
  <a href="https://github.com/avaje">
    <img src="/profile/logo.svg" alt="Logo" width="40%">
  </a>

  <!--Title-->
  <h3 align="center">Compile-time libraries for JVM applications</h3>

  <a href="https://avaje.io" style="margin: 1em"><strong>View the documentation →</strong></a>

  <!--License badge-->
  <a href="https://github.com/javalin/javalin/blob/master/LICENSE">
    <img alt="Static Badge" src="https://img.shields.io/badge/License-Apache_2.0-blue">
  </a>
  <!--Discord badge-->
  <a href="https://discord.gg/Qcqf9R27BR">
    <img alt="Discord Link" src="https://img.shields.io/badge/discord-avaje-blue?logo=discord&logoColor=white">
  </a>
</div>

# 

Avaje is a set of Java libraries for building applications. 

Most use annotation processing to make them exceptionally light and most importantly, _**reflection-free**_. The effective size of all the following libraries _combined_ barely takes up 0.8MB. (This is because most of the heavy lifting is done in annotation processors that are not included in your final jar)

- [avaje-config](https://github.com/avaje/avaje-config) (Provides external configuration via loading yaml and property files)
- [avaje-inject](https://github.com/avaje/avaje-inject) (Compile-time Dependency Injection)
- [avaje-http](https://github.com/avaje/avaje-http) (Generates Helidon/Javalin/Jex/Sigma adapters from JAX-RS Style Controllers)
- [avaje-http-client](https://github.com/avaje/avaje-http/tree/master/http-client) (Wraps and enhances the built-in JDK HTTP client)
- [avaje-jsonb](https://github.com/avaje/avaje-jsonb) ([Lightning fast](https://github.com/fabienrenaud/java-json-benchmark#users-model) compile-time json serialization)
- [avaje-validator](https://github.com/avaje/avaje-validator) (Compile-time Pojo Validation)
- [avaje-jex](https://github.com/avaje/avaje-jex) (Wraps the built-in JDK HttpServer to make it ergonomic)
- [avaje-sigma](https://github.com/avaje/avaje-sigma) (Http Routing for AWS lambda)
- [avaje-record-builder](https://github.com/avaje/avaje-record-builder) (Creates builders for JDK 17 records)
- [avaje-spi-service](https://github.com/avaje/avaje-spi-service) (Adds META-INF/services entries for classes and validates module files)
- [avaje-prisms](https://github.com/avaje/avaje-prisms) (Utility Lib for writing annotation processors)

General information:
* The project webpage and docs for the various libraries are at [avaje.io](https://avaje.io).
* Chat/Ask questions on Discord: https://discord.gg/Qcqf9R27BR
* License summary: https://tldrlegal.com/license/apache-license-2.0-(apache-2.0)

