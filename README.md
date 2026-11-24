# Billing Platform

A billing and receivables platform for a fictional utility company. It bills customers, takes payments, charges interest and penalties on late balances, runs installment plans, handles disputes, and exchanges data with outside systems.

All data is synthetic. The domain model draws on years of building billing and receivables systems for public-sector clients.

## Stack

- Java 25
- Spring Boot 4.2
- Maven (through the wrapper, so no local install is needed)

## Run it

```bash
./mvnw spring-boot:run
```

Then check that it is up:

```bash
curl http://localhost:8080/actuator/health
```

## Test it

```bash
./mvnw verify
```
