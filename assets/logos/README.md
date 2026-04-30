# Logos — Arquivos editáveis

12 SVGs limpos, agrupados por camadas, com `<title>`, `<desc>` e IDs nomeados. Para regras de uso, ver [`../../LOGOS.md`](../../LOGOS.md).

## Tabela de uso rápido

| Arquivo | Cor | Sobre | Aplicação |
|---|---|---|---|
| `cipasa-icone.svg` | full color | claro | favicon, ícone solo, marca d'água |
| `cipasa-icone-branco.svg` | branco | escuro | mesmas situações, sobre fundo escuro |
| `cipasa-icone-mono.svg` | `#005A45` | claro | monocromia (carimbo, fax, baixo-relevo) |
| `cipasa-wordmark.svg` | `#005A45` | claro | quando só o nome importa, sem o símbolo |
| `cipasa-wordmark-branco.svg` | branco | escuro | mesmo uso |
| `cipasa-logo.svg` | full color | claro | **lockup padrão** — papelaria, site, assinatura |
| `cipasa-logo-branco.svg` | branco | escuro | mesmo uso |
| `cipasa-logo-mono.svg` | `#005A45` | claro | monocromia |
| `cipasa-completo-35anos.svg` | full color | claro | **lockup oficial 35 anos** — toda peça institucional |
| `cipasa-completo-35anos-branco.svg` | branco | escuro | mesmo uso |
| `cipasa-35anos-badge.svg` | `#20592D` | claro | badge isolado (rodapé, watermark, selo) |
| `cipasa-35anos-badge-branco.svg` | branco | escuro | mesmo uso |

## ViewBoxes

| Arquivo | viewBox | Proporção |
|---|---|---|
| ícone | `0 0 97 111` | ~1:1.14 |
| wordmark | `113 5 312 103` | preserva offset para alinhar com ícone no lockup |
| badge 35 anos | `0 0 168 111` | corrigido (era `431 0 168 111` no original) |
| logo (ícone + wordmark) | `0 0 424 111` | horizontal |
| lockup completo | `0 0 598 111` | horizontal estendido com badge |

## PNGs

A pasta [`png/`](png/) tem exports rasterizados @1x e @2x para contextos onde SVG não é viável (e-mail, alguns CRMs, miniaturas). Regerar via Inkscape se necessário.

## Editando

Os SVGs estão em XML legível, com grupos `<g>` e IDs nomeados. Você pode:
- Abrir no Inkscape, Figma ou qualquer editor SVG — cada camada é um grupo selecionável
- Editar à mão em um editor de texto — paths estão organizados por camada
- Aplicar CSS por classe ou ID — cada elemento é endereçável
- Manipular via `xml.etree.ElementTree` em Python — estrutura previsível

## Histórico

Estes arquivos foram **reformulados** a partir dos SVGs originais em 2026. As mudanças:

- ✓ Adicionado `<title>` e `<desc>` em todos
- ✓ Paths agrupados em `<g id>` por camada lógica
- ✓ IDs nomeados em paths-chave
- ✓ Header com comentário descrevendo cores
- ✓ Corrigido viewBox do badge (offset 431px era bug de exportação)
- ✓ Geradas variantes mono e brancas faltantes
- ✓ Removidas duplicidades antigas (`cipasa-35anos-original.svg`, `cipasa-logo-completo.svg`, etc.)
