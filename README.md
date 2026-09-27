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

- 🏢 **Current Role**: Software Development Engineer 2 (SDE 2) at **ANAROCK**
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
        <img src="https://img.shields.io/badge/Spring%20Boot-3.4-brightgreen.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Redis-Redisson-red.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/MySQL-8.0-blue.svg?style=flat-square"/>
      </div>
      <ul>
        <li><strong>Distributed Concurrency</strong>: Eliminates overselling race conditions under high contention using <strong>Redisson Distributed Fair Locks</strong> with watchdog auto-renewal.</li>
        <li><strong>Double-Entry Ledger</strong>: Enforces strict mathematical balance invariants (<code>&sum; Debits == &sum; Credits</code>) with zero balance drift across atomic operations.</li>
        <li><strong>Idempotency Engine</strong>: Built a distributed <code>Idempotency-Key</code> engine serving cached booking responses in <strong>~4ms</strong>.</li>
        <li><strong>Verification</strong>: Covered by <strong>14/14 automated integration tests</strong> simulating concurrent race conditions.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🌊 <a href="https://github.com/vijendrasaini/pulsestream">PulseStream</a></h3>
      <p><em>Distributed Event-Driven Microservices Platform with Transactional Outbox & Sagas</em></p>
      <div>
        <img src="https://img.shields.io/badge/Java-21-orange.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Apache%20Kafka-3.7%20KRaft-red.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Spring%20Kafka-3.3-green.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Saga-Choreography-purple.svg?style=flat-square"/>
      </div>
      <ul>
        <li><strong>Transactional Outbox</strong>: Eliminates dual-write vulnerabilities between MySQL and Kafka; guarantees at-least-once delivery with zero phantom events.</li>
        <li><strong>Idempotent Consumers</strong>: Deduplicates event streams inside transactional boundaries, guaranteeing zero double-deductions.</li>
        <li><strong>Non-Blocking DLQ</strong>: Isolates poison pills and handles transient failures via <code>@RetryableTopic</code> with exponential backoff without stalling main partitions.</li>
        <li><strong>Choreographed Sagas</strong>: Coordinates distributed rollbacks and compensating refunds across isolated databases.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🏢 <a href="https://github.com/vijendrasaini/estateflow-backend">EstateFlow Backend</a></h3>
      <p><em>Enterprise High-Scale Residential & Community Management Platform (ANAROCK Platform Clean-Room Port)</em></p>
      <div>
        <img src="https://img.shields.io/badge/Java-17-orange.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Spring%20Boot-3.3-brightgreen.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Spring%20Security-6-green.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/JWT-Stateless-blue.svg?style=flat-square"/>
        <img src="https://img.shields.io/badge/Flyway-Migrations-red.svg?style=flat-square"/>
      </div>
      <ul>
        <li>Clean-room architectural port of high-volume UAE community platforms (Samana & Taraf) serving thousands of residential units.</li>
        <li>Engineered decoupled microservices with stateless HMAC-SHA256 JWT auth, role-based access control (RBAC), and multi-tenant resident portals.</li>
        <li>Optimized MySQL relational schemas and implemented Redis cache-aside layers to eliminate query bottlenecks.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Core Technical Skills

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | Java 21 LTS, SQL, Bash |
| **Backend & Frameworks** | Spring Boot 3, Spring Data JPA, Spring Security 6, Spring Kafka, Hibernate |
| **Distributed Systems & Caching** | Apache Kafka (KRaft mode), Redis (Redisson Fair Locks), HikariCP Connection Pool |
| **Databases & Migrations** | MySQL 8, PostgreSQL, Flyway Database Migrations |
| **Distributed Architecture** | Event-Driven Architecture (EDA), Transactional Outbox Pattern, Choreographed Sagas, Idempotent Consumers, Double-Entry Accounting |
| **Testing & Tooling** | JUnit 5, Mockito, MockMvc, Testcontainers, Docker, Docker Compose, Git, Postman |

---

### 📊 GitHub Activity & Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vijendrasaini&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Vijendra's GitHub Stats" width="48%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vijendrasaini&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" width="48%"/>
</p>

---

<p align="center">
  <em>"Any fool can write code that a computer can understand. Good programmers write code that humans can understand." — Martin Fowler</em>
</p>
