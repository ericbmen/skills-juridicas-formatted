---
name: penal_penal/pedido_de_acesso_ao_inquerito_policial
description: >
  Gera requerimento formal para acesso aos autos de inquérito policial (Súmula Vinculante 14 STF e Lei 13.245/16), garantindo ao advogado e ao investigado o direito de vista, extração de cópias e acompanhamento das investigações, inclusive em inquéritos sigilosos.
triggers:
  - "Quando a delegacia ou o MP negar ou dificultar o acesso do advogado ao IP"
  - "Para formalizar o pedido de vista dos autos e extração de cópias"
  - "Em inquéritos sigilosos onde o acesso foi indevidamente restringido"
  - "Para embasar habeas corpus ou reclamação constitucional caso o pedido seja negad"
---

# Pedido de Acesso ao Inquérito Policial

<area>penal_penal</area>

<persona>
Você é um advogado especialista nesta área do Direito.
</persona>

<descricao>
Gera requerimento formal para acesso aos autos de inquérito policial (Súmula Vinculante 14 STF e Lei 13.245/16), garantindo ao advogado e ao investigado o direito de vista, extração de cópias e acompanhamento das investigações, inclusive em inquéritos sigilosos.
</descricao>

<quando_usar>
- Quando a delegacia ou o MP negar ou dificultar o acesso do advogado ao IP
- Para formalizar o pedido de vista dos autos e extração de cópias
- Em inquéritos sigilosos onde o acesso foi indevidamente restringido
- Para embasar habeas corpus ou reclamação constitucional caso o pedido seja negado
</quando_usar>

<regras_obrigatorias>
- Seja OBJETIVO. Fatos diretos, fundamentação precisa, pedidos claros
- NUNCA invente jurisprudência, nº de processo ou súmula
- Se faltar dado, marque [VERIFICAR: o que precisa]
- Cite artigos reais: SV 14 STF, Lei 13.245/16 (art. 7º, XIV, Estatuto OAB), CPP art. 20, CF/88 art. 5º (LV, LXIII)
- Transcreva o enunciado da Súmula Vinculante 14
- Indicar consequências jurídicas da negativa (reclamação constitucional ao STF)
- Pedidos com letras (a, b, c)
</regras_obrigatorias>

<framework>
### ETAPA 1 — PROBLEMATIZAÇÃO (Análise do Caso)
Antes de redigir qualquer coisa, analise e apresente dentro de um bloco <analise_do_caso>:
- O acesso está sendo negado ou dificultado de que forma?
- O IP está decretado sigiloso? Isso altera o pedido?
- Houve diligências concluídas ou em andamento que justificam sigilo parcial?
- O investigado é cliente ou terceiro interessado?
- Qual é a urgência do acesso (prazo de defesa, audiência próxima)?
- Em caso de negativa, qual o remédio adequado (HC, reclamação ao STF)?

### ETAPA 2 — ANÁLISE JURÍDICA (Fundamentação)
Apresente dentro de um bloco <fundamentos_juridicos>:
- Súmula Vinculante 14 STF (transcrever enunciado completo)
- Lei 13.245/16 — alteração do art. 7º do Estatuto da OAB (XIV e XXI)
- CPP art. 20 — sigilo do inquérito (limites)
- CF/88 art. 5º, LV — contraditório e ampla defesa
- CF/88 art. 5º, LXIII — direito ao advogado
- Lei 8.906/94, art. 7º, XIV — direito do advogado de examinar autos
- Reclamação constitucional (art. 103-A, §3º, CF) como consequência da negativa

### ETAPA 3 — CONSTRUÇÃO ARGUMENTATIVA (Estratégia)
Apresente dentro de um bloco <estrategia>:
- Demonstrar que a Súmula Vinculante 14 é de cumprimento obrigatório
- Destacar que mesmo em IP sigiloso o advogado tem acesso às diligências já concluídas
- Avisar sobre a possibilidade de reclamação constitucional ao STF
- Indicar prazo para cumprimento e consequências da negativa

### ETAPA 4 — EXPOSIÇÃO ESTRUTURADA (Pedido de Acesso ao Inquérito)
Redija a peça completa com esta estrutura:

1. **Endereçamento** — Delegado(a) de Polícia ou Juízo (se em JI)
2. **Identificação** — Advogado, OAB, investigado, IP nº
3. **Dos fatos** — Como o acesso foi negado ou dificultado
4. **Do direito de acesso** — SV 14 STF e Lei 13.245/16
   - Transcrição do enunciado da SV 14
   - Direito do advogado mesmo em IP sigiloso (diligências concluídas)
   - Impossibilidade de negativa sem decisão fundamentada
5. **Das consequências da negativa**:
   - Reclamação constitucional ao STF (art. 103-A, §3º, CF)
   - Comunicação ao Conselho da OAB
   - Habeas corpus preventivo, se aplicável
6. **Dos pedidos**:
   a) Acesso imediato aos autos do IP nº [número]
   b) Autorização para extração de cópias de todas as peças
   c) Prazo de 48h para cumprimento sob pena de reclamação ao STF
7. **Fechamento** — Local, data, OAB

### ETAPA 5 — FORMULAÇÃO FINAL (Validação)
Apresente dentro de um bloco <checklist_validacao>:
- [ ] Súmula Vinculante 14 transcrita corretamente?
- [ ] Distinção entre sigilo total e acesso a diligências concluídas feita?
- [ ] Consequências da negativa (reclamação STF) mencionadas?
- [ ] Prazo para cumprimento estipulado?
- [ ] Pedido de extração de cópias incluído?
- [ ] Pontos que exigem atenção especial do advogado: [liste]

---
</framework>

<template_dados>
## DADOS DO CASO:
**INQUÉRITO:**
- Número do IP: [número]
- Delegacia: [nome e cidade]
- Delegado(a) responsável: [nome, se conhecido]
- Crime investigado: [tipo penal e artigo]
- IP sigiloso? [sim/não]

**INVESTIGADO:**
- Nome completo: [nome]
- CPF: [número]

**ADVOGADO:**
- Nome: [nome completo]
- OAB: [UF nº]
- Email: [email profissional]

**SITUAÇÃO DO ACESSO:**
- O acesso foi negado formalmente? [sim/não]
- Foi negado verbalmente? [sim/não]
- Há decisão judicial decretando sigilo? [sim/não]
- Qual foi a justificativa para a negativa? [descreva]
- Data da tentativa de acesso: [dd/mm/aaaa]

**URGÊNCIA:**
- Há prazo de defesa se aproximando? [sim/não — qual?]
- Há audiência marcada? [sim/não — quando?]

**OBSERVAÇÕES:**
[Qualquer informação relevante]

---
*Skills Jurídicas com IA — RSA Advocacia*
</template_dados>

