# Kafka + Spring Boot Demo

A compact Kafka/Spring Boot example project. The repository contains a compressed project archive, `kafka-springboot-demo.7z`; extract it to access the application source, Maven configuration, and any associated instructions.

## Requirements

- JDK version required by the extracted project's Maven configuration
- Apache Kafka broker
- 7-Zip or another tool capable of extracting `.7z` archives

## Getting started

```bash
git clone https://github.com/Rawkesh2k/kafka-springboot-simplified.git
cd kafka-springboot-simplified
```

Extract `kafka-springboot-demo.7z`, then inspect its `pom.xml` and application configuration. Start a Kafka broker and set the bootstrap-server/topic configuration before launching the Spring Boot application. Use the Maven Wrapper if included in the extracted project; otherwise use Maven:

```bash
./mvnw spring-boot:run
```

## Tests

If the extracted Maven project includes tests:

```bash
./mvnw test
```

## Notes

Exact API routes, message formats, and broker settings depend on the archived source; this README avoids assuming details not visible in the repository root. Keep Kafka credentials outside source control.
