# Database Model

| Informação | Valor |
|------------|-------|
| **Versão** | 1.0 Alpha |
| **Status** | Approved |
| **Projeto** | Operation Backend |
| **Responsável** | Igor Pacheco |
| **Última atualização** | 18/07/2026 |

## Documentos Relacionados

- Technical Architecture
- Dashboard
- Roadmap
- Planner
- Notion Implementation

---

# 1. Objetivo

Este documento define a estrutura de dados do Operation Backend.

Seu objetivo é especificar todas as Databases utilizadas pelo sistema, suas propriedades, relações e responsabilidades.

Toda implementação no Notion deverá seguir este modelo.

---

# 2. Arquitetura das Databases

O sistema será composto pelas seguintes Databases.

1. Objetivos

2. Competências

3. Tecnologias

4. Roadmap

5. Missões

6. Projetos

7. Certificações

8. Diário de Bordo

---

# 3. Database Objetivos

## Objetivo

Representar o destino final da jornada.

### Properties

| Nome | Tipo |
|------|------|
| Objetivo | Title |
| Área | Select |
| Status | Status |
| Prioridade | Select |
| Data Limite | Date |
| Progresso | Formula |

### Relations

- Roadmap

---

# 4. Database Competências

## Objetivo

Representar todas as competências necessárias para atingir o objetivo profissional.

### Properties

| Nome | Tipo |
|------|------|
| Competência | Title |
| Categoria | Select |
| Prioridade | Select |
| Status | Status |
| Progresso | Formula |

### Relations

- Tecnologias
- Missões
- Projetos
- Roadmap

---

# 5. Database Tecnologias

## Objetivo

Centralizar todas as tecnologias estudadas.

### Properties

| Nome | Tipo |
|------|------|
| Tecnologia | Title |
| Categoria | Select |
| Nível | Select |
| Status | Status |
| Documentação | URL |

### Relations

- Competências

---

# 6. Database Roadmap

## Objetivo

Organizar toda sequência de evolução.

### Properties

| Nome | Tipo |
|------|------|
| Etapa | Title |
| Ordem | Number |
| Status | Status |
| Início | Date |
| Fim | Date |

### Relations

- Competências
- Missões
- Objetivos

---

# 7. Database Missões

## Objetivo

Representar pequenas tarefas executáveis.

### Properties

| Nome | Tipo |
|------|------|
| Missão | Title |
| Status | Status |
| Prioridade | Select |
| Estimativa | Number |
| Data | Date |

### Relations

- Competências
- Projetos
- Roadmap

---

# 8. Database Projetos

## Objetivo

Materializar o aprendizado.

### Properties

| Nome | Tipo |
|------|------|
| Projeto | Title |
| Status | Status |
| GitHub | URL |
| Deploy | URL |
| README | URL |

### Relations

- Competências
- Missões

---

# 9. Database Certificações

## Objetivo

Gerenciar certificações.

### Properties

| Nome | Tipo |
|------|------|
| Certificação | Title |
| Plataforma | Select |
| Status | Status |
| Data | Date |
| Link | URL |

### Relations

- Competências

---

# 10. Database Diário de Bordo

## Objetivo

Registrar toda evolução diária.

### Properties

| Nome | Tipo |
|------|------|
| Data | Title |
| Horas Estudadas | Number |
| Aprendizados | Text |
| Dificuldades | Text |
| Melhorias | Text |

### Relations

- Missões
- Competências

---

# 11. Relações

Objetivos

↓

Roadmap

↓

Competências

↓

Tecnologias

↓

Missões

↓

Projetos

↓

Diário

Certificações possuem relação direta com Competências.

---

# 12. Convenções

Todas as Databases deverão utilizar:

- Status padrão do Notion.
- Select para classificações.
- Relations para integração.
- Rollups para indicadores.
- Fórmulas apenas quando necessário.

---

# 13. Views

Cada Database deverá possuir no mínimo:

## Table

Visualização completa.

---

## Board

Organização por Status.

---

## Timeline

Quando possuir datas.

---

## Gallery

Quando facilitar visualização.

---

# 14. Considerações Finais

O Database Model representa a estrutura oficial de dados do Operation Backend.

Todas as implementações deverão seguir este documento.