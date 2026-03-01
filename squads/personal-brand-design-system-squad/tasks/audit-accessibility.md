---
task: "Audit Accessibility"
responsavel: "@qa-accessibility"
responsavel_type: agent
atomic_layer: task
Entrada: |
  - componentes-base
  - guidelines
Saida: |
  - relatorio-acessibilidade
  - plano-de-correcao
Checklist:
  - "[ ] Validate input parameters"
  - "[ ] Execute main logic"
  - "[ ] Format output"
  - "[ ] Return result"
---

# *audit-accessibility

Task generated from squad design blueprint for personal-brand-design-system-squad.

## Usage

```
@qa-accessibility
*audit-accessibility
```

## Parameters

| Parameter | Type | Required | Description |
|-----------|------|----------|-------------|
| `componentes-base` | string | Yes | componentes-base |
| `guidelines` | string | Yes | guidelines |

## Output

- **relatorio-acessibilidade**: relatorio-acessibilidade
- **plano-de-correcao**: plano-de-correcao

## Origin

Confidence: 93%
