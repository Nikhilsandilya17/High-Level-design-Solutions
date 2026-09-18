# System Design Notes — 25+ HLD Problems Solved

My structured notes on high-level design (HLD) — built while preparing for system design interviews and refined on the job as a backend engineer working on large-scale distributed systems.

Not walls of text — each problem is worked through the way you'd actually present it in an interview: requirements → estimation → API design → deep dive on the hard part → trade-offs.

## What's inside

### System Design Problems (27)

| | | | |
|---|---|---|---|
| Uber | Tinder | Twitter | WhatsApp Chat |
| YouTube | Netflix / Hotstar / Prime Video | Facebook News Feed | Facebook Live Comments |
| Google Docs | Google News | BookMyShow | Yelp |
| URL Shortener | Web Crawler | Notification System | Payment System |
| Rate Limiter | Key-Value Store | Online Auction | Price Tracking Service |
| Stock Price Alerts | Real-Time Gaming Leaderboard | LeetCode | Cheatsheet |

### Core Concepts

The fundamentals that come up in every round:

- Database indexing — B-trees, when indexes help and when they hurt
- Two-phase commit (2PC) — distributed transactions and consensus

### Advanced Topics

- Vector databases — embeddings, ANN search, and why every RAG system leans on them

### Technologies

- Elasticsearch — how it actually works under the hood

## How the notes are structured

Each system design problem covers:

1. **Functional & non-functional requirements** — what's actually in scope, what to clarify with the interviewer
2. **Back-of-envelope estimation** — QPS, storage, bandwidth, memory
3. **API & data model design** — before drawing boxes
4. **High-level architecture** — with diagrams (Excalidraw)
5. **Deep dive** — the one hard sub-problem worth spending time on (hot partitions, fan-out, sharding, consistency)
6. **Trade-offs** — what you give up with each choice

## Why another system design repo?

Most repos are either walls of textbook text or scattered one-liner diagrams. These notes are written for *retrieval* — structured enough to skim the night before an interview, detailed enough that you understand *why* each design decision is made, not just what it is.

## Contributing / Feedback

Found a gap, a wrong assumption, or a better trade-off? Issues and PRs welcome.

---

⭐ If these helped you, star the repo — it helps others find it.
