# batuta-template

Este diretório contém um template copy-paste-ready do framework multi-agente
**Batuta**, extraído do uso real no projeto ATUA e genericizado para outros
repositórios.

## O que instalar em um novo projeto

Copie para a raiz do repositório de destino:

- `.github/agents/`
- `.github/copilot-instructions.md`
- `.github/VERSION`
- `.github/CHANGELOG.md`
- `.github/README.md`
- `docs/protocols/`
- `docs/decisions/` (ou pelo menos o diretório para ADRs)

## O que customizar

- nome do projeto e exemplos de domínio nas instruções;
- convenções de código em `.github/copilot-instructions.md`;
- agentes adicionais específicos do contexto do projeto;
- nicknames dos agentes, se desejar;
- documentação complementar (`docs/requirements/`, `docs/features/`,
  `docs/architecture/`, `docs/releases/`, quando aplicável).

## Observação

O template mantém a estrutura, a autoridade e os protocolos centrais do
Batuta, removendo referências específicas de produto, marca, AWS,
convenções C# e histórico interno do projeto ATUA.
