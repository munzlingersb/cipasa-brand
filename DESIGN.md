---
version: alpha
name: Cipasa Urbanismo — 35 Anos
description: >
  Marca corporativa da Cipasa Urbanismo na campanha de 35 anos (2026).
  Conceito central: "Aqui, fazer bem feito faz diferença!" — estrutural,
  atravessa comunicação externa, discurso comercial, cultura interna e
  próximos lançamentos. 21 estados, 35 anos de história.

colors:
  verde-floresta:  "#004D36"
  verde-corpo:     "#005A45"
  verde-lime:      "#62BB46"
  verde-brilho:    "#3DAF1E"
  verde-claro:     "#A8D98A"
  verde-pale:      "#E8F5E0"
  olive:           "#B5C98A"
  branco:          "#FFFFFF"
  off-white:       "#F5F6F2"
  ink:             "#1A2A1A"

typography:
  display:
    fontFamily: Montserrat
    fontSize: "clamp(2.5rem,6vw,5rem)"
    fontWeight: "900"
    lineHeight: "1.04"
    letterSpacing: "-0.025em"
  diferenca:
    fontFamily: Montserrat
    fontSize: "clamp(2.5rem,6vw,4.5rem)"
    fontWeight: "900"
    fontStyle: italic
    lineHeight: "1"
    letterSpacing: "-0.015em"
  headline:
    fontFamily: Montserrat
    fontSize: "clamp(1.5rem,3vw,2.5rem)"
    fontWeight: "700"
    lineHeight: "1.2"
  slogan:
    fontFamily: Montserrat
    fontSize: "1.375rem"
    fontWeight: "700"
    fontStyle: italic
    lineHeight: "1.4"
  body-lg:
    fontFamily: Inter
    fontSize: "1.125rem"
    fontWeight: "400"
    lineHeight: "1.65"
  label:
    fontFamily: Montserrat
    fontSize: "0.75rem"
    fontWeight: "700"
    lineHeight: "1"
    letterSpacing: "0.1em"

rounded:
  sm:   "6px"
  md:   "10px"
  lg:   "16px"
  xl:   "18px"
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
  24: "96px"

components:
  selo-35anos:
    borderColor: "{colors.verde-corpo}"
    borderWidth: "2px"
    rounded: md
    padding: "8px 18px"
    textColor: "{colors.verde-corpo}"

  selo-35anos-filled:
    backgroundColor: "{colors.verde-corpo}"
    borderColor: "{colors.verde-corpo}"
    borderWidth: "2px"
    rounded: md
    padding: "8px 18px"
    textColor: "{colors.branco}"

  icon-badge-filled:
    backgroundColor: "{colors.verde-lime}"
    textColor: "{colors.verde-floresta}"
    rounded: md
    borderColor: "{colors.verde-lime}"
    borderWidth: "2px"

  icon-badge-outline:
    backgroundColor: "transparent"
    textColor: "{colors.verde-corpo}"
    rounded: md
    borderColor: "{colors.verde-lime}"
    borderWidth: "2px"

  dark-card:
    backgroundColor: "{colors.verde-floresta}"
    textColor: "{colors.branco}"
    rounded: xl
    padding: "36px"

  ribbon-olive:
    backgroundColor: "{colors.olive}"
    height: "40px"
---

## Overview

Cipasa Urbanismo completa 35 anos em 2026. O conceito **"Aqui, fazer bem feito faz diferença!"** é estrutural — sustenta comunicação externa, discurso comercial, cultura interna e próximos ciclos.

**Posicionamento:** Autoridade verde + modernidade limpa. Aspiracional familiar. 35 anos de consistência como prova de entrega.

## Colors

Paleta 100% verde — do floresta profundo ao lime vibrante.

| Token | Hex | Uso |
|---|---|---|
| `verde-floresta` | `#004D36` | Backgrounds escuros, dark cards, hero |
| `verde-corpo` | `#005A45` | Textos, logo, bordas de selos |
| `verde-lime` | `#62BB46` | Logo Cipasa, "diferença" sobre dark, badges filled |
| `verde-brilho` | `#3DAF1E` | "diferença" em peças muito escuras (polo grafite) |
| `verde-claro` | `#A8D98A` | Gradientes, slide backgrounds |
| `verde-pale` | `#E8F5E0` | Seções claras, cards internos |
| `olive` | `#B5C98A` | Ribbons decorativos horizontais |

**Regra crítica:** "diferença" é SEMPRE em verde-lime (sobre dark) ou verde-floresta (sobre claro/foto). Montserrat 900 Italic. Nunca em outra cor, nunca regular.

## Typography

Montserrat 900 Italic é a assinatura tipográfica da campanha — inviolável para "diferença" e "bem feito". Inter para corpo e dados.

**Desdobramentos do mote:**
- "Isso faz diferença."
- "e isso faz diferença"
- "Nós fazemos diferente"
- "35 anos fazendo a diferença, nos projetos, nas cidades e na vida das pessoas."
- "Contratar certo faz diferença." / "Cultura forte faz diferença." / etc.

## Layout

**Outdoor 16:9:** Split — esquerda (fundo claro + círculo + ribbon olive + logo) / direita (foto aérea tintada verde + família + copy + selo 35 anos).

**Feed 1:1:** Dois padrões — (A) família + círculo + mote sobre fundo claro; (B) foto aérea tintada + "diferença" em destaque + selo.

**Story 9:16:** Foto aérea tintada (~65%) + badges de dados + rodapé com logo empreendimento + Cipasa 35 anos.

**Slides internos 16:9:** Gradiente verde-claro → off-white. Verde-corpo para texto. Verde-lime para destaques.

## Elevation & Depth

Cards sobre fundo branco: `box-shadow: 0 2px 12px rgba(0,77,54,.08)`. Overlay foto aérea: `rgba(62,180,60,.4)`. Nunca sombra colorida fora do verde.

## Shapes

- Selos/badges: `border-radius: 10px`, borda 2px — nunca circular
- Círculo compositivo: `border-radius: 50%`, transparente, pode ser cortado pelo frame
- Ribbons: sem border-radius, apenas horizontais

## Components

### Selo CIPASA 35 anos
Retângulo arredondado 10px, borda 2px verde-corpo. "CIPASA" + "35" (maior) + "anos". Versão filled: bg verde-corpo, "35" em verde-lime.

### Badge de iconografia
Retângulo arredondado 10px, borda verde-lime 2px. Superior: ícone + label. Inferior: dado em Montserrat 900. Filled: bg verde-lime. Outline: transparente.

### Dark card (mote)
Bg verde-floresta, padding 36px, border-radius 18px. Mote Montserrat 900 Italic branco, "diferença" em verde-lime.

## Do's and Don'ts

**Do:**
- "diferença" e "bem feito" SEMPRE em Montserrat 900 Italic
- Fotos reais de família em momentos mundanos
- Fotos aéreas reais com overlay verde
- Mote ou variações com "faz diferença" ao final
- Selo "CIPASA 35 anos" em todas as peças 2026
- Círculo orgânico como elemento compositivo
- Ribbon olive como acento horizontal em impressos

**Don't:**
- "diferença" em peso regular ou outra fonte
- Numeral 3D metálico de capa em peças de Ad
- Cores fora da paleta verde (vermelho, azul, laranja)
- Copy genérico sem ancorar em "faz diferença"
- Ribbon olive vertical
- Render 3D de empreendimentos
- Mote truncado — usar sempre a construção
