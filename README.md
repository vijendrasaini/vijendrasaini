# Hi, I'm Vijendra Saini 👋

<p align="left">
  <strong>Backend Software Engineer (SDE 2)</strong> [Promoted from SDE 1 @ ANAROCK] specializing in <strong>Java 21</strong>, <strong>Spring Boot 3</strong>, <strong>Distributed Systems</strong>, and <strong>Event-Driven Architecture (Apache Kafka)</strong>.
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/ervijendrasaini/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:vijendrasaini0101@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Location-Bengaluru%2C%20India-blue?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location"/>
</p>

---

### 🚀 About Me

Backend Software Engineer with **4+ years of production experience** designing, building, and operating RESTful APIs, automated batch data pipelines, and distributed event-driven systems. Promoted from SDE 1 to SDE 2 at **ANAROCK**. Passionate about solving complex race conditions, maintaining strict mathematical invariants in financial ledgers, and building resilient event-driven microservices.

- 🏢 **Current Role**: Software Development Engineer 2 (SDE 2) @ ANAROCK [Promoted from SDE 1]
- 🛡️ **Production Reliability**: **Zero P0 outages** over 2+ years of production platform operations (DLF luxury communities with 99.9% availability)
- 🧠 **Algorithmic Foundation**: Strong foundation in **Data Structures & Algorithms (DSA)** and Low-Level Design (LLD)
- 🏆 **Academic Honors**: **AIR 768** in IIT JAM Physics | **INSPIRE Scholar** (Top 1% nationwide by DST, Govt. of India)

---

### ⚡ Flagship Distributed Systems

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/vijendrasaini/flashledger">FlashLedger</a></h3>
      <p><em>Distributed High-Throughput Booking & Double-Entry Financial Ledger Engine</em></p>
      <div>
        <img src="https://img.shields.io/badge/Java-21-orange.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Spring%20Boot-3.4.5-brightgreen.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Redis-Redisson-red.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/MySQL-9.0-blue.svg?style=flat-square"/>
      </div>
      <ul>
        <li><strong>Distributed Concurrency</strong>: Prevents inventory overselling race conditions under concurrent load using <strong>Redisson Fair Locks</strong> with watchdog auto-renewal (0 oversold units).</li>
        <li><strong>Double-Entry Ledger</strong>: Enforces strict mathematical balance parity (<code>&sum; Debits == &sum; Credits</code>) with zero balance drift across atomic operations.</li>
        <li><strong>Idempotency Engine</strong>: Built a distributed <code>Idempotency-Key</code> engine in Redis serving cached booking responses in <strong>under 4ms</strong>.</li>
        <li><strong>Verification</strong>: Covered by <strong>11/11 automated integration tests</strong> simulating concurrent race conditions.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🌊 <a href="https://github.com/vijendrasaini/pulsestream">PulseStream</a></h3>
      <p><em>Distributed Event-Driven Microservices Platform with Transactional Outbox & Sagas</em></p>
      <div>
        <img src="https://img.shields.io/badge/Java-21-orange.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Spring%20Boot-3.4.3-brightgreen.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Apache%20Kafka-4.2.2%20KRaft-red.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Testcontainers-1.20.4-black.svg?style=flat-square"/>
      </div>
      <ul>
        <li><strong>Transactional Outbox</strong>: Prevents dual-write inconsistencies between MySQL and Kafka with an automated polling relay (<code>acks=all</code>).</li>
        <li><strong>Idempotent Consumers</strong>: Inbox pattern deduplication guarantees zero duplicate debits during network retries or consumer group rebalances.</li>
        <li><strong>Non-Blocking DLQ</strong>: Isolates poison pills via <code>@RetryableTopic</code> with exponential backoff and <code>.DLT</code> error routing.</li>
        <li><strong>Choreographed Sagas</strong>: Coordinates compensating refunds on inventory failure; resolves concurrent lost update anomalies using <strong>MySQL row-level pessimistic locking</strong>.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🏢 <a href="https://github.com/vijendrasaini/estateflow-backend">EstateFlow Backend</a></h3>
      <p><em>Enterprise High-Scale Residential & Multi-Tenant Community Management Platform</em></p>
      <div>
        <img src="https://img.shields.io/badge/Java-17-orange.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Spring%20Boot-3.3-brightgreen.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Spring%20Security-6-green.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/JWT-Stateless-blue.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Flyway-Migrations-red.svg?style=flat-square"/>
      </div>
      <ul>
        <li>Enterprise community platform engineered for high-density multi-tenant residential properties serving thousands of residential units.</li>
        <li>Engineered decoupled services with stateless HMAC-SHA256 JWT auth, role-based access control (RBAC), and multi-tenant resident portals.</li>
        <li>Implemented pluggable Strategy pattern CRM Gateway routing via Spring <code>RestClient</code> with dynamic mock/Salesforce switching.</li>
        <li>Optimized MySQL relational schemas and implemented Redis caching to eliminate database query bottlenecks.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Core Technical Skills

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | Java 21 LTS (Streams, Multithreading, Concurrency, OOP), PHP, SQL (MySQL) |
| **Backend & Frameworks** | Spring Boot 3, Spring Core (IoC/DI), Spring Data JPA/Hibernate, Spring Security 6, Spring AOP, RESTful APIs, Laravel |
| **Distributed Systems & Messaging** | Apache Kafka 4.x (KRaft mode), Spring Kafka, Event-Driven Architecture (EDA), Transactional Outbox, Idempotent Consumers, Non-Blocking Retry/DLQ, Choreographed Sagas, Double-Entry Ledgers |
| **Databases & Caching** | MySQL 8/9 (Indexing, Transactions, Row-Level Locking), Redis (Redisson Fair Locks & Caching), HikariCP, Flyway Database Migrations |
| **Testing & Tools** | JUnit 5, Spring Boot Test, Testcontainers, Awaitility, Docker, Docker Compose, Git, GitHub, Maven, Postman |

---

### 📊 GitHub Activity & Statistics

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=vijendrasaini&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Vijendra's GitHub Stats" width="48%"/>
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=vijendrasaini&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" width="48%"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=vijendrasaini&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="97%"/>
</p>

---

<p align="center">
  <em>"Any fool can write code that a computer can understand. Good programmers write code that humans can understand." — Martin Fowler</em>
</p>
