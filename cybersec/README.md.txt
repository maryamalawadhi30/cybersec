Exploring Defence Mechanisms Against Prompt Injection in Generative and Agentic AI

An LLM-powered document assistant that evaluates prompt injection defences.

Objectives
-Evaluate how it responds to direct and indirect prompt injection attacks
-Evaluate if it effectively defends against these attacks and prevents unauthorized activity

Project Structure
/cybersec
├── README.md # readme file
├── /configs # configuration models
│ ├── baseline.py # baseline AI agent with no defence features
│ ├── combined.py # AI agent with both defence mechanisms combined
│ ├── prompt-based.py # AI agent with prompt-based defence
│ └── tool-authorization.py # AI agent with tool-authorization layer activated
├── /results
│ └── evaluation.py # results and evaluation of models
├── /tests
│ └── test1.py # first test