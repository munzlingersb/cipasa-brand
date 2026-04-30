---
version: alpha
name: Cipasa Heritage
description: 35 anos fazendo bem feito. Identidade verde, editorial, photo-first, com forma orgânica branca como assinatura visual e uma palavra-chave em lima italic como gancho emocional.
colors:
  # Verdes corporativos
  primary:        "#005A45"
  primary-deep:   "#112A25"
  primary-hover:  "#173F35"
  # Badge 35 anos
  badge-35:       "#20592D"
  # Lima accent
  accent:         "#62BB46"
  accent-soft:    "#82ADA1"
  # Camadas da paisagem do ícone
  paisagem-clara: "#B0CAC1"
  paisagem-meio:  "#D8E6DC"
  agua-escura:    "#407B6B"
  # Neutrals
  neutral:        "#F8FAF9"
  ink:            "#2C2C2C"
  muted:          "#555454"
  white:          "#FFFFFF"
  # Overlay (usado com opacidade sobre foto)
  overlay-green:  "#005A45"
typography:
  display-2xl:
    fontFamily: Work Sans
    fontSize: 96px
    fontWeight: 900
    fontStyle: italic
    lineHeight: 0.95
    letterSpacing: -0.02em
  display-xl:
    fontFamily: Work Sans
    fontSize: 64px
    fontWeight: 900
    fontStyle: italic
    lineHeight: 1.0
  display-lg:
    fontFamily: Work Sans
    fontSize: 48px
    fontWeight: 900
    fontStyle: italic
    lineHeight: 1.05
  h1:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: -0.01em
  h2:
    fontFamily: Work Sans
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.2
  h3:
    fontFamily: Work Sans
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.3
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.55
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: 600
    letterSpacing: 0.08em
  caption:
    fontFamily: Work Sans
    fontSize: 11px
    fontWeight: 400
    letterSpacing: 0.04em
rounded:
  none: 0px
  sm: 4px
  md: 14px
  lg: 28px
  full: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  2xl: 64px
  3xl: 96px
  base: 8px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    padding: 14px 24px
    typography: "{typography.label}"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
  button-ghost:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    rounded: "{rounded.md}"
    padding: 14px 24px
  badge-data:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    padding: 14px 20px
  badge-data-secondary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    padding: 14px 20px
  badge-35-anos:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    rounded: "{rounded.lg}"
    padding: 8px 20px
  badge-35-anos-on-photo:
    backgroundColor: transparent
    textColor: "{colors.white}"
    rounded: "{rounded.lg}"
  card-keyword-circle:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.full}"
  card-closing:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.full}"
    padding: 32px
  # Componentes semânticos para referenciar cores do sistema
  page:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.ink}"
  page-dark:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.white}"
  text-headline:
    textColor: "{colors.primary-deep}"
  text-muted:
    textColor: "{colors.muted}"
  badge-35-original:
    backgroundColor: "{colors.badge-35}"
    textColor: "{colors.white}"
  icon-paisagem-claro:
    backgroundColor: "{colors.paisagem-clara}"
  icon-paisagem-meio:
    backgroundColor: "{colors.paisagem-meio}"
  icon-agua:
    backgroundColor: "{colors.agua-escura}"
  icon-accent-soft:
    backgroundColor: "{colors.accent-soft}"
  photo-overlay:
    backgroundColor: "{colors.overlay-green}"
---

# Cipasa Heritage

A identidade visual da Cipasa Urbanismo. Para a alma da marca (manifesto, voice & tone, posicionamento), ver [`BRAND.md`](BRAND.md). Para o sistema de logos (variantes, regras de uso), ver [`LOGOS.md`](LOGOS.md).

## Overview

**Cipasa Heritage. 35 anos de fazer bem feito.**

A identidade visual traduz isso em três decisões fundamentais:

1. **Deep greens** que carregam tradição — não são "verdes de natureza" decorativos, são verdes que comunicam consistência e maturidade.
2. **Forma orgânica branca** como assinatura — um círculo ou arco branco que sangra de um canto da imagem, criando respiro editorial e contraste sem agressividade.
3. **Uma palavra-chave em lima italic** como gancho emocional — sempre uma só palavra, em Work Sans 900 italic, lima (`#62BB46`), que é o coração de cada peça.

A composição é sempre **photo-first**: foto real do empreendimento ocupa todo o frame, e os elementos da marca constroem a narrativa por cima dela. Não usa banners, top bars, pill badges ou shadows. A profundidade vem das camadas da foto + forma orgânica branca + tints sutis verdes.

A marca não é "corporativa premium imobiliária" — é **editorial premium imobiliária**. A diferença está no respeito ao olhar do leitor: não grita, não força urgência, não decora.

## Colors

A paleta é dominada por verdes — não como cor de marca, mas como sistema. Cada verde tem uma função clara.

- **Primary `#005A45`** — verde escuro do wordmark e dos textos âncora. É o verde que diz "Cipasa". Aparece em logos, headlines de overlay, e textos sobre fundos claros.
- **Primary Deep `#112A25`** — verde quase preto. Usado em headlines pesadas e situações de máximo contraste tipográfico.
- **Primary Hover `#173F35`** — estado de hover dos botões e CTAs. Pequena variação para feedback de interação.
- **Badge 35 `#20592D`** — verde específico do badge comemorativo dos 35 anos. **Apenas no badge** — não usar em outros contextos.
- **Accent `#62BB46`** — lima, o coração da identidade. É o verde da palavra-chave, dos badges de dados, dos elementos que precisam saltar. Usado com parcimônia: nunca em texto corrido, sempre em destaques.
- **Accent Soft `#82ADA1`** — verde-azulado das camadas internas da paisagem do ícone. Decorativo, não estrutural.
- **Paisagem Clara `#B0CAC1`**, **Paisagem Meio `#D8E6DC`**, **Água Escura `#407B6B`** — camadas da paisagem dentro do ícone. Usadas apenas no símbolo, não na UI.
- **Neutral `#F8FAF9`** — off-white de fundo. Mais quente que branco puro.
- **Ink `#2C2C2C`** — texto corpo padrão.
- **Muted `#555454`** — texto secundário, captions, metadados.
- **White `#FFFFFF`** — usado em formas orgânicas, texto sobre foto escura, círculos.
- **Overlay Green `#005A45`** — verde aplicado com opacidade (20–35%) sobre fotos para reforçar identidade visual sem matar a foto.

### Roles práticos

| Aplicação | Cor |
|---|---|
| Texto corpo | `{colors.ink}` |
| Texto secundário | `{colors.muted}` |
| Headlines | `{colors.primary-deep}` |
| Logo / wordmark | `{colors.primary}` |
| Palavra-chave em ad | `{colors.accent}` |
| Badge de dado | `{colors.accent}` (fundo) + `{colors.white}` (texto) |
| Badge 35 anos sobre foto | `{colors.white}` (borda + texto), fundo transparente |
| Tint sobre foto | `{colors.overlay-green}` com 20–35% opacity |
| Fundos editoriais | `{colors.neutral}` |

## Typography

Duas famílias. **Work Sans** é a fonte da operação — usada em UI, anúncios, badges, headlines de campanha. **Montserrat** entra apenas em editoriais raros (capa de folder, key visual de outdoor) onde queremos peso editorial diferente.

- **Display 2XL e XL (Work Sans 900 italic)** — a palavra-chave dos anúncios. "diferença", "clube", "consciente", "verana". Sempre uma só palavra. Sempre em italic.
- **Display LG (Work Sans 900 italic)** — headlines secundárias com mesma personalidade.
- **H1 (Montserrat 800)** — capas e key visuals editoriais. Reservado.
- **H2/H3 (Work Sans 700)** — títulos de seção em material institucional.
- **Body LG/MD/SM (Work Sans 400)** — texto corrido em todos os tamanhos.
- **Label (Work Sans 600, tracking 0.08em)** — labels de UI, CTAs em botões, micro-copy estrutural.
- **Caption (Work Sans 400, tracking 0.04em)** — disclaimers, asteriscos, créditos.

A hierarquia respeita o princípio editorial: **uma palavra grande, várias pequenas**. Nunca duas palavras grandes brigando por atenção.

## Layout

Sistema base 8px. Todos os spacings são múltiplos de 8.

- `xs` (4) — espaçamentos micro entre elementos relacionados
- `sm` (8) — gap padrão entre badges, ícones e textos
- `md` (16) — padding interno de componentes
- `lg` (24) — separação entre componentes
- `xl` (40) — separação entre seções
- `2xl` (64) — separação entre blocos principais
- `3xl` (96) — margens de página em material editorial

A composição dos anúncios é **photo-first**:
1. Foto real ocupa 100% do frame.
2. Forma orgânica branca sangra de um canto (~480–620px de raio em um canvas 1080).
3. Logo discreto dentro da forma orgânica.
4. Palavra-chave em lima italic posicionada onde ela respira.
5. Badges de dados (quando houver) em coluna ou linha, sempre lima preenchido.

Nunca centralizado. Nunca simétrico. A composição é sempre direcionada — esquerda/direita, topo/base.

## Elevation & Depth

A marca é **flat**. Não usa box-shadow, drop-shadow, gradient overlays decorativos.

A profundidade visual vem de três técnicas:

1. **Forma orgânica branca** — cria uma camada clara contrastante sobre a foto.
2. **Tints verdes sobre foto** — overlay `{colors.overlay-green}` com opacidade entre 20% e 35% unifica fotos de origens diferentes em um sistema visual coerente.
3. **Faixa wave lima** — uma tira diagonal `{colors.accent}` no canto inferior, com inclinação de aproximadamente -12°, marca o rodapé de stories e WhatsApp sem precisar de barra ou banner.

Hover e focus em UI usam apenas mudança de cor (`{colors.primary-hover}`). Sem elevação.

## Shapes

A marca tem três shapes-chave que aparecem repetidamente:

- **Círculo orgânico (forma signature)** — um círculo de raio grande (480–620px num canvas 1080) que sangra de um canto. Não é um círculo perfeito centralizado: é uma fração de círculo que entra na composição como uma "lua branca". Cria respiro e zona limpa para o logo.
- **Badge arredondado de dados (`{rounded.md}` = 14px)** — retângulos com cantos arredondados, fundo lima, conteúdo `[ícone branco] + [número grande] + [label pequena]`.
- **Badge pill 35 anos (`{rounded.lg}` = 28px)** — pílula outline com borda fina branca ou verde escuro, contendo o lockup "CIPASA 35 anos".
- **Faixa wave** — tira diagonal lima inclinada -12° no rodapé esquerdo de stories e WhatsApp.

Botões usam `{rounded.md}`. Cards e contêineres editoriais usam `{rounded.sm}` (4px) — nunca arredondamento exagerado.

## Components

### `button-primary`
Botão principal. Usado em CTAs primários: "Agende uma visita", "Falar com especialista".
- Fundo: `{colors.primary}`
- Texto: `{colors.white}`, tipografia `{typography.label}` em uppercase
- Padding: `14px 24px`
- Border-radius: `{rounded.md}`
- Hover: fundo muda para `{colors.primary-hover}`

### `button-ghost`
Variante secundária com borda. Usado em CTAs alternativos.
- Fundo: transparente
- Texto e borda: `{colors.primary}`
- Mesmo padding e raio do `button-primary`

### `badge-data`
Badge de dado em ad. Estrutura: `[ícone] + [coluna: label / número]`.
- Fundo: `{colors.accent}`
- Texto: `{colors.white}`
- Border-radius: `{rounded.md}` (14px)
- Padding: `14px 20px`

Exemplo: ícone seta → "lotes a partir de" (label pequena, branco) → "300m²" (número grande, branco, Work Sans 900).

> **Nota de acessibilidade:** o contraste branco em `{colors.accent}` é 2.41:1, abaixo do WCAG AA. Esta é uma decisão de design intencional justificada por: (1) uso exclusivo em **peças publicitárias** (não interface funcional), (2) tipografia em peso máximo (Work Sans 900) e tamanho grande (≥40px), e (3) coerência com a identidade visual estabelecida da marca. Para UI funcional (botões, formulários, navegação) onde acessibilidade é crítica, use `{colors.primary}` como fundo de elementos interativos — esse atinge contraste 9.86:1 com texto branco.

### `badge-data-secondary`
Variante usada para complementar um `badge-data` (ex: "Pronto para construir" ao lado de "300m²").
- Fundo: `{colors.primary}` (verde escuro, não lima)
- Texto: `{colors.white}`
- Mesmas dimensões do `badge-data`

### `badge-35-anos`
Pílula outline com lockup "CIPASA 35 anos". Sempre no rodapé de cards e stories.
- Fundo: transparente
- Borda: `{colors.primary}` 2px
- Texto: `{colors.primary}`
- Border-radius: `{rounded.lg}` (28px)
- Padding: `8px 20px`

### `badge-35-anos-on-photo`
Variante quando o badge fica diretamente sobre foto escura (sem círculo orgânico).
- Borda e texto: `{colors.white}`
- Fundo: transparente

### `card-keyword-circle`
A forma orgânica branca que abre espaço para logo e copy.
- Fundo: branco
- Border-radius: `{rounded.full}` (forma circular)
- Posicionado fora do canvas em 1 corner; sangra ~25–35% para dentro.

### `card-closing`
Versão maior do `card-keyword-circle`, contém todo o CTA do card de fechamento (logo, dados, "Agende uma visita").

## Do's and Don'ts

**Do**

1. Use foto real do empreendimento sempre que possível.
2. Deixe a palavra-chave dominar visualmente (ela é o herói da peça).
3. Forma orgânica branca sangra de um canto, sempre.
4. Aplique tint verde (overlay `{colors.overlay-green}` 20–35%) quando a foto tem origens visuais inconsistentes.
5. Mantenha a tipografia em Work Sans para 99% das peças. Montserrat só em editoriais.
6. Lima `{colors.accent}` é destaque. Use com parcimônia.

**Don't**

1. Não use top bands, banners de topo, ou faixas horizontais escuras no topo.
2. Não use pill badges no topo da imagem.
3. Não centralize composições — sempre direcione para um lado.
4. Não use box-shadow ou gradient overlays decorativos.
5. Não use mais de uma palavra-chave em italic na mesma peça.
6. Não recolore o ícone fora das cores aprovadas.
7. Não use o badge 35 anos com fundo preenchido — só outline.
8. Não force urgência em CTAs ("aja agora", "garanta já"). A marca é convite, não pressão.

## Layout Templates

A marca tem 4 sistemas de layout para criativos digitais (descritos em [`CREATIVES.md`](CREATIVES.md)) e um conjunto de templates físicos (descritos em [`PHYSICAL.md`](PHYSICAL.md)).

### Os 4 layouts digitais

| Tipo | Quando | Componentes principais |
|---|---|---|
| **A — Circle + Keyword** | Lifestyle (clube, relaxante, friozinho, amigos) | foto + círculo orgânico + keyword única em lima italic |
| **B — "diferença" Impact** | Aspiracional/value driven | foto + tint + headline 3-linhas + keyword hero (lima OU branca) + badges + 35 anos |
| **C — Data Badges Story** | Racional, formato vertical | story 9:16 + 3 badges lima empilhados + CTA + wave strip |
| **D — Closing CTA** | Conversão, fim de carrossel | círculo grande inf-esq + tudo dentro: dados + logos + CTA |

### Templates SVG editáveis

Pasta `assets/templates/`:

- `template-feed-1x1.svg` — 1080×1080 (layouts A, B, D)
- `template-story-9x16.svg` — 1080×1920 (layouts B vertical, C)
- `template-outdoor-8x3.svg` — 4800×1800 (B expandido para mídia OOH)
- `template-folder-a4.svg` — A4 dobrado em 3 (folder editorial)
- `template-cartao-visita.svg` — 90×50mm (papelaria)
- `template-papel-timbrado.svg` — A4 (correspondência institucional)

Cada template tem guides verde-lima dashed (safe zones), verde-lima solid (posições do círculo orgânico), vermelho dashed (danger zones), e boxes preenchidos marcando onde cada elemento (logo, keyword, headline, badges, CTA) deve viver.

## Channel-specific Rules

Ajustes da identidade por canal de aplicação.

### Mídia paga digital (Meta Ads, Google Ads)

- Texto crítico fora dos primeiros 200px do topo (UI Instagram cobre)
- Texto crítico fora dos últimos 280px da base em stories (botão "Enviar mensagem")
- Tipografia mínima: 22px (corpo), 14px (label), 60px (keyword italic)
- Tint verde overlay: **20%** (foto coerente) / **30%** (multi-source) / **35%** (foto escura)
- Logo Verana sempre dentro do círculo orgânico, exceto em `closing card` onde tudo vai dentro do círculo

### Web

- Tipografia escala automaticamente: `display-2xl` → 96px desktop, 56px tablet, 40px mobile
- Botões: padding sempre `14px 24px` desktop, `12px 18px` mobile
- Forma orgânica branca: ajustar raio para 35% da largura da viewport
- Hover states usam `{colors.primary-hover}` exclusivamente (não shadow)

### Email transacional

- Largura útil: 600px máximo
- Sem foto de fundo full-bleed (compatibilidade Outlook) — usar bloco com cor sólida + foto separada
- Tipografia fallback: `Arial`, `Helvetica`, `sans-serif` (Work Sans não carrega em alguns clientes)
- Botão CTA: tabela HTML com `bgcolor` direto

### Outdoor / Mídia OOH

- Cor: perfil **CMYK**, não RGB. Verde primary `#005A45` ≈ `C100 M0 Y50 K65`
- Resolução: 300dpi para impressão grande
- Margens de segurança: 120px de cada borda (estrutura, fixação)
- Tipografia mínima legível a 100m: stroke ~40cm equivalente (display-2xl = 280–400px no render 4800×1800)

### Material impresso (folder, papelaria, merch)

- Cor: perfil **CMYK** com prova de cor obrigatória antes de tiragem
- Sangra: 3mm em todos os bordas
- Couché fosco 250g (capa) / 170g (miolo) / offset 90g (papel timbrado)
- Lima `#62BB46` em CMYK pode tender ao amarelo se separação errada — **sempre fazer prova**

### Tinção da foto: matriz de decisão

| Cenário | Overlay | Quando |
|---|---|---|
| Foto bem iluminada, coerente | nenhum (0%) | Foto é hero absoluto |
| Foto bem iluminada com áreas muito claras | `{colors.overlay-green}` 20% | Suaviza highlights, ganha legibilidade |
| Conjunto de fotos de múltiplas fontes | `{colors.overlay-green}` 30% | Unifica, aumenta coerência |
| Foto escura, baixo contraste | `{colors.overlay-green}` 35% | Reforça identidade visual |
| Story 9:16 padrão | `{colors.overlay-green}` 30% | Composição vertical com mais texto sobre foto |

### Badge 35 anos: matriz de fundo

| Sobre... | Variante | Justificativa |
|---|---|---|
| Fundo claro / off-white | outline `{colors.primary}` (verde escuro) | Contraste natural, identidade institucional |
| Fundo verde escuro Cipasa | outline `{colors.white}` | Inversão clara |
| Foto clara (sem círculo orgânico) | outline `{colors.white}` com fundo escuro 30% | Garante legibilidade |
| Dentro do círculo orgânico branco | outline `{colors.primary}` | Mesmo da regra para fundo claro |
| Foto média/escura | outline `{colors.white}` | Sem fundo extra (testar legibilidade) |
