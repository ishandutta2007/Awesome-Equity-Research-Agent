# Security Policy for Awesome Equity Research Agents

This repository is a curated list of AI agents and frameworks for equity research. While we do not host executable code for the agents listed here, we take the security and privacy of the financial AI community seriously.

## Supported Versions

We track the latest stable versions of the projects listed in the `README.md`.

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Security Concern

If you identify a security issue with one of the projects listed here, or if you believe a link in this repository points to malicious content:

1. **Do not open a public issue.**
2. Please report the concern by opening a private PR or contacting the maintainer via GitHub.

## Security in Financial AI Agents

When building or using **Autonomous Equity Research Agents**, we recommend following these security best practices:

- **Data Sovereignty**: Use local LLMs (via **Ollama** or **OpenClaw**) for sensitive proprietary research.
- **Model Drift**: Regularly monitor agents for "hallucinations" or "logic drift" in financial modeling.
- **API Safety**: Use **MCP (Model Context Protocol)** to safely connect agents to your internal financial databases.
- **Human-in-the-Loop**: Ensure critical investment decisions are reviewed by licensed professionals.

---

**Prioritizing trust and transparency in Autonomous Financial Intelligence.**
