<!-- ================= HEADER ================= -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=34&duration=2500&pause=800&color=00F7FF&center=true&vCenter=true&width=900&lines=Samar+Abbas;Backend+Systems+Engineer;HealthTech+%7C+Blockchain+%7C+FinTech" />
</p>

<p align="center">
  <b>Backend engineer building reliability-critical distributed systems</b><br/>
  Focused on healthcare interoperability, financial infrastructure, and blockchain-based systems.
</p>

---

<!-- ================= BADGES ================= -->

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Distributed_Systems-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-HealthTech-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Blockchain-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-FinTech-purple?style=for-the-badge" />
</p>

---

## ⚙️ Engineering Focus

I build backend systems where **correctness, traceability, and failure handling are core requirements**.

My work involves:

- Designing **event-driven pipelines** for real-world data systems  
- Building **idempotent and retry-safe workflows** using queues  
- Handling **data consistency across distributed services**  
- Ensuring **observability and auditability** in system behavior  

---

## 🧠 Domain Expertise

### 🏥 HealthTech (HL7 · FHIR · DICOM)
- HL7 message parsing and transformation pipelines  
- DICOM workflows for PACS systems and imaging data  
- FHIR-based resource modeling and API integration  
- Data normalization across heterogeneous healthcare systems  

---

### 🔗 Blockchain / Web3
- Transaction monitoring and classification systems  
- Deterministic processing of on-chain data  
- Risk scoring pipelines for financial compliance  
- Bridging on-chain events with backend services  

---

### 💰 FinTech Infrastructure
- Asynchronous financial data pipelines  
- Consistency and reconciliation workflows  
- Queue-based processing for high-integrity systems  
- Backend systems designed for traceability and compliance  

---

## 🏗️ Selected Systems

### 🔹 MedLedger
**Blockchain-backed healthcare data integrity system**

- Designed pipeline for **HL7 → normalized schema → FHIR resources**
- Anchored critical data hashes onto blockchain for **tamper-evidence**
- Built backend services using **FastAPI / Django**
- Containerized services with **Docker**
- Designed for **auditability and cross-system consistency**

**Key Engineering Work**
- Data normalization across inconsistent HL7 messages  
- Deterministic hashing for record verification  
- Handling partial/invalid healthcare data safely  

→ https://github.com/samar-syd7/medledger

---

### 🔹 Crypto Transaction Monitoring API
**Deterministic risk scoring and compliance backend**

- Built **event-driven transaction processing pipeline**
- Designed **rule-based scoring engine** for AML-style monitoring
- Processed transaction flows using **queue-based systems (Redis / Kafka)**
- Structured backend using **FastAPI / Spring Boot (modular services)**

**Key Engineering Work**
- Idempotent transaction evaluation (no duplicate scoring)  
- Traceable decision pipelines for compliance review  
- Handling asynchronous transaction ingestion  

→ https://github.com/samar-syd7/crypto-transaction-monitoring-api

---

### 🔹 Exchange Ops Automation Service
**Distributed job orchestration and execution system**

- Implemented **Celery-based distributed task execution**
- Built **retry-safe pipelines with backoff strategies**
- Used **Redis queues** for asynchronous processing
- Containerized worker + API services using **Docker**

**Key Engineering Work**
- Idempotent job execution (safe retries)  
- Failure recovery mechanisms for long-running tasks  
- Separation of orchestration vs execution layers  

→ https://github.com/samar-syd7/exchange-ops-automation-service

---

## 🧭 System Flow (Conceptual Architecture)

### HealthTech Pipeline (HL7 → FHIR → Blockchain)

```text
HL7 Messages
     ↓
Parsing & Validation Layer
     ↓
Normalization Engine
     ↓
FHIR Resource Mapping
     ↓
Hashing Layer (Deterministic)
     ↓
Blockchain Anchoring
     ↓
API Layer (Access / Query)

```

### FinTech / Blockchain Pipeline (Transaction Monitoring)

```text
Incoming Transactions
     ↓
Queue / Stream (Kafka / Redis)
     ↓
Processing Workers
     ↓
Risk Scoring Engine
     ↓
Decision Output (Flag / Score)
     ↓
Storage (PostgreSQL)
     ↓
Audit Logs / Traceability

```

### Distributed Job Execution System

```text
Client Request
     ↓
API Layer
     ↓
Task Queue (Redis)
     ↓
Worker Nodes (Celery)
     ↓
Execution + Retry Logic
     ↓
Result Storage
     ↓
Monitoring (Prometheus Metrics)

```

---

## 🧩 Systems & Architecture Patterns

```text
Event-Driven Architecture   | Kafka / Redis Queues
Idempotent Processing       | Retry / Backoff Handling
Distributed Task Execution  | Celery Workers
Data Consistency Models     | Reconciliation Pipelines
Schema Validation           | HL7 / FHIR Processing
Observability               | Logging, Traceability
````

---

## 🛠️ Tech Stack

```text
Languages → Python · Go · Java · TypeScript

Backend Systems → Django · FastAPI · Spring Boot

Distributed Systems & Messaging → Kafka · Redis · Celery · Event-driven architectures

Data & Storage → PostgreSQL · Relational data modeling

Infrastructure & DevOps → Docker · Containerized services · CI/CD workflows

Observability & Monitoring → Prometheus · Metrics-based monitoring · System visibility

APIs & Integration → REST APIs · HL7 · FHIR · DICOM
```

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=samar-syd7&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" height="150"/>
  <img src="https://streak-stats.demolab.com/?user=samar-syd7&theme=tokyonight&hide_border=true" height="150"/>
</p>

---

## 🎯 Current Work

* Building **healthcare interoperability pipelines (HL7 → FHIR)**
* Designing **blockchain-integrated backend systems**
* Developing **event-driven financial processing systems**
* Improving **reliability and observability in distributed systems**

---

## 📫 Availability

* Open to backend / distributed systems roles
* Focus: Infrastructure · Platform · Systems Engineering

---

## ⚡ Engineering Principle

> Systems must remain deterministic, observable, and consistent under failure.
