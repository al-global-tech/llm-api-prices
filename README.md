# LLM API prices

*MartLLM was called UberLLM until November 2026; the `uberllm_*` column names stay as they are.*

An open, daily-updated dataset of AI API prices: the official list price of 1397 text, image, video, music and speech models next to the lowest live price on the [MartLLM](https://martllm.com/models) market, how far below list that is, context length and capabilities.

**Updated:** 2026-11-28T03:17:08Z · **Models:** 355 text, 324 image, 492 video, 49 music, 37 speech, 10 transcription, 130 other · **Files:** [`prices.json`](prices.json), [`prices.csv`](prices.csv), [`CHANGELOG.md`](CHANGELOG.md), [`history/`](history/)

Disclosure: this repo is maintained by the team that runs MartLLM. The MartLLM column is our own price; the official column is the maker's price, sourced as described in [Sources](#sources). Live prices: <https://martllm.com/models>.

## Cheapest right now

Lowest MartLLM price per category among models that can be called now. Text: $ per 1M input / output tokens. Full list: [`prices.csv`](prices.csv).

### Text (chat) models

| Model | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | 128K | $0.03 / $0.15 | $0.000315 / $0.001575 | 99% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | 32K | $0.04 / $0.04 | $0.0084 / $0.0084 | 79% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | 128K | $0.04 / $0.08 | $0.0105 / $0.021 | 73.8% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | 128K | $0.0725 / $0.25 | $0.008374 / $0.02888 | 88.4% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | 262K | $0.20 / $2.00 | $0.0042 / $0.042 | 97.9% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | 128K | $0.105 / $0.105 | $0.02756 / $0.02756 | 73.7% |
| [NVIDIA Nemotron Nano 9B v2](https://martllm.com/models/nvidia/nemotron-nano-9b-v2) | 128K | $0.06 / $0.23 | $0.0126 / $0.0483 | 79% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | 256K | $0.11 / $0.44 | $0.0127 / $0.05082 | 88.5% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | 128K | $0.07 / $0.30 | $0.01323 / $0.0567 | 81.1% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | 262K | $0.10 / $0.30 | $0.0189 / $0.0567 | 81.1% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | 1048K | $0.1575 / $0.71 | $0.01488 / $0.0671 | 90.5% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | 256K | $0.12 / $0.36 | $0.02142 / $0.06426 | 82.2% |
| [Palmyra Vision 7B](https://martllm.com/models/writer/palmyra-vision-7b) | 4K | $0.15 / $0.60 | $0.01733 / $0.0693 | 88.4% |
| [MiniMax M3.1 Flash](https://martllm.com/models/minimax/minimax-m3-1-flash) | 1000K | $0.15 / $0.60 | $0.0189 / $0.0756 | 87.4% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | 32K | $0.12 / $0.40 | $0.021 / $0.0735 | 81.6–82.5% |

### Major model makers

<details><summary>OpenAI, Anthropic, Google, DeepSeek, xAI, Qwen, Moonshot, Z.ai, Mistral, Meta (185 models)</summary>

| Model | Maker | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|---|
| [GPT-5.4 Pro](https://martllm.com/models/openai/gpt-5.4-pro) | openai | 1000K | $30.00 / $180.00 | $15.12 / $90.72 | 49.6% |
| [GPT-5.5 Pro](https://martllm.com/models/openai/gpt-5.5-pro) | openai | 1000K | $30.00 / $180.00 | $17.95 / $107.73 | 40.1–40.2% |
| [GPT 5.2](https://martllm.com/models/openai/gpt-5.2-pro) | openai | 400K | $21.00 / $168.00 | $15.88 / $127.01 | 24.4% |
| [GPT-5 pro](https://martllm.com/models/openai/gpt-5-pro) | openai | 400K | $15.00 / $120.00 | $11.34 / $90.72 | 24.4% |
| [o3 Pro](https://martllm.com/models/openai/o3-pro) | openai | 200K | $20.00 / $80.00 | $15.12 / $60.48 | 24.4% |
| [GPT-6 Astra](https://martllm.com/models/openai/gpt-6-astra) | openai | 1050K | $10.00 / $50.00 | $3.46 / $17.32 | 65.3% |
| [GPT-6 Astra Pro](https://martllm.com/models/openai/gpt-6-astra-pro) | openai | 1050K | $10.00 / $50.00 | $5.63 / $28.18 | 43.6% |
| [GPT-6.2 Astra](https://martllm.com/models/openai/gpt-6.2-astra) | openai | 1050K | $8.00 / $40.00 | $2.52 / $12.60 | 68.5% |
| [GPT-6.2 Astra Pro](https://martllm.com/models/openai/gpt-6.2-astra-pro) | openai | 1050K | $8.00 / $40.00 | $8.32 / $41.58 | -4–-3.9% |
| [GPT-5.5](https://martllm.com/models/openai/gpt-5.5) | openai | 1000K | $5.00 / $30.00 | $1.94 / $11.65 | 61.2% |
| [GPT-5.6 Sol](https://martllm.com/models/openai/gpt-5.6-sol) | openai | 1050K | $4.00 / $20.00 | $1.34 / $6.72 | 66.4% |
| [GPT-5.6 Sol Pro](https://martllm.com/models/openai/gpt-5.6-sol-pro) | openai | 1050K | $4.00 / $20.00 | $4.12 / $20.58 | -2.9% |
| [GPT-5.4](https://martllm.com/models/openai/gpt-5.4) | openai | 1000K | $2.50 / $15.00 | $0.945 / $5.67 | 62.2% |
| [GPT-5.2](https://martllm.com/models/openai/gpt-5.2) | openai | 256K | $1.75 / $14.00 | $0.6615 / $5.29 | 62.2% |
| [GPT-5.2 Codex](https://martllm.com/models/openai/gpt-5.2-codex) | openai | 256K | $1.75 / $14.00 | $1.84 / $14.70 | -5% |
| [GPT-5.3 Codex](https://martllm.com/models/openai/gpt-5.3-codex) | openai | 400K | $1.75 / $14.00 | $0.9555 / $7.64 | 45.4% |
| [GPT-5.6 Terra](https://martllm.com/models/openai/gpt-5.6-terra) | openai | 1050K | $2.00 / $12.00 | $0.777 / $4.66 | 61.1% |
| [GPT-5.6 Terra Pro](https://martllm.com/models/openai/gpt-5.6-terra-pro) | openai | 1050K | $2.00 / $12.00 | $2.10 / $12.60 | -5% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | openai | 128K | $2.50 / $10.00 | $0.3675 / $1.47 | 85.3% |
| [GPT-4o (2024-08-06)](https://martllm.com/models/openai/gpt-4o-2024-08-06) | openai | 128K | $2.50 / $10.00 | $2.10 / $8.40 | 16% |
| [GPT-4o (2024-11-20)](https://martllm.com/models/openai/gpt-4o-2024-11-20) | openai | 128K | $2.50 / $10.00 | $1.41 / $5.63 | 43.6% |
| [GPT-5](https://martllm.com/models/openai/gpt-5) | openai | 400K | $1.25 / $10.00 | $0.945 / $7.56 | 24.4% |
| [GPT-5.1](https://martllm.com/models/openai/gpt-5.1) | openai | 400K | $1.25 / $10.00 | $0.945 / $7.56 | 24.4% |
| [GPT-6 Sol](https://martllm.com/models/openai/gpt-6-sol) | openai | 1050K | $2.00 / $10.00 | $0.756 / $3.78 | 62.2% |
| [GPT-6 Sol Pro](https://martllm.com/models/openai/gpt-6-sol-pro) | openai | 1050K | $2.00 / $10.00 | $2.10 / $10.50 | -5% |
| [GPT-6.1 Sol](https://martllm.com/models/openai/gpt-6.1-sol) | openai | 1050K | $2.00 / $10.00 | $0.735 / $3.67 | 63.3% |
| [OpenAI: GPT-6.1 Sol Pro](https://martllm.com/models/openai/gpt-6.1-sol-pro) | openai | 1050K | $2.00 / $10.00 | $2.10 / $10.50 | -5% |
| [GPT-6.2 Sol](https://martllm.com/models/openai/gpt-6.2-sol) | openai | 1050K | $2.00 / $10.00 | $0.819 / $4.09 | 59.1% |
| [GPT-6.2 Sol Pro](https://martllm.com/models/openai/gpt-6.2-sol-pro) | openai | 1050K | $2.00 / $10.00 | $2.08 / $10.39 | -4–-3.9% |
| [GPT-4.1](https://martllm.com/models/openai/gpt-4.1) | openai | 1047K | $2.00 / $8.00 | $1.51 / $6.05 | 24.4% |
| [o3](https://martllm.com/models/openai/o3) | openai | 200K | $2.00 / $8.00 | $1.51 / $6.05 | 24.4% |
| [OpenAI: GPT-6.1 Terra](https://martllm.com/models/openai/gpt-6.1-terra) | openai | 1050K | $1.00 / $5.00 | $0.3675 / $1.84 | 63.3% |
| [OpenAI: GPT-6.1 Terra Pro](https://martllm.com/models/openai/gpt-6.1-terra-pro) | openai | 1050K | $1.00 / $5.00 | $1.57 / $7.88 | -57.5% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | openai | 400K | $0.75 / $4.50 | $0.1811 / $1.09 | 75.8% |
| [GPT 5 Mini](https://martllm.com/models/openai/gpt-5-mini) | openai | 400K | $0.25 / $2.00 | $0.05513 / $0.441 | 78% |
| [GPT-4.1 mini](https://martllm.com/models/openai/gpt-4.1-mini) | openai | 1047K | $0.40 / $1.60 | $0.3024 / $1.21 | 24.4% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | openai | 400K | $0.20 / $1.25 | $0.1617 / $1.01 | 19.1% |
| [GPT-5.6 Luna](https://martllm.com/models/openai/gpt-5.6-luna) | openai | 1050K | $0.20 / $1.20 | $0.0609 / $0.3654 | 69.5% |
| [GPT-5.6 Luna Pro](https://martllm.com/models/openai/gpt-5.6-luna-pro) | openai | 1050K | $0.20 / $1.20 | $0.2079 / $1.25 | -4–-3.9% |
| [GPT OSS 120B](https://martllm.com/models/openai/e2ee-gpt-oss-120b-p) | openai | 128K | $0.13 / $0.65 | $0.1365 / $0.6825 | -5% |
| [GPT-4o Mini](https://martllm.com/models/openai/gpt-4o-mini) | openai | 128K | $0.15 / $0.60 | $0.0504 / $0.2016 | 66.4% |
| [GPT-4o-mini (2024-07-18)](https://martllm.com/models/openai/gpt-4o-mini-2024-07-18) | openai | 128K | $0.15 / $0.60 | $0.08453 / $0.3381 | 43.6% |
| [GPT OSS Safeguard 120B](https://martllm.com/models/openai/gpt-oss-safeguard-120b) | openai | 128K | $0.15 / $0.60 | $0.03938 / $0.1575 | 73.8% |
| [GPT-6 Luna](https://martllm.com/models/openai/gpt-6-luna) | openai | 1050K | $0.10 / $0.50 | $0.0357 / $0.1785 | 64.3% |
| [GPT-6 Luna Pro](https://martllm.com/models/openai/gpt-6-luna-pro) | openai | 1050K | $0.10 / $0.50 | $0.105 / $0.525 | -5% |
| [GPT-4.1 nano](https://martllm.com/models/openai/gpt-4.1-nano) | openai | 1047K | $0.10 / $0.40 | $0.084 / $0.336 | 16% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | openai | 400K | $0.05 / $0.40 | $0.01523 / $0.1218 | 69.5% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | openai | 128K | $0.07 / $0.30 | $0.01323 / $0.0567 | 81.1% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | openai | 128K | $0.0725 / $0.25 | $0.008374 / $0.02888 | 88.4% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | openai | 128K | $0.03 / $0.15 | $0.000315 / $0.001575 | 99% |
| [Claude Fable 5](https://martllm.com/models/anthropic/claude-fable-5) | anthropic | 1000K | $10.00 / $50.00 | $5.67 / $28.35 | 43.3% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | anthropic | 1000K | $10.00 / $50.00 | $5.36 / $26.77 | 46.4–46.5% |
| [Claude Opus 5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5-fast) | anthropic | 1000K | $10.00 / $50.00 | $8.29 / $41.48 | 17% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | anthropic | 1000K | $8.00 / $40.00 | $4.37 / $21.84 | 45.4% |
| [Claude Opus 4.5](https://martllm.com/models/anthropic/claude-opus-4.5) | anthropic | 198K | $5.00 / $25.00 | $4.09 / $20.48 | 18.1% |
| [Claude Opus 4.6](https://martllm.com/models/anthropic/claude-opus-4.6) | anthropic | 1000K | $5.00 / $25.00 | $4.20 / $21.00 | 16% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | anthropic | 1000K | $5.00 / $25.00 | $2.99 / $14.96 | 40.1% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | anthropic | 1000K | $5.00 / $25.00 | $2.89 / $14.44 | 42.2% |
| [Claude Opus 5](https://martllm.com/models/anthropic/claude-opus-5) | anthropic | 1000K | $5.00 / $25.00 | $2.78 / $13.91 | 44.4% |
| [Claude Opus 5.5](https://martllm.com/models/anthropic/claude-opus-5.5) | anthropic | 1000K | $4.00 / $20.00 | $2.06 / $10.29 | 48.6% |
| [Claude Sonnet 4.5](https://martllm.com/models/anthropic/claude-sonnet-4.5) | anthropic | 198K | $3.00 / $15.00 | $2.58 / $12.91 | 13.9% |
| [Claude Sonnet 4.6](https://martllm.com/models/anthropic/claude-sonnet-4.6) | anthropic | 1000K | $3.00 / $15.00 | $1.92 / $9.61 | 36% |
| [Claude Sonnet 5](https://martllm.com/models/anthropic/claude-sonnet-5) | anthropic | 1000K | $2.00 / $10.00 | $1.20 / $5.99 | 40.1% |
| [Claude Sonnet 5.5](https://martllm.com/models/anthropic/claude-sonnet-5.5) | anthropic | 1000K | $2.00 / $10.00 | $1.01 / $5.04 | 49.6% |
| [Claude Haiku 4.5](https://martllm.com/models/anthropic/claude-haiku-4.5) | anthropic | 200K | $1.00 / $5.00 | $0.6195 / $3.10 | 38% |
| [Claude Haiku 5.5](https://martllm.com/models/anthropic/claude-haiku-5.5) | anthropic | 1000K | $0.10 / $0.50 | $0.0798 / $0.399 | 20.2% |
| [Google: Gemini 4 Neon](https://martllm.com/models/google/gemini-4-neon) | google | 1048K | $3.00 / $15.00 | $1.32 / $6.62 | 55.9% |
| [Gemini 3.1 Pro Preview](https://martllm.com/models/google/gemini-3.1-pro-preview) | google | 1000K | $2.00 / $12.00 | $0.546 / $3.28 | 72.7% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | google | 1048K | $2.00 / $10.00 | $0.315 / $1.57 | 84.2% |
| [Google: Gemini 4 Carbon](https://martllm.com/models/google/gemini-4-carbon) | google | 1048K | $2.00 / $10.00 | $0.735 / $3.67 | 63.3% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | google | 1048K | $1.50 / $9.00 | $1.05 / $6.30 | 30% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | google | 1048K | $1.50 / $7.50 | $0.2993 / $1.50 | 80% |
| [Gemini 3.6 Flash](https://martllm.com/models/google/gemini-3-6-flash) | google | 1000K | $0.75 / $3.75 | $0.3937 / $1.97 | 47.5% |
| [Gemini 3.7 Flash](https://martllm.com/models/google/gemini-3.7-flash) | google | 1048K | $0.75 / $3.75 | $0.6375 / $3.19 | 15% |
| [Gemini 3.8 Flash](https://martllm.com/models/google/gemini-3.8-flash) | google | 1048K | $0.75 / $3.75 | $0.126 / $0.63 | 83.2% |
| [Gemini 3 Flash](https://martllm.com/models/google/gemini-3-flash) | google | 1000K | $0.50 / $3.00 | $0.42 / $2.52 | 16% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | google | 256K | $0.50 / $3.00 | $0.1943 / $1.17 | 61.1% |
| [Gemini 3.1 Flash Lite](https://martllm.com/models/google/gemini-3.1-flash-lite) | google | 1048K | $0.25 / $1.50 | $0.21 / $1.26 | 16% |
| [Gemini 3.1 Flash Lite Preview](https://martllm.com/models/google/gemini-3.1-flash-lite-preview) | google | 1048K | $0.25 / $1.50 | $0.189 / $1.13 | 24.4% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | google | 256K | $0.12 / $0.36 | $0.02142 / $0.06426 | 82.2% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | google | 262K | $0.12 / $0.36 | $0.08442 / $0.2533 | 29.6% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | google | 262K | $0.10 / $0.30 | $0.0189 / $0.0567 | 81.1% |
| [Gemma 3 27B](https://martllm.com/models/google/gemma-3-27b-it) | google | 40K | $0.08 / $0.20 | $0.02772 / $0.0693 | 65.3% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | google | 128K | $0.0625 / $0.1875 | $0.04791 / $0.1437 | 23.3–23.4% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | google | 128K | $0.045 / $0.09 | $0.04725 / $0.0945 | -5% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | google | 128K | $0.04 / $0.08 | $0.0105 / $0.021 | 73.8% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | deepseek | 1048K | $1.32 / $3.96 | $0.2218 / $0.6653 | 83.2% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | deepseek | 1000K | $1.36 / $2.72 | $0.3707 / $0.7415 | 72.7% |
| [R1 0528](https://martllm.com/models/deepseek/deepseek-r1-0528) | deepseek | 163K | $0.571 / $2.29 | $0.3856 / $1.16 | 32.5–49.1% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-v3.1) | deepseek | 128K | $0.27 / $1.00 | $0.06807 / $0.2521 | 74.8% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | deepseek | 1048K | $0.21 / $0.78 | $0.1345 / $0.4996 | 35.9–36% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | deepseek | 1048K | $0.1575 / $0.71 | $0.01488 / $0.0671 | 90.5% |
| [DeepSeek V4 Flash 0731 Fast](https://martllm.com/models/deepseek/deepseek-v4-flash-0731-fast) | deepseek | 1000K | $0.35 / $0.70 | $0.2903 / $0.5806 | 17% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | deepseek | 1048K | $0.2156 / $0.6468 | $0.2264 / $0.6791 | -5% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | deepseek | 160K | $0.26 / $0.38 | $0.06279 / $0.09177 | 75.8% |
| [DeepSeek V4 Flash E2EE](https://martllm.com/models/deepseek/e2ee-deepseek-v4-flash) | deepseek | 1000K | $0.182 / $0.373 | $0.1911 / $0.3916 | -5% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | deepseek | 1000K | $0.1325 / $0.275 | $0.07095 / $0.1473 | 46.4% |
| [DeepSeek V4 Flash 0731](https://martllm.com/models/deepseek/deepseek-v4-flash-0731) | deepseek | 1048K | $0.13 / $0.26 | $0.06552 / $0.131 | 49.6% |
| [Grok 4.5](https://martllm.com/models/x-ai/grok-4.5) | x-ai | 500K | $2.27 / $6.80 | $1.12 / $3.36 | 50.6% |
| [Grok 4.6](https://martllm.com/models/x-ai/grok-4.6) | x-ai | 500K | $2.27 / $6.80 | $2.17 / $6.50 | 4.4% |
| [Grok 4.7](https://martllm.com/models/x-ai/grok-4.7) | x-ai | 500K | $2.00 / $6.00 | $1.51 / $4.54 | 24.4% |
| [Grok 4.20 Beta](https://martllm.com/models/x-ai/grok-4.20-beta) | x-ai | 2000K | $1.42 / $2.83 | $0.6411 / $1.28 | 54.9% |
| [Grok 4.20 Multi-Agent Beta](https://martllm.com/models/x-ai/grok-4.20-multi-agent-beta) | x-ai | 2000K | $1.42 / $2.83 | $1.03 / $2.05 | 27.5% |
| [Grok 4.3](https://martllm.com/models/x-ai/grok-4.3) | x-ai | 1000K | $1.42 / $2.83 | $0.4622 / $0.9212 | 67.5% |
| [Grok 4.20 Multi-Agent](https://martllm.com/models/x-ai/grok-4.20-multi-agent) | x-ai | 2000K | $1.25 / $2.50 | $0.8002 / $1.59 | 36–36.2% |
| [Qwen: Qwen3.8 Max Prime](https://martllm.com/models/qwen/qwen3.8-max-prime) | qwen | 1000K | $4.00 / $12.00 | $4.20 / $12.60 | -5% |
| [Qwen3.7 Max](https://martllm.com/models/qwen/qwen3.7-max) | qwen | 256K | $2.70 / $8.05 | $2.64 / $7.86 | 2.3–2.4% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | qwen | 1000K | $2.00 / $6.00 | $1.74 / $5.23 | 12.8% |
| [Qwen3.8 2.4T A95B](https://martllm.com/models/qwen/qwen3.8-2.4t-a95b) | qwen | 1000K | $2.00 / $6.00 | $1.39 / $4.16 | 30.7% |
| [Qwen: Qwen3.8 Max (0902)](https://martllm.com/models/qwen/qwen3.8-max-0902) | qwen | 1000K | $2.00 / $6.00 | $0.42 / $1.26 | 79% |
| [Qwen 4 Max](https://martllm.com/models/qwen/qwen4-max) | qwen | 1000K | $1.43 / $4.28 | $0.3741 / $1.12 | 73.7% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | qwen | 128K | $0.50 / $3.60 | $0.294 / $2.12 | 41.2% |
| [Qwen 3 235B A22B Thinking 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-thinking-2507) | qwen | 128K | $0.45 / $3.50 | $0.2599 / $2.02 | 42.2% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | qwen | 256K | $0.32 / $3.20 | $0.04368 / $0.4368 | 86.3–86.4% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | qwen | 262K | $0.20 / $2.00 | $0.0042 / $0.042 | 97.9% |
| [Qwen 3.7 Plus](https://martllm.com/models/qwen/qwen3.7-plus) | qwen | 256K | $0.50 / $2.00 | $0.4988 / $2.00 | 0.2% |
| [Qwen 3.6 Plus](https://martllm.com/models/qwen/qwen3.6-plus) | qwen | 1000K | $0.325 / $1.95 | $0.2161 / $1.30 | 33.5% |
| [Qwen3 VL 235B A22B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-instruct) | qwen | 256K | $0.21 / $1.90 | $0.04851 / $0.4389 | 76.9% |
| [Qwen3 VL 235B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-thinking) | qwen | 256K | $0.21 / $1.90 | $0.2007 / $1.82 | 4.4% |
| [Qwen 3 Coder 480B Turbo](https://martllm.com/models/qwen/qwen3-coder-turbo) | qwen | 256K | $0.35 / $1.50 | $0.3528 / $1.51 | -0.8% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | qwen | 256K | $0.325 / $1.25 | $0.04436 / $0.1706 | 86.3% |
| [Qwen 3.6 35B A3B (E2EE)](https://martllm.com/models/qwen/e2ee-qwen3-6-35b-a3b) | qwen | 128K | $0.182 / $1.18 | $0.1815 / $1.18 | 0.2–0.3% |
| [Qwen3.6 Flash](https://martllm.com/models/qwen/qwen3.6-flash) | qwen | 1000K | $0.1875 / $1.12 | $0.1296 / $0.7775 | 30.9% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | qwen | 256K | $0.095 / $1.10 | $0.02372 / $0.2747 | 75% |
| [Qwen 3.6 35B A3B](https://martllm.com/models/qwen/qwen3-6-35b-a3b) | qwen | 262K | $0.10 / $1.00 | $0.063 / $0.63 | 37% |
| [Qwen 3.5 35B A3B](https://martllm.com/models/qwen/qwen3.5-35b-a3b) | qwen | 256K | $0.15 / $1.00 | $0.148 / $0.987 | 1.3% |
| [Qwen3 VL 30B A3B](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-thinking) | qwen | 128K | $0.25 / $0.90 | $0.2625 / $0.945 | -5% |
| [Qwen3 Coder Next](https://martllm.com/models/qwen/qwen3-coder-next) | qwen | 256K | $0.12 / $0.80 | $0.03137 / $0.2092 | 73.9% |
| [Qwen 3 235B A22B Instruct 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-2507) | qwen | 128K | $0.135 / $0.75 | $0.02551 / $0.1417 | 81.1% |
| [Qwen3 30B A3B](https://martllm.com/models/qwen/qwen3-30b-a3b) | qwen | 256K | $0.12 / $0.50 | $0.09954 / $0.4148 | 17% |
| [Qwen3.8 Flash](https://martllm.com/models/qwen/qwen3.8-flash) | qwen | 1000K | $0.15 / $0.47 | $0.02993 / $0.09377 | 80% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | qwen | 1000K | $0.15 / $0.47 | $0.0252 / $0.07896 | 83.2% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | qwen | 256K | $0.11 / $0.44 | $0.0127 / $0.05082 | 88.5% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | qwen | 32K | $0.12 / $0.40 | $0.021 / $0.0735 | 81.6–82.5% |
| [Qwen 2.5 7B](https://martllm.com/models/qwen/e2ee-qwen-2-5-7b-p) | qwen | 32K | $0.05 / $0.13 | $0.04673 / $0.1215 | 6.6% |
| [Qwen: Qwen3.7 Flash](https://martllm.com/models/qwen/qwen3.7-flash) | qwen | 1000K | $0.03 / $0.13 | $0.01921 / $0.08327 | 35.9–36% |
| [Kimi K3 Fast](https://martllm.com/models/moonshotai/kimi-k3-fast-api) | moonshotai | 1000K | $4.50 / $22.50 | $4.49 / $22.44 | 0.2–0.3% |
| [Kimi K3](https://martllm.com/models/moonshotai/kimi-k3) | moonshotai | 1000K | $3.00 / $15.00 | $0.2764 / $1.42 | 90.5–90.8% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | moonshotai | 1048K | $2.00 / $10.00 | $0.651 / $3.25 | 67.5% |
| [Kimi K2.7 Code](https://martllm.com/models/moonshotai/kimi-k2.7-code) | moonshotai | 262K | $0.75 / $3.50 | $0.2284 / $1.07 | 69.5% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | moonshotai | 256K | $0.70 / $3.42 | $0.2132 / $1.04 | 69.5% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | moonshotai | 256K | $0.55 / $2.75 | $0.1559 / $0.7796 | 71.6–71.7% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | moonshotai | 256K | $0.60 / $2.50 | $0.1569 / $0.6536 | 73.9% |
| [Kimi K2](https://martllm.com/models/moonshotai/kimi-k2) | moonshotai | 256K | $0.57 / $2.30 | $0.6284 / $2.54 | -10.3% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | z-ai | 524K | $1.75 / $5.75 | $1.82 / $5.98 | -4% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | z-ai | 1000K | $1.68 / $5.28 | $0.03528 / $0.1109 | 97.9% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | z-ai | 1048K | $1.40 / $4.40 | $0.1911 / $0.6006 | 86.3–86.4% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | z-ai | 1000K | $1.40 / $4.40 | $0.02425 / $0.09013 | 98–98.3% |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | z-ai | 1000K | $1.16 / $4.29 | $1.08 / $4.01 | 6.5–6.6% |
| [GLM-5 Turbo](https://martllm.com/models/z-ai/glm-5-turbo) | z-ai | 200K | $1.20 / $4.00 | $0.9198 / $3.07 | 23.4% |
| [GLM 5V Turbo](https://martllm.com/models/z-ai/glm-5v-turbo) | z-ai | 200K | $1.20 / $4.00 | $1.20 / $3.99 | 0.2% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | z-ai | 200K | $1.26 / $3.96 | $0.462 / $1.74 | 56–63.3% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | z-ai | 200K | $1.26 / $3.96 | $0.3175 / $0.9979 | 74.8% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | z-ai | 198K | $0.95 / $2.55 | $0.5486 / $1.47 | 42.2% |
| [GLM 4.5](https://martllm.com/models/z-ai/glm-4.5) | z-ai | 128K | $0.60 / $2.20 | $0.5922 / $2.17 | 1.3% |
| [GLM-4.6](https://martllm.com/models/z-ai/glm-4.6) | z-ai | 198K | $0.43 / $1.75 | $0.1354 / $0.5513 | 68.5% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | z-ai | 128K | $0.40 / $1.75 | $0.2436 / $1.07 | 39.1% |
| [Z.ai: GLM 5.3 FlashX](https://martllm.com/models/z-ai/glm-5.3-flashx) | z-ai | 1048K | $0.37 / $1.25 | $0.2603 / $0.8794 | 29.6% |
| [Z.ai: GLM 5.3 FlashX Legal](https://martllm.com/models/z-ai/glm-5.3-flashx-legal) | z-ai | 1048K | $0.37 / $1.25 | $0.2914 / $0.9844 | 21.3% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | z-ai | 128K | $0.17 / $0.98 | $0.1053 / $0.6071 | 38–38.1% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | z-ai | 198K | $0.0605 / $0.40 | $0.01398 / $0.0924 | 76.9% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | z-ai | 1048K | $0.12 / $0.40 | $0.02898 / $0.0966 | 75.8% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | mistralai | 128K | $2.00 / $6.00 | $0.315 / $0.945 | 84.2% |
| [Mistral: Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4-0) | mistralai | 524K | $0.735 / $2.21 | $0.1235 / $0.3704 | 83.2% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | mistralai | 256K | $0.40 / $2.00 | $0.0504 / $0.252 | 87.4% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | mistralai | 256K | $0.525 / $1.57 | $0.1307 / $0.3921 | 75.1% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | mistralai | 128K | $0.50 / $1.50 | $0.08925 / $0.2677 | 82.2% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-4) | mistralai | 256K | $0.165 / $0.66 | $0.1732 / $0.693 | -5% |
| [Voxtral Small 24B 2507](https://martllm.com/models/mistralai/voxtral-small-24b-2507) | mistralai | 32K | $0.105 / $0.315 | $0.08489 / $0.2547 | 19.1% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | mistralai | 128K | $0.21 / $0.21 | $0.08379 / $0.08379 | 60.1% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | mistralai | 256K | $0.075 / $0.20 | $0.07166 / $0.1911 | 4.4–4.5% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | mistralai | 128K | $0.1575 / $0.1575 | $0.06615 / $0.06615 | 58% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | mistralai | 128K | $0.105 / $0.105 | $0.02756 / $0.02756 | 73.7% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | mistralai | 32K | $0.04 / $0.04 | $0.0084 / $0.0084 | 79% |
| [Meta: Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder) | meta-llama | 1048K | $4.00 / $20.00 | $2.06 / $10.29 | 48.6% |
| [Meta: Muse Spark 1.1](https://martllm.com/models/meta-llama/muse-spark-1.1) | meta-llama | 1048K | $1.25 / $4.25 | $0.6038 / $2.05 | 51.7% |
| [Meta: Muse Spark 1.2](https://martllm.com/models/meta-llama/muse-spark-1.2) | meta-llama | 1048K | $1.25 / $4.25 | $0.6694 / $2.28 | 46.4–46.5% |
| [Meta: Muse Spark 1.3](https://martllm.com/models/meta-llama/muse-spark-1.3) | meta-llama | 1048K | $1.25 / $4.25 | $0.6169 / $2.10 | 50.6–50.7% |
| [Meta: Muse Spark Open](https://martllm.com/models/meta-llama/muse-spark-open) | meta-llama | 1048K | $1.25 / $4.25 | $1.18 / $4.02 | 5.5% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | meta-llama | 131K | $0.325 / $1.35 | $0.4095 / $1.70 | -26% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | meta-llama | 128K | $0.293 / $0.71 | $0.06153 / $0.1491 | 79% |
| [Meta: Muse Ember](https://martllm.com/models/meta-llama/muse-ember) | meta-llama | 1048K | $0.10 / $0.50 | $0.105 / $0.525 | -5% |
| [Llama 3.2 3B](https://martllm.com/models/meta-llama/llama-3.2-3b-instruct) | meta-llama | 128K | $0.05 / $0.33 | $0.0504 / $0.3326 | -0.8% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.105 / $0.21 | -5% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.0861 / $0.1722 | 13.9% |

</details>

### Image models (per image)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Image Converter](https://martllm.com/models/studio/image-converter) | – | $0.0005 / image | – |
| [FeyNoBg Background Remover](https://martllm.com/models/studio/feynobg) | – | $0.001 / image | – |
| [Image Face Blur](https://martllm.com/models/studio/image-face-blur) | – | $0.001 / image | – |
| [Recraft V4.1 Flash](https://martllm.com/models/recraft/recraft-v4-1-flash) | $0.007 / image | $0.002352 / image | 66.4% |
| [Recraft V4.1 Flash V2](https://martllm.com/models/recraft/recraft-v4-1-flash-v2) | $0.007 / image | $0.002352 / image | 66.4% |
| [Real-ESRGAN](https://martllm.com/models/xinntao/real-esrgan) | – | $0.0024 / image | – |
| [FLUX.1 [schnell]](https://martllm.com/models/black-forest-labs/flux-schnell) | – | $0.002856 / image | – |
| [Image 01 Image To Image](https://martllm.com/models/minimax/image-01-image-to-image) | – | $0.003332 / image | – |
| [MiniMax Image-01](https://martllm.com/models/minimax/image-01-text-to-image) | – | $0.003332 / image | – |
| [Recraft Crisp Upscale](https://martllm.com/models/recraft/recraft-crisp-upscale) | – | $0.004 / image | – |

### Image models (per megapixel)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [FLUX.2 Klein 4B](https://martllm.com/models/black-forest-labs/flux.2-klein-4b) | – | $0.015 / megapixel | – |
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
| [Cosmos Predict (image-to-video)](https://martllm.com/models/nvidia/cosmos-predict-image-to-video) | – | $0.8971 / video | – |

### Music models

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Audio Converter to MP3](https://martllm.com/models/studio/audio-converter-mp3) | – | $0.0001 / sec | – |
| [ACE-Step](https://martllm.com/models/ace-step/ace-step) | – | $0.0002 / sec | – |
| [Vocal Isolator](https://martllm.com/models/studio/vocal-isolator) | – | $0.001 / sec | – |
| [MMAudio V2 Text-to-Audio (Venice)](https://martllm.com/models/venice/mmaudio-v2-text-to-audio) | – | $0.00103 / sec | – |
| [Seed Audio 1.0](https://martllm.com/models/bytedance/seed-audio-1-0) | $0.002875 / sec | $0.001771 / sec | 38.4% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | $0.0023 / sec | $0.001804 / sec | 21.6% |
| [ElevenLabs Audio Isolation](https://martllm.com/models/elevenlabs/elevenlabs-audio-isolation) | – | $0.001833 / sec | – |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-sound-effects-v1-0) | $0.00207 / sec | $0.001855 / sec | 10.4% |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | $0.002875 / sec | $0.001932 / sec | 32.8% |
| [ElevenLabs Sound Effects v3](https://martllm.com/models/elevenlabs/elevenlabs-sound-effects-v3) | – | $0.002 / sec | – |

### Speech models

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Kokoro Text to Speech (Venice)](https://martllm.com/models/venice/kokoro-tts) | $0.0035 / 1K chars | $0.003136 / 1K chars | 10.4% |
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | – | $0.003881 / 1K chars | – |
| [HeyGen Voice Turbo](https://martllm.com/models/heygen/heygen-voice-turbo) | – | $0.005 / 1K chars | – |
| [Inworld 1.5 Max TTS](https://martllm.com/models/inworld/tts-inworld-1-5-max) | $0.0125 / 1K chars | $0.0112 / 1K chars | 10.4% |
| [Gemini 2.5 Flash TTS](https://martllm.com/models/google/gemini-2-5-flash-tts) | – | $0.02 / 1K chars | – |
| [xAI v1 TTS](https://martllm.com/models/x-ai/tts-xai-v1) | – | $0.02079 / 1K chars | – |
| [Inworld TTS 1.5 Mini](https://martllm.com/models/inworld/tts-inworld-1-5-mini) | – | $0.03 / 1K chars | – |
| [Chatterbox TTS](https://martllm.com/models/resemble-ai/chatterbox-tts) | – | $0.03 / 1K chars | – |
| [HeyGen Voice](https://martllm.com/models/heygen/heygen-voice) | – | $0.035 / 1K chars | – |
| [Eleven Flash v2](https://martllm.com/models/elevenlabs/eleven-flash-v2) | – | $0.04 / 1K chars | – |

## Prices under review

The catalog's official price for these 33 models failed a sanity check (see `list_price_review_reason`), so it is left out, with no % below list, until it is checked against the maker's own page. The MartLLM price is still listed.

| Model | Category | Why |
|---|---|---|
| [FLUX.1 [schnell]](https://martllm.com/models/black-forest-labs/flux-schnell) | image | more than 10x off the median image price per image |
| [Image 01 Image To Image](https://martllm.com/models/minimax/image-01-image-to-image) | image | more than 10x off the median image price per image |
| [MiniMax Image-01](https://martllm.com/models/minimax/image-01-text-to-image) | image | more than 10x off the median image price per image |
| [Hunyuan Image 3 Instruct Edit](https://martllm.com/models/tencent/hunyuan-image-3-instruct-edit) | image | more than 10x off the median image price per image |
| [Hunyuan Image 3.0 Instruct](https://martllm.com/models/tencent/hunyuan-image-3-instruct-text-to-image) | image | more than 10x off the median image price per image |
| [Wan 2.2 5B (text-to-video)](https://martllm.com/models/wan/wan-2-2-5b-text-to-video) | video | more than 10x off the median video price per second |
| [Molmo 2 Image Captioner](https://martllm.com/models/allenai/molmo-2-image-captioner) | other | more than 10x off the median other price per job |
| [Molmo 2 Image Content Moderator](https://martllm.com/models/allenai/molmo-2-image-content-moderator) | other | more than 10x off the median other price per job |
| [Molmo 2 Image Q&A](https://martllm.com/models/allenai/molmo-2-image-qa) | other | more than 10x off the median other price per job |
| [Molmo 2 Prompt Optimizer](https://martllm.com/models/allenai/molmo-2-prompt-optimizer) | other | more than 10x off the median other price per job |
| [Molmo 2 Text Content Moderator](https://martllm.com/models/allenai/molmo-2-text-content-moderator) | other | more than 10x off the median other price per job |
| [Molmo 2 Video Content Moderator](https://martllm.com/models/allenai/molmo-2-video-content-moderator) | other | more than 10x off the median other price per job |
| [PaddleOCR-VL](https://martllm.com/models/baidu/paddleocr-vl) | other | more than 10x off the median other price per job |
| [SAM 3 Image RLE](https://martllm.com/models/meta/sam3-image-rle) | other | more than 10x off the median other price per job |
| [MiniMax Lyrics](https://martllm.com/models/minimax/minimax-lyrics) | other | more than 10x off the median other price per job |
| [Moondream 3 Preview Caption](https://martllm.com/models/moondream/moondream3-preview-caption) | other | more than 10x off the median other price per job |
| [Moondream 3 Preview Detect](https://martllm.com/models/moondream/moondream3-preview-detect) | other | more than 10x off the median other price per job |
| [Moondream 3 Preview Point](https://martllm.com/models/moondream/moondream3-preview-point) | other | more than 10x off the median other price per job |
| [Moondream 3 Preview Query](https://martllm.com/models/moondream/moondream3-preview-query) | other | more than 10x off the median other price per job |
| [Mureka Create Upload ID](https://martllm.com/models/mureka/mureka-create-upload-id) | other | more than 10x off the median other price per job |
| [Mureka Extend Lyrics](https://martllm.com/models/mureka/mureka-extend-lyrics) | other | more than 10x off the median other price per job |
| [Mureka Lyrics](https://martllm.com/models/mureka/mureka-lyrics) | other | more than 10x off the median other price per job |
| [Mureka V7.6 Recognize Song](https://martllm.com/models/mureka/mureka-v7-6-recognize-song) | other | more than 10x off the median other price per job |
| [Mureka Vocal Clone](https://martllm.com/models/mureka/mureka-vocal-clone) | other | more than 10x off the median other price per job |
| [MiniCPM-V 4.5 Image](https://martllm.com/models/openbmb/minicpm-v-image) | other | more than 10x off the median other price per job |
| [MiniCPM-V 4.5 Video](https://martllm.com/models/openbmb/minicpm-v-video) | other | more than 10x off the median other price per job |
| [Any LLM](https://martllm.com/models/studio/any-llm) | other | more than 10x off the median other price per job |
| [Content Moderator Image](https://martllm.com/models/studio/content-moderator-image) | other | more than 10x off the median other price per job |
| [Content Moderator Text](https://martllm.com/models/studio/content-moderator-text) | other | more than 10x off the median other price per job |
| [Image Captioner](https://martllm.com/models/studio/image-captioner) | other | more than 10x off the median other price per job |
| [Prompt Optimizer](https://martllm.com/models/studio/prompt-optimizer) | other | more than 10x off the median other price per job |
| [Wan 2.2 Image-to-Video LoRA Trainer](https://martllm.com/models/studio/wan-2-2-i2v-lora-trainer) | other | more than 10x off the median other price per step |
| [Zonos 2 Voice Clone](https://martllm.com/models/zyphra/zonos-2) | other | more than 10x off the median other price per job |

## Biggest drops this week (2026-11-21 to 2026-11-28)

From MartLLM's daily catalog snapshots (`GET /api/v1/public/price-changes`). Text: $ per 1M input / output tokens, sorted by the larger of the two moves.

### Official list price cuts

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Wan 2.2 A14B Text-to-Video](https://martllm.com/models/wan/wan-2-2-a14b-text-to-video) | video | $0.20 / sec | $0.04 / sec | −80% |
| [Topaz Video Upscale](https://martllm.com/models/topaz-labs/topaz-video-upscale) | video | $0.15 / sec | $0.0448 / sec | −70% |
| [Runway Gen-4 Aleph](https://martllm.com/models/runway/runway-gen4-aleph) | video | $0.50 / sec | $0.25 / sec | −50% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.30 / $1.20 | $0.1575 / $0.71 | in −48% / out −41% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.30 / $1.20 | $0.21 / $0.78 | in −30% / out −35% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $1.32 / $3.96 | $1.36 / $2.72 | in +3% / out −31% |
| [NVIDIA Nemotron 3 Ultra 550B](https://martllm.com/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.625 / $3.12 | $0.50 / $2.20 | in −20% / out −30% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | text | $0.27 / $0.48 | $0.26 / $0.38 | in −4% / out −21% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | text | $0.5002 / $2.06 | $0.40 / $1.75 | in −20% / out −15% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.2695 / $0.8085 | $0.2156 / $0.6468 | −20% |

### MartLLM price drops

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [LTX 2 19B Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-19b-full-text-to-video) | video | $0.088 / sec | $0.01523 / sec | −83% |
| [GPT Image 2.5 Flare (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-flare-edit) | image | $0.0315 / image | $0.0056 / image | −82% |
| [GPT Image 2.5 Sunburst (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-sunburst-edit) | image | $0.0315 / image | $0.0056 / image | −82% |
| [GPT Image 2 (Venice)](https://martllm.com/models/venice/gpt-image-2) | image | $0.0315 / image | $0.0056 / image | −82% |
| [GPT Image 2 — Edit (Venice)](https://martllm.com/models/venice/gpt-image-2-edit) | image | $0.0315 / image | $0.0056 / image | −82% |
| [Qwen3.5 Flash](https://martllm.com/models/qwen/qwen3.5-flash) | text | $0.1029 / $0.4116 | $0.02084 / $0.08337 | −80% |
| [Qwen3.5 Plus](https://martllm.com/models/qwen/qwen3.5-plus) | text | $0.2675 / $1.61 | $0.05446 / $0.3268 | −80% |
| [Nano Banana 2 Lite (image-to-image)](https://martllm.com/models/google/nano-banana-2-lite-edit) | image | $0.05418 / image | $0.0112 / image | −79% |
| [Ideogram V4.5 (image-to-image)](https://martllm.com/models/ideogram/ideogram-v4-5-edit) | image | $0.273 / image | $0.05712 / image | −79% |
| [Nano Banana Pro (Venice)](https://martllm.com/models/venice/nano-banana-pro) | image | $0.0945 / image | $0.02022 / image | −79% |

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
