# CREATIVES — Direção para Criativos Digitais

> Como construir um anúncio Cipasa do zero. 4 layout systems, templates por formato, regras de composição. Para tokens visuais, ver [`DESIGN.md`](DESIGN.md). Para fotografia, [`PHOTO.md`](PHOTO.md).

---

## Os 4 Layout Systems

Toda peça digital Cipasa cabe em um destes quatro arquétipos. Eles foram extraídos do manual de 35 anos (págs. 16–25) e codificam visualmente os 3 ângulos de comunicação (aspiracional, racional, objeção).

### A — Circle + Keyword Card

**Quando usar:** carrossel lifestyle (cards do meio: clube/relaxante/friozinho/amigos/sol).

**Diagrama:**

```
┌────────────────────────────────────────┐
│ [LOGO VERANA]      ┌────────────────┐ │
│                    │  círculo       │ │
│                    │  orgânico      │ │
│  foto              │  branco       ─│ │ ← raio ~480px,
│  full-bleed        │  do canto      │ │   sangra 25-35%
│                    │  superior-     │ │
│                    │  direito       │ │
│                    └────────────────┘ │
│                                        │
│  Uma manhã no                          │
│  clube ← Work Sans 900 italic, lima   │
│  ░░░░ wave lima                        │
└────────────────────────────────────────┘
        1080×1080
```

**Especificações:**
- Foto: full-bleed, sem overlay, golden hour ideal
- Círculo orgânico: branco opaco, raio 480–520px, centro em (1080, 0)
- Logo Verana: dentro do círculo, canto superior-direito, ~65px altura, x=750 y=80
- Companion text ("Uma manhã no"): Work Sans 400 branco, 26px, x=60 y=850
- Keyword ("clube"): Work Sans 900 italic, lima `#62BB46`, 90px, x=60 y=890
- Wave strip: opcional, lima diagonal -12° no canto inferior-esquerdo
- **Sem** badge 35 anos neste layout (apenas em closing)

**Variações de canto** (alternar pelo carrossel para variar o ritmo visual):
- Círculo top-right + texto bottom-left (padrão)
- Círculo top-left + texto bottom-right
- Círculo bottom-right + texto top-left
- Círculo left-center + texto right
- Círculo right-center + texto left

### B — "diferença" Impact Card

**Quando usar:** carrossel/feed aspiracional value-driven; o card que comunica o valor central da marca.

**Diagrama:**

```
┌────────────────────────────────────────┐
│ [LOGO VERANA]                          │
│                                        │
│  foto                                  │
│  com tint verde                        │
│  20% opacity                           │
│                                        │
│  Investimento seguro                   │
│  é o que faz a                         │
│  ░░░░░░░░░░░░░░░░░░░░░░░░░░           │
│  diferença ← Work Sans 900 italic     │
│  ░░░░░░░░░░  branco, ~96px            │
│                                        │
│  [300m²][Pronto]  ← badges lima       │
│                                        │
│  ─── CIPASA 35 anos badge ───         │
└────────────────────────────────────────┘
        1080×1080
```

**Especificações:**
- Foto: full-bleed + tint `overlay-green` 20% (foto bem iluminada e coerente)
- "diferença": Work Sans 900 italic **branco** (não lima quando palavra é dominante), 96px, full-width, y≈420
- Suporte: Work Sans 400 branco, 22px, 3 linhas pequenas acima da palavra hero
- Badges lado a lado: lime green `#62BB46` rounded 14px, padding 14×20
- Logo Verana: centralizado abaixo de badges, y≈700
- Badge 35 anos outline branco no rodapé, y≈980

### C — Data Badges Story

**Quando usar:** stories WhatsApp, anúncios racionais com dados (m², construção, parcelamento), formatos verticais.

**Diagrama (1080×1920):**

```
┌─────────────────────┐
│ [LOGO]   ┌────────┐ │
│          │ círculo│ │
│          │ branco │ │
│ foto +   └────────┘ │
│ tint                │
│ 30%                 │
│                     │
│ A natureza e        │
│ a cidade            │
│ lado a lado         │
│                     │
│ ┌─────────────────┐ │
│ │[ico] 300m²       │ │
│ │     lotes a partir│ │
│ └─────────────────┘ │
│ ┌─────────────────┐ │
│ │[ico] construir   │ │
│ │     pronto para  │ │
│ └─────────────────┘ │
│ ┌─────────────────┐ │
│ │[ico] 240x        │ │
│ │     parcele em até│ │
│ └─────────────────┘ │
│                     │
│ Agende sua visita.  │
│                     │
│ ░░░ wave lima ░░░  │
│ ─── CIPASA 35 ───  │
└─────────────────────┘
       1080×1920
```

**Especificações:**
- Foto aérea preferencial, tint verde 30% para legibilidade
- Headline em 3 linhas: light → medium → bold (peso crescente)
- 3 badges empilhados lima 14px rounded, gap 16px
  - Cada badge: ícone branco 28px + coluna [label 14px / número Work Sans 900 44–52px]
- CTA "Agende sua visita." em lima `#62BB46` médio (destaque dentro do branco)
- Wave strip lima -12° no canto inferior-esquerdo
- Logos rodapé: Verana + badge 35 anos lado a lado

### D — Closing Card (CTA)

**Quando usar:** último card de carrossel, peça de conversão, post de fechamento de campanha.

**Diagrama:**

```
┌────────────────────────────────────────┐
│                                        │
│  foto full-bleed                       │
│  da área de lazer                      │
│  ou aérea                              │
│                                        │
│                                        │
│ ┌─────────────────────┐                │
│ │  círculo orgânico   │                │
│ │  branco GRANDE      │                │
│ │  raio 600-620px     │                │
│ │                     │                │
│ │  CIPASA 35 anos     │                │
│ │  Conheça o Verana   │                │
│ │  mais próximo de    │                │
│ │  você.              │                │
│ │  [300m²][Pronto]    │                │
│ │  Agende uma visita. │                │
│ │  [VERANA][CIPASA]   │                │
│ └─────────────────────┘                │
└────────────────────────────────────────┘
        1080×1080
```

**Especificações:**
- Círculo grande: raio 600–620px, sangra do canto inferior-esquerdo
- TUDO de marca dentro do círculo (área branca):
  - Badge 35 anos outline verde escuro (não branco)
  - Headline "Conheça o Verana mais próximo de você." em verde escuro, medium
  - Badges de dado lima
  - Texto "Agende uma visita." em verde escuro, medium
  - Logos compactos lado a lado (Verana + Cipasa Urbanismo)
- Foto fora do círculo: limpa, sem tint, sem texto

---

## Formatos por canal

### Feed 1:1 (Instagram, Facebook feed)
- 1080×1080px PNG/JPG
- Layouts: A, B, D
- Margem segura: 60px de cada borda

### Story 9:16 (Instagram/Facebook stories, WhatsApp status)
- 1080×1920px
- Layouts: B (vertical), C
- Margem segura: 60px laterais, 200px topo (UI Instagram), 280px base (UI Instagram)

### Reels capa 9:16
- 1080×1920px
- Layout B preferencial
- **Atenção:** evitar texto crítico na faixa 350px da base (cobertura do título)

### Carousel feed 1:1
- Até 10 cards, 1080×1080 cada
- Mistura de A (lifestyle) + B (impact) + D (closing)
- Sequência típica: 1 abertura impactante → 2-4 cards lifestyle → 1 fechamento CTA

### Outdoor 8:3 (placa de rua / mídia OOH)
- Proporção 8:3 (típico billboard horizontal)
- Render: 4800×1800 (proporção mantida) ou 8000×3000 (alta res)
- Layout: B com keyword ainda maior (Work Sans 900 italic 250–400px)
- Considerar legibilidade a 50–100m

---

## Photo treatment rules

A foto base sempre passa por uma decisão de overlay. Três níveis:

| Cenário | Tint verde overlay | Justificativa |
|---|---|---|
| Foto bem iluminada, sem disputa visual com texto | **Sem tint** ou 10% | Foto é o protagonista |
| Foto coerente mas com áreas claras demais para texto | **20%** `#005A45` | Suaviza highlights |
| Conjunto de fotos de múltiplas fontes (ex: stock + drone próprio) | **30%** `#005A45` | Unifica o conjunto |
| Foto escura demais, baixo contraste | **35%** `#005A45` | Reforça identidade |

**Dark gradient localizado** (não global):
- Sobre área onde fica o texto, gradiente vertical/horizontal preto 0% → 60%
- Nunca aplicar sobre o frame inteiro — só na zona de copy

---

## Copy patterns por ângulo

### Aspiracional — uma palavra italica
Tipologia: keyword única em lima, dominante.
- Exemplos: "verana", "clube", "relaxante", "friozinho", "amigos", "sol", "consciente"
- Acompanhada de 1–2 linhas de suporte em peso leve, branco

### Racional — texto curto + dado em badge
Tipologia: headline em 3 linhas com peso crescente, badge lima com número.
- Exemplo headline: "A natureza e / a cidade / lado a lado"
- Exemplo dado: "300m² / lotes a partir de"

### Objeção — resposta dominante
Tipologia: pergunta pequena, **resposta** enorme em lima italic.
- "Posso construir quando quiser?" → **"sim,"** + "pode construir"
- "Preciso comprovar renda?" → **"não."** + "Direto com a Cipasa."
- "É seguro?" → **"sempre."**

A resposta sempre toma o lugar do hero visual. A pergunta é fina.

---

## Hierarquia universal

Em qualquer peça Cipasa, a leitura segue esta ordem (do mais visual ao mais informativo):

1. **Foto** — chama atenção, gera contexto emocional
2. **Forma orgânica branca** — cria âncora visual e respiro
3. **Keyword** (lima italic) ou **headline impacto** — comunica em 3 segundos
4. **Texto suporte** — completa o sentido
5. **Dados** (badges) — provam, racionalizam
6. **Logo + CTA** — assina, convida

Nunca inverter essa ordem. Se a peça não tem foto, não é Cipasa — é outra marca.

---

## Templates disponíveis

Pasta [`assets/templates/`](assets/templates/) tem 6 grids SVG com guides, safe zones e marcação dos elementos:

| Template | Formato | Layout type |
|---|---|---|
| `template-feed-1x1.svg` | 1080×1080 | A, B, D |
| `template-story-9x16.svg` | 1080×1920 | B, C |
| `template-outdoor-8x3.svg` | 4800×1800 | B expandido |
| `template-folder-a4.svg` | A4 dobrado em 3 | (físico — ver `PHYSICAL.md`) |
| `template-cartao-visita.svg` | 90×50mm | (físico — ver `PHYSICAL.md`) |
| `template-papel-timbrado.svg` | A4 | (físico — ver `PHYSICAL.md`) |

Abra os templates em Figma, Inkscape ou direct paste no código. Cada um tem:
- Marcação do "círculo orgânico" nas posições possíveis
- Áreas de texto delimitadas (keyword, suporte, dados)
- Margens de segurança
- Posição do logo

---

## Workflow de criação

1. **Briefing** — qual ângulo? aspiracional, racional ou objeção?
2. **Layout pick** — A, B, C ou D?
3. **Format pick** — feed, story, outdoor?
4. **Foto** — escolher do banco em `assets/photography/` ou shoot novo (briefing em `PHOTO.md`)
5. **Tint decision** — sem / 20% / 30% / 35%?
6. **Copy** — keyword, headline ou pergunta-resposta?
7. **Render** — abrir template, posicionar elementos seguindo regras
8. **QA** — checa: hierarquia respeitada? respiro adequado? logo discreto? sem top band?
9. **Export** — PNG 1080×1080 (feed) ou 1080×1920 (story), 90% qualidade JPG para web

---

## Não fazer

- ✗ Misturar 2+ keywords italicas na mesma peça
- ✗ Centralizar a composição
- ✗ Adicionar top band ou pill badge no topo
- ✗ Usar shadow/elevation
- ✗ Texto sobre rosto de pessoa
- ✗ CTA de urgência ("garanta já", "última chance")
- ✗ Mais de 3 badges de dado por peça
- ✗ Headlines com mais de 8 palavras
