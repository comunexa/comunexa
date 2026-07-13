# Documento 006 — Modelo de Domínio

**Categoria:** Produto  
**Versão:** 1.0  
**Status:** Aprovado  
**Última atualização:** 13/07/2026  
**Responsável:** Elberth Moraes

---

> Este documento define o modelo de domínio do **Comunexa Escola**.

Seu objetivo é identificar os principais conceitos do negócio e a relação entre eles, servindo como base para a modelagem do banco de dados, APIs e arquitetura do sistema.

Este documento descreve **o negócio**, não a tecnologia.

---

# Objetivo

Representar os principais elementos do domínio do produto e como eles se relacionam.

O modelo de domínio deverá orientar:

- modelagem do banco de dados;
- definição das APIs;
- arquitetura do backend;
- arquitetura do frontend;
- regras de negócio;
- evolução da plataforma.

---

# Visão Geral

```text
Escola

│

├── Usuários

├── Turmas

│      │

│      └── Publicações

│               │

│               ├── Página Pública

│               ├── Mensagem WhatsApp

│               ├── Anexos

│               └── Histórico

│

└── Calendário
```

---

# Escola

Representa a instituição responsável pela comunicação.

Uma escola possui:

- usuários;
- turmas;
- disciplinas;
- publicações;
- calendário.

A escola é o principal contexto organizacional da plataforma.

---

# Usuário

Representa qualquer pessoa autenticada no sistema.

## Tipos previstos

- Administrador
- Coordenação
- Professor
- Secretaria

## Evolução futura

- Responsável
- Aluno

Todo usuário pertence a uma única escola.

---

# Turma

Representa um grupo de alunos.

Cada turma possui:

- série;
- ano letivo;
- professores;
- publicações.

Uma turma pertence a apenas uma escola.

---

# Publicação

A publicação é a entidade central do Comunexa Escola.

Toda informação oficial registrada pela escola será representada por uma publicação.

## Tipos

- Comunicado
- Prova
- Tarefa
- Evento
- Passeio
- Financeiro
- Reunião

## Atributos principais

- título;
- resumo;
- descrição;
- autor;
- data de criação;
- data da última atualização;
- tipo;
- turma;
- anexos;
- status (Rascunho ou Publicado).

---

# Anexo

Representa qualquer arquivo associado a uma publicação.

## Tipos previstos

- PDF
- Imagem
- Documento
- Planilha
- Apresentação

Uma publicação poderá possuir zero ou vários anexos.

---

# Página Pública

Representa a visualização oficial de uma publicação.

Características:

- URL permanente;
- acesso público;
- compartilhável;
- atualizada automaticamente quando a publicação é alterada.

---

# Mensagem para WhatsApp

Representa o resumo utilizado para divulgação.

Cada mensagem contém:

- emoji;
- título;
- resumo;
- link permanente.

A mensagem nunca substitui a publicação.

Seu objetivo é apenas divulgar sua existência.

---

# Calendário

Agrupa eventos importantes da escola.

Exemplos:

- provas;
- tarefas;
- passeios;
- reuniões;
- eventos institucionais.

O calendário será construído automaticamente a partir das publicações.

---

# Linha do Tempo

Representa a visão cronológica das publicações.

Permite filtros por:

- turma;
- disciplina;
- tipo;
- período.

---

# Relacionamentos

```text
Escola

├── Usuários

├── Turmas

│      └── Publicações

│              ├── Anexos

│              ├── Página Pública

│              └── Mensagem WhatsApp

└── Calendário
```

Regras:

- Uma Escola possui vários Usuários.
- Uma Escola possui várias Turmas.
- Uma Turma possui várias Publicações.
- Uma Publicação pertence a apenas uma Turma.
- Uma Publicação possui um Autor.
- Uma Publicação pode possuir vários Anexos.
- Uma Publicação gera uma Página Pública.
- Uma Publicação gera uma Mensagem para WhatsApp.

---

# Entidade Central

A entidade central do sistema é **Publicação**.

Todas as funcionalidades do produto deverão, direta ou indiretamente, estar relacionadas a uma publicação.

Essa decisão reduz a complexidade do sistema, facilita a evolução da plataforma e mantém a comunicação como elemento central do negócio.

---

# Evolução Esperada

Após a validação do Comunexa Escola, novas entidades poderão ser incorporadas ao domínio.

Exemplos:

- Agenda do Aluno;
- Responsável;
- Aluno;
- Notificações;
- Comentários;
- Confirmação de leitura;
- Inteligência Artificial;
- Integrações com sistemas escolares.

Essas entidades deverão respeitar o princípio de simplicidade definido na Visão do Produto.

---

# Princípios do Modelo de Domínio

- A Publicação é o núcleo do sistema.
- Toda comunicação oficial nasce de uma Publicação.
- O WhatsApp apenas divulga uma Publicação.
- O domínio deve permanecer simples.
- O modelo deve evoluir sem quebrar funcionalidades existentes.

---

# Documentos Relacionados

- Documento 001 — Visão do Produto
- Documento 002 — Personas
- Documento 003 — Mapa Funcional
- Documento 004 — Regras de Negócio
- Documento 005 — Backlog do Produto

---
