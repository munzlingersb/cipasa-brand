# Icons — Sistema de ícones Cipasa

6 ícones do sistema, todos em traço linear `2px`, viewBox `0 0 32 32`, com `currentColor` para herdar cor via CSS.

| Arquivo | Uso |
|---|---|
| `lazer.svg` | Amenidades, lazer integrado, áreas comuns |
| `seguranca.svg` | Portaria 24h, condomínio fechado, segurança |
| `natureza.svg` | Vegetação preservada, urbanismo responsável |
| `lote-area.svg` | Área do lote em m² (ex: "lotes a partir de 300m²") |
| `construcao.svg` | "Pronto para construir", liberado para obra |
| `parcela.svg` | Parcelamento, condições de pagamento |

## Como usar

### Inline em HTML
```html
<svg style="color: #62BB46;">
  <use href="assets/icons/lote-area.svg#lote-area"/>
</svg>
```

### Em badges de dados (uso típico Cipasa)
```html
<div class="badge-data" style="background: #62BB46; color: white; padding: 14px 20px; border-radius: 14px; display: flex; align-items: center; gap: 12px;">
  <svg width="28" height="28" viewBox="0 0 32 32" stroke="currentColor" stroke-width="2" fill="none">
    <use href="assets/icons/lote-area.svg#lote-area"/>
  </svg>
  <div>
    <div style="font-size: 14px;">lotes a partir de</div>
    <div style="font-size: 48px; font-weight: 900;">300m²</div>
  </div>
</div>
```

### Cor

Os ícones usam `currentColor` no atributo `stroke` — herdam a cor do elemento pai. Em badges lima sobre lima, defina `color: white;` no container do badge.
