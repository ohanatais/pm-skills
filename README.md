# pm-skills

> Skills de Claude Code para o dia a dia de quem trabalha com produto.

**Em PT-BR. Para o trabalho real e recorrente de Product Management.**

Parte do ecossistema [build-from-zero](https://github.com/ohanatais/build-from-zero), com um foco diferente: enquanto os repos do build-from-zero te levam de uma ideia até o lançamento, o `pm-skills` é sobre o trabalho que se repete depois que o produto já existe e está em operação. Priorizar, especificar, comunicar, analisar. As tarefas de toda semana de um PM.

---

## O que são skills de Claude Code?

Skills são arquivos de instrução que ficam na pasta `.claude/skills/` do seu projeto.
Quando você trabalha com Claude Code, ele lê essas skills automaticamente e sabe
exatamente qual framework, qual abordagem, e qual padrão aplicar para cada tarefa.

Pensa assim: você não precisa mais explicar do zero o que quer que o Claude faça.
A skill já carrega esse contexto, e ele executa como se fosse uma PM sênior do seu lado
em cada tipo de tarefa.

---

## Onde o pm-skills se encaixa

| | build-from-zero | pm-skills |
|---|---|---|
| Momento | tirar uma ideia do zero até o lançamento | tocar um produto que já está no ar |
| Skills | pesquisa, validação, personas, posicionamento, marca, copy, build, go-to-market | descoberta, priorização, especificação, comunicação, análise |
| Onde vivem | dentro de cada repo de conteúdo (product-thinking, brand-and-copy, etc.) | aqui |

Um exemplo da diferença: o build-from-zero tem `prd`, a versão enxuta de PRD para um solo builder escrevendo do zero. O `pm-skills` cuida do PRD de um produto que **já existe** — refinar, versionar, manter coerência com o que já foi entregue.

---

## Skills planejadas

> Esta lista é um rascunho de direção, não um compromisso fechado. Vai mudar conforme as
> skills forem construídas e testadas no uso real.

### Descoberta e priorização
| Skill | O que faz |
|---|---|
| `discovery-continuo` | Roteiros de entrevista e síntese de sinais de descoberta contínua |
| `priorizacao` | RICE, impacto-esforço e afins, para decidir com clareza o que entra agora |
| `feedback-em-temas` | Transformar feedback solto (tickets, reviews, vendas) em temas acionáveis |

### Especificação e execução
| Skill | O que faz |
|---|---|
| `refino-de-prd` | Refinar o PRD de um produto já em operação, mantendo coerência com o entregue |
| `fatiar-epics` | Quebrar épicos em histórias finas, sequenciadas e independentes |
| `criterios-de-aceite` | Escrever critérios de aceite claros e testáveis |

### Comunicação e stakeholders
| Skill | O que faz |
|---|---|
| `update-de-status` | Draft de update executivo e status report direto ao ponto |
| `release-notes` | Release notes e changelog na voz do produto |
| `narrativa-de-roadmap` | Transformar um roadmap em uma narrativa que convence |

### Análise
| Skill | O que faz |
|---|---|
| `metricas-e-kpis` | Definir a métrica ou KPI e a pergunta de produto que ela responde |
| `teardown-competitivo` | Análise rápida de um concorrente com leitura acionável |

---

## Como instalar e usar

```bash
# 1. Clone este repositório
git clone https://github.com/ohanatais/pm-skills.git

# 2. Copie a skill desejada para o seu projeto
cp -r pm-skills/priorizacao /seu-projeto/.claude/skills/

# 3. No Claude Code, a skill é ativada automaticamente quando relevante
#    Ou você pode invocar manualmente:
#    /priorizacao
```

Se você ainda não tem o Claude Code instalado, o guia completo está em
[build-with-claude](https://github.com/ohanatais/build-with-claude).

---

## Status

> Repo recém-reposicionado. Nenhuma skill construída ainda; tudo abaixo está planejado.

| Skill | Status |
|---|---|
| `priorizacao` | 📋 Planejada |
| `feedback-em-temas` | 📋 Planejada |
| `discovery-continuo` | 📋 Planejada |
| `refino-de-prd` | 📋 Planejada |
| `fatiar-epics` | 📋 Planejada |
| `criterios-de-aceite` | 📋 Planejada |
| `update-de-status` | 📋 Planejada |
| `release-notes` | 📋 Planejada |
| `narrativa-de-roadmap` | 📋 Planejada |
| `metricas-e-kpis` | 📋 Planejada |
| `teardown-competitivo` | 📋 Planejada |

---

## Sobre

Feito por [Ohana Taís](https://github.com/ohanatais) — Senior PM, construindo em público.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ohanatais-blue?style=flat&logo=linkedin)](https://linkedin.com/in/ohana-taís)
