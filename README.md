# OpenMRS module bahmnicore

This module provides necessary services for running Bahmni

## Build 

## Prerequisites

- JDK 1.8
- Ruby 2.2+
- RubyGems
- Compass 1.0.3

## Build Instructions

```bash
git clone https://github.com/Rijan9860/BahmniCore-0.92.git
cd bahmni-core
mvn clean install -DskipTests
```

## Deploy
Copy bahmni-core/bahmnicore-omod/target/bahmnicore-omod-VERSION-SNAPSHOT.omod into OpenMRS modules directory and restart OpenMRS
