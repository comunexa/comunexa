# Documento 003 — Mapa Funcional do Produto

**Categoria:** Produto  
**Versão:** 1.0  
**Status:** Aprovado  
**Última atualização:** 13/07/2026  
**Responsável:** Elberth Moraes

---

> Este documento organiza as funcionalidades do Comunexa Escola de forma evolutiva.

Seu objetivo é orientar o desenvolvimento do produto, agrupando funcionalidades por módulos e permitindo que a plataforma cresça de maneira consistente, incremental e priorizada.

Cada funcionalidade deve gerar valor para pelo menos uma persona do sistema.

---

# Objetivo

Definir a estrutura funcional do produto e organizar sua evolução ao longo das próximas versões.

Este documento servirá como referência para:

- planejamento das sprints;
- definição do backlog;
- priorização de funcionalidades;
- evolução da arquitetura.

---

# Visão Geral

```text
Comunexa Escola

├── Comunicação
├── Publicação
├── WhatsApp
├── Consulta
├── Calendário
├── Arquivos
├── Usuários
├── Escola
├── Pessoas
├── Administração
└── Inteligência Artificial (Futuro)
```

---

# Módulo 01 — Comunicação

**Objetivo**

Permitir que a escola publique informações oficiais.

### Funcionalidades

- Publicar comunicado
- Publicar tarefa
- Publicar prova
- Publicar evento
- Publicar reunião
- Publicar passeio
- Publicar comunicado financeiro

---

# Módulo 02 — Publicação

**Objetivo**

Disponibilizar as informações aos responsáveis de forma organizada.

### Funcionalidades

- Página pública
- Link permanente
- Atualização da publicação
- Histórico de alterações
- Compartilhamento

---

# Módulo 03 — WhatsApp

**Objetivo**

Facilitar a divulgação sem substituir o WhatsApp.

### Funcionalidades

- Gerar mensagem para WhatsApp
- Copiar mensagem
- Gerar QR Code
- Link curto

---

# Módulo 04 — Consulta

**Objetivo**

Facilitar a localização das informações.

### Funcionalidades

- Buscar publicação
- Filtrar por turma
- Filtrar por disciplina
- Filtrar por tipo
- Ordenação por data

---

# Módulo 05 — Calendário

**Objetivo**

Organizar eventos e atividades escolares.

### Funcionalidades

- Calendário
- Próximas provas
- Próximas tarefas
- Próximos eventos
- Linha do tempo

---

# Módulo 06 — Arquivos

**Objetivo**

Organizar documentos relacionados às publicações.

### Funcionalidades

- Upload
- Download
- Visualização
- Organização por publicação

---

# Módulo 07 — Usuários

**Objetivo**

Controlar autenticação e acesso ao sistema.

### Funcionalidades

- Login
- Logout
- Recuperação de senha
- Perfil
- Alteração de senha

> **Observação:** este módulo não faz parte do MVP inicial e será implementado posteriormente.

---

# Módulo 08 — Escola

**Objetivo**

Representar a estrutura organizacional da instituição.

### Funcionalidades

- Escola
- Unidade
- Ano letivo
- Série
- Turma
- Disciplina

---

# Módulo 09 — Pessoas

**Objetivo**

Organizar os usuários vinculados à escola.

### Funcionalidades

- Professores
- Coordenadores
- Secretaria
- Responsáveis
- Alunos

---

# Módulo 10 — Administração

**Objetivo**

Administrar o ambiente da escola.

### Funcionalidades

- Configurações
- Auditoria
- Permissões
- Templates
- Backup

---

# Módulo 11 — Inteligência Artificial

**Objetivo**

Auxiliar professores e gestores na criação e organização da comunicação.

### Funcionalidades previstas

- Gerar resumo automático
- Criar mensagem para WhatsApp
- Melhorar textos
- Sugerir categorias
- Responder dúvidas
- Assistente escolar

---

# MVP

A primeira versão do Comunexa Escola deverá conter apenas as funcionalidades necessárias para validar o produto.

## Comunicação

- ✔ Publicar comunicado
- ✔ Publicar prova
- ✔ Publicar tarefa

## Publicação

- ✔ Página pública
- ✔ Link permanente

## WhatsApp

- ✔ Gerar mensagem para WhatsApp

## Consulta

- ✔ Consulta por turma

Todo o restante permanecerá registrado neste documento e será priorizado futuramente conforme o Roadmap do produto.

---

# Critérios para Evolução

Uma funcionalidade somente deverá entrar em desenvolvimento quando:

- resolver um problema real;
- gerar valor para pelo menos uma persona;
- puder ser entregue em uma sprint;
- estiver alinhada com a Visão do Produto;
- possuir critérios claros de homologação;
- contribuir para a simplicidade do sistema.

---

# Princípios

- O produto deve crescer de forma incremental.
- O MVP deve permanecer o menor possível.
- Funcionalidades futuras não devem aumentar a complexidade do MVP.
- Simplicidade é mais importante do que quantidade de recursos.
- Todo módulo deve possuir um objetivo claro.

---

# Observações

Este documento representa o mapa funcional da primeira geração do Comunexa Escola.

Novos módulos poderão surgir conforme a plataforma evoluir para outros segmentos, como empresas, condomínios, igrejas e associações.

---

# Documentos Relacionados

- Documento 001 — Visão do Produto
- Documento 002 — Personas
- Documento 004 — Requisitos Funcionais
- Documento 006 — MVP
- Documento 007 — Roadmap

---
