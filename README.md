# AutoCare AI

AutoCare AI is an intelligent, multi-agent system designed to automate healthcare insurance claim processing. It replaces slow, manual prior authorization workflows with a fast, data-driven, and explainable solution.

---

## Overview

In traditional healthcare systems, insurance approvals are time-consuming, error-prone, and often lack transparency. AutoCare AI addresses these challenges by integrating validation logic, fraud detection, and AI-based reasoning into a unified pipeline that delivers real-time decisions.

---

## Key Features

* Role-based authentication (Patient, Agent, Admin)
* Document upload with OCR-based data extraction
* Multi-agent architecture:

  * Agent A – Document Processing and Structuring
  * Agent B – Policy Validation and Cost Analysis
  * Agent C – Fraud Detection and Claim History Check
  * Supervisor – Final Decision Engine
* Dataset-driven cost validation using historical claims
* Fraud detection (duplicate claims, anomalies, mismatches)
* Decision engine (Approve / Review / Reject)
* Explainable outputs with clear reasoning
* Dashboard interface for different user roles

---

## System Workflow

1. User submits a claim with medical documents
2. OCR extracts and structures medical data
3. Validation engine checks policy rules and cost boundaries
4. Claim history and fraud patterns are analyzed
5. AI reasoning generates explanations
6. Supervisor produces the final decision with transparency

---

## Tech Stack

* Frontend: React (Vite)
* Backend: Node.js (Express)
* Database: SQLite / JSON dataset
* AI Service: Python FastAPI
* Core Logic: Rule-based, dataset-driven, and LLM-ready

---

## Impact

* Reduces approval time from days to seconds
* Detects and prevents fraudulent claims
* Improves efficiency in healthcare workflows
* Provides transparent and explainable decisions

---

## Project Team

* Aravind Adityaa M 
* Lohitha Sai K 
* Nivetha J 
* Rajamurugan VS 

---

## Conclusion

AutoCare AI demonstrates how multi-agent systems and data-driven validation can transform healthcare insurance processes into faster, more accurate, and transparent systems.
