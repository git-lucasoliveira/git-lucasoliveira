<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=00D1FF&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Lucas+Oliveira!+%F0%9F%91%8B;Java+Backend+Developer;+Java+%7C+Spring+Boot+%7C+AWS" alt="Typing SVG" />
</p>

---

# 👨‍💻 About Me

I am a **Java Backend Developer** at a consumer-credit fintech, where I build and maintain the internal platforms the operation runs on — replacing manual processes with software, and measuring the result. Currently pursuing a **Postgraduate Degree in Software Architecture at FIAP**, I focus on the Java ecosystem, Cloud Computing (AWS), and architecture decisions that are justified and measured rather than fashionable.

Beyond coding, I strongly value soft skills such as clear communication, problem-solving, and teamwork, always striving to understand the business needs to deliver impactful technical solutions.

---

# 🛠️ Tech Stack

### ⚙️ Core: Backend & Cloud
[![Backend Skills](https://skillicons.dev/icons?i=java,spring,postgresql,mysql,aws,docker,linux)](https://skillicons.dev)

### 🎨 Integração & Ferramentas
[![Frontend & Tools](https://skillicons.dev/icons?i=js,html,css,git,github)](https://skillicons.dev)

---

# 🚀 Featured Projects

### 🏦 StarSuite — Internal Credit Operations Platform
> *Professional work — source code is private (company-owned). Described here at the level of architecture and outcomes.*

The platform a consumer-credit fintech runs its operation on: 11 multi-tenant modules that replaced manual, spreadsheet-driven processes with software. I created it and remain its main developer as the project grew to involve other engineers.

<details>
  <summary><strong>📌 View Full Project Details</strong></summary>

- **Tech Stack:** Java 21, Spring Boot, PostgreSQL, Flyway, Docker, AWS (EC2, ECR, RDS), Resilience4j, Google Gemini API.
- **Measured Impact:** ~700 hours of manual work removed in 4 months — 2,800+ credit applications whose document validation took ~15 minutes each now complete in seconds, via an AI-assisted document analysis pipeline wired into the credit flow.
- **Financial Precision:** custom debt-evolution engine built entirely on `BigDecimal` with a Newton-Raphson solver for daily-rate conversion, versioned so a statement generated today stays reproducible later — `Math.pow(double, double)` accumulates cent-level error over 96+ installment loans.
- **Throughput:** scheduled reprocessing that re-runs 3,000+ debt statements in a 3-hour window — a volume that was never feasible manually.
- **Architecture:** Clean Architecture per module (domain → application → infrastructure), multi-tenant isolation, role-based access control, full operation audit logging, and resilient outbound integrations (circuit breaker + bulkhead, async outbox with reconciliation).
- **Decisions on record:** architecture decisions documented as ADRs — including the deliberate choice *not* to scale horizontally, backed by measured load.
</details>

---

### 🏢 RH System (Enterprise Onboarding API)
An open-source employee onboarding platform featuring stateless JWT authentication, complete audit logging, and automatic document generation (PDF). Built as a showcase of clean architecture, SOLID principles, and enterprise-grade security.

<details>
  <summary><strong>📌 View Full Project Details</strong></summary>

- **Tech Stack:** Java, Spring Boot, Spring Security, SQL Server, Docker  
- **Enterprise Security:** Role-Based Access Control (RBAC) and BCrypt encryption.  
- **Document Automation:** Automated PDF generation for employee responsibility terms using Apache POI.  
- **Clean Architecture:** Layered design with DTOs, custom Bean Validations, and repository pattern.  
- **Testing & Docs:** Unit testing with JUnit/Mockito and interactive Swagger/OpenAPI UI.  

👉 **Repository:** [github.com/git-lucasoliveira/onboarding-manager](https://github.com/git-lucasoliveira/onboarding-manager)
</details>

---

### 💸 Money Transfer API (Financial Transaction MVP)
A robust RESTful API built to simulate financial transactions, focusing on data consistency, enterprise-grade validations, and strict business rules. Developed with a strong emphasis on test-driven quality and layered architecture.

<details>
  <summary><strong>📌 View Full Project Details</strong></summary>

- **Tech Stack:** Java 21, Spring Boot 3, PostgreSQL, Hibernate / Spring Data JPA.
- **Data Consistency:** 100% usage of `BigDecimal` for financial operations to prevent precision loss, alongside strict database constraints to ensure data integrity.
- **Quality Assurance:** Comprehensive unit testing using JUnit 5 and Mockito to simulate database behaviors and rigorously validate business logic (e.g., insufficient funds, data conflicts).
- **Architecture & Resilience:** Classic MVC Layered Architecture integrated with global exception handling (`@RestControllerAdvice`) to provide resilient and user-friendly API responses.

👉 **Repository:** [github.com/git-lucasoliveira/money-transfer-api](https://github.com/git-lucasoliveira/money-transfer-api)
</details>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/git-lucasoliveira/git-lucasoliveira/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/git-lucasoliveira/git-lucasoliveira/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/git-lucasoliveira/git-lucasoliveira/output/pacman-contribution-graph.svg">
</picture>

---

<h2>📫 Contact & Connect</h2>
<p align="center">
  <a href="https://www.linkedin.com/in/lucasoliveiraamorim/" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" height="50"/>
  </a>
  <a href="mailto:lucas.oliveiraa120505@gmail.com" target="_blank">
    <img src="https://skillicons.dev/icons?i=gmail" height="50"/>
  </a>
</p>

---
