# Fernando Viana

**Vulnerability research · AppSec · Offensive security · AI and MCP**

Hi! I'm Fernando, a security researcher based in Brasília, Brazil.

I like understanding where trust between users, applications, and AI systems can fail. These days, I split my time between web application research, offensive security for LLMs and AI agents, and the exploration of Model Context Protocol (MCP) implementations.

My approach is simple: a finding only becomes useful when others can understand and reproduce it. That is why I publish technical analysis, evidence, impact, remediation, and a controlled proof of concept. This work has resulted in eight CVEs so far.

📍 Brasília, Brazil · [LinkedIn](https://www.linkedin.com/in/fernanduviana/) · **English** | [Português](README.pt-BR.md)

## CVEs I have published

| CVE | Product | Vulnerability | Research |
| --- | --- | --- | --- |
| [CVE-2026-120218](https://www.cve.org/CVERecord?id=CVE-2026-120218) | **TypeMill CMS** | Stored XSS through an SVG XSLT processing instruction | [Analysis and PoC](https://github.com/capivara-research/CVE-2026-120218) |
| [CVE-2026-116004](https://www.cve.org/CVERecord?id=CVE-2026-116004) | **Onyx** | Same-origin iframe sandbox bypass and stored XSS | [Analysis and PoC](https://github.com/capivara-research/CVE-2026-116004) |
| [CVE-2026-116000](https://www.cve.org/CVERecord?id=CVE-2026-116000) | **PrivateGPT** | SSRF in URI-based artifact loading | [Analysis and PoC](https://github.com/capivara-research/CVE-2026-116000) |
| [CVE-2026-110025](https://www.cve.org/CVERecord?id=CVE-2026-110025) | **phpwcms** | Unrestricted upload with potential remote code execution | [Analysis and PoC](https://github.com/capivara-research/CVE-2026-110025) |
| [CVE-2026-108924](https://www.cve.org/CVERecord?id=CVE-2026-108924) | **Kirby CMS** | Authorization bypass in dynamic field options | [Analysis and PoC](https://github.com/capivara-research/CVE-2026-108924) |
| [CVE-2026-105950](https://www.cve.org/CVERecord?id=CVE-2026-105950) | **Formwork CMS** | Stored XSS through a `formaction` sanitizer bypass | [Analysis and PoC](https://github.com/capivara-research/CVE-2026-105950) |
| [CVE-2026-90932](https://www.cve.org/CVERecord?id=CVE-2026-90932) | **LaraDashboard** | Path traversal with arbitrary file deletion/write and potential RCE | [Analysis and PoC](https://github.com/capivara-research/CVE-2026-90932) |
| [CVE-2026-90931](https://www.cve.org/CVERecord?id=CVE-2026-90931) | **LaraDashboard** | Stored XSS through SVG upload | [Analysis and PoC](https://github.com/capivara-research/CVE-2026-90931) |

Six of these CVEs were assigned by VulDB and two by VulnCheck.

## Projects

- **[MCPEnum](https://github.com/capivara-research/MCPEnum)** — a Go tool that discovers MCP endpoints and enumerates their advertised tools, resources, templates, and prompts without invoking them.
- **[Pentest-Tools](https://github.com/capivara-research/Pentest-Tools)** — tools and references I use during authorized penetration tests and labs.
- **[RedSonnet-5](https://github.com/capivara-research/RedSonnet-5)** — agents and commands that support my CTF, HTB, OffSec PG, and DESEC workflows.

## On my radar

- Attack surfaces and trust boundaries in LLMs and AI agents.
- Discovery, enumeration, and abuse of functionality exposed by MCP servers.
- Web application and CMS vulnerabilities, especially access control, XSS, SSRF, path traversal, and file uploads.
- Automation that makes offensive research faster and reproducible.

## Contact

If you would like to discuss vulnerability research, AI security, or a possible collaboration, reach out on [LinkedIn](https://www.linkedin.com/in/fernanduviana/).

> Every test and proof of concept published here was developed for systems I own or environments where I had authorization.
