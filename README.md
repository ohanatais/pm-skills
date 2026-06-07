# pm-skills

> Skills de Claude Code para cada etapa da jornada de produto — do zero ao lançamento.

**Em PT-BR. Para quem está aprendendo e construindo ao mesmo tempo.**

Parte do ecossistema [build-from-zero](https://github.com/ohanatais/build-from-zero).

---

## O que são skills de Claude Code?

Skills são arquivos de instrução que ficam na pasta `.claude/skills/` do seu projeto.
Quando você trabalha com Claude Code, ele lê essas skills automaticamente e sabe
exatamente qual framework, qual abordagem, e qual padrão aplicar para cada tarefa.

Pensa assim: você não precisa mais explicar do zero o que quer que o Claude faça.
A skill já carrega esse contexto — e ele executa como se fosse uma consultora especialista
em cada área.

---

## Skills disponíveis

### Produto
| Skill | O que faz |
|---|---|
| `pesquisa-de-mercado` | Pesquisa e análise de mercado estruturada | 
| `validacao-de-ideia` | Framework de validação antes de escrever uma linha de código |
| `personas` | Criação de personas com profundidade real, não cartão de visita |
| `posicionamento` | Análise de oceano azul/vermelho, diferenciação e posicionamento |
| `prd` | PRD enxuto para solo builders — o que é necessário, nada mais |

### Marca e comunicação
| Skill | O que faz |
|---|---|
| `identidade-visual` | Briefing de marca, paleta, tipografia e tom visual |
| `tom-de-voz` | Definição de voz e tom para produto digital |
| `copy-de-produto` | Copy de landing page, onboarding e produto que converte |

### Build
| Skill | O que faz |
|---|---|
| `decisoes-tecnicas` | Explica cada decisão técnica em linguagem humana |
| `setup-de-ferramentas` | Guia de configuração (Supabase, Vercel, etc.) para não-devs |

### Go-to-market
| Skill | O que faz |
|---|---|
| `estrategia-de-lancamento` | Planejamento de lançamento para produto sem audiência |
| `primeiros-usuarios` | Como conseguir os primeiros 10, 50, 100 usuários reais |

**Legenda:** Skills marcadas com 🔄 estão em construção. As demais estão planejadas.

---

## Como instalar e usar

```bash
# 1. Clone este repositório
git clone https://github.com/ohanatais/pm-skills.git

# 2. Copie a skill desejada para o seu projeto
cp -r pm-skills/pesquisa-de-mercado /seu-projeto/.claude/skills/

# 3. No Claude Code, a skill é ativada automaticamente quando relevante
#    Ou você pode invocar manualmente:
#    /pesquisa-de-mercado
```

Se você ainda não tem o Claude Code instalado, o guia completo está em
[build-with-claude](https://github.com/ohanatais/build-with-claude).

---

## Status

| Skill | Status |
|---|---|
| `pesquisa-de-mercado` | 🔄 Em construção |
| `validacao-de-ideia` | 📋 Planejada |
| `personas` | 📋 Planejada |
| `posicionamento` | 📋 Planejada |
| `prd` | 📋 Planejada |
| `identidade-visual` | 📋 Planejada |
| `tom-de-voz` | 📋 Planejada |
| `copy-de-produto` | 📋 Planejada |
| `decisoes-tecnicas` | 📋 Planejada |
| `setup-de-ferramentas` | 📋 Planejada |
| `estrategia-de-lancamento` | 📋 Planejada |
| `primeiros-usuarios` | 📋 Planejada |

---

## Sobre

Feito por [Ohana Taís](https://github.com/ohanatais) — Senior PM, construindo em público.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ohana-taís-blue?style=flat&logo=linkedin)](https://linkedin.com/in/ohana-taís)
