# Ferdynand Odhiambo

**Backend Engineer · Java, Go & Python · Testing and reliability of AI-enabled systems**

Nairobi, Kenya · open to remote roles

---

## About

Backend engineer working mainly in Java, Go and Python. I have built and maintained Go and Python services for fintech and talent-management platforms, including payment event processing, transaction workflows and data pipelines. I am completing Product Engineering training at Kood/Nairobi (Java on the backend, TypeScript on the frontend) and working through the 01 Edu curriculum to build the fundamentals properly.

My public work is about one question: how do you know an AI-enabled system behaves? Each project below validates model output, limits what an agent may do, and ships with tests that can fail.

---

## Selected projects

| Project | Language | What it is |
|---|---|---|
| [autonomous-qa-agent](https://github.com/MeFerdi/autonomous-qa-agent) | TypeScript | Deterministic Playwright checks find the failure; an AI agent explains it and files a structured bug report. Ships with a mock storefront whose bugs can be switched on, so diagnosis is checked against ground truth. |
| [rag-knowledge-assistant](https://github.com/MeFerdi/rag-knowledge-assistant) | TypeScript | Question answering with machine-verified citations and an evaluation harness that fails CI when a metric drops. Includes a planted prompt injection to test the defence. |
| [ai-support-agent](https://github.com/MeFerdi/ai-support-agent) | TypeScript | A support agent that calls backend tools under an explicit read/write permission model: writes wait for customer confirmation and PII is redacted before the model sees it. Runs against mock services; not production-tested. |
| [tweet-audit](https://github.com/MeFerdi/tweet-audit) | Go | Resumable, rate-limited pipeline that reviews an X archive in batches and recovers from interruption. |
| [key-value-store](https://github.com/MeFerdi/key-value-store) | Go | Distributed key-value store with a gRPC interface, built to study replication. Raft consensus is stubbed; work in progress. |
| [http-server](https://github.com/MeFerdi/http-server) | Rust | Single-threaded, non-blocking HTTP/1.1 server on `epoll` and raw POSIX syscalls, with no async runtime or framework. |

Learning in the open: [exercism-java](https://github.com/MeFerdi/exercism-java).

---

## Stack

```
Java · Go · Python · TypeScript · PostgreSQL · Redis · Docker · Playwright · GitHub Actions
```

---

## Writing

- [Cache Invalidation: The Silent Performance Killer](https://dev.to/ferdinandodhiambo/cache-invalidation-the-silent-performance-killer-1fl8)
- [Mastering CORS in Golang](https://dev.to/ferdinandodhiambo/mastering-cors-in-golang-a-comprehensive-guide-25h2)
- [Bridging the Gap: From axios to gRPC Interceptors in Go](https://dev.to/ferdinandodhiambo/bridging-the-gap-from-axios-to-grpc-interceptors-in-go-3a0m)

---

## Contact

[linkedin.com/in/ferdynand-odhiambo](https://linkedin.com/in/ferdynand-odhiambo) · [f3rdinand.vercel.app](https://f3rdinand.vercel.app) · oferdinaddev112@gmail.com
