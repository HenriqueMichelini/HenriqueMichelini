# Henrique Michelini

I’m a software developer in São Paulo, Brazil. I build backends with **Java, Spring Boot, and PostgreSQL**. I also work on the React interfaces and deployment infrastructure for those services, so I can follow a feature from a database transaction to the screen someone uses.

I was selected for Agibank’s **Programa de Formação de Devs Nativos em IA**, a developer training program focused on AI. In my own projects, I give coding agents a scoped issue and acceptance criteria, then review the changes and test the behavior.

## What I’m building

### [CareerOS](https://github.com/HenriqueMichelini/careeros)

CareerOS helps job seekers tailor a résumé and cover letter to a specific opening. An applicant saves their experience once, pastes a job posting, and reviews the drafts before exporting them. I’m building it with Go, React, and PostgreSQL. My next milestone is to test the MVP with job seekers and see which drafts they would actually send.

### [Vencce](https://vencce.com)

I’m building Vencce to help small businesses replace repetitive manual work with custom software. I start with the day-to-day process. If someone has to copy the same information between two tools, connecting those tools may be all the software the business needs.

## Selected Java projects

### [Craftalism](https://github.com/HenriqueMichelini/craftalism)

A Minecraft economy where Paper plugins and a React dashboard share a Spring Boot API. When a player uses `/pay`, the API debits one balance, credits the other, and records the transfer in a single PostgreSQL transaction. Retrying the same request with the same idempotency key returns the original transfer.

### [Dynamic Biomes](https://github.com/HenriqueMichelini/dynamic-biomes)

A Paper plugin where the same crop can grow differently depending on the season, biome, and soil fertility. I keep the growth rules in plain Java so I can test how a crop responds to different conditions without starting a Minecraft server. [Crop implementation](https://github.com/HenriqueMichelini/dynamic-biomes/tree/main/java/app/src/main/java/io/github/henriquemichelini/dynamicbiomes/crops)

### [Minecraft Lab Experiments](https://github.com/HenriqueMichelini/minecraft-lab-experiments)

I benchmark how Java code scans Minecraft terrain for ore. In one benchmark where all 4,096 blocks in a section matched, storing their positions in a `short[]` cut allocation from about **247 KB to 8.2 KB per scan** compared with creating an object for each match.

## Tools I use

- **Backend** · Java, Spring Boot, Spring Security, PostgreSQL
- **Frontend** · React, TypeScript, Astro, Tailwind CSS
- **Build and test** · Gradle (Kotlin DSL), JUnit, Testcontainers, JaCoCo, SonarQube, GitHub Actions
- **Infrastructure** · Linux, Docker Compose, Oracle Cloud Infrastructure (OCI), AWS, Terraform

**Certification** · Oracle Cloud Infrastructure 2025 Certified Architect Associate

## Contact

[Email](mailto:henrique.g.michelini@gmail.com) · [LinkedIn](https://linkedin.com/in/henrique-giammellaro-michelini)
