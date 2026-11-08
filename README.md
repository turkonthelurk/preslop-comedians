# preslop-comedians

Local-first structural style packs for classic pre-2020 comedians and comic actors.

## Legal boundary (read first)

This repository contains **structural analyses and system prompts only**.  
No raw transcripts, no voice clones, no verbatim material from any special or sketch.

All packs are framed as:
- Inspired by structural patterns
- Not affiliated with any comedian or estate
- AI-generated pastiche for local experimentation
- Fair-use style commentary / parody framing

Right of publicity and copyright risks remain for living named performers. Use at your own risk. Do not represent outputs as the real comedian's work.

## Goal

Enable local LLM runs (Ollama, Grok Build, Unsloth QLoRA, etc.) that capture recognizable comic cadences and moves without feeding hyperscalers or scraping commercial specials.

## Usage

1. Pick a persona under `personas/`.
2. Load the system-prompt.md into your local model.
3. Or follow the (future) training-recipe.md for a lightweight adapter.
4. Verify with the eval protocol before shipping anything public.

## Personas

46 total (42 + original examples). See `personas/index.yaml`.

v0.1 = analyses + prompts only. Synthetic data and training recipes come later after human verification that outputs are actually funny and distinct.
