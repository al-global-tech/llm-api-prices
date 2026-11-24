# LLM API prices

*MartLLM was called UberLLM until November 2026; the `uberllm_*` column names stay as they are.*

An open, daily-updated dataset of AI API prices: the official list price of 547 text, image, video, music and speech models next to the lowest live price on the [MartLLM](https://martllm.com/models) market, how far below list that is, context length and capabilities.

**Updated:** 2026-11-24T03:17:07Z · **Models:** 238 text, 113 image, 156 video, 20 music, 11 speech, 6 transcription, 3 other · **Files:** [`prices.json`](prices.json), [`prices.csv`](prices.csv), [`CHANGELOG.md`](CHANGELOG.md), [`history/`](history/)

Disclosure: this repo is maintained by the team that runs MartLLM. The MartLLM column is our own price; the official column is the maker's price, sourced as described in [Sources](#sources). Live prices: <https://martllm.com/models>.

## Cheapest right now

Lowest MartLLM price per category among models that can be called now. Text: $ per 1M input / output tokens. Full list: [`prices.csv`](prices.csv).

### Text (chat) models

| Model | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | 128K | $0.0725 / $0.25 | $0.001523 / $0.00525 | 97.9% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | 32K | $0.04 / $0.04 | $0.0084 / $0.0084 | 79% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | 131K | $0.03 / $0.15 | $0.002835 / $0.01418 | 90.5% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | 1000K | $0.15 / $0.47 | $0.0063 / $0.01974 | 95.8% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | 128K | $0.045 / $0.09 | $0.01229 / $0.02457 | 72.7% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | 128K | $0.04 / $0.08 | $0.01302 / $0.02604 | 67.5% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | 128K | $0.105 / $0.105 | $0.02866 / $0.02866 | 72.7% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | 262K | $0.10 / $0.30 | $0.0147 / $0.0441 | 85.3% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | 128K | $0.0625 / $0.1875 | $0.01509 / $0.04528 | 75.8–75.9% |
| [NVIDIA Nemotron Nano 9B v2](https://martllm.com/models/nvidia/nemotron-nano-9b-v2) | 128K | $0.06 / $0.23 | $0.0126 / $0.0483 | 79% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | 131K | $0.07 / $0.30 | $0.01544 / $0.06615 | 78% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | 256K | $0.11 / $0.44 | $0.01848 / $0.07392 | 83.2% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | 400K | $0.05 / $0.40 | $0.0105 / $0.084 | 79% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | 128K | $0.1575 / $0.1575 | $0.04961 / $0.04961 | 68.5% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | 256K | $0.12 / $0.36 | $0.02495 / $0.07484 | 79.2% |

### Major model makers

<details><summary>OpenAI, Anthropic, Google, DeepSeek, xAI, Qwen, Moonshot, Z.ai, Mistral, Meta (169 models)</summary>

| Model | Maker | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|---|
| [GPT-5.4 Pro](https://martllm.com/models/openai/gpt-5.4-pro) | openai | 1000K | $30.00 / $180.00 | $17.64 / $105.84 | 41.2% |
| [GPT-5.5 Pro](https://martllm.com/models/openai/gpt-5.5-pro) | openai | 1000K | $30.00 / $180.00 | $21.11 / $126.63 | 29.6% |
| [GPT-6 Astra](https://martllm.com/models/openai/gpt-6-astra) | openai | 1050K | $10.00 / $50.00 | $3.57 / $17.85 | 64.3% |
| [GPT-6.2 Astra](https://martllm.com/models/openai/gpt-6.2-astra) | openai | 1050K | $8.00 / $40.00 | $4.96 / $24.78 | 38% |
| [GPT-6.2 Astra Pro](https://martllm.com/models/openai/gpt-6.2-astra-pro) | openai | 1050K | $8.00 / $40.00 | $7.98 / $39.90 | 0.2–0.3% |
| [GPT-5.5](https://martllm.com/models/openai/gpt-5.5) | openai | 1000K | $5.00 / $30.00 | $3.20 / $19.21 | 35.9–36% |
| [GPT-5.6 Sol](https://martllm.com/models/openai/gpt-5.6-sol) | openai | 1050K | $4.00 / $20.00 | $1.64 / $8.19 | 59.1% |
| [GPT-5.6 Sol Pro](https://martllm.com/models/openai/gpt-5.6-sol-pro) | openai | 1050K | $4.00 / $20.00 | $3.99 / $19.95 | 0.2–0.3% |
| [GPT-5.4](https://martllm.com/models/openai/gpt-5.4) | openai | 1000K | $2.50 / $15.00 | $1.36 / $8.19 | 45.4% |
| [GPT-5.2](https://martllm.com/models/openai/gpt-5.2) | openai | 400K | $1.75 / $14.00 | $0.9004 / $7.20 | 48.5% |
| [GPT-5.2 Codex](https://martllm.com/models/openai/gpt-5.2-codex) | openai | 256K | $1.75 / $14.00 | $1.56 / $12.49 | 10.8% |
| [GPT-5.3 Codex](https://martllm.com/models/openai/gpt-5.3-codex) | openai | 400K | $1.75 / $14.00 | $0.882 / $7.06 | 49.6% |
| [GPT-5.6 Terra](https://martllm.com/models/openai/gpt-5.6-terra) | openai | 1050K | $2.00 / $12.00 | $0.756 / $4.54 | 62.2% |
| [GPT-5.6 Terra Pro](https://martllm.com/models/openai/gpt-5.6-terra-pro) | openai | 1050K | $2.00 / $12.00 | $1.93 / $11.59 | 3.4% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | openai | 128K | $2.50 / $10.00 | $0.4988 / $2.00 | 80% |
| [GPT-6 Sol](https://martllm.com/models/openai/gpt-6-sol) | openai | 1050K | $2.00 / $10.00 | $1.09 / $5.46 | 45.4% |
| [GPT-6 Sol Pro](https://martllm.com/models/openai/gpt-6-sol-pro) | openai | 1050K | $2.00 / $10.00 | $2.02 / $10.08 | -0.8% |
| [GPT-6.1 Sol](https://martllm.com/models/openai/gpt-6.1-sol) | openai | 1050K | $2.00 / $10.00 | $0.819 / $4.09 | 59.1% |
| [OpenAI: GPT-6.1 Sol Pro](https://martllm.com/models/openai/gpt-6.1-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.93 / $9.66 | 3.4% |
| [GPT-6.2 Sol](https://martllm.com/models/openai/gpt-6.2-sol) | openai | 1050K | $2.00 / $10.00 | $1.13 / $5.67 | 43.3% |
| [GPT-6.2 Sol Pro](https://martllm.com/models/openai/gpt-6.2-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.93 / $9.66 | 3.4% |
| [OpenAI: GPT-6.1 Terra](https://martllm.com/models/openai/gpt-6.1-terra) | openai | 1050K | $1.00 / $5.00 | $0.5145 / $2.57 | 48.6% |
| [OpenAI: GPT-6.1 Terra Pro](https://martllm.com/models/openai/gpt-6.1-terra-pro) | openai | 1050K | $1.00 / $5.00 | $0.9765 / $4.88 | 2.3% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | openai | 400K | $0.75 / $4.50 | $0.189 / $1.13 | 74.8% |
| [GPT 5 Mini](https://martllm.com/models/openai/gpt-5-mini) | openai | 400K | $0.25 / $2.00 | $0.05775 / $0.462 | 76.9% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | openai | 400K | $0.20 / $1.25 | $0.0714 / $0.4462 | 64.3% |
| [GPT-5.6 Luna](https://martllm.com/models/openai/gpt-5.6-luna) | openai | 1050K | $0.20 / $1.20 | $0.105 / $0.63 | 47.5% |
| [GPT-5.6 Luna Pro](https://martllm.com/models/openai/gpt-5.6-luna-pro) | openai | 1050K | $0.20 / $1.20 | $0.1974 / $1.18 | 1.3% |
| [GPT OSS 120B](https://martllm.com/models/openai/e2ee-gpt-oss-120b-p) | openai | 128K | $0.13 / $0.65 | $0.1092 / $0.546 | 16% |
| [GPT-4o Mini](https://martllm.com/models/openai/gpt-4o-mini) | openai | 128K | $0.15 / $0.60 | $0.0504 / $0.2016 | 66.4% |
| [GPT OSS Safeguard 120B](https://martllm.com/models/openai/gpt-oss-safeguard-120b) | openai | 128K | $0.15 / $0.60 | $0.03938 / $0.1575 | 73.8% |
| [GPT-6 Luna](https://martllm.com/models/openai/gpt-6-luna) | openai | 1050K | $0.10 / $0.50 | $0.05565 / $0.2782 | 44.4% |
| [GPT-6 Luna Pro](https://martllm.com/models/openai/gpt-6-luna-pro) | openai | 1050K | $0.10 / $0.50 | $0.0945 / $0.4725 | 5.5% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | openai | 400K | $0.05 / $0.40 | $0.0105 / $0.084 | 79% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | openai | 131K | $0.07 / $0.30 | $0.01544 / $0.06615 | 78% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | openai | 128K | $0.0725 / $0.25 | $0.001523 / $0.00525 | 97.9% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | openai | 131K | $0.03 / $0.15 | $0.002835 / $0.01418 | 90.5% |
| [Claude Fable 5](https://martllm.com/models/anthropic/claude-fable-5) | anthropic | 1000K | $10.00 / $50.00 | $6.09 / $30.45 | 39.1% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | anthropic | 1000K | $10.00 / $50.00 | $6.20 / $30.98 | 38% |
| [Claude Opus 5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5-fast) | anthropic | 1000K | $10.00 / $50.00 | $6.72 / $33.60 | 32.8% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | anthropic | 1000K | $8.00 / $40.00 | $5.04 / $25.20 | 37% |
| [Claude Opus 4.5](https://martllm.com/models/anthropic/claude-opus-4.5) | anthropic | 198K | $5.00 / $25.00 | $3.15 / $15.75 | 37% |
| [Claude Opus 4.6](https://martllm.com/models/anthropic/claude-opus-4.6) | anthropic | 1000K | $5.00 / $25.00 | $2.26 / $11.29 | 54.9% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | anthropic | 1000K | $5.00 / $25.00 | $2.15 / $10.76 | 57% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | anthropic | 1000K | $5.00 / $25.00 | $2.21 / $11.03 | 55.9% |
| [Claude Opus 5](https://martllm.com/models/anthropic/claude-opus-5) | anthropic | 1000K | $5.00 / $25.00 | $2.15 / $10.76 | 57% |
| [Claude Opus 5.5](https://martllm.com/models/anthropic/claude-opus-5.5) | anthropic | 1000K | $4.00 / $20.00 | $1.89 / $9.45 | 52.8% |
| [Claude Sonnet 4.5](https://martllm.com/models/anthropic/claude-sonnet-4.5) | anthropic | 198K | $3.00 / $15.00 | $2.27 / $11.34 | 24.4% |
| [Claude Sonnet 4.6](https://martllm.com/models/anthropic/claude-sonnet-4.6) | anthropic | 1000K | $3.00 / $15.00 | $1.54 / $7.72 | 48.5% |
| [Claude Sonnet 5](https://martllm.com/models/anthropic/claude-sonnet-5) | anthropic | 1000K | $2.00 / $10.00 | $0.861 / $4.30 | 57% |
| [Claude Sonnet 5.5](https://martllm.com/models/anthropic/claude-sonnet-5.5) | anthropic | 1000K | $2.00 / $10.00 | $1.11 / $5.57 | 44.4% |
| [Claude Haiku 4.5](https://martllm.com/models/anthropic/claude-haiku-4.5) | anthropic | 200K | $1.00 / $5.00 | $1.05 / $5.25 | -5% |
| [Claude Haiku 5.5](https://martllm.com/models/anthropic/claude-haiku-5.5) | anthropic | 1000K | $0.10 / $0.50 | $0.0672 / $0.336 | 32.8% |
| [Google: Gemini 4 Neon](https://martllm.com/models/google/gemini-4-neon) | google | 1048K | $3.00 / $15.00 | $1.98 / $9.92 | 33.9% |
| [Gemini 3.1 Pro Preview](https://martllm.com/models/google/gemini-3.1-pro-preview) | google | 1000K | $2.00 / $12.00 | $0.294 / $1.76 | 85.3% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | google | 1048K | $2.00 / $10.00 | $0.84 / $4.20 | 58% |
| [Google: Gemini 4 Carbon](https://martllm.com/models/google/gemini-4-carbon) | google | 1048K | $2.00 / $10.00 | $0.672 / $3.36 | 66.4% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | google | 1048K | $1.50 / $9.00 | $0.6458 / $3.87 | 56.9–57% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | google | 1048K | $1.50 / $7.50 | $0.504 / $2.52 | 66.4% |
| [Gemini 3.6 Flash](https://martllm.com/models/google/gemini-3-6-flash) | google | 1000K | $0.75 / $3.75 | $0.63 / $3.15 | 16% |
| [Gemini 3.7 Flash](https://martllm.com/models/google/gemini-3.7-flash) | google | 1048K | $0.75 / $3.75 | $0.6379 / $3.19 | 14.9–15% |
| [Gemini 3.8 Flash](https://martllm.com/models/google/gemini-3.8-flash) | google | 1048K | $0.75 / $3.75 | $0.1024 / $0.5119 | 86.4% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | google | 256K | $0.50 / $3.00 | $0.07875 / $0.4725 | 84.2% |
| [Gemini 3.5 Flash Lite](https://martllm.com/models/google/gemini-3-5-flash-lite) | google | 1000K | $0.30 / $2.50 | $0.09135 / $0.7612 | 69.5% |
| [Gemini 3.1 Flash Lite](https://martllm.com/models/google/gemini-3.1-flash-lite) | google | 1048K | $0.25 / $1.50 | $0.2415 / $1.45 | 3.4% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | google | 256K | $0.12 / $0.36 | $0.02495 / $0.07484 | 79.2% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | google | 262K | $0.12 / $0.36 | $0.08442 / $0.2533 | 29.6% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | google | 262K | $0.10 / $0.30 | $0.0147 / $0.0441 | 85.3% |
| [Gemma 3 27B](https://martllm.com/models/google/gemma-3-27b-it) | google | 40K | $0.08 / $0.20 | $0.04116 / $0.1029 | 48.5–48.6% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | google | 128K | $0.0625 / $0.1875 | $0.01509 / $0.04528 | 75.8–75.9% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | google | 128K | $0.045 / $0.09 | $0.01229 / $0.02457 | 72.7% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | google | 128K | $0.04 / $0.08 | $0.01302 / $0.02604 | 67.5% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | deepseek | 1048K | $1.32 / $3.96 | $0.5267 / $1.58 | 60.1% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | deepseek | 1048K | $1.28 / $2.56 | $0.2285 / $0.457 | 82.2% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-v3.1) | deepseek | 128K | $0.27 / $1.00 | $0.05953 / $0.2205 | 78% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | deepseek | 1048K | $0.2695 / $0.8085 | $0.1981 / $0.5942 | 26.5% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | deepseek | 1048K | $0.195 / $0.75 | $0.04709 / $0.1811 | 75.8% |
| [DeepSeek V4 Flash 0731 Fast](https://martllm.com/models/deepseek/deepseek-v4-flash-0731-fast) | deepseek | 1000K | $0.35 / $0.70 | $0.272 / $0.5439 | 22.3% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | deepseek | 1048K | $0.1485 / $0.64 | $0.02807 / $0.121 | 81.1% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | deepseek | 163K | $0.27 / $0.48 | $0.06237 / $0.1109 | 76.9% |
| [DeepSeek V4 Flash E2EE](https://martllm.com/models/deepseek/e2ee-deepseek-v4-flash) | deepseek | 1000K | $0.182 / $0.373 | $0.1414 / $0.2898 | 22.3% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | deepseek | 1048K | $0.12 / $0.27 | $0.07938 / $0.1786 | 33.8–33.9% |
| [DeepSeek V4 Flash 0731](https://martllm.com/models/deepseek/deepseek-v4-flash-0731) | deepseek | 1048K | $0.13 / $0.26 | $0.05051 / $0.101 | 61.1% |
| [Grok 4.5](https://martllm.com/models/x-ai/grok-4.5) | x-ai | 500K | $2.27 / $6.80 | $1.48 / $4.43 | 34.9% |
| [Grok 4.6](https://martllm.com/models/x-ai/grok-4.6) | x-ai | 500K | $2.27 / $6.80 | $1.74 / $5.21 | 23.3–23.4% |
| [Grok 4.7](https://martllm.com/models/x-ai/grok-4.7) | x-ai | 500K | $2.00 / $6.00 | $1.39 / $4.16 | 30.7% |
| [Grok 4.20 Beta](https://martllm.com/models/x-ai/grok-4.20-beta) | x-ai | 2000K | $1.42 / $2.83 | $0.7306 / $1.46 | 48.6% |
| [Grok 4.20 Multi-Agent Beta](https://martllm.com/models/x-ai/grok-4.20-multi-agent-beta) | x-ai | 2000K | $1.42 / $2.83 | $0.6571 / $1.31 | 53.7% |
| [Grok 4.3](https://martllm.com/models/x-ai/grok-4.3) | x-ai | 1000K | $1.42 / $2.83 | $0.4026 / $0.8023 | 71.6% |
| [Grok Build 0.1](https://martllm.com/models/x-ai/grok-build-0.1) | x-ai | 256K | $1.00 / $2.00 | $1.05 / $2.10 | -5% |
| [Qwen: Qwen3.8 Max Prime](https://martllm.com/models/qwen/qwen3.8-max-prime) | qwen | 1000K | $4.00 / $12.00 | $2.94 / $8.82 | 26.5% |
| [Qwen3.7 Max](https://martllm.com/models/qwen/qwen3.7-max) | qwen | 1000K | $2.70 / $8.05 | $2.35 / $7.02 | 12.9% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | qwen | 1000K | $2.50 / $7.50 | $0.5775 / $1.73 | 76.9% |
| [Qwen3.8 2.4T A95B](https://martllm.com/models/qwen/qwen3.8-2.4t-a95b) | qwen | 1000K | $2.00 / $6.00 | $0.819 / $2.46 | 59.1% |
| [Qwen: Qwen3.8 Max (0902)](https://martllm.com/models/qwen/qwen3.8-max-0902) | qwen | 1000K | $2.00 / $6.00 | $0.273 / $0.819 | 86.3–86.4% |
| [Qwen 4 Max](https://martllm.com/models/qwen/qwen4-max) | qwen | 1000K | $1.43 / $4.28 | $0.5386 / $1.62 | 62.2% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | qwen | 128K | $0.55 / $3.60 | $0.3061 / $2.00 | 44.4% |
| [Qwen 3 235B A22B Thinking 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-thinking-2507) | qwen | 128K | $0.45 / $3.50 | $0.1512 / $1.18 | 66.4% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | qwen | 256K | $0.3225 / $3.20 | $0.1592 / $1.58 | 50.6–50.7% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | qwen | 262K | $0.20 / $2.20 | $0.0105 / $0.1155 | 94.8% |
| [Qwen 3.7 Plus](https://martllm.com/models/qwen/qwen3.7-plus) | qwen | 256K | $0.50 / $2.00 | $0.3937 / $1.57 | 21.3% |
| [Qwen3 VL 235B A22B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-instruct) | qwen | 256K | $0.21 / $1.90 | $0.05292 / $0.4788 | 74.8% |
| [Qwen3 VL 235B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-thinking) | qwen | 256K | $0.21 / $1.90 | $0.1389 / $1.26 | 33.8% |
| [Qwen 3 Coder 480B Turbo](https://martllm.com/models/qwen/qwen3-coder-turbo) | qwen | 256K | $0.35 / $1.50 | $0.3014 / $1.29 | 13.9% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | qwen | 256K | $0.325 / $1.25 | $0.1058 / $0.4069 | 67.4–67.5% |
| [Qwen 3.6 35B A3B (E2EE)](https://martllm.com/models/qwen/e2ee-qwen3-6-35b-a3b) | qwen | 128K | $0.182 / $1.18 | $0.1414 / $0.9169 | 22.3% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | qwen | 262K | $0.095 / $1.10 | $0.03092 / $0.358 | 67.4–67.5% |
| [Qwen 3.6 35B A3B](https://martllm.com/models/qwen/qwen3-6-35b-a3b) | qwen | 262K | $0.10 / $1.00 | $0.04095 / $0.4095 | 59.1% |
| [Qwen 3.5 35B A3B](https://martllm.com/models/qwen/qwen3.5-35b-a3b) | qwen | 256K | $0.15 / $1.00 | $0.1213 / $0.8085 | 19.1% |
| [Qwen3 VL 30B A3B](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-thinking) | qwen | 128K | $0.25 / $0.90 | $0.2205 / $0.7938 | 11.8% |
| [Qwen3 Coder Next](https://martllm.com/models/qwen/qwen3-coder-next) | qwen | 256K | $0.12 / $0.80 | $0.0378 / $0.252 | 68.5% |
| [Qwen 3 235B A22B Instruct 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-2507) | qwen | 128K | $0.135 / $0.75 | $0.09214 / $0.5119 | 31.7–31.8% |
| [Qwen3 30B A3B](https://martllm.com/models/qwen/qwen3-30b-a3b) | qwen | 256K | $0.12 / $0.50 | $0.0882 / $0.3675 | 26.5% |
| [Qwen3.8 Flash](https://martllm.com/models/qwen/qwen3.8-flash) | qwen | 1000K | $0.15 / $0.47 | $0.02993 / $0.09377 | 80% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | qwen | 1000K | $0.15 / $0.47 | $0.0063 / $0.01974 | 95.8% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | qwen | 256K | $0.11 / $0.44 | $0.01848 / $0.07392 | 83.2% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | qwen | 32K | $0.12 / $0.40 | $0.0252 / $0.084 | 79% |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | qwen | 256K | $0.17 / $0.25 | $0.0735 / $0.1103 | 55.9–56.8% |
| [Qwen 2.5 7B](https://martllm.com/models/qwen/e2ee-qwen-2-5-7b-p) | qwen | 32K | $0.05 / $0.13 | $0.0399 / $0.1037 | 20.2% |
| [Qwen: Qwen3.7 Flash](https://martllm.com/models/qwen/qwen3.7-flash) | qwen | 1000K | $0.03 / $0.13 | $0.02174 / $0.09419 | 27.5% |
| [Kimi K3 Fast](https://martllm.com/models/moonshotai/kimi-k3-fast-api) | moonshotai | 1000K | $4.50 / $22.50 | $3.97 / $19.84 | 11.8% |
| [Kimi K3](https://martllm.com/models/moonshotai/kimi-k3) | moonshotai | 1048K | $3.00 / $15.00 | $0.3591 / $1.89 | 87.4–88% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | moonshotai | 1048K | $2.00 / $10.00 | $0.462 / $2.31 | 76.9% |
| [Kimi K2.7 Code](https://martllm.com/models/moonshotai/kimi-k2.7-code) | moonshotai | 262K | $0.75 / $3.50 | $0.2205 / $1.03 | 70.6% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | moonshotai | 262K | $0.70 / $3.40 | $0.0441 / $0.2142 | 93.7% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | moonshotai | 256K | $0.57 / $2.85 | $0.1676 / $0.8379 | 70.6% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | moonshotai | 262K | $0.60 / $2.50 | $0.1575 / $0.6562 | 73.8% |
| [Kimi K2](https://martllm.com/models/moonshotai/kimi-k2) | moonshotai | 256K | $0.57 / $2.30 | $0.4249 / $1.71 | 25.4% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | z-ai | 524K | $1.75 / $5.75 | $1.71 / $5.61 | 2.4% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | z-ai | 1000K | $1.68 / $5.28 | $0.3352 / $1.05 | 80% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | z-ai | 1048K | $1.40 / $4.40 | $0.1095 / $0.462 | 89.5–92.2% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | z-ai | 1000K | $1.40 / $4.40 | $0.04998 / $0.1848 | 95.8–96.4% |
| [GLM-5 Turbo](https://martllm.com/models/z-ai/glm-5-turbo) | z-ai | 200K | $1.20 / $4.00 | $0.8568 / $2.86 | 28.6% |
| [GLM 5V Turbo](https://martllm.com/models/z-ai/glm-5v-turbo) | z-ai | 200K | $1.20 / $4.00 | $0.8568 / $2.86 | 28.6% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | z-ai | 200K | $1.26 / $3.96 | $0.462 / $1.74 | 56–63.3% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | z-ai | 200K | $1.26 / $3.96 | $0.6615 / $2.08 | 47.5% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | z-ai | 204K | $0.975 / $3.04 | $0.4505 / $1.40 | 53.8% |
| [GLM 4.5](https://martllm.com/models/z-ai/glm-4.5) | z-ai | 128K | $0.60 / $2.20 | $0.4473 / $1.64 | 25.5% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | z-ai | 204K | $0.5002 / $2.06 | $0.2889 / $1.19 | 42.2% |
| [GLM-4.6](https://martllm.com/models/z-ai/glm-4.6) | z-ai | 204K | $0.43 / $1.75 | $0.1896 / $0.7718 | 55.9% |
| [Z.ai: GLM 5.3 FlashX](https://martllm.com/models/z-ai/glm-5.3-flashx) | z-ai | 1048K | $0.37 / $1.25 | $0.2603 / $0.8794 | 29.6% |
| [Z.ai: GLM 5.3 FlashX Legal](https://martllm.com/models/z-ai/glm-5.3-flashx-legal) | z-ai | 1048K | $0.37 / $1.25 | $0.2681 / $0.9056 | 27.5% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | z-ai | 128K | $0.14 / $0.86 | $0.09849 / $0.605 | 29.6–29.7% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | z-ai | 1048K | $0.127 / $0.475 | $0.04934 / $0.1845 | 61.1% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | z-ai | 198K | $0.0653 / $0.40 | $0.01714 / $0.105 | 73.8% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | mistralai | 262K | $2.00 / $6.00 | $0.273 / $0.819 | 86.3–86.4% |
| [Mistral: Pixtral Large 2502](https://martllm.com/models/mistralai/pixtral-large-2502) | mistralai | 128K | $2.00 / $6.00 | $1.51 / $4.54 | 24.4% |
| [Mistral: Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4-0) | mistralai | 524K | $0.735 / $2.21 | $0.2778 / $0.8335 | 62.2% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | mistralai | 256K | $0.40 / $2.00 | $0.0966 / $0.483 | 75.8% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | mistralai | 256K | $0.525 / $1.57 | $0.1323 / $0.3969 | 74.8% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | mistralai | 128K | $0.50 / $1.50 | $0.1365 / $0.4095 | 72.7% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-4) | mistralai | 256K | $0.165 / $0.66 | $0.1732 / $0.693 | -5% |
| [Voxtral Small 24B 2507](https://martllm.com/models/mistralai/voxtral-small-24b-2507) | mistralai | 32K | $0.105 / $0.315 | $0.07387 / $0.2216 | 29.6% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | mistralai | 256K | $0.09 / $0.25 | $0.0671 / $0.1864 | 25.4% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | mistralai | 128K | $0.21 / $0.21 | $0.09922 / $0.09922 | 52.8% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | mistralai | 128K | $0.1575 / $0.1575 | $0.04961 / $0.04961 | 68.5% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | mistralai | 128K | $0.105 / $0.105 | $0.02866 / $0.02866 | 72.7% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | mistralai | 32K | $0.04 / $0.04 | $0.0084 / $0.0084 | 79% |
| [Meta: Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder) | meta-llama | 1048K | $4.00 / $20.00 | $2.77 / $13.86 | 30.7% |
| [Meta: Muse Spark 1.1](https://martllm.com/models/meta-llama/muse-spark-1.1) | meta-llama | 1048K | $1.25 / $4.25 | $0.8006 / $2.72 | 35.9% |
| [Meta: Muse Spark 1.2](https://martllm.com/models/meta-llama/muse-spark-1.2) | meta-llama | 1048K | $1.25 / $4.25 | $0.735 / $2.50 | 41.2% |
| [Meta: Muse Spark 1.3](https://martllm.com/models/meta-llama/muse-spark-1.3) | meta-llama | 1048K | $1.25 / $4.25 | $0.7219 / $2.45 | 42.2% |
| [Meta: Muse Spark Open](https://martllm.com/models/meta-llama/muse-spark-open) | meta-llama | 1048K | $1.25 / $4.25 | $1.04 / $3.53 | 17% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | meta-llama | 131K | $0.30 / $1.20 | $0.2205 / $0.882 | 26.5% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | meta-llama | 131K | $0.293 / $0.71 | $0.0923 / $0.2236 | 68.5% |
| [Meta: Muse Ember](https://martllm.com/models/meta-llama/muse-ember) | meta-llama | 1048K | $0.10 / $0.50 | $0.07665 / $0.3832 | 23.4% |
| [Llama 3.2 3B](https://martllm.com/models/meta-llama/llama-3.2-3b-instruct) | meta-llama | 128K | $0.05 / $0.33 | $0.0399 / $0.2633 | 20.2% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.07875 / $0.1575 | 21.3% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.105 / $0.21 | -5% |

</details>

### Image models (per image)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Venice SD35](https://martllm.com/models/venice/sd35) | $0.01 / image | $0.0063 / image | 37% |
| [Kling Image](https://martllm.com/models/kling/kling-image) | $0.007 / image | $0.006783 / image | 3.1% |
| [Flux 1.1 (Venice, legacy)](https://martllm.com/models/venice/flux-1.1) | $0.01 / image | $0.007875 / image | 21.3% |
| [Stable Diffusion XL (Venice, legacy)](https://martllm.com/models/venice/sdxl) | $0.01 / image | $0.007875 / image | 21.3% |
| [GPT Image 2.6 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare) | $0.09 / image | $0.008083 / image | 91% |
| [GPT Image 2.6 Flare (image-to-image)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare-edit) | $0.10 / image | $0.008083 / image | 91.9% |
| [Gen4-image](https://martllm.com/models/runway/gen4-image) | $0.01 / image | $0.00816 / image | 18.4% |
| [Z-Image Turbo (Venice)](https://martllm.com/models/venice/z-image-turbo) | $0.01 / image | $0.008295 / image | 17% |
| [Flux 3 Klein](https://martllm.com/models/black-forest-labs/flux-3-klein) | – | $0.0084 / image | – |
| [Chroma (Venice)](https://martllm.com/models/venice/chroma) | $0.01 / image | $0.00945 / image | 5.5% |

### Image models (per megapixel)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [FLUX.2 Klein 4B](https://martllm.com/models/black-forest-labs/flux.2-klein-4b) | $0.015 / megapixel | $0.01145 / megapixel | 23.7% |
| [FLUX.2 Flex](https://martllm.com/models/black-forest-labs/flux.2-flex) | $0.06 / megapixel | $0.04578 / megapixel | 23.7% |

### Video models (per second)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Grok Imagine](https://martllm.com/models/x-ai/grok-imagine-image-to-video) | $0.05 / sec | $0.012 / sec | 76% |
| [Grok Imagine Video 1.5](https://martllm.com/models/x-ai/grok-imagine-1-5-image-to-video) | $0.08 / sec | $0.0126 / sec | 84.2% |
| [Seedance 1.0 Pro](https://martllm.com/models/bytedance/seedance-1-0-pro) | – | $0.014 / sec | – |
| [Longcat Distilled (image-to-video)](https://martllm.com/models/meituan/longcat-distilled-image-to-video) | $0.018 / sec | $0.01418 / sec | 21.2% |
| [Hailuo 02 Standard Image to Video](https://martllm.com/models/fal-ai/minimax/hailuo-02/standard/image-to-video) | $0.01619 / sec | $0.015 / sec | 7.3% |
| [Seedance 1.0 Pro Fast](https://martllm.com/models/bytedance/seedance-1-0-pro-fast-image-to-video) | – | $0.018 / sec | – |
| [Seedance 2.0 Mini (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-image-to-video) | $0.044 / sec | $0.01817 / sec | 58.7% |
| [LongCat Distilled Text-to-Video](https://martllm.com/models/meituan/longcat-distilled-text-to-video) | – | $0.0189 / sec | – |
| [Seedance 1.0 Pro Quality](https://martllm.com/models/bytedance/seedance-1-0-pro-quality) | $0.0204 / sec | $0.0194 / sec | 4.9% |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-text-to-video) | $0.025 / sec | $0.01969 / sec | 21.2% |

### Video models (per video)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Topaz Video Upscale](https://martllm.com/models/topaz-labs/topaz-video-upscale) | – | $0.1635 / video | – |
| [Wan 2.2 A14B Text-to-Video](https://martllm.com/models/wan/wan-2-2-a14b-text-to-video) | – | $0.218 / video | – |
| [Runway Gen-4 Aleph](https://martllm.com/models/runway/runway-gen4-aleph) | – | $0.545 / video | – |
| [Cosmos Predict (image-to-video)](https://martllm.com/models/nvidia/cosmos-predict-image-to-video) | – | $0.8731 / video | – |

### Music models

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [MMAudio V2 Text-to-Audio (Venice)](https://martllm.com/models/venice/mmaudio-v2-text-to-audio) | – | $0.001003 / sec | – |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-sound-effects-v1-0) | $0.00207 / sec | $0.001579 / sec | 23.7% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | $0.0023 / sec | $0.001755 / sec | 23.7% |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | $0.002875 / sec | $0.002507 / sec | 12.8% |
| [Seed Audio 1.0](https://martllm.com/models/byteplus/seed-audio-1-0) | – | $0.003134 / sec | – |
| [ACE-Step 1.5 (Venice)](https://martllm.com/models/venice/ace-step-15) | $0.03 / track | $0.02453 / track | 18.2% |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | $0.04 / track | $0.0327 / track | 18.2% |
| [Venice Music Gen (legacy alias)](https://martllm.com/models/venice/music-gen) | – | $0.0327 / track | – |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | – | $0.05014 / 1K chars | – |
| [Lyria 3 Pro](https://martllm.com/models/google-deepmind/lyria-3-pro) | $0.10 / track | $0.0763 / track | 23.7% |

### Speech models

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Kokoro Text to Speech (Venice)](https://martllm.com/models/venice/kokoro-tts) | $0.0035 / 1K chars | $0.002899 / 1K chars | 17.2% |
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | – | $0.002938 / 1K chars | – |
| [Inworld 1.5 Max TTS](https://martllm.com/models/inworld/tts-inworld-1-5-max) | – | $0.01362 / 1K chars | – |
| [xAI v1 TTS](https://martllm.com/models/x-ai/tts-xai-v1) | $0.01875 / 1K chars | $0.01533 / 1K chars | 18.3% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://martllm.com/models/venice/elevenlabs-tts-turbo-v2-5) | $0.0625 / 1K chars | $0.04769 / 1K chars | 23.7% |
| [Chatterbox HD TTS](https://martllm.com/models/resemble-ai/tts-chatterbox-hd) | – | $0.0545 / 1K chars | – |
| [Orpheus TTS](https://martllm.com/models/canopy-labs/tts-orpheus) | – | $0.06813 / 1K chars | – |
| [Qwen3 0.6B TTS](https://martllm.com/models/qwen/tts-qwen3-0-6b) | – | $0.09538 / 1K chars | – |
| [MiniMax Speech 02 HD TTS](https://martllm.com/models/minimax/tts-minimax-speech-02-hd) | $0.125 / 1K chars | $0.1063 / 1K chars | 15% |
| [Qwen3 1.7B TTS](https://martllm.com/models/qwen/tts-qwen3-1-7b) | – | $0.1226 / 1K chars | – |

## Prices under review

The catalog's official price for these 1 models failed a sanity check (see `list_price_review_reason`), so it is left out, with no % below list, until it is checked against the maker's own page. The MartLLM price is still listed.

| Model | Category | Why |
|---|---|---|
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | speech | more than 10x off the median speech price per 1K characters |

## Biggest drops this week (2026-11-17 to 2026-11-24)

From MartLLM's daily catalog snapshots (`GET /api/v1/public/price-changes`). Text: $ per 1M input / output tokens, sorted by the larger of the two moves.

### Official list price cuts

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | text | $0.70 / $0.71 | $0.293 / $0.71 | in −58% / out 0% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.30 / $1.20 | $0.1485 / $0.64 | in −50% / out −47% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.44 / $1.32 | $0.2695 / $0.8085 | −39% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.30 / $1.20 | $0.195 / $0.75 | in −35% / out −38% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $1.32 / $3.96 | $1.28 / $2.56 | in −3% / out −35% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.15 / $0.60 | $0.11 / $0.44 | −27% |
| [Particle AI: Particle-1](https://martllm.com/models/particle-ai/particle-1) | text | $0.06 / $0.50 | $0.0525 / $0.375 | in −12% / out −25% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | text | $0.35 / $1.50 | $0.30 / $1.20 | in −14% / out −20% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | text | $0.075 / $0.30 | $0.0725 / $0.25 | in −3% / out −17% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.15 / $0.50 | $0.127 / $0.475 | in −15% / out −5% |

### MartLLM price drops

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MiniMax M2.1](https://martllm.com/models/minimax/minimax-m2.1) | text | $0.315 / $1.26 | $0.003045 / $0.009975 | −99% |
| [GPT Image 2.6 Flare (image-to-image)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare-edit) | image | $0.10 / image | $0.008083 / image | −92% |
| [GPT Image 2.6 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare) | image | $0.09 / image | $0.008083 / image | −91% |
| [Nano Banana Pro (image-to-image)](https://martllm.com/models/google/nano-banana-pro-edit) | image | $0.09 / image | $0.01802 / image | −80% |
| [Nano Banana Pro (Venice)](https://martllm.com/models/venice/nano-banana-pro) | image | $0.09 / image | $0.01802 / image | −80% |
| [Wan 3.0 Prime Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-reference-to-video) | video | $0.364 / sec | $0.09282 / sec | −74% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | text | $0.024 / $0.0752 | $0.0063 / $0.01974 | −74% |
| [Wan 3.0 Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-reference-to-video) | video | $0.26 / sec | $0.06825 / sec | −74% |
| [Gemini Omni Flash 1.1](https://martllm.com/models/google/gemini-omni-flash-1-1) | video | $0.07875 / sec | $0.02162 / sec | −73% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | text | $0.0295 / $0.236 | $0.0105 / $0.084 | −64% |

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
