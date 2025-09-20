# Structured Brainstorming with TRIZ and Generative AI (AutoGen Multi-Agent System)

## Overview
This project integrates **TRIZ (Theory of Inventive Problem Solving)** with the **AutoGen multi-agent framework** to enable **structured brainstorming** and **innovation problem-solving** using Generative AI.  

The system helps executives, engineers, and researchers **resolve contradictions, forecast innovation trends, and reduce hallucinations in AI outputs** by leveraging TRIZ principles.  

---

## Objectives
- Apply **TRIZ methodology** to address real-world AI and business challenges.  
- Use **multi-agent collaboration (Expert, Validator, User Proxy)** for role-based innovation brainstorming.  
- Demonstrate how **AI hallucinations** can be mitigated with TRIZ principles like **Prior Action** and **Intermediary**.  
- Provide a **prompt library** for structured ideation and problem-solving.  

---

## Features
- **Multi-Agent Framework** (AutoGen):  
  - **TRIZ Expert** → Suggests inventive principles.  
  - **Technical Validator** → Checks feasibility and correctness.  
  - **User Proxy** → Represents stakeholder questions and concerns.  

- **TRIZ Principles in Action**:  
  - Contradiction elimination (e.g., “More detail leads to more hallucinations”)  
  - 9-Window System Analysis (Past → Present → Future)  
  - Technology evolution trends for Generative AI  

- **Hallucination Mitigation Use Case**:  
  - Applied TRIZ principles (#24 Intermediary, #10 Prior Action)  
  - Designed a fact-checking and retrieval layer  
  - Proposed hallucination-aware architectures with RAG  

---

## 🖼️ Visuals

### TRIZ Hallucination Problem (Slides)  
<img src="screenshots/GNHW1 (1).png" alt="GenAI Hallucination Problem" width="600"/>  

### 9-Window Analysis  
<img src="screenshots/GNHW2 (1).png" alt="9-Window TRIZ Analysis" width="600"/>  

---

## Tech Stack
- **Python**  
- **AutoGen (Microsoft)**  
- **OpenAI GPT Models (gpt-4o-mini)**  

---

## Methodology

### 1. Frame the Contradiction
Example:  
> *“Adding more detail improves quality, but also increases hallucinations.”*

### 2. Apply TRIZ Principles via AI Agents
- Ask TRIZ Expert:  
  `Apply Principle #10 (Prior Action) to reduce hallucinations in Generative AI.`  
- Validator checks practicality.  
- User Proxy provides executive perspective.  

### 3. Use 9-Window Analysis
- Map hallucination problem across **sub-system**, **system**, and **super-system**.  
- Explore past, present, and future trends.  

### 4. Forecast Technology Evolution
- How might hallucination-aware GenAI systems evolve?  
- Adaptive token allocation, self-tuning prompts, and grounded RAG pipelines.  
