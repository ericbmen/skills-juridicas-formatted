---
name: contratos_contratos/sla_acordo_de_nivel_de_servico
description: >
  Elabora Acordos de Nivel de Servico (SLA) completos e juridicamente vinculantes, com fundamentacao nos arts. 421-422 do Codigo Civil (funcao social e boa-fe objetiva) e nos arts. 408-416 CC (clausula penal), estruturando metricas de disponibilidade, suporte, tempo de resposta, re
triggers:
  - "Para definir metricas de disponibilidade em contratos de TI e SaaS"
  - "Como anexo tecnico a contratos de prestacao de servicos"
  - "Para formalizar compromisos de suporte em contratos de manutencao"
  - "Em contratos com provedores de infraestrutura e nuvem (cloud)"
  - "Para definir penalidades por descumprimento de indicadores de servico"
---

# SLA — Acordo de Nivel de Servico

<area>contratos_contratos</area>

<persona>
Você é um advogado especialista nesta área do Direito.
</persona>

<descricao>
Elabora Acordos de Nivel de Servico (SLA) completos e juridicamente vinculantes, com fundamentacao nos arts. 421-422 do Codigo Civil (funcao social e boa-fe objetiva) e nos arts. 408-416 CC (clausula penal), estruturando metricas de disponibilidade, suporte, tempo de resposta, resolucao de incidentes, penalidades por descumprimento e procedimentos de escalonamento. O SLA pode ser um documento autonomo ou um anexo tecnico a um contrato de servicos ou SaaS. Aplica o framework P.A.C.E.F para garantir que os niveis de servico sejam mensuráveis, monitoraveis e executaveis juridicamente.
</descricao>

<quando_usar>
- Para definir metricas de disponibilidade em contratos de TI e SaaS
- Como anexo tecnico a contratos de prestacao de servicos
- Para formalizar compromisos de suporte em contratos de manutencao
- Em contratos com provedores de infraestrutura e nuvem (cloud)
- Para definir penalidades por descumprimento de indicadores de servico
- Em contratos de outsourcing de TI ou operacoes
</quando_usar>

<framework>
### ETAPA 1 — PROBLEMATIZACAO
Apresente dentro de um bloco <analise_do_caso>:
- Qual e o servico objeto do SLA?
- Quais sao as metricas mais criticas para o contratante?
- Qual o impacto do descumprimento no negocio do contratante?
- Ha dados pessoais envolvidos? (LGPD)
- O SLA e documento autonomo ou anexo ao contrato principal?
- Quais excecoes (forca maior, janelas de manutencao) devem ser previstas?

### ETAPA 2 — ANALISE JURIDICA (Fundamentacao)
Apresente dentro de um bloco <fundamentos_juridicos>:
- **Arts. 408-416 CC:** clausula penal como mecanismo de estimulo ao cumprimento
- **Art. 389-395 CC:** inadimplemento e suas consequencias
- **Art. 413 CC:** possibilidade de reducao judicial da pena excessiva — dimensionar corretamente
- **LGPD:** obrigacoes de seguranca e comunicacao de incidentes
- **Marco Civil:** responsabilidade por falhas de seguranca
- **Jurisprudencia STJ:** responsabilidade por falha de sistemas e indenizacao por downtime

### ETAPA 3 — CONSTRUCAO ARGUMENTATIVA
Apresente dentro de um bloco <estrategia_contratual>:
- Quais metricas sao criticas e devem ter penalidade mais severa?
- Como calcular uptime (excluir janelas de manutencao, forca maior)?
- Como escalonar as penalidades de forma proporcional ao art. 412 CC?
- Mecanismo de credito vs. reembolso vs. rescisao por descumprimento reiterado
- Procedimento de escalonamento de incidentes (N1, N2, N3)

### ETAPA 4 — EXPOSICAO ESTRUTURADA (O SLA)
Redija o SLA completo:

1. **Titulo e identificacao** — SLA autonomo ou Anexo X ao Contrato [numero]
2. **Partes** — Fornecedor e Cliente, data de vigencia
3. **Clausula 1a — Do Objeto e Escopo** — Servico coberto pelo SLA, o que esta incluido e excluido
4. **Clausula 2a — Das Definicoes** — Glossario tecnico-juridico:
   - Disponibilidade (Uptime): percentual do tempo em que o servico esta operacional
   - Incidente: qualquer interrupção nao planejada ou degradacao do servico
   - Janela de Manutencao: periodo programado de indisponibilidade (nao conta no uptime)
   - Tempo de Resposta: tempo entre abertura do chamado e primeiro retorno do fornecedor
   - Tempo de Resolucao: tempo entre abertura do chamado e resolucao definitiva
   - Prioridade Critica / Alta / Media / Baixa: criterios de classificacao de incidentes
5. **Clausula 3a — Da Disponibilidade (Uptime)** — Percentual minimo garantido (ex: 99,5% mensal), exclusoes validas (janela de manutencao, forca maior, culpa exclusiva do usuario), formula de calculo, mecanismo de monitoramento
6. **Clausula 4a — Do Suporte e Atendimento** — Horarios (comercial / 24x7), canais (email, chat, telefone, portal), SLAs por prioridade:
   | Prioridade | Criterio | Resposta | Resolucao |
   |-----------|---------|---------|---------|
   | Critica | Sistema fora do ar | 1h | 4h |
   | Alta | Funcionalidade critica impactada | 2h | 8h |
   | Media | Funcionalidade nao critica impactada | 4h | 24h |
   | Baixa | Duvida ou melhoria | 8h | 72h |
7. **Clausula 5a — Das Penalidades por Descumprimento** — Escalonamento proporcional:
   - Disponibilidade entre X% e Y%: credito de Z% na mensalidade
   - Disponibilidade abaixo de X%: credito de Z% + direito de rescisao sem multa
   - Descumprimento reiterado de SLA de suporte: multa por incidente
   - Limites legais: arts. 412-413 CC
8. **Clausula 6a — Das Exclusoes de SLA** — Hipoteses em que o descumprimento nao gera penalidade: forca maior, manutencao programada comunicada com antecedencia, falha de infraestrutura do cliente, uso inadequado
9. **Clausula 7a — Do Monitoramento e Relatorios** — Dashboard em tempo real, relatorio mensal de disponibilidade, mecanismo de contestacao
10. **Clausula 8a — Da Seguranca e Protecao de Dados (LGPD)** — Medidas de seguranca tecnicas e administrativas (art. 46 LGPD), comunicacao de incidentes de seguranca em ate 72h (art. 48 LGPD)
11. **Clausula 9a — Da Gestao de Incidentes** — Procedimento de escalonamento, responsabilidades, comunicacao ao cliente
12. **Clausula 10a — Da Vigencia e Revisao** — Prazo de vigencia do SLA, procedimento de revisao e atualizacao das metricas
13. **Clausula 11a — Das Disposicoes Gerais** — Relacao com o contrato principal, prevalencia, integralidade

### ETAPA 5 — FORMULACAO FINAL (Validacao)
Apresente dentro de um bloco <checklist_validacao>:
- [ ] As metricas de disponibilidade estao claras e mensuráveis?
- [ ] A formula de calculo do uptime esta definida com as exclusoes validas?
- [ ] Os SLAs de suporte por prioridade estao tabelados e claros?
- [ ] As penalidades sao proporcionais e respeitam o art. 412 CC?
- [ ] Ha procedimento claro de escalonamento de incidentes?
- [ ] As exclusoes de SLA (forca maior, manutencao) estao definidas?
- [ ] Ha mecanismo de monitoramento e relatorio mensal?
- [ ] A clausula LGPD cobre seguranca e comunicacao de incidentes?
- [ ] O SLA esta alinhado ao contrato principal (se e anexo)?

---
</framework>

<dicas>
1. **Metricas devem ser mensuráveis** — SLA com metricas vagas e ineficaz. Defina percentuais, horas e criterios objetivos.
2. **Escalonamento proporcional de penalidades** — Penalidades progressivas (quanto maior o descumprimento, maior a multa) sao mais eficazes e juridicamente sustentaveis.
3. **Limite de clausula penal** — A soma das penalidades nao pode exceder o valor da obrigacao principal (art. 412 CC). Dimensione corretamente.
4. **Exclusoes de SLA sao essenciais** — Sem exclusoes claras, o fornecedor fica exposto a penalidades por eventos fora do seu controle.
5. **Relatorio mensal e obrigatorio** — Transparencia no monitoramento reduz disputas e aumenta a confianca contratual.

---
**Tags:** Avancado | Template | Juridico & Compliance | Contratos | TI | SLA | SaaS

---
*Skills Jurídicas com IA — RSA Advocacia*
</dicas>
