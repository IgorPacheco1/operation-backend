# Changelog

Todas as mudanças relevantes do projeto serão documentadas neste arquivo.

---

# [1.2.0-alpha] - 2026-07-16

## Added

- Criação do documento Career Strategy como base estratégica do projeto.
- Introdução da camada de Estratégia na arquitetura da documentação.
- Introdução do conceito de Competências.
- Separação entre Competências e Tecnologias.
- Definição da arquitetura em camadas (Estratégia → Arquitetura → Modelagem → Implementação).
- Definição do fluxo Objetivo → Competências → Tecnologias → Roadmap → Missões → Projetos.
- Padronização do cabeçalho para todos os documentos.
- Definição do fluxo oficial de desenvolvimento do projeto.

## Changed

- O objetivo principal do Operation Backend passa a ser preparar o usuário para conquistar o estágio em Desenvolvimento Backend no Banco Inter.
- O Roadmap deixa de representar apenas tecnologias e passa a representar uma estratégia de evolução profissional.
- O Dashboard passa a representar evolução por competências.
- Missões passam a desenvolver competências.
- Tecnologias passam a servir como ferramentas para desenvolver competências.
- A documentação passa a seguir uma abordagem enxuta, focada exclusivamente no que agrega valor à implementação do sistema.

## Removed

- Removido do escopo da versão 1.0:
  - Documentation Roadmap
  - Glossary
  - Documentações auxiliares que não contribuem diretamente para a implementação do Notion.

## Decisions

### ADR-001

Competências e Tecnologias coexistem.

**Motivo**

Competências representam aquilo que o usuário é capaz de construir.

Tecnologias representam as ferramentas necessárias para desenvolver cada competência.

Essa abordagem permite que usuários iniciantes tenham um caminho claro de aprendizado sem perder a visão prática da evolução.

---

### ADR-002

Fluxo oficial de desenvolvimento.

Pesquisa

↓

Análise

↓

Documento

↓

Revisão

↓

Aprovação

↓

Versionamento

↓

Próximo Documento

**Motivo**

Garantir que todas as decisões sejam fundamentadas antes da implementação.

---

### ADR-003

Documentação enxuta.

**Motivo**

A documentação deve existir para acelerar a implementação.

Qualquer documento que não agregue valor direto ao desenvolvimento da versão atual ficará fora do escopo da Sprint 0.

---

### ADR-004

O Operation Backend será desenvolvido inicialmente para um único usuário.

**Motivo**

Toda decisão arquitetural será otimizada para a preparação do Igor para o estágio em Desenvolvimento Backend no Banco Inter.

A generalização do sistema para múltiplos usuários será considerada apenas em versões futuras.