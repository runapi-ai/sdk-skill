<p align="center">
  <a href="https://runapi.ai">
    <img src="https://runapi.ai/icon.svg" height="56" alt="RunAPI">
  </a>
</p>

<p align="center">
  <a href="https://github.com/runapi-ai/sdk-skill">
    <h3 align="center">RunAPI SDK Skill</h3>
  </a>
</p>

<p align="center">
  Choose the right RunAPI model SDK package for JavaScript, Ruby, or Go.
</p>

<p align="center">
  <a href="https://runapi.ai/models"><strong>Model SDKs</strong></a> · <a href="https://www.skills.sh/runapi-ai"><strong>Agent Skills</strong></a> · <a href="https://github.com/runapi-ai/core-sdk"><strong>Core SDK</strong></a>
</p>

<div align="center">

[![skills.sh](https://www.skills.sh/b/runapi-ai/sdk-skill)](https://www.skills.sh/runapi-ai/sdk-skill/sdk)
[![ClawHub](https://img.shields.io/badge/ClawHub-runapi--sdk-111827)](https://clawhub.ai/runapi-ai/runapi-sdk)
[![Model SDKs](https://img.shields.io/badge/Model%20SDKs-runapi.ai-0f766e)](https://runapi.ai/models)
[![Core SDK](https://img.shields.io/badge/RunAPI-Core%20SDK-111827)](https://github.com/runapi-ai/core-sdk)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-skills.sh-2563eb)](https://www.skills.sh/runapi-ai)
[![License](https://img.shields.io/github/license/runapi-ai/sdk-skill)](https://github.com/runapi-ai/sdk-skill/blob/main/LICENSE)

</div>
<br/>

Choose and install the right RunAPI model SDK for JavaScript, Ruby, or Go. This skill helps Claude Code, Codex, Gemini CLI, Cursor, and 50+ agents pick the correct SDK package and link to public docs.

The canonical agent file is `skills/sdk/SKILL.md`.

## Install

```bash
npx skills add runapi-ai/sdk-skill -g
```

Or paste this prompt to your AI agent:

```text
Install the sdk skill for me:

1. Clone https://github.com/runapi-ai/sdk-skill
2. Copy the skills/sdk/ directory into your
   user-level skills directory (e.g. ~/.claude/skills/
   for Claude Code, ~/.codex/skills/ for Codex).
3. Verify that SKILL.md is present.
4. Confirm the install path when done.
```

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
