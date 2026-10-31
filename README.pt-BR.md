# Fernando Viana

**Pesquisa de Vulnerabilidades · Segurança de Aplicações · Segurança Ofensiva · Segurança MCP**

Pesquisador de segurança focado em pesquisas reproduzíveis, divulgação responsável e ferramentas práticas para avaliações autorizadas. Meu trabalho público inclui oito CVEs publicadas e provas de conceito seguras que documentam causa raiz, pré-requisitos, impacto e correção.

📍 Brasília, Brasil · [LinkedIn](https://www.linkedin.com/in/fernanduviana/) · [English](README.md) | **Português**

## CVEs publicadas

| CVE | Produto | Vulnerabilidade | Pesquisa e PoC |
| --- | --- | --- | --- |
| [CVE-2026-120218](https://www.cve.org/CVERecord?id=CVE-2026-120218) | **TypeMill CMS** | XSS armazenado por instrução de processamento XSLT em SVG | [Repositório](https://github.com/capivara-research/CVE-2026-120218) |
| [CVE-2026-116004](https://www.cve.org/CVERecord?id=CVE-2026-116004) | **Onyx** | Bypass do sandbox de iframe de mesma origem resultando em XSS armazenado | [Repositório](https://github.com/capivara-research/CVE-2026-116004) |
| [CVE-2026-116000](https://www.cve.org/CVERecord?id=CVE-2026-116000) | **PrivateGPT** | SSRF no carregador de artefatos por URI | [Repositório](https://github.com/capivara-research/CVE-2026-116000) |
| [CVE-2026-110025](https://www.cve.org/CVERecord?id=CVE-2026-110025) | **phpwcms** | Upload irrestrito com execução remota de código quando `.phtml` é executável | [Repositório](https://github.com/capivara-research/CVE-2026-110025) |
| [CVE-2026-108924](https://www.cve.org/CVERecord?id=CVE-2026-108924) | **Kirby CMS** | Bypass de autorização expondo metadados restritos em opções dinâmicas | [Repositório](https://github.com/capivara-research/CVE-2026-108924) |
| [CVE-2026-105950](https://www.cve.org/CVERecord?id=CVE-2026-105950) | **Formwork CMS** | XSS armazenado por bypass do sanitizador de URI em `formaction` | [Repositório](https://github.com/capivara-research/CVE-2026-105950) |
| [CVE-2026-90932](https://www.cve.org/CVERecord?id=CVE-2026-90932) | **LaraDashboard** | Path traversal permitindo exclusão/escrita arbitrária e possível RCE | [Repositório](https://github.com/capivara-research/CVE-2026-90932) |
| [CVE-2026-90931](https://www.cve.org/CVERecord?id=CVE-2026-90931) | **LaraDashboard** | XSS armazenado por upload de SVG sem sanitização | [Repositório](https://github.com/capivara-research/CVE-2026-90931) |

Os registros e as fontes de atribuição das CVEs me creditam como autor dos relatos. Seis registros foram atribuídos pelo VulDB e os dois registros do LaraDashboard foram atribuídos pela VulnCheck. Cada repositório contém análise baseada em evidências e uma demonstração controlada e reproduzível para ambientes autorizados.

## Tools by Capivara

| Ferramenta | Tecnologia | Finalidade | Links |
| --- | --- | --- | --- |
| **MCPEnum** | Go | Descoberta e enumeração somente leitura de servidores MCP acessíveis por HTTP, incluindo ferramentas, recursos, modelos e prompts anunciados | [Código](https://github.com/capivara-research/MCPEnum) · [Releases](https://github.com/capivara-research/MCPEnum/releases) |
| **Pentest-Tools** | Shell / múltiplas linguagens | Coleção organizada para pentest autorizado, Active Directory, escalação de privilégios, movimento lateral e pivoting | [Código](https://github.com/capivara-research/Pentest-Tools) |
| **RedSonnet-5** | Shell / OpenCode | Pacote de agentes e comandos para fluxos autorizados de CTF, HTB, OffSec PG e DESEC | [Código](https://github.com/capivara-research/RedSonnet-5) |

### MCPEnum

O MCPEnum é um binário Go que descobre endpoints MCP e inventaria as capacidades anunciadas. Suporta Streamable HTTP e HTTP+SSE legado, oferece saída legível ou JSON e não invoca ferramentas, lê recursos ou executa prompts durante o inventário.

```sh
mcpenum --target 127.0.0.1:8000
mcpenum --url https://mcp.example.test/api/mcp --format json
```

## Foco de pesquisa e desenvolvimento

- **Segurança de aplicações web:** pesquisa em CMS, controle de acesso, XSS, SSRF, path traversal e segurança de uploads.
- **Divulgação responsável:** relatos baseados em evidências, coordenação com fornecedores e PoCs locais ligados a registros públicos.
- **Ferramentas de segurança:** reconhecimento MCP em Go e ferramentas práticas para ambientes autorizados de segurança ofensiva.

## Contato

Para colaborações em pesquisa ou assuntos profissionais, entre em contato pelo [LinkedIn](https://www.linkedin.com/in/fernanduviana/). Os testes e provas de conceito publicados aqui destinam-se a sistemas próprios ou avaliados com autorização.
