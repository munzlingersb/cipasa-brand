---
version: alpha
name: Cipasa Urbanismo — 35 Anos
description: >
  Marca corporativa da Cipasa Urbanismo na campanha de 35 anos (2026).
  Conceito central: "Aqui, fazer bem feito faz diferença!" — estrutural,
  atravessa comunicação externa, discurso comercial, cultura interna e
  próximos lançamentos. 21 estados, 35 anos de história.

# Compliance: follows DESIGN.md spec (alpha) — google-labs-code/design.md
# Fontes verificadas: site cipasa.com (Work Sans UI + Montserrat editorial)
# Cores verificadas: SVG original do logo + inspeção CSS do site

colors:
  # ── Verdes primários — extraídos do SVG original e do site ──────────────
  verde-lime:      "#62BB46"   # anel ícone · CTA float WA · badge newsletter · accent ←SVG
  verde-corpo:     "#005A45"   # CIPASA URBANISMO wordmark · CTAs outline · links footer ←SVG+site
  verde-35anos:    "#20592D"   # badge 35 anos mark ←SVG
  verde-dark:      "#112A25"   # headings Montserrat site · bottom bar footer ←site
  verde-hover:     "#173F35"   # hover states de links e botões ←site
  verde-icon:      "#407A6B"   # ícones secundários ←site

  # ── Paisagem do ícone (uso restrito ao símbolo) ──────────────────────────
  icon-bruma:      "#B0CAC1"   # camada topo da paisagem ←SVG
  icon-nevoa:      "#D8E6DC"   # camada clara da paisagem ←SVG
  icon-terra:      "#407B6B"   # camada inferior da paisagem ←SVG
  icon-campo:      "#82ADA1"   # camada de fundo da paisagem ←SVG

  # ── Neutros — verificados no site ────────────────────────────────────────
  branco:          "#FFFFFF"   # texto sobre dark, card bg
  off-white:       "#F8FAF9"   # backgrounds de seção alternadas ←site
  surface:         "#F5F5F5"   # inputs e superfícies leves ←site
  ink:             "#2C2C2C"   # texto de conteúdo primário ←site (rgb 44,44,37)
  texto-muted:     "#555454"   # footer links, texto secundário ←site
  verde-pale:      "#E8F5E0"   # slides internos claros
  olive:           "#B5C98A"   # ribbons decorativos outdoor/folder

  # ── Bug documentado ──────────────────────────────────────────────────────
  # #1976D2 (azul MUI padrão) aparece 428x no site — NÃO pertence à paleta
  # O tema MUI precisa de palette.primary.main: '#005A45' para corrigir

typography:
  # Work Sans — fonte primária do sistema (UI, anúncios, copy)
  display-ui:
    fontFamily: "Work Sans"
    fontSize: "clamp(2.5rem, 6vw, 5rem)"
    fontWeight: "700"
    lineHeight: "1.04"
    letterSpacing: "-0.025em"

  headline-ui:
    fontFamily: "Work Sans"
    fontSize: "clamp(1.5rem, 3vw, 2.5rem)"
    fontWeight: "700"
    lineHeight: "1.2"

  # Assinatura de campanha — "diferença" e "bem feito"
  # Contexto editorial (slides, key visual, outdoor): Montserrat 900 Italic
  diferenca-editorial:
    fontFamily: Montserrat
    fontSize: "clamp(2.5rem, 7vw, 5rem)"
    fontWeight: "900"
    fontStyle: italic
    lineHeight: "1"
    letterSpacing: "-0.02em"

  # Contexto product/ads (WhatsApp, carrossel feed): Work Sans 900
  diferenca-ads:
    fontFamily: "Work Sans"
    fontSize: "clamp(3rem, 8vw, 6rem)"
    fontWeight: "900"
    lineHeight: "1"
    letterSpacing: "-0.02em"

  # Montserrat — editorial e seções de conteúdo
  h2-editorial:
    fontFamily: Montserrat
    fontSize: "42px"
    fontWeight: "700"
    lineHeight: "1.15"
    textTransform: uppercase

  # Work Sans — labels e UI
  label:
    fontFamily: "Work Sans"
    fontSize: "0.75rem"
    fontWeight: "700"
    lineHeight: "1"
    letterSpacing: "0.08em"

  nav-link:
    fontFamily: "Work Sans"
    fontSize: "14px"
    fontWeight: "500"
    letterSpacing: "0.4px"
    textTransform: uppercase

  body:
    fontFamily: "Work Sans"
    fontSize: "16px"
    fontWeight: "400"
    lineHeight: "1.6"

rounded:
  none: "0px"
  sm:   "4px"
  md:   "8px"
  lg:   "13px"
  xl:   "30px"
  pill: "50px"   # padrão dos CTAs outline do site
  full: "9999px"

spacing:
  1:  "4px"
  2:  "8px"
  4:  "16px"
  6:  "24px"
  8:  "32px"
  12: "48px"
  16: "64px"
  20: "80px"
  24: "100px"   # padding-top do rodapé no site

layout:
  container-max: "1250px"   # max-width do site cipasa.com
  header-height: "100px"
  hero-height:   "650px"

components:
  # CTA principal do site — outline pill
  cta-outline:
    backgroundColor: "transparent"
    textColor: "{colors.verde-corpo}"
    borderColor: "{colors.verde-corpo}"
    borderWidth: "1px"
    rounded: pill
    padding: "0 29px"
    typography: label

  cta-outline-hover:
    backgroundColor: "{colors.verde-corpo}"
    textColor: "{colors.branco}"

  # Botão CTA verde lime (flutuante WA, newsletter)
  cta-filled-lime:
    backgroundColor: "{colors.verde-lime}"
    textColor: "{colors.branco}"
    rounded: lg
    padding: "8px 14px"
    typography: label

  # Badge / iconografia de empreendimento
  icon-badge-filled:
    backgroundColor: "{colors.verde-lime}"
    textColor: "{colors.verde-dark}"
    rounded: md
    borderColor: "{colors.verde-lime}"
    borderWidth: "2px"

  icon-badge-outline:
    backgroundColor: "transparent"
    textColor: "{colors.verde-corpo}"
    rounded: md
    borderColor: "{colors.verde-lime}"
    borderWidth: "2px"

  # Selo 35 anos
  selo-35anos:
    borderColor: "{colors.verde-35anos}"
    borderWidth: "2px"
    rounded: md
    padding: "6px 16px"
    textColor: "{colors.verde-35anos}"

  # Card de empreendimento (site)
  card-empreendimento:
    backgroundColor: "{colors.branco}"
    rounded: none   # full-bleed no site
    # separação por espaçamento, não por sombra

  # Hero overlay
  hero-overlay:
    background: "#000000"
    overlayImage: "PNG com tratamento verde embutido (bg-size: cover)"

  # Gradiente lime strip (anúncios — bottom branding)
  lime-strip:
    background: "linear-gradient(180deg, transparent 0%, rgba(98,187,70,.35) 60%, rgba(98,187,70,.8) 100%)"
    # Aparece no rodapé dos cards WhatsApp e carrossel de amenidades

  # Círculo orgânico (elemento compositivo)
  organic-circle:
    borderRadius: "50%"
    border: "1px solid rgba(98,187,70,.2)"
    background: "rgba(255,255,255,.08)"
    # Decorativo, pode ser cortado pelo frame. Nunca opaco.
---

## Overview

Cipasa Urbanismo completa 35 anos em 2026. O conceito **"Aqui, fazer bem feito faz diferença!"** é estrutural — não apenas uma tagline comemorativa.

**Stack visual:**
- **Work Sans** — fonte primária do sistema: site, anúncios, copy de produto
- **Montserrat** — fonte editorial: headings de seção, key visual da campanha
- **Verde-lime `#62BB46`** — accent único, CTAs, badges, "diferença" em fundo escuro
- **Verde-corpo `#005A45`** — texto principal, outline buttons, wordmark

## Colors

### Paleta verificada — site cipasa.com + SVG original

| Token | Hex | Fonte | Uso |
|---|---|---|---|
| `verde-lime` | `#62BB46` | SVG + site | Anel do ícone, CTA float, badges filled, accent |
| `verde-corpo` | `#005A45` | SVG + site | Wordmark, CTAs outline, telefones footer |
| `verde-35anos` | `#20592D` | SVG | Badge 35 anos mark |
| `verde-dark` | `#112A25` | site | Headings Montserrat, bottom bar |
| `verde-hover` | `#173F35` | site | Hover states |
| `verde-icon` | `#407A6B` | site | Ícones secundários |
| `ink` | `#2C2C2C` | site | Texto de conteúdo |
| `texto-muted` | `#555454` | site | Footer, secundário |
| `off-white` | `#F8FAF9` | site | Seções alternadas |

**⚠️ Bug documentado:** `#1976D2` (azul MUI padrão) aparece 428x no site sem ser sobrescrito no tema. Não faz parte da identidade. Corrigir com `palette.primary.main: '#005A45'`.

### Regra de "diferença"
- Fundo escuro / foto: `verde-lime` (#62BB46) ou branco (#FFFFFF) — sempre Montserrat/Work Sans 900
- Fundo claro / slide: `verde-dark` (#112A25) — Montserrat 900 Italic
- Nunca: peso regular, outra cor, outra fonte

## Typography

### Dois sistemas que coexistem

| Sistema | Fonte | Pesos | Contexto |
|---|---|---|---|
| **UI / Produto** | Work Sans | 400/500/600/700 | Site, anúncios, copy de ad |
| **Editorial** | Montserrat | 400/700 (bold via `<strong>`) | Seções de conteúdo, key visual |

**"diferença" — assinatura tipográfica da campanha:**
- Peças editoriais (outdoor, slides, key visual): **Montserrat 900 Italic**
- Peças de produto (WhatsApp, feed, carrossel): **Work Sans 900** em branco sobre foto

**Escala do site (verificada por inspeção CSS):**
- Hero H1: Work Sans 700 / 51.2px
- Hero H2 (slide): Work Sans 400 / 65px / tracking -3px / UPPERCASE
- Section H2: Montserrat 400–700 / 42px
- Stats: Montserrat 700 / 44px
- Nav: Work Sans 500 / 14px / tracking 0.4px / UPPERCASE
- Body: Work Sans 400 / 16px / 24px line-height

## Layout

### Site cipasa.com
- Container: `max-width: 1250px`
- Header: `height: 100px` (fixo)
- Hero: `height: 650px` + `background: #000` com PNG overlay verde embutido

### Ads — WhatsApp Story (9:16)
Template mapeado dos criativos reais:
1. **Foto de pessoa** — real, natural, não olhando para câmera
2. **Copy setup** — Work Sans 400 branco, ~18–22px: "Investimento seguro é o que faz a"
3. **"diferença"** — Work Sans 900 branco, enorme (~72–96px): palavra isolada
4. **Badges de dados** — lime filled: "lotes a partir de 300m²" + "Pronto para construir"
5. **Logo empreendimento** — Verana logo centralizado
6. **Gradiente lime strip** — faixa diagonal verde-lime no rodapé
7. **"CIPASA 35 anos" badge** — outline, na faixa branca do rodapé

### Ads — Outdoor/Billboard (16:9)
Template mapeado do outdoor real:
- **Split dinâmico** (não 50/50 rígido — família no centro cruza os dois lados):
  - Esquerda: gradiente lime-to-white + badges de dados + texto copy
  - Direita: foto de empreendimento/natureza com gradiente verde escuro
- **Logo do empreendimento** no canto superior direito
- **"diferença"** em Work Sans 900 branco + setup em texto menor regular
- **Cipasa 35 anos badge** filled dark

### Ads — Grid de amenidades (1:1 carrossel)
- Foto real da amenidade (piscina, quadra, academia)
- Palavra-chave grande sobreposta: verde-lime / Work Sans 900
- Círculo orgânico branco/translucente em algum canto
- Badge com m² ou CTA no último card

## Elevation & Depth

- Cards site: sem sombra detectada (separação por espaço e contraste)
- Elementos flutuantes: `box-shadow: rgba(0,0,0,0.2) 0px 0px 35px 0px`
- Botão WA: `box-shadow: rgba(98,187,70,0.41) 1px 1px 3px 0px`
- Hero overlay: PNG com tratamento de cor verde embutido na pré-produção (não CSS filter)

## Shapes

- CTAs site: `border-radius: 50px` (pill) — padrão principal
- Badge 35 anos: `border-radius: 8–10px` (retângulo arredondado com borda)
- Icon badges: `border-radius: 8px`
- Cards: sem border-radius (full-bleed)
- Círculo orgânico: `border-radius: 50%`, decorativo, pode ser cortado

## Components

### CTA outline pill (padrão do site)
```
border: 1px solid #005A45
border-radius: 50px
color: #005A45
background: transparent
font: Work Sans 14px/700 UPPERCASE
padding: 0 29px
```
Hover: `background: #005A45; color: #FFFFFF`

### Badge de dados de empreendimento
```
border: 2px solid #62BB46
border-radius: 8px
Filled: background #62BB46, text dark #112A25
Outline: background transparent, text #005A45
```

### "diferença" em ads
```
Work Sans 900 / branco / enormes (72–96px no canvas)
Texto setup acima: Work Sans 400 / branco / ~18–22px
```

## Do's and Don'ts

**Do:**
- "diferença" e "bem feito" sempre 900 (negrito máximo)
- Fotos reais de pessoas em momentos naturais — nunca posadas
- Overlay verde embutido na imagem (não via CSS filter)
- CTAs em pill `border-radius: 50px` + verde-corpo outline
- Badge 35 anos em **todas** as peças de campanha 2026
- Círculo orgânico como recurso compositivo (pode sair do frame)
- Gradiente lime strip no rodapé de cards de produto

**Don't:**
- `#1976D2` azul MUI — não é da paleta, remover sobrescrevendo o tema
- "diferença" em peso regular
- Border-radius misturado sem padrão (escolher pill OU md por contexto)
- Sombra em cards — o site não usa; separação por espaço
- Foto de banco americano / render 3D
- Mote truncado sem o "faz diferença"
