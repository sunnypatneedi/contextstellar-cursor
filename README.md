# contextstellar-cursor

Cursor IDE plugin for [ContextStellar](https://contextstellar.com) — context observability for LLM applications.

## What it does

- Adds context engineering rules to your Cursor workspace
- Provides skills for analyzing prompt context structure
- Integrates with `@contextstellar/engine` for transcript analysis

## Installation

Install from the Cursor Marketplace, or clone this repo into your `.cursor/` directory.

## Structure

```
rules/          # Cursor rules (.mdc files)
skills/         # Cursor skills
assets/         # Plugin assets
```

## Related

- [@contextstellar/sdk](https://github.com/sunnypatneedi/contextstellar-js/tree/main/packages/sdk) — Context observability SDK
- [@contextstellar/engine](https://github.com/sunnypatneedi/contextstellar-js/tree/main/packages/engine) — Transcript decision extractor
- [ContextStellar Dashboard](https://contextstellar.com) — Web dashboard

## License

MIT
