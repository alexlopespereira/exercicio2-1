# Transcript da sessão `/grill-me` — Mapa de Atores do SD (canal telefônico)

> Sessão de destilação da pesquisa adversária (v3) em um mapa de atores decidido.
> Cada rodada = uma pergunta do agente (com recomendação) + a decisão do aluno.
> Produto: `C_mapa_atores.md`.

---

## Rodada 1 — Passo 0: Propósito do mapa

**Pergunta:** Qual é O propósito que o mapa vai endereçar? O v3 oferece candidatos
(H1–H6). Opções: (a) demanda falha do canal telefônico [recomendado], (b) opacidade
do operador da URA 158, (c) exclusão digital/equidade, (d) judicialização.

**Decisão:** **(a) Demanda falha do canal telefônico** — a bipartição 158
(MTE/concessão) ↔ 0800 726 0207 (Caixa/pagamento), com o handoff feito pelo próprio
cidadão. É o achado mais "journey-native"; os demais viram lentes secundárias.

---

## Rodada 2 — Altitude / escopo da jornada

**Pergunta:** Quanto do ecossistema multicanal entra como ator detalhado vs.
fronteira? Opções: (a) telefônico-cêntrico (158+0800 focais) [recomendado],
(b) multicanal pleno, (c) só a perna telefônica sem retaguarda.

**Decisão:** **(a) Telefônico-cêntrico com retaguarda.** Atores detalhados = fluxo
telefônico + retaguarda que gera o motivo de ligar (Dataprev, MTE-concessão,
Caixa-pagamento). App CTPS / gov.br / SINE = nós de fronteira.

---

## Rodada 3 — Sistemas automatizados como atores

**Pergunta:** Sistemas automatizados entram como atores distintos ou são dobrados
nos operadores? Opções: (a) URA + motor BGSD/Dataprev como atores [recomendado],
(b) só a URA/IVR, (c) nenhum.

**Decisão:** **(a) URA/IVR 158 + motor CNIS-CAGED-BGSD como atores.** A URA é o
beco-sem-saída ("todos os atendentes ocupados"); o motor BGSD gera a notificação
imprópria. gov.br/SERPRO fica como sistema de fronteira (identidade).

---

## Rodada 4 — Esquema de categorização

**Pergunta:** Qual taxonomia de categoria os atores usam? Opções: (a) 7 categorias
da aula02 + 'Sistema', (b) taxonomia fina do v3, (c) dois eixos categoria × palco.

**Decisão:** **(c) Dois eixos — categoria (aula02 + Sistema) × palco
(frontstage / backstage / governança).** Estilo service blueprint: separa quem o
cidadão vê de quem age nos bastidores.

---

## Rodada 5 — Formato do artefato

**Pergunta:** RACI, mermaid + tabela, ou ambos? Opções: (a) mermaid + tabela,
(b) RACI pura, (c) ambos.

**Decisão:** **(c) Ambos** — mermaid para as relações/handoffs e tabela RACI para
responsabilidades por etapa, mantidos coerentes (mesmo conjunto de atores).

---

## Rodada 6 — Roster: atores de fronteira/upstream

**Pergunta:** Além do core de 9, quais atores de fronteira/upstream entram?
(multi-seleção) Empregador+contador (e-Social), SINE/SRTE, TCU, Centrais sindicais.

**Decisão:** **Incluir empregador+contador (e-Social), SINE/SRTE presencial e TCU.**
Centrais sindicais vão só para a seção Vozes Críticas. Roster final = 12 atores.

---

## Rodada 7 — Tipos de relação no diagrama

**Pergunta:** Que relações o mermaid codifica? Opções: (a) jornada + handoffs +
fluxo de dados [recomendado], (b) só jornada + handoffs, (c) todos os fluxos.

**Decisão:** **(a) Jornada + handoffs + fluxo de dados a montante**, com governança
(CODEFAT normatiza, TCU audita) como setas tracejadas. O handoff 158→Caixa em
vermelho ('feito pelo cidadão'); URA→SINE como beco-sem-saída.

---

## Rodada 8 — Passo 5: hipóteses de diagnóstico

**Pergunta:** Quais hipóteses o mapa carrega? Opções: (a) H1 + H2/H3/H6 [recomendado],
(b) só H1, (c) todas as 6.

**Decisão:** **(a) H1 (central) + H2 (opacidade BPO 158) + H3 (MTE-Dataprev = ponto
único de falha) + H6 (exclusão digital).** H4/H5 viram nota "fora de escopo".

---

## Rodada 9 — Vozes críticas

**Pergunta:** Como tratar as vozes críticas? Opções: (a) seção dedicada + a lacuna
como achado [recomendado], (b) como atores no mapa, (c) só TCU sem seção.

**Decisão:** **(a) Seção dedicada** — TCU, Reclame Aqui, Ipea TD 3059 — e explicitar
a lacuna: nenhuma org de controle social digital cobre a URA 158 (a ausência é, ela
mesma, um achado que reforça H2).

---

## Síntese — entendimento compartilhado

- **Propósito:** demanda falha do canal telefônico (bipartição 158↔0800).
- **Altitude:** telefônico-cêntrico + retaguarda; canais digitais = fronteira.
- **12 atores** em eixo categoria × palco; sistemas (URA, BGSD) são atores.
- **Formato:** mermaid (3 camadas) + RACI por etapa.
- **Hipóteses:** H1 + H2 + H3 + H6.
- **Vozes críticas:** seção dedicada + lacuna de controle social como achado.

> **Atores nomeados nesta sessão** (consistência transcript ↔ mapa): cidadão,
> URA/IVR 158, atendente humano 158, empresa BPO/operadora do 158, Ouvidoria-Geral
> do MTE, MTE-concessão (SPT/DGB/Coord-Geral SD), Dataprev + motor BGSD, Caixa
> 0800/agente pagador, CODEFAT, empregador + contador (e-Social), SINE/SRTE, TCU.

---

## Pendências em aberto (não decididas nesta sessão)

1. **Render do mermaid.** O diagrama usa `linkStyle 6` e `7` (índice por ordem das
   arestas) para colorir os handoffs em vermelho. Se a ordem das arestas mudar, os
   índices apontam para a aresta errada. *Pendente:* validar a renderização antes de
   circular. **Status:** em aberto.
2. **Empregador vs. contador.** Hoje são uma única linha (ator 10). A aula02 (Passo 1)
   sugere destrinchar sub-grupos com incentivos distintos — empregador (origem do
   dado) vs. contador (intermediário que lança o e-Social). *Pendente:* separar em
   dois atores (roster passaria a 13) ou manter consolidado. **Status:** em aberto.

> **Confiança declarada (Feynman):** alta na estrutura e aderência à aula02/rubrica;
> **média** nas células RACI por etapa (E1–E7) — são inferência do arranjo descrito
> no v3, não há documento que formalize "quem é A na etapa E5".
