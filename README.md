<div align="center">

# 💫 Lê Văn Nguyên (NguyenLee15)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Hi+there%2C+I'm+L%C3%AA+V%C4%83n+Nguy%C3%AAn+%F0%9F%91%8B;Full-Stack+%26+Backend+Software+Engineer+%F0%9F%9A%80;.NET+8+%E2%80%A2+Spring+Boot+3+%E2%80%A2+NestJS+%E2%80%A2+Next.js+16;Distributed+Systems+%E2%80%A2+Clean+Architecture+%E2%80%A2+AI+Integration;Building+High-Concurrency+%26+Mission-Critical+Platforms+%E2%9A%A1" alt="Typing SVG" />

<p align="center">
  <a href="mailto:nguyen2004hd@gmail.com"><img src="https://img.shields.io/badge/Email-nguyen2004hd%40gmail.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/></a>
  <a href="https://github.com/NguyenLee15"><img src="https://img.shields.io/badge/GitHub-NguyenLee15-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/></a>
  <img src="https://img.shields.io/badge/Location-Hanoi%2C%20Vietnam-22C55E?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location Badge"/>
  <img src="https://img.shields.io/badge/Status-Open_to_Opportunities-blueviolet?style=for-the-badge&logo=target&logoColor=white" alt="Status Badge"/>
</p>

---

<p align="center">
  <b>Software Engineer</b> with deep focus on <b>Backend Architecture</b>, <b>High-Concurrency Systems</b>, and <b>Distributed Infrastructure</b>.<br/>
  Passionate about implementing <b>Clean Architecture / DDD</b>, eliminating data race conditions, engineering resilient asynchronous workflows, and building cross-platform web & mobile applications.
</p>

</div>

---

### 🏛️ Core Engineering Principles

```text
  [ Client Tier ] ───► [ Clean Architecture / CQRS ] ───► [ Multi-Tier Concurrency ]
  React 19 / Next.js     MediatR / Domain Invariants       Redis RedLock + Optimistic Locking
          │                                                               │
          ▼                                                               ▼
  [ Event-Driven Bus ] ◄─────────────────────────────────── [ Atomic Persistence ]
  RabbitMQ / Outbox Pattern                                SQL Server / Postgres / EF Core
```

- **Zero Data Corruption**: Multi-tier concurrency control (Redis Distributed Lock + Optimistic/Pessimistic DB Locks) ensuring 100% seat/inventory consistency under peak traffic.
- **Resilient Message Delivery**: Transactional Outbox Pattern combined with RabbitMQ & BullMQ message brokers for guaranteed at-least-once asynchronous event delivery.
- **Enterprise-Grade Security**: Asymmetric RSA token rotation (PKCS#8), HTTP-only rotating refresh tokens, HMAC-SHA256/512 IPN webhook verification, and zero hardcoded secrets.
- **Clean Layered Separation**: Strict adherence to Clean Architecture, Domain-Driven Design (DDD), and SOLID principles for maintainable, easily auditable codebases.

---

### 🚀 Featured Architectural Projects

<table>
  <!-- Row 1: TickeX & ZUP Marketplace -->
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🎟️ <a href="https://github.com/NguyenLee15/TiketX">TickeX — Real-Time Event Ticketing</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
        <img src="https://img.shields.io/badge/C%23_12-239120?style=flat-square&logo=csharp&logoColor=white"/>
        <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/Redis_Lock-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white"/>
        <img src="https://img.shields.io/badge/SignalR-0078D7?style=flat-square&logo=signal&logoColor=white"/>
        <img src="https://img.shields.io/badge/PayOS_VietQR-0052CC?style=flat-square&logo=cashapp&logoColor=white"/>
      </p>
      <ul>
        <li><b>High-Concurrency Event & Ticketing Platform</b> engineered under Clean Architecture and CQRS (MediatR).</li>
        <li><b>Zero Overselling Concurrency Engine</b>: Multi-tier protection fusing <b>Redis Distributed Lock (RedLock)</b> and <b>EF Core Optimistic Concurrency</b> to eradicate seat race conditions during flash ticket drops.</li>
        <li><b>Guaranteed Delivery via Outbox Pattern</b>: Decoupled transactional event publishing via <b>RabbitMQ (MassTransit)</b> ensuring zero partial state failures during checkout and ticket issuance.</li>
        <li><b>Real-Time Seat Matrix Synchronization</b>: Instant visual seat reservation state broadcasted across all concurrent browser sessions using <b>SignalR WebSockets</b>.</li>
        <li><b>Enterprise Auth & Security</b>: Asymmetric RSA PKCS#8 key rotation, HTTP-Only cookies, HMAC-SHA256 signature verification, and background reconciliation with <b>Hangfire</b>.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🏠 <a href="https://github.com/NguyenLee15/ZUP_Service-Marketplace">ZUP Service Marketplace</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=next.js&logoColor=white"/>
        <img src="https://img.shields.io/badge/Expo_SDK_54-000020?style=flat-square&logo=expo&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Gemini_2.5_Flash-8E75C2?style=flat-square&logo=googlegemini&logoColor=white"/>
        <img src="https://img.shields.io/badge/VNPay-ED1C24?style=flat-square&logo=contactlesspayment&logoColor=white"/>
      </p>
      <ul>
        <li><b>Enterprise On-Demand Service Platform</b> with real-time bidding, GPS radius discovery, and a robust 6-state booking lifecycle.</li>
        <li><b>Financial Integrity & Anti-Race Condition</b>: Provider deposit wallet, atomic transactions via Prisma, custom VNPay HMAC-SHA512 IPN payment gateway.</li>
        <li><b>AI & Semantic Vector Search</b>: Google Gemini 2.5 Flash embeddings with <b>pgvector</b> for intelligent service discovery and automated dispute mediation.</li>
        <li><b>Cross-Platform Parity</b>: Next.js 16 Web Portal (Customer & Admin) + Expo React Native App (SDK 54) for service technicians.</li>
      </ul>
    </td>
  </tr>

  <!-- Row 2: EduPortal & Flower Recognition -->
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🎓 <a href="https://github.com/NguyenLee15/student-management">EduPortal — Academic ERP</a></h3>
      <p align="center">
        <a href="https://lee-eduportal.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-lee--eduportal.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white"/></a>
        <img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
        <img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
        <img src="https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/MySQL_8.0-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
        <img src="https://img.shields.io/badge/PayOS_VietQR-0052CC?style=flat-square&logo=cashapp&logoColor=white"/>
      </p>
      <ul>
        <li><b>Enterprise University Academic & Student Information ERP</b> with 3 decoupled portals for <b>Admins</b>, <b>Lecturers</b>, and <b>Students</b>.</li>
        <li><b>National Educational Compliance</b>: Full compliance with Vietnamese MOET regulations (<b>Thông tư 08/2021/TT-BGDĐT</b>) for 10-point, 4-point GPA, and letter grading.</li>
        <li><b>Registration Race Condition Elimination</b>: Pessimistic database locking preventing course over-enrollment during peak registration spikes.</li>
        <li><b>Automated Tuition & VietQR</b>: Real-time dynamic QR generation and idempotent webhook reconciliation via PayOS.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🌸 <a href="https://github.com/NguyenLee15/Flower-recognition">Flower Recognition AI</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img src="https://img.shields.io/badge/Computer_Vision-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
        <img src="https://img.shields.io/badge/Deep_Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      </p>
      <ul>
        <li><b>Intelligent Botanical Classification Engine</b> leveraging Convolutional Neural Networks (CNN) and Transfer Learning.</li>
        <li><b>Automated Image Preprocessing & Feature Extraction</b>: High-accuracy plant species recognition from real-world, noisy mobile photo inputs.</li>
        <li><b>Lightweight Inference Pipeline</b>: Served via optimized REST endpoints for real-time mobile and web integration.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Technical Arsenal & Technology Matrix

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Backend & Microservices** | <img src="https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/> <img src="https://img.shields.io/badge/C%23_12-239120?style=for-the-badge&logo=csharp&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"/> <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> |
| **Architecture & Patterns** | <img src="https://img.shields.io/badge/Clean_Architecture-00599C?style=for-the-badge&logoColor=white"/> <img src="https://img.shields.io/badge/CQRS_%26_MediatR-4A154B?style=for-the-badge&logoColor=white"/> <img src="https://img.shields.io/badge/Domain--Driven_Design-181717?style=for-the-badge&logoColor=white"/> <img src="https://img.shields.io/badge/Outbox_Pattern-F58025?style=for-the-badge&logoColor=white"/> <img src="https://img.shields.io/badge/RESTful_APIs-22C55E?style=for-the-badge&logoColor=white"/> |
| **Distributed Systems & Queues**| <img src="https://img.shields.io/badge/Redis_Distributed_Lock-DC382D?style=for-the-badge&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/RabbitMQ_MassTransit-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/> <img src="https://img.shields.io/badge/BullMQ-FF4438?style=for-the-badge&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/SignalR-0078D7?style=for-the-badge&logo=signal&logoColor=white"/> <img src="https://img.shields.io/badge/Hangfire-009688?style=for-the-badge&logoColor=white"/> |
| **Frontend & Mobile** | <img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=next.js&logoColor=white"/> <img src="https://img.shields.io/badge/React_19%2F18-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/Expo_SDK_54-000020?style=for-the-badge&logo=expo&logoColor=white"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white"/> <img src="https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logoColor=white"/> |
| **Databases & Vector Store** | <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL_8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/EF_Core_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/> <img src="https://img.shields.io/badge/Prisma_ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/> |
| **Cloud, DevOps & Testing** | <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/> <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/> <img src="https://img.shields.io/badge/xUnit-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/> <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/> |
| **AI & Financial Gateways** | <img src="https://img.shields.io/badge/Google_Gemini-8E75C2?style=for-the-badge&logo=googlegemini&logoColor=white"/> <img src="https://img.shields.io/badge/PayOS_VietQR-0052CC?style=for-the-badge&logo=cashapp&logoColor=white"/> <img src="https://img.shields.io/badge/VNPay_Gateway-ED1C24?style=for-the-badge&logo=contactlesspayment&logoColor=white"/> <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white"/> |

</div>

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <table border="0">
    <tr>
      <td width="50%">
        <img src="https://github-stats-extended.vercel.app/api?username=NguyenLee15&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=38bdf8&text_color=e2e8f0" alt="GitHub Stats" width="100%"/>
      </td>
      <td width="50%">
        <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=NguyenLee15&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=e2e8f0" alt="Top Languages" width="100%"/>
      </td>
    </tr>
  </table>

  <img src="https://streak-stats.demolab.com/?user=NguyenLee15&theme=tokyonight&hide_border=true&background=0d1117&ring=38bdf8&fire=38bdf8&currStreakLabel=38bdf8&sideNums=e2e8f0&sideLabels=94a3b8&dates=94a3b8" alt="Streak Stats" width="95%"/>
</div>

---

### 🐍 Contribution Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NguyenLee15/NguyenLee15/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NguyenLee15/NguyenLee15/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/NguyenLee15/NguyenLee15/output/github-contribution-grid-snake.svg">
  </picture>
</div>

---

<div align="center">
  <b>⭐ Open to Software Engineering, Backend & Full-Stack Opportunities ⭐</b><br/>
  <i>Let's connect and build scalable, high-impact systems together.</i><br/><br/>
  <a href="mailto:nguyen2004hd@gmail.com"><img src="https://img.shields.io/badge/Contact_Me-nguyen2004hd%40gmail.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white" alt="Contact Me"/></a>
</div>

