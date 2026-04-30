# LOGOS — Sistema de Logos Cipasa

> Tudo sobre o sistema de logos: anatomia, variantes disponíveis, regras de uso. Os arquivos SVG editáveis estão em [`assets/logos/`](assets/logos/).

---

## Anatomia

### Ícone (símbolo)

Arquivo master: [`assets/logos/cipasa-icone.svg`](assets/logos/cipasa-icone.svg) — ViewBox `0 0 97 111`, proporção 1:1.14.

O ícone é um **anel verde-lima** abraçando uma **paisagem em camadas** estilizada — montanhas suaves no topo, vegetação intermediária e camadas de água em verde-azulado abaixo. Comunica urbanismo responsável integrado à natureza.

**Camadas do ícone (de fundo para frente, organizadas em `<g>`):**

| Camada (`<g id>`) | Path | Cor | Função |
|---|---|---|---|
| `paisagem-topo` | `paisagem-clara` | `#B0CAC1` | Banda superior — montanhas/relevo |
|  | `detalhe-branco` | `#FFFFFF` | Detalhe pontual de luz |
| `anel` | (anel completo) | `#62BB46` | O símbolo Cipasa, círculo aberto |
| `paisagem-meio` | (vegetação) | `#D8E6DC` | Camada vegetal intermediária |
| `agua` | `agua-escura` | `#407B6B` | Água profunda (base) |
|  | `agua-media` | `#82ADA1` | Água média entre vegetação e profunda |

### Wordmark

Arquivo: [`assets/logos/cipasa-wordmark.svg`](assets/logos/cipasa-wordmark.svg) — ViewBox `113 5 312 103` (preserva alinhamento com o ícone no lockup).

- **CIPASA** — letras maiúsculas em desenho proprietário (não é Work Sans direto). Cor `{colors.primary}` (`#005A45`).
- **URBANISMO** — abaixo, em tracking aberto, mesmo verde escuro.

### Badge 35 anos

Arquivo: [`assets/logos/cipasa-35anos-badge.svg`](assets/logos/cipasa-35anos-badge.svg) — ViewBox **corrigido** `0 0 168 111` (anteriormente tinha offset `431 0 168 111`, bug de exportação).

Selo comemorativo: o numeral "35" estilizado integrado com "CIPASA" e "anos". Cor única `{colors.badge-35}` (`#20592D`).

> No lockup completo (`cipasa-completo-35anos.svg`), o badge mantém suas coordenadas originais (offset 431) porque está integrado à composição horizontal completa.

---

## Variantes Disponíveis

12 arquivos SVG, todos com `<title>`, `<desc>`, grupos lógicos e IDs nomeados.

### Símbolo (ícone)

| Arquivo | Quando usar |
|---|---|
| `cipasa-icone.svg` | Padrão. Sobre fundos claros. Cores completas. |
| `cipasa-icone-branco.svg` | Sobre fundos escuros ou foto escura. Camadas em branco com opacidades graduadas. |
| `cipasa-icone-mono.svg` | Aplicações monocromáticas: carimbo, baixo-relevo, fax, grayscale obrigatório. Cor única `{colors.primary}`. |

### Wordmark

| Arquivo | Quando usar |
|---|---|
| `cipasa-wordmark.svg` | Padrão. Cor `{colors.primary}`. |
| `cipasa-wordmark-branco.svg` | Sobre fundos escuros / fotos escuras. |

### Logo (ícone + wordmark)

| Arquivo | Quando usar |
|---|---|
| `cipasa-logo.svg` | Lockup horizontal padrão. Sobre fundos claros. |
| `cipasa-logo-branco.svg` | Sobre fundos escuros. |
| `cipasa-logo-mono.svg` | Monocromático. |

### Lockup completo (com 35 anos)

| Arquivo | Quando usar |
|---|---|
| `cipasa-completo-35anos.svg` | Lockup oficial da campanha de 35 anos. Toda peça institucional, key visual, papelaria. |
| `cipasa-completo-35anos-branco.svg` | Sobre fundos escuros / fotos. |

### Badge 35 anos isolado

| Arquivo | Quando usar |
|---|---|
| `cipasa-35anos-badge.svg` | Quando o badge precisa aparecer sozinho — em rodapés de stories, watermarks, selos comemorativos. |
| `cipasa-35anos-badge-branco.svg` | Mesmo uso, sobre fundos escuros. |

---

## Regras de Uso

### Clearspace

Mantenha **1× a altura do ícone** como espaço livre em todos os lados do logo. Nada deve invadir esse espaço — nem texto, nem outros elementos visuais, nem bordas de container.

### Tamanho mínimo

| Asset | Mínimo |
|---|---|
| Ícone solo | 24px de altura |
| Wordmark solo | 80px de largura |
| Logo (ícone + wordmark) | 120px de largura |
| Lockup completo (com badge 35) | 200px de largura |

Abaixo desses tamanhos, a legibilidade comprometida prejudica a marca. Em telas pequenas, prefira ícone solo.

### Sobre fundos

| Fundo | Variante |
|---|---|
| Branco / off-white / qualquer claro | Versão color (padrão) |
| Verde escuro Cipasa | Versão branca |
| Foto clara | Versão color sobre uma área limpa (use o círculo orgânico branco como zona de respiro) |
| Foto escura | Versão branca diretamente sobre a foto |
| Foto média (sem zona limpa) | Aplicar overlay `{colors.overlay-green}` ~30% e usar versão branca |

### Aplicação em ad (Verana)

Em peças de mídia (Meta Ads, WhatsApp), o **logo Verana Parque Alvorada** entra em vez do logo Cipasa Urbanismo principal. O Cipasa aparece apenas no badge "CIPASA 35 anos" no rodapé. Esta é uma escolha estratégica: na peça promocional do empreendimento, o Verana é a marca primária; a Cipasa endossa.

Ver `BRAND.md` para detalhes de portfolio e relação Cipasa ↔ Verana.

---

## Don'ts

1. **Não recolore.** Os verdes do ícone (camadas internas) não são intercambiáveis. Mude apenas usando as variantes oficiais (color, branco, mono).
2. **Não estique.** Mantenha sempre a proporção viewBox. SVG já preserva isso, mas certifique-se de que a aplicação não força aspect ratio.
3. **Não rotacione.** O logo é horizontal. Rotacionar quebra a leitura.
4. **Não separe ícone e wordmark** quando o lockup é necessário. Se precisar do ícone solo, use `cipasa-icone.svg` — não recorte o ícone do logo composto.
5. **Não aplique shadow ou outline.** A marca é flat. Não tem efeito de elevação.
6. **Não mude o tracking ou kerning** do wordmark. Os paths são fechados.
7. **Não preencha o badge 35 anos.** O lockup do badge no contexto de aplicação (sobre foto, em rodapé) usa apenas outline. O badge SVG isolado preserva o desenho original com fundo `{colors.badge-35}`.
8. **Não use o ícone com paisagem em monocromático.** Use a variante `cipasa-icone-mono.svg` apropriada — ela tem o desenho simplificado para 1 cor.

---

## Estrutura interna dos SVGs

Cada SVG segue este padrão:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="..." viewBox="..." role="img" aria-labelledby="title desc">
  <title id="title">Nome do logo</title>
  <desc id="desc">Descrição estrutural para acessibilidade e LLMs</desc>
  <!-- Comentário com cores utilizadas -->

  <g id="camada-1">
    <path id="elemento-1" fill="..." d="..."/>
    <path id="elemento-2" fill="..." d="..."/>
  </g>
  <g id="camada-2">
    <path fill="..." d="..."/>
  </g>
</svg>
```

Isso facilita:
- Leitura por LLMs (cada path é nomeável e referenciável)
- Edição manual (cada camada pode ser selecionada inteira)
- Manipulação por CSS (classes podem ser aplicadas a grupos)
- Acessibilidade (`<title>` + `<desc>` lidos por leitores de tela)
