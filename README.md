# LLM API prices

*MartLLM was called UberLLM until November 2026; the `uberllm_*` column names stay as they are.*

An open, daily-updated dataset of AI API prices: the official list price of 1083 text, image, video, music and speech models next to the lowest live price on the [MartLLM](https://martllm.com/models) market, how far below list that is, context length and capabilities.

**Updated:** 2026-11-27T03:17:07Z · **Models:** 468 text, 226 image, 342 video, 21 music, 17 speech, 9 transcription · **Files:** [`prices.json`](prices.json), [`prices.csv`](prices.csv), [`CHANGELOG.md`](CHANGELOG.md), [`history/`](history/)

Disclosure: this repo is maintained by the team that runs MartLLM. The MartLLM column is our own price; the official column is the maker's price, sourced as described in [Sources](#sources). Live prices: <https://martllm.com/models>.

## Cheapest right now

Lowest MartLLM price per category among models that can be called now. Text: $ per 1M input / output tokens. Full list: [`prices.csv`](prices.csv).

### Text (chat) models

| Model | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | 128K | $0.045 / $0.09 | $0.002363 / $0.004725 | 94.7–94.8% |
| [Palmyra Vision 7B](https://martllm.com/models/writer/palmyra-vision-7b) | 4K | $0.15 / $0.60 | $0.00315 / $0.0126 | 97.9% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | 32K | $0.04 / $0.04 | $0.0084 / $0.0084 | 79% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | 128K | $0.04 / $0.08 | $0.00588 / $0.01176 | 85.3% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | 128K | $0.105 / $0.105 | $0.01213 / $0.01213 | 88.4% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | 128K | $0.0725 / $0.25 | $0.00609 / $0.021 | 91.6% |
| [Solar Mini 4.5](https://martllm.com/models/upstage/solar-mini-4-5) | 524K | $0.01 / $0.04 | $0.005775 / $0.0231 | 42.2% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | 262K | $0.10 / $0.32 | $0.00735 / $0.02352 | 92.7% |
| [Mistral Nemo 12B](https://martllm.com/models/mistralai/mistral-nemo) | 131K | $0.029 / $0.03 | $0.01675 / $0.01733 | 42.2% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | 128K | $0.0625 / $0.1875 | $0.008531 / $0.02559 | 86.3–86.4% |
| [Ling 3.0 Tiny](https://martllm.com/models/inclusionai/ling-3.0-tiny) | 262K | $0.015 / $0.045 | $0.008663 / $0.02599 | 42.2% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | 128K | $0.03 / $0.15 | $0.005985 / $0.02993 | 80% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | 262K | $0.20 / $2.00 | $0.0042 / $0.042 | 97.9% |
| [Ling 3.0 Flash](https://martllm.com/models/inclusionai/ling-3.0-flash) | 256K | $0.021 / $0.063 | $0.01213 / $0.03638 | 42.2% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | 128K | $0.1575 / $0.1575 | $0.02481 / $0.02481 | 84.3% |

### Major model makers

<details><summary>OpenAI, Anthropic, Google, DeepSeek, xAI, Qwen, Moonshot, Z.ai, Mistral, Meta (244 models)</summary>

| Model | Maker | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|---|
| [GPT-5.4 Pro](https://martllm.com/models/openai/gpt-5.4-pro) | openai | 1000K | $30.00 / $180.00 | $15.44 / $92.61 | 48.5–48.6% |
| [GPT-5.5 Pro](https://martllm.com/models/openai/gpt-5.5-pro) | openai | 1000K | $30.00 / $180.00 | $17.64 / $105.84 | 41.2% |
| [GPT 5.2](https://martllm.com/models/openai/gpt-5.2-pro) | openai | 400K | $21.00 / $168.00 | $12.13 / $97.02 | 42.2% |
| [GPT-5 pro](https://martllm.com/models/openai/gpt-5-pro) | openai | 400K | $15.00 / $120.00 | $8.66 / $69.30 | 42.2% |
| [o3 Pro](https://martllm.com/models/openai/o3-pro) | openai | 200K | $20.00 / $80.00 | $11.55 / $46.20 | 42.2% |
| [GPT-4](https://martllm.com/models/openai/gpt-4) | openai | 8K | $30.00 / $60.00 | $17.32 / $34.65 | 42.2% |
| [GPT-6 Astra](https://martllm.com/models/openai/gpt-6-astra) | openai | 1050K | $10.00 / $50.00 | $6.30 / $31.50 | 37% |
| [GPT-6 Astra Pro](https://martllm.com/models/openai/gpt-6-astra-pro) | openai | 1050K | $10.00 / $50.00 | $5.78 / $28.88 | 42.2% |
| [GPT-6.2 Astra](https://martllm.com/models/openai/gpt-6.2-astra) | openai | 1050K | $8.00 / $40.00 | $5.21 / $26.04 | 34.9% |
| [GPT-6.2 Astra Pro](https://martllm.com/models/openai/gpt-6.2-astra-pro) | openai | 1050K | $8.00 / $40.00 | $7.98 / $39.90 | 0.2–0.3% |
| [GPT-5.5](https://martllm.com/models/openai/gpt-5.5) | openai | 1000K | $5.00 / $30.00 | $1.94 / $11.65 | 61.2% |
| [GPT Chat Latest](https://martllm.com/models/openai/gpt-chat-latest) | openai | 400K | $5.00 / $30.00 | $2.89 / $17.32 | 42.2% |
| [GPT-5.6 Sol](https://martllm.com/models/openai/gpt-5.6-sol) | openai | 1050K | $4.00 / $20.00 | $1.97 / $9.87 | 50.6–50.7% |
| [GPT-5.6 Sol Pro](https://martllm.com/models/openai/gpt-5.6-sol-pro) | openai | 1050K | $4.00 / $20.00 | $3.91 / $19.53 | 2.3% |
| [GPT-4o (2024-05-13)](https://martllm.com/models/openai/gpt-4o-2024-05-13) | openai | 128K | $5.00 / $15.00 | $2.89 / $8.66 | 42.2% |
| [GPT-5.4](https://martllm.com/models/openai/gpt-5.4) | openai | 1000K | $2.50 / $15.00 | $0.945 / $5.67 | 62.2% |
| [GPT-5.2](https://martllm.com/models/openai/gpt-5.2) | openai | 256K | $1.75 / $14.00 | $0.6431 / $5.14 | 63.3% |
| [GPT-5.2 Codex](https://martllm.com/models/openai/gpt-5.2-codex) | openai | 256K | $1.75 / $14.00 | $1.64 / $13.08 | 6.6% |
| [GPT-5.3 Codex](https://martllm.com/models/openai/gpt-5.3-codex) | openai | 400K | $1.75 / $14.00 | $0.9555 / $7.64 | 45.4% |
| [GPT-5.6 Terra](https://martllm.com/models/openai/gpt-5.6-terra) | openai | 1050K | $2.00 / $12.00 | $1.18 / $7.06 | 41.2% |
| [GPT-5.6 Terra Pro](https://martllm.com/models/openai/gpt-5.6-terra-pro) | openai | 1050K | $2.00 / $12.00 | $2.00 / $11.97 | 0.2% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | openai | 128K | $2.50 / $10.00 | $0.2362 / $0.945 | 90.5% |
| [GPT-4o (2024-08-06)](https://martllm.com/models/openai/gpt-4o-2024-08-06) | openai | 128K | $2.50 / $10.00 | $1.44 / $5.78 | 42.2% |
| [GPT-4o (2024-11-20)](https://martllm.com/models/openai/gpt-4o-2024-11-20) | openai | 128K | $2.50 / $10.00 | $1.44 / $5.78 | 42.2% |
| [GPT-5](https://martllm.com/models/openai/gpt-5) | openai | 400K | $1.25 / $10.00 | $0.7219 / $5.78 | 42.2% |
| [GPT-5.1](https://martllm.com/models/openai/gpt-5.1) | openai | 400K | $1.25 / $10.00 | $0.7219 / $5.78 | 42.2% |
| [GPT-5.1-Codex](https://martllm.com/models/openai/gpt-5.1-codex) | openai | 400K | $1.25 / $10.00 | $0.7219 / $5.78 | 42.2% |
| [GPT 5.1 Codex Max](https://martllm.com/models/openai/gpt-5.1-codex-max) | openai | 400K | $1.25 / $10.00 | $0.7219 / $5.78 | 42.2% |
| [GPT-6 Sol](https://martllm.com/models/openai/gpt-6-sol) | openai | 1050K | $2.00 / $10.00 | $1.22 / $6.09 | 39.1% |
| [GPT-6 Sol Pro](https://martllm.com/models/openai/gpt-6-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.97 / $9.87 | 1.3% |
| [GPT-6.1 Sol](https://martllm.com/models/openai/gpt-6.1-sol) | openai | 1050K | $2.00 / $10.00 | $1.03 / $5.14 | 48.6% |
| [OpenAI: GPT-6.1 Sol Pro](https://martllm.com/models/openai/gpt-6.1-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.97 / $9.87 | 1.3% |
| [GPT-6.2 Sol](https://martllm.com/models/openai/gpt-6.2-sol) | openai | 1050K | $2.00 / $10.00 | $1.09 / $5.46 | 45.4% |
| [GPT-6.2 Sol Pro](https://martllm.com/models/openai/gpt-6.2-sol-pro) | openai | 1050K | $2.00 / $10.00 | $2.02 / $10.08 | -0.8% |
| [GPT-4.1](https://martllm.com/models/openai/gpt-4.1) | openai | 1047K | $2.00 / $8.00 | $1.16 / $4.62 | 42.2% |
| [o3](https://martllm.com/models/openai/o3) | openai | 200K | $2.00 / $8.00 | $1.16 / $4.62 | 42.2% |
| [OpenAI: GPT-6.1 Terra](https://martllm.com/models/openai/gpt-6.1-terra) | openai | 1050K | $1.00 / $5.00 | $0.3675 / $1.84 | 63.3% |
| [OpenAI: GPT-6.1 Terra Pro](https://martllm.com/models/openai/gpt-6.1-terra-pro) | openai | 1050K | $1.00 / $5.00 | $0.987 / $4.93 | 1.3% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | openai | 400K | $0.75 / $4.50 | $0.2756 / $1.65 | 63.3% |
| [GPT-3.5 Turbo (older v0613)](https://martllm.com/models/openai/gpt-3.5-turbo-0613) | openai | 4K | $1.00 / $2.00 | $0.5775 / $1.16 | 42.2% |
| [GPT 5 Mini](https://martllm.com/models/openai/gpt-5-mini) | openai | 400K | $0.25 / $2.00 | $0.05513 / $0.441 | 78% |
| [GPT 5.1 Codex Mini](https://martllm.com/models/openai/gpt-5.1-codex-mini) | openai | 400K | $0.25 / $2.00 | $0.1444 / $1.16 | 42.2% |
| [GPT-4.1 mini](https://martllm.com/models/openai/gpt-4.1-mini) | openai | 1047K | $0.40 / $1.60 | $0.231 / $0.924 | 42.2% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | openai | 400K | $0.20 / $1.25 | $0.0504 / $0.315 | 74.8% |
| [GPT-5.6 Luna](https://martllm.com/models/openai/gpt-5.6-luna) | openai | 1050K | $0.20 / $1.20 | $0.0693 / $0.4158 | 65.3% |
| [GPT-5.6 Luna Pro](https://martllm.com/models/openai/gpt-5.6-luna-pro) | openai | 1050K | $0.20 / $1.20 | $0.1995 / $1.20 | 0.2% |
| [GPT OSS 120B](https://martllm.com/models/openai/e2ee-gpt-oss-120b-p) | openai | 128K | $0.13 / $0.65 | $0.1365 / $0.6825 | -5% |
| [GPT-4o Mini](https://martllm.com/models/openai/gpt-4o-mini) | openai | 128K | $0.15 / $0.60 | $0.0315 / $0.126 | 79% |
| [GPT-4o-mini (2024-07-18)](https://martllm.com/models/openai/gpt-4o-mini-2024-07-18) | openai | 128K | $0.15 / $0.60 | $0.08662 / $0.3465 | 42.2% |
| [GPT OSS Safeguard 120B](https://martllm.com/models/openai/gpt-oss-safeguard-120b) | openai | 128K | $0.15 / $0.60 | $0.01103 / $0.0441 | 92.7% |
| [GPT-6 Luna](https://martllm.com/models/openai/gpt-6-luna) | openai | 1050K | $0.10 / $0.50 | $0.03675 / $0.1837 | 63.3% |
| [GPT-6 Luna Pro](https://martllm.com/models/openai/gpt-6-luna-pro) | openai | 1050K | $0.10 / $0.50 | $0.0987 / $0.4935 | 1.3% |
| [GPT-4.1 nano](https://martllm.com/models/openai/gpt-4.1-nano) | openai | 1047K | $0.10 / $0.40 | $0.05775 / $0.231 | 42.2% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | openai | 400K | $0.05 / $0.40 | $0.01523 / $0.1218 | 69.5% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | openai | 128K | $0.07 / $0.30 | $0.01544 / $0.06615 | 78% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | openai | 128K | $0.0725 / $0.25 | $0.00609 / $0.021 | 91.6% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | openai | 128K | $0.03 / $0.15 | $0.005985 / $0.02993 | 80% |
| [Claude Opus 4.1](https://martllm.com/models/anthropic/claude-opus-4.1) | anthropic | 200K | $15.00 / $75.00 | $8.66 / $43.31 | 42.2% |
| [Claude Fable 5](https://martllm.com/models/anthropic/claude-fable-5) | anthropic | 1000K | $10.00 / $50.00 | $6.30 / $31.50 | 37% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | anthropic | 1000K | $10.00 / $50.00 | $6.30 / $31.50 | 37% |
| [Claude Opus 5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5-fast) | anthropic | 1000K | $10.00 / $50.00 | $8.29 / $41.48 | 17% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | anthropic | 1000K | $8.00 / $40.00 | $5.46 / $27.30 | 31.8% |
| [Claude Opus 4.5](https://martllm.com/models/anthropic/claude-opus-4.5) | anthropic | 198K | $5.00 / $25.00 | $4.09 / $20.48 | 18.1% |
| [Claude Opus 4.6](https://martllm.com/models/anthropic/claude-opus-4.6) | anthropic | 1000K | $5.00 / $25.00 | $4.20 / $21.00 | 16% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | anthropic | 1000K | $5.00 / $25.00 | $2.99 / $14.96 | 40.1% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | anthropic | 1000K | $5.00 / $25.00 | $2.78 / $13.91 | 44.4% |
| [Claude Opus 5](https://martllm.com/models/anthropic/claude-opus-5) | anthropic | 1000K | $5.00 / $25.00 | $2.94 / $14.70 | 41.2% |
| [Claude Opus 5.5](https://martllm.com/models/anthropic/claude-opus-5.5) | anthropic | 1000K | $4.00 / $20.00 | $2.06 / $10.29 | 48.6% |
| [Claude Sonnet 4.5](https://martllm.com/models/anthropic/claude-sonnet-4.5) | anthropic | 198K | $3.00 / $15.00 | $2.65 / $13.23 | 11.8% |
| [Claude Sonnet 4.6](https://martllm.com/models/anthropic/claude-sonnet-4.6) | anthropic | 1000K | $3.00 / $15.00 | $1.92 / $9.61 | 36% |
| [Claude Sonnet 5](https://martllm.com/models/anthropic/claude-sonnet-5) | anthropic | 1000K | $2.00 / $10.00 | $1.20 / $5.99 | 40.1% |
| [Claude Sonnet 5.5](https://martllm.com/models/anthropic/claude-sonnet-5.5) | anthropic | 1000K | $2.00 / $10.00 | $1.30 / $6.51 | 34.9% |
| [Claude Haiku 4.5](https://martllm.com/models/anthropic/claude-haiku-4.5) | anthropic | 200K | $1.00 / $5.00 | $1.05 / $5.25 | -5% |
| [Claude Haiku 5.5](https://martllm.com/models/anthropic/claude-haiku-5.5) | anthropic | 1000K | $0.10 / $0.50 | $0.063 / $0.315 | 37% |
| [Google: Gemini 4 Neon](https://martllm.com/models/google/gemini-4-neon) | google | 1048K | $3.00 / $15.00 | $1.32 / $6.62 | 55.9% |
| [Nano Banana Pro (Gemini 3 Pro Image Preview)](https://martllm.com/models/google/gemini-3-pro-image-preview) | google | 65K | $2.00 / $12.00 | $1.16 / $6.93 | 42.2% |
| [Gemini 3.1 Pro Preview](https://martllm.com/models/google/gemini-3.1-pro-preview) | google | 1000K | $2.00 / $12.00 | $0.546 / $3.28 | 72.7% |
| [Gemini 3.1 Pro Preview Custom Tools](https://martllm.com/models/google/gemini-3.1-pro-preview-customtools) | google | 1048K | $2.00 / $12.00 | $1.16 / $6.93 | 42.2% |
| [Gemini 2.5 Pro Preview 06-05](https://martllm.com/models/google/gemini-2.5-pro-preview) | google | 1048K | $1.25 / $10.00 | $0.7219 / $5.78 | 42.2% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | google | 1048K | $2.00 / $10.00 | $0.399 / $2.00 | 80% |
| [Google: Gemini 4 Carbon](https://martllm.com/models/google/gemini-4-carbon) | google | 1048K | $2.00 / $10.00 | $0.882 / $4.41 | 55.9% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | google | 1048K | $1.50 / $9.00 | $1.50 / $9.00 | 0% |
| [Gemini Omni 1.1 Flash](https://martllm.com/models/google/gemini-omni-1.1-flash) | google | 131K | $1.50 / $9.00 | $0.8662 / $5.20 | 42.2% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | google | 1048K | $1.50 / $7.50 | $0.2205 / $1.10 | 85.3% |
| [Gemini Nano Banana 2.1](https://martllm.com/models/google/gemini-nano-banana-2.1) | google | 131K | $1.50 / $7.50 | $0.8662 / $4.33 | 42.2% |
| [Gemini 3.6 Flash](https://martllm.com/models/google/gemini-3-6-flash) | google | 1000K | $0.75 / $3.75 | $0.5513 / $2.76 | 26.5% |
| [Gemini 3.7 Flash](https://martllm.com/models/google/gemini-3.7-flash) | google | 1048K | $0.75 / $3.75 | $0.6375 / $3.19 | 15% |
| [Gemini 3.8 Flash](https://martllm.com/models/google/gemini-3.8-flash) | google | 1048K | $0.75 / $3.75 | $0.126 / $0.63 | 83.2% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | google | 256K | $0.50 / $3.00 | $0.1207 / $0.7245 | 75.8% |
| [Gemini 3.1 Flash Image (Nano Banana 2)](https://martllm.com/models/google/gemini-3.1-flash-image) | google | 131K | $0.50 / $3.00 | $0.2888 / $1.73 | 42.2% |
| [Nano Banana 2 (Gemini 3.1 Flash Image Preview)](https://martllm.com/models/google/gemini-3.1-flash-image-preview) | google | 65K | $0.50 / $3.00 | $0.2888 / $1.73 | 42.2% |
| [Gemini 2.5 Flash](https://martllm.com/models/google/gemini-2.5-flash) | google | 1048K | $0.30 / $2.50 | $0.1732 / $1.44 | 42.2% |
| [Gemini 3.1 Flash Lite](https://martllm.com/models/google/gemini-3.1-flash-lite) | google | 1048K | $0.25 / $1.50 | $0.21 / $1.26 | 16% |
| [Gemini 3.1 Flash Lite Image (Nano Banana 2 Lite)](https://martllm.com/models/google/gemini-3.1-flash-lite-image) | google | 65K | $0.25 / $1.50 | $0.1444 / $0.8662 | 42.2% |
| [Gemini 3.1 Flash Lite Preview](https://martllm.com/models/google/gemini-3.1-flash-lite-preview) | google | 1048K | $0.25 / $1.50 | $0.1444 / $0.8662 | 42.2% |
| [Gemini 2.5 Flash Lite](https://martllm.com/models/google/gemini-2.5-flash-lite) | google | 1048K | $0.10 / $0.40 | $0.05775 / $0.231 | 42.2% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | google | 256K | $0.12 / $0.36 | $0.0189 / $0.0567 | 84.2% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | google | 262K | $0.12 / $0.36 | $0.08442 / $0.2533 | 29.6% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | google | 262K | $0.10 / $0.32 | $0.00735 / $0.02352 | 92.7% |
| [Gemma 3 27B](https://martllm.com/models/google/gemma-3-27b-it) | google | 40K | $0.08 / $0.20 | $0.02268 / $0.0567 | 71.7% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | google | 128K | $0.0625 / $0.1875 | $0.008531 / $0.02559 | 86.3–86.4% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | google | 128K | $0.045 / $0.09 | $0.002363 / $0.004725 | 94.7–94.8% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | google | 128K | $0.04 / $0.08 | $0.00588 / $0.01176 | 85.3% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | deepseek | 1048K | $1.32 / $3.96 | $0.2218 / $0.6653 | 83.2% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | deepseek | 1000K | $1.36 / $2.72 | $0.4135 / $0.827 | 69.5% |
| [R1 0528](https://martllm.com/models/deepseek/deepseek-r1-0528) | deepseek | 163K | $0.571 / $2.29 | $0.3856 / $1.16 | 32.5–49.1% |
| [DeepSeek V3](https://martllm.com/models/deepseek/deepseek-chat) | deepseek | 163K | $0.2574 / $1.03 | $0.1486 / $0.5941 | 42.2–42.3% |
| [DeepSeek V3 0324](https://martllm.com/models/deepseek/deepseek-chat-v3-0324) | deepseek | 163K | $0.25 / $1.00 | $0.1444 / $0.5775 | 42.2% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-v3.1) | deepseek | 128K | $0.27 / $1.00 | $0.05387 / $0.1995 | 80% |
| [DeepSeek V3.1 Terminus](https://martllm.com/models/deepseek/deepseek-v3.1-terminus) | deepseek | 163K | $0.27 / $1.00 | $0.1559 / $0.5775 | 42.2% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-chat-v3.1) | deepseek | 163K | $0.25 / $0.95 | $0.1444 / $0.5486 | 42.2% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | deepseek | 1048K | $0.2112 / $0.84 | $0.08427 / $0.3352 | 60.1% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | deepseek | 1048K | $0.2695 / $0.8085 | $0.2632 / $0.7895 | 2.3–2.4% |
| [DeepSeek V4 Flash 0731 Fast](https://martllm.com/models/deepseek/deepseek-v4-flash-0731-fast) | deepseek | 1000K | $0.35 / $0.70 | $0.2903 / $0.5806 | 17% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | deepseek | 1048K | $0.15 / $0.70 | $0.0189 / $0.0882 | 87.4% |
| [DeepSeek V3.2 Exp](https://martllm.com/models/deepseek/deepseek-v3.2-exp) | deepseek | 163K | $0.27 / $0.41 | $0.1559 / $0.2368 | 42.2% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | deepseek | 160K | $0.26 / $0.38 | $0.05733 / $0.08379 | 78% |
| [DeepSeek V4 Flash E2EE](https://martllm.com/models/deepseek/e2ee-deepseek-v4-flash) | deepseek | 1000K | $0.182 / $0.373 | $0.1854 / $0.3799 | -1.9–-1.8% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | deepseek | 1000K | $0.1325 / $0.275 | $0.08069 / $0.1675 | 39.1% |
| [DeepSeek V4 Flash 0731](https://martllm.com/models/deepseek/deepseek-v4-flash-0731) | deepseek | 1048K | $0.13 / $0.26 | $0.07098 / $0.142 | 45.4% |
| [Grok 4.5](https://martllm.com/models/x-ai/grok-4.5) | x-ai | 500K | $2.27 / $6.80 | $1.45 / $4.36 | 35.9–36% |
| [Grok 4.6](https://martllm.com/models/x-ai/grok-4.6) | x-ai | 500K | $2.27 / $6.80 | $2.12 / $6.35 | 6.6% |
| [Grok 4.7](https://martllm.com/models/x-ai/grok-4.7) | x-ai | 500K | $2.00 / $6.00 | $1.51 / $4.54 | 24.4% |
| [Grok 4.20 Beta](https://martllm.com/models/x-ai/grok-4.20-beta) | x-ai | 2000K | $1.42 / $2.83 | $0.7008 / $1.40 | 50.6% |
| [Grok 4.20 Multi-Agent Beta](https://martllm.com/models/x-ai/grok-4.20-multi-agent-beta) | x-ai | 2000K | $1.42 / $2.83 | $1.15 / $2.29 | 19.1% |
| [Grok 4.3](https://martllm.com/models/x-ai/grok-4.3) | x-ai | 1000K | $1.42 / $2.83 | $0.4622 / $0.9212 | 67.5% |
| [Grok 4.20](https://martllm.com/models/x-ai/grok-4.20) | x-ai | 2000K | $1.25 / $2.50 | $0.7219 / $1.44 | 42.2% |
| [Grok 4.20 Multi-Agent](https://martllm.com/models/x-ai/grok-4.20-multi-agent) | x-ai | 2000K | $1.25 / $2.50 | $0.7219 / $1.44 | 42.2% |
| [Grok Build 0.1](https://martllm.com/models/x-ai/grok-build-0.1) | x-ai | 256K | $1.00 / $2.00 | $1.05 / $2.10 | -5% |
| [Qwen: Qwen3.8 Max Prime](https://martllm.com/models/qwen/qwen3.8-max-prime) | qwen | 1000K | $4.00 / $12.00 | $3.95 / $11.84 | 1.3% |
| [Qwen3.7 Max](https://martllm.com/models/qwen/qwen3.7-max) | qwen | 256K | $2.70 / $8.05 | $2.64 / $7.86 | 2.3–2.4% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | qwen | 1000K | $2.00 / $6.00 | $1.74 / $5.23 | 12.8% |
| [Qwen3.8 2.4T A95B](https://martllm.com/models/qwen/qwen3.8-2.4t-a95b) | qwen | 1000K | $2.00 / $6.00 | $1.39 / $4.16 | 30.7% |
| [Qwen: Qwen3.8 Max (0902)](https://martllm.com/models/qwen/qwen3.8-max-0902) | qwen | 1000K | $2.00 / $6.00 | $0.42 / $1.26 | 79% |
| [Qwen 4 Max](https://martllm.com/models/qwen/qwen4-max) | qwen | 1000K | $1.43 / $4.28 | $0.6434 / $1.93 | 54.8% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | qwen | 128K | $0.50 / $3.60 | $0.294 / $2.12 | 41.2% |
| [Qwen 3 235B A22B Thinking 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-thinking-2507) | qwen | 128K | $0.45 / $3.50 | $0.1229 / $0.9555 | 72.7% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | qwen | 256K | $0.32 / $3.20 | $0.03696 / $0.3696 | 88.5% |
| [Qwen3.5-27B](https://martllm.com/models/qwen/qwen3.5-27b) | qwen | 262K | $0.26 / $2.60 | $0.1502 / $1.50 | 42.2% |
| [Qwen3.5-122B-A10B](https://martllm.com/models/qwen/qwen3.5-122b-a10b) | qwen | 262K | $0.26 / $2.08 | $0.1502 / $1.20 | 42.2% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | qwen | 262K | $0.20 / $2.00 | $0.0042 / $0.042 | 97.9% |
| [Qwen 3.7 Plus](https://martllm.com/models/qwen/qwen3.7-plus) | qwen | 256K | $0.50 / $2.00 | $0.4988 / $2.00 | 0.2% |
| [Qwen 3.6 Plus](https://martllm.com/models/qwen/qwen3.6-plus) | qwen | 1000K | $0.325 / $1.95 | $0.1877 / $1.13 | 42.2% |
| [Qwen3 VL 235B A22B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-instruct) | qwen | 256K | $0.21 / $1.90 | $0.05475 / $0.4954 | 73.9% |
| [Qwen3 VL 235B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-thinking) | qwen | 256K | $0.21 / $1.90 | $0.2007 / $1.82 | 4.4% |
| [Qwen3.5 Plus 2026-04-20](https://martllm.com/models/qwen/qwen3.5-plus-20260420) | qwen | 1000K | $0.30 / $1.80 | $0.1732 / $1.04 | 42.2% |
| [Qwen3.5 Plus 2026-02-15](https://martllm.com/models/qwen/qwen3.5-plus-02-15) | qwen | 1000K | $0.26 / $1.56 | $0.1502 / $0.9009 | 42.2% |
| [Qwen 3 Coder 480B Turbo](https://martllm.com/models/qwen/qwen3-coder-turbo) | qwen | 256K | $0.35 / $1.50 | $0.3528 / $1.51 | -0.8% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | qwen | 256K | $0.325 / $1.25 | $0.04777 / $0.1837 | 85.3% |
| [Qwen 3.6 35B A3B (E2EE)](https://martllm.com/models/qwen/e2ee-qwen3-6-35b-a3b) | qwen | 128K | $0.182 / $1.18 | $0.1815 / $1.18 | 0.2–0.3% |
| [Qwen3.6 Flash](https://martllm.com/models/qwen/qwen3.6-flash) | qwen | 1000K | $0.1875 / $1.12 | $0.1083 / $0.6497 | 42.2–42.3% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | qwen | 256K | $0.095 / $1.10 | $0.01496 / $0.1732 | 84.2% |
| [Qwen2.5 Coder 32B Instruct](https://martllm.com/models/qwen/qwen-2.5-coder-32b-instruct) | qwen | 32K | $0.66 / $1.00 | $0.3811 / $0.5775 | 42.2–42.3% |
| [Qwen 3.6 35B A3B](https://martllm.com/models/qwen/qwen3-6-35b-a3b) | qwen | 262K | $0.10 / $1.00 | $0.0777 / $0.777 | 22.3% |
| [Qwen 3.5 35B A3B](https://martllm.com/models/qwen/qwen3.5-35b-a3b) | qwen | 256K | $0.15 / $1.00 | $0.148 / $0.987 | 1.3% |
| [Qwen3 Coder Flash](https://martllm.com/models/qwen/qwen3-coder-flash) | qwen | 1000K | $0.195 / $0.975 | $0.1126 / $0.5631 | 42.2% |
| [Qwen3 VL 30B A3B](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-thinking) | qwen | 128K | $0.25 / $0.90 | $0.2625 / $0.945 | -5% |
| [Qwen3 Coder Next](https://martllm.com/models/qwen/qwen3-coder-next) | qwen | 256K | $0.12 / $0.80 | $0.02268 / $0.1512 | 81.1% |
| [Qwen-Plus](https://martllm.com/models/qwen/qwen-plus) | qwen | 1000K | $0.26 / $0.78 | $0.1502 / $0.4505 | 42.2% |
| [Qwen 3 235B A22B Instruct 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-2507) | qwen | 128K | $0.135 / $0.75 | $0.1006 / $0.5591 | 25.4–25.5% |
| [Qwen3 VL 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-instruct) | qwen | 262K | $0.15 / $0.60 | $0.08662 / $0.3465 | 42.2% |
| [Qwen3 30B A3B](https://martllm.com/models/qwen/qwen3-30b-a3b) | qwen | 256K | $0.12 / $0.50 | $0.09954 / $0.4148 | 17% |
| [Qwen3.8 Flash](https://martllm.com/models/qwen/qwen3.8-flash) | qwen | 1000K | $0.15 / $0.47 | $0.03623 / $0.1135 | 75.8% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | qwen | 1000K | $0.15 / $0.47 | $0.0252 / $0.07896 | 83.2% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | qwen | 256K | $0.11 / $0.44 | $0.01963 / $0.07854 | 82.2% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | qwen | 32K | $0.12 / $0.40 | $0.01512 / $0.0504 | 87.4% |
| [Qwen3 30B A3B Instruct 2507](https://martllm.com/models/qwen/qwen3-30b-a3b-instruct-2507) | qwen | 262K | $0.10 / $0.30 | $0.05775 / $0.1732 | 42.2% |
| [Qwen3.5-Flash](https://martllm.com/models/qwen/qwen3.5-flash-02-23) | qwen | 1000K | $0.065 / $0.26 | $0.03754 / $0.1502 | 42.2% |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | qwen | 256K | $0.10 / $0.25 | $0.0735 / $0.1103 | 26.5–55.9% |
| [Qwen 2.5 7B](https://martllm.com/models/qwen/e2ee-qwen-2-5-7b-p) | qwen | 32K | $0.05 / $0.13 | $0.04673 / $0.1215 | 6.6% |
| [Qwen: Qwen3.7 Flash](https://martllm.com/models/qwen/qwen3.7-flash) | qwen | 1000K | $0.03 / $0.13 | $0.02489 / $0.1078 | 17% |
| [Kimi K3 Fast](https://martllm.com/models/moonshotai/kimi-k3-fast-api) | moonshotai | 1000K | $4.50 / $22.50 | $4.49 / $22.44 | 0.2–0.3% |
| [Kimi K3](https://martllm.com/models/moonshotai/kimi-k3) | moonshotai | 1000K | $3.00 / $15.00 | $0.3071 / $1.57 | 89.5–89.8% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | moonshotai | 1048K | $2.00 / $10.00 | $1.03 / $5.14 | 48.6% |
| [Kimi K2.7 Code](https://martllm.com/models/moonshotai/kimi-k2.7-code) | moonshotai | 262K | $0.75 / $3.50 | $0.2284 / $1.07 | 69.5% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | moonshotai | 256K | $0.70 / $3.41 | $0.2132 / $1.04 | 69.5% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | moonshotai | 256K | $0.55 / $2.75 | $0.1328 / $0.6641 | 75.8–75.9% |
| [Kimi K2 0905](https://martllm.com/models/moonshotai/kimi-k2-0905) | moonshotai | 262K | $0.60 / $2.50 | $0.3465 / $1.44 | 42.2% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | moonshotai | 256K | $0.60 / $2.50 | $0.0882 / $0.3675 | 85.3% |
| [Kimi K2](https://martllm.com/models/moonshotai/kimi-k2) | moonshotai | 256K | $0.57 / $2.30 | $0.6284 / $2.54 | -10.3% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | z-ai | 524K | $1.75 / $5.75 | $1.82 / $5.98 | -4% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | z-ai | 1000K | $1.68 / $5.28 | $0.194 / $0.6098 | 88.4–88.5% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | z-ai | 1048K | $1.40 / $4.40 | $0.1764 / $0.5544 | 87.4% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | z-ai | 1000K | $1.40 / $4.40 | $0.08747 / $0.3155 | 92.8–93.8% |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | z-ai | 1000K | $1.19 / $4.29 | $1.11 / $4.01 | 6.5–6.6% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | z-ai | 200K | $1.33 / $4.18 | $0.5775 / $2.18 | 47.9–56.6% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | z-ai | 200K | $1.33 / $4.18 | $0.3491 / $1.10 | 73.8% |
| [GLM-5 Turbo](https://martllm.com/models/z-ai/glm-5-turbo) | z-ai | 200K | $1.20 / $4.00 | $0.9198 / $3.07 | 23.4% |
| [GLM 5V Turbo](https://martllm.com/models/z-ai/glm-5v-turbo) | z-ai | 200K | $1.20 / $4.00 | $1.17 / $3.91 | 2.3% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | z-ai | 198K | $0.925 / $2.71 | $0.5342 / $1.57 | 42.2% |
| [GLM 4.5](https://martllm.com/models/z-ai/glm-4.5) | z-ai | 128K | $0.60 / $2.20 | $0.5922 / $2.17 | 1.3% |
| [GLM 4.5V](https://martllm.com/models/z-ai/glm-4.5v) | z-ai | 66K | $0.60 / $1.80 | $0.3465 / $1.04 | 42.2% |
| [GLM-4.6](https://martllm.com/models/z-ai/glm-4.6) | z-ai | 198K | $0.43 / $1.75 | $0.1309 / $0.5329 | 69.5% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | z-ai | 128K | $0.40 / $1.75 | $0.1974 / $0.8636 | 50.6–50.7% |
| [Z.ai: GLM 5.3 FlashX](https://martllm.com/models/z-ai/glm-5.3-flashx) | z-ai | 1048K | $0.37 / $1.25 | $0.2797 / $0.945 | 24.4% |
| [Z.ai: GLM 5.3 FlashX Legal](https://martllm.com/models/z-ai/glm-5.3-flashx-legal) | z-ai | 1048K | $0.37 / $1.25 | $0.2642 / $0.8925 | 28.6% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | z-ai | 128K | $0.17 / $0.98 | $0.1285 / $0.7409 | 24.4% |
| [GLM 4.6V](https://martllm.com/models/z-ai/glm-4.6v) | z-ai | 131K | $0.30 / $0.90 | $0.1732 / $0.5198 | 42.2% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | z-ai | 1048K | $0.125 / $0.45 | $0.02231 / $0.08032 | 82.1–82.2% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | z-ai | 198K | $0.0605 / $0.40 | $0.01398 / $0.0924 | 76.9% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | mistralai | 128K | $2.00 / $6.00 | $0.168 / $0.504 | 91.6% |
| [Mistral Large 2407](https://martllm.com/models/mistralai/mistral-large-2407) | mistralai | 131K | $2.00 / $6.00 | $1.16 / $3.46 | 42.2% |
| [Mixtral 8x22B Instruct](https://martllm.com/models/mistralai/mixtral-8x22b-instruct) | mistralai | 65K | $2.00 / $6.00 | $1.16 / $3.46 | 42.2% |
| [Mistral: Pixtral Large 2502](https://martllm.com/models/mistralai/pixtral-large-2502) | mistralai | 128K | $2.00 / $6.00 | $1.95 / $5.86 | 2.3% |
| [Mistral: Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4-0) | mistralai | 524K | $0.735 / $2.21 | $0.1003 / $0.301 | 86.3% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | mistralai | 256K | $0.40 / $2.00 | $0.0504 / $0.252 | 87.4% |
| [Devstral 2 2512](https://martllm.com/models/mistralai/devstral-2512) | mistralai | 262K | $0.40 / $2.00 | $0.231 / $1.16 | 42.2% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | mistralai | 256K | $0.525 / $1.57 | $0.07717 / $0.2315 | 85.3% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | mistralai | 128K | $0.50 / $1.50 | $0.063 / $0.189 | 87.4% |
| [Codestral 2508](https://martllm.com/models/mistralai/codestral-2508) | mistralai | 256K | $0.30 / $0.90 | $0.1732 / $0.5198 | 42.2% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-4) | mistralai | 256K | $0.165 / $0.66 | $0.1732 / $0.693 | -5% |
| [Saba](https://martllm.com/models/mistralai/mistral-saba) | mistralai | 32K | $0.20 / $0.60 | $0.1155 / $0.3465 | 42.2% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-2603) | mistralai | 262K | $0.15 / $0.60 | $0.08662 / $0.3465 | 42.2% |
| [Mistral Small 3.1 24B](https://martllm.com/models/mistralai/mistral-small-3.1-24b-instruct) | mistralai | 128K | $0.351 / $0.555 | $0.2027 / $0.3205 | 42.2% |
| [Voxtral Small 24B 2507](https://martllm.com/models/mistralai/voxtral-small-24b-2507) | mistralai | 32K | $0.105 / $0.315 | $0.08489 / $0.2547 | 19.1% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | mistralai | 128K | $0.21 / $0.21 | $0.0463 / $0.0463 | 78% |
| [Ministral 14B](https://martllm.com/models/mistralai/ministral-14b) | mistralai | 262K | $0.20 / $0.20 | $0.184 / $0.184 | 8% |
| [Ministral 3 14B 2512](https://martllm.com/models/mistralai/ministral-14b-2512) | mistralai | 262K | $0.20 / $0.20 | $0.1155 / $0.1155 | 42.2% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | mistralai | 256K | $0.075 / $0.20 | $0.07166 / $0.1911 | 4.4–4.5% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | mistralai | 128K | $0.1575 / $0.1575 | $0.02481 / $0.02481 | 84.3% |
| [Ministral 8B](https://martllm.com/models/mistralai/ministral-8b) | mistralai | 262K | $0.15 / $0.15 | $0.138 / $0.138 | 8% |
| [Ministral 3 8B 2512](https://martllm.com/models/mistralai/ministral-8b-2512) | mistralai | 262K | $0.15 / $0.15 | $0.08662 / $0.08662 | 42.2% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | mistralai | 128K | $0.105 / $0.105 | $0.01213 / $0.01213 | 88.4% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3b) | mistralai | 131K | $0.10 / $0.10 | $0.092 / $0.092 | 8% |
| [Ministral 3 3B 2512](https://martllm.com/models/mistralai/ministral-3b-2512) | mistralai | 131K | $0.10 / $0.10 | $0.05775 / $0.05775 | 42.2% |
| [Mistral Small 3](https://martllm.com/models/mistralai/mistral-small-24b-instruct-2501) | mistralai | 32K | $0.05 / $0.08 | $0.02888 / $0.0462 | 42.2% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | mistralai | 32K | $0.04 / $0.04 | $0.0084 / $0.0084 | 79% |
| [Mistral Nemo 12B](https://martllm.com/models/mistralai/mistral-nemo) | mistralai | 131K | $0.029 / $0.03 | $0.01675 / $0.01733 | 42.2% |
| [Meta: Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder) | meta-llama | 1048K | $4.00 / $20.00 | $2.14 / $10.71 | 46.4–46.5% |
| [Meta: Muse Spark 1.1](https://martllm.com/models/meta-llama/muse-spark-1.1) | meta-llama | 1048K | $1.25 / $4.25 | $0.5644 / $1.92 | 54.9% |
| [Meta: Muse Spark 1.2](https://martllm.com/models/meta-llama/muse-spark-1.2) | meta-llama | 1048K | $1.25 / $4.25 | $0.5381 / $1.83 | 57% |
| [Meta: Muse Spark 1.3](https://martllm.com/models/meta-llama/muse-spark-1.3) | meta-llama | 1048K | $1.25 / $4.25 | $0.4725 / $1.61 | 62.2% |
| [Meta: Muse Spark Open](https://martllm.com/models/meta-llama/muse-spark-open) | meta-llama | 1048K | $1.25 / $4.25 | $1.21 / $4.11 | 3.4% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | meta-llama | 131K | $0.325 / $1.35 | $0.3242 / $1.35 | 0.2–0.3% |
| [Llama 4 Maverick](https://martllm.com/models/meta-llama/llama-4-maverick) | meta-llama | 1048K | $0.35 / $1.00 | $0.2021 / $0.5775 | 42.2% |
| [Llama 3.1 70B Instruct](https://martllm.com/models/meta-llama/llama-3.1-70b) | meta-llama | 128K | $0.72 / $0.72 | $0.6624 / $0.6624 | 8% |
| [Llama 3.1 70B Instruct](https://martllm.com/models/meta-llama/llama-3.1-70b-instruct) | meta-llama | 131K | $0.72 / $0.72 | $0.4158 / $0.4158 | 42.2% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | meta-llama | 128K | $0.293 / $0.71 | $0.243 / $0.5889 | 17% |
| [Meta: Muse Ember](https://martllm.com/models/meta-llama/muse-ember) | meta-llama | 1048K | $0.10 / $0.50 | $0.09765 / $0.4883 | 2.3–2.4% |
| [Llama 3.2 3B](https://martllm.com/models/meta-llama/llama-3.2-3b-instruct) | meta-llama | 128K | $0.05 / $0.33 | $0.0483 / $0.3188 | 3.4% |
| [Llama 4 Scout](https://martllm.com/models/meta-llama/llama-4-scout) | meta-llama | 327K | $0.10 / $0.30 | $0.05775 / $0.1732 | 42.2% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.0483 / $0.0966 | 51.7% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.0483 / $0.0966 | 51.7% |
| [Llama 3.1 8B Instruct](https://martllm.com/models/meta-llama/llama-3.1-8b-instruct) | meta-llama | 131K | $0.05 / $0.08 | $0.02888 / $0.0462 | 42.2% |

</details>

### Image models (per image)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Recraft V4.1 Flash](https://martllm.com/models/recraft/recraft-v4-1-flash) | $0.007 / image | $0.002352 / image | 66.4% |
| [Recraft V4.1 Flash V2](https://martllm.com/models/recraft/recraft-v4-1-flash-v2) | $0.007 / image | $0.002352 / image | 66.4% |
| [FLUX.1 [schnell]](https://martllm.com/models/fal-ai/flux/schnell) | – | $0.002856 / image | – |
| [Image 01 Image To Image](https://martllm.com/models/minimax/image-01-image-to-image) | – | $0.003332 / image | – |
| [MiniMax Image-01](https://martllm.com/models/minimax/image-01-text-to-image) | – | $0.003332 / image | – |
| [Z-Image Turbo (Venice)](https://martllm.com/models/venice/z-image-turbo) | $0.01 / image | $0.00448 / image | 55.2% |
| [FLUX.1 Dev Ultra Fast](https://martllm.com/models/black-forest-labs/flux-dev-ultra-fast) | $0.005 / image | $0.00476 / image | 4.8% |
| [P-Image](https://martllm.com/models/pruna-ai/p-image-text-to-image) | $0.005 / image | $0.00476 / image | 4.8% |
| [Muse Image](https://martllm.com/models/meta-llama/venice-muse-image) | $0.02 / image | $0.004852 / image | 75.7% |
| [Photon Flash](https://martllm.com/models/luma/photon-flash) | – | $0.005 / image | – |

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
| [SeedVR2 Video Upscaler](https://martllm.com/models/bytedance/seedvr2-video-upscaler) | $0 / sec | $0 / sec | – |
| [daVinci-MagiHuman (image-to-video)](https://martllm.com/models/gair/davinci-magihuman-image-to-video) | $0 / sec | $0 / sec | – |
| [Gemini Omni Flash 1.1 Edit](https://martllm.com/models/google/gemini-omni-flash-1-1-video-to-video) | $0 / sec | $0 / sec | – |
| [Kling O3 4K Video Reference](https://martllm.com/models/kling/kling-o3-4k-video-reference) | $0 / sec | $0 / sec | – |
| [Kling 4.0 Flash Edit](https://martllm.com/models/kling/kling-v4-flash-video-to-video) | $0 / sec | $0 / sec | – |
| [Kling 4.0 Edit](https://martllm.com/models/kling/kling-v4-video-to-video) | $0 / sec | $0 / sec | – |
| [LTX-2 19B Control (pose)](https://martllm.com/models/lightricks/ltx-2-19b-control) | $0 / sec | $0 / sec | – |
| [LTX-2 Pro (image-to-video)](https://martllm.com/models/lightricks/ltx-2-pro-image-to-video) | $0 / sec | $0 / sec | – |

### Video models (per video)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Topaz Video Astra](https://martllm.com/models/topaz-labs/topaz-video-astra) | $0 / video | $0 / video | – |
| [Topaz Video Denoise](https://martllm.com/models/topaz-labs/topaz-video-denoise) | $0 / video | $0 / video | – |
| [Topaz Video Precision](https://martllm.com/models/topaz-labs/topaz-video-precision) | $0 / video | $0 / video | – |
| [Topaz Video Starlight](https://martllm.com/models/topaz-labs/topaz-video-starlight) | $0 / video | $0 / video | – |
| [Topaz Video Starlight Fast](https://martllm.com/models/topaz-labs/topaz-video-starlight-fast) | $0 / video | $0 / video | – |

### Music models

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [MMAudio V2 Text-to-Audio (Venice)](https://martllm.com/models/venice/mmaudio-v2-text-to-audio) | $0.00092 / sec | $0.0007733 / sec | 15.9% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | $0.0023 / sec | $0.001159 / sec | 49.6% |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-sound-effects-v1-0) | $0.00207 / sec | $0.001855 / sec | 10.4% |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-v1-1-sound-effects) | – | $0.00207 / sec | – |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | – | $0.003187 / sec | – |
| [Seed Audio 1.0](https://martllm.com/models/byteplus/seed-audio-1-0) | – | $0.00322 / sec | – |
| [ACE-Step 1.5 (Venice)](https://martllm.com/models/venice/ace-step-15) | $0.03 / track | $0.0252 / track | 16% |
| [Venice Music Gen (legacy alias)](https://martllm.com/models/venice/music-gen) | – | $0.0336 / track | – |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | $0.046 / 1K chars | $0.03864 / 1K chars | 16% |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | – | $0.0448 / track | – |

### Speech models

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Kokoro Text to Speech (Venice)](https://martllm.com/models/venice/kokoro-tts) | $0.0035 / 1K chars | $0.00294 / 1K chars | 16% |
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | – | $0.003881 / 1K chars | – |
| [Inworld 1.5 Max TTS](https://martllm.com/models/inworld/tts-inworld-1-5-max) | $0.0125 / 1K chars | $0.0112 / 1K chars | 10.4% |
| [xAI v1 TTS](https://martllm.com/models/x-ai/tts-xai-v1) | – | $0.02079 / 1K chars | – |
| [Eleven Flash v2](https://martllm.com/models/elevenlabs/eleven-flash-v2) | – | $0.04 / 1K chars | – |
| [Eleven Flash v2.5](https://martllm.com/models/elevenlabs/eleven-flash-v2-5) | – | $0.04 / 1K chars | – |
| [Eleven Turbo v2](https://martllm.com/models/elevenlabs/eleven-turbo-v2) | – | $0.04 / 1K chars | – |
| [Eleven v3 Conversational](https://martllm.com/models/elevenlabs/eleven-v3-conversational) | – | $0.04 / 1K chars | – |
| [Gradium TTS](https://martllm.com/models/gradium/tts-gradium-v1) | – | $0.0475 / 1K chars | – |
| [Chatterbox HD TTS](https://martllm.com/models/resemble-ai/tts-chatterbox-hd) | – | $0.056 / 1K chars | – |

## Prices under review

The catalog's official price for these 11 models failed a sanity check (see `list_price_review_reason`), so it is left out, with no % below list, until it is checked against the maker's own page. The MartLLM price is still listed.

| Model | Category | Why |
|---|---|---|
| [Gemma 2 27B](https://martllm.com/models/google/gemma-2-27b-it) | text | output:input ratio 1.0 vs 5.0 for the maker's other models |
| [Mistral Large 3 2512](https://martllm.com/models/mistralai/mistral-large-2512) | text | input list price more than 3x off other listings of the same model |
| [Nemotron 3.5 Content Safety](https://martllm.com/models/nvidia/nemotron-3.5-content-safety) | text | output:input ratio 1.0 vs 3.6 for the maker's other models |
| [GPT-3.5 Turbo 16k](https://martllm.com/models/openai/gpt-3.5-turbo-16k) | text | output:input ratio 1.3 vs 5.0 for the maker's other models |
| [Sonar](https://martllm.com/models/perplexity/sonar) | text | output:input ratio 1.0 vs 4.0 for the maker's other models |
| [Qwen2.5 VL 72B Instruct](https://martllm.com/models/qwen/qwen2.5-vl-72b-instruct) | text | output:input ratio 1.2 vs 4.2 for the maker's other models |
| [FLUX.1 [schnell]](https://martllm.com/models/fal-ai/flux/schnell) | image | more than 10x off the median image price per image |
| [Image 01 Image To Image](https://martllm.com/models/minimax/image-01-image-to-image) | image | more than 10x off the median image price per image |
| [MiniMax Image-01](https://martllm.com/models/minimax/image-01-text-to-image) | image | more than 10x off the median image price per image |
| [Hunyuan Image 3 Instruct Edit](https://martllm.com/models/tencent/hunyuan-image-3-instruct-edit) | image | more than 10x off the median image price per image |
| [Hunyuan Image 3.0 Instruct](https://martllm.com/models/tencent/hunyuan-image-3-instruct-text-to-image) | image | more than 10x off the median image price per image |

## Biggest drops this week (2026-11-20 to 2026-11-27)

From MartLLM's daily catalog snapshots (`GET /api/v1/public/price-changes`). Text: $ per 1M input / output tokens, sorted by the larger of the two moves.

### Official list price cuts

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Wan 2.2 A14B Text-to-Video](https://martllm.com/models/wan/wan-2-2-a14b-text-to-video) | video | $0.20 / sec | $0.04 / sec | −80% |
| [MiniMax H3 Chili Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-chili-text-to-video) | video | $0.12 / sec | $0.03 / sec | −75% |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-text-to-video) | video | $0.10 / sec | $0.025 / sec | −75% |
| [Topaz Video Upscale](https://martllm.com/models/topaz-labs/topaz-video-upscale) | video | $0.15 / sec | $0.0448 / sec | −70% |
| [Runway Gen-4 Aleph](https://martllm.com/models/runway/runway-gen4-aleph) | video | $0.50 / sec | $0.25 / sec | −50% |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | text | $0.17 / $0.25 | $0.10 / $0.25 | in −41% / out 0% |
| [NVIDIA Nemotron 3 Ultra 550B](https://martllm.com/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.625 / $3.12 | $0.50 / $2.20 | in −20% / out −30% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | text | $0.5002 / $2.06 | $0.40 / $1.75 | in −20% / out −15% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.09 / $0.25 | $0.075 / $0.20 | in −17% / out −20% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | text | $2.50 / $7.50 | $2.00 / $6.00 | −20% |

### MartLLM price drops

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Palmyra Vision 7B](https://martllm.com/models/writer/palmyra-vision-7b) | text | $0.0441 / $0.1764 | $0.00315 / $0.0126 | −93% |
| [Wan 3.0 Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-reference-to-video) | video | $0.2782 / sec | $0.03324 / sec | −88% |
| [Wan 3.0 Prime Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-reference-to-video) | video | $0.3895 / sec | $0.05199 / sec | −87% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | text | $0.01606 / $0.03213 | $0.002363 / $0.004725 | −85% |
| [MiniMax H3 Image (image-to-image)](https://martllm.com/models/minimax/venice-minimax-h3-image-edit) | image | $0.063 / image | $0.01008 / image | −84% |
| [LTX 2 19B Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-19b-full-text-to-video) | video | $0.09416 / sec | $0.01523 / sec | −84% |
| [GPT Image 2.5 Sunburst (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-sunburst-edit) | image | $0.0315 / image | $0.0056 / image | −82% |
| [GPT Image 2.5 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-flare) | image | $0.0315 / image | $0.0056 / image | −82% |
| [GPT Image 2.5 Sunburst (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-sunburst) | image | $0.0315 / image | $0.0056 / image | −82% |
| [GPT Image 2 (Venice)](https://martllm.com/models/venice/gpt-image-2) | image | $0.0315 / image | $0.0056 / image | −82% |

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
