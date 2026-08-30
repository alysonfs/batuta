# Instruções do projeto

Este conjunto de agentes, skills e protocolos compõe o framework
**Batuta**, com versionamento próprio (ver `.github/README.md`,
`.github/VERSION` e `.github/CHANGELOG.md`).

Este repositório utiliza um workflow multi-agente coordenado. Antes de
executar qualquer tarefa de análise, arquitetura, implementação, QA,
documentação ou release, consulte:

- `docs/protocols/hierarchy.md` — hierarquia e autoridade dos agentes.
- `docs/protocols/communication.md` — formato obrigatório de comunicação.
- `docs/protocols/workflow.md` — estados e ciclo de vida da tarefa.
- `docs/protocols/decisions.md` — quando e como registrar decisões (ADR).

Os agentes especializados estão definidos em `.github/agents/` (`orchestrator`,
`product-analyst`, `software-architect`, `backend-engineer`,
`frontend-engineer`, `qa-engineer`, `documentation`, `release-versioning`).

Para tarefas que envolvam mais de um domínio (produto, arquitetura,
implementação, QA, documentação ou release), prefira acionar
o agente `orchestrator` em vez de executar a tarefa diretamente.

Documentação viva do projeto:

- Requisitos: `docs/requirements/`
- Funcionalidades: `docs/features/`
- Arquitetura: `docs/architecture/`
- Decisões: `docs/decisions/`
- Releases: `docs/releases/` (se aplicável)

Quando a documentação e a memória da conversa divergirem, a documentação
versionada é a fonte de verdade, salvo decisão explícita do usuário em
contrário.

## Convenções de código do projeto

- preencher com as convenções específicas de código deste projeto;
- registrar exceções relevantes na documentação versionada quando necessário.
