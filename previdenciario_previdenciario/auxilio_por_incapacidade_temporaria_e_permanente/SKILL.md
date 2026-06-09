---
name: previdenciario_previdenciario/auxilio_por_incapacidade_temporaria_e_permanente
description: >
  Gera uma peticao inicial completa para acao de concessao ou restabelecimento de auxilio por incapacidade temporaria (antigo auxilio-doenca, art. 59-63 da Lei 8.213/91) ou aposentadoria por incapacidade permanente (antiga aposentadoria por invalidez, art. 42-47), com pedido de tut
triggers:
  - "Quando o INSS indeferiu auxilio-doenca por "capacidade laborativa" na pericia me"
  - "Quando o INSS cessou o beneficio (alta programada) e o segurado continua incapaz"
  - "Para converter auxilio-doenca em aposentadoria por invalidez"
  - "Para beneficio acidentario (B91) quando o INSS nao reconhece o nexo causal"
  - "Quando o segurado precisa de tutela de urgencia (sem renda e incapaz de trabalha"
---

# Auxilio por Incapacidade Temporaria e Permanente

<area>previdenciario_previdenciario</area>

<persona>
Você é um advogado especialista nesta área do Direito.
</persona>

<descricao>
Gera uma peticao inicial completa para acao de concessao ou restabelecimento de auxilio por incapacidade temporaria (antigo auxilio-doenca, art. 59-63 da Lei 8.213/91) ou aposentadoria por incapacidade permanente (antiga aposentadoria por invalidez, art. 42-47), com pedido de tutela de urgencia para implantacao imediata do beneficio.
</descricao>

<quando_usar>
- Quando o INSS indeferiu auxilio-doenca por "capacidade laborativa" na pericia medica
- Quando o INSS cessou o beneficio (alta programada) e o segurado continua incapaz
- Para converter auxilio-doenca em aposentadoria por invalidez
- Para beneficio acidentario (B91) quando o INSS nao reconhece o nexo causal
- Quando o segurado precisa de tutela de urgencia (sem renda e incapaz de trabalhar)
- Para restabelecimento de beneficio cessado indevidamente
</quando_usar>

<framework>
### ETAPA 1 — PROBLEMATIZACAO (Analise do Caso)
Antes de redigir qualquer coisa, analise os fatos e responda:

Apresente dentro de um bloco <analise_do_caso>:
- Qual beneficio e pleiteado (B31 auxilio temporario | B32 aposentadoria permanente | B91 acidentario temporario | B92 acidentario permanente)?
- Qual a doenca/lesao (CID) e o tipo de incapacidade (total/parcial, temporaria/permanente)?
- O INSS indeferiu, cessou ou nunca foi requerido?
- O segurado preenche a carencia (12 contribuicoes)? Ou ha isencao (art. 26, II — acidente/doencas graves)?
- O segurado mantem qualidade de segurado (art. 15 da Lei 8.213/91)?
- Ha nexo causal com o trabalho (beneficio acidentario)?
- Ha urgencia (segurado sem renda, em tratamento, risco de agravamento)?
- Quais laudos medicos estao disponiveis?
- Ha alta programada (art. 60, §8o, Lei 8.213/91) contestada?

### ETAPA 2 — ANALISE JURIDICA (Fundamentacao)
Identifique e organize toda a base legal:

Apresente dentro de um bloco <fundamentos_juridicos>:
- **Auxilio por incapacidade temporaria**: Art. 59-63 da Lei 8.213/91
- **Aposentadoria por incapacidade permanente**: Art. 42-47 da Lei 8.213/91
- **Carencia**: Art. 25, I (12 meses) e art. 26, II (isencao para acidente e doencas do art. 151)
- **Qualidade de segurado**: Art. 15 da Lei 8.213/91 (periodo de graca)
- **Nexo causal (acidentario)**: Art. 19-23 da Lei 8.213/91, art. 21-A (nexo tecnico epidemiologico — NTEP)
- **Alta programada**: Art. 60, §8o e §9o, Lei 8.213/91
- **Adicional de 25%**: Art. 45 da Lei 8.213/91 (grande invalidez)
- **Tutela de urgencia**: Art. 300 e 497 do CPC
- **Pericia judicial**: Art. 420 do CPC, art. 12 da Lei 10.259/2001 (JEF)
- **Sumula 78 da TNU**: incapacidade parcial para atividade habitual gera auxilio-doenca
- **Tema 177 do STJ**: data de inicio do beneficio

### ETAPA 3 — CONSTRUCAO ARGUMENTATIVA (Estrategia)
Defina a linha de argumentacao:

Apresente dentro de um bloco <estrategia>:
- Tese principal: incapacidade comprovada por documentacao medica
- Tese subsidiaria: se nao permanente, ao menos temporaria (e vice-versa)
- Demonstracao da incapacidade com base nos laudos
- Contra-argumentos previsiveis do INSS (perito administrativo atestou capacidade)
- Fundamentacao da tutela de urgencia (risco de dano irreparavel)
- Necessidade de pericia judicial

### ETAPA 4 — EXPOSICAO ESTRUTURADA (A Peticao)
Redija a peticao inicial completa com esta estrutura:

1. **Enderecamento** — JEF ou Vara Federal
2. **Qualificacao das partes** — Autor(a) e INSS
3. **Do previo requerimento administrativo** — DER, resultado, fundamentacao do indeferimento
4. **Dos fatos** — Historico da doenca/acidente, tratamentos, limitacoes funcionais
5. **Do direito** — Fundamentacao organizada:
   - Da incapacidade laborativa
   - Do preenchimento dos requisitos legais (carencia, qualidade)
   - Do nexo causal (se acidentario)
   - Da ilegalidade do indeferimento/cessacao
6. **Da tutela de urgencia** — Art. 300 CPC:
   - Probabilidade do direito (laudos medicos + fundamentacao legal)
   - Perigo de dano (segurado sem renda, necessidade de tratamento)
   - Reversibilidade da medida
7. **Dos pedidos** — Lista com letras (a, b, c):
   - Tutela de urgencia para implantacao imediata
   - Concessao/restabelecimento do beneficio desde a DER/cessacao
   - Producao de prova pericial medica
   - Pagamento dos atrasados com correcao e juros
   - Adicional de 25% (se grande invalidez)
   - Honorarios advocaticios
8. **Dos quesitos periciais** — Lista de quesitos para o perito judicial
9. **Das provas**
10. **Do valor da causa**
11. **Fechamento**

### ETAPA 5 — FORMULACAO FINAL (Validacao)
Apresente dentro de um bloco <checklist_validacao>:
- [ ] Beneficio correto identificado (B31/B32/B91/B92)?
- [ ] Incapacidade descrita com base em documentacao medica (CID, exames, laudos)?
- [ ] Carencia preenchida ou isencao aplicavel?
- [ ] Qualidade de segurado verificada?
- [ ] Tutela de urgencia fundamentada (periculum + fumus)?
- [ ] Quesitos periciais elaborados?
- [ ] Nexo causal demonstrado (se acidentario)?
- [ ] Data de inicio do beneficio indicada (DER ou cessacao)?
- [ ] Previo requerimento administrativo comprovado?
- [ ] Pontos que exigem atencao especial do advogado: [liste]

---
</framework>

<template_dados>
## DADOS DO CASO:
**AUTOR(A) / SEGURADO(A):**
- Nome completo: [nome]
- CPF: [numero]
- Nacionalidade: [brasileira(o)]
- Estado civil: [solteiro/casado/divorciado/viuvo/uniao estavel]
- Data de nascimento: [dd/mm/aaaa]
- Profissao/Ultima atividade: [cargo/funcao]
- Endereco completo: [rua, numero, bairro, cidade, UF, CEP]
- NIT/PIS: [numero]
- Escolaridade: [grau de instrucao]
- Email: [para intimacoes eletronicas]
- Telefone: [contato]

**REQUERIMENTO ADMINISTRATIVO:**
- NB: [numero do beneficio]
- DER: [data do requerimento]
- Resultado: [indeferido | cessado | alta programada]
- Motivo do indeferimento: [conforme carta/decisao do INSS]
- Data da cessacao (se restabelecimento): [dd/mm/aaaa]

**SITUACAO PREVIDENCIARIA:**
- Ultimo vinculo empregaticio: [empresa — periodo]
- Esta empregado atualmente? [sim/nao]
- Total de contribuicoes (meses): [quantidade]
- Carencia preenchida (12 meses)? [sim/nao]
- Qualidade de segurado mantida? [sim/nao — ultimo recolhimento em dd/mm/aaaa]

**SITUACAO MEDICA:**
- Doenca/Lesao principal: [descricao + CID]
- Doencas/Lesoes secundarias: [se houver]
- Data de inicio da incapacidade (DII): [dd/mm/aaaa ou estimada]
- Tipo de incapacidade: [total ou parcial]
- Duracao da incapacidade: [temporaria ou permanente]
- Causa: [doença comum | acidente de trabalho | doenca ocupacional]
- Tratamentos realizados: [cirurgias, internacoes, fisioterapia, medicamentos]
- Tratamento em andamento: [sim/nao — qual]
- Prognostico: [cura possivel | estabilizacao | agravamento progressivo]
- Necessita de assistencia permanente de terceiro? [sim/nao — para adicional de 25%]

**DOCUMENTACAO MEDICA DISPONIVEL:**
[Liste todos os documentos medicos:
- Laudos medicos (data e medico)
- Atestados de afastamento
- Exames complementares (ressonancia, tomografia, etc.)
- Relatorio de internacao
- Receitas medicas
- CAT (Comunicacao de Acidente de Trabalho) — se acidentario
- PPP (se doenca ocupacional)]

**URGENCIA:**
- O segurado esta sem renda? [sim/nao]
- Ha risco de agravamento sem tratamento? [sim/nao]
- Ha despesas medicas urgentes? [sim/nao — valor estimado]
- Motivo da urgencia: [descreva a situacao]

**INFORMACOES ADICIONAIS:**
- Competencia: [JEF ou Vara Federal — cidade]
- Ha acoes anteriores sobre o mesmo beneficio? [sim/nao]
- Observacoes: [informacoes adicionais]
</template_dados>

<dicas>
1. **Laudos medicos sao a peca central** — Quanto mais recentes e detalhados, melhor. Oriente o cliente a obter laudos com CID, descricao das limitacoes e prognostico.
2. **Diferencie B31 de B32** — Auxilio temporario (B31) exige incapacidade para a atividade habitual. Aposentadoria por invalidez (B32) exige incapacidade total e permanente para qualquer atividade. Peca ambos subsidiariamente.
3. **Tutela de urgencia e quase sempre cabivel** — Segurado sem renda e incapaz de trabalhar preenche o perigo de dano. Fundamente bem e peca implantacao em 72h.
4. **Quesitos periciais fazem diferenca** — Elabore quesitos direcionados a atividade habitual do segurado, nao apenas sobre a doenca em abstrato.
5. **Atencao a qualidade de segurado** — Se o segurado esta ha muito tempo sem contribuir, verifique o periodo de graca (art. 15). Desemprego involuntario estende por mais 12 meses.

---
*Skills Jurídicas com IA — RSA Advocacia*
</dicas>
