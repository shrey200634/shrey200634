<div align="center">

```
┌─────────────────────────────────────────────────────────┐
│  root@shrey-dave:~$ ./boot_profile.sh                    │
│                                                           │
│  [ OK ] Loading identity ......... shrey_dave             │
│  [ OK ] Mounting stack ........... java / spring / kafka  │
│  [ OK ] Starting services ........ backend-engineer.svc   │
│  [ OK ] Uptime ................... building since 2024    │
│                                                           │
│  system ready.                                            │
└─────────────────────────────────────────────────────────┘
```

</div>

<h3 align="center">Backend Engineer — Distributed Systems & Event-Driven Architecture</h3>
<p align="center"><sub>B.Tech CSE (Cloud Computing & Automation), VIT Bhopal · Noida, India</sub></p>

<p align="center">
  <a href="mailto:dshrey60@gmail.com">Email</a> ·
  <a href="https://linkedin.com/in/shrey-dave-326528325/">LinkedIn</a> ·
  <a href="https://github.com/shrey200634">GitHub</a> ·
  <a href="https://leetcode.com/u/dshrey/">LeetCode</a>
</p>

<br/>

### `$ whoami`

I build backend systems that stay correct under load — event-driven services, idempotent job processing, and the failure-handling that keeps them boring in production. Most of what's below started as a "will this actually survive concurrent load" question, then got benchmarked until it had an answer.

Recently wrapped a backend engineering internship at a US fintech, where I spent three months making inter-service calls harder to forge and ETL pipelines harder to break.

<br/>

### `$ cat //work/springer-capital.log`

**Backend Engineering Intern · Springer Capital Investments LLC** — *Mar 2026 – Jun 2026 (Remote, Dover, DE)*

```diff
+ Locked down 4+ inter-service API calls against replay attacks with HMAC-SHA256
  request signing at the Spring Security layer, ahead of production rollout.

+ Shipped 6+ Apache Airflow ETL pipelines with idempotent retries and exponential
  backoff — zero manual intervention needed on failure.

+ Wrote integration/unit test suites validating REST contracts pre-deployment,
  cutting production rollback incidents by 40%.

+ Defined RESTful API contracts across 2 cross-service integrations to kill
  contract drift before it reached consumers.
```

<br/>

### `$ ls ./featured-builds/`

<table>
<tr>
<td width="50%" valign="top">

**🚨 AI Incident Commander**

Event-driven incident response platform on CQRS — command and query services run independently, with an AI agent that diagnoses and proposes fixes for a human to approve.

- Dual-LLM agent (Gemini 2.5 Flash → Groq LLaMA 3.3 70B fallback) reasoning over live Prometheus metrics through 6 diagnostic tools
- Redis-backed idempotency keys behind a JWT-secured WebSocket dashboard, so nothing gets double-executed
- Resilience4j circuit breaker falling back to cached Redis snapshots when Prometheus goes down
- Docker-based execution engine with a MySQL dead-letter-queue recovery pipeline

`Java 21 · Spring Boot · Spring AI · Kafka · Redis · MySQL · React · Docker`

</td>
<td width="50%" valign="top">

**🍔 FoodRush**

Backend for a full-stack delivery platform — ordering, payments, and live tracking split across 8 independent services.

- Fault-tolerant checkout: a failed payment automatically reverses the order and refunds across every affected service
- Gemini-powered assistant for natural-language ordering and wallet queries
- Load-tested to **5,000 concurrent users at 239 req/sec, 0% errors**, with live dashboards for system health

`Java 21 · Spring Boot · Kafka · Spring AI · React`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**⚙️ DistributedJobForge**

Distributed job-scheduling platform that runs thousands of tasks across multiple workers without losing any of them, even when a worker dies mid-job.

- Automatic dependency resolution so dependent jobs always run in the correct order cluster-wide
- Token-bucket rate limiter throttling submission/execution to protect downstream services during spikes
- Java virtual threads pushed throughput to **1,735 jobs/min, 0% errors across 20,000 jobs**

`Java 21 · Spring Boot · Kafka · Redis · Docker`

</td>
<td width="50%" valign="top">

**🚦 Rate Limiter Suite**

Five rate-limiting algorithms — Fixed Window, Token Bucket, Leaky Bucket, Sliding Window Log, Sliding Window Counter — shipped as independent, swappable Spring Boot services.

- Redis + Lua scripting for atomic, race-free limit checks
- Full HLD/LLD design docs written for each algorithm before implementation

`Java · Spring Boot · Redis · Lua`

</td>
</tr>
</table>

<br/>

### `$ cat //stack.json`

```
{
  "languages"     : ["Java", "Python", "SQL", "JavaScript"],
  "backend"       : ["Spring Boot", "Spring Security", "REST APIs", "Microservices", "JWT"],
  "data_layer"    : ["MySQL", "MongoDB", "Redis"],
  "streaming"     : ["Apache Kafka", "Event-Driven Architecture"],
  "cloud_devops"  : ["AWS EC2", "Docker", "CI/CD", "Git"],
  "foundations"   : ["DSA", "OOP", "DBMS", "Operating Systems", "System Design (HLD/LLD)"],
  "learning_now"  : ["React.js", "advanced backend architecture"]
}
```

<br/>

### `$ cat //stats.log`

- 🧩 300+ LeetCode problems solved across arrays, trees, graphs, DP, and backtracking — 100+ day daily streak
- 📦 1,000+ GitHub contributions across backend and distributed-systems projects
- 🎓 Core Member — Fusion Club & DSA Community, VIT Bhopal

<div align="center">
  <br/>
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=shrey200634&show_icons=true&theme=chartreuse-dark&hide_border=true&count_private=true" />
  <img height="165em" src="https://leetcard.jacoblin.cool/dshrey?theme=dark&font=Fira%20Code&ext=heatmap" />
</div>

<br/>

<div align="center">

```
root@shrey-dave:~$ status --current
> targeting backend SDE roles @ fintech product companies
> open to distributed systems / platform engineering work
> always down to talk system design over chai
```

<sub>Profile views: <img src="https://komarev.com/ghpvc/?username=shrey200634&style=flat&color=39FF14" alt="views" valign="middle"/></sub>

</div>
