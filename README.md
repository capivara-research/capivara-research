# Fernando Viana

**Vulnerability Research · Application Security · Offensive Security · MCP Security**

Security researcher focused on reproducible vulnerability research, responsible disclosure, and practical tooling for authorized assessments. My public work includes seven published CVEs and safe proofs of concept that document root cause, prerequisites, impact, and remediation.

📍 Brasília, Brazil · [LinkedIn](https://www.linkedin.com/in/fernanduviana/) · **English** | [Português](README.pt-BR.md)

## Published CVEs

| CVE | Product | Finding | Research and PoC |
| --- | --- | --- | --- |
| [CVE-2026-116004](https://www.cve.org/CVERecord?id=CVE-2026-116004) | **Onyx** | Same-origin iframe sandbox bypass leading to stored XSS | [Repository](https://github.com/capivara-research/CVE-2026-116004) |
| [CVE-2026-116000](https://www.cve.org/CVERecord?id=CVE-2026-116000) | **PrivateGPT** | Server-side request forgery in the URI artifact loader | [Repository](https://github.com/capivara-research/CVE-2026-116000) |
| [CVE-2026-110025](https://www.cve.org/CVERecord?id=CVE-2026-110025) | **phpwcms** | Unrestricted file upload leading to remote code execution when `.phtml` is executable | [Repository](https://github.com/capivara-research/CVE-2026-110025) |
| [CVE-2026-108924](https://www.cve.org/CVERecord?id=CVE-2026-108924) | **Kirby CMS** | Authorization bypass exposing restricted model metadata in dynamic field options | [Repository](https://github.com/capivara-research/CVE-2026-108924) |
| [CVE-2026-105950](https://www.cve.org/CVERecord?id=CVE-2026-105950) | **Formwork CMS** | Stored XSS through a `formaction` URI sanitizer bypass | [Repository](https://github.com/capivara-research/CVE-2026-105950) |
| [CVE-2026-90932](https://www.cve.org/CVERecord?id=CVE-2026-90932) | **LaraDashboard** | Path traversal enabling arbitrary file deletion/write and potential RCE | [Repository](https://github.com/capivara-research/CVE-2026-90932) |
| [CVE-2026-90931](https://www.cve.org/CVERecord?id=CVE-2026-90931) | **LaraDashboard** | Stored XSS through unsanitized SVG upload | [Repository](https://github.com/capivara-research/CVE-2026-90931) |

The official CVE records credit me as the reporter. Five records were assigned by VulDB and two LaraDashboard records were assigned by VulnCheck. Each repository contains evidence-backed analysis and a controlled, reproducible demonstration intended for authorized environments.

## Tools by Capivara

| Tool | Technology | Purpose | Links |
| --- | --- | --- | --- |
| **MCPEnum** | Go | Read-only discovery and enumeration of HTTP-accessible Model Context Protocol servers, tools, resources, templates, and prompts | [Source](https://github.com/capivara-research/MCPEnum) · [Releases](https://github.com/capivara-research/MCPEnum/releases) |
| **Pentest-Tools** | Shell / multi-language | Categorized collection for authorized penetration testing, Active Directory, privilege escalation, lateral movement, and pivoting | [Source](https://github.com/capivara-research/Pentest-Tools) |
| **RedSonnet-5** | Shell / OpenCode | Agent and command pack for authorized CTF, HTB, OffSec PG, and DESEC workflows | [Source](https://github.com/capivara-research/RedSonnet-5) |

### MCPEnum

MCPEnum is a single Go binary that discovers MCP endpoints and inventories their advertised capabilities. It supports Streamable HTTP and legacy HTTP+SSE, produces human-readable or JSON output, and does not invoke tools, read resources, or execute prompts during inventory.

```sh
mcpenum --target 127.0.0.1:8000
mcpenum --url https://mcp.example.test/api/mcp --format json
```

## Research and engineering focus

- **Web application security:** CMS research, access control, XSS, SSRF, path traversal, and file upload security.
- **Responsible disclosure:** evidence-backed reports, vendor coordination, and local proofs of concept linked to public records.
- **Security tooling:** MCP reconnaissance in Go and practical tooling for authorized offensive-security environments.

## Contact

For research collaboration or professional inquiries, connect with me on [LinkedIn](https://www.linkedin.com/in/fernanduviana/). Security testing and proof-of-concept work published here is intended for systems I own or am authorized to assess.
