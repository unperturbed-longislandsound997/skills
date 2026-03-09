# Skills

Skills used with agents, by Emmanuel Paraskakis.

## API Design

- **design-api** — End-to-end: requirements → stories → review → OpenAPI spec → lint → iterate. One skill, one flow. Defaults to OpenAPI 3.1.0 for maximum tool compatibility — override by specifying a version in your input. If you already have stories, provide them as input and the skill skips straight to spec generation.
- **design-api-stories** — Stories only. Use if you just need the stories step.
- **design-api-spec** — Spec only. Use if you already have stories and want to go straight to a spec.

For a complete working example (inputs and outputs), see [`paraskakis/apidesign/conference`](https://github.com/paraskakis/apidesign/tree/main/conference).

### Optional dependencies

For the full experience (automated linting + local preview):

- **RateMyOpenAPI API key** (free) — [api.ratemyopenapi.com/docs](https://api.ratemyopenapi.com/docs). Set as `RMOA_API_KEY` env var.
- **Node.js** — for Swagger UI preview via `npx http-server`.
- **curl + python3** — for the RMOA API call (usually pre-installed).

Without these, the skills still generate a complete OpenAPI spec.

See the `api/` folder.
