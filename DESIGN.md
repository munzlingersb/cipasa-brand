---
version: alpha
name: Cipasa Urbanismo — Verana Parque Alvorada
description: >
  Dois layers de marca: Cipasa Urbanismo (corporativo, 35 anos, verde-limão
  energético) e Verana Parque Alvorada (sub-marca aspiracional de Marília-SP,
  comunidade integrada à natureza, verde-floresta + coral quente). Criativos
  Meta Ads usam exclusivamente a paleta VPA. Materiais institucionais usam
  a paleta Cipasa corporate.

# Compliance: follows DESIGN.md spec (alpha) — google-labs-code/design.md
# Section order: Overview · Colors · Typography · Layout · Shapes · Components · Do's and Don'ts

colors:
  # ── VPA ad palette — usada em todos os criativos Meta Ads ────────────────
  vpa-ink:        "#0F1714"   # texto escuro sobre fundos claros
  vpa-forest:     "#2A5C3C"   # verde floresta VPA — tarjas, backgrounds, CTAs
  vpa-grass:      "#4D7C0F"   # verde médio — pinos de mapa, barras, checkmarks
  vpa-sage:       "#6B9E3A"   # verde claro — detalhe, outline map, secondary bars
  vpa-coral:      "#E5734A"   # coral VPA — CTA principal, pin destaque, destaques
  vpa-paper:      "#F5F4EE"   # off-white papel — fundo cards editoriais
  vpa-sky:        "#5BA8D9"   # azul céu Marília (aparece em fotos aéreas)

  # ── Cipasa corporate — branding institucional, não ads ───────────────────
  corp-lime:      "#62BB46"   # verde-limão Cipasa (logo, nav ativa, badge site)
  corp-forest:    "#005A45"   # verde institucional (CTA site)
  corp-ink:       "#112A25"   # quase-preto verde (headlines site)
  corp-gold:      "#C6AA6E"   # dourado (projetos premium, selos)

  # ── Neutros compartilhados ────────────────────────────────────────────────
  neutral-off:    "#F8FAF9"   # branco levemente esverdeado (cards site)
  neutral-mid:    "#555454"   # cinza botões secundários
  neutral-light:  "#F4F4F4"   # cinza claro backgrounds

typography:
  display:
    fontFamily: Montserrat
    fontSize: 3.5rem
    fontWeight: "800"
    lineHeight: "1.1"
    letterSpacing: "-0.02em"
  h1:
    fontFamily: Work Sans
    fontSize: 3.2rem
    fontWeight: "700"
    lineHeight: "1.15"
  h2:
    fontFamily: Work Sans
    fontSize: 2rem
    fontWeight: "600"
    lineHeight: "1.2"
  h3:
    fontFamily: Work Sans
    fontSize: 1.25rem
    fontWeight: "600"
    lineHeight: "1.3"
  body-lg:
    fontFamily: Work Sans
    fontSize: 1.125rem
    fontWeight: "400"
    lineHeight: "1.6"
  body-md:
    fontFamily: Work Sans
    fontSize: 1rem
    fontWeight: "400"
    lineHeight: "1.6"
  label:
    fontFamily: Work Sans
    fontSize: 0.75rem
    fontWeight: "600"
    lineHeight: "1"
    letterSpacing: "0.08em"
  ad-headline:
    fontFamily: Work Sans
    fontSize: 3.5rem
    fontWeight: "900"
    lineHeight: "1.05"
    letterSpacing: "-0.01em"
  ad-subhead:
    fontFamily: Work Sans
    fontSize: 1.625rem
    fontWeight: "600"
    lineHeight: "1.25"

rounded:
  none: "0px"
  sm:   "4px"
  md:   "15px"
  lg:   "30px"
  pill: "50px"
  full: "9999px"

spacing:
  1:  "4px"
  2:  "8px"
  3:  "12px"
  4:  "16px"
  5:  "20px"
  6:  "24px"
  8:  "32px"
  10: "40px"
  12: "48px"
  16: "64px"
  20: "80px"
  24: "96px"

components:
  ad-tarja:
    backgroundColor: "{colors.vpa-forest}"
    textColor: "{colors.vpa-paper}"
    typography: label
    rounded: none
    height: "80px"
    padding: "0 24px"

  ad-tarja-slim:
    backgroundColor: "{colors.vpa-forest}"
    textColor: "{colors.vpa-paper}"
    typography: label
    rounded: none
    height: "70px"
    padding: "0 20px"

  ad-pill-badge:
    backgroundColor: "{colors.vpa-paper}"
    textColor: "{colors.vpa-forest}"
    typography: label
    rounded: pill
    padding: "6px 20px"

  cta-primary:
    backgroundColor: "{colors.vpa-coral}"
    textColor: "#FFFFFF"
    typography: label
    rounded: pill
    padding: "14px 32px"

  cta-primary-hover:
    backgroundColor: "#C95A30"
    textColor: "#FFFFFF"
    typography: label
    rounded: pill

  cta-secondary:
    backgroundColor: "{colors.corp-forest}"
    textColor: "#FFFFFF"
    typography: label
    rounded: pill
    padding: "14px 32px"

  logo-badge:
    backgroundColor: "#FFFFFF"
    rounded: full
    padding: "8px"
    height: "90px"

  pin-main:
    backgroundColor: "{colors.vpa-coral}"
    size: "24px"

  pin-secondary:
    backgroundColor: "{colors.vpa-grass}"
    size: "16px"

  map-label-box:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.vpa-ink}"
    typography: label
    rounded: sm
    padding: "4px 10px"

  big-number:
    fontFamily: Work Sans
    fontSize: "160px"
    fontWeight: "900"
    textColor: "{colors.vpa-coral}"

  divider-coral:
    backgroundColor: "{colors.vpa-coral}"
    width: "120px"
    height: "4px"
---

## Overview

Cipasa Urbanismo é uma loteadora nacional com 35 anos de história, presente em 21 estados. A linguagem visual é **autoridade verde + modernidade limpa**: não é construtora de luxo nem popular — é aspiracional familiar, acessível a quem valoriza qualidade de vida.

**Verana Parque Alvorada** (VPA) é o empreendimento de Marília-SP. A sub-marca usa uma paleta mais escura, editorial e quente que o corporate: verde-floresta profundo como âncora, coral como energia e apelo à ação, off-white papel como respiro. O mood é "fim de semana quieto, espaço para crescer".

**Dois layers, uma hierarquia:**
- Cipasa corporate (verde-limão `#62BB46`): confiança institucional, usa-se em materiais de marca e FAQ
- VPA sub-brand (verde-floresta `#2A5C3C` + coral `#E5734A`): criativos de Ads, carrosseis, stories

## Colors

### VPA Ad Palette (uso em criativos Meta Ads)

| Token | Hex | Uso |
|---|---|---|
| `vpa-forest` | `#2A5C3C` | Tarjas, fundos, backgrounds, CTAs dark |
| `vpa-grass` | `#4D7C0F` | Pinos de mapa, barras comparativas, checkmarks |
| `vpa-coral` | `#E5734A` | Pin principal, CTA button, destaques, dividers |
| `vpa-paper` | `#F5F4EE` | Background de cards editoriais (mapas, gráficos) |
| `vpa-ink` | `#0F1714` | Texto escuro sobre fundo claro |
| `vpa-sage` | `#6B9E3A` | Versão mais clara de grass (bordas de mapa, sombra) |

**Regra de contraste:** texto claro sobre `vpa-forest` tem ratio ≥ 7:1. Coral sobre branco é borderline — usar apenas em tamanho ≥ 24px ou bold.

### Cipasa Corporate

Não misturar verde-limão `#62BB46` com verde-floresta `#2A5C3C` no mesmo ad — paletas distintas, contextos distintos.

## Typography

Dois pesos de marca Work Sans conduzem a hierarquia: **900/700 para headlines visuais**, **400/500 para corpo**. Montserrat reservada para display type muito grande (herói, cartão-destaque), nunca em body.

**Regras de escala em Ads 1080×1080:**
- H1 dentro da imagem: `ad-headline` (Work Sans 900, ~56–64px no canvas)
- Tarja pill badge: `label` com letterSpacing 0.08em, máximo 35 caracteres
- Body/copy embaixo da imagem: `body-md` 16–18px em fonte do Meta

**Pesos permitidos:** 300 · 400 · 500 · 600 · 700 · 800 · 900

**Não usar:** Itálico em headlines de produto (ok em storyselling aspiracional). Nunca texto sobre gradiente.

## Layout

**Grade de ads 1080×1080:**
- Tarja no topo: 70–80px de altura fixo, full width
- Zona limpa (negativo superior): mínimo 200px — onde o headline do Meta aparece
- Logo rodapé: 80–90px de altura, posicionado 24px da borda inferior-direita
- Margem de segurança: 40px em todos os lados para garantir que nada seja cortado

**Grade de stories 1080×1920:**
- Zona segura superior: 250px (notch/câmera)
- Zona segura inferior: 300px (swipe-up indicator)
- Split portrait: 65% imagem / 35% bloco de texto verde-floresta

**Ritmo de espaçamento:** nunca padding uniforme. Variar: header tight, corpo respirado, rodapé moderado.

## Elevation & Depth

Fundo fotográfico com leve overlay escuro (`rgba(15, 23, 20, 0.25)`) para garantir legibilidade da tarja. Não usar sombras em texto — preferir área negativa clara (céu aberto) ou tarja opaca.

Cards informativos (mapas, gráficos): fundo `vpa-paper` com sombra `box-shadow: 0 2px 12px rgba(15,23,20,0.08)`.

## Shapes

- **Botão CTA:** pill `border-radius: 50px` — nunca quadrado ou apenas arredondado
- **Badge de tarja:** pill interno `border-radius: 9999px` dentro da tarja retangular
- **Cards informativos:** `border-radius: 15px`
- **Logo em rodapé:** círculo ou badge circular com fundo branco
- **Sem side-stripe borders** — se precisa delimitar, use background tint ou borda completa

## Components

### Tarja de topo (ad)
Faixa verde-floresta `#2A5C3C` full width, altura 70–80px. Dentro: pill badge off-white com texto label do empreendimento em Work Sans Semibold 600.
```
[    VERANA PARQUE ALVORADA · MARÍLIA    ]  ← pill badge centralizado na tarja
```
Variação: pill pode ficar alinhado à esquerda com logo à direita na tarja.

### CTA Button (em cards com fundo escuro)
Pill coral `#E5734A`, Work Sans 600, texto branco, padding 14×32px.
Hover: `#C95A30` (15% mais escuro).

### Logo badge (rodapé)
Logo Verana sobre círculo branco 90px de diâmetro, opacidade 95%, 24px da borda inferior-direita.

### Big Number (cards de investimento)
Montserrat Black ou Work Sans 900, coral `#E5734A`, ~140–160px. Nunca caber dois big numbers na mesma tela.

### Mapa editorial
Fundo `vpa-paper`, roads finas verde-floresta, bairros off-white distintos. Pinos de localização: coral (VPA, tamanho 1.5×) e verde-grass (outros pontos). Labels em caixinhas brancas Work Sans 13px.

## Do's and Don'ts

**Do:**
- Usar foto real do empreendimento como background — nunca render 3D genérico
- Deixar zona de negativo no superior-direito para texto do Meta
- Tarja + pill badge em cards com foto dark
- Coral apenas para o elemento mais importante da tela
- Work Sans 900 em headlines curtos (≤ 40 chars)
- Escalar família de verde (`vpa-forest → vpa-grass → vpa-sage`) para hierarquia de dados

**Don't:**
- Misturar verde-limão Cipasa (`#62BB46`) com verde-floresta VPA na mesma peça
- Texto no terço central da imagem (área de eye-tracking do feed)
- Gradiente de texto (`background-clip: text`) — proibido pelo spec
- Glassmorphism decorativo
- Mais de 2 pesos tipográficos por card
- Imagem com pessoas olhando direto para câmera (break fourth wall — gera rejeição)
- Lawns super-saturados ou cores neon
- Compor card com mais de 1 big number
