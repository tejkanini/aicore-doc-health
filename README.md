# AI Core Doc Guardian

AI Core Doc Guardian is an AI-powered documentation quality and diagnostics engine built for Docusaurus and AI Core.

It continuously audits documentation using semantic embeddings, reasoning, and optional execution checks to detect gaps, inconsistencies, and outdated content.

The goal is simple: make documentation reliable, accurate, and self-improving.

---

## Problem

Documentation degrades over time.

Common issues include:

- outdated steps
- broken links
- missing prerequisites
- duplicated or conflicting explanations
- undocumented features
- unclear instructions
- increased support load caused by poor docs

Manual review does not scale.

---

## Value Proposition

Doc Guardian uses AI Core to automatically understand, audit, and improve documentation.

It provides:

- semantic understanding of content
- reasoning-based issue detection
- automated rewrite suggestions
- documentation health scoring
- optional command validation

This reduces onboarding time, improves developer experience, and lowers support costs.

---

## How It Uses AI Core

Doc Guardian directly leverages AI Core capabilities.

### Embeddings
- generate semantic vectors for each documentation chunk
- detect duplicates and overlaps
- find related or conflicting sections

### Vector Catalog
- store and search documentation semantically
- enable similarity and coverage analysis

### LLM Reasoning
- validate logical step order
- detect missing prerequisites
- identify ambiguity
- suggest clearer rewrites

### Structured Planning
- analyze procedural flows
- verify instruction sequences

### Optional MCP Execution
- validate commands in a safe sandbox
- confirm examples actually work

Without AI Core, these checks would require manual effort or weak rule-based tools.

---

## Core Capabilities

- Documentation ingestion and parsing
- Semantic similarity detection
- Duplicate content detection
- Gap and coverage analysis
- Logical step validation
- Clarity and readability suggestions
- Broken link detection
- Documentation health score
- Web dashboard for insights
- Optional command execution validation

---

## Repository Structure

```
aicore-doc-guardian/
│
├─ docs/                       # Docusaurus documentation content (input)
│
├─ scripts/
│   ├─ analyze_docs.py         # Run full diagnostics
│   ├─ embed_docs.py           # Generate embeddings
│   └─ health_report.py        # Produce summary report
│
├─ src/
│   ├─ ingestion/              # File loading and chunking
│   ├─ embeddings/             # AI Core embedding + vector logic
│   ├─ analysis/               # Reasoning and diagnostics
│   ├─ validators/             # Links and structure checks
│   ├─ mcp/                    # Optional execution tools
│   ├─ api/                    # Backend service
│   └─ dashboard/              # Docusaurus/React UI
│
├─ tests/
├─ requirements.txt
├─ package.json
├─ README.md
└─ .env.example
```

---

## Quick Start

Install dependencies:

```
pip install -r requirements.txt
```

Run analysis:

```
python scripts/analyze_docs.py ./docs
```

Start dashboard:

```
npm run start
```

---

## Example Output

- Documentation Health Score: 82/100
- 12 broken links detected
- 5 unclear sections flagged
- 3 duplicate pages detected
- 4 missing topic suggestions

---

## Vision

Turn documentation from static text into an intelligent system that continuously validates and improves itself using AI Core.
