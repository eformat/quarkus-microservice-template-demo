# quarkus-microservice-template-demo

a template base extension for your microservice


## Local build

Add `-DskipTests` if you dont want the devservices test to run:

```bash
mvn clean install
```

## Usage

Create a dependant microservice:

```bash
quarkus create app \
  --maven --java --no-wrapper \
  org.acme:movies:1.0.0-SNAPSHOT
```

add:

```xml
    <dependency>
      <groupId>me.escoffier.microservice</groupId>
      <artifactId>quarkus-microservice-deployment</artifactId>
      <version>1.0.0-SNAPSHOT</version>
    </dependency>
```

Code !!
