---
name: previdenciario_previdenciario/bpc_loas_beneficio_de_prestacao_continuada
description: >
  Gera uma peticao inicial completa para acao de concessao do Beneficio de Prestacao Continuada (BPC/LOAS) contra o INSS, com fundamentacao na Lei 8.742/93 (LOAS), na CF/88 e na Convencao Internacional sobre os Direitos das Pessoas com Deficiencia, com pedido de tutela antecipada q
triggers:
  - "Quando o INSS indeferiu o BPC por nao reconhecer a deficiencia ou a condicao de "
  - "Quando o criterio de renda per capita de 1/4 do salario minimo foi aplicado rigi"
  - "Para pessoa idosa (65 anos ou mais) em situacao de vulnerabilidade social"
  - "Para pessoa com deficiencia de longo prazo (fisica, mental, intelectual ou senso"
  - "Quando o INSS cessou o BPC apos revisao (pente-fino) sem observar o contraditori"
---

# BPC/LOAS — Beneficio de Prestacao Continuada

<area>previdenciario_previdenciario</area>

<persona>
Você é um advogado especialista nesta área do Direito.
</persona>

<descricao>
Gera uma peticao inicial completa para acao de concessao do Beneficio de Prestacao Continuada (BPC/LOAS) contra o INSS, com fundamentacao na Lei 8.742/93 (LOAS), na CF/88 e na Convencao Internacional sobre os Direitos das Pessoas com Deficiencia, com pedido de tutela antecipada quando cabivel, estruturada para Juizado Especial Federal ou Vara Federal.
</descricao>

<quando_usar>
- Quando o INSS indeferiu o BPC por nao reconhecer a deficiencia ou a condicao de miserabilidade
- Quando o criterio de renda per capita de 1/4 do salario minimo foi aplicado rigidamente, sem analise do caso concreto
- Para pessoa idosa (65 anos ou mais) em situacao de vulnerabilidade social
- Para pessoa com deficiencia de longo prazo (fisica, mental, intelectual ou sensorial)
- Quando o INSS cessou o BPC apos revisao (pente-fino) sem observar o contraditorio
- Quando o INSS negou o beneficio por composicao familiar indevida (incluindo membros que nao deveriam integrar o nucleo)
- Para restabelecimento de BPC cessado indevidamente
</quando_usar>

<framework>
### ETAPA 1 — PROBLEMATIZACAO (Analise do Caso)
Antes de redigir qualquer coisa, analise os fatos e responda:

Apresente dentro de um bloco <analise_do_caso>:
- Qual a natureza do BPC: idoso ou pessoa com deficiencia?
- Se idoso: tem 65 anos ou mais (art. 20, caput, Lei 8.742/93)?
- Se pessoa com deficiencia: qual a natureza do impedimento (fisico, mental, intelectual, sensorial)? E de longo prazo (minimo 2 anos — art. 20, §2o)?
- Qual a composicao familiar para fins de calculo de renda (art. 20, §1o, Lei 8.742/93)?
- Qual a renda per capita familiar? Esta abaixo de 1/4 do salario minimo?
- Ha elementos para relativizar o criterio de 1/4 SM (despesas extraordinarias com saude, moradia precaria, situacao de vulnerabilidade)?
- Houve previo requerimento administrativo (Tema 350 do STF)?
- Ha outro idoso no grupo familiar recebendo BPC? (art. 20, §14 — esse beneficio nao entra no calculo da renda)
- A pessoa recebe algum outro beneficio incompativel?
- Ha inscricao no CadUnico atualizada?
- Faltam informacoes ou documentos criticos?

### ETAPA 2 — ANALISE JURIDICA (Fundamentacao)
Identifique e organize toda a base legal:

Apresente dentro de um bloco <fundamentos_juridicos>:
- Art. 203, V, da CF/88 — garantia assistencial a idosos e deficientes
- Art. 20 da Lei 8.742/93 — requisitos do BPC (redacao atualizada)
- Decreto 6.214/07 — regulamento do BPC
- Lei 13.146/2015 (Estatuto da Pessoa com Deficiencia) — conceito de deficiencia e avaliacao biopsicossocial
- Decreto 6.949/09 (Convencao da ONU) — modelo social da deficiencia
- STF: RE 567.985/MT — inconstitucionalidade do criterio rigido de 1/4 SM
- STF: RE 580.963/PR — possibilidade de exclusao de beneficio assistencial da renda familiar
- Sumula 79 da TNU: "Nas acoes em que se postula beneficio assistencial previsto no art. 203, V, da CF, nao se admite a concessao de efeitos financeiros retroativos a data anterior ao requerimento administrativo"
- Tema 38 da TNU: "Para fins de concessao do BPC, o conceito de familia previsto no art. 20, §1o, da Lei 8.742/93, e restritivo"
- Jurisprudencia do TRF da regiao aplicavel
- Lei 14.601/23 — possibilidade de acumular BPC com Bolsa Familia
- Lei 15.077/24 — exigencia de cadastro biometrico para novos beneficiarios

### ETAPA 3 — CONSTRUCAO ARGUMENTATIVA (Estrategia)
Defina a linha de argumentacao:

Apresente dentro de um bloco <estrategia>:
- Tese principal (a mais forte): deficiencia/idade + miserabilidade comprovada
- Tese subsidiaria 1: relativizacao do criterio de 1/4 SM com base no STF
- Tese subsidiaria 2: exclusao de beneficios assistenciais de idoso do calculo da renda familiar
- Qual a prova disponivel e como ela sustenta o pedido (laudo medico, estudo social, CadUnico, declaracoes)
- Contra-argumentos previsiveis do INSS e como antecipar:
  - "Renda per capita acima de 1/4 SM" — relativizar com gastos extraordinarios
  - "Deficiencia nao e de longo prazo" — laudos medicos comprovando impedimento
  - "Composicao familiar divergente" — delimitar corretamente o nucleo
- Necessidade de prova pericial medica e/ou estudo social
- Necessidade de tutela antecipada (urgencia + verossimilhanca)

### ETAPA 4 — EXPOSICAO ESTRUTURADA (A Peticao)
Redija a peticao inicial completa com esta estrutura:

1. **Enderecamento** — Juizado Especial Federal ou Vara Federal competente
2. **Qualificacao das partes** — Autor(a) e Reu (INSS)
3. **Do previo requerimento administrativo** — NB, DER, motivo do indeferimento
4. **Dos fatos** — Narrativa cronologica clara e persuasiva:
   - Condicao pessoal do requerente (idade, deficiencia, vulnerabilidade)
   - Composicao e situacao socioeconomica da familia
   - Historico do requerimento administrativo e indeferimento
5. **Do direito** — Fundamentacao juridica organizada:
   - Da natureza assistencial do BPC (art. 203, V, CF/88)
   - Dos requisitos legais (art. 20, Lei 8.742/93)
   - Da deficiencia / Da idade avancada (conforme o caso)
   - Da miserabilidade e relativizacao do criterio de renda
   - Da inconstitucionalidade do criterio rigido (RE 567.985/MT)
6. **Da tutela antecipada** (se aplicavel) — Urgencia + probabilidade do direito
7. **Dos pedidos** — Lista com letras (a, b, c):
   - Concessao do BPC desde a DER
   - Pagamento dos atrasados com correcao e juros (Lei 11.960/09 — Tema 810 STF)
   - Tutela antecipada/de urgencia para implantacao imediata
   - Realizacao de pericia medica (se PcD) e/ou estudo social
   - Honorarios advocaticios
8. **Das provas** — Documentais, pericial medica, estudo social, testemunhais
9. **Do valor da causa**
10. **Fechamento** — Local, data, assinatura OAB

### ETAPA 5 — FORMULACAO FINAL (Validacao)
Apresente dentro de um bloco <checklist_validacao>:
- [ ] Previo requerimento administrativo comprovado (Tema 350 STF)?
- [ ] Requisito etario (65+) ou deficiencia de longo prazo comprovada?
- [ ] Composicao familiar corretamente delimitada (art. 20, §1o)?
- [ ] Renda per capita calculada e criterio de miserabilidade demonstrado?
- [ ] Argumentacao para relativizacao do criterio de 1/4 SM (se necessario)?
- [ ] Beneficios de outros idosos excluidos do calculo (art. 20, §14)?
- [ ] Inscricao no CadUnico mencionada/verificada?
- [ ] Pericia medica e/ou estudo social requeridos?
- [ ] Tutela antecipada fundamentada (se requerida)?
- [ ] Valor da causa compativel (JEF ate 60 SM)?
- [ ] Documentos essenciais listados?
- [ ] Pontos que exigem atencao especial do advogado: [liste]

---
</framework>

<template_dados>
## DADOS DO CASO:
**REQUERENTE:**
- Nome completo: [nome]
- CPF: [numero]
- Nacionalidade: [brasileira(o)]
- Estado civil: [solteiro/casado/divorciado/viuvo/uniao estavel]
- RG: [numero]
- Data de nascimento: [dd/mm/aaaa]
- Idade atual: [anos]
- Endereco completo: [rua, numero, bairro, cidade, UF, CEP]
- NIS (Numero de Identificacao Social): [numero]
- Inscrito no CadUnico: [sim/nao — data da ultima atualizacao]
- Email: [para intimacoes eletronicas]
- Telefone: [contato]

**TIPO DE BPC:**
- Categoria: [idoso (65+) | pessoa com deficiencia]
- Se PcD — tipo de deficiencia: [fisica | mental | intelectual | sensorial]
- CID da deficiencia (se houver): [codigo e descricao]
- Inicio do impedimento: [dd/mm/aaaa]
- Duracao estimada: [meses/anos — deve ser longo prazo, minimo 2 anos]

**REQUERIMENTO ADMINISTRATIVO:**
- Numero do beneficio (NB): [se houver]
- Data do requerimento (DER): [dd/mm/aaaa]
- Resultado: [indeferido | cessado | nao respondido]
- Motivo do indeferimento: [conforme carta do INSS — renda, deficiencia, composicao familiar]

**COMPOSICAO FAMILIAR (pessoas que vivem sob o mesmo teto):**
| Nome | Parentesco | Idade | Renda mensal | Fonte da renda |
|------|-----------|-------|-------------|----------------|
| [nome] | [relacao] | [idade] | [R$] | [trabalho/beneficio/nenhuma] |

**RENDA FAMILIAR:**
- Renda bruta total da familia: [R$]
- Numero de membros do nucleo familiar: [numero]
- Renda per capita: [R$]
- Salario minimo vigente: [R$]
- 1/4 do SM: [R$]
- Despesas extraordinarias (medicamentos, tratamentos, fraldas): [R$ e descricao]

**SITUACAO DE SAUDE (se PcD):**
- Doenca/Deficiencia principal: [CID e descricao]
- Limitacoes funcionais: [o que nao consegue fazer / barreiras enfrentadas]
- Tratamentos em curso: [medicamentos, terapias, internacoes]
- Laudos medicos disponiveis: [sim/nao — quais, datas]

**PROVAS DISPONIVEIS:**
[Liste os documentos que possui:
- Carta de indeferimento do INSS
- Comprovante de inscricao no CadUnico
- Laudos e atestados medicos (com CID)
- Receituarios medicos
- Comprovantes de renda da familia (ou declaracao de hipossuficiencia)
- Comprovante de residencia
- Certidao de nascimento/casamento
- Declaracao de composicao familiar
- Fotos da moradia (se relevante)
- Relatorio de assistente social (se houver)
- Outros]

**INFORMACOES ADICIONAIS:**
- Competencia: [JEF ou Vara Federal — cidade/secao]
- Ha urgencia para tutela antecipada? [sim/nao — motivo: risco alimentar, saude, situacao de rua]
- Recebe outro beneficio atualmente? [sim/nao — qual]
- Outro idoso da familia recebe BPC? [sim/nao]
- Recebe Bolsa Familia? [sim/nao — valor]
- Observacoes: [qualquer informacao adicional relevante]
</template_dados>

<dicas>
1. **Cadastro Unico atualizado e essencial** — O CadUnico e a principal fonte de informacao sobre a composicao e renda familiar. Oriente o cliente a atualiza-lo antes do ajuizamento.
2. **Relativize o criterio de renda** — Mesmo que a renda per capita supere 1/4 SM, argumente com base no RE 567.985/MT. Apresente gastos com saude, moradia precaria e vulnerabilidade social.
3. **Exclua beneficios de outros idosos** — O art. 20, §14, da Lei 8.742/93 determina que o BPC recebido por outro idoso da familia nao entra no calculo da renda per capita.
4. **Peca avaliacao biopsicossocial** — Para PcD, a deficiencia deve ser avaliada conforme modelo biopsicossocial (Lei 13.146/2015), nao apenas pela limitacao medica.
5. **Documente a vulnerabilidade** — Fotos da moradia, relatorios do CRAS, declaracoes de vizinhos e estudo social fortalecem a tese de miserabilidade.
6. **BPC e Bolsa Familia sao cumulaveis** — Desde a Lei 14.601/23, a acumulacao e permitida. O Bolsa Familia nao deve ser computado como renda.
7. **Efeitos financeiros** — A Sumula 79 da TNU limita os efeitos financeiros a data do requerimento administrativo. Certifique-se de que a DER esteja correta.

---
*Skills Jurídicas com IA — RSA Advocacia*
</dicas>
