<!-- ================= HEADER ================= -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=34&duration=2500&pause=800&color=00F7FF&center=true&vCenter=true&width=900&lines=Samar+Abbas;Backend+Systems+Engineer;Distributed+Systems+%7C+Web3+%7C+FinTech" />
</p>

<p align="center">
  <b>Backend engineer building scalable, high-performance distributed systems</b><br/>
  Focused on backend infrastructure, event-driven systems, and real-time data pipelines.
</p>

---

<!-- ================= BADGES ================= -->

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Distributed_Systems-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-High_Performance_Systems-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-FinTech-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Blockchain-blue?style=for-the-badge" />
</p>

---

## ⚙️ Engineering Focus

I build backend systems where **scalability, consistency, and failure handling are critical requirements**.

My work focuses on:

* Designing **high-throughput event-driven systems** (Kafka, async pipelines)
* Building **idempotent, retry-safe workflows** under distributed conditions
* Developing **real-time data pipelines and streaming systems**
* Ensuring **system reliability, observability, and performance under load**

---

## ⚡ System Design Principles

* Systems must remain **deterministic under retries and replays**
* Execution must be **consistent under concurrent input**
* Failures must be **observable, traceable, and recoverable**
* External systems are treated as **eventually consistent and unreliable**

---

## 🏗️ Selected Systems

---

### 🔹 Perpetual DEX Matching Engine (Real-Time Trading System)

**Low-latency order execution engine with deterministic matching**

* Built **price-time priority (FIFO) matching engine** with support for partial fills and cancellations
* Designed **order book (price-level architecture)** enabling **O(1) best bid/ask access**
* Implemented **deterministic execution** using sequence IDs for replayability
* Developed **real-time streaming (WebSockets)** for order book and trade updates
* Achieved **sub-millisecond processing latency** in local benchmarks

**Key Engineering Work**

* Matching logic under concurrent order flow
* Low-latency system design and execution guarantees
* Real-time state propagation and consistency

→ https://github.com/samar-syd7/dex-matching-engine

---

### 🔹 Crypto Transaction Monitoring System

**Event-driven financial processing and risk evaluation**

* Built **Kafka-based ingestion pipelines** for high-volume transaction streams
* Implemented **risk scoring engine** for anomaly detection and compliance workflows
* Designed **audit logging architecture** ensuring traceability across distributed systems

→ https://github.com/samar-syd7/crypto-transaction-monitoring-api

---

### 🔹 Real-World Asset Tokenization Platform

**On-chain asset lifecycle with off-chain consistency guarantees**

* Designed and deployed **ERC-721 smart contracts**
* Built backend services for **asset lifecycle (mint → transfer → verify)**
* Implemented **event-driven synchronization** using blockchain logs
* Handled **on-chain/off-chain consistency** under asynchronous execution

→ https://github.com/samar-syd7/asset-tokenization-platform

---

## 🧭 System Flow (Trading System)

```text
Incoming Orders
     ↓
Matching Engine (Price-Time Priority)
     ↓
Order Book Update
     ↓
Trade Execution
     ↓
Event Stream (WebSockets)
     ↓
Client State Sync
```

---

## 🧩 Systems & Architecture Patterns

```text
Event-Driven Architecture   | Kafka / Streams
Matching Engine Design      | Order Book + Execution Logic
Idempotent Processing       | Replay Safety
Concurrency Control         | Deterministic Execution
Real-Time Systems           | WebSockets / Streaming
Observability               | Metrics + Monitoring
```

---

## 🛠️ Tech Stack

```text
Languages → Go · TypeScript · Python · Java  

Backend Systems → Node.js · Fastify · Django · Spring Boot  

Distributed Systems → Kafka · Redis · Event-driven architectures  

Data → PostgreSQL · Relational modeling  

Infrastructure → Docker · Containerized services · CI/CD  

Observability → Prometheus · Metrics-based monitoring  

Blockchain → Solidity · Ethereum · Web3.js  
```

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=samar-syd7&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" height="150"/>
  <img src="https://streak-stats.demolab.com/?user=samar-syd7&theme=tokyonight&hide_border=true" height="150"/>
</p>

---

## 🎯 Current Work

* Building **high-performance backend systems and real-time pipelines**
* Designing **event-driven architectures using Kafka and distributed systems patterns**
* Developing **low-latency execution and data processing systems**
* Improving **system reliability, observability, and scalability under load**

---

## 📫 Availability

* Open to backend / distributed systems roles
* Focus: Infrastructure · Platform · Trading Systems

---

## ⚡ Engineering Principle

> Systems must remain deterministic, observable, and correct under failure.
