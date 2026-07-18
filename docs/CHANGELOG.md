# Changelog

Todas as mudanças relevantes do projeto serão documentadas neste arquivo.

---

# [1.2.0-alpha] - 2026-07-16

## Added

- Criação do documento Career Strategy como base estratégica do projeto.
- Introdução da camada de Estratégia na arquitetura da documentação.
- Introdução do conceito de Competências.
- Separação entre Competências e Tecnologias.
- Definição da arquitetura em camadas.
- Definição do fluxo Objetivo → Competências → Tecnologias → Roadmap → Missões → Projetos.
- Padronização do cabeçalho para todos os documentos.
- Criação da Matriz de Competências como elemento central da estratégia.

## Changed

- O objetivo principal do Operation Backend passa a ser preparar o usuário para conquistar um estágio em Desenvolvimento Backend no Banco Inter.
- O Roadmap deixa de representar apenas tecnologias e passa a representar uma estratégia completa de evolução profissional.
- O Dashboard passa a acompanhar a evolução por Competências.
- Missões passam a desenvolver Competências.
- Tecnologias passam a servir como ferramentas para desenvolver Competências.
- A documentação passa a seguir uma abordagem enxuta, focada apenas no que agrega valor à implementação do Notion.

## Removed

- Documentation Roadmap removido do escopo da versão 1.0.
- Glossary removido do escopo da versão 1.0.
- Documentações auxiliares removidas para acelerar a implementação.

## Decisions

### ADR-001

Competências e Tecnologias coexistem.

**Motivo**

Competências representam aquilo que o usuário é capaz de construir.

Tecnologias representam as ferramentas necessárias para desenvolver essas competências.

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

---

### ADR-003

Documentação enxuta.

**Motivo**

A documentação deve existir para acelerar a implementação.

---

### ADR-004

O sistema será desenvolvido inicialmente para um único usuário.

**Motivo**

Toda decisão será otimizada para preparar o usuário para conquistar um estágio no Banco Inter.

---

### ADR-005

Architecture Freeze v1.0

**Motivo**

Após a conclusão do Career Strategy, a arquitetura do Operation Backend é considerada congelada.

A partir desta decisão não serão adicionados novos módulos, novos fluxos ou mudanças estruturais.

O foco passa a ser exclusivamente concluir a documentação e implementar o sistema.