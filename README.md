# Hackathon STATEC: Architecture Solution

## 1. Project Overview

This project proposes a lightweight and responsive architecture for **visualizing and analyzing Luxembourg’s economic data in a simple and accessible way**, leveraging STATEC datasets.  
**Goal:** Enable users to ask questions related to Luxembourg’s economy and receive AI-assisted answers while visualizing key indicators through an interactive dashboard.

### Main Components:
- **Dashboard**: Visualization of economic indicators and charts by theme (finance, demographics, and territory), with optional extensibility.
- **Explanatory Index**: Helps users understand economic topics.
- **AI Assistant**: Answers user questions using a GPT model connected to PowerBI to orchestrate any type of data-driven conversation.

---

## 2. Why This Project Matters for STATEC

- **Clarity and Accessibility**: Makes public statistics more understandable, accessible, and visual.
- **Facilitates AI usage around data**.
- **Optimized Cost**: The entire architecture can be built with open-source and free components (Python dashboard or Tableau, local and free N8N workflow engine, open-source GenAI).
- **Modularity and Speed**: Independent components, decentralized implementation, no heavy infrastructure. Dashboard development is independent from the workflow engine and AI.

---

## 3. How to Run the Project

### Technical Prerequisites
- **STATEC Datasets**: Available locally.
- **Front-end**: Local, without server or external API. Dashboard can be published for sharing.
- **Middleware**: N8N (€24/month, can be replace by free N8N running locally) to manage flows (possible with no-code).
- **AI**: OpenAI API (cost ≈ €0.01 per request).

### Recommended Tools
- **Microsoft PowerBI or Tableau**: Dashboard.
- **Microsoft PowerApps**: Input field.
- **Microsoft PowerAutomate**: Flow orchestration.
- **N8N**: Lightweight middleware between PowerAutomate and OpenAI API.
- **OpenAI API**: AI assistant.

### Steps
1. Create accounts (OpenAI, N8N).
2. Build an MVP.
3. Test and validate.

---

## 4. Key Principles
- Lightweight and modular architecture.
- Minimize data calls.
- Standardize flows.
- Decentralization (low/no-code).
- Avoid VMs, centralized middleware, full cloud.

---

**Author: Hackathon STATEC – EY Teams**  
© 2025 Ernst & Young S.A.
