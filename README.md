<!-- README.md — place in repo named Arnav-Purushotam -->

<!-- Profile Picture -->
<p align="center">
  <img src="./profile.png" alt="Profile Picture" width="150" style="border-radius:50%;" />
</p>


<h1 align="center">Hey, I'm Arnav Purushotam&nbsp;👋</h1>

<p align="center">
  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/arnav-purushotam-2375aa203/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin">
  </a>
  <!-- Email -->
  <a href="mailto:arnavpsusa@gmail.com">
    <img src="https://img.shields.io/badge/Email-Say%20hi!-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</p>

---

## 🧮 LeetCode Progress

<p align="center">
  <!-- Count badges -->
  <img src="https://img.shields.io/badge/Solved-163-brightgreen?style=for-the-badge&logo=leetcode&logoColor=yellow" />
  <img src="https://img.shields.io/badge/Easy-36-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Medium-119-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Hard-8-critical?style=for-the-badge" /><br/>
  <!-- Percentile badges -->
  <img src="https://img.shields.io/badge/Beats-89.8%25-4c1?style=for-the-badge&logo=leetcode&logoColor=yellow" />
  <img src="https://img.shields.io/badge/Top-10%25-4c1?style=for-the-badge" />
</p>

<p align="center">
  <!-- Live-updating card (no contest, no heatmap) -->
  <a href="https://leetcode.com/arnavp818/">
    <img src="https://leetcard.jacoblin.cool/arnavp818?theme=light&font=Roboto&hide=contest" alt="LeetCode Stats" />
  </a>
</p>





## 💼 Experience

### Open Source Contributor — curl / libcurl (C / Portability / Toolchains)

- Proposed and validated a cross-compiler logging strategy that enabled `CURL_DISABLE_VERBOSE_STRINGS` to truly compile out verbose trace format strings on **MSVC/Windows** via C99-style variadic trace macros; collaborated in public review with maintainers and was **credited in the final upstream solution**. ([PR #20387](https://github.com/curl/curl/pull/20387))
- Eliminated **GCC 15.2** `-Woverflow`/`-Wconversion` failures (often promoted to `-Werror` in CI) by preventing unintended high-bit propagation from `~mask` / `~0L` patterns, making auth/protocol/SSH option masks **warning-free, portable, and stable** when stored in 32-bit contexts.
- Contributed upstream fixes to **curl/libcurl** (large-scale, production, public-facing C codebase), hardening the `curl.h` public API bitmask macros against LP64 type-width pitfalls by constraining “ANY/ALL” masks to a **32-bit flag domain**, ensuring consistent behavior across 32/64-bit platforms. ([PR #20416](https://github.com/curl/curl/pull/20416))

## 💻 Projects

---

### 🗄️ Modular C++ Database Engine  
**August 2025 – September 2025**  
[github.com/Arnav-Purushotam-CUBoulder/cpp-db-engine](https://github.com/Arnav-Purushotam-CUBoulder/cpp-db-engine)

- Built a modular database engine in modern C++ (C++17/20): an in-memory hash map and a file-backed key–value store delivering `O(1)` lookups with durable writes; benchmarked against Redis to sanity-check throughput and latency.
- Designed a pluggable storage layer (PIMPL) to swap memory, disk, and cached-disk backends without changing call sites—setting the stage for sharding and future distribution.
- Added secondary indexes, bucketed namespaces, and templated key/value types (C++20 concepts) to enable fast searches over STL containers with zero-copy paths where possible.
- Automated cross-platform builds and tests with CMake and Catch2, using GitHub CLI; verified on Linux (GCC/Clang), macOS (Clang), and Windows (MSVC).
- Used complexity analysis to guide performance trade-offs.

---

### 🕒 CU Boulder Shift Scheduler  
**November 2024 – December 2024**  
[github.com/Arnav-Purushotam-CUBoulder/CUBoulder-Shift-Scheduler](https://github.com/Arnav-Purushotam-CUBoulder/CUBoulder-Shift-Scheduler)

Engineered a cloud-native, end-to-end shift-scheduling platform for high-traffic CU Boulder operations—bookstores, dining halls, and markets—using AWS EC2, CloudFormation, RDS, S3, and DynamoDB, with Flask APIs and Airflow orchestration.  
Automated scheduling workflows via AWS Lambda, SQS, SES, and CloudWatch event rules, delivering real-time notifications and error-free shift allocations.


**Architecture:**  
![Shift Scheduler Architecture](https://github.com/Arnav-Purushotam-CUBoulder/CUBoulder-Shift-Scheduler/blob/main/02_Documentation/Architecture.png)

---

### 🛒 Distributed Student E-Commerce Platform  
**July 2024 – July 2025**  
[github.com/Arnav-Purushotam-CUBoulder/distributed-student-ecommerce-platform](https://github.com/Arnav-Purushotam-CUBoulder/distributed-student-ecommerce-platform)

Built a microservices-based e-commerce platform tailored to students, with separate Product, Inventory, Order, and Notification services behind a Spring Cloud Gateway and Angular 18 + Tailwind frontend.  
Enabled event-driven ordering with Kafka and Schema Registry, resilience with Resilience4j and Micrometer, and secured the app using Keycloak SSO.  
Deployed full-stack observability using Prometheus, Grafana, Loki, Tempo, and Zipkin; containerized via Docker Compose and later migrated to Kubernetes (Kind), with CI using Testcontainers.




**Architecture:**  
![E-Commerce Architecture](https://github.com/Arnav-Purushotam-CUBoulder/distributed-student-ecommerce-platform/blob/master/img.png)







---

## 🤝 Connect
Open to collaborations on developing web software (full stack) or dev-tooling. Ping me on LinkedIn or raise an issue!

