# Replication Package

This repository contains the replication data and scripts for the paper titled  
**"Model Context Protocol (MCP) at First Glance: Studying the Security and Maintainability of MCP Servers"**.  
It provides structured datasets and supporting materials for reproducing the study's analyses and results.

## 📦 Contents

The repository includes the following datasets:

### 1. MCP Server List (Full Set)
- **Count:** 1,899 MCP servers
- **Description:** Combines both:
  - Official and community servers listed in <a href="https://github.com/modelcontextprotocol/servers" target="_blank">Anthropic's MCP repository</a>
  - Additional MCP-compatible open source servers mined from GitHub

### 2. MCP Servers with Star Count > 10
- **Count:** 583 MCP servers
- **Description:** A curated subset of MCP servers that have gained significant developer attention on GitHub (i.e., more than 10 stars).
- **Includes:** Repository metadata and key maintainability metrics such as contributor count, issue count, commit activity, codebase size, and CI/CD metrics.

### 3. General-Purpose Vulnerabilities
- **Source:** Static analysis using **SonarQube**
- **Focus:** Standard vulnerabilities detectable by static analysis.

### 4. MCP-Specific Tool Poisoning Reports
- **Source:** <a href="https://github.com/invariantlabs-ai/mcp-scan" target="_blank">mcp-scan</a>
- **Focus:** Identifies **tool poisoning** and other MCP-specific risks in codebases that expose or depend on model context manipulation.

### 5. Code Smells and Bugs
- **Source:** SonarQube
- **Focus:** Maintainability concerns such as complex code, duplicated logic, overly long methods, and latent bugs with severity `CRITICAL` or `BLOCKER`.

## 🛠 How to Use

You can use these datasets for:
- Reproducing experiments from the paper
- Conducting follow-up research on secure and maintainable AI infrastructure
- Benchmarking static analysis tools and threat detection techniques for protocol-driven services

## 📜 Citation

If you use this dataset in your work, please cite the original paper:

```
citation details will be provided soon
```

For questions or feedback, please open an issue or contact the authors directly.
