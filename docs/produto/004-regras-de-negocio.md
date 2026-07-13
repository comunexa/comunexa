# Documento 004 — Regras de Negócio

**Categoria:** Produto  
**Versão:** 1.0  
**Status:** Aprovado  
**Última atualização:** 13/07/2026  
**Responsável:** Elberth Moraes

---

> Este documento define as regras de negócio que deverão ser respeitadas pelo Comunexa Escola, independentemente da tecnologia utilizada ou da interface implementada.

As regras de negócio representam o comportamento esperado do produto e servem como referência para desenvolvimento, testes e homologação.

---

# Objetivo

Garantir que todas as implementações do sistema respeitem os princípios do produto, mantendo um comportamento consistente ao longo da evolução da plataforma.

As regras descritas neste documento são independentes de telas, APIs ou tecnologias.

---

# Visão Geral

```text
Produto

        ↓

Regras de Negócio

        ↓

Implementação

        ↓

Testes

        ↓

Homologação
```

Toda funcionalidade desenvolvida deverá respeitar estas regras.

---

# Comunicação

## RN-001

Toda informação oficial da escola deverá ser cadastrada no sistema antes de ser divulgada.

---

## RN-002

Nenhuma informação oficial deverá existir apenas no WhatsApp.

---

## RN-003

O WhatsApp será utilizado apenas como canal de divulgação.

---

## RN-004

Toda publicação deverá possuir uma página própria.

---

## RN-005

Toda publicação deverá possuir um link permanente.

---

## RN-006

Uma publicação poderá ser atualizada sem alteração do seu link.

---

# Escola

## RN-007

Toda publicação pertence obrigatoriamente a uma escola.

---

## RN-008

Toda publicação deverá estar vinculada a uma turma.

---

## RN-009

Uma turma pertence a apenas uma escola.

---

# Usuários

## RN-010

Toda publicação deverá possuir um autor responsável.

---

## RN-011

Somente usuários autenticados poderão criar ou alterar publicações.

---

## RN-012

Usuários autenticados visualizarão apenas informações pertencentes à própria escola.

---

# Publicações

## RN-013

Toda publicação deverá possuir um tipo.

Tipos previstos:

- Comunicado
- Prova
- Tarefa
- Evento
- Passeio
- Financeiro
- Reunião

---

## RN-014

Toda publicação deverá possuir data de criação.

---

## RN-015

Toda alteração deverá registrar a data da última atualização.

---

## RN-016

Uma publicação poderá possuir anexos.

---

## RN-017

Uma publicação poderá permanecer em rascunho até sua publicação.

---

# WhatsApp

## RN-018

Toda publicação poderá gerar automaticamente uma mensagem resumida para WhatsApp.

---

## RN-019

Toda mensagem gerada deverá conter o link oficial da publicação.

---

## RN-020

O conteúdo completo permanecerá disponível apenas no portal da Comunexa.

---

# Consulta

## RN-021

Publicações deverão poder ser consultadas por turma.

---

## RN-022

Publicações poderão ser filtradas por tipo.

---

## RN-023

Publicações poderão ser ordenadas por data.

---

## RN-024

As informações públicas não exigirão autenticação.

---

# Auditoria

## RN-025

Toda publicação deverá registrar sua data de criação.

---

## RN-026

Toda alteração deverá registrar:

- usuário responsável;
- data;
- horário;
- versão da publicação.

---

# Produto

## RN-027

A simplicidade terá prioridade sobre novas funcionalidades.

---

## RN-028

Nenhuma funcionalidade deverá aumentar o trabalho do professor.

---

## RN-029

Toda funcionalidade deverá gerar valor para pelo menos uma persona.

---

## RN-030

Sempre que possível, o sistema deverá reduzir a quantidade de mensagens enviadas no WhatsApp.

---

## RN-031

O sistema deverá adaptar-se ao processo da escola sempre que possível.

---

## RN-032

Nenhuma funcionalidade deverá existir apenas por questões técnicas; toda implementação deverá resolver um problema real do usuário.

---

# Diretrizes para Desenvolvimento

Ao implementar qualquer funcionalidade, a equipe deverá verificar:

- Todas as regras deste documento estão sendo respeitadas?
- Existe alguma regra impactada pela alteração?
- A nova funcionalidade exige a criação de uma nova regra de negócio?
- Existe algum teste validando esta regra?

---

# Observações

As regras de negócio representam a essência do produto.

Mudanças neste documento deverão ocorrer apenas quando houver alteração no comportamento esperado da plataforma.

Mudanças de interface, arquitetura ou tecnologia não alteram as regras de negócio.

---

# Documentos Relacionados

- Documento 001 — Visão do Produto
- Documento 002 — Personas
- Documento 003 — Mapa Funcional
- Documento 005 — Requisitos Funcionais
- Documento 006 — Requisitos Não Funcionais

---
