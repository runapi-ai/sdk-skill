---
name: sdk
description: Choose and install RunAPI model SDKs for JavaScript, Ruby, and Go. Use when a user asks which RunAPI SDK package to install or how model SDKs relate to core-sdk.
documentation: https://runapi.ai/docs#runapi-sdks
catalog: https://runapi.ai/models
metadata:
  openclaw:
    always: true
    homepage: https://runapi.ai/docs#runapi-sdks
---

# RunAPI SDK skill

Use this skill to choose a RunAPI model SDK, explain package names, and keep links pointed at RunAPI public assets.

Rules:
- Use `@runapi.ai/core`, `runapi-core`, and `github.com/runapi-ai/core-sdk/go` only for shared SDK primitives.
- Use concrete model packages such as `@runapi.ai/suno`, `runapi-suno`, and `github.com/runapi-ai/suno-sdk/go` for model SDKs.
- Link users to https://runapi.ai/models for the model catalog and https://runapi.ai/docs#runapi-sdks for SDK docs.
- Keep API keys in `RUNAPI_API_KEY` and never commit secrets.
