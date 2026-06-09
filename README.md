# Skills Jurídicas — Formato SKILL.md

> 415 skills jurídicas convertidas para o formato `SKILL.md`, compatível com **Claude Code**, **Antigravity** e qualquer sistema de agentes IA que use *Intelligent Routing*.

## Diferença para o repositório original

| Original (`skills-juridicas-ia`) | Este repositório |
|---|---|
| Prompts para copiar e colar | Skills carregadas automaticamente pelo agente |
| Uso manual | Uso autônomo via routing semântico |
| Arquivo único por área | Pasta `area/skill/SKILL.md` por peça |
| Sem metadados estruturados | YAML frontmatter + tags XML |

## Estrutura

```
area/
  nome_da_peca/
    SKILL.md   ← persona + regras + framework + template de dados
```

## Áreas disponíveis (23)

| Área | Skills |
|---|---|
| administrativo | 14 |
| aeronautico | 12 |
| agrario | 7 |
| ambiental | 14 |
| bancario | 14 |
| civel | 39 |
| consumidor | 19 |
| contratos | 22 |
| desportivo | 12 |
| digital_lgpd | 17 |
| eleitoral | 7 |
| familia | 30 |
| ferramentas | 1 |
| free_gratuitas | 5 |
| imobiliario | 22 |
| internacional | 6 |
| militar | 10 |
| penal | 35 |
| previdenciario | 28 |
| regulatorio | 7 |
| saude | 14 |
| societario | 8 |
| trabalhista | 38 |
| tributario | 35 |

## Como usar com Claude Code

```bash
# Clone para o diretório de skills do seu agente
git clone https://github.com/ericbmen/skills-juridicas-formatted ~/.claude/skills/juridicas

# O Claude carregará automaticamente via Intelligent Routing
```

## Repositório original

Prompts originais: [ericbmen/skills-juridicas-ia](https://github.com/ericbmen/skills-juridicas-ia)

---
*Gerado automaticamente via Claude — Conversão para formato SKILL.md*