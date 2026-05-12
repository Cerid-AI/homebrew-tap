# Cerid-AI Homebrew Tap

Homebrew formulas for [Cerid AI](https://github.com/Cerid-AI) projects.

## Install

```sh
brew tap cerid-ai/tap
```

## Available formulas

| Formula | Description | Upstream |
|---|---|---|
| `quenchforge` | Local LLM, embedding, reranker, image-gen, TTS, and Whisper inference for Mac + AMD discrete GPU. Ollama- and OpenAI-compatible HTTP APIs. | [`Cerid-AI/quenchforge`](https://github.com/Cerid-AI/quenchforge) |

## Quick start

```sh
brew install cerid-ai/tap/quenchforge
brew services start quenchforge
quenchforge doctor
```

## How this tap stays current

Formulas in this tap are **auto-generated** by [goreleaser](https://goreleaser.com)
running in each upstream project's release workflow. Manual edits to
`Formula/*.rb` will be overwritten on the next release.

If you need to override behaviour locally, install in HEAD mode or run from
source — see each upstream project's README.

## Sponsorship

This tap is sponsored by Cerid AI. The Quenchforge formula itself is
Apache-2.0 (the binaries are unsigned bootstrap builds today; signed +
notarized releases will land once Apple Developer ID is wired in).

## License

This metadata repository is BSD-2-Clause. Each formula points at the
upstream project's own license.
