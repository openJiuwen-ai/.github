# openJiuwen Security Policy
This document describes openJiuwen's trust model, defines the security boundaries of our distributed AI Agent platform, and sets the scope for reporting vulnerabilities.

## Reporting a Vulnerability
Please report any security vulnerabilities privately via email at contact@openjiuwen.com . Do not open public issues or pull requests for security vulnerabilities. openJiuwen does not currently operate a paid bug bounty program.

To help us triage and patch the issue quickly, a useful report should include:

Summary & Severity: A concise description of the vulnerability and its potential impact/severity. Affected Repository & Component: Since openJiuwen is modular, please specify the exact repository (e.g., agent-core, agent-studio, jiuwenswarm) and the affected code path.

Environment Details: SDK / Library versions (e.g., openjiuwen-core pip package version or Git commit SHA). Runtime environment (Python/Java version, OS, Distributed Runtime configs if applicable).

Steps to Reproduce: A minimal, self-contained proof of concept (PoC) demonstrating the exploit against the main branch or the latest stable release.

Any system behavior demonstrating prompt injection mitigation limitations or standard agent hallucinations that fails to compromise execution sandboxes or violate multi-tenant data isolation boundaries. Such incidents are explicitly classified as operational or functional software bugs rather than actionable security exploits.security
