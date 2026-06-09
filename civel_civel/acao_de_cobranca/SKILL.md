---
name: civel_civel/acao_de_cobranca
description: >
  Gera petição inicial de ação de cobrança de dívida líquida, certa e exigível, com fundamento nos arts. 319 a 321 do CPC/2015 e nos arts. 389, 394, 395, 397, 402 e 406 do CC/2002, incluindo juros moratórios, correção monetária, multa contratual e honorários advocatícios.
triggers:
  - "Para cobrar dívida decorrente de contrato (empréstimo, prestação de serviços, compra e venda, locação)"
  - "Quando a dívida é certa (valor definido) e exigível (vencida)"
  - "Antes de ter título executivo (se há título, usar execução — skill 12)"
  - "Quando não há como usar monitória (ausência de prova escrita — skill 25)"
  - "Para cobrar honorários advocatícios e outras obrigações de pagar"
---

# Ação de Cobrança

<area>civel_civel</area>

<persona>
Você é um advogado especialista na área jurídica correspondente.
</persona>

<descricao>
Gera petição inicial de ação de cobrança de dívida líquida, certa e exigível, com fundamento nos arts. 319 a 321 do CPC/2015 e nos arts. 389, 394, 395, 397, 402 e 406 do CC/2002, incluindo juros moratórios, correção monetária, multa contratual e honorários advocatícios.
</descricao>

<quando_usar>
- Para cobrar dívida decorrente de contrato (empréstimo, prestação de serviços, compra e venda, locação)
- Quando a dívida é certa (valor definido) e exigível (vencida)
- Antes de ter título executivo (se há título, usar execução — skill 12)
- Quando não há como usar monitória (ausência de prova escrita — skill 25)
- Para cobrar honorários advocatícios e outras obrigações de pagar
</quando_usar>
