# Giovanni Latorre

> Security engineer portfolio — AWS, Kubernetes runtime detection, MCP tooling, and LLM infrastructure.

| | |
|---|---|
| **GitHub** | [@GiovanniLatorre](https://github.com/GiovanniLatorre) |
| **Focus** | Cloud security, detection engineering, security automation |

## About

Hands-on security work across **AWS organizations**, **EKS/Falco**, **VPN posture**, and **AI-assisted operations** (MCP + LLM gateways). Repositories below are maintained as reference implementations and interview artifacts — sensitive org data is excluded or anonymized in public repos.

Documentation standard: [DOCUMENTATION-STANDARD.md](DOCUMENTATION-STANDARD.md)

---

## Public projects

### Security & detection

| Project | Description | Stack |
|---------|-------------|-------|
| [**security-mcp**](https://github.com/GiovanniLatorre/security-mcp) | MCP server for Cursor: AWS + Splunk investigation, daily posture, playbooks, guarded write tools | Python, MCP, boto3, SQLite |
| [**security-n1-bot**](https://github.com/GiovanniLatorre/security-n1-bot) | Slack bot with playbooks for tier-1 alert triage (VPN/DNS, ephemeral compute) | Python, Slack API, Docker |
| [**falco-ioc-audit**](https://github.com/GiovanniLatorre/falco-ioc-audit) | EKS Falco posture audit + 12 IOC rules (credential theft, fileless evasion) | Falco YAML, Markdown |

### LLM & infrastructure

| Project | Description | Stack |
|---------|-------------|-------|
| [**llm-smart-gateway**](https://github.com/GiovanniLatorre/llm-smart-gateway) | LLM gateway: cascade routing (fast/mid/heavy), PII guardrails, LiteLLM, Cursor SDK | Python, TypeScript, Docker |
| [**mikrotik-hardening**](https://github.com/GiovanniLatorre/mikrotik-hardening) | Home lab network: MikroTik VLAN segmentation, CFTV/IoT isolation, RouterOS exports | RouterOS |

---

## Private repositories (available on request)

These repos are on GitHub as **private** backups; I can walk through them in interviews or grant access when appropriate.

| Project | Description |
|---------|-------------|
| [ec2-credential-boundary](https://github.com/GiovanniLatorre/ec2-credential-boundary) | AWS SCP pilot — EC2 credential boundary (IP/role constraints) |
| [aws-credential-posture](https://github.com/GiovanniLatorre/aws-credential-posture) | Org-wide read-only inventory of IAM roles with EC2 trust |
| [pritunl-automation](https://github.com/GiovanniLatorre/pritunl-automation) | Pritunl API automation (servers, routes, org analysis) |
| [pritunl-posture](https://github.com/GiovanniLatorre/pritunl-posture) | Pritunl posture dashboard (FastAPI + frontend) |
| [pritunl-zero-audit](https://github.com/GiovanniLatorre/pritunl-zero-audit) | Pritunl Zero exposure audit tooling and reports |
| [vpn-monitor](https://github.com/GiovanniLatorre/vpn-monitor) | VPN/cloud collectors, anomaly/IOC analysis, Streamlit UI |
| [slack-migration](https://github.com/GiovanniLatorre/slack-migration) | Slack workspace migration utilities |
| [Deploy-Wazuh](https://github.com/GiovanniLatorre/Deploy-Wazuh) | Bash automation for Wazuh agent infrastructure on AWS |
| [gastos-casal](https://github.com/GiovanniLatorre/gastos-casal) | Personal Next.js expense tracker with Google Sheets sync |

---

## Highlights for interviews

- **MCP in production workflows** — `security-mcp` integrates investigation, posture, and playbook memory into the IDE.
- **Defense in depth on AWS credentials** — boundary pilot + org-wide EC2-trust mapping (private repos).
- **Runtime detection engineering** — Falco IOC rules validated against real cluster findings (anonymized in public docs).
- **Cost-aware LLM routing** — tiered models and PII masking before upstream API calls.

---

## License

Public code repositories (except this portfolio index) are licensed under the **MIT License** — see each repo’s `LICENSE` file.
