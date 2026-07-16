# Changelog

Todas as mudanças relevantes do projeto serão documentadas neste arquivo.

---

# [1.1.0-alpha] - 2026-07-16

## Added

- Definição da camada de Estratégia do produto.
- Criação do documento Career Strategy (Banco Inter).
- Introdução do conceito de Competências.
- Separação entre Competências e Tecnologias.
- Definição da arquitetura em camadas.
- Definição do fluxo Objetivo → Competências → Tecnologias → Missões.
- Aprovação da metodologia "Documentação antes da implementação".

## Changed

- Roadmap deixa de representar apenas tecnologias.
- Dashboard passa a representar evolução por competências.
- Missões passam a desenvolver competências.
- Tecnologias passam a servir como ferramentas para desenvolver competências.

## Decisions

### ADR-001

Competências e Tecnologias coexistem.

**Motivo**

Competências representam aquilo que o usuário é capaz de construir.

Tecnologias representam as ferramentas necessárias para desenvolver cada competência.

Essa abordagem permite que usuários iniciantes tenham um caminho claro de aprendizado sem perder a visão prática da evolução.

### ADR-002

Todo desenvolvimento deverá seguir o fluxo:

Pesquisa → Documento → Revisão → Aprovação → Versionamento → Próximo Documento.

Nenhuma implementação será iniciada antes da aprovação da documentação correspondente.