# Ferdynand Odhiambo

Backend engineer.

I work primarily in Go and Python, building APIs, payment systems, and data pipelines.
Most of my recent work has been in fintech — Go microservices handling payment event
processing at Payd HQ, and backend systems for a talent platform at Zone01 Kisumu
(01 Talent Partner).

I care about what happens when systems fail: partial writes, retry loops,
inconsistent state across services. That's where most of the interesting
engineering work actually is.

---

## Currently building

**[PesaFlow](https://github.com/MeFerdi)** — M-Pesa payment integration backend in Go.
STK Push, C2B callbacks, double-entry ledger, idempotency via Redis.
The hard part: Safaricom retries callbacks three times. Your handler must
produce the same result every time.

**[Monolith](https://github.com/MeFerdi/monolith)** — Local-first documentation indexer.
Search across local files, Google Drive, and Notion from one interface.
No cloud sync. Entirely on your machine.

**[Tweet Audit](https://github.com/MeFerdi)** — Resumable pipeline for processing
a full X archive against the Gemini API. Rate-limited, checkpoint-based,
recovers from mid-run crashes.

---

## Stack
```
Go · Python · PostgreSQL · Redis · Kafka · Django · FastAPI · Docker · Kubernetes
```

---

## Writing

- [Cache Invalidation: The Silent Performance Killer](https://dev.to/ferdinandodhiambo/cache-invalidation-the-silent-performance-killer-1fl8)
- [Mastering CORS in Golang](https://dev.to/ferdinandodhiambo/mastering-cors-in-golang-a-comprehensive-guide-25h2)

---

## Reach me
```
email     oferdinaddev112@gmail.com
linkedin  linkedin.com/in/ferdynand-odhiambo
web       f3rdinand.vercel.app
```
