# Gemini API Skills

These skills are vendored from [google-gemini/gemini-skills](https://github.com/google-gemini/gemini-skills)
(Apache 2.0, see [LICENSE](LICENSE)) so that coding agents working on this repo
have up-to-date Gemini API knowledge — current model names, SDK usage, and best
practices that post-date most models' training data.

| Skill | Use for |
| :--- | :--- |
| [`gemini-api-dev`](gemini-api-dev/SKILL.md) | Everything using `ai.models.generateContent` — text, images, audio, video, tools, structured output, thinking. This covers demos 01–18. |
| [`gemini-live-api-dev`](gemini-live-api-dev/SKILL.md) | The real-time WebSocket Live API (`ai.live.connect`) — audio streaming, VAD, transcription. This covers demo 19. |

To refresh them from upstream:

```sh
npx skills add google-gemini/gemini-skills --list
```

Note for this repo: the demos are standalone browser HTML files using the
`@google/genai` JS SDK from esm.sh with a user-supplied API key, so the
`generateContent` API (not the server-side Interactions API) is the right
surface here. Request options must be nested under `config:` — the SDK
silently drops top-level `generationConfig`, `tools`, and `systemInstruction`.
