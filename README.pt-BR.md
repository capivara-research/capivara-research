# Fernando Viana

**Pesquisa de Vulnerabilidades · Segurança de Aplicações · Segurança Ofensiva · Segurança MCP**

Descobri e divulguei três CVEs publicadas que afetam Formwork, Kirby e phpwcms. Minhas pesquisas públicas documentam causas, pré-requisitos e provas de conceito seguras e reproduzíveis. Também desenvolvo ferramentas para avaliações de segurança autorizadas, incluindo o MCPEnum, utilitário em Go para descoberta de serviços Model Context Protocol (MCP).

📍 Brasília, Brasil · [LinkedIn](https://www.linkedin.com/in/fernanduviana/) · [English](README.md) | **Português**

## Projeto de código aberto em destaque

### [MCPEnum](https://github.com/capivara-research/MCPEnum)

Ferramenta de linha de comando em Go para **descoberta e enumeração de servidores MCP**. Encontra endpoints MCP acessíveis por HTTP e inventaria ferramentas, recursos, modelos de recursos e prompts anunciados. Compatível com Streamable HTTP e HTTP+SSE legado, com saída legível ou em JSON. O inventário é somente leitura: a ferramenta não executa ferramentas nem lê recursos.

[Código e documentação](https://github.com/capivara-research/MCPEnum) · [Versões para download](https://github.com/capivara-research/MCPEnum/releases)

## CVEs publicadas

| CVE | Produto e vulnerabilidade | Pesquisa |
| --- | --- | --- |
| [CVE-2026-110025](https://www.cve.org/CVERecord?id=CVE-2026-110025) | **phpwcms** — upload irrestrito de arquivos; execução remota de código quando o servidor executa arquivos `.phtml` enviados | [Análise técnica e PoC segura](https://github.com/capivara-research/CVE-2026-110025) |
| [CVE-2026-108924](https://www.cve.org/CVERecord?id=CVE-2026-108924) | **Kirby CMS** — falha de autorização que expõe metadados de modelos restritos em opções dinâmicas de campos | [Análise técnica e PoC segura](https://github.com/capivara-research/CVE-2026-108924) |
| [CVE-2026-105950](https://www.cve.org/CVERecord?id=CVE-2026-105950) | **Formwork CMS** — XSS armazenado por falha na validação de URI do atributo `formaction` | [Análise técnica e PoC segura](https://github.com/capivara-research/CVE-2026-105950) |

Os registros oficiais das CVEs me creditam como autor dos relatos. Cada repositório documenta a vulnerabilidade, seus pré-requisitos e uma demonstração local reproduzível.

## Foco de pesquisa e desenvolvimento

- **Segurança de aplicações web:** pesquisa de vulnerabilidades em CMS, controle de acesso, cross-site scripting (XSS) e segurança de uploads.
- **Divulgação responsável:** relatos com evidências e provas de conceito locais vinculados a registros CVE publicados.
- **Ferramentas de segurança:** reconhecimento e enumeração de servidores MCP em Go; ferramentas em Python e para testes de intrusão em ambientes autorizados.

Também mantenho o [Pentest-Tools](https://github.com/capivara-research/Pentest-Tools), uma coleção organizada de ferramentas para trabalhos autorizados em segurança ofensiva.

## Contato

Para colaborações em pesquisa ou assuntos profissionais, entre em contato pelo [LinkedIn](https://www.linkedin.com/in/fernanduviana/). Os testes de segurança e as provas de conceito aqui publicados destinam-se a sistemas próprios ou avaliados com autorização.
