# Fernando Viana

**Pesquisador de Vulnerabilidades · Segurança Ofensiva · Segurança de Aplicações · Testes de Intrusão**

Pesquiso falhas de segurança em aplicações web e desenvolvo ferramentas para avaliações de segurança autorizadas. Meu trabalho envolve descoberta de vulnerabilidades, divulgação responsável, provas de conceito reproduzíveis e segurança do Model Context Protocol (MCP).

📍 Brasília, Brasil · [LinkedIn](https://www.linkedin.com/in/fernanduviana/) · [English](README.md) | **Português**

## Ferramenta de segurança de código aberto

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

## Áreas de atuação

`Pesquisa de Vulnerabilidades` · `Divulgação Responsável` · `Segurança de Aplicações Web` · `Segurança de CMS` · `Controle de Acesso` · `Cross-Site Scripting (XSS)` · `Segurança de Uploads` · `Segurança MCP` · `Go` · `Python` · `Testes de Intrusão`

Também mantenho o [Pentest-Tools](https://github.com/capivara-research/Pentest-Tools), uma coleção organizada de ferramentas para trabalhos autorizados em segurança ofensiva.

## Contato

Para colaborações em pesquisa ou assuntos profissionais, entre em contato pelo [LinkedIn](https://www.linkedin.com/in/fernanduviana/). Os testes de segurança e as provas de conceito aqui publicados destinam-se a sistemas próprios ou avaliados com autorização.
