# Cipasa Heritage — Brandbook

Identidade visual da **Cipasa Urbanismo** (35 anos). Brandbook em formato [DESIGN.md](https://github.com/google-labs-code/design.md) — markdown + YAML — otimizado para consulta por LLMs e agentes de IA.

> **Aqui, fazer bem feito faz diferença.**

---

## TL;DR

Para um anúncio Cipasa-fiel:
- **Foto real** do empreendimento ocupa 100% do frame.
- **Forma orgânica branca** sangra de um canto (canto superior-direito é o padrão).
- **Uma palavra-chave** em Work Sans 900 italic, lima `#62BB46` — domina visualmente.
- **Logo discreto** dentro da forma orgânica.
- **Sem** top bands, pill badges, shadows, ou composição centralizada.

Para regras de aplicação, paleta exata, tipografia e componentes: leia [`DESIGN.md`](DESIGN.md).
Para alma da marca, voice & tone, posicionamento: leia [`BRAND.md`](BRAND.md).
Para sistema de logos: leia [`LOGOS.md`](LOGOS.md).

---

## Mapa de arquivos

```
cipasa-brand/
├── README.md                 ← Você está aqui
├── DESIGN.md                 ← Identidade visual (Stitch format) — fonte de verdade dos tokens
├── BRAND.md                  ← Alma da marca — manifesto, pilares, voice & tone
├── LOGOS.md                  ← Sistema de logos — variantes, regras, anatomia
├── tokens.json               ← Tokens machine-readable (gerado de DESIGN.md)
├── index.html                ← Catálogo visual — light theme (homepage)
├── preview-dark.html         ← Catálogo visual — dark theme
└── assets/
    ├── logos/                ← 12 SVGs editáveis com <title>, <desc>, grupos nomeados
    ├── icons/                ← 6 pictogramas do sistema (lazer, segurança, natureza, etc.)
    ├── patterns/             ← 3 shapes da identidade (círculo orgânico, faixa wave, numeral 35)
    ├── brand/                ← Imagens reais de aplicação (folder, outdoor, ad)
    └── ads/                  ← Criativos de campanha publicados
```

---

## Como usar com LLMs

Para qualquer tarefa de geração de peça (anúncio, post, key visual, peça impressa) com agente de IA:

1. Anexe `DESIGN.md` (tokens + componentes) e `BRAND.md` (voice + posicionamento) no contexto.
2. Para sistema de logos, anexe `LOGOS.md` + os SVGs relevantes de `assets/logos/`.
3. Para tooling de design (Tailwind, Figma Variables, Penpot), use `tokens.json` direto.

Um agente lendo apenas esses 3 markdowns deve produzir uma peça Cipasa-fiel sem mais briefing.

---

## Stack

- **Formato:** [DESIGN.md alpha spec](https://github.com/google-labs-code/design.md) (Google Labs / Stitch)
- **Lint:** `npx @google/design.md lint DESIGN.md`
- **Coleção de exemplos:** [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md)

---

## Manutenção

Este brandbook é editável e versionável. Para mudanças:

1. Edite `DESIGN.md` (tokens) ou `BRAND.md` (estratégia) — fonte de verdade.
2. Regenere `tokens.json` a partir do YAML frontmatter.
3. Se mudou logo, regere o SVG correspondente em `assets/logos/`.
4. Atualize `preview.html` se mudou a estrutura visual.
5. Rode lint do DESIGN.md.

---

*Design system mantido por [Agência Iluminar7S](https://iluminar7s.com.br) · Todos os direitos reservados Cipasa Urbanismo.*
