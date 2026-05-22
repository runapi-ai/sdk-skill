# RunAPI SDK Skill

[![skills.sh](https://skills.sh/b/runapi-ai/sdk-skill)](https://skills.sh/runapi-ai/sdk-skill)

Choose and install the right RunAPI model SDK for JavaScript, Ruby, or Go. This skill helps Claude Code, Codex, Gemini CLI, Cursor, and 50+ agents pick the correct SDK package and link to public docs.

The canonical agent file is `skills/sdk/SKILL.md`.

## Install

```bash
npx skills add runapi-ai/sdk-skill -g
```

Or manually: clone this repo and copy `skills/sdk/` into your agent's skills directory.

## Quick example

Each AI model has its own SDK package. Install the one you need:

```bash
npm install @runapi.ai/kling        # Kling video generation
npm install @runapi.ai/suno         # Suno music generation
npm install @runapi.ai/flux-kontext # Flux Kontext image generation
npm install @runapi.ai/elevenlabs   # ElevenLabs audio
```

All RunAPI model SDKs share `@runapi.ai/core` for HTTP primitives and error types.

## Use this skill when

- A user asks which JavaScript, Ruby, or Go RunAPI SDK package to install.
- A user asks why each model has its own model SDK repository.
- An agent needs to route pricing or documentation links without guessing URL shapes.

## Links

- SDK docs: https://runapi.ai/docs#runapi-sdks
- Model catalog: https://runapi.ai/models
- Repository: https://github.com/runapi-ai/sdk-skill

## License

Licensed under the Apache License, Version 2.0.
