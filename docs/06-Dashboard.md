# Dashboard

| Informação | Valor |
|------------|-------|
| **Versão** | 1.0 Alpha |
| **Status** | Approved |
| **Projeto** | Operation Backend |
| **Responsável** | Igor Pacheco |
| **Última atualização** | 18/07/2026 |

## Documentos Relacionados

- Functional Architecture
- Technical Architecture
- Database Model

---

# 1. Objetivo

O Dashboard é o ponto central de utilização do Operation Backend.

Seu objetivo é concentrar todas as informações necessárias para iniciar o dia de estudos sem que o usuário precise navegar entre diferentes páginas.

Toda sessão de estudo deverá começar pelo Dashboard.

---

# 2. Filosofia

O Dashboard não é um local para cadastrar informações.

Sua função é apresentar informações já existentes de forma clara e objetiva.

Sempre que possível, as informações devem ser atualizadas automaticamente pelas Databases relacionadas.

---

# 3. Estrutura Geral

O Dashboard será dividido nas seguintes seções:

1. Cabeçalho
2. Objetivo Principal
3. Missões do Dia
4. Roadmap
5. Competências
6. Projetos
7. Certificações
8. Diário de Bordo
9. Estatísticas

---

# 4. Implementação

## 4.1 Cabeçalho

Criar uma página chamada:

Operation Backend

Adicionar:

- Foto ou ícone do projeto.
- Frase de motivação.
- Data atual.
- Links rápidos para GitHub e LinkedIn.

---

## 4.2 Objetivo Principal

Inserir um bloco contendo:

Objetivo Atual

Exemplo:

Conquistar estágio em Desenvolvimento Backend no Banco Inter.

Abaixo, adicionar uma barra de progresso vinculada ao database "Objetivos".

---

## 4.3 Missões do Dia

Adicionar uma visualização da Database "Missões".

Filtros:

- Status = Não iniciada ou Em andamento.
- Data = Hoje.

Ordenação:

1. Prioridade
2. Data

Exibir apenas as colunas:

- Missão
- Prioridade
- Competência
- Status

---

## 4.4 Roadmap

Adicionar uma visualização da Database "Roadmap".

Exibir:

- Etapa atual.
- Próxima etapa.
- Progresso geral.

---

## 4.5 Competências

Adicionar uma visualização da Database "Competências".

Ordenar por:

- Progresso decrescente.

Exibir:

- Nome
- Categoria
- Progresso
- Status

---

## 4.6 Projetos

Adicionar uma visualização da Database "Projetos".

Mostrar:

- Projetos em andamento.
- Última atualização.
- Status.

---

## 4.7 Certificações

Adicionar uma visualização da Database "Certificações".

Filtrar:

Status ≠ Concluída.

Mostrar:

- Nome
- Plataforma
- Status
- Data prevista

---

## 4.8 Diário de Bordo

Adicionar uma visualização da Database "Diário de Bordo".

Ordenação:

Mais recente primeiro.

Mostrar:

- Data
- Horas estudadas
- Aprendizados

---

## 4.9 Estatísticas

Adicionar indicadores como:

- Horas estudadas na semana.
- Dias consecutivos de estudo.
- Competências concluídas.
- Tecnologias estudadas.
- Projetos concluídos.
- Certificações concluídas.

Esses indicadores poderão ser calculados por Rollups ou Fórmulas.

---

# 5. Layout

Sugestão de organização:

══════════════════════════════

🎯 Objetivo

══════════════════════════════

📌 Missões do Dia

══════════════════════════════

🛣️ Roadmap

══════════════════════════════

💻 Competências

══════════════════════════════

🚀 Projetos

══════════════════════════════

🏆 Certificações

══════════════════════════════

📖 Diário de Bordo

══════════════════════════════

📊 Estatísticas

══════════════════════════════

---

# 6. Fluxo Diário

1. Abrir o Dashboard.
2. Ler o Objetivo Principal.
3. Verificar as Missões do Dia.
4. Executar as Missões.
5. Atualizar o status das Missões.
6. Registrar o estudo no Diário de Bordo.
7. Verificar a evolução das Competências.
8. Encerrar a sessão.

---

# 7. Boas Práticas

- Não cadastrar informações diretamente no Dashboard.
- Atualizar apenas pelas Databases correspondentes.
- Revisar o Dashboard no início e no fim de cada dia.
- Manter apenas informações relevantes para evitar poluição visual.

---

# 8. Checklist de Implementação

- [ ] Criar página principal "Operation Backend".
- [ ] Adicionar cabeçalho.
- [ ] Inserir objetivo principal.
- [ ] Configurar visualização das Missões.
- [ ] Configurar visualização do Roadmap.
- [ ] Configurar visualização das Competências.
- [ ] Configurar visualização dos Projetos.
- [ ] Configurar visualização das Certificações.
- [ ] Configurar visualização do Diário de Bordo.
- [ ] Adicionar indicadores e estatísticas.

---

# 9. Critérios de Sucesso

O Dashboard será considerado concluído quando:

- Todas as informações essenciais estiverem disponíveis em uma única página.
- O usuário conseguir identificar sua próxima missão em menos de um minuto.
- Não seja necessário navegar entre páginas para iniciar os estudos.
- O progresso da jornada possa ser acompanhado de forma intuitiva.

---

# 10. Considerações Finais

O Dashboard representa a principal interface do Operation Backend.

Seu objetivo é reduzir o tempo gasto com organização e maximizar o tempo dedicado ao aprendizado.

Toda sessão de estudo deverá começar e terminar por esta página.