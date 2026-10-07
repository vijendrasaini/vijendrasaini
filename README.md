# Hi, I'm Vijendra Saini 👋

<p align="left">
  <strong>Senior Backend Software Engineer (SDE 2)</strong> specializing in <strong>Java 21</strong>, <strong>Spring Boot 3</strong>, <strong>Distributed Systems</strong>, and <strong>Event-Driven Architecture (Apache Kafka)</strong>.
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/ervijendrasaini/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:vijendrasaini0101@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Location-Bengaluru%2C%20India-blue?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location"/>
</p>

---

### 🚀 About Me

Backend Software Engineer with **4+ years of production experience** engineering high-availability APIs, distributed backend systems, and automated data pipelines. Passionate about solving complex race conditions, maintaining strict mathematical invariants in financial ledgers, and building resilient event-driven systems that eliminate dual-write vulnerabilities.

- 🏢 **Current Role**: Software Development Engineer 2 (SDE 2) @ ANAROCK
- 🛡️ **Production Reliability**: **Zero P0 outages** over 2+ years of production platform operations
- 🧠 **Algorithmic Foundation**: **450+ Data Structures & Algorithms** problems solved
- 🏆 **Academic Honors**: **AIR 768** in IIT JAM Physics | **INSPIRE Fellow** (Top 1% nationwide by DST, Govt. of India)

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
        <li><strong>Distributed Concurrency</strong>: Eliminates overselling race conditions under concurrent load using <strong>Redisson Distributed Fair Locks</strong> with watchdog auto-renewal.</li>
        <li><strong>Double-Entry Ledger</strong>: Enforces strict mathematical balance invariants (<code>&sum; Debits == &sum; Credits</code>) with zero balance drift across atomic operations.</li>
        <li><strong>Idempotency Engine</strong>: Built a distributed <code>Idempotency-Key</code> engine serving cached booking responses in <strong>~4ms</strong>.</li>
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
        <li><strong>Transactional Outbox</strong>: Eliminates dual-write vulnerabilities between MySQL and Kafka with an asynchronous polling relay (<code>acks=all</code>).</li>
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
        <li>Engineered decoupled microservices with stateless HMAC-SHA256 JWT auth, role-based access control (RBAC), and multi-tenant resident portals.</li>
        <li>Implemented pluggable Strategy pattern CRM Gateway routing via Spring <code>RestClient</code> with dynamic mock/Salesforce switching.</li>
        <li>Optimized MySQL relational schemas and implemented Redis cache-aside layers to eliminate query bottlenecks.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Core Technical Skills

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | Java 21 LTS (OOP, Streams, Concurrency), PHP, SQL (MySQL) |
| **Backend & Frameworks** | Spring Boot 3, Spring Core (IoC/DI), Spring Data JPA, Spring Security 6, Spring Kafka, Hibernate, RESTful APIs |
| **Distributed Systems & Caching** | Apache Kafka 4.x (KRaft mode), Redis (Redisson Fair Locks & Caching), HikariCP Connection Pool |
| **Databases & Migrations** | MySQL 8/9, Flyway Database Migrations |
| **Distributed Architecture** | Event-Driven Architecture (EDA), Transactional Outbox Pattern, Choreographed Sagas, Idempotent Consumers (Inbox), Double-Entry Accounting, BFF, Stateless JWT |
| **Testing & Tooling** | JUnit 5, Mockito, MockMvc, Testcontainers, Docker, Docker Compose, Git, Postman, Maven |

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
