# Functional Architecture

| Informação | Valor |
|------------|-------|
| **Versão** | 1.0 Alpha |
| **Status** | Approved |
| **Projeto** | Operation Backend |
| **Responsável** | Igor Pacheco |
| **Última atualização** | 16/07/2026 |

## Documentos Relacionados

- Product Requirements Document
- Functional Architecture
- Career Strategy

---

# 1. Objetivo

Este documento descreve a arquitetura funcional do Operation Backend.

Seu propósito é definir como o sistema funciona do ponto de vista do usuário, quais são seus módulos, como eles se relacionam e qual fluxo de utilização foi projetado.

Este documento não descreve aspectos técnicos de implementação.

---

# 2. Filosofia do Produto

O Operation Backend foi concebido para eliminar a principal dificuldade encontrada durante a preparação para vagas na área de tecnologia:

> Decidir constantemente o que fazer.

Ao invés de exigir planejamento diário, o sistema deve apresentar automaticamente a próxima ação mais importante para aproximar o usuário do seu objetivo.

O usuário não deve administrar tarefas.

O usuário deve apenas executar a próxima missão.

Toda a arquitetura do sistema foi construída para reduzir a carga cognitiva, aumentar a produtividade e manter o foco na evolução contínua.

---

# 3. Objetivo Principal

Permitir que qualquer estudante acompanhe diariamente sua evolução profissional através de uma única plataforma.

O sistema deve responder rapidamente perguntas como:

- O que devo estudar agora?
- Qual tecnologia estou evoluindo?
- Quanto já evoluí?
- Qual será minha próxima etapa?
- Quanto falta para concluir meu objetivo?

---

# 4. Jornada do Usuário

A utilização diária do sistema foi projetada para exigir poucos minutos de planejamento.

Fluxo esperado:

Início do dia

↓

Abrir Dashboard

↓

Visualizar Missões do Dia

↓

Executar Missão

↓

Registrar Conclusão

↓

Atualizar Evolução

↓

Encerrar Dia

Toda navegação do sistema foi construída para seguir esse fluxo.

---

# 5. Arquitetura Funcional

O sistema é composto por módulos independentes.

Cada módulo possui uma única responsabilidade.

Os módulos cooperam entre si para construir a jornada completa do usuário.

Objetivo

↓

Competências

↓

Tecnologias

↓

Roadmap

↓

Missões

↓

Projetos

↓

Diário

↓

Dashboard

↓

Objetivo Final

---

# 6. Módulos

## Dashboard

Responsável por apresentar rapidamente todas as informações relevantes.

O Dashboard deverá responder:

- O que fazer hoje?
- Qual meu progresso?
- Quanto falta?
- Qual tecnologia está sendo estudada?
- Qual missão possui maior prioridade?

Nenhuma configuração deverá ser realizada nesta tela.

Ela deverá ser exclusivamente visual.

---

## Roadmap

O Roadmap representa toda a jornada de aprendizado.

Ele organiza a ordem correta dos conteúdos.

Nenhuma missão poderá existir sem estar associada ao Roadmap.

O Roadmap é o núcleo estratégico do sistema.

---

## Missões

Representam pequenas entregas executáveis.

Cada missão possui um objetivo claro.

Uma missão nunca deverá representar um estudo genérico.

Exemplos:

✔ Implementar autenticação JWT.

✔ Criar CRUD de usuários.

✔ Dockerizar aplicação.

Exemplos incorretos:

✘ Estudar Java.

✘ Aprender Spring.

---

## Competências

As Competências representam aquilo que o usuário deverá ser capaz de realizar ao concluir sua jornada de aprendizado.

Uma Competência sempre será composta por uma ou mais Tecnologias.

Exemplos:

- Desenvolver APIs REST
- Persistir Dados
- Implementar Autenticação
- Escrever Testes Automatizados
- Containerizar Aplicações
- Realizar Deploy

As Competências representam o resultado esperado do aprendizado.

Elas não substituem as Tecnologias.

Elas organizam sua aplicação prática.

---

## Tecnologias

Tecnologias representam ferramentas, frameworks, linguagens e conceitos necessários para desenvolver Competências.

Exemplos:

- Java
- Spring Boot
- Maven
- PostgreSQL
- Docker
- AWS

Cada Tecnologia poderá contribuir para diversas Competências.

Da mesma forma, uma Competência poderá utilizar diversas Tecnologias.

Essa relação permite organizar o aprendizado de maneira mais intuitiva para usuários iniciantes.

---

## Projeto

Todo aprendizado deverá gerar uma implementação prática.

O projeto principal representa a materialização do conhecimento adquirido.

Ele evolui continuamente durante toda a jornada.

---

## Diário de Bordo

Responsável por registrar aprendizados.

Cada dia deverá possuir uma entrada contendo:

- aprendizados

- dificuldades

- soluções

- melhorias

Esse histórico permitirá visualizar toda a evolução ao longo do tempo.

---

## Inglês

Centraliza todo o aprendizado relacionado ao inglês técnico.

Seu objetivo é tornar o inglês parte da rotina do usuário sem necessidade de um planejamento separado.

---

## Certificações

Controla certificações planejadas, em andamento e concluídas.

As certificações fazem parte da evolução profissional, mas não representam o objetivo principal do sistema.

---

## Banco Inter

Representa o objetivo final da jornada.

Esta área centraliza:

- competências exigidas

- checklist

- currículo

- GitHub

- LinkedIn

- preparação para entrevistas

Este módulo serve como referência para todas as decisões do Roadmap.

---

# 7. Fluxo Funcional

Roadmap

↓

Seleciona próxima missão

↓

Missão executada

↓

Atualiza Projeto

↓

Atualiza Tecnologia

↓

Atualiza Diário

↓

Atualiza Dashboard

↓

Usuário acompanha evolução

---

# 8. Navegação

Toda navegação deverá seguir três princípios.

Baixo número de cliques.

Pouca necessidade de configuração.

Alta velocidade de consulta.

O Dashboard deverá funcionar como ponto central do sistema.

Todos os demais módulos deverão ser acessados a partir dele.

---

# 9. Princípios de Experiência

Toda interação deverá respeitar os seguintes princípios.

## Clareza

As informações importantes devem estar visíveis imediatamente.

---

## Simplicidade

Cada tela deverá possuir apenas os elementos necessários.

---

## Consistência

Os módulos deverão possuir comportamento semelhante.

---

## Rapidez

Nenhuma ação comum deverá exigir muitos cliques.

---

## Motivação

O sistema deverá transmitir sensação constante de progresso.

---

# 10. Critérios de Sucesso

A Arquitetura Funcional será considerada bem sucedida quando:

O usuário conseguir iniciar seus estudos em menos de cinco minutos.

O Dashboard responder às principais dúvidas sem necessidade de navegar entre páginas.

Toda missão possuir relação direta com um objetivo do Roadmap.

Toda evolução ser refletida automaticamente no restante do sistema.

O usuário sentir que está sempre avançando em direção ao objetivo final.

---

# 11. Considerações Finais

O Operation Backend não foi concebido como um organizador de tarefas.

Ele foi projetado para funcionar como um sistema operacional de evolução profissional.

Sua missão é reduzir a necessidade de planejamento, aumentar a velocidade de execução e permitir que o usuário concentre sua energia naquilo que realmente importa:

Aprender.

Construir.

Evoluir.