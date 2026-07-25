<h1 align="center">Hi 👋, I'm Mohan Krishna Gudumala</h1>
<h3 align="center">
Software Engineer @ Stryv.ai | Java/Python Backend + React.js | Distributed Systems & Microservices
</h3>

<img align="right" alt="coding" width="400" src="https://github.com/user-attachments/assets/a8167fd8-7025-42b8-911c-c38b765a2027">

<p align="center">
  <i>Open to Backend Engineering / Full Stack SDE roles — Distributed Systems, Microservices, API Design.</i>
</p>

---

### 👨‍💻 About Me

I build backend systems that don't fall over under load.

- 💼 Software Engineer at **Stryv.ai**, building REST APIs, auth workflows, and 
  microservices for a cloud-native SaaS platform — with hands-on React.js experience 
  on the frontend
- 🔭 Outside of work, building **Mini S3** — a distributed object storage system from 
  scratch mirroring AWS S3 internals (consistent hashing, async replication via Kafka, 
  heartbeat-based fault tolerance)
- 🧩 Solved 230+ problems on LeetCode (DP, graphs, sliding window, trees)
- 🎓 B.Tech in Mechanical Engineering — self-transitioned into software engineering, 
  so I've had to prove myself with working systems rather than a CS pedigree. 
  That's still how I operate.
- 📫 Reach me at **mk4400320@gmail.com** · Portfolio: 
  [krishna-portfolio-tft6.onrender.com](https://krishna-portfolio-tft6.onrender.com/)
---

## 💼 Work Experience

### Software Engineer — Stryv.ai *(July 2024 – Present)*
*Cloud-native SaaS Platform · Hyderabad, India*

- Migrated core API functionality from a legacy **.NET** application to **Python/FastAPI**, reducing API response times by **60%**
- Build and maintain REST APIs across a **4-repository, 400+ endpoint** backend platform using Python/FastAPI and Java/Spring Boot
- Core contributor to a **Netflix-style session management system**, implementing single-active-session enforcement to prevent concurrent logins and improve account security
- Implemented authentication workflows using **Azure AD B2C** for secure sign-in and identity management in a multi-tenant SaaS application
- Collaborated cross-functionally with frontend, product, and QA in an agile environment to ship features and provide production support

---

## 🚀 Flagship Project — Mini S3

> A production-inspired distributed object storage system built from scratch — inspired by AWS S3 internals.

| Feature | Status |
|---|---|
| Bucket & Object CRUD with ETag validation | ✅ |
| Multipart upload with resume support | ✅ |
| Consistent hashing (150 virtual nodes) | ✅ |
| 3x async replication via Kafka | ✅ |
| Heartbeat failure detection (5s interval) | ✅ |
| Automatic failover to healthy replica | ✅ |
| Redis metadata caching (P99 < 10ms) | 🔄 |
| Presigned URLs + Object versioning | 🔄 |

**Tech:** Java 17 · Spring Boot · PostgreSQL · Redis · Kafka · Docker · GitHub Actions CI

**Systems concepts applied:**

| Concept | Applied In |
|---|---|
| Consistent hashing + virtual nodes | Object → node routing |
| CAP theorem trade-offs | Chose eventual consistency for higher write availability |
| Async event-driven replication | Kafka decouples write from replication |
| Heartbeat-based failure detection | 5s interval, 3-miss threshold |
| Metadata / data separation | PostgreSQL for metadata, disk for bytes |
| Multipart upload + ETag validation | MD5 checksum per part + final assembly |

[![mini-s3](https://img.shields.io/badge/View_Project-mini--s3-181717?style=for-the-badge&logo=github)](https://github.com/Mohan1234570/mini-s3)

---

## 🏗️ Other Projects

### Chatbook — Enterprise Microservices Chat Platform
*Spring Cloud Gateway · OAuth2 · JWT · Redis · WebSockets*

- Designed a **Spring Cloud Gateway**–based microservices architecture as the single entry point
- Implemented centralised authentication & authorisation using **OAuth2, JWT, and JWKS**
- Built **Redis-backed rate limiting** for abuse protection and scalability
- Developed real-time notifications and messaging using **WebSockets**
- Followed enterprise best practices: stateless services, zero-trust security, service isolation

<!-- Replace with the actual chatbook repo URL -->
[![chatbook](https://img.shields.io/badge/View_Project-chatbook-181717?style=for-the-badge&logo=github)](https://github.com/Mohan1234570/Chatbook-API-Gateway)

---

## 🧠 Core Skills

```java
Languages   →  Java 17, Python, JavaScript, TypeScript, SQL
Frontend    →  React.js, JavaScript (ES6+), HTML5, CSS3
Frameworks  →  Spring Boot, Spring Cloud, Spring Security, FastAPI, React
Databases   →  PostgreSQL, MySQL, Oracle, MongoDB, Redis
Messaging   →  Apache Kafka
Cloud/DevOps→  AWS, Docker, Kubernetes, GitHub Actions CI/CD, Linux
Auth        →  OAuth2, JWT/JWKS, Azure AD B2C
Concepts    →  Distributed Systems, Consistent Hashing, Replication,
               Clean Architecture, Design Patterns, REST API Design,
               Microservices, System Design
```

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" />
  <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" />
  <img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" alt="kafka" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="git" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40"/>
</p>

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mohan1234570&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohan1234570&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mohan1234570&theme=tokyonight&hide_border=true"/>
</p>

---

## 📝 Latest Writing

I write about distributed systems, Java backend engineering, and system design on Medium.

[![Medium](https://img.shields.io/badge/Follow_on_Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@mk4400320)

---

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/mohan-krishna-gudumala-802474248/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" width="40" /></a>
<a href="https://stackoverflow.com/users/21869969/gmkrishna" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="Stack Overflow" width="40" /></a>
<a href="https://medium.com/@mk4400320" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="Medium" width="40" /></a>
<a href="https://www.youtube.com/@g.mkrishna9218" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube" width="40" /></a>
<a href="https://www.hackerrank.com/profile/mk4400320" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="HackerRank" width="40" /></a>
<a href="https://leetcode.com/u/gm-krishna_123/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="LeetCode" width="40" /></a>
<a href="https://practice.geeksforgeeks.org/leaderboard" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/geeks-for-geeks.svg" alt="GeeksforGeeks" width="40" /></a>
</p>

<p align="center">
  <a href="mailto:mk4400320@gmail.com"><b>mk4400320@gmail.com</b></a>
</p>
