# Documento 011 — Jornada do Usuário

**Categoria:** Produto  
**Versão:** 1.0  
**Status:** Aprovado  
**Última atualização:** 13/07/2026  
**Responsável:** Elberth Moraes

---

> Este documento descreve as principais jornadas dos usuários do **Comunexa Escola**.

Seu objetivo é representar como as pessoas interagem com a plataforma, desde a criação de uma publicação até sua consulta pelos responsáveis.

As jornadas descritas neste documento deverão orientar o desenvolvimento da interface, da experiência do usuário (UX) e dos testes de homologação.

---

# Objetivo

Garantir que o sistema seja simples de utilizar, intuitivo e eficiente para todos os seus usuários.

Cada jornada representa um fluxo completo de utilização do produto.

---

# Visão Geral

```text
Professor

↓

Cria Publicação

↓

Comunexa organiza

↓

WhatsApp divulga

↓

Responsável consulta

↓

Informação permanece disponível
```

Essa é a principal jornada do Comunexa Escola.

---

# Jornada 01 — Publicar um Comunicado

## Ator

Professor, Coordenação ou Secretaria.

---

## Objetivo

Publicar uma informação oficial da escola.

---

## Fluxo

1. Realiza login.
2. Seleciona **Nova Publicação**.
3. Escolhe o tipo da publicação.
4. Preenche as informações.
5. Anexa arquivos (opcional).
6. Salva a publicação.
7. O sistema gera automaticamente:
   - página pública;
   - link permanente;
   - mensagem resumida para WhatsApp.
8. O usuário copia a mensagem.
9. Compartilha no grupo da turma.

---

## Resultado Esperado

Os responsáveis recebem uma mensagem curta contendo um link para a publicação oficial.

---

# Jornada 02 — Consultar um Comunicado

## Ator

Responsável.

---

## Objetivo

Consultar uma informação enviada pela escola.

---

## Fluxo

1. Recebe a mensagem no WhatsApp.
2. Clica no link.
3. Visualiza a publicação.
4. Consulta anexos (quando existirem).
5. Compartilha o link, se necessário.

---

## Resultado Esperado

O responsável encontra rapidamente todas as informações sem depender do histórico do WhatsApp.

---

# Jornada 03 — Atualizar uma Publicação

## Ator

Professor ou Coordenação.

---

## Objetivo

Corrigir ou complementar uma publicação existente.

---

## Fluxo

1. Localiza a publicação.
2. Realiza a edição.
3. Salva as alterações.
4. O sistema atualiza automaticamente a página pública.
5. O link permanece inalterado.

---

## Resultado Esperado

Todos os responsáveis continuam utilizando o mesmo endereço para acessar a informação atualizada.

---

# Jornada 04 — Encontrar uma Publicação Antiga

## Ator

Responsável.

---

## Objetivo

Localizar rapidamente uma informação publicada anteriormente.

---

## Fluxo

1. Acessa o portal.
2. Seleciona a turma.
3. Utiliza filtros.
4. Localiza a publicação desejada.

---

## Resultado Esperado

Nenhuma informação importante se perde com o tempo.

---

# Jornada 05 — Consultar o Calendário Escolar

## Ator

Responsável.

---

## Objetivo

Visualizar eventos importantes da turma.

---

## Fluxo

1. Acessa o calendário.
2. Visualiza provas, tarefas e eventos.
3. Seleciona um item.
4. Acessa a publicação correspondente.

---

## Resultado Esperado

O responsável consegue acompanhar a rotina escolar sem depender de mensagens recentes.

---

# Características das Jornadas

Todas as jornadas deverão seguir os seguintes princípios:

- poucos passos;
- linguagem simples;
- interface intuitiva;
- baixo tempo de execução;
- mínimo retrabalho;
- experiência consistente.

Sempre que uma jornada se tornar complexa, ela deverá ser revisada antes da implementação.

---

# Princípios de Experiência do Usuário

A Comunexa deverá proporcionar uma experiência baseada em cinco pilares:

- simplicidade;
- organização;
- rapidez;
- clareza;
- confiança.

Esses princípios deverão orientar todas as telas da plataforma.

---

# Observações

As jornadas descritas representam a primeira versão do Comunexa Escola.

Novas jornadas serão adicionadas à medida que novos módulos forem incorporados ao produto.

---

# Documentos Relacionados

- Documento 001 — Visão do Produto
- Documento 002 — Personas
- Documento 003 — Mapa Funcional
- Documento 004 — Regras de Negócio
- Documento 006 — Modelo de Domínio
- Documento 008 — Roadmap Estratégico do Produto

---
