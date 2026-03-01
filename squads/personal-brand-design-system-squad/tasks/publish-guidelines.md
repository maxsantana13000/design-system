---
task: "Publish Guidelines"
responsavel: "@documentation-writer"
responsavel_type: agent
atomic_layer: task
Entrada: |
  - componentes-base
  - decisoes-de-arquitetura
Saida: |
  - guia-de-uso
  - pagina-de-documentacao
Checklist:
  - "[ ] Validate input parameters"
  - "[ ] Execute main logic"
  - "[ ] Format output"
  - "[ ] Return result"
---

# *publish-guidelines

Task generated from squad design blueprint for personal-brand-design-system-squad.

## Usage

```
@documentation-writer
*publish-guidelines
```

## Parameters

| Parameter | Type | Required | Description |
|-----------|------|----------|-------------|
| `componentes-base` | string | Yes | componentes-base |
| `decisoes-de-arquitetura` | string | Yes | decisoes-de-arquitetura |

## Output

- **guia-de-uso**: guia-de-uso
- **pagina-de-documentacao**: pagina-de-documentacao

## Origin

Confidence: 90%
