# Covid Testing Service

 

- Covid API Gatway service runs on the port 9000
  `` http://localhost:9000``

## Prerequisites

What things you need to install the software and how to install them

```
- IntelliJ(Optional)
- JDK11
- Maven

```
## Start the spring boot service from root folder of the project
  - mvn clean package
  - java -jar target/covid_api_gateway-0.0.1-SNAPSHOT.jar
   * ``(Or)``
  - mvn spring-boot:run
   * ``(Or)``
  - Can import in IntelliJ aand run as main application by adding the Main file

## API
  - http://localhost:9000/covid-vaccination-service/vaccination/country/iso-code/{isoCode3}
  - http://localhost:9000/covid-vaccination-service/vaccination/manufacturer/iso-code/{isoCode3}
  - http://localhost:9000/covid-testing-service/testing/timeline/{isoCode3}
  - http://localhost:9000/covid-testing-service/testing/iso-code/{isoCode3}
  - http://localhost:9000/covid-reporting-service/reporting/all/stats
  - http://localhost:9000/covid-reporting-service/reporting/all
  
  - Repalce iso-code with isoCode3 of countries like GBR,IND.
  - Example : http://localhost:9000/covid-vaccination-service/vaccination/country/iso-code/GBR

## Diagnostics

1. Check for jdk version as it requires JDK 11
      - <terminal>> java -version
2. All the other srvices need to be up
       
## Contributing

 - Suhail Mir
  
 ## References
  - https://start.spring.io/
  - https://spring.io/projects/spring-cloud-gateway
  

