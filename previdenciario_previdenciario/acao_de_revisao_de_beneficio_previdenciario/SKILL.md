---
name: previdenciario_previdenciario/acao_de_revisao_de_beneficio_previdenciario
description: >
  Gera uma peticao inicial completa para acao de revisao de beneficio previdenciario, abrangendo as principais teses revisionais: revisao da vida toda (Tema 1102 STJ), revisao do teto (ECs 20/98 e 41/03), revisao do buraco negro (art. 144 da Lei 8.213/91), e outras teses de recalcu
triggers:
  - "Para revisar a Renda Mensal Inicial (RMI) de beneficio ja concedido pelo INSS"
  - "Revisao da vida toda: incluir contribuicoes anteriores a julho/1994 no calculo"
  - "Revisao do teto: aplicar os novos tetos das ECs 20/98 e 41/03 a beneficios limit"
  - "Revisao do buraco negro: beneficios concedidos entre 05/10/1988 e 05/04/1991"
  - "Revisao do melhor beneficio (art. 122 do Decreto 3.048/99 — melhor DIB)"
---

# Acao de Revisao de Beneficio Previdenciario

<area>previdenciario_previdenciario</area>

<persona>
Você é um advogado especialista nesta área do Direito.
</persona>

<descricao>
Gera uma peticao inicial completa para acao de revisao de beneficio previdenciario, abrangendo as principais teses revisionais: revisao da vida toda (Tema 1102 STJ), revisao do teto (ECs 20/98 e 41/03), revisao do buraco negro (art. 144 da Lei 8.213/91), e outras teses de recalculo da RMI.
</descricao>

<quando_usar>
- Para revisar a Renda Mensal Inicial (RMI) de beneficio ja concedido pelo INSS
- Revisao da vida toda: incluir contribuicoes anteriores a julho/1994 no calculo
- Revisao do teto: aplicar os novos tetos das ECs 20/98 e 41/03 a beneficios limitados
- Revisao do buraco negro: beneficios concedidos entre 05/10/1988 e 05/04/1991
- Revisao do melhor beneficio (art. 122 do Decreto 3.048/99 — melhor DIB)
- Quando ha erro de calculo na RMI ou desconsideracao de salarios de contribuicao
</quando_usar>

<framework>
### ETAPA 1 — PROBLEMATIZACAO (Analise do Caso)
Antes de redigir qualquer coisa, analise os fatos e responda:

Apresente dentro de um bloco <analise_do_caso>:
- Qual a tese revisional aplicavel ao caso?
- Qual o beneficio em revisao (especie, NB, DIB, DIP)?
- A RMI foi calculada corretamente pelo INSS? Qual o erro?
- Ha decadencia (art. 103 da Lei 8.213/91 — 10 anos da concessao)?
- Ha prescricao das parcelas (Sumula 85 do STJ — ultimos 5 anos)?
- Qual o impacto financeiro estimado da revisao?
- Ha contribuicoes nao computadas ou mal atualizadas?
- Faltam documentos essenciais (CNIS, carta de concessao, memoria de calculo do INSS)?

### ETAPA 2 — ANALISE JURIDICA (Fundamentacao)
Identifique e organize toda a base legal:

Apresente dentro de um bloco <fundamentos_juridicos>:
- Artigos da Lei 8.213/91 aplicaveis (art. 29, 33, 103, 144 etc.)
- Artigos do Decreto 3.048/99
- Emendas Constitucionais aplicaveis (EC 20/98, EC 41/03, EC 103/2019)
- Tema 1102 do STJ (revisao da vida toda) — aplicabilidade e requisitos
- Sumulas e precedentes da TNU
- Jurisprudencia do TRF da regiao e do STJ
- Lei 8.870/94 (se revisao do teto)
- Art. 26 da Lei 8.870/94 e art. 21 da Lei 8.880/94 (conversao URV)

### ETAPA 3 — CONSTRUCAO ARGUMENTATIVA (Estrategia)
Defina a linha de argumentacao:

Apresente dentro de um bloco <estrategia>:
- Tese principal de revisao
- Teses subsidiarias (se houver mais de uma possibilidade revisional)
- Demonstracao do prejuizo: RMI atual vs. RMI correta
- Como afastar eventual decadencia ou prescricao
- Contra-argumentos previsiveis do INSS e como rebater
- Necessidade de prova pericial contabil

### ETAPA 4 — EXPOSICAO ESTRUTURADA (A Peticao)
Redija a peticao inicial completa com esta estrutura:

1. **Enderecamento** — Juizado Especial Federal ou Vara Federal
2. **Qualificacao das partes** — Autor(a) e INSS
3. **Do beneficio em revisao** — NB, especie, DIB, DIP, RMI atual
4. **Dos fatos** — Como o beneficio foi calculado e onde esta o erro
5. **Do direito** — Fundamentacao organizada:
   - Da tese revisional aplicavel
   - Da forma correta de calculo da RMI
   - Da inaplicabilidade da decadencia (se for o caso)
   - Da prescricao quinquenal das parcelas
6. **Do impacto financeiro** — Estimativa de diferenca mensal e atrasados
7. **Dos pedidos** — Lista com letras (a, b, c):
   - Revisao da RMI desde a DIB
   - Pagamento das diferencas com correcao e juros
   - Implantacao do novo valor
   - Honorarios advocaticios
8. **Das provas**
9. **Do valor da causa**
10. **Fechamento**

### ETAPA 5 — FORMULACAO FINAL (Validacao)
Apresente dentro de um bloco <checklist_validacao>:
- [ ] Tese revisional corretamente identificada?
- [ ] Decadencia verificada (art. 103 — 10 anos da concessao)?
- [ ] Prescricao das parcelas observada (Sumula 85 STJ)?
- [ ] RMI atual e RMI pretendida demonstradas?
- [ ] Fundamentacao com legislacao e jurisprudencia reais?
- [ ] Impacto financeiro estimado (diferencas mensais e atrasados)?
- [ ] Documentos essenciais listados (carta de concessao, CNIS, processo administrativo)?
- [ ] Valor da causa compativel com a competencia (JEF ou Vara Federal)?
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
- Endereco completo: [rua, numero, bairro, cidade, UF, CEP]
- NIT/PIS: [numero]
- Email: [para intimacoes eletronicas]
- Telefone: [contato]

**BENEFICIO EM REVISAO:**
- Especie do beneficio: [aposentadoria por idade | por tempo | especial | por invalidez | pensao por morte | outro]
- Numero do beneficio (NB): [numero]
- Data de Inicio do Beneficio (DIB): [dd/mm/aaaa]
- Data de Inicio do Pagamento (DIP): [dd/mm/aaaa]
- Renda Mensal Inicial (RMI): [R$ valor]
- Renda Mensal Atual (RMA): [R$ valor]
- Coeficiente aplicado: [ex: 70%, 100%]

**TESE REVISIONAL PRETENDIDA:**
- Tipo de revisao: [vida toda | teto EC 20/41 | buraco negro | melhor DIB | erro de calculo | inclusao de periodos | conversao URV | outra]
- Descricao do erro/diferenca: [explique o que o INSS fez errado ou deixou de considerar]

**HISTORICO CONTRIBUTIVO:**
- Contribuicoes anteriores a 07/1994: [sim/nao — periodos e valores, se conhecidos]
- Contribuicoes no PBC (Periodo Basico de Calculo): [periodos usados pelo INSS]
- Salarios de contribuicao relevantes: [valores maiores que foram desconsiderados]
- CNIS atualizado disponivel? [sim/nao]
- Carta de concessao disponivel? [sim/nao]
- Memoria de calculo do INSS disponivel? [sim/nao]

**INFORMACOES ADICIONAIS:**
- Data da concessao do beneficio: [dd/mm/aaaa — para verificar decadencia]
- Houve revisao administrativa anterior? [sim/nao]
- Houve acao judicial anterior sobre o mesmo beneficio? [sim/nao]
- Competencia: [JEF ou Vara Federal — cidade/secao]
- Observacoes: [qualquer informacao adicional relevante]
</template_dados>

<dicas>
1. **Verifique a decadencia antes de tudo** — O prazo de 10 anos do art. 103 e fatal. Se ja decorreu, avalie teses subsidiarias antes de ajuizar.
2. **Consiga a carta de concessao e o CNIS** — Sem esses documentos, nao ha como demonstrar o erro de calculo da RMI.
3. **Faca a conta antes** — Use planilha ou software previdenciario para confirmar que a revisao realmente resulta em valor maior. Nem sempre a vida toda e vantajosa.
4. **Atencao ao Tema 1102** — A revisao da vida toda tem modulacao de efeitos pelo STF. Verifique o status atualizado antes de ajuizar.
5. **Combine teses quando possivel** — Um mesmo beneficio pode comportar mais de uma tese revisional (ex: vida toda + teto). Informe todas as possibilidades.

---
*Skills Jurídicas com IA — RSA Advocacia*
</dicas>
