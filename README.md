A LangGraph-powered simulation of mortality rate analysis using a multi-agent system with observability.

MortalityGraph is a Python-based project that demonstrates how a supervisor agent orchestrates worker agents to analyze healthcare data—specifically, mortality rate disparities across facilities. Built with LangGraph, it structures the workflow as a graph, simulating API calls to a read-only database and delivering actionable insights. Observability is baked in via LangSmith, providing transparency into every step.

Perfect for exploring multi-agent systems, healthcare analytics, or graph-based orchestration!

Features
Multi-Agent Architecture: A supervisor agent delegates tasks to worker agents (data fetching, analysis, visualization).
Graph Workflow: LangGraph defines a clear, programmable sequence of steps.
Simulated APIs: Hardcoded responses mimic fast database queries (e.g., mortality rates, staffing data).
Observability: LangSmith traces execution for debugging and performance insights.
Healthcare Focus: Analyzes why mortality rates differ between facilities, with text and simulated visualizations.

