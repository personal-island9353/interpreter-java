# About this project

Java version of Monkey language interpreter from "Writing an Interpreter in Go" book by
Thorsten Ball

# Versions

## Java

```
openjdk version "25.0.1" 2025-10-21 LTS
OpenJDK Runtime Environment Temurin-25.0.1+8 (build 25.0.1+8-LTS)
OpenJDK 64-Bit Server VM Temurin-25.0.1+8 (build 25.0.1+8-LTS, mixed mode, sharing)
```

## Windows

**Windows 11 Home** version **25H2**

## Build and run Monkey interpreter

Build the app-image:

```shell
./mvnw clean package -Pwindows
```

Run the freshly built app-image:

```shell
.\monkey\monkey.exe
```

# TODO

* JUnit5
* GitHub Actions
    * tests
    * quality
    * release