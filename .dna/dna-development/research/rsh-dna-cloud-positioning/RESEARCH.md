---
apiVersion: github.com/ruinosus/dna/sdlc/v1
kind: Research
metadata:
  name: rsh-dna-cloud-positioning
spec:
  title: DNA Cloud — posicionamento de mercado (memory layer · vendor-neutral · willingness-to-pay)
  status: published
  objective: Validar com evidência o posicionamento, ICP e sanidade de preço do DNA Cloud como camada
    de IA vendor-neutral + memória portátil que o usuário é dono.
  methodology: web-search-curated
  executive_summary: |
    O posicionamento "memória de IA portátil, vendor-neutral e do usuário, servida por MCP" NÃO é oceano azul — já é categoria disputada: Mnemoverse, MemoryLake e o Open Memory Protocol shipam o pitch quase idêntico ("escreve 1x, recupera em Claude/ChatGPT/Cursor"), vários open-source/self-hostable; e a camada de memory-infra (Mem0, Letta, Zep, Cognee) já é Apache-2.0 open-core. PORÉM o GAP que valida a tese é REAL: os incumbentes (ChatGPT/Claude/Copilot) mantêm memória SILADA por fornecedor — preferências/skills não transferem entre ferramentas. O diferenciador real do DNA Cloud é o SEGUNDO pilar (DEFINITIONS — agents/skills compostos ao vivo por MCP), que os rivais só-de-memória NÃO têm. Preço: $29/mês Pro é sensato (dev-tools individuais ancoram $10-20 entrada / $60-200 premium; memory APIs tipo Mem0 $19-249). Demanda pagante mais forte no nível TIME/ORG (OpenAI: 1M+ clientes business, 7M+ seats ChatGPT-for-Work), mesmo com PLG bottom-up puxando power-users solo primeiro. Ponto FRACO: a MOAT — memória portátil via MCP é largamente commodity (open-core + MCP virando padrão). Defensabilidade tem que vir do pilar DEFINITIONS + lock-in de dado (memória acumulada) + distribuição — não da portabilidade de memória sozinha.
  findings:
  - id: f-memory-crowded
    title: O pilar Memory já é campo lotado — Mnemoverse, MemoryLake, Open Memory Protocol shipam o MESMO
      pitch (vários open-source)
    evidence_rating: evidence-based
  - id: f-infra-commodity
    title: A infra de memória já é open-core/self-hostable (Mem0/Letta/Cognee Apache-2.0) — 'ownership/self-host'
      não é diferencial único
    evidence_rating: evidence-based
  - id: f-gap-real
    title: 'O gap cross-tool É real e aberto: incumbentes silam memória por fornecedor; skills/prefs não
      transferem'
    evidence_rating: evidence-based
  - id: f-definitions-edge
    title: O diferenciador real do DNA Cloud é o 2º pilar (Definitions/agents ao vivo por MCP) — nenhum
      rival só-de-memória oferece
    evidence_rating: evidence-based
  - id: f-pricing-team
    title: $29/mo Pro é sensato; demanda pagante mais forte em time/org (não solo)
    evidence_rating: evidence-based
  - id: f-moat-weak
    title: Moat de memória portátil é FRACA (commodity + MCP padrão) — defensabilidade vem de Definitions
      + lock-in de dado + distribuição
    evidence_rating: evidence-based
  recommendations:
  - id: rec-lead-definitions
    priority: high
    summary: NÃO liderar com 'memória portátil' (categoria lotada). Liderar com a COMBINAÇÃO agents-ao-vivo
      (Definitions) + memória — o que os rivais só-de-memória não fazem.
  - id: rec-team-icp
    priority: high
    summary: ICP pagante = time/org (anti-lock-in + camada compartilhada), com PLG solo como funil de
      entrada.
  - id: rec-moat
    priority: high
    summary: Construir moat via Definitions + lock-in do dado acumulado (memória+contexto) + distribuição
      — não apostar na portabilidade de memória como moat.
  - id: rec-pricing-ok
    priority: medium
    summary: $29 Pro validado; desenhar tier de TIME (seats) como o motor de receita.
  created_at: '2026-07-12T12:35:35+00:00'
  updated_at: '2026-07-12T12:35:35+00:00'
---

# Research — DNA Cloud — posicionamento de mercado (memory layer · vendor-neutral · willingness-to-pay)

Methodology: web-search-curated · 0 sources · 6 findings.

This file's spec (frontmatter above) is the authoritative data. The prose below is for human reading and is regenerated on each write. Edit via `dna research` CLI or the Studio viewer; raw frontmatter edits are also supported.
