# SnapDub agent skills

Skills that let an AI agent use [SnapDub](https://snapdub.ai): turn a long video (stream, podcast, interview, gameplay) into short vertical clips with captions, pick the best ones, schedule them to TikTok, YouTube or Instagram, and find live paid clipping campaigns.

## Install

**Hermes Agent**

```bash
hermes skills tap add aheront/snapdub-skills
hermes skills install snapdub
```

**OpenClaw**

```bash
clawhub install snapdub
```

## Connect SnapDub

Two ways, the skill explains both:

1. **MCP server (recommended, works on the free plan):** add `https://snapdub.ai/mcp` and sign in.
2. **REST API (paid plans):** set `SNAPDUB_API_KEY`, created at https://snapdub.ai/developers/api.

## What is inside

- `skills/snapdub/SKILL.md`: when to use SnapDub and the step by step procedure.
- `skills/snapdub/references/rest-api.md`: the REST calls the skill uses.

More about the connector: https://snapdub.ai/mcp-server

License: MIT
