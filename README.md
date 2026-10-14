<div align="center">

# ⚡ Đinh Tuấn Duy
### Systems & Backend Software Engineer | C++ & Go Enthusiast
**B.Sc. in Computer Science @ HCMUS** • **IELTS 7.0** • **GPA 3.3/4.0**

[Website / Portfolio](https://github.com/dtduy23) • [LinkedIn](https://linkedin.com/in/YOUR_LINKEDIN) • [dtuanduy2005@gmail.com](mailto:dtuanduy2005@gmail.com)

[![GitHub followers](https://img.shields.io/github/followers/dtduy23?label=Follow&style=social)](https://github.com/dtduy23)
[![GitHub stars](https://img.shields.io/github/stars/dtduy23?label=Stars&style=social)](https://github.com/dtduy23)

</div>

---

### 👨‍💻 Engineering Summary
I am a 2nd-year Computer Science student at **Ho Chi Minh City University of Science (HCMUS)** focusing on **Systems Programming, Concurrency, and Cloud-Native Backends**. 

- 🏎️ **Low-Latency & Systems:** Experience building non-blocking I/O event loops (`epoll`), custom binary protocols, memory-safe C++20 design with RAII & ASan/UBSan.
- 🌐 **Distributed Systems & Concurrency:** Designing zero-overbooking admission systems, message queues, and GitOps pipelines.
- 🎓 **Core Foundations:** Data Structures & Algorithms, Operating Systems, Computer Networks, and Database Internals.

---

### 🚀 Highlighted Systems & Projects

#### 1. [mini-redis-cpp](https://github.com/dtduy23/mini-redis) `C++20` `Linux` `epoll` `ASan/UBSan`
> High-performance, event-driven in-memory key-value store built from scratch with POSIX sockets.
- **Throughput & Latency:** Reached **103,000 GET requests/sec** with **0.93 ms p99 latency** (native TCP benchmark: 50 concurrent clients, 100k requests).
- **Core Features:** Streaming RESP2 parser with command pipelining, fork-based RDB snapshots with checksums, atomic file replacement, lazy/active TTL expiration, and async thread pool for `UNLINK`.
- **Engineering Rigor:** Hardened against TCP half-close, buffer overflows, and corrupted snapshots using RAII, AddressSanitizer (ASan), and UBSan.

#### 2. [UniHub Workshop](https://github.com/dtduy23/Unihub-workshop) `Go` `Kubernetes` `ArgoCD` `RabbitMQ` `PostgreSQL`
> Full-featured event platform & GitOps infrastructure handling high-contention ticket reservations.
- **High Concurrency Engine:** Built registration API with Redis admission control, RabbitMQ workers, PostgreSQL row-level locking, and RSA-signed QR tickets.
- **Correctness:** Allocated 100 seats across **2,000 simulated concurrent requests with ZERO overbooking**.
- **Production GitOps:** Packaged via Helm & KEDA autoscaling, orchestrated by **ArgoCD sync waves** and **Argo Workflows CI DAG** with automated **k6 performance gates** ($p95 < 200\text{ms}$).
- **Observability:** Centralized logging with Fluent Bit / OpenSearch (trace IDs) and custom Prometheus / Grafana dashboards.

---

### 🛠️ Technical Arsenal

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | `C++17/20`, `Go`, `C`, `Python`, `SQL`, `Bash`, `Java` |
| **Systems & Low-Level** | Linux internals, `epoll`, POSIX sockets, multithreading, mutexes/CVs, memory sanitizers (`ASan`, `UBSan`) |
| **Backend Architecture** | Clean Architecture, RESTful APIs, PostgreSQL, Redis, RabbitMQ |
| **Cloud & GitOps** | Docker, Kubernetes, Helm, ArgoCD, Argo Workflows, KEDA, Nginx |
| **Testing & Observability** | k6, Prometheus, Grafana, OpenSearch, Fluent Bit |

---

### 📈 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dtduy23&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb" height="155" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dtduy23&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff" height="155" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dtduy23&theme=github_dark&hide_border=true&background=0d1117&ring=58a6ff&fire=1f6feb&currStreakLabel=58a6ff" alt="GitHub Streak" />
</div>

<p align="center">
  <i>"Writing fast, correct, and resilient software from the kernel up to distributed clouds."</i>
</p>
