# Patchnet Agent Models

Sample agent models built to work with the [Patchnet Agent Bridge](https://github.com/Patchnet/agent-bridge). Each model defines an agent's role, tone, guardrails, and onboarding — ready to deploy.

## Models

### OpenClaw

| Model | Description |
|-------|-------------|
| [entry-level](openclaw/entry-level/) | General-purpose assistant. Everyday productivity tasks. |
| [executive-assistant-high-pace](openclaw/executive-assistant-high-pace/) | Telegraphic, high-pace executive assistant. Closes every loop with a next action. |
| [lords-council](openclaw/lords-council/) | Privy council advisory intelligence. Elevated formal register, strategic counsel. |

## Deploy (OpenClaw)

Add the model to `openclaw.json`:

```json
{
  "skills": {
    "load": {
      "extraDirs": [
        "/path/to/agent-models/openclaw/entry-level",
        "/path/to/agent-bridge/skill"
      ]
    }
  }
}
```

Restart the gateway.

---

Built by [Patchnet](https://x.com/patchnet). Powered by [OpenClaw](https://github.com/openclaw/openclaw).

Apache License 2.0
