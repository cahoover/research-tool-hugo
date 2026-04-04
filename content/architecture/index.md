---
title: "Architecture"
---

Research Tool is a multi-layered platform that turns complex, evolving sources into durable, queryable, evidence-backed systems of knowledge. Its architecture preserves structure, supports reproducibility, and enables discovery across documents, datasets, media, and time. It's built in Python and Rust. 

**Multimodal Ingestion**  
RT’s ingestion layer turns raw sources into durable, versioned artifacts across documents, datasets, HTML, XML, and media. It is the front door to the platform and the beginning of the evidence chain, designed to preserve provenance from the first step of processing.

**Structured Data Engine**  
RT does not store simple tables. It transforms structured data into governed analytical surfaces that can be normalized across sources, compared over time, and projected into reusable states, relationships, and dynamics. Our testing routinely processes 200M rows. 

**Document & Media Parsing**  
RT preserves structure, hierarchy, and evidence fidelity across PDFs, HTML, XML, and media transcripts. Rather than flattening everything into undifferentiated chunks, it retains the internal form of source material so downstream systems can reason over real structure.

**Annotation Substrate**  
RT’s annotation substrate is a foundational architecture for stand-off semantics. It combines a structure substrate, canonical annotation bundles, and deterministic resolution, allowing machine and human annotations to remain grounded in stable document coordinates.

**Durable Artifact Plane**  
This is RT’s source-of-truth layer: deterministic identities, reproducible artifacts, manifest-based publishing, and stable contracts for downstream systems. It is the foundation that makes replay, auditability, and controlled evolution possible.

**Enrichment & Knowledge Derivation**  
RT combines machine enrichment with analyst-authored semantic layering. This layer derives observations, states, arcs, and annotations from source artifacts while also supporting human validation, curation, and interpretation as first-class knowledge surfaces.

**Search & Retrieval Stack**  
RT’s search stack combines query understanding, hybrid retrieval, graph context expansion, and answer generation. It is designed not as a thin keyword layer, but as a multi-stage retrieval system for evidence-backed exploration.

**Graph Projection & Runtime**  
RT projects durable artifacts into navigable runtime surfaces, including graph, search, and vector representations. This layer supports graph rendering, graph persistence, search indexing, embeddings, and staged projection into operational views.

**Exploration & Discovery Loop**  
RT supports graph-in-the-loop discovery through bounded planning and iterative computation. Candidate sets, checkpoints, and guided exploration loops make it possible to move from raw information to high-signal analytical paths without brute force.

**Control Plane & Orchestration**  
RT’s control plane coordinates jobs, manages specifications, tracks execution, and governs graph change workflows. It is the orchestration layer that keeps the system reproducible, observable, and operational at scale.