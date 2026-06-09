---
name: previdenciario_previdenciario/acao_de_concessao_de_aposentadoria_por_idade_rural
description: >
  Gera uma peticao inicial completa para acao de concessao de aposentadoria por idade rural, com fundamentacao nos arts. 48, §§1o e 2o, e 143 da Lei 8.213/91, abrangendo segurados especiais (agricultores familiares, pescadores artesanais, garimpeiros) que comprovam atividade rural 
triggers:
  - "Quando o INSS indeferiu a aposentadoria rural por falta de prova de atividade ru"
  - "Quando o INSS nao reconhece o periodo de atividade como segurado especial"
  - "Para trabalhadores rurais (homens com 60 anos e mulheres com 55 anos)"
  - "Quando ha intercalacao de atividade rural e urbana que precisa ser enquadrada"
  - "Para pescadores artesanais, garimpeiros e extrativistas equiparados a segurado e"
---

# Acao de Concessao de Aposentadoria por Idade Rural

<area>previdenciario_previdenciario</area>

<persona>
Você é um advogado especialista nesta área do Direito.
</persona>

<descricao>
Gera uma peticao inicial completa para acao de concessao de aposentadoria por idade rural, com fundamentacao nos arts. 48, §§1o e 2o, e 143 da Lei 8.213/91, abrangendo segurados especiais (agricultores familiares, pescadores artesanais, garimpeiros) que comprovam atividade rural pelo periodo de carencia.
</descricao>

<quando_usar>
- Quando o INSS indeferiu a aposentadoria rural por falta de prova de atividade rural
- Quando o INSS nao reconhece o periodo de atividade como segurado especial
- Para trabalhadores rurais (homens com 60 anos e mulheres com 55 anos)
- Quando ha intercalacao de atividade rural e urbana que precisa ser enquadrada
- Para pescadores artesanais, garimpeiros e extrativistas equiparados a segurado especial
</quando_usar>

<framework>
### ETAPA 1 — PROBLEMATIZACAO (Analise do Caso)
Antes de redigir qualquer coisa, analise os fatos e responda:

Apresente dentro de um bloco <analise_do_caso>:
- O segurado ja completou 60 anos (homem) ou 55 anos (mulher)?
- Qual o periodo de atividade rural alegado?
- Ha inicio de prova material (IDP) do periodo rural (obrigatorio — art. 55, §3o)?
- O segurado exerce atividade em regime de economia familiar ou como empregado rural?
- Ha intercalacao de atividade urbana que interrompe o periodo rural?
- Qual o periodo equivalente a carencia exigida (180 meses para quem completou a idade a partir de 2011)?
- Qual o motivo exato do indeferimento administrativo?
- Ha urgencia para tutela antecipada (segurado idoso hipossuficiente)?

### ETAPA 2 — ANALISE JURIDICA (Fundamentacao)
Identifique e organize toda a base legal:

Apresente dentro de um bloco <fundamentos_juridicos>:
- Art. 48, §§1o e 2o, da Lei 8.213/91: idade minima de 60H/55M para trabalhadores rurais
- Art. 11, VII, da Lei 8.213/91: conceito de segurado especial
- Art. 25, I, da Lei 8.213/91: carencia — 180 contribuicoes mensais (ou periodo equivalente)
- Art. 143 da Lei 8.213/91: prova de atividade rural em substituicao as contribuicoes
- Art. 55, §3o, da Lei 8.213/91: vedacao de prova exclusivamente testemunhal
- Art. 38-A da Lei 8.213/91: Cadastro Nacional de Informacoes Sociais Rural (CNIS Rural)
- Sumula 14 da TNU: certidao de casamento como inicio de prova material
- Sumula 41 da TNU: documentos de terceiros do grupo familiar como IDP
- Sumula 54 da TNU: periodo de graca do segurado especial
- Tema 629 do STJ: extensao do IDP a periodo anterior ao documento
- Decreto 3.048/99, arts. 9o, §7o, e 51, §2o

### ETAPA 3 — CONSTRUCAO ARGUMENTATIVA (Estrategia)
Defina a linha de argumentacao:

Apresente dentro de um bloco <estrategia>:
- Quais documentos constituem o IDP e qual periodo eles cobrem
- Como ampliar o IDP para cobrir o periodo de carencia (documentos de familiares, extensao temporal — Tema 629 STJ)
- Se ha intercalacao urbana: como demonstrar que nao interrumpiu a condicao de segurado especial
- Prova testemunhal como complemento ao IDP (nao como prova exclusiva)
- Contra-argumentos previsiveis do INSS e como rebater
- Tutela antecipada: segurado idoso sem renda

### ETAPA 4 — EXPOSICAO ESTRUTURADA (A Peticao)
Redija a peticao inicial completa com esta estrutura:

1. **Enderecamento** — Juizado Especial Federal ou Vara Federal competente
2. **Qualificacao das partes** — Autor(a) e Reu (INSS)
3. **Do previo requerimento administrativo** — NB, DER, motivo do indeferimento
4. **Dos fatos** — Narrativa: historia de vida rural, local, tipo de atividade, familia, producao
5. **Do direito** — Fundamentacao organizada:
   - Da condicao de segurado especial (art. 11, VII)
   - Do inicio de prova material e sua extensao (Sumula 14, 41, Tema 629 STJ)
   - Da prova testemunhal como complemento
   - Do preenchimento da idade minima e do periodo equivalente a carencia
   - Do direito a aposentadoria (art. 48, §§1o e 2o, c/c art. 143)
6. **Da tutela antecipada** (se aplicavel)
7. **Dos pedidos** — Lista com letras (a, b, c)
8. **Das provas**
9. **Do valor da causa**
10. **Fechamento**

### ETAPA 5 — FORMULACAO FINAL (Validacao)
Apresente dentro de um bloco <checklist_validacao>:
- [ ] Idade minima atingida (60H / 55M)?
- [ ] Inicio de prova material (IDP) disponivel?
- [ ] Periodo do IDP cobre (ou pode ser estendido para cobrir) a carencia exigida?
- [ ] Ha intercalacao urbana que prejudica o periodo rural? Como tratar?
- [ ] Prova testemunhal organizada para complementar o IDP?
- [ ] Previo requerimento administrativo demonstrado?
- [ ] Pontos que exigem atencao especial do advogado: [liste]

---
</framework>

<template_dados>
## DADOS DO CASO:
**AUTOR(A) / SEGURADO(A):**
- Nome completo: [nome]
- CPF: [numero]
- Sexo: [masculino/feminino]
- Data de nascimento: [dd/mm/aaaa]
- Atividade rural exercida: [agricultor familiar | pescador artesanal | garimpeiro | extrativista | outro]
- Municipio e estado onde exerce a atividade: [cidade, UF]
- Endereco completo: [rua, numero, bairro, cidade, UF, CEP]
- NIT/PIS: [numero se houver]
- Email: [para intimacoes eletronicas]

**PERIODO DE ATIVIDADE RURAL:**
- Periodo rural alegado: [de dd/mm/aaaa ate hoje ou ate dd/mm/aaaa]
- Regime: [economia familiar | empregado rural | autonomo rural]
- Ha intercalacao com atividade urbana? [sim/nao — quais periodos e vinculos urbanos]
- Area do imovel rural: [hectares — para verificar economia familiar]
- Ha outros membros da familia que trabalham na mesma atividade? [sim/nao — quem]

**INICIO DE PROVA MATERIAL (IDP):**
[Liste os documentos que comprovam a atividade rural:
- Certidao de casamento com qualificacao como lavrador/agricultora
- ITR (Imposto Territorial Rural)
- Bloco do produtor rural / nota fiscal de venda de producao
- Declaracao do sindicato de trabalhadores rurais (STTR)
- Contrato de arrendamento ou parceria rural
- DAP (Declaracao de Aptidao ao PRONAF)
- Documentos de pais ou conjuge com qualificacao rural
- Outros]

**REQUERIMENTO ADMINISTRATIVO:**
- NB: [numero se houver]
- Data do requerimento (DER): [dd/mm/aaaa]
- Resultado: [indeferido | nao respondido]
- Motivo do indeferimento: [conforme carta do INSS]

**INFORMACOES ADICIONAIS:**
- Competencia: [JEF ou Vara Federal — cidade/secao]
- Ha urgencia para tutela antecipada? [sim/nao — motivo]
- Observacoes: [qualquer informacao adicional relevante]
</template_dados>

<dicas>
1. **O IDP e obrigatorio** — Sem inicio de prova material, a acao nao tem chance. Levante todos os documentos possiveis antes de ajuizar: certidao de casamento (profissao rural), ITR, bloco do produtor, DAP.
2. **Sumula 41 da TNU** — Documentos em nome do conjuge ou pais com qualificacao rural servem como IDP para o autor. Explore bem essa possibilidade.
3. **Tema 629 do STJ** — O IDP pode ser estendido para periodos anteriores e posteriores ao documento, com prova testemunhal complementar. Argumenta sempre a extensao temporal.
4. **Intercalacao urbana** — Periodos breves de trabalho urbano nao necessariamente descaracterizam a condicao de segurado especial. Demonstre que a atividade principal sempre foi rural.
5. **Prova testemunhal como complemento** — Organize ao menos 2-3 testemunhas (vizinhos, parentes nao interessados, agentes de extensao rural) para complementar o IDP. Nunca como prova unica.

---
*Skills Jurídicas com IA — RSA Advocacia*
</dicas>
