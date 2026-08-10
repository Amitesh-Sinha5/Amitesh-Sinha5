# Amitesh Sinha

CS undergrad at PES University. I build distributed systems and like the parts
that only show up under failure — consensus, replication, and what a cluster does
when a node stops answering.

---

### Selected work

**[mini-raft](https://github.com/Amitesh-Sinha5/miniraft)** — Raft from scratch
in Node.js
Randomized election timeouts, term-based voting with the §5.4.1 log up-to-date
restriction, `AppendEntries` log repair with conflict-term backtracking, and
majority-quorum commit across four replicas — under a real-time collaborative
canvas. Includes a partition simulator for reproducing split-brain. In-memory
state; the README is explicit about which paper guarantees that costs.
`Node.js · Docker · WebSockets`

**[mini-hdfs](https://github.com/Amitesh-Sinha5/mini-hdfs)** — distributed file
store
Namenode with `fsimage` + append-only edit log and periodic checkpoint merge,
2 MB chunking with SHA-256 checksums, replication factor 2 with heartbeat-driven
failure detection and automatic re-replication, free-space-aware placement.
`Python · TCP sockets · threading`

**[helix-agentic-ai-ops](https://github.com/Amitesh-Sinha5/helix-agentic-ai-ops)**
— agentic AI platform
Three LangGraph agent pods on one governed backend: auth and RBAC, tier-aware
rate limiting, hybrid retrieval with RRF and reranking, semantic caching
(p95 38.5 ms → 10.7 ms under a 5,106-request load test), cost telemetry, and a CI
gate on answer quality. Runs fully offline on a deterministic mock LLM.
`FastAPI · PostgreSQL · Redis · Terraform · ECS/K8s`

**[NeuroFit](https://github.com/Amitesh-Sinha5/NeuroFit)** — real-time pose
analysis with an LLM safety layer
Camera-based strength-training assistant built to test whether grounded
adversarial self-reflection reduces unsafe coaching advice.
`Python · computer vision`

**[Structural-Coder](https://github.com/RahulAnand2077/Structural-Coder)** —
collaboration, top contributor (31 of 55 commits)

**[HoneyTrap Firewall](https://github.com/Amitesh-Sinha5/Firewall)** — packet
filtering, IP banning, and attacker logging with a honeypot adapter layer.
`Python`

---

### Currently

Reading the Raft and Dynamo papers with an editor open, and looking for a
systems-side internship where storage and replication are the product rather than
a dependency.

sinhaamitesh0@gmail.com
