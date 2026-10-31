# Fernando Viana

**Pesquisa de vulnerabilidades · AppSec · Segurança ofensiva · IA e MCP**

Olá! Eu sou o Fernando, pesquisador de segurança em Brasília.

Gosto de entender como aplicações quebram, transformar descobertas em pesquisas reproduzíveis e criar ferramentas que sejam úteis fora do laboratório. Tenho explorado especialmente a segurança ofensiva de LLMs, agentes de IA e implementações do Model Context Protocol (MCP).

Quando encontro uma vulnerabilidade, procuro publicar algo que outra pessoa consiga verificar: análise técnica, evidências, impacto, correção e uma prova de conceito controlada. Até agora, esse trabalho resultou em oito CVEs.

📍 Brasília, Brasil · [LinkedIn](https://www.linkedin.com/in/fernanduviana/) · [English](README.md) | **Português**

## CVEs que publiquei

| CVE | Produto | Vulnerabilidade | Pesquisa |
| --- | --- | --- | --- |
| [CVE-2026-120218](https://www.cve.org/CVERecord?id=CVE-2026-120218) | **TypeMill CMS** | XSS armazenado por instrução XSLT em SVG | [Análise e PoC](https://github.com/capivara-research/CVE-2026-120218) |
| [CVE-2026-116004](https://www.cve.org/CVERecord?id=CVE-2026-116004) | **Onyx** | Bypass do sandbox de iframe de mesma origem e XSS armazenado | [Análise e PoC](https://github.com/capivara-research/CVE-2026-116004) |
| [CVE-2026-116000](https://www.cve.org/CVERecord?id=CVE-2026-116000) | **PrivateGPT** | SSRF no carregamento de artefatos por URI | [Análise e PoC](https://github.com/capivara-research/CVE-2026-116000) |
| [CVE-2026-110025](https://www.cve.org/CVERecord?id=CVE-2026-110025) | **phpwcms** | Upload irrestrito com possibilidade de execução remota de código | [Análise e PoC](https://github.com/capivara-research/CVE-2026-110025) |
| [CVE-2026-108924](https://www.cve.org/CVERecord?id=CVE-2026-108924) | **Kirby CMS** | Bypass de autorização em opções dinâmicas de campos | [Análise e PoC](https://github.com/capivara-research/CVE-2026-108924) |
| [CVE-2026-105950](https://www.cve.org/CVERecord?id=CVE-2026-105950) | **Formwork CMS** | XSS armazenado por bypass do sanitizador de `formaction` | [Análise e PoC](https://github.com/capivara-research/CVE-2026-105950) |
| [CVE-2026-90932](https://www.cve.org/CVERecord?id=CVE-2026-90932) | **LaraDashboard** | Path traversal com escrita/exclusão arbitrária e possível RCE | [Análise e PoC](https://github.com/capivara-research/CVE-2026-90932) |
| [CVE-2026-90931](https://www.cve.org/CVERecord?id=CVE-2026-90931) | **LaraDashboard** | XSS armazenado por upload de SVG | [Análise e PoC](https://github.com/capivara-research/CVE-2026-90931) |

Seis dessas CVEs foram atribuídas pelo VulDB e duas pela VulnCheck.

## Projetos

- **[MCPEnum](https://github.com/capivara-research/MCPEnum)** — ferramenta em Go para descobrir endpoints MCP e enumerar, sem invocá-los, ferramentas, recursos, templates e prompts anunciados.
- **[Pentest-Tools](https://github.com/capivara-research/Pentest-Tools)** — coleção de ferramentas e referências que uso em pentests e laboratórios autorizados.
- **[RedSonnet-5](https://github.com/capivara-research/RedSonnet-5)** — agentes e comandos para apoiar meus fluxos de CTF, HTB, OffSec PG e DESEC.

## O que tenho explorado

- Superfícies de ataque em LLMs, agentes de IA e servidores MCP.
- Vulnerabilidades em aplicações web e CMS, principalmente controle de acesso, XSS, SSRF, path traversal e upload de arquivos.
- Automação e ferramentas para pesquisa ofensiva em ambientes autorizados.

## Contato

Se quiser conversar sobre pesquisa de vulnerabilidades, segurança de IA ou colaboração em algum projeto, fale comigo pelo [LinkedIn](https://www.linkedin.com/in/fernanduviana/).

> Todo teste e PoC publicado aqui foi desenvolvido para sistemas próprios ou ambientes com autorização.
