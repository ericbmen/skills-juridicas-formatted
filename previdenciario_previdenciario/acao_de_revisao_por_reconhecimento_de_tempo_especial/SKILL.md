---
name: previdenciario_previdenciario/acao_de_revisao_por_reconhecimento_de_tempo_especial
description: >
  Gera uma peticao inicial completa para revisao de beneficio pela inclusao ou reconhecimento de periodos de atividade especial nao considerados no calculo original, com fundamentacao nos arts. 57 e 58 da Lei 8.213/91 e art. 70 do Decreto 3.048/99, permitindo a conversao de tempo e
triggers:
  - "Quando o segurado ja esta aposentado mas nao teve reconhecido o tempo especial n"
  - "Quando a revisao do tempo especial permite mudar a especie do beneficio (ex: por"
  - "Quando a conversao de tempo especial em comum aumenta o coeficiente da aposentad"
  - "Quando o INSS nao aplicou a conversao correta (fator multiplicador — art. 70 do "
  - "Para beneficios concedidos sem o PPP ou antes da obrigatoriedade do laudo indivi"
---

# Acao de Revisao por Reconhecimento de Tempo Especial

<area>previdenciario_previdenciario</area>

<persona>
Você é um advogado especialista nesta área do Direito.
</persona>

<descricao>
Gera uma peticao inicial completa para revisao de beneficio pela inclusao ou reconhecimento de periodos de atividade especial nao considerados no calculo original, com fundamentacao nos arts. 57 e 58 da Lei 8.213/91 e art. 70 do Decreto 3.048/99, permitindo a conversao de tempo especial em comum para aumento da RMI ou mudanca de especie de aposentadoria.
</descricao>

<quando_usar>
- Quando o segurado ja esta aposentado mas nao teve reconhecido o tempo especial na concessao
- Quando a revisao do tempo especial permite mudar a especie do beneficio (ex: por tempo para especial)
- Quando a conversao de tempo especial em comum aumenta o coeficiente da aposentadoria por tempo
- Quando o INSS nao aplicou a conversao correta (fator multiplicador — art. 70 do Decreto 3.048/99)
- Para beneficios concedidos sem o PPP ou antes da obrigatoriedade do laudo individual
</quando_usar>

<framework>
### ETAPA 1 — PROBLEMATIZACAO (Analise do Caso)
Antes de redigir qualquer coisa, analise os fatos e responda:

Apresente dentro de um bloco <analise_do_caso>:
- Qual o beneficio em revisao (especie, NB, DIB)?
- Quais periodos de atividade especial nao foram reconhecidos?
- Qual o agente nocivo de cada periodo?
- Qual o enquadramento legal (15, 20 ou 25 anos)?
- Ha PPP ou LTCAT para os periodos nao reconhecidos?
- Para periodos anteriores a 1997: e possivel enquadramento por categoria profissional?
- O reconhecimento dos periodos especiais: (a) permite mudar a especie do beneficio? (b) aumenta o coeficiente da aposentadoria por tempo? (c) gera diferenca de RMI?
- Ha decadencia em curso (art. 103 — 10 anos da concessao)?
- Qual o impacto financeiro estimado da revisao?

### ETAPA 2 — ANALISE JURIDICA (Fundamentacao)
Identifique e organize toda a base legal:

Apresente dentro de um bloco <fundamentos_juridicos>:
- Art. 57 da Lei 8.213/91: conceito e periodos de aposentadoria especial
- Art. 58 da Lei 8.213/91: prova da atividade especial (PPP/LTCAT)
- Art. 70 do Decreto 3.048/99: tabela de conversao de tempo especial em comum
- Decretos 53.831/64 e 83.080/79: enquadramento por categoria profissional (pre-1997)
- Decreto 2.172/97 e Decreto 3.048/99: enquadramento por agente (pos-1997)
- RE 664.335 (Tema 888 STF): EPI nao afasta a especialidade
- Sumula 49 da TNU: reconhecimento de atividade especial por enquadramento profissional
- Sumula 68 da TNU: laudo pode ser suprido por outros meios de prova
- Art. 103 da Lei 8.213/91: decadencia decenal
- Sumula 85 do STJ: prescricao quinquenal

### ETAPA 3 — CONSTRUCAO ARGUMENTATIVA (Estrategia)
Defina a linha de argumentacao:

Apresente dentro de um bloco <estrategia>:
- Para cada periodo especial: qual o enquadramento legal aplicavel (pre ou pos-1997)
- Provas disponíveis para cada periodo (PPP, LTCAT, enquadramento profissional, prova pericial)
- Calculo do impacto: tempo especial convertido x coeficiente ou mudanca de especie
- Como afastar eventual argumento de decadencia
- Contra-argumentos previsiveis do INSS e como rebater
- Necessidade de prova pericial se o LTCAT for inexistente ou insuficiente

### ETAPA 4 — EXPOSICAO ESTRUTURADA (A Peticao)
Redija a peticao inicial completa com esta estrutura:

1. **Enderecamento** — Juizado Especial Federal ou Vara Federal competente
2. **Qualificacao das partes** — Autor(a) e Reu (INSS)
3. **Do beneficio em revisao** — NB, especie, DIB, RMI atual
4. **Dos fatos** — Historico profissional, periodos especiais, como o INSS os desconsiderou
5. **Do direito** — Fundamentacao organizada:
   - Da atividade especial de cada periodo (art. 57 da Lei 8.213/91)
   - Do enquadramento legal aplicavel a cada periodo
   - Da prova (PPP, LTCAT, categoria profissional, prova pericial)
   - Da conversao de tempo especial em comum (art. 70 do Decreto 3.048/99)
   - Do impacto na RMI ou mudanca de especie
   - Da inaplicabilidade da decadencia
6. **Dos pedidos** — Lista com letras
7. **Das provas**
8. **Do valor da causa**
9. **Fechamento**

### ETAPA 5 — FORMULACAO FINAL (Validacao)
Apresente dentro de um bloco <checklist_validacao>:
- [ ] Periodos especiais corretamente identificados?
- [ ] Enquadramento legal verificado por periodo (pre/pos-1997)?
- [ ] PPP ou LTCAT disponivel para cada periodo?
- [ ] Fator de conversao correto aplicado (art. 70 do Decreto 3.048/99)?
- [ ] Impacto na RMI ou mudanca de especie calculado?
- [ ] Decadencia verificada (art. 103 — 10 anos)?
- [ ] Prescricao das parcelas observada (Sumula 85 STJ)?
- [ ] Pontos que exigem atencao especial do advogado: [liste]

---
</framework>

<template_dados>
## DADOS DO CASO:
**AUTOR(A) / SEGURADO(A):**
- Nome completo: [nome]
- CPF: [numero]
- Data de nascimento: [dd/mm/aaaa]
- Endereco completo: [rua, numero, bairro, cidade, UF, CEP]
- NIT/PIS: [numero]
- Email: [para intimacoes eletronicas]

**BENEFICIO EM REVISAO:**
- Especie: [aposentadoria por tempo de contribuicao | por idade | por invalidez | outro]
- Numero do beneficio (NB): [numero]
- Data de concessao: [dd/mm/aaaa — CRITICO para decadencia]
- DIB: [dd/mm/aaaa]
- RMI original: [R$ valor]
- RMA atual: [R$ valor]

**PERIODOS DE ATIVIDADE ESPECIAL NAO RECONHECIDOS:**
[Para cada periodo, informe:]
- Empregador: [razao social, CNPJ]
- Periodo: [de dd/mm/aaaa ate dd/mm/aaaa]
- Cargo/funcao: [descricao]
- Agente nocivo: [especificar]
- PPP disponivel: [sim/nao]
- LTCAT disponivel: [sim/nao]
- Legislacao do periodo: [Decreto 53.831/64 | Decreto 83.080/79 | Decreto 2.172/97 | Decreto 3.048/99]

**IMPACTO DA REVISAO:**
- Tempo especial nao reconhecido: [anos e meses — total]
- Enquadramento (15/20/25 anos): [informar]
- Fator de conversao: [1,0 | 1,2 | 1,4]
- Tempo comum equivalente apos conversao: [calcule]
- Impacto esperado: [aumento de coeficiente | mudanca de especie | nova RMI estimada]

**PROVAS DISPONIVEIS:**
[Liste: PPP, LTCAT, CTPS, carta de concessao, CNIS, outros]

**INFORMACOES ADICIONAIS:**
- Competencia: [JEF ou Vara Federal — cidade/secao]
- Observacoes: [qualquer informacao adicional relevante]
</template_dados>

<dicas>
1. **Calcule o impacto antes** — Nao basta ter tempo especial. Verifique se a revisao realmente aumenta a RMI ou muda a especie. As vezes o impacto e minimo e nao justifica o ajuizamento.
2. **Tabela de conversao (art. 70 do Decreto 3.048/99)** — Para quem nao teve aposentadoria especial: tempo especial de 25 anos = fator 1,4; de 20 anos = fator 1,2; de 15 anos = fator 1,0 sobre o tempo comum.
3. **Pre-1997 e por categoria profissional** — Para periodos anteriores ao Decreto 2.172/97, o enquadramento e por categoria, sem necessidade de laudo. Consulte os Decretos 53.831/64 e 83.080/79.
4. **Decadencia e fatal** — Se ja passaram 10 anos da concessao do beneficio, a acao de revisao nao e possivel (art. 103 da Lei 8.213/91). Verifique a data de concessao com cuidado.
5. **Combine com outros pedidos revisionais** — Um mesmo beneficio pode ter mais de uma tese revisional. Ex: revisao de tempo especial + revisao da vida toda. Combine quando cabivel.

---
*Skills Jurídicas com IA — RSA Advocacia*
</dicas>
