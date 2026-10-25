# Fernando Viana

**Vulnerability Research · Application Security · Offensive Security · MCP Security**

I discovered and disclosed three published CVEs affecting Formwork, Kirby, and phpwcms. My public research documents root causes, prerequisites, and safe, reproducible proofs of concept. I also build tools for authorized security assessment, including MCPEnum, a Go utility for Model Context Protocol (MCP) discovery.

📍 Brasília, Brazil · [LinkedIn](https://www.linkedin.com/in/fernanduviana/) · **English** | [Português](README.pt-BR.md)

## Featured open source project

### [MCPEnum](https://github.com/capivara-research/MCPEnum)

A Go command line tool for **MCP server discovery and enumeration**. It finds HTTP-accessible MCP endpoints and inventories advertised tools, resources, resource templates, and prompts. It supports Streamable HTTP and legacy HTTP+SSE, with human-readable and JSON output. Its inventory is read-only: it does not invoke tools or read resources.

[Source and documentation](https://github.com/capivara-research/MCPEnum) · [Releases](https://github.com/capivara-research/MCPEnum/releases)

## Published CVEs

| CVE | Product and finding | Research |
| --- | --- | --- |
| [CVE-2026-110025](https://www.cve.org/CVERecord?id=CVE-2026-110025) | **phpwcms** — unrestricted file upload; remote code execution when the server executes uploaded `.phtml` files | [Technical analysis and safe PoC](https://github.com/capivara-research/CVE-2026-110025) |
| [CVE-2026-108924](https://www.cve.org/CVERecord?id=CVE-2026-108924) | **Kirby CMS** — authorization bypass exposing restricted model metadata in dynamic field options | [Technical analysis and safe PoC](https://github.com/capivara-research/CVE-2026-108924) |
| [CVE-2026-105950](https://www.cve.org/CVERecord?id=CVE-2026-105950) | **Formwork CMS** — stored cross-site scripting through a `formaction` URI sanitizer bypass | [Technical analysis and safe PoC](https://github.com/capivara-research/CVE-2026-105950) |

The official CVE records credit me as the reporter. Each linked repository documents the vulnerability, its prerequisites, and a reproducible local demonstration.

## Research and engineering focus

- **Web application security:** CMS vulnerability research, access control, cross-site scripting (XSS), and file upload security.
- **Responsible disclosure:** evidence-backed reports and local proofs of concept linked to published CVE records.
- **Security tooling:** MCP server reconnaissance and enumeration in Go; Python and penetration testing tools for authorized environments.

I also maintain [Pentest-Tools](https://github.com/capivara-research/Pentest-Tools), a categorized collection of tools for authorized offensive security work.

## Contact

For research collaboration or professional inquiries, connect with me on [LinkedIn](https://www.linkedin.com/in/fernanduviana/). Security testing and proof of concept work here are intended for systems I own or am authorized to assess.
