# Skills

Skills used with agents, by Emmanuel Paraskakis.

## API Design

- **design-api** — End-to-end: requirements → stories → review → OpenAPI spec → lint → iterate. One skill, one flow. Defaults to OpenAPI 3.1.0 for maximum tool compatibility — override by specifying a version in your input. If you already have stories, provide them as input and the skill skips straight to spec generation.
- **design-api-stories** — Stories only. Use if you just need the stories step.
- **design-api-spec** — Spec only. Use if you already have stories and want to go straight to a spec.

For a complete working example (inputs and outputs), see [`paraskakis/apidesign/conference`](https://github.com/paraskakis/apidesign/tree/main/conference).

See the `api/` folder.
