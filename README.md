<p align="center">
  <samp>monastir, tunisia &nbsp;·&nbsp; backendglitch.com</samp>
</p>

I build infrastructure that moves money, identifies people, and coordinates machines. Backend systems, computer vision, blockchain. If the problem requires writing Rust at 2am and reasoning about consensus algorithms, that is where I live.

---

### What I ship

**Wasla** — AI-powered transport infrastructure deployed across 15+ Tunisian louage stations. Real-time vehicle detection (YOLOv8, ONNX), bilingual license plate recognition (PaddleOCR SVTR, Arabic/French), and automated queue management processing 5,000+ vehicles per day. Built the entire stack: CV pipeline in Python/OpenCV, NestJS + Drizzle backend with Redis job queues and WebSocket streaming, Next.js station dashboard with live analytics.

**NexaPay** — Custom Proof-of-Stake L1 blockchain in Rust (Axum + RocksDB). BFT consensus, account model with WASM smart contracts, 2,500 TPS in benchmarks. TypeScript e-wallet with biometric auth. Bilingual CIN identity verification pipeline: ArcFace facial recognition (99.2% accuracy on Tunisian CIN dataset), passive liveness detection (MiniFASNet, 98.7% anti-spoofing rate), and on-chain KYC attestation with zero-knowledge proofs. Built the validator client, the RPC layer, and the KYC SDK.

**Fabrix** — Distributed 3D printing marketplace. Rust orchestration server matching print jobs across 50+ makers in Tunisia. Paxos-inspired consensus for job assignment, automatic failover on print failure, maker reputation scoring. Next.js marketplace frontend with real-time job tracking.

**Tanit** — Identity verification SaaS for North African fintech. API-first, developer-facing. JS SDK integrates in three lines. Client dashboard with live verification feed, fraud analytics, webhook dispatch. BCT Sandbox compliant.

### Engineering range

Rust, Go, Python, TypeScript, C++, Solidity. PostgreSQL, Redis, RocksDB, pgvector. Docker, Nginx, Cloudflare, Linux VPS. PyTorch, ONNX, TensorRT, OpenCV, PaddleOCR, ArcFace, MediaPipe. Distributed systems, consensus algorithms, computer vision pipelines, compiler design, smart contract security.

I do not build toy projects. Everything I write ships to production. Every line is written for the engineer who inherits it six months from now.

### Currently

Scaling Wasla to 30+ stations. Training engineers and interns in CV, Rust, and distributed systems. Running a 15-agent AI operations system that manages my company 24/7. Building Tanit's client SDK and attestation protocol.

---

<samp>backendglitch.com &nbsp;·&nbsp; contact@backendglitch.com &nbsp;·&nbsp; github.com/BackendGlitch</samp>
