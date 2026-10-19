# 🚀 Shibil Das | Lead Software Engineer

<p align="left">
  <a href="https://linkedin.com/in/shibil-dev/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://medium.com/@shibildas"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="https://github.com/shibildas/RelayQueue"><img src="https://img.shields.io/badge/Featured_Project-RelayQueue-0d9488?style=for-the-badge&logo=zap&logoColor=white" alt="RelayQueue" /></a>
  <a href="https://leetcode.com/shibildev"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
  <img src="https://komarev.com/ghpvc/?username=shibildas&style=for-the-badge&color=0d9488" alt="Profile Views" />
</p>

---

## 👨‍💻 Executive Summary

Results-driven **Lead Software Engineer** with **3+ years of full-stack engineering experience** and proven technical leadership across high-scale distributed systems. Progressed from Junior to Lead Engineer at **Packapeer Academy Private Limited** (Bengaluru), architecting event-driven microservices, high-throughput payment rails, and automated operations engines.

- 👥 **Leadership & Governance:** Direct people management for a **21-member cross-functional engineering team**, driving technical mentorship, Liquibase database standards, and AWS cloud governance.
- 💳 **Scale & Financial Reliability:** Architected automated payment processing with **HDFC SmartGateway**, processing **₹1–3 Cr in monthly transactions** with zero payment leakage, and automated **~1,000 monthly facilitation tax invoices**.
- ⚡ **High Concurrency:** Owns architecture across backend microservices and **KrakenD API Gateway** supporting **2,500–2,800 active daily students/staff** and **10,000+ daily web visitors**.
- 🤖 **Velocity Acceleration:** Championed **AI prompt-driven development** (Cursor, LLMs), **cutting development lead time by 35%** and enabling **2x higher deployment frequency**.

---

## 📊 Impact at a Glance

| Metric | Achievement | Impact |
|:---|:---|:---|
| **21 Engineers** | People Management & Mentorship | Architecture reviews, RFCs, CI/CD, and AWS governance |
| **₹1–3 Cr / mo** | Payment Processing Volume | Zero financial leakage via HDFC SmartGateway & auto-invoicing |
| **10,000+** | Daily Active Web Visitors | 2,800+ concurrent users on KrakenD API Gateway |
| **35% Faster** | Lead Time Reduction | AI prompt-driven workflows, eliminating boilerplate |
| **Instantaneous** | Admission Verification | Reduced manual student onboarding from **2 days to real-time** |

---

## 📝 Published Technical Papers & System Design Guides

I write deep-dive architectural essays on Medium covering distributed systems, network communication protocols, and microservices design patterns:

- 🧵 **[Concurrency Made Easy: A System Design Guide](https://medium.com/@shibildas/concurrency-made-easy-a-system-design-guide-93c7b02f88b9)**  
  *Deep dive into multithreading models, race conditions, atomic operations, deadlock avoidance, optimistic vs. pessimistic locking, and patterns for handling concurrent spikes without throughput degradation.*

- 🌐 **[The Internet’s Secret Languages: Exploring Communication Protocols](https://medium.com/@shibildas/the-internets-secret-languages-exploring-communication-protocols-c8caf80956e4)**  
  *An architectural journey comparing modern network protocols: stateless HTTP/REST, persistent duplex WebSockets, binary serialization in gRPC (HTTP/2), and enterprise message brokers (AMQP / MQTT).*

- 🚪 **[Streamlining Microservices with KrakenD: The Power of API Gateways for Modern Applications](https://medium.com/@shibildas/streamlining-microservices-with-krakend-the-power-of-api-gateways-for-modern-applications-159fe1d89e50)**  
  *Practical blueprint on utilizing KrakenD stateless API Gateways in enterprise production for endpoint aggregation, Backend-for-Frontend (BFF) decoupling, rate limiting, and failure isolation.*

👉 **[Follow my writing on Medium @shibildas](https://medium.com/@shibildas)**

---

## 🏗️ Featured Engineering Projects

### ⚡ [RelayQueue](https://github.com/shibildas/RelayQueue) &bull; *High-Throughput Event Relay & Webhook Gateway*
*Built with Next.js 15 App Router, TypeScript, Upstash Redis, and Tailwind CSS v4.*
- **Zero Data-Loss Delivery:** High-throughput webhook relay engine positioned between webhook producers and receiving consumer services.
- **Timing-Safe HMAC-SHA256:** Validates signatures with `crypto.timingSafeEqual` and a ±300s timestamp tolerance window to eliminate side-channel timing analysis and replay attacks.
- **Full Jitter Exponential Backoff:** Implements randomized full jitter ($Sleep = \text{rand}(0.5 \times \text{Base}, \min(\text{Cap}, \text{Base} \times 2^{\text{attempt}-1}))$) to eradicate thundering herd retry storms.
- **DLQ & 1-Click Replay:** Isolates exhausted retries with complete audit logs and enables atomic 1-click re-injection.
- **Interactive Developer Cockpit:** Real-time metrics dashboard tracking SLA compliance, throughput, and p50/p95/p99 latency percentiles.

### 📬 Distributed AMQP Message Bus (Packapeer Production Core)
*Built with RabbitMQ (amqplib), TypeScript, Awilix IoC, PostgreSQL, and Docker.*
- Architected enterprise AMQP message pipelines utilizing RabbitMQ topic/direct exchanges with dedicated consumer workers.
- Orchestrates asynchronous payment state transitions, batch admission intakes, and task queues with automatic dead-letter routing and retry policies.

### 💳 Automated Payment & Invoicing Engine (HDFC SmartGateway)
*Built with Node.js, Express, PostgreSQL, and PDFKit.*
- Zero-defect financial reconciliation processing ₹1–3 Cr in monthly transactions.
- Automated generation of ~1,000 monthly digital facilitation tax invoices with automated verification.

---

## 💻 Technical Repertoire

<table align="center" width="100%">
  <tr>
    <td width="33%" valign="top">
      <h4>🏛️ Architecture & Systems</h4>
      <ul>
        <li>Microservices Architecture</li>
        <li>Event-Driven Architecture (EDA)</li>
        <li>KrakenD API Gateway</li>
        <li>System Design (HLD / LLD)</li>
        <li>Database Modeling & Caching</li>
        <li>Clean Architecture & DI (Awilix)</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>⚡ Messaging & Backend</h4>
      <ul>
        <li>RabbitMQ (AMQP)</li>
        <li>Redis Caching & Pub/Sub</li>
        <li>TypeScript / Node.js</li>
        <li>Express.js / REST APIs</li>
        <li>PostGraphile (GraphQL)</li>
        <li>WebSockets (Socket.IO)</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>🗄️ Databases & Cloud</h4>
      <ul>
        <li>PostgreSQL & Prisma ORM</li>
        <li>MongoDB</li>
        <li>Liquibase Database Migrations</li>
        <li>AWS (S3, Secrets Manager)</li>
        <li>Docker Containerization</li>
        <li>Prometheus & Winston</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📈 Activity & Coding Profiles

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shibildas&show_icons=true&theme=radical&hide_border=true&title_color=2dd4bf&icon_color=2dd4bf" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shibildas&layout=compact&theme=radical&hide_border=true&title_color=2dd4bf" height="165" alt="Top Languages" />
</div>

<div align="center" style="margin-top: 15px;">
  <a href="https://leetcode.com/shibildev">
    <img src="https://leetcard.jacoblin.cool/shibildev?ext=heatmap&theme=dark" alt="Shibil's LeetCode Profile" />
  </a>
</div>

---

## 📬 Contact & Connect

- 🌐 **Portfolio Website:** [shibildas.github.io](https://shibildas.github.io)
- 💼 **LinkedIn:** [linkedin.com/in/shibil-dev](https://www.linkedin.com/in/shibil-dev/)
- 📝 **Medium:** [medium.com/@shibildas](https://medium.com/@shibildas)
- ✉️ **Email:** [shibildas@gmail.com](mailto:shibildas@gmail.com)
- 📍 **Location:** Bengaluru, Karnataka, India
