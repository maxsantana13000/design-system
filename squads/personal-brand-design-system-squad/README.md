# personal-brand-design-system-squad

Squad para criar e evoluir o Design System da marca pessoal

## Installation

This squad is installed locally in your project:

```
./squads/personal-brand-design-system-squad/
```

## Usage

Activate agents from this squad and use their commands.

### Available Agents

- brand-strategist
- design-system-architect
- ui-component-designer
- documentation-writer
- qa-accessibility

### Available Tasks

- define-brand-foundation
- define-design-tokens
- design-core-components
- publish-guidelines
- audit-accessibility

## Brand Foundation Assets

- `data/brand-foundation.md`: manifesto visual e direcao fotografica
- `data/design-tokens.json`: tokens-base de cor, tipografia, espacamento e radii
- `data/design-tokens.css`: variaveis CSS de tokens
- `templates/brand-foundation-preview.html`: preview visual inicial da marca

## Visual Preview

Abra o preview no navegador:

```bash
open ./squads/personal-brand-design-system-squad/templates/brand-foundation-preview.html
```

Ou publique esse arquivo no seu site como pagina de referencia interna.

## Configuration

This squad extends the core AIOS configuration.

## Development

1. Add agents in `agents/` directory
2. Add tasks in `tasks/` directory (task-first architecture!)
3. Update `squad.yaml` components section
4. Validate: `@squad-creator *validate-squad personal-brand-design-system-squad`

## License

MIT
