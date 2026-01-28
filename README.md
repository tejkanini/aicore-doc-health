# AI Core Doc Guardian

AI Core Doc Guardian is an intelligent documentation quality and diagnostics engine built on Docusaurus and AI Core.

It continuously analyzes documentation using embeddings, semantic reasoning, and optional execution checks to detect gaps, inconsistencies, and outdated content.

Instead of treating documentation as static text, Doc Guardian treats it as structured knowledge that can be validated, improved, and maintained automatically.

---

## Why this exists

Documentation naturally degrades over time. Manual review does not scale.

Common problems include:
- outdated instructions
- broken links
- missing prerequisites
- duplicated or conflicting content
- undocumented features
- unclear explanations
- high support load caused by poor docs


Doc Guardian uses AI Core to continuously audit and improve documentation quality.

---

## What this project is

Doc Guardian is a DocOps intelligence system that:

- understands documentation semantically
- detects logical and structural issues
- identifies knowledge gaps
- suggests improvements
- optionally validates commands using MCP

It uses AI Core’s embeddings, reasoning, and orchestration capabilities to perform deep analysis that rule-based tools cannot.

---

## Core Capabilities

### Documentation Quality Scanning
- broken links
- missing references
- outdated commands
- inconsistent terminology
- unclear or overly complex language

### Semantic Intelligence (AI Core Embeddings)
- detect duplicate or overlapping pages
- identify conflicting instructions
- cluster similar topics
- find undocumented features

### Reasoning (AI Core LLM)
- validate step order
- detect missing prerequisites
- flag ambiguous instructions
- suggest rewrites
- generate clearer explanations

### Documentation Health Score
- per-page quality score
- overall documentation health rating
- prioritized issues list

### Optional MCP Validation
- execute commands in sandbox
- verify examples actually work
- flag failing instructions

---

## How it uses AI Core

This project directly leverages AI Core capabilities:

- Embeddings API for semantic understanding
- Vector Catalog for similarity search
- LLM reasoning for instruction validation
- Structured planning for step analysis
- MCP tools for optional execution checks

Without AI Core, these checks would not be possible or would require heavy manual review.

---

## Architecture

Docs (Docusaurus)
    ↓
Ingestion + Chunking
    ↓
AI Core Embeddings → Vector Catalog
    ↓
AI Core Reasoning Engine
    ↓
Optional MCP Execution Checks
    ↓
Diagnostics Dashboard

---

## Repository Structure

