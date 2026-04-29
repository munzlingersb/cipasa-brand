# Cipasa Urbanismo — Verana Parque Alvorada · Brand Design System

Brandbook público da **Cipasa Urbanismo** e do empreendimento **Verana Parque Alvorada** (Marília-SP) para consulta visual e por agentes/LLMs.

## Links

- **Brandbook visual:** [`index.html`](https://munzlingersb.github.io/cipasa-brand/) — paleta, tipografia, componentes de ad
- **Design system para LLMs:** [`DESIGN.md`](./DESIGN.md) — tokens YAML + prosa (spec: [google-labs-code/design.md](https://github.com/google-labs-code/design.md))
- **Contexto de produto:** [`PRODUCT.md`](./PRODUCT.md) — público, tom, ângulos de comunicação, naming

## Como usar com LLMs

Use `DESIGN.md` como fonte dos tokens de design (cores, tipografia, componentes) e `PRODUCT.md` como contexto estratégico da marca. Juntos, eles substituem um briefing manual para qualquer agente de geração de criativos.

```
DESIGN.md   → cores exatas (hex), fontes, border-radius, componentes (tarja, CTA, logo badge)
PRODUCT.md  → público-alvo, tom de voz, ângulos de comunicação, naming dos arquivos
```

## Design System — Resumo

| Token | Valor | Uso |
|---|---|---|
| `vpa-forest` | `#2A5C3C` | Tarjas, backgrounds, CTAs |
| `vpa-coral` | `#E5734A` | CTA principal, pin destaque |
| `vpa-paper` | `#F5F4EE` | Background cards editoriais |
| `vpa-grass` | `#4D7C0F` | Pinos de mapa, barras |
| Fonte primária | Work Sans | Headlines e body |
| Fonte display | Montserrat | Big numbers |

## Segurança

Este repositório é uma cópia pública sanitizada. Contém apenas HTML, Markdown e SVG do brandbook. Não inclui arquivos de ambiente, chaves, tokens, configurações de deploy ou automações internas.

## Empreendimento

**Verana Parque Alvorada** — loteamento fechado em Marília-SP, Rod. Rachid Rayes (SP-333) km 336, Região dos Vales. Lotes a partir de 250 m². Financiamento direto com a Cipasa Urbanismo.

---

*Design system mantido por [Agência Iluminar7S](https://iluminar7s.com.br) · Todos os direitos reservados Cipasa Urbanismo.*
