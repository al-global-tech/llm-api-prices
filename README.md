# LLM API prices

*MartLLM was called UberLLM until November 2026; the `uberllm_*` column names stay as they are.*

An open, daily-updated dataset of AI API prices: the official list price of 871 text, image, video, music and speech models next to the lowest live price on the [MartLLM](https://martllm.com/models) market, how far below list that is, context length and capabilities.

**Updated:** 2026-11-26T03:17:07Z · **Models:** 469 text, 178 image, 176 video, 21 music, 17 speech, 10 transcription · **Files:** [`prices.json`](prices.json), [`prices.csv`](prices.csv), [`CHANGELOG.md`](CHANGELOG.md), [`history/`](history/)

Disclosure: this repo is maintained by the team that runs MartLLM. The MartLLM column is our own price; the official column is the maker's price, sourced as described in [Sources](#sources). Live prices: <https://martllm.com/models>.

## Cheapest right now

Lowest MartLLM price per category among models that can be called now. Text: $ per 1M input / output tokens. Full list: [`prices.csv`](prices.csv).

### Text (chat) models

| Model | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | 32K | $0.04 / $0.04 | $0.00882 / $0.00882 | 78% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | 128K | $0.045 / $0.09 | $0.008978 / $0.01795 | 80% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | 128K | $0.04 / $0.08 | $0.0105 / $0.021 | 73.8% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | 128K | $0.03 / $0.15 | $0.005985 / $0.02993 | 80% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | 262K | $0.09 / $0.30 | $0.008505 / $0.02835 | 90.5% |
| [Solar Mini 4.5](https://martllm.com/models/upstage/solar-mini-4-5) | 524K | $0.01 / $0.04 | $0.0084 / $0.0336 | 16% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | 128K | $0.105 / $0.105 | $0.02205 / $0.02205 | 79% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | 128K | $0.0725 / $0.25 | $0.01066 / $0.03675 | 85.3% |
| [Mistral Nemo 12B](https://martllm.com/models/mistralai/mistral-nemo) | 131K | $0.029 / $0.03 | $0.02436 / $0.0252 | 16% |
| [Ling 3.0 Tiny](https://martllm.com/models/inclusionai/ling-3.0-tiny) | 262K | $0.015 / $0.045 | $0.0126 / $0.0378 | 16% |
| [NVIDIA Nemotron Nano 9B v2](https://martllm.com/models/nvidia/nemotron-nano-9b-v2) | 128K | $0.06 / $0.23 | $0.0126 / $0.0483 | 79% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | 256K | $0.11 / $0.44 | $0.0127 / $0.05082 | 88.5% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | 1000K | $0.15 / $0.47 | $0.01575 / $0.04935 | 89.5% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | 128K | $0.1575 / $0.1575 | $0.03308 / $0.03308 | 79% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | 128K | $0.0625 / $0.1875 | $0.01706 / $0.05119 | 72.7% |

### Major model makers

<details><summary>OpenAI, Anthropic, Google, DeepSeek, xAI, Qwen, Moonshot, Z.ai, Mistral, Meta (248 models)</summary>

| Model | Maker | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|---|
| [GPT-5.4 Pro](https://martllm.com/models/openai/gpt-5.4-pro) | openai | 1000K | $30.00 / $180.00 | $16.70 / $100.17 | 44.4% |
| [GPT-5.5 Pro](https://martllm.com/models/openai/gpt-5.5-pro) | openai | 1000K | $30.00 / $180.00 | $17.32 / $103.95 | 42.2% |
| [GPT 5.2](https://martllm.com/models/openai/gpt-5.2-pro) | openai | 400K | $21.00 / $168.00 | $15.88 / $127.01 | 24.4% |
| [GPT-5 pro](https://martllm.com/models/openai/gpt-5-pro) | openai | 400K | $15.00 / $120.00 | $11.34 / $90.72 | 24.4% |
| [o3 Pro](https://martllm.com/models/openai/o3-pro) | openai | 200K | $20.00 / $80.00 | $15.12 / $60.48 | 24.4% |
| [GPT-4](https://martllm.com/models/openai/gpt-4) | openai | 8K | $30.00 / $60.00 | $25.20 / $50.40 | 16% |
| [GPT-6 Astra](https://martllm.com/models/openai/gpt-6-astra) | openai | 1050K | $10.00 / $50.00 | $6.30 / $31.50 | 37% |
| [GPT-6 Astra Pro](https://martllm.com/models/openai/gpt-6-astra-pro) | openai | 1050K | $10.00 / $50.00 | $8.40 / $42.00 | 16% |
| [GPT-6.2 Astra](https://martllm.com/models/openai/gpt-6.2-astra) | openai | 1050K | $8.00 / $40.00 | $5.21 / $26.04 | 34.9% |
| [GPT-6.2 Astra Pro](https://martllm.com/models/openai/gpt-6.2-astra-pro) | openai | 1050K | $8.00 / $40.00 | $7.98 / $39.90 | 0.2–0.3% |
| [GPT-5.5](https://martllm.com/models/openai/gpt-5.5) | openai | 1000K | $5.00 / $30.00 | $1.89 / $11.34 | 62.2% |
| [GPT Chat Latest](https://martllm.com/models/openai/gpt-chat-latest) | openai | 400K | $5.00 / $30.00 | $4.20 / $25.20 | 16% |
| [GPT-5.6 Sol](https://martllm.com/models/openai/gpt-5.6-sol) | openai | 1050K | $4.00 / $20.00 | $1.97 / $9.87 | 50.6–50.7% |
| [GPT-5.6 Sol Pro](https://martllm.com/models/openai/gpt-5.6-sol-pro) | openai | 1050K | $4.00 / $20.00 | $3.91 / $19.53 | 2.3% |
| [GPT-4o (2024-05-13)](https://martllm.com/models/openai/gpt-4o-2024-05-13) | openai | 128K | $5.00 / $15.00 | $4.20 / $12.60 | 16% |
| [GPT-5.4](https://martllm.com/models/openai/gpt-5.4) | openai | 1000K | $2.50 / $15.00 | $0.945 / $5.67 | 62.2% |
| [GPT-5.2](https://martllm.com/models/openai/gpt-5.2) | openai | 256K | $1.75 / $14.00 | $0.588 / $4.70 | 66.4% |
| [GPT-5.2 Codex](https://martllm.com/models/openai/gpt-5.2-codex) | openai | 256K | $1.75 / $14.00 | $1.58 / $12.64 | 9.7% |
| [GPT-5.3 Codex](https://martllm.com/models/openai/gpt-5.3-codex) | openai | 400K | $1.75 / $14.00 | $0.6799 / $5.44 | 61.1% |
| [GPT-5.6 Terra](https://martllm.com/models/openai/gpt-5.6-terra) | openai | 1050K | $2.00 / $12.00 | $1.18 / $7.06 | 41.2% |
| [GPT-5.6 Terra Pro](https://martllm.com/models/openai/gpt-5.6-terra-pro) | openai | 1050K | $2.00 / $12.00 | $2.00 / $11.97 | 0.2% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | openai | 128K | $2.50 / $10.00 | $0.2362 / $0.945 | 90.5% |
| [GPT-4o (2024-08-06)](https://martllm.com/models/openai/gpt-4o-2024-08-06) | openai | 128K | $2.50 / $10.00 | $2.10 / $8.40 | 16% |
| [GPT-4o (2024-11-20)](https://martllm.com/models/openai/gpt-4o-2024-11-20) | openai | 128K | $2.50 / $10.00 | $1.89 / $7.56 | 24.4% |
| [GPT-5](https://martllm.com/models/openai/gpt-5) | openai | 400K | $1.25 / $10.00 | $0.945 / $7.56 | 24.4% |
| [GPT-5.1](https://martllm.com/models/openai/gpt-5.1) | openai | 400K | $1.25 / $10.00 | $0.945 / $7.56 | 24.4% |
| [GPT-5.1-Codex](https://martllm.com/models/openai/gpt-5.1-codex) | openai | 400K | $1.25 / $10.00 | $1.05 / $8.40 | 16% |
| [GPT 5.1 Codex Max](https://martllm.com/models/openai/gpt-5.1-codex-max) | openai | 400K | $1.25 / $10.00 | $1.05 / $8.40 | 16% |
| [GPT-6 Sol](https://martllm.com/models/openai/gpt-6-sol) | openai | 1050K | $2.00 / $10.00 | $1.22 / $6.09 | 39.1% |
| [GPT-6 Sol Pro](https://martllm.com/models/openai/gpt-6-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.97 / $9.87 | 1.3% |
| [GPT-6.1 Sol](https://martllm.com/models/openai/gpt-6.1-sol) | openai | 1050K | $2.00 / $10.00 | $1.03 / $5.14 | 48.6% |
| [OpenAI: GPT-6.1 Sol Pro](https://martllm.com/models/openai/gpt-6.1-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.97 / $9.87 | 1.3% |
| [GPT-6.2 Sol](https://martllm.com/models/openai/gpt-6.2-sol) | openai | 1050K | $2.00 / $10.00 | $1.09 / $5.46 | 45.4% |
| [GPT-6.2 Sol Pro](https://martllm.com/models/openai/gpt-6.2-sol-pro) | openai | 1050K | $2.00 / $10.00 | $2.02 / $10.08 | -0.8% |
| [GPT-4.1](https://martllm.com/models/openai/gpt-4.1) | openai | 1047K | $2.00 / $8.00 | $1.51 / $6.05 | 24.4% |
| [o3](https://martllm.com/models/openai/o3) | openai | 200K | $2.00 / $8.00 | $1.51 / $6.05 | 24.4% |
| [OpenAI: GPT-6.1 Terra](https://martllm.com/models/openai/gpt-6.1-terra) | openai | 1050K | $1.00 / $5.00 | $0.3885 / $1.94 | 61.1–61.2% |
| [OpenAI: GPT-6.1 Terra Pro](https://martllm.com/models/openai/gpt-6.1-terra-pro) | openai | 1050K | $1.00 / $5.00 | $0.987 / $4.93 | 1.3% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | openai | 400K | $0.75 / $4.50 | $0.2756 / $1.65 | 63.3% |
| [GPT-3.5 Turbo (older v0613)](https://martllm.com/models/openai/gpt-3.5-turbo-0613) | openai | 4K | $1.00 / $2.00 | $0.84 / $1.68 | 16% |
| [GPT 5 Mini](https://martllm.com/models/openai/gpt-5-mini) | openai | 400K | $0.25 / $2.00 | $0.05513 / $0.441 | 78% |
| [GPT 5.1 Codex Mini](https://martllm.com/models/openai/gpt-5.1-codex-mini) | openai | 400K | $0.25 / $2.00 | $0.21 / $1.68 | 16% |
| [GPT-4.1 mini](https://martllm.com/models/openai/gpt-4.1-mini) | openai | 1047K | $0.40 / $1.60 | $0.3024 / $1.21 | 24.4% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | openai | 400K | $0.20 / $1.25 | $0.042 / $0.2625 | 79% |
| [GPT-5.6 Luna](https://martllm.com/models/openai/gpt-5.6-luna) | openai | 1050K | $0.20 / $1.20 | $0.0693 / $0.4158 | 65.3% |
| [GPT-5.6 Luna Pro](https://martllm.com/models/openai/gpt-5.6-luna-pro) | openai | 1050K | $0.20 / $1.20 | $0.2079 / $1.25 | -4–-3.9% |
| [GPT OSS 120B](https://martllm.com/models/openai/e2ee-gpt-oss-120b-p) | openai | 128K | $0.13 / $0.65 | $0.1133 / $0.5665 | 12.8–12.9% |
| [GPT-4o Mini](https://martllm.com/models/openai/gpt-4o-mini) | openai | 128K | $0.15 / $0.60 | $0.03623 / $0.1449 | 75.8% |
| [GPT-4o-mini (2024-07-18)](https://martllm.com/models/openai/gpt-4o-mini-2024-07-18) | openai | 128K | $0.15 / $0.60 | $0.126 / $0.504 | 16% |
| [GPT OSS Safeguard 120B](https://martllm.com/models/openai/gpt-oss-safeguard-120b) | openai | 128K | $0.15 / $0.60 | $0.03938 / $0.1575 | 73.8% |
| [GPT-6 Luna](https://martllm.com/models/openai/gpt-6-luna) | openai | 1050K | $0.10 / $0.50 | $0.03675 / $0.1837 | 63.3% |
| [GPT-6 Luna Pro](https://martllm.com/models/openai/gpt-6-luna-pro) | openai | 1050K | $0.10 / $0.50 | $0.0987 / $0.4935 | 1.3% |
| [GPT-4.1 nano](https://martllm.com/models/openai/gpt-4.1-nano) | openai | 1047K | $0.10 / $0.40 | $0.084 / $0.336 | 16% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | openai | 400K | $0.05 / $0.40 | $0.0147 / $0.1176 | 70.6% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | openai | 128K | $0.07 / $0.30 | $0.01544 / $0.06615 | 78% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | openai | 128K | $0.0725 / $0.25 | $0.01066 / $0.03675 | 85.3% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | openai | 128K | $0.03 / $0.15 | $0.005985 / $0.02993 | 80% |
| [Claude Opus 4.1](https://martllm.com/models/anthropic/claude-opus-4.1) | anthropic | 200K | $15.00 / $75.00 | $12.60 / $63.00 | 16% |
| [Claude Fable 5](https://martllm.com/models/anthropic/claude-fable-5) | anthropic | 1000K | $10.00 / $50.00 | $7.67 / $38.33 | 23.3–23.4% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | anthropic | 1000K | $10.00 / $50.00 | $6.30 / $31.50 | 37% |
| [Claude Opus 5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5-fast) | anthropic | 1000K | $10.00 / $50.00 | $7.35 / $36.75 | 26.5% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | anthropic | 1000K | $8.00 / $40.00 | $6.30 / $31.50 | 21.3% |
| [Claude Opus 4.5](https://martllm.com/models/anthropic/claude-opus-4.5) | anthropic | 198K | $5.00 / $25.00 | $3.36 / $16.80 | 32.8% |
| [Claude Opus 4.6](https://martllm.com/models/anthropic/claude-opus-4.6) | anthropic | 1000K | $5.00 / $25.00 | $2.78 / $13.91 | 44.4% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | anthropic | 1000K | $5.00 / $25.00 | $2.68 / $13.39 | 46.4–46.5% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | anthropic | 1000K | $5.00 / $25.00 | $2.52 / $12.60 | 49.6% |
| [Claude Opus 5](https://martllm.com/models/anthropic/claude-opus-5) | anthropic | 1000K | $5.00 / $25.00 | $2.94 / $14.70 | 41.2% |
| [Claude Opus 5.5](https://martllm.com/models/anthropic/claude-opus-5.5) | anthropic | 1000K | $4.00 / $20.00 | $2.06 / $10.29 | 48.6% |
| [Claude Sonnet 4.5](https://martllm.com/models/anthropic/claude-sonnet-4.5) | anthropic | 198K | $3.00 / $15.00 | $2.24 / $11.18 | 25.5% |
| [Claude Sonnet 4.6](https://martllm.com/models/anthropic/claude-sonnet-4.6) | anthropic | 1000K | $3.00 / $15.00 | $1.61 / $8.03 | 46.4–46.5% |
| [Claude Sonnet 5](https://martllm.com/models/anthropic/claude-sonnet-5) | anthropic | 1000K | $2.00 / $10.00 | $0.882 / $4.41 | 55.9% |
| [Claude Sonnet 5.5](https://martllm.com/models/anthropic/claude-sonnet-5.5) | anthropic | 1000K | $2.00 / $10.00 | $1.30 / $6.51 | 34.9% |
| [Claude Haiku 4.5](https://martllm.com/models/anthropic/claude-haiku-4.5) | anthropic | 200K | $1.00 / $5.00 | $1.05 / $5.25 | -5% |
| [Claude Haiku 5.5](https://martllm.com/models/anthropic/claude-haiku-5.5) | anthropic | 1000K | $0.10 / $0.50 | $0.063 / $0.315 | 37% |
| [Google: Gemini 4 Neon](https://martllm.com/models/google/gemini-4-neon) | google | 1048K | $3.00 / $15.00 | $0.9765 / $4.88 | 67.5% |
| [Nano Banana Pro (Gemini 3 Pro Image)](https://martllm.com/models/google/gemini-3-pro-image) | google | 65K | $2.00 / $12.00 | $1.68 / $10.08 | 16% |
| [Nano Banana Pro (Gemini 3 Pro Image Preview)](https://martllm.com/models/google/gemini-3-pro-image-preview) | google | 65K | $2.00 / $12.00 | $1.68 / $10.08 | 16% |
| [Gemini 3.1 Pro Preview](https://martllm.com/models/google/gemini-3.1-pro-preview) | google | 1000K | $2.00 / $12.00 | $0.273 / $1.64 | 86.3–86.4% |
| [Gemini 3.1 Pro Preview Custom Tools](https://martllm.com/models/google/gemini-3.1-pro-preview-customtools) | google | 1048K | $2.00 / $12.00 | $1.68 / $10.08 | 16% |
| [Gemini 2.5 Pro](https://martllm.com/models/google/gemini-2.5-pro) | google | 1048K | $1.25 / $10.00 | $1.05 / $8.40 | 16% |
| [Gemini 2.5 Pro Preview 06-05](https://martllm.com/models/google/gemini-2.5-pro-preview) | google | 1048K | $1.25 / $10.00 | $1.05 / $8.40 | 16% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | google | 1048K | $2.00 / $10.00 | $0.399 / $2.00 | 80% |
| [Google: Gemini 4 Carbon](https://martllm.com/models/google/gemini-4-carbon) | google | 1048K | $2.00 / $10.00 | $0.882 / $4.41 | 55.9% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | google | 1000K | $1.50 / $9.00 | $0.1103 / $0.6615 | 92.7% |
| [Gemini Omni 1.1 Flash](https://martllm.com/models/google/gemini-omni-1.1-flash) | google | 131K | $1.50 / $9.00 | $1.26 / $7.56 | 16% |
| [Gemini Omni 1.2 Flash](https://martllm.com/models/google/gemini-omni-1.2-flash) | google | 131K | $1.50 / $9.00 | $1.26 / $7.56 | 16% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | google | 1048K | $1.50 / $7.50 | $0.2047 / $1.02 | 86.4% |
| [Gemini Nano Banana 2.1](https://martllm.com/models/google/gemini-nano-banana-2.1) | google | 131K | $1.50 / $7.50 | $1.26 / $6.30 | 16% |
| [Gemini 3.6 Flash](https://martllm.com/models/google/gemini-3-6-flash) | google | 1000K | $0.75 / $3.75 | $0.6221 / $3.11 | 17% |
| [Gemini 3.7 Flash](https://martllm.com/models/google/gemini-3.7-flash) | google | 1048K | $0.75 / $3.75 | $0.6142 / $3.07 | 18.1% |
| [Gemini 3.8 Flash](https://martllm.com/models/google/gemini-3.8-flash) | google | 1048K | $0.75 / $3.75 | $0.126 / $0.63 | 83.2% |
| [Gemini 3 Flash](https://martllm.com/models/google/gemini-3-flash) | google | 1000K | $0.50 / $3.00 | $0.42 / $2.52 | 16% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | google | 256K | $0.50 / $3.00 | $0.0945 / $0.567 | 81.1% |
| [Gemini 3.1 Flash Image (Nano Banana 2)](https://martllm.com/models/google/gemini-3.1-flash-image) | google | 131K | $0.50 / $3.00 | $0.42 / $2.52 | 16% |
| [Nano Banana 2 (Gemini 3.1 Flash Image Preview)](https://martllm.com/models/google/gemini-3.1-flash-image-preview) | google | 65K | $0.50 / $3.00 | $0.42 / $2.52 | 16% |
| [Gemini 2.5 Flash](https://martllm.com/models/google/gemini-2.5-flash) | google | 1048K | $0.30 / $2.50 | $0.252 / $2.10 | 16% |
| [Gemini 3.1 Flash Lite](https://martllm.com/models/google/gemini-3.1-flash-lite) | google | 1048K | $0.25 / $1.50 | $0.189 / $1.13 | 24.4% |
| [Gemini 3.1 Flash Lite Image (Nano Banana 2 Lite)](https://martllm.com/models/google/gemini-3.1-flash-lite-image) | google | 65K | $0.25 / $1.50 | $0.21 / $1.26 | 16% |
| [Gemini 3.1 Flash Lite Preview](https://martllm.com/models/google/gemini-3.1-flash-lite-preview) | google | 1048K | $0.25 / $1.50 | $0.189 / $1.13 | 24.4% |
| [Gemini 2.5 Flash Lite](https://martllm.com/models/google/gemini-2.5-flash-lite) | google | 1048K | $0.10 / $0.40 | $0.084 / $0.336 | 16% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | google | 256K | $0.12 / $0.36 | $0.0189 / $0.0567 | 84.2% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | google | 262K | $0.12 / $0.36 | $0.06294 / $0.1888 | 47.6% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | google | 262K | $0.09 / $0.30 | $0.008505 / $0.02835 | 90.5% |
| [Gemma 3 27B](https://martllm.com/models/google/gemma-3-27b-it) | google | 40K | $0.08 / $0.20 | $0.02268 / $0.0567 | 71.7% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | google | 128K | $0.0625 / $0.1875 | $0.01706 / $0.05119 | 72.7% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | google | 128K | $0.045 / $0.09 | $0.008978 / $0.01795 | 80% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | google | 128K | $0.04 / $0.08 | $0.0105 / $0.021 | 73.8% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | deepseek | 1048K | $1.31 / $3.96 | $0.2209 / $0.6653 | 83.2% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | deepseek | 1000K | $1.36 / $2.72 | $0.4135 / $0.827 | 69.5% |
| [R1 0528](https://martllm.com/models/deepseek/deepseek-r1-0528) | deepseek | 163K | $0.571 / $2.29 | $0.3856 / $1.16 | 32.5–49.1% |
| [DeepSeek V3](https://martllm.com/models/deepseek/deepseek-chat) | deepseek | 163K | $0.2574 / $1.03 | $0.2162 / $0.8641 | 16% |
| [DeepSeek V3 0324](https://martllm.com/models/deepseek/deepseek-chat-v3-0324) | deepseek | 163K | $0.25 / $1.00 | $0.21 / $0.84 | 16% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-v3.1) | deepseek | 128K | $0.27 / $1.00 | $0.0567 / $0.21 | 79% |
| [DeepSeek V3.1 Terminus](https://martllm.com/models/deepseek/deepseek-v3.1-terminus) | deepseek | 163K | $0.27 / $1.00 | $0.2268 / $0.84 | 16% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-chat-v3.1) | deepseek | 163K | $0.25 / $0.95 | $0.21 / $0.798 | 16% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | deepseek | 1048K | $0.2695 / $0.8085 | $0.2632 / $0.7895 | 2.3–2.4% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | deepseek | 1048K | $0.21 / $0.78 | $0.0463 / $0.172 | 78% |
| [DeepSeek V4 Flash 0731 Fast](https://martllm.com/models/deepseek/deepseek-v4-flash-0731-fast) | deepseek | 1000K | $0.35 / $0.70 | $0.3014 / $0.6027 | 13.9% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | deepseek | 1048K | $0.15 / $0.666 | $0.0189 / $0.08392 | 87.4% |
| [DeepSeek V3.2 Exp](https://martllm.com/models/deepseek/deepseek-v3.2-exp) | deepseek | 163K | $0.27 / $0.41 | $0.2268 / $0.3444 | 16% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | deepseek | 160K | $0.26 / $0.38 | $0.06305 / $0.09215 | 75.8% |
| [DeepSeek V4 Flash E2EE](https://martllm.com/models/deepseek/e2ee-deepseek-v4-flash) | deepseek | 1000K | $0.182 / $0.373 | $0.1433 / $0.2937 | 21.2% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | deepseek | 1000K | $0.1325 / $0.275 | $0.08208 / $0.1704 | 38% |
| [DeepSeek V4 Flash 0731](https://martllm.com/models/deepseek/deepseek-v4-flash-0731) | deepseek | 1048K | $0.13 / $0.26 | $0.07098 / $0.142 | 45.4% |
| [Grok 4.5](https://martllm.com/models/x-ai/grok-4.5) | x-ai | 500K | $2.27 / $6.80 | $1.60 / $4.78 | 29.6% |
| [Grok 4.6](https://martllm.com/models/x-ai/grok-4.6) | x-ai | 500K | $2.27 / $6.80 | $2.12 / $6.35 | 6.6% |
| [Grok 4.7](https://martllm.com/models/x-ai/grok-4.7) | x-ai | 500K | $2.00 / $6.00 | $1.49 / $4.47 | 25.4–25.5% |
| [Grok 4.20 Beta](https://martllm.com/models/x-ai/grok-4.20-beta) | x-ai | 2000K | $1.42 / $2.83 | $0.7008 / $1.40 | 50.6% |
| [Grok 4.20 Multi-Agent Beta](https://martllm.com/models/x-ai/grok-4.20-multi-agent-beta) | x-ai | 2000K | $1.42 / $2.83 | $1.15 / $2.29 | 19.1% |
| [Grok 4.3](https://martllm.com/models/x-ai/grok-4.3) | x-ai | 1000K | $1.42 / $2.83 | $0.4622 / $0.9212 | 67.5% |
| [Grok 4.20](https://martllm.com/models/x-ai/grok-4.20) | x-ai | 2000K | $1.25 / $2.50 | $1.05 / $2.10 | 16% |
| [Grok 4.20 Multi-Agent](https://martllm.com/models/x-ai/grok-4.20-multi-agent) | x-ai | 2000K | $1.25 / $2.50 | $1.05 / $2.10 | 16% |
| [Grok Build 0.1](https://martllm.com/models/x-ai/grok-build-0.1) | x-ai | 256K | $1.00 / $2.00 | $1.05 / $2.10 | -5% |
| [Qwen: Qwen3.8 Max Prime](https://martllm.com/models/qwen/qwen3.8-max-prime) | qwen | 1000K | $4.00 / $12.00 | $3.95 / $11.84 | 1.3% |
| [Qwen3.7 Max](https://martllm.com/models/qwen/qwen3.7-max) | qwen | 256K | $2.70 / $8.05 | $2.32 / $6.93 | 13.9% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | qwen | 1000K | $2.00 / $6.00 | $1.78 / $5.36 | 10.7–10.8% |
| [Qwen3.8 2.4T A95B](https://martllm.com/models/qwen/qwen3.8-2.4t-a95b) | qwen | 1000K | $2.00 / $6.00 | $1.26 / $3.78 | 37% |
| [Qwen: Qwen3.8 Max (0902)](https://martllm.com/models/qwen/qwen3.8-max-0902) | qwen | 1000K | $2.00 / $6.00 | $0.42 / $1.26 | 79% |
| [Qwen 4 Max](https://martllm.com/models/qwen/qwen4-max) | qwen | 1000K | $1.43 / $4.28 | $0.6434 / $1.93 | 54.8% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | qwen | 128K | $0.50 / $3.60 | $0.2572 / $1.85 | 48.6% |
| [Qwen 3 235B A22B Thinking 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-thinking-2507) | qwen | 128K | $0.45 / $3.50 | $0.1323 / $1.03 | 70.6% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | qwen | 256K | $0.32 / $3.20 | $0.0336 / $0.336 | 89.5% |
| [Qwen3.5-27B](https://martllm.com/models/qwen/qwen3.5-27b) | qwen | 262K | $0.26 / $2.60 | $0.2184 / $2.18 | 16% |
| [Qwen3.5-122B-A10B](https://martllm.com/models/qwen/qwen3.5-122b-a10b) | qwen | 262K | $0.26 / $2.08 | $0.2184 / $1.75 | 16% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | qwen | 262K | $0.20 / $2.00 | $0.021 / $0.21 | 89.5% |
| [Qwen 3.7 Plus](https://martllm.com/models/qwen/qwen3.7-plus) | qwen | 256K | $0.50 / $2.00 | $0.4515 / $1.81 | 9.7% |
| [Qwen 3.6 Plus](https://martllm.com/models/qwen/qwen3.6-plus) | qwen | 1000K | $0.325 / $1.95 | $0.2161 / $1.30 | 33.5% |
| [Qwen3 VL 235B A22B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-instruct) | qwen | 256K | $0.21 / $1.90 | $0.05072 / $0.4588 | 75.8% |
| [Qwen3 VL 235B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-thinking) | qwen | 256K | $0.21 / $1.90 | $0.1698 / $1.54 | 19.1% |
| [Qwen3.5 Plus 2026-04-20](https://martllm.com/models/qwen/qwen3.5-plus-20260420) | qwen | 1000K | $0.30 / $1.80 | $0.252 / $1.51 | 16% |
| [Qwen3.5 Plus 2026-02-15](https://martllm.com/models/qwen/qwen3.5-plus-02-15) | qwen | 1000K | $0.26 / $1.56 | $0.2184 / $1.31 | 16% |
| [Qwen 3 Coder 480B Turbo](https://martllm.com/models/qwen/qwen3-coder-turbo) | qwen | 256K | $0.35 / $1.50 | $0.3087 / $1.32 | 11.8% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | qwen | 256K | $0.325 / $1.25 | $0.06143 / $0.2362 | 81.1% |
| [Qwen 3.6 35B A3B (E2EE)](https://martllm.com/models/qwen/e2ee-qwen3-6-35b-a3b) | qwen | 128K | $0.182 / $1.18 | $0.151 / $0.9788 | 17% |
| [Qwen3.6 Flash](https://martllm.com/models/qwen/qwen3.6-flash) | qwen | 1000K | $0.1875 / $1.12 | $0.1296 / $0.7775 | 30.9% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | qwen | 256K | $0.095 / $1.10 | $0.01795 / $0.2079 | 81.1% |
| [Qwen2.5 Coder 32B Instruct](https://martllm.com/models/qwen/qwen-2.5-coder-32b-instruct) | qwen | 32K | $0.66 / $1.00 | $0.5544 / $0.84 | 16% |
| [Qwen 3.6 35B A3B](https://martllm.com/models/qwen/qwen3-6-35b-a3b) | qwen | 262K | $0.10 / $1.00 | $0.0777 / $0.777 | 22.3% |
| [Qwen 3.5 35B A3B](https://martllm.com/models/qwen/qwen3.5-35b-a3b) | qwen | 256K | $0.15 / $1.00 | $0.1244 / $0.8295 | 17% |
| [Qwen3 Coder Flash](https://martllm.com/models/qwen/qwen3-coder-flash) | qwen | 1000K | $0.195 / $0.975 | $0.1638 / $0.819 | 16% |
| [Qwen3 VL 30B A3B](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-thinking) | qwen | 128K | $0.25 / $0.90 | $0.2205 / $0.7938 | 11.8% |
| [Qwen3 Coder Next](https://martllm.com/models/qwen/qwen3-coder-next) | qwen | 256K | $0.12 / $0.80 | $0.02268 / $0.1512 | 81.1% |
| [Qwen-Plus](https://martllm.com/models/qwen/qwen-plus) | qwen | 1000K | $0.26 / $0.78 | $0.2184 / $0.6552 | 16% |
| [Qwen 3 235B A22B Instruct 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-2507) | qwen | 128K | $0.135 / $0.75 | $0.1006 / $0.5591 | 25.4–25.5% |
| [Qwen3 VL 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-instruct) | qwen | 262K | $0.15 / $0.60 | $0.126 / $0.504 | 16% |
| [Qwen3 30B A3B](https://martllm.com/models/qwen/qwen3-30b-a3b) | qwen | 256K | $0.12 / $0.50 | $0.09324 / $0.3885 | 22.3% |
| [Qwen3.8 Flash](https://martllm.com/models/qwen/qwen3.8-flash) | qwen | 1000K | $0.15 / $0.47 | $0.03623 / $0.1135 | 75.8% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | qwen | 1000K | $0.15 / $0.47 | $0.01575 / $0.04935 | 89.5% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | qwen | 256K | $0.11 / $0.44 | $0.0127 / $0.05082 | 88.5% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | qwen | 32K | $0.12 / $0.40 | $0.02142 / $0.0714 | 82.2% |
| [Qwen3 30B A3B Instruct 2507](https://martllm.com/models/qwen/qwen3-30b-a3b-instruct-2507) | qwen | 262K | $0.10 / $0.30 | $0.084 / $0.252 | 16% |
| [Qwen3.5-Flash](https://martllm.com/models/qwen/qwen3.5-flash-02-23) | qwen | 1000K | $0.065 / $0.26 | $0.0546 / $0.2184 | 16% |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | qwen | 256K | $0.10 / $0.25 | $0.0735 / $0.1103 | 26.5–55.9% |
| [Qwen 2.5 7B](https://martllm.com/models/qwen/e2ee-qwen-2-5-7b-p) | qwen | 32K | $0.05 / $0.13 | $0.04095 / $0.1065 | 18.1% |
| [Qwen: Qwen3.7 Flash](https://martllm.com/models/qwen/qwen3.7-flash) | qwen | 1000K | $0.03 / $0.13 | $0.02489 / $0.1078 | 17% |
| [Kimi K3 Fast](https://martllm.com/models/moonshotai/kimi-k3-fast-api) | moonshotai | 1000K | $4.50 / $22.50 | $3.78 / $18.90 | 16% |
| [Kimi K3](https://martllm.com/models/moonshotai/kimi-k3) | moonshotai | 1000K | $3.00 / $15.00 | $0.3071 / $1.57 | 89.5–89.8% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | moonshotai | 1048K | $2.00 / $10.00 | $1.03 / $5.14 | 48.6% |
| [Kimi K2.7 Code](https://martllm.com/models/moonshotai/kimi-k2.7-code) | moonshotai | 262K | $0.75 / $3.50 | $0.1496 / $0.6983 | 80% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | moonshotai | 256K | $0.70 / $3.41 | $0.1543 / $0.7519 | 78% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | moonshotai | 256K | $0.55 / $2.75 | $0.1155 / $0.5775 | 79% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | moonshotai | 256K | $0.60 / $2.50 | $0.1197 / $0.4988 | 80% |
| [Kimi K2](https://martllm.com/models/moonshotai/kimi-k2) | moonshotai | 256K | $0.57 / $2.30 | $0.5985 / $2.42 | -5% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | z-ai | 524K | $1.75 / $5.75 | $1.47 / $4.83 | 16% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | z-ai | 1000K | $1.68 / $5.28 | $0.194 / $0.6098 | 88.4–88.5% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | z-ai | 1048K | $1.40 / $4.40 | $0.147 / $0.462 | 89.5% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | z-ai | 1000K | $1.40 / $4.40 | $0.08747 / $0.3222 | 92.7–93.8% |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | z-ai | 1000K | $1.19 / $4.38 | $0.2499 / $0.9207 | 79% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | z-ai | 200K | $1.33 / $4.18 | $0.5775 / $2.18 | 47.9–56.6% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | z-ai | 200K | $1.33 / $4.18 | $0.7122 / $2.24 | 46.5% |
| [GLM-5 Turbo](https://martllm.com/models/z-ai/glm-5-turbo) | z-ai | 200K | $1.20 / $4.00 | $0.9828 / $3.28 | 18.1% |
| [GLM 5V Turbo](https://martllm.com/models/z-ai/glm-5v-turbo) | z-ai | 200K | $1.20 / $4.00 | $1.17 / $3.91 | 2.3% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | z-ai | 198K | $0.925 / $2.71 | $0.5245 / $1.54 | 43.3% |
| [GLM 4.5](https://martllm.com/models/z-ai/glm-4.5) | z-ai | 128K | $0.60 / $2.20 | $0.5922 / $2.17 | 1.3% |
| [GLM 4.5V](https://martllm.com/models/z-ai/glm-4.5v) | z-ai | 66K | $0.60 / $1.80 | $0.504 / $1.51 | 16% |
| [GLM-4.6](https://martllm.com/models/z-ai/glm-4.6) | z-ai | 198K | $0.43 / $1.75 | $0.2122 / $0.8636 | 50.6% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | z-ai | 128K | $0.40 / $1.75 | $0.2184 / $0.9555 | 45.4% |
| [Z.ai: GLM 5.3 FlashX](https://martllm.com/models/z-ai/glm-5.3-flashx) | z-ai | 1048K | $0.37 / $1.25 | $0.2797 / $0.945 | 24.4% |
| [Z.ai: GLM 5.3 FlashX Legal](https://martllm.com/models/z-ai/glm-5.3-flashx-legal) | z-ai | 1048K | $0.37 / $1.25 | $0.2603 / $0.8794 | 29.6% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | z-ai | 128K | $0.17 / $0.98 | $0.1285 / $0.7409 | 24.4% |
| [GLM 4.6V](https://martllm.com/models/z-ai/glm-4.6v) | z-ai | 131K | $0.30 / $0.90 | $0.252 / $0.756 | 16% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | z-ai | 1048K | $0.13 / $0.50 | $0.02593 / $0.09975 | 80% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | z-ai | 198K | $0.0605 / $0.40 | $0.01144 / $0.0756 | 81.1% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | mistralai | 128K | $2.00 / $6.00 | $0.189 / $0.567 | 90.5% |
| [Mistral Large 2407](https://martllm.com/models/mistralai/mistral-large-2407) | mistralai | 131K | $2.00 / $6.00 | $1.68 / $5.04 | 16% |
| [Mixtral 8x22B Instruct](https://martllm.com/models/mistralai/mixtral-8x22b-instruct) | mistralai | 65K | $2.00 / $6.00 | $1.68 / $5.04 | 16% |
| [Mistral: Pixtral Large 2502](https://martllm.com/models/mistralai/pixtral-large-2502) | mistralai | 128K | $2.00 / $6.00 | $1.95 / $5.86 | 2.3% |
| [Mistral: Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4-0) | mistralai | 524K | $0.735 / $2.21 | $0.301 / $0.9029 | 59% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | mistralai | 256K | $0.40 / $2.00 | $0.0504 / $0.252 | 87.4% |
| [Devstral 2 2512](https://martllm.com/models/mistralai/devstral-2512) | mistralai | 262K | $0.40 / $2.00 | $0.336 / $1.68 | 16% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | mistralai | 256K | $0.525 / $1.57 | $0.1158 / $0.3473 | 77.9% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | mistralai | 128K | $0.50 / $1.50 | $0.063 / $0.189 | 87.4% |
| [Codestral 2508](https://martllm.com/models/mistralai/codestral-2508) | mistralai | 256K | $0.30 / $0.90 | $0.252 / $0.756 | 16% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-4) | mistralai | 256K | $0.165 / $0.66 | $0.1732 / $0.693 | -5% |
| [Saba](https://martllm.com/models/mistralai/mistral-saba) | mistralai | 32K | $0.20 / $0.60 | $0.168 / $0.504 | 16% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-2603) | mistralai | 262K | $0.15 / $0.60 | $0.126 / $0.504 | 16% |
| [Mistral Small 3.1 24B](https://martllm.com/models/mistralai/mistral-small-3.1-24b-instruct) | mistralai | 128K | $0.351 / $0.555 | $0.2948 / $0.4662 | 16% |
| [Voxtral Small 24B 2507](https://martllm.com/models/mistralai/voxtral-small-24b-2507) | mistralai | 32K | $0.105 / $0.315 | $0.05402 / $0.1621 | 48.5% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | mistralai | 128K | $0.21 / $0.21 | $0.0441 / $0.0441 | 79% |
| [Ministral 14B](https://martllm.com/models/mistralai/ministral-14b) | mistralai | 262K | $0.20 / $0.20 | $0.184 / $0.184 | 8% |
| [Ministral 3 14B 2512](https://martllm.com/models/mistralai/ministral-14b-2512) | mistralai | 262K | $0.20 / $0.20 | $0.168 / $0.168 | 16% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | mistralai | 256K | $0.075 / $0.20 | $0.06143 / $0.1638 | 18.1% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | mistralai | 128K | $0.1575 / $0.1575 | $0.03308 / $0.03308 | 79% |
| [Ministral 8B](https://martllm.com/models/mistralai/ministral-8b) | mistralai | 262K | $0.15 / $0.15 | $0.138 / $0.138 | 8% |
| [Ministral 3 8B 2512](https://martllm.com/models/mistralai/ministral-8b-2512) | mistralai | 262K | $0.15 / $0.15 | $0.126 / $0.126 | 16% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | mistralai | 128K | $0.105 / $0.105 | $0.02205 / $0.02205 | 79% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3b) | mistralai | 131K | $0.10 / $0.10 | $0.092 / $0.092 | 8% |
| [Ministral 3 3B 2512](https://martllm.com/models/mistralai/ministral-3b-2512) | mistralai | 131K | $0.10 / $0.10 | $0.084 / $0.084 | 16% |
| [Mistral Small 3](https://martllm.com/models/mistralai/mistral-small-24b-instruct-2501) | mistralai | 32K | $0.05 / $0.08 | $0.042 / $0.0672 | 16% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | mistralai | 32K | $0.04 / $0.04 | $0.00882 / $0.00882 | 78% |
| [Mistral Nemo 12B](https://martllm.com/models/mistralai/mistral-nemo) | mistralai | 131K | $0.029 / $0.03 | $0.02436 / $0.0252 | 16% |
| [Meta: Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder) | meta-llama | 1048K | $4.00 / $20.00 | $2.14 / $10.71 | 46.4–46.5% |
| [Meta: Muse Spark 1.1](https://martllm.com/models/meta-llama/muse-spark-1.1) | meta-llama | 1048K | $1.25 / $4.25 | $0.6038 / $2.05 | 51.7% |
| [Meta: Muse Spark 1.2](https://martllm.com/models/meta-llama/muse-spark-1.2) | meta-llama | 1048K | $1.25 / $4.25 | $0.63 / $2.14 | 49.6% |
| [Meta: Muse Spark 1.3](https://martllm.com/models/meta-llama/muse-spark-1.3) | meta-llama | 1048K | $1.25 / $4.25 | $1.06 / $3.61 | 14.9% |
| [Meta: Muse Spark Open](https://martllm.com/models/meta-llama/muse-spark-open) | meta-llama | 1048K | $1.25 / $4.25 | $1.21 / $4.11 | 3.4% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | meta-llama | 131K | $0.325 / $1.35 | $0.3242 / $1.35 | 0.2–0.3% |
| [Llama 4 Maverick](https://martllm.com/models/meta-llama/llama-4-maverick) | meta-llama | 1048K | $0.35 / $1.00 | $0.294 / $0.84 | 16% |
| [Llama 3.1 70B Instruct](https://martllm.com/models/meta-llama/llama-3.1-70b) | meta-llama | 128K | $0.72 / $0.72 | $0.6624 / $0.6624 | 8% |
| [Llama 3.1 70B Instruct](https://martllm.com/models/meta-llama/llama-3.1-70b-instruct) | meta-llama | 131K | $0.72 / $0.72 | $0.6048 / $0.6048 | 16% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b) | meta-llama | 128K | $0.71 / $0.71 | $0.6624 / $0.6624 | 6.7% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | meta-llama | 128K | $0.293 / $0.71 | $0.243 / $0.5889 | 17% |
| [Meta: Muse Ember](https://martllm.com/models/meta-llama/muse-ember) | meta-llama | 1048K | $0.10 / $0.50 | $0.09765 / $0.4883 | 2.3–2.4% |
| [Llama 3.2 3B](https://martllm.com/models/meta-llama/llama-3.2-3b-instruct) | meta-llama | 128K | $0.05 / $0.33 | $0.04462 / $0.2945 | 10.8% |
| [Llama 4 Scout](https://martllm.com/models/meta-llama/llama-4-scout) | meta-llama | 327K | $0.10 / $0.30 | $0.084 / $0.252 | 16% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.105 / $0.21 | -5% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.0672 / $0.1344 | 32.8% |
| [Llama 3.1 8B Instruct](https://martllm.com/models/meta-llama/llama-3.1-8b-instruct) | meta-llama | 131K | $0.05 / $0.08 | $0.042 / $0.0672 | 16% |

</details>

### Image models (per image)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [FLUX.1 [schnell]](https://martllm.com/models/fal-ai/flux/schnell) | – | $0.003 / image | – |
| [Image 01 Image To Image](https://martllm.com/models/minimax/image-01-image-to-image) | – | $0.0035 / image | – |
| [Z-Image Turbo (Venice)](https://martllm.com/models/venice/z-image-turbo) | $0.01 / image | $0.0042 / image | 58% |
| [Photon Flash](https://martllm.com/models/luma/photon-flash) | – | $0.005 / image | – |
| [GPT Image 2.6](https://martllm.com/models/openai/gpt-image-2-6) | – | $0.0055 / image | – |
| [GPT Image 2.5 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-flare) | $0.07 / image | $0.0055 / image | 92.1% |
| [GPT Image 2.5 Sunburst (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-sunburst) | $0.07 / image | $0.0055 / image | 92.1% |
| [GPT Image 2 (Venice)](https://martllm.com/models/venice/gpt-image-2) | $0.27 / image | $0.0055 / image | 98% |
| [GPT Image 2 — Edit (Venice)](https://martllm.com/models/venice/gpt-image-2-edit) | $0.36 / image | $0.0055 / image | 98.5% |
| [Grok Imagine (Venice)](https://martllm.com/models/venice/grok-imagine) | $0.03 / image | $0.0055 / image | 81.7% |

### Image models (per megapixel)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [FLUX.2 Klein 4B](https://martllm.com/models/black-forest-labs/flux.2-klein-4b) | – | $0.01562 / megapixel | – |
| [FLUX.2 Flex](https://martllm.com/models/black-forest-labs/flux.2-flex) | – | $0.0625 / megapixel | – |

### Video models (per second)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Seedance 2.5 Edit](https://martllm.com/models/bytedance/seedance-2-5-edit-video-basic) | $0 / sec | $0 / sec | – |
| [Seedance 2.5 Flash Edit](https://martllm.com/models/bytedance/seedance-2-5-flash-edit-video-basic) | $0 / sec | $0 / sec | – |
| [Gemini Omni Flash 1.1 Edit](https://martllm.com/models/google/gemini-omni-flash-1-1-video-to-video) | $0 / sec | $0 / sec | – |
| [HappyHorse 1.0 Edit](https://martllm.com/models/happyhorse/happyhorse-1-0-video-to-video) | $0 / sec | $0 / sec | – |
| [Kling 4.0 Flash Edit](https://martllm.com/models/kling/kling-v4-flash-video-to-video) | $0 / sec | $0 / sec | – |
| [Kling 4.0 Edit](https://martllm.com/models/kling/kling-v4-video-to-video) | $0 / sec | $0 / sec | – |
| [Wan 2.7 Edit](https://martllm.com/models/wan/wan-2-7-video-to-video) | $0 / sec | $0 / sec | – |
| [Muse Video](https://martllm.com/models/meta-llama/muse-video) | – | $0.002352 / sec | – |
| [Seedance 1.0 Pro Fast](https://martllm.com/models/bytedance/seedance-1-0-pro-fast-image-to-video) | $0.018 / sec | $0.01142 / sec | 36.5% |
| [Grok Imagine Video 1.5](https://martllm.com/models/x-ai/grok-imagine-1-5-image-to-video) | $0.08 / sec | $0.0126 / sec | 84.2% |

### Video models (per video)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Cosmos Predict (image-to-video)](https://martllm.com/models/nvidia/cosmos-predict-image-to-video) | $0.801 / video | $0.7626 / video | 4.8% |

### Music models

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [MMAudio V2 Text-to-Audio (Venice)](https://martllm.com/models/venice/mmaudio-v2-text-to-audio) | $0.00092 / sec | $0.0008245 / sec | 10.4% |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-sound-effects-v1-0) | $0.00207 / sec | $0.001855 / sec | 10.4% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | $0.0023 / sec | $0.002061 / sec | 10.4% |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-v1-1-sound-effects) | – | $0.00207 / sec | – |
| [Seed Audio 1.0](https://martllm.com/models/byteplus/seed-audio-1-0) | $0.002875 / sec | $0.002576 / sec | 10.4% |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | – | $0.003187 / sec | – |
| [ACE-Step 1.5 (Venice)](https://martllm.com/models/venice/ace-step-15) | – | $0.03024 / track | – |
| [Venice Music Gen (legacy alias)](https://martllm.com/models/venice/music-gen) | – | $0.03024 / track | – |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | $0.04 / track | $0.0336 / track | 16% |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | $0.046 / 1K chars | $0.03864 / 1K chars | 16% |

### Speech models

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Kokoro Text to Speech (Venice)](https://martllm.com/models/venice/kokoro-tts) | $0.0035 / 1K chars | $0.003136 / 1K chars | 10.4% |
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | – | $0.003175 / 1K chars | – |
| [Inworld 1.5 Max TTS](https://martllm.com/models/inworld/tts-inworld-1-5-max) | – | $0.014 / 1K chars | – |
| [xAI v1 TTS](https://martllm.com/models/x-ai/tts-xai-v1) | $0.01875 / 1K chars | $0.01764 / 1K chars | 5.9% |
| [Eleven Flash v2](https://martllm.com/models/elevenlabs/eleven-flash-v2) | – | $0.04 / 1K chars | – |
| [Eleven Flash v2.5](https://martllm.com/models/elevenlabs/eleven-flash-v2-5) | – | $0.04 / 1K chars | – |
| [Eleven Turbo v2](https://martllm.com/models/elevenlabs/eleven-turbo-v2) | – | $0.04 / 1K chars | – |
| [Eleven v3 Conversational](https://martllm.com/models/elevenlabs/eleven-v3-conversational) | – | $0.04 / 1K chars | – |
| [Chatterbox HD TTS](https://martllm.com/models/resemble-ai/tts-chatterbox-hd) | $0.05 / 1K chars | $0.0448 / 1K chars | 10.4% |
| [Gradium TTS](https://martllm.com/models/gradium/tts-gradium-v1) | – | $0.0475 / 1K chars | – |

## Prices under review

The catalog's official price for these 7 models failed a sanity check (see `list_price_review_reason`), so it is left out, with no % below list, until it is checked against the maker's own page. The MartLLM price is still listed.

| Model | Category | Why |
|---|---|---|
| [Gemma 2 27B](https://martllm.com/models/google/gemma-2-27b-it) | text | output:input ratio 1.0 vs 5.0 for the maker's other models |
| [Mistral Large 3 2512](https://martllm.com/models/mistralai/mistral-large-2512) | text | input list price more than 3x off other listings of the same model |
| [Nemotron 3.5 Content Safety](https://martllm.com/models/nvidia/nemotron-3.5-content-safety) | text | output:input ratio 1.0 vs 3.6 for the maker's other models |
| [GPT-3.5 Turbo 16k](https://martllm.com/models/openai/gpt-3.5-turbo-16k) | text | output:input ratio 1.3 vs 5.0 for the maker's other models |
| [Sonar](https://martllm.com/models/perplexity/sonar) | text | output:input ratio 1.0 vs 4.0 for the maker's other models |
| [Qwen2.5 VL 72B Instruct](https://martllm.com/models/qwen/qwen2.5-vl-72b-instruct) | text | output:input ratio 1.2 vs 4.2 for the maker's other models |
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | speech | more than 10x off the median speech price per 1K characters |

## Biggest drops this week (2026-11-19 to 2026-11-26)

From MartLLM's daily catalog snapshots (`GET /api/v1/public/price-changes`). Text: $ per 1M input / output tokens, sorted by the larger of the two moves.

### Official list price cuts

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Wan 2.2 A14B Text-to-Video](https://martllm.com/models/wan/wan-2-2-a14b-text-to-video) | video | $0.20 / sec | $0.04 / sec | −80% |
| [Topaz Video Upscale](https://martllm.com/models/topaz-labs/topaz-video-upscale) | video | $0.15 / sec | $0.042 / sec | −72% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | text | $0.70 / $0.71 | $0.293 / $0.71 | in −58% / out 0% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.30 / $1.20 | $0.15 / $0.666 | in −50% / out −44% |
| [Runway Gen-4 Aleph](https://martllm.com/models/runway/runway-gen4-aleph) | video | $0.50 / sec | $0.25 / sec | −50% |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | text | $0.17 / $0.25 | $0.10 / $0.25 | in −41% / out 0% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.44 / $1.32 | $0.2695 / $0.8085 | −39% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.30 / $1.20 | $0.21 / $0.78 | in −30% / out −35% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $1.32 / $3.96 | $1.36 / $2.72 | in +3% / out −31% |
| [NVIDIA Nemotron 3 Ultra 550B](https://martllm.com/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.625 / $3.12 | $0.50 / $2.20 | in −20% / out −30% |

### MartLLM price drops

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MiniMax M2.1](https://martllm.com/models/minimax/minimax-m2.1) | text | $0.3307 / $1.32 | $0.002741 / $0.008978 | −99% |
| [GPT Image 2 — Edit (Venice)](https://martllm.com/models/venice/gpt-image-2-edit) | image | $0.378 / image | $0.0055 / image | −99% |
| [GPT Image 2 (Venice)](https://martllm.com/models/venice/gpt-image-2) | image | $0.2807 / image | $0.0055 / image | −98% |
| [GPT Image 2.5 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-flare) | image | $0.06542 / image | $0.0055 / image | −92% |
| [GPT Image 2.6 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare) | image | $0.0945 / image | $0.008568 / image | −91% |
| [GPT Image 2.5 Sunburst (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-sunburst) | image | $0.06027 / image | $0.0055 / image | −91% |
| [LTX 2 19B Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-19b-full-text-to-video) | video | $0.0924 / sec | $0.01523 / sec | −84% |
| [Nano Banana 2 (image-to-image)](https://martllm.com/models/google/nano-banana-2-edit) | image | $0.0945 / image | $0.0165 / image | −83% |
| [Nano Banana 2.1 (Venice)](https://martllm.com/models/google/venice-nano-banana-2-1) | image | $0.0945 / image | $0.0165 / image | −83% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | text | $1.09 / $5.43 | $0.2047 / $1.02 | −81% |

Every change, day by day: [`CHANGELOG.md`](CHANGELOG.md).

## Use the data

Plain HTTPS, no key. Raw file URLs:

- JSON: `https://raw.githubusercontent.com/al-global-tech/llm-api-prices/main/prices.json`
- CSV: `https://raw.githubusercontent.com/al-global-tech/llm-api-prices/main/prices.csv`
- A past day: `https://raw.githubusercontent.com/al-global-tech/llm-api-prices/main/history/YYYY-MM-DD.csv`

Python (stdlib):

```python
import json, urllib.request
URL = "https://raw.githubusercontent.com/al-global-tech/llm-api-prices/main/prices.json"
data = json.load(urllib.request.urlopen(URL))
chat = [m for m in data["models"] if m["category"] == "text" and m["available"]
        and m["list_output_usd_per_mtok"] and "tools" in m["capabilities"]]
for m in sorted(chat, key=lambda m: m["list_output_usd_per_mtok"])[:10]:
    print(m["id"], m["list_input_usd_per_mtok"], m["list_output_usd_per_mtok"], m["list_price_source"])
```

JavaScript:

```js
const res = await fetch("https://raw.githubusercontent.com/al-global-tech/llm-api-prices/main/prices.json");
const { updated_at, models } = await res.json();
const video = models.filter(m => m.category === "video" && m.unit === "second");
console.log(updated_at, video.sort((a, b) => a.uberllm_usd_per_unit - b.uberllm_usd_per_unit).slice(0, 5));
```

jq: `jq '.models[] | select(.maker=="anthropic") | {id, list_input_usd_per_mtok, list_output_usd_per_mtok}' prices.json`

### Fields

| Field | Meaning |
|---|---|
| `id` | Model id, as used in the `model` field of an OpenAI-compatible request to MartLLM |
| `category` | text, image, video, music, speech, transcription, embedding or other (from the output modality) |
| `unit` | `1M tokens` for token-priced models; otherwise what one unit price buys: `image`, `megapixel`, `second`, `job` (one video or track), `minute`, `1K characters` |
| `list_input_usd_per_mtok`, `list_output_usd_per_mtok` | Official list price, USD per 1M tokens |
| `uberllm_input_usd_per_mtok`, `uberllm_output_usd_per_mtok` | MartLLM price a buyer can count on at snapshot time, USD per 1M tokens: per side, the higher of the best live seller and the listed price |
| `list_usd_per_unit`, `uberllm_usd_per_unit` | The same for per-unit (media) prices |
| `pct_below_list_*` | 100 × (1 − MartLLM / list), one decimal; negative = above list; empty = no list price |
| `list_price_source`, `list_price_source_url`, `list_price_checked` | Where the official price comes from (see Sources) |
| `list_price_hosts` | JSON only: the published per-token prices of named hosts (Together AI, Fireworks, Bedrock, ...) for the model |
| `video_rates` | JSON only: every per-second video price by resolution and sound, official and MartLLM |
| `vendor_pricing_page` | The maker's own pricing page, to check a list price against |
| `capabilities` | tools, reasoning, vision, structured_outputs; video: text-to-video, image-to-video, sound |
| `available` | A request can be served right now |
| `nsfw` | Made for adult or unfiltered content (text only; adult image/video/sound models are not listed) |

## Sources

Every number comes from MartLLM's public catalog, read once a day by [`update.py`](update.py):

- `GET https://api.martllm.com/api/v1/public/models`: model list, context length, capabilities, official list prices, MartLLM prices.
- `GET https://api.martllm.com/api/v1/public/market/live`: the live market board (refreshed every 30 s). The text price published here is, per side, the higher of its best seller and the catalog's listed price, as on martllm.com's comparison pages.
- `GET https://api.martllm.com/v1/models`: the OpenAI-compatible model list (reasoning flag).
- `GET https://api.martllm.com/api/v1/public/price-changes`: the weekly diff used for "Biggest drops this week" and the first CHANGELOG entry.

Official list price, per row:

- `list_price_source` starting "MartLLM catalog list price": the direct (list) price the catalog carries for the model, meant to be the maker's own API price for first-party models (OpenAI, Anthropic, Google, ...) and the host's list price for open-weight models. The public catalog does not record which vendor page that number was read from, so `list_price_source_url` is empty and the source says so. `vendor_pricing_page` is the maker's pricing page to check it against (it is not where the number was read); for open-weight models, `list_price_hosts` has the named hosts' own prices.
- Any other `list_price_source` (for example `OpenRouter`, `Z.ai`, `Fal`, `Kling (Kuaishou)`, `Stability AI`): the catalog had no list of its own, so the price was read from that public page (`list_price_source_url`) on `list_price_checked`.
- `list_price_status`: `ok` = the official price passed the sanity check; `unverified` = it failed it (input under 1/40 of output, an output:input ratio more than 3x off the maker's other models, an input more than 3x off other listings of the same model, or a media price more than 10x off its category median), so the official price and every % below list are left empty until it is checked; `none` = no official price.
- No official price: the field is empty. A media model whose only known official price is not above what MartLLM charges gets no official price, so a saving is never claimed against a number we cannot show.

MartLLM price = the best offer a seller on the MartLLM market makes at snapshot time, fee included. Market prices move during the day; the snapshot is a point in time, and <https://martllm.com/models> always has the current one.

Found a wrong official price? Open an issue with the vendor page that shows the right one.

## How it updates

`update.py` (Python stdlib only) runs once a day. It fetches the catalog, refuses an answer that lost more than 40% of the models, diffs against the last snapshot, and commits `prices.json`, `prices.csv`, `README.md`, `CHANGELOG.md` and `history/<day>.csv` through the GitHub GraphQL API (`createCommitOnBranch`), so commits are signed by GitHub. Nothing is committed when nothing changed.

Run it yourself: `python3 update.py --out ./build` writes every file locally without touching GitHub.

To run it from GitHub Actions instead, save this as `.github/workflows/update.yml` (also in [`docs/update.yml`](docs/update.yml)):

```yaml
name: update prices
on:
  schedule:
    - cron: "17 3 * * *"
  workflow_dispatch:
permissions:
  contents: write
jobs:
  update:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-python@v5
        with:
          python-version: "3.12"
      - run: python3 update.py --commit
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

## License

- Data (`prices.json`, `prices.csv`, `history/`, `CHANGELOG.md`): [CC BY 4.0](LICENSE-DATA). Credit: "LLM API prices, al-global-tech/llm-api-prices (MartLLM)" with a link to this repo.
- Code (`update.py`): [MIT](LICENSE).
