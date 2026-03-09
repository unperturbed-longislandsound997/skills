# Skills

Skills used with agents, by Emmanuel Paraskakis.

## API Design

Two skills that chain together to design APIs using LLMs:

1. **design-api-stories** — Generate API user stories from requirements, a domain model, and API standards.
2. **design-api-spec** — Generate an OpenAPI spec from stories, then lint and iterate to quality. Defaults to OpenAPI 3.1.0 for maximum tool compatibility — override by specifying a version in your input.

For a complete working example (inputs and outputs), see [`paraskakis/apidesign/conference`](https://github.com/paraskakis/apidesign/tree/main/conference).

See the `api/` folder.
