# Documento 005 — Backlog do Produto

**Categoria:** Produto  
**Versão:** 1.0  
**Status:** Aprovado  
**Última atualização:** 13/07/2026  
**Responsável:** Elberth Moraes

---

> Este documento organiza o backlog oficial do Comunexa Escola.

Seu objetivo é registrar todas as funcionalidades previstas para o produto, mantendo uma ordem de prioridade alinhada à estratégia da Comunexa.

Cada item do backlog representa uma entrega de valor para pelo menos uma persona do sistema.

---

# Objetivo

Organizar as funcionalidades do produto em ordem de prioridade, permitindo que o desenvolvimento aconteça de forma incremental, simples e sustentável.

O backlog é um documento vivo e poderá ser reorganizado sempre que necessário.

---

# Organização do Backlog

Cada funcionalidade deverá possuir:

- Identificador único;
- Nome;
- Objetivo;
- Prioridade;
- Status;
- Critérios de aceite;
- Persona beneficiada;
- Módulo relacionado.

---

# Backlog Inicial

## EP001 — Publicar Comunicado

**Objetivo**

Permitir que a escola publique um comunicado oficial.

**Módulo**

Comunicação

**Persona**

Professor, Coordenação e Secretaria.

**Prioridade**

⭐⭐⭐⭐⭐ Muito Alta

**Status**

Não iniciado

**Critérios de Aceite**

- O usuário consegue cadastrar um comunicado.
- O comunicado é salvo.
- O comunicado fica disponível para publicação.

---

## EP002 — Página Pública

**Objetivo**

Disponibilizar uma página pública para cada comunicado.

**Módulo**

Publicação

**Persona**

Responsável.

**Prioridade**

⭐⭐⭐⭐⭐ Muito Alta

**Status**

Não iniciado

**Critérios de Aceite**

- O comunicado possui URL própria.
- A página pode ser acessada sem autenticação.

---

## EP003 — Mensagem para WhatsApp

**Objetivo**

Gerar automaticamente uma mensagem resumida para divulgação.

**Módulo**

WhatsApp

**Persona**

Professor, Coordenação e Secretaria.

**Prioridade**

⭐⭐⭐⭐⭐ Muito Alta

**Status**

Não iniciado

**Critérios de Aceite**

- O sistema gera uma mensagem pronta para copiar.
- A mensagem contém o link da publicação.

---

## EP004 — Publicar Prova

**Objetivo**

Cadastrar avaliações.

**Módulo**

Comunicação

**Persona**

Professor.

**Prioridade**

⭐⭐⭐⭐ Alta

**Status**

Não iniciado

**Critérios de Aceite**

- Permite informar disciplina.
- Permite informar data.
- Permite informar conteúdo.

---

## EP005 — Publicar Tarefa

**Objetivo**

Cadastrar tarefas escolares.

**Módulo**

Comunicação

**Persona**

Professor.

**Prioridade**

⭐⭐⭐⭐ Alta

**Status**

Não iniciado

**Critérios de Aceite**

- O professor consegue cadastrar uma tarefa.
- A tarefa fica disponível para consulta.

---

## EP006 — Consulta por Turma

**Objetivo**

Permitir que responsáveis encontrem rapidamente as informações.

**Módulo**

Consulta

**Persona**

Responsável.

**Prioridade**

⭐⭐⭐⭐ Alta

**Status**

Não iniciado

**Critérios de Aceite**

- O sistema permite filtrar por turma.
- Apenas informações da turma são apresentadas.

---

## EP007 — Atualizar Publicação

**Objetivo**

Editar informações mantendo o mesmo link.

**Módulo**

Publicação

**Persona**

Professor e Coordenação.

**Prioridade**

⭐⭐⭐⭐ Alta

**Status**

Não iniciado

**Critérios de Aceite**

- O usuário consegue editar uma publicação.
- O link permanece inalterado.
- O histórico registra a alteração.

---

## EP008 — Arquivos

**Objetivo**

Permitir anexar documentos às publicações.

**Módulo**

Arquivos

**Persona**

Professor e Secretaria.

**Prioridade**

⭐⭐⭐ Média

**Status**

Não iniciado

---

## EP009 — Calendário

**Objetivo**

Organizar provas, eventos e tarefas em uma visão cronológica.

**Módulo**

Calendário

**Persona**

Responsáveis.

**Prioridade**

⭐⭐⭐ Média

**Status**

Não iniciado

---

## EP010 — Login

**Objetivo**

Permitir acesso seguro ao sistema.

**Módulo**

Usuários

**Persona**

Todos os usuários internos.

**Prioridade**

⭐⭐⭐ Média

**Status**

Não iniciado

---

# Fluxo das Funcionalidades

Cada funcionalidade deverá passar pelos seguintes estados:

```text
Não iniciada

↓

Refinamento

↓

Pronta para Desenvolvimento

↓

Em Desenvolvimento

↓

Desenvolvimento Concluído

↓

Em Homologação

↓

Homologada

↓

Publicada
```

Nenhuma funcionalidade poderá ser publicada sem aprovação da Product Owner.

---

# Papel da Product Owner

A Product Owner será responsável por:

- definir prioridades;
- detalhar funcionalidades;
- esclarecer dúvidas da equipe;
- validar critérios de aceite;
- homologar entregas;
- aprovar publicações;
- reorganizar o backlog sempre que necessário.

A equipe de desenvolvimento será responsável pela implementação técnica das funcionalidades aprovadas.

---

# Critérios para Entrada no Backlog

Uma funcionalidade somente poderá entrar no backlog quando responder claramente às seguintes perguntas:

- Qual problema resolve?
- Quem será beneficiado?
- Qual valor entrega?
- Como será homologada?
- Está alinhada com a Visão do Produto?
- Está alinhada às Personas?
- Existe alguma regra de negócio relacionada?

Caso alguma dessas respostas não esteja clara, a funcionalidade deverá permanecer em estudo.

---

# Princípios

- O backlog é dinâmico.
- A prioridade pode mudar conforme a validação do produto.
- O MVP deve permanecer pequeno.
- Funcionalidades somente entram em desenvolvimento quando estiverem refinadas.
- O backlog deve refletir a estratégia do produto e não apenas demandas pontuais.

---

# Documentos Relacionados

- Documento 001 — Visão do Produto
- Documento 002 — Personas
- Documento 003 — Mapa Funcional
- Documento 004 — Regras de Negócio
- Documento 006 — Requisitos Funcionais

---
