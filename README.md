# Editor AI

Describe a Geometry Dash level in plain words and watch it get built for you. EditorAI talks to the AI of your choice, then places the result in the editor on its own preview layer you can accept, edit, or deny — your level, your call, always.

*Consider supporting the project by starring it on [GitHub](https://github.com/entity12208/editorai).*

## Install

1. Download the [latest release](https://github.com/entity12208/editorai/releases/latest) (`.geode` file)
2. In GD, open the **Geode** page → press the **manual install** button → pick the file
3. Restart the game

> EditorAI is distributed here rather than on the Geode index, whose guidelines don't allow AI-placed objects.

## Open the panel

Press **E** anywhere in the game (desktop), or tap the floating **AI** bubble (mobile). Everything lives in that panel: starting generations, watching them run, chatting with the AI, and every setting.

## Pick an AI

Open the panel → **Settings** → choose a provider. Two are free with zero accounts:

- **Platinum** *(free, community-run — servers by [VLT GG](https://vltgg.net))* — set provider to `ollama`, enable **Use Platinum**. Your prompts run on volunteer machines, so keep personal info out of them. Want to donate compute? See the [Platinum repository](https://github.com/entity12208/editorai-platinum).
- **Ollama** *(free, fully local — recommended with 6+ GB VRAM)* — install [Ollama](https://ollama.com), pull a model, set provider to `ollama`, pick the model. Nothing leaves your machine.

For hosted providers, pick one and either press **Sign in with browser** (OpenRouter, HuggingFace — no key-copying needed) or paste an API key:

| Provider | Get a key |
|---|---|
| OpenRouter | sign-in button, or [openrouter.ai/keys](https://openrouter.ai/keys) |
| HuggingFace | sign-in button, or [huggingface.co/settings/tokens](https://huggingface.co/settings/tokens) |
| Claude | [console.anthropic.com](https://console.anthropic.com) |
| OpenAI | [platform.openai.com/api-keys](https://platform.openai.com/api-keys) |
| Mistral | [console.mistral.ai](https://console.mistral.ai/api-keys/) |
| DeepSeek | [platform.deepseek.com](https://platform.deepseek.com) |
| Groq | [console.groq.com/keys](https://console.groq.com/keys) *(free tier, fastest inference)* |
| Gemini | [aistudio.google.com](https://aistudio.google.com/api-keys) *(tight rate limits)* |

LM Studio, llama.cpp, and any OpenAI-compatible endpoint work too — point the URL at your server.

## Use it

1. Panel → **Generate**
2. Pick a target: the current editor, a brand-new level, or any of your created levels
3. Describe what you want, set difficulty/style/length (or type your own), press **Generate**
4. Watch it think and work live in **Sessions** — you can close the panel, or even the editor, while it runs
5. With **live block placement** (default on) blocks appear in the editor while the AI is still building; the result lands on its own editor layer (the rest of the level fades back): **Accept**, **Edit**, or **Deny**
6. Keep talking to it in Sessions to refine, plan, or just ask questions
7. Rate generations when asked — your ratings teach the AI your taste over time

Every option in the panel has a hover tooltip explaining what it does.

While it works, the AI can analyze your level's **song** (BPM + waveform) to sync gameplay to the music, keep **scratch memory** between generations, and set itself a **goal with a task checklist** that it grinds through until done — watch the checklist tick off in the status line and session log.

## Fine-tune your own model

Join the [HuggingFace org](https://huggingface.co/EditorAI-Geode/) to publish models trained on EditorAI datasets.

## Support

Found a bug or have an idea? [Open an issue](https://github.com/entity12208/editorai/issues) or [fork the repository](https://github.com/entity12208/EditorAI/fork).
You can also check to see if there is a [fork](https://github.com/entity12208/editorai/forks) where the bug is fixed.


### EditorAI (Android64 Fork)

> ⚠️ **This is an unofficial fork.** It is not an official release from, nor endorsed by, the original creator.
> Original project: https://github.com/Entity12208/EditorAI
> All credit for the original mod goes to [Entity12208](https://github.com/Entity12208).

## Why this fork exists
Improves Android64 (arm64-v8a) support for EditorAI: build/CI, mobile networking, touch UI, and stability.

## Based on
Forked from upstream version/commit: `[vX.X.X / commit hash]`

## Changes from upstream
- [Replace with your actual changes]
- [e.g. Added android64 build to CI]
- [e.g. Added LAN IP guidance and a connection test button for local providers]

## Installation
[Write the Android64 build and install steps here]

## Known limitations
- Local providers (Ollama, LM Studio, llama.cpp) require your PC's LAN IP. `localhost` will not work on a phone.
- [Add other limitations]

## AI-assisted development
Parts of this fork were written with the help of an AI coding assistant and were reviewed and tested by the maintainer on: `[device / Android version / Geode version]`.

## AI-assisted development and language note
I am not fluent in English, so I used an AI assistant to help write this README
and other English text (issues, pull requests, and comments). Please forgive any
awkward or unnatural phrasing.

Parts of this fork's code were also written with the help of an AI coding assistant.
All changes were reviewed and tested by the maintainer on:
`[device / Android version / Geode version]`.

## Reporting issues
Please report issues with this fork in **this** repository.
Do not contact the original author about problems in this fork.

## Upstream contribution
Where possible, changes are offered back to upstream as pull requests.

## Disclaimer
This fork is provided "as is" without warranty of any kind. Some code was AI-assisted and may contain bugs.

## License
Same license as upstream (see [LICENSE](./LICENSE)).
The original copyright notice is preserved.

