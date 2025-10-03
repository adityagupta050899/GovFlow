# GovFlow — Agentic AI for Public Service Automation

From bureaucracy to clarity — permits approved in minutes, not months.

GovFlow is a compliance-aware, **agentic** workflow that collects inputs, validates documents, applies policy, drafts a decision, keeps humans in the loop, and audits every step.

---

## Table of Contents
- [Features](#features)
- [Architecture](#architecture)
  - [Component Diagram](#component-diagram)
  - [Request Flow](#request-flow)
  - [Data Stores](#data-stores)
  - [Agents](#agents)
  - [Contracts (JSON shapes)](#contracts-json-shapes)
  - [Security & Ops](#security--ops)
- [Directory Layout](#directory-layout)
- [Quickstart](#quickstart)
  - [Backend (FastAPI / Python)](#backend-fastapi--python)
  - [Frontend (Next.js / React)](#frontend-nextjs--react)
- [API Overview](#api-overview)
- [Demo Data](#demo-data)
- [Database Schema (Postgres)](#database-schema-postgres)
- [Development Workflow](#development-workflow)
- [Configuration](#configuration)
- [License](#license)

---

## Features
- **Agentic methodology:** single-responsibility agents (Intake, Validation, Policy, Decision, Human Review, Comms, Audit)
- **Explainable outputs:** JSON checklists with citations and confidence per rule
- **Human-in-the-loop:** reviewers approve/override final decision
- **Continuous audit:** every action logged for transparency and fairness
- **Cloud-ready:** works locally; deployable to Cloud Run / Vertex AI (optional)

---

## Architecture

### Component Diagram
![GovFlow home](assets/screenshots/flow1.png)

---

## Results
![GovFlow home](assets/screenshots/result1.png)
![GovFlow home](assets/screenshots/result2.png)
![GovFlow home](assets/screenshots/result3.png)
![GovFlow home](assets/screenshots/result4.png)
