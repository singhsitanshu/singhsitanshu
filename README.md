# Hi, I'm Aansh Singh 👋

Computer Science student at **UCLA Samueli School of Engineering**, interested in building reliable software systems, AI-powered developer tools, and intelligent systems.

My work has focused on **distributed systems, backend engineering, agentic AI, retrieval-augmented generation, and computer vision**.

## Featured Projects

### TaskForge

A distributed task-execution platform built around reliability, concurrency, fault tolerance, and measurable performance.

**Tech:** Go · Python · PostgreSQL · Redis · Docker · Prometheus · Grafana · React · TypeScript

- Implemented atomic PostgreSQL task claiming with `FOR UPDATE SKIP LOCKED`
- Built priority scheduling, heartbeats, renewable leases, retries, idempotent submission, crash recovery, and durable attempt history
- Validated **3,000 tasks across 6,000 attempts with zero duplicate executions**
- Recovered **30/30 crash-affected attempts** during hard-kill testing
- Demonstrated **15.84× scaling across 16 workers at 99% parallel efficiency** on a synthetic 50 ms workload
- Sustained a median **2,143 API submissions/second** across 30,000 persisted submissions with zero request or transport errors
- Added Prometheus metrics and Grafana observability for runtime behavior and performance analysis

---

### CodeGraph

A full-stack repository-intelligence platform for understanding large codebases through static analysis, graph retrieval, and AI agents.

**Tech:** Python · FastAPI · React · TypeScript · Neo4j GDS · LangGraph · Tree-sitter · Postman

- Built repository ingestion and repository-scoped file, function, and call graphs
- Developed a **LangGraph ReAct agent with 7 repository-scoped tools** for structure, dependency, blast-radius, external-call, vector-search, source, and architecture analysis
- Integrated Neo4j vector indexes, **1,536-dimensional OpenAI embeddings**, and GDS Leiden-based semantic retrieval
- Reduced LLM context from roughly **737K to 18K tokens per query**, a **97.5% reduction**
- Built automated Postman workflows covering repository ingestion, graph retrieval, source lookup, Graph-RAG queries, and cleanup
- Added NDJSON assertions, negative tests, dynamic workflow variables, and HMAC-SHA256 signed webhook validation
- Tested the system with **82 Pytest cases** alongside Node-based testing

## Robotics & Computer Vision

I've also worked with **Bruin Underwater Robotics** on autonomous-system development involving:

- ROS2
- NVIDIA Jetson and Raspberry Pi
- YOLOv11 perception
- PyTorch
- ONNX
- TensorRT

## Technologies

**Languages**

`Go` `Python` `TypeScript` `Java` `C++`

**Backend & Systems**

`FastAPI` `PostgreSQL` `Redis` `Docker` `Prometheus` `Grafana`

**AI & Data**

`LangGraph` `Neo4j` `Neo4j GDS` `Tree-sitter` `OpenAI Embeddings`

**Frontend & API Development**

`React` `Postman`

**Robotics & Computer Vision**

`ROS2` `PyTorch` `YOLOv11` `ONNX` `TensorRT`

## Currently Exploring

I'm especially interested in projects involving:

- Distributed systems and concurrency
- Reliable backend infrastructure
- AI agents and developer tooling
- Retrieval-augmented generation
- Graph-based software analysis
- Computer vision and autonomous systems

---

**B.S. Computer Science · UCLA · Expected June 2029**
