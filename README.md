# AI Security Auditor

An AI-powered cybersecurity auditing tool built in Python that scans targets
for vulnerabilities and uses Llama 3.3 70B (via Groq) to analyze findings,
assign CVSS scores, and generate remediation reports.

## Features
- Port scanning (nmap)
- HTTP security header auditing
- SSL/TLS certificate checking
- AI-powered severity classification (CRITICAL / HIGH / MEDIUM / LOW)
- CVSS v3 scoring
- Actionable remediation suggestions
- JSON report export

## Tech Stack
Python · Groq API · Llama 3.3 70B · nmap · Google Colab

## How to Run
1. Open the notebook in Google Colab
2. Get a free API key at console.groq.com
3. Run all cells top to bottom

## Results Sample
The AI correctly identified 5 vulnerabilities including SQL injection (CVSS 9.0)
and exposed AWS credentials (CVSS 9.0) with specific fix recommendations.
