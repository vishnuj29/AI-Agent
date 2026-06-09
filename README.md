## 🚀 Building AI Agents with ADK: From Single Agents to Multi-Agent Systems

Welcome to the **Agent Development Kit (ADK) Codelab** repository! This hands-on tutorial is designed to take developers from foundational agent configuration to orchestrating production-grade, multi-agent networks using Google's modern AI ecosystem.

---

### 🗺️ Learning Roadmap & Architecture

This system walks you through building complex architectural topologies, starting from isolated search tools up to fully decoupled routing nodes:

```text
       ┌────────────────────────┐
       │   Knowledge Navigator  │  ◄── (Top-Level Intent Router)
       └───────────┬────────────┘
       ┌───────────┼────────────┐
       ▼           ▼            ▼
┌──────────┐ ┌──────────┐ ┌────────────┐
│ Research │ │   Code   │ │  Creative  │  ◄── (Domain Specialist Sub-Agents)
│ Specialist│ │Specialist│ │ Specialist │
└──────────┘ └──────────┘ └────────────┘
