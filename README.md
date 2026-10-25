# Fernando Viana

**Vulnerability Researcher · Offensive Security · Application Security · Penetration Testing**

I research security flaws in web applications and build tools for authorized security assessment. My work focuses on vulnerability discovery, responsible disclosure, reproducible proof of concept research, and Model Context Protocol (MCP) security.

📍 Brasília, Brazil · [LinkedIn](https://www.linkedin.com/in/fernanduviana/) · **English** | [Português](README.pt-BR.md)

## Open source security tool

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

## Areas of work

`Vulnerability Research` · `Responsible Disclosure` · `Web Application Security` · `CMS Security` · `Access Control` · `Cross-Site Scripting (XSS)` · `File Upload Security` · `MCP Security` · `Go` · `Python` · `Penetration Testing`

I also maintain [Pentest-Tools](https://github.com/capivara-research/Pentest-Tools), a categorized collection of tools for authorized offensive security work.

## Contact

For research collaboration or professional inquiries, connect with me on [LinkedIn](https://www.linkedin.com/in/fernanduviana/). Security testing and proof of concept work here are intended for systems I own or am authorized to assess.
