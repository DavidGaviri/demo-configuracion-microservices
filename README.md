 Configuration Repository for Microservices

This repository serves as a centralized configuration store for multiple microservices.
It is typically used with Spring Cloud Config Server, allowing microservices to fetch their configuration dynamically from a single source of truth.

 Purpose

Centralize configuration management for all microservices.

Decouple configuration from service code.

Support multiple environments (development, testing, staging, production).

Provide version control and traceability of configuration changes.

 How It Works

Microservices request their configuration from the Config Server.

The Config Server reads the appropriate file from this repository (based on the service name and active profile).

Configuration is injected into the microservice at startup or refreshed dynamically.
