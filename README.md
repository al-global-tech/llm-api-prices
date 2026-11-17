# LLM API prices

An open, daily-updated dataset of AI API prices: the official list price of 537 text, image, video, music and speech models next to the lowest live price on the [UberLLM](https://uberllm.dev/models) market, how far below list that is, context length and capabilities.

**Updated:** 2026-11-17T03:17:13Z · **Models:** 241 text, 95 image, 161 video, 20 music, 11 speech, 6 transcription, 3 other · **Files:** [`prices.json`](prices.json), [`prices.csv`](prices.csv), [`CHANGELOG.md`](CHANGELOG.md), [`history/`](history/)

Disclosure: this repo is maintained by the team that runs UberLLM. The UberLLM column is our own price; the official column is the maker's price, sourced as described in [Sources](#sources). Live prices: <https://uberllm.dev/models>.

## Cheapest right now

Lowest UberLLM price per category among models that can be called now. Text: $ per 1M input / output tokens. Full list: [`prices.csv`](prices.csv).

### Text (chat) models

| Model | Context | Official price | UberLLM price | Below list |
|---|---|---|---|---|
| [Qwen: Qwen3.8 Omni Flash](https://uberllm.dev/models/qwen/qwen3.8-omni-flash) | 1000K | $0.15 / $0.47 | $0.0015 / $0.0047 | 99% |
| [GPT OSS Safeguard 20B](https://uberllm.dev/models/openai/gpt-oss-safeguard-20b) | 128K | $0.075 / $0.30 | $0.0015 / $0.006 | 98% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | 262K | $0.09 / $0.30 | $0.0027 / $0.009 | 97% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://uberllm.dev/models/nvidia/nemotron-nano-12b-v2) | 128K | $0.20 / $0.60 | $0.004 / $0.012 | 98% |
| [GLM 5.3 Flash](https://uberllm.dev/models/z-ai/glm-5.3-flash) | 1048K | $0.0399 / $0.0784 | $0.005985 / $0.01176 | 85% |
| [Gemini 2.5 Flash](https://uberllm.dev/models/google/gemini-2.5-flash) | 1048K | $0.30 / $2.50 | $0.003 / $0.025 | 99% |
| [Gemma 4 E2B](https://uberllm.dev/models/google/gemma-4-e2b) | 128K | $0.04 / $0.08 | $0.01 / $0.02 | 75% |
| [NVIDIA Nemotron Nano 9B v2](https://uberllm.dev/models/nvidia/nemotron-nano-9b-v2) | 128K | $0.06 / $0.23 | $0.0066 / $0.0253 | 89% |
| [GPT-OSS 120B](https://uberllm.dev/models/openai/gpt-oss-120b) | 128K | $0.07 / $0.30 | $0.0077 / $0.033 | 89% |
| [Qwen3.8 Flash](https://uberllm.dev/models/qwen/qwen3.8-flash) | 1000K | $0.15 / $0.47 | $0.012 / $0.0376 | 92% |
| [Ministral 3 8B](https://uberllm.dev/models/mistralai/ministral-3-8b-instruct) | 128K | $0.15 / $0.15 | $0.0255 / $0.0255 | 83% |
| [Gemma 3 4B IT](https://uberllm.dev/models/google/gemma-3-4b-it) | 128K | $0.05 / $0.10 | $0.017 / $0.034 | 66% |
| [Ministral 3B](https://uberllm.dev/models/mistralai/ministral-3-3b-instruct) | 128K | $0.10 / $0.10 | $0.026 / $0.026 | 74% |
| [Qwen3 Coder 30B A3B Instruct](https://uberllm.dev/models/qwen/qwen3-coder-30b-a3b-instruct) | 256K | $0.15 / $0.60 | $0.0135 / $0.054 | 91% |
| [Gemma 3 27B](https://uberllm.dev/models/google/gemma-3-27b-it) | 40K | $0.08 / $0.20 | $0.02 / $0.05 | 75% |

### Major model makers

<details><summary>OpenAI, Anthropic, Google, DeepSeek, xAI, Qwen, Moonshot, Z.ai, Mistral, Meta (160 models)</summary>

| Model | Maker | Context | Official price | UberLLM price | Below list |
|---|---|---|---|---|---|
| [GPT-5.4 Pro](https://uberllm.dev/models/openai/gpt-5.4-pro) | openai | 1000K | $30.00 / $180.00 | $12.00 / $72.00 | 60% |
| [GPT-5.5 Pro](https://uberllm.dev/models/openai/gpt-5.5-pro) | openai | 1000K | $30.00 / $180.00 | $20.40 / $122.40 | 32% |
| [GPT-6 Astra](https://uberllm.dev/models/openai/gpt-6-astra) | openai | 1050K | $10.00 / $50.00 | $2.30 / $11.50 | 77% |
| [GPT-5.5](https://uberllm.dev/models/openai/gpt-5.5) | openai | 1000K | $5.00 / $30.00 | $2.15 / $12.90 | 57% |
| [GPT-5.6 Sol](https://uberllm.dev/models/openai/gpt-5.6-sol) | openai | 1050K | $4.00 / $20.00 | $1.32 / $6.60 | 67% |
| [GPT-5.6 Sol Pro](https://uberllm.dev/models/openai/gpt-5.6-sol-pro) | openai | 1050K | $4.00 / $20.00 | $3.24 / $16.20 | 19% |
| [GPT-5.4](https://uberllm.dev/models/openai/gpt-5.4) | openai | 1000K | $2.50 / $15.00 | $1.05 / $6.30 | 58% |
| [GPT-5.2](https://uberllm.dev/models/openai/gpt-5.2) | openai | 256K | $1.75 / $14.00 | $0.7175 / $5.74 | 59% |
| [GPT-5.2 Codex](https://uberllm.dev/models/openai/gpt-5.2-codex) | openai | 256K | $1.75 / $14.00 | $1.59 / $12.74 | 9% |
| [GPT-5.3 Codex](https://uberllm.dev/models/openai/gpt-5.3-codex) | openai | 400K | $1.75 / $14.00 | $0.735 / $5.88 | 58% |
| [GPT-5.6 Terra](https://uberllm.dev/models/openai/gpt-5.6-terra) | openai | 1050K | $2.00 / $12.00 | $0.40 / $2.40 | 80% |
| [GPT-5.6 Terra Pro](https://uberllm.dev/models/openai/gpt-5.6-terra-pro) | openai | 1050K | $2.00 / $12.00 | $1.68 / $10.08 | 16% |
| [GPT-4o](https://uberllm.dev/models/openai/gpt-4o) | openai | 128K | $2.50 / $10.00 | $0.45 / $1.80 | 82% |
| [GPT-6 Sol](https://uberllm.dev/models/openai/gpt-6-sol) | openai | 1050K | $2.00 / $10.00 | $0.76 / $3.80 | 62% |
| [GPT-6 Sol Pro](https://uberllm.dev/models/openai/gpt-6-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.44 / $7.20 | 28% |
| [GPT-6.1 Sol](https://uberllm.dev/models/openai/gpt-6.1-sol) | openai | 1050K | $2.00 / $10.00 | $0.54 / $2.70 | 73% |
| [OpenAI: GPT-6.1 Sol Pro](https://uberllm.dev/models/openai/gpt-6.1-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.80 / $9.00 | 10% |
| [OpenAI: GPT-6.1 Terra](https://uberllm.dev/models/openai/gpt-6.1-terra) | openai | 1050K | $1.00 / $5.00 | $0.40 / $2.00 | 60% |
| [OpenAI: GPT-6.1 Terra Pro](https://uberllm.dev/models/openai/gpt-6.1-terra-pro) | openai | 1050K | $1.00 / $5.00 | $0.71 / $3.55 | 29% |
| [GPT-5.4 Mini](https://uberllm.dev/models/openai/gpt-5.4-mini) | openai | 400K | $0.75 / $4.50 | $0.105 / $0.63 | 86% |
| [GPT 5 Mini](https://uberllm.dev/models/openai/gpt-5-mini) | openai | 400K | $0.25 / $2.00 | $0.125 / $1.00 | 50% |
| [GPT 5.4 Nano](https://uberllm.dev/models/openai/gpt-5.4-nano) | openai | 400K | $0.20 / $1.25 | $0.036 / $0.225 | 82% |
| [GPT-5.6 Luna](https://uberllm.dev/models/openai/gpt-5.6-luna) | openai | 1050K | $0.20 / $1.20 | $0.048 / $0.288 | 76% |
| [GPT-5.6 Luna Pro](https://uberllm.dev/models/openai/gpt-5.6-luna-pro) | openai | 1050K | $0.20 / $1.20 | $0.158 / $0.948 | 21% |
| [GPT OSS 120B](https://uberllm.dev/models/openai/e2ee-gpt-oss-120b-p) | openai | 128K | $0.13 / $0.65 | $0.0806 / $0.403 | 38% |
| [GPT-4o Mini](https://uberllm.dev/models/openai/gpt-4o-mini) | openai | 128K | $0.15 / $0.60 | $0.099 / $0.396 | 34% |
| [GPT OSS Safeguard 120B](https://uberllm.dev/models/openai/gpt-oss-safeguard-120b) | openai | 128K | $0.15 / $0.60 | $0.03 / $0.12 | 80% |
| [GPT-6 Luna](https://uberllm.dev/models/openai/gpt-6-luna) | openai | 1050K | $0.10 / $0.50 | $0.059 / $0.295 | 41% |
| [GPT-6 Luna Pro](https://uberllm.dev/models/openai/gpt-6-luna-pro) | openai | 1050K | $0.10 / $0.50 | $0.091 / $0.455 | 9% |
| [GPT 5 Nano](https://uberllm.dev/models/openai/gpt-5-nano) | openai | 400K | $0.05 / $0.40 | $0.0275 / $0.22 | 45% |
| [GPT-OSS 120B](https://uberllm.dev/models/openai/gpt-oss-120b) | openai | 128K | $0.07 / $0.30 | $0.0077 / $0.033 | 89% |
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | openai | 128K | $0.075 / $0.30 | $0.021 / $0.084 | 72% |
| [GPT OSS Safeguard 20B](https://uberllm.dev/models/openai/gpt-oss-safeguard-20b) | openai | 128K | $0.075 / $0.30 | $0.0015 / $0.006 | 98% |
| [Claude Fable 5](https://uberllm.dev/models/anthropic/claude-fable-5) | anthropic | 1000K | $10.00 / $50.00 | $4.70 / $23.50 | 53% |
| [Claude Fable 5.1](https://uberllm.dev/models/anthropic/claude-fable-5.1) | anthropic | 1000K | $10.00 / $50.00 | $4.20 / $21.00 | 58% |
| [Claude Opus 5 (Fast)](https://uberllm.dev/models/anthropic/claude-opus-5-fast) | anthropic | 1000K | $10.00 / $50.00 | $7.20 / $36.00 | 28% |
| [Claude Fable 5.2](https://uberllm.dev/models/anthropic/claude-fable-5.2) | anthropic | 1000K | $8.00 / $40.00 | $3.44 / $17.20 | 57% |
| [Claude Opus 4.5](https://uberllm.dev/models/anthropic/claude-opus-4.5) | anthropic | 198K | $5.00 / $25.00 | $2.60 / $13.00 | 48% |
| [Claude Opus 4.6](https://uberllm.dev/models/anthropic/claude-opus-4.6) | anthropic | 1000K | $5.00 / $25.00 | $1.80 / $9.00 | 64% |
| [Claude Opus 4.7](https://uberllm.dev/models/anthropic/claude-opus-4.7) | anthropic | 1000K | $5.00 / $25.00 | $2.10 / $10.50 | 58% |
| [Claude Opus 4.8](https://uberllm.dev/models/anthropic/claude-opus-4.8) | anthropic | 1000K | $5.00 / $25.00 | $2.00 / $10.00 | 60% |
| [Claude Opus 5](https://uberllm.dev/models/anthropic/claude-opus-5) | anthropic | 1000K | $5.00 / $25.00 | $2.45 / $12.25 | 51% |
| [Claude Opus 5.5](https://uberllm.dev/models/anthropic/claude-opus-5.5) | anthropic | 1000K | $4.00 / $20.00 | $1.36 / $6.80 | 66% |
| [Claude Sonnet 4.5](https://uberllm.dev/models/anthropic/claude-sonnet-4.5) | anthropic | 198K | $3.00 / $15.00 | $1.89 / $9.45 | 37% |
| [Claude Sonnet 4.6](https://uberllm.dev/models/anthropic/claude-sonnet-4.6) | anthropic | 1000K | $3.00 / $15.00 | $1.44 / $7.20 | 52% |
| [Claude Sonnet 5](https://uberllm.dev/models/anthropic/claude-sonnet-5) | anthropic | 1000K | $2.00 / $10.00 | $0.74 / $3.70 | 63% |
| [Claude Sonnet 5.5](https://uberllm.dev/models/anthropic/claude-sonnet-5.5) | anthropic | 1000K | $2.00 / $10.00 | $1.18 / $5.90 | 41% |
| [Claude Haiku 4.5](https://uberllm.dev/models/anthropic/claude-haiku-4.5) | anthropic | 200K | $1.00 / $5.00 | $0.62 / $3.10 | 38% |
| [Claude Haiku 5.5](https://uberllm.dev/models/anthropic/claude-haiku-5.5) | anthropic | 100K | $0.10 / $0.50 | $0.051 / $0.255 | 49% |
| [Gemini 3.1 Pro Preview](https://uberllm.dev/models/google/gemini-3.1-pro-preview) | google | 1000K | $2.00 / $12.00 | $0.24 / $1.44 | 88% |
| [Gemini 2.5 Pro](https://uberllm.dev/models/google/gemini-2.5-pro) | google | 1048K | $1.25 / $10.00 | $0.175 / $1.40 | 86% |
| [Google: Gemini 4 Argon](https://uberllm.dev/models/google/gemini-4-argon) | google | 1048K | $2.00 / $10.00 | $0.24 / $1.20 | 88% |
| [Google: Gemini 4 Carbon](https://uberllm.dev/models/google/gemini-4-carbon) | google | 1048K | $2.00 / $10.00 | $0.82 / $4.10 | 59% |
| [Gemini 3.5 Flash](https://uberllm.dev/models/google/gemini-3.5-flash) | google | 1000K | $1.50 / $9.00 | $0.255 / $1.53 | 83% |
| [Google: Gemini 4 Hydrogen](https://uberllm.dev/models/google/gemini-4-hydrogen) | google | 1048K | $1.50 / $7.50 | $0.285 / $1.43 | 81% |
| [Gemini 3.8 Flash](https://uberllm.dev/models/google/gemini-3.8-flash) | google | 1048K | $0.825 / $4.12 | $0.033 / $0.165 | 96% |
| [Gemini 3.6 Flash](https://uberllm.dev/models/google/gemini-3-6-flash) | google | 1000K | $0.75 / $3.75 | $0.4725 / $2.36 | 37% |
| [Gemini 3.7 Flash](https://uberllm.dev/models/google/gemini-3.7-flash) | google | 1048K | $0.75 / $3.75 | $0.015 / $0.075 | 98% |
| [Gemini 3 Flash Preview](https://uberllm.dev/models/google/gemini-3-flash-preview) | google | 256K | $0.50 / $3.00 | $0.02 / $0.12 | 96% |
| [Gemini 2.5 Flash](https://uberllm.dev/models/google/gemini-2.5-flash) | google | 1048K | $0.30 / $2.50 | $0.003 / $0.025 | 99% |
| [Gemini 3.5 Flash Lite](https://uberllm.dev/models/google/gemini-3-5-flash-lite) | google | 1000K | $0.30 / $2.50 | $0.228 / $1.90 | 24% |
| [Gemini 3.1 Flash Lite](https://uberllm.dev/models/google/gemini-3.1-flash-lite) | google | 1048K | $0.25 / $1.50 | $0.0725 / $0.435 | 71% |
| [Gemma 4 31B](https://uberllm.dev/models/google/gemma-4-31b) | google | 256K | $0.12 / $0.36 | $0.0324 / $0.0972 | 73% |
| [Gemma 4 31B IT](https://uberllm.dev/models/google/gemma-4-31b-it) | google | 262K | $0.12 / $0.36 | $0.0708 / $0.2124 | 41% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | google | 262K | $0.09 / $0.30 | $0.0027 / $0.009 | 97% |
| [Gemma 3 27B](https://uberllm.dev/models/google/gemma-3-27b-it) | google | 40K | $0.08 / $0.20 | $0.02 / $0.05 | 75% |
| [Gemma 3 12B IT](https://uberllm.dev/models/google/gemma-3-12b-it) | google | 128K | $0.05 / $0.15 | $0.0265 / $0.0795 | 47% |
| [Gemma 3 4B IT](https://uberllm.dev/models/google/gemma-3-4b-it) | google | 128K | $0.05 / $0.10 | $0.017 / $0.034 | 66% |
| [Gemma 4 E2B](https://uberllm.dev/models/google/gemma-4-e2b) | google | 128K | $0.04 / $0.08 | $0.01 / $0.02 | 75% |
| [DeepSeek V4 Pro](https://uberllm.dev/models/deepseek/deepseek-v4-pro) | deepseek | 1000K | $1.32 / $3.96 | $0.18 / $0.30 | 86.4–92.4% |
| [DeepSeek V4 Pro 0813](https://uberllm.dev/models/deepseek/deepseek-v4-pro-0813) | deepseek | 1048K | $1.32 / $3.96 | $0.06327 / $2.53 | 36.1–95.2% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://uberllm.dev/models/deepseek/deepseek-v4-flash-vision-exp) | deepseek | 1048K | $0.44 / $1.32 | $0.308 / $0.924 | 30% |
| [DeepSeek V4.1 Flash](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash) | deepseek | 1048K | $0.30 / $1.20 | $0.0588 / $0.1764 | 80.4–85.3% |
| [DeepSeek V4.1 Flash 1017](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash-1017) | deepseek | 1048K | $0.30 / $1.20 | $0.051 / $0.204 | 83% |
| [DeepSeek V3.1](https://uberllm.dev/models/deepseek/deepseek-v3.1) | deepseek | 128K | $0.25 / $0.95 | $0.0743 / $0.2823 | 70.3% |
| [DeepSeek V4 Flash 0731 Fast](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731-fast) | deepseek | 1000K | $0.35 / $0.70 | $0.2095 / $0.4191 | 40.1% |
| [DeepSeek V3.2](https://uberllm.dev/models/deepseek/deepseek-v3.2) | deepseek | 160K | $0.26 / $0.38 | $0.0364 / $0.0532 | 86% |
| [DeepSeek V4 Flash E2EE](https://uberllm.dev/models/deepseek/e2ee-deepseek-v4-flash) | deepseek | 1000K | $0.182 / $0.373 | $0.1183 / $0.2424 | 35% |
| [DeepSeek V4 Flash](https://uberllm.dev/models/deepseek/deepseek-v4-flash) | deepseek | 1000K | $0.09 / $0.18 | $0.0513 / $0.1026 | 43% |
| [DeepSeek V4 Flash 0731](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731) | deepseek | 1048K | $0.06 / $0.18 | $0.0288 / $0.0864 | 52% |
| [Grok 4.5](https://uberllm.dev/models/x-ai/grok-4.5) | x-ai | 500K | $2.00 / $6.00 | $1.26 / $3.78 | 37% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | x-ai | 500K | $2.00 / $6.00 | $0.98 / $2.94 | 51% |
| [Grok 4.7](https://uberllm.dev/models/x-ai/grok-4.7) | x-ai | 500K | $2.00 / $6.00 | $0.90 / $2.70 | 55% |
| [Grok 4.20 Beta](https://uberllm.dev/models/x-ai/grok-4.20-beta) | x-ai | 2000K | $1.25 / $2.50 | $0.425 / $0.85 | 66% |
| [Grok 4.20 Multi-Agent Beta](https://uberllm.dev/models/x-ai/grok-4.20-multi-agent-beta) | x-ai | 2000K | $1.25 / $2.50 | $0.625 / $1.25 | 50% |
| [Grok 4.3](https://uberllm.dev/models/x-ai/grok-4.3) | x-ai | 1000K | $1.25 / $2.50 | $0.6375 / $1.27 | 49% |
| [Grok Build 0.1](https://uberllm.dev/models/x-ai/grok-build-0.1) | x-ai | 256K | $1.00 / $2.00 | $0.77 / $1.54 | 23% |
| [Qwen: Qwen3.8 Max Prime](https://uberllm.dev/models/qwen/qwen3.8-max-prime) | qwen | 1000K | $4.00 / $12.00 | $2.80 / $8.40 | 30% |
| [Qwen3.7 Max](https://uberllm.dev/models/qwen/qwen3.7-max) | qwen | 256K | $2.70 / $8.05 | $1.65 / $4.91 | 39% |
| [Qwen 3.8 Max](https://uberllm.dev/models/qwen/qwen-3-8-max) | qwen | 1000K | $2.50 / $7.50 | $0.55 / $1.65 | 78% |
| [Qwen3.8 2.4T A95B](https://uberllm.dev/models/qwen/qwen3.8-2.4t-a95b) | qwen | 1000K | $2.00 / $6.00 | $0.66 / $1.98 | 67% |
| [Qwen: Qwen3.8 Max (0902)](https://uberllm.dev/models/qwen/qwen3.8-max-0902) | qwen | 1000K | $2.00 / $6.00 | $0.74 / $2.22 | 63% |
| [Qwen 4 Max](https://uberllm.dev/models/qwen/qwen4-max) | qwen | 1000K | $1.43 / $4.28 | $1.05 / $3.15 | 26.3% |
| [Qwen 3 235B A22B Thinking 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-thinking-2507) | qwen | 128K | $0.45 / $3.50 | $0.099 / $0.77 | 78% |
| [Qwen 3.6 27B](https://uberllm.dev/models/qwen/qwen3.6-27b) | qwen | 256K | $0.32 / $3.20 | $0.1216 / $1.22 | 62% |
| [Qwen 3.5 397B](https://uberllm.dev/models/qwen/qwen3.5-397b-a17b) | qwen | 128K | $0.45 / $3.00 | $0.342 / $2.28 | 24% |
| [Qwen 3.7 Plus](https://uberllm.dev/models/qwen/qwen3.7-plus) | qwen | 256K | $0.50 / $2.00 | $0.2497 / $0.999 | 50% |
| [Qwen3 VL 235B A22B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-instruct) | qwen | 256K | $0.21 / $1.90 | $0.0462 / $0.418 | 78% |
| [Qwen3 VL 235B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-thinking) | qwen | 256K | $0.21 / $1.90 | $0.147 / $1.33 | 30% |
| [Qwen 3.8 27B](https://uberllm.dev/models/qwen/qwen-3-8-27b) | qwen | 262K | $0.15 / $1.88 | $0.006 / $0.075 | 96% |
| [Qwen 3 Coder 480B Turbo](https://uberllm.dev/models/qwen/qwen3-coder-turbo) | qwen | 256K | $0.35 / $1.50 | $0.175 / $0.75 | 50% |
| [Qwen 3.6 35B A3B (E2EE)](https://uberllm.dev/models/qwen/e2ee-qwen3-6-35b-a3b) | qwen | 128K | $0.182 / $1.18 | $0.1074 / $0.6962 | 41% |
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | qwen | 256K | $0.09 / $1.10 | $0.0198 / $0.242 | 78% |
| [Qwen 3.6 35B A3B](https://uberllm.dev/models/qwen/qwen3-6-35b-a3b) | qwen | 262K | $0.10 / $1.00 | $0.041 / $0.41 | 59% |
| [Qwen 3 Coder 480b](https://uberllm.dev/models/qwen/qwen3-coder) | qwen | 256K | $0.30 / $1.00 | $0.084 / $0.28 | 72% |
| [Qwen 3.5 35B A3B](https://uberllm.dev/models/qwen/qwen3.5-35b-a3b) | qwen | 256K | $0.15 / $1.00 | $0.102 / $0.68 | 32% |
| [Qwen3 VL 30B A3B](https://uberllm.dev/models/qwen/qwen3-vl-30b-a3b-thinking) | qwen | 128K | $0.25 / $0.90 | $0.24 / $0.864 | 4% |
| [Qwen3 Coder Next](https://uberllm.dev/models/qwen/qwen3-coder-next) | qwen | 256K | $0.12 / $0.80 | $0.0216 / $0.144 | 82% |
| [Qwen 3 235B A22B Instruct 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-2507) | qwen | 128K | $0.14 / $0.75 | $0.0924 / $0.495 | 34% |
| [Qwen3 Coder 30B A3B Instruct](https://uberllm.dev/models/qwen/qwen3-coder-30b-a3b-instruct) | qwen | 256K | $0.15 / $0.60 | $0.0135 / $0.054 | 91% |
| [Qwen3 30B A3B](https://uberllm.dev/models/qwen/qwen3-30b-a3b) | qwen | 256K | $0.12 / $0.50 | $0.084 / $0.35 | 30% |
| [Qwen3.8 Flash](https://uberllm.dev/models/qwen/qwen3.8-flash) | qwen | 1000K | $0.15 / $0.47 | $0.012 / $0.0376 | 92% |
| [Qwen: Qwen3.8 Omni Flash](https://uberllm.dev/models/qwen/qwen3.8-omni-flash) | qwen | 1000K | $0.15 / $0.47 | $0.0015 / $0.0047 | 99% |
| [Qwen3 32B](https://uberllm.dev/models/qwen/qwen3-32b) | qwen | 32K | $0.08 / $0.28 | $0.02 / $0.07 | 75% |
| [Qwen 2.5 7B](https://uberllm.dev/models/qwen/e2ee-qwen-2-5-7b-p) | qwen | 32K | $0.05 / $0.13 | $0.0325 / $0.0845 | 35% |
| [Qwen: Qwen3.7 Flash](https://uberllm.dev/models/qwen/qwen3.7-flash) | qwen | 1000K | $0.03 / $0.13 | $0.0204 / $0.0884 | 32% |
| [Kimi K3 Fast](https://uberllm.dev/models/moonshotai/kimi-k3-fast-api) | moonshotai | 1000K | $4.50 / $22.50 | $2.70 / $13.50 | 40% |
| [Kimi K3](https://uberllm.dev/models/moonshotai/kimi-k3) | moonshotai | 1000K | $3.00 / $15.00 | $0.01536 / $1.28 | 91.5–99.5% |
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | moonshotai | 262K | $0.60 / $3.50 | $0.114 / $0.665 | 81% |
| [Kimi K2.6](https://uberllm.dev/models/moonshotai/kimi-k2.6) | moonshotai | 256K | $0.65 / $3.41 | $0.0585 / $0.3069 | 91% |
| [Kimi K2 Thinking](https://uberllm.dev/models/moonshotai/kimi-k2-thinking) | moonshotai | 256K | $0.60 / $2.50 | $0.15 / $0.625 | 75% |
| [Kimi K2.5](https://uberllm.dev/models/moonshotai/kimi-k2.5) | moonshotai | 256K | $0.50 / $2.50 | $0.275 / $1.38 | 45% |
| [Kimi K2](https://uberllm.dev/models/moonshotai/kimi-k2) | moonshotai | 256K | $0.57 / $2.30 | $0.399 / $1.61 | 30% |
| [Z.ai: GLM 5.3 Prime](https://uberllm.dev/models/z-ai/glm-5.3-prime) | z-ai | 1000K | $2.80 / $8.80 | $0.224 / $0.704 | 92% |
| [GLM 5.2 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5-2-p) | z-ai | 524K | $1.75 / $5.75 | $1.44 / $4.71 | 18% |
| [GLM 5.1 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5.1) | z-ai | 200K | $1.40 / $4.40 | $0.55 / $2.08 | 52.8–60.7% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | z-ai | 200K | $1.40 / $4.40 | $0.056 / $0.176 | 96% |
| [GLM-5.2](https://uberllm.dev/models/z-ai/glm-5.2) | z-ai | 1048K | $1.40 / $4.40 | $0.00084 / $0.528 | 88–99.9% |
| [GLM 5.3](https://uberllm.dev/models/z-ai/glm-5.3) | z-ai | 1000K | $1.40 / $4.40 | $0.004194 / $0.084 | 98.1–99.7% |
| [GLM-5 Turbo](https://uberllm.dev/models/z-ai/glm-5-turbo) | z-ai | 200K | $1.20 / $4.00 | $0.696 / $2.32 | 42% |
| [GLM 5V Turbo](https://uberllm.dev/models/z-ai/glm-5v-turbo) | z-ai | 200K | $1.20 / $4.00 | $1.08 / $3.60 | 10% |
| [GLM-5](https://uberllm.dev/models/z-ai/glm-5) | z-ai | 198K | $1.00 / $3.20 | $0.33 / $1.06 | 67% |
| [GLM 4.5](https://uberllm.dev/models/z-ai/glm-4.5) | z-ai | 128K | $0.60 / $2.20 | $0.036 / $0.132 | 94% |
| [GLM-4.6](https://uberllm.dev/models/z-ai/glm-4.6) | z-ai | 198K | $0.43 / $1.75 | $0.0946 / $0.385 | 78% |
| [GLM-4.7](https://uberllm.dev/models/z-ai/glm-4.7) | z-ai | 128K | $0.40 / $1.75 | $0.184 / $0.805 | 54% |
| [Z.ai: GLM 5.3 FlashX](https://uberllm.dev/models/z-ai/glm-5.3-flashx) | z-ai | 1048K | $0.37 / $1.25 | $0.2516 / $0.85 | 32% |
| [Z.ai: GLM 5.3 FlashX Legal](https://uberllm.dev/models/z-ai/glm-5.3-flashx-legal) | z-ai | 1048K | $0.37 / $1.25 | $0.259 / $0.875 | 30% |
| [GLM 4.5 Air](https://uberllm.dev/models/z-ai/glm-4.5-air) | z-ai | 128K | $0.13 / $0.85 | $0.0338 / $0.221 | 74% |
| [GLM 4.7 Flash](https://uberllm.dev/models/z-ai/glm-4.7-flash) | z-ai | 198K | $0.0605 / $0.40 | $0.0121 / $0.08 | 80% |
| [GLM 5.3 Flash](https://uberllm.dev/models/z-ai/glm-5.3-flash) | z-ai | 1048K | $0.0399 / $0.0784 | $0.005985 / $0.01176 | 85% |
| [Mistral Large](https://uberllm.dev/models/mistralai/mistral-large) | mistralai | 128K | $2.00 / $6.00 | $0.64 / $1.92 | 68% |
| [Mistral: Mistral Large 4](https://uberllm.dev/models/mistralai/mistral-large-4-0) | mistralai | 524K | $0.70 / $2.10 | $0.42 / $1.26 | 40% |
| [Devstral 2 123B](https://uberllm.dev/models/mistralai/devstral-2-123b) | mistralai | 256K | $0.40 / $2.00 | $0.06 / $0.30 | 85% |
| [Magistral Small 2509](https://uberllm.dev/models/mistralai/magistral-small-2509) | mistralai | 128K | $0.50 / $1.50 | $0.11 / $0.33 | 78% |
| [Mistral Large 3](https://uberllm.dev/models/mistralai/mistral-large-3) | mistralai | 256K | $0.50 / $1.50 | $0.125 / $0.375 | 75% |
| [Mistral Small 4](https://uberllm.dev/models/mistralai/mistral-small-4) | mistralai | 256K | $0.15 / $0.60 | $0.1005 / $0.402 | 33% |
| [Mistral Small 3.2 24B Instruct](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct) | mistralai | 256K | $0.0938 / $0.25 | $0.04315 / $0.115 | 54% |
| [Ministral 14B 3.0](https://uberllm.dev/models/mistralai/ministral-3-14b-instruct) | mistralai | 128K | $0.20 / $0.20 | $0.046 / $0.046 | 77% |
| [Ministral 3 8B](https://uberllm.dev/models/mistralai/ministral-3-8b-instruct) | mistralai | 128K | $0.15 / $0.15 | $0.0255 / $0.0255 | 83% |
| [Ministral 3B](https://uberllm.dev/models/mistralai/ministral-3-3b-instruct) | mistralai | 128K | $0.10 / $0.10 | $0.026 / $0.026 | 74% |
| [Meta: Muse Wonder](https://uberllm.dev/models/meta-llama/muse-wonder) | meta-llama | 1048K | $4.00 / $20.00 | $1.56 / $7.80 | 61% |
| [Meta: Muse Spark 1.1](https://uberllm.dev/models/meta-llama/muse-spark-1.1) | meta-llama | 1048K | $1.25 / $4.25 | $0.5375 / $1.83 | 57% |
| [Meta: Muse Spark 1.2](https://uberllm.dev/models/meta-llama/muse-spark-1.2) | meta-llama | 1048K | $1.25 / $4.25 | $0.5375 / $1.83 | 57% |
| [Meta: Muse Spark 1.3](https://uberllm.dev/models/meta-llama/muse-spark-1.3) | meta-llama | 1048K | $1.25 / $4.25 | $0.4875 / $1.66 | 61% |
| [Meta: Muse Spark Open](https://uberllm.dev/models/meta-llama/muse-spark-open) | meta-llama | 1048K | $1.25 / $4.25 | $0.7375 / $2.51 | 41% |
| [Meta: Muse Glimmer 30B](https://uberllm.dev/models/meta-llama/muse-glimmer-30b) | meta-llama | 131K | $0.30 / $1.20 | $0.21 / $0.84 | 30% |
| [Meta: Muse Ember](https://uberllm.dev/models/meta-llama/muse-ember) | meta-llama | 1048K | $0.10 / $0.50 | $0.074 / $0.37 | 26% |
| [Llama 3.2 3B](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct) | meta-llama | 128K | $0.0509 / $0.335 | $0.03512 / $0.2311 | 31% |
| [Meta: Muse Spark 1.2 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.2-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.058 / $0.116 | 42% |
| [Meta: Muse Spark 1.3 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.3-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.037 / $0.074 | 63% |

</details>

### Image models (per image)

| Model | Official price | UberLLM price | Below list |
|---|---|---|---|
| [Z-Image Turbo (Venice)](https://uberllm.dev/models/venice/z-image-turbo) | $0.01 / image | $0.00396 / image | 60.4% |
| [Venice SD35](https://uberllm.dev/models/venice/sd35) | $0.01 / image | $0.007 / image | 30% |
| [Flux 3 Klein](https://uberllm.dev/models/black-forest-labs/flux-3-klein) | $0.009 / image | $0.008 / image | 11.1% |
| [Chroma (Venice)](https://uberllm.dev/models/venice/chroma) | $0.01 / image | $0.008 / image | 20% |
| [Flux 1.1 (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1) | $0.01 / image | $0.008 / image | 20% |
| [Stable Diffusion XL (Venice, legacy)](https://uberllm.dev/models/venice/sdxl) | $0.01 / image | $0.008 / image | 20% |
| [Flux 2 Pro (Venice)](https://uberllm.dev/models/venice/flux-2-pro) | $0.03 / image | $0.0114 / image | 62% |
| [Grok Imagine High Quality (Venice)](https://uberllm.dev/models/venice/grok-imagine-quality) | $0.06 / image | $0.015 / image | 75% |
| [Seedream 5.0 Flash](https://uberllm.dev/models/bytedance/seedream-5-0-flash) | – | $0.0162 / image | – |
| [Seedream 3.0](https://uberllm.dev/models/bytedance/seedream-3-0) | – | $0.0175 / image | – |

### Image models (per megapixel)

| Model | Official price | UberLLM price | Below list |
|---|---|---|---|
| [FLUX.2 Flex](https://uberllm.dev/models/black-forest-labs/flux.2-flex) | $0.06 / megapixel | $0.0036 / megapixel | 94% |
| [FLUX.2 Klein 4B](https://uberllm.dev/models/black-forest-labs/flux.2-klein-4b) | $0.015 / megapixel | $0.00375 / megapixel | 75% |

### Video models (per second)

| Model | Official price | UberLLM price | Below list |
|---|---|---|---|
| [Longcat Distilled (image-to-video)](https://uberllm.dev/models/meituan/longcat-distilled-image-to-video) | $0.018 / sec | $0.0108 / sec | 40% |
| [Grok Imagine Video 1.5](https://uberllm.dev/models/x-ai/grok-imagine-1-5-image-to-video) | $0.08 / sec | $0.012 / sec | 85% |
| [Grok Imagine](https://uberllm.dev/models/x-ai/grok-imagine-image-to-video) | $0.05 / sec | $0.012 / sec | 76% |
| [Grok Imagine Text-to-Video](https://uberllm.dev/models/x-ai/grok-imagine-text-to-video) | $0.0895 / sec | $0.012 / sec | 86.6% |
| [Seedance 1.0 Pro](https://uberllm.dev/models/bytedance/seedance-1-0-pro) | – | $0.014 / sec | – |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | $0.018 / sec | $0.0144 / sec | 20% |
| [Hailuo 02 Standard Image to Video](https://uberllm.dev/models/fal-ai/minimax/hailuo-02/standard/image-to-video) | $0.017 / sec | $0.01445 / sec | 15% |
| [Seedance 1.0 Pro Fast](https://uberllm.dev/models/bytedance/seedance-1-0-pro-fast-image-to-video) | – | $0.018 / sec | – |
| [Seedance 2.0 Mini (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-image-to-video) | $0.044 / sec | $0.019 / sec | 56.8% |
| [PixVerse V6](https://uberllm.dev/models/pixverse/pixverse-v6) | $0.02222 / sec | $0.02 / sec | 10% |

### Video models (per video)

| Model | Official price | UberLLM price | Below list |
|---|---|---|---|
| [Topaz Video Upscale](https://uberllm.dev/models/topaz-labs/topaz-video-upscale) | $0.15 / video | $0.105 / video | 30% |
| [Wan 2.2 A14B Text-to-Video](https://uberllm.dev/models/wan/wan-2-2-a14b-text-to-video) | $0.20 / video | $0.14 / video | 30% |
| [Runway Gen-4 Aleph](https://uberllm.dev/models/runway/runway-gen4-aleph) | $0.50 / video | $0.35 / video | 30% |
| [Cosmos Predict (image-to-video)](https://uberllm.dev/models/nvidia/cosmos-predict-image-to-video) | $0.801 / video | $0.5607 / video | 30% |

### Music models

| Model | Official price | UberLLM price | Below list |
|---|---|---|---|
| [MMAudio V2 Text-to-Audio (Venice)](https://uberllm.dev/models/venice/mmaudio-v2-text-to-audio) | $0.00092 / sec | $0.000736 / sec | 20% |
| [ElevenLabs Sound Effects v2 (Venice)](https://uberllm.dev/models/venice/elevenlabs-sound-effects-v2) | $0.0023 / sec | $0.00184 / sec | 20% |
| [Sonilo V1.1 Sound Effects](https://uberllm.dev/models/sonilo/sonilo-sound-effects-v1-0) | – | $0.00207 / sec | – |
| [Seed Audio 1.0](https://uberllm.dev/models/byteplus/seed-audio-1-0) | – | $0.002875 / sec | – |
| [Sonilo V1.1 Music](https://uberllm.dev/models/sonilo/sonilo-music-v1-1) | – | $0.002875 / sec | – |
| [ACE-Step 1.5 (Venice)](https://uberllm.dev/models/venice/ace-step-15) | $0.03 / track | $0.021 / track | 30% |
| [Venice Music Gen (legacy alias)](https://uberllm.dev/models/venice/music-gen) | $0.03 / track | $0.024 / track | 20% |
| [MiniMax Music 2.0 (Venice)](https://uberllm.dev/models/venice/minimax-music-v2) | $0.04 / track | $0.028 / track | 30% |
| [ElevenLabs TTS v4 Turbo](https://uberllm.dev/models/elevenlabs/elevenlabs-tts-v4-turbo) | – | $0.046 / 1K chars | – |
| [ElevenLabs TTS v4](https://uberllm.dev/models/elevenlabs/elevenlabs-tts-v4) | – | $0.092 / 1K chars | – |

### Speech models

| Model | Official price | UberLLM price | Below list |
|---|---|---|---|
| [Kokoro Text to Speech (Venice)](https://uberllm.dev/models/venice/kokoro-tts) | $0.0035 / 1K chars | $0.00245 / 1K chars | 30% |
| [Venice TTS 1 (legacy alias)](https://uberllm.dev/models/venice/tts-1) | – | $0.0028 / 1K chars | – |
| [Inworld 1.5 Max TTS](https://uberllm.dev/models/inworld/tts-inworld-1-5-max) | $0.0125 / 1K chars | $0.00875 / 1K chars | 30% |
| [xAI v1 TTS](https://uberllm.dev/models/x-ai/tts-xai-v1) | $0.01875 / 1K chars | $0.01031 / 1K chars | 45% |
| [Chatterbox HD TTS](https://uberllm.dev/models/resemble-ai/tts-chatterbox-hd) | $0.05 / 1K chars | $0.04 / 1K chars | 20% |
| [Orpheus TTS](https://uberllm.dev/models/canopy-labs/tts-orpheus) | $0.0625 / 1K chars | $0.04063 / 1K chars | 35% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://uberllm.dev/models/venice/elevenlabs-tts-turbo-v2-5) | $0.0625 / 1K chars | $0.05 / 1K chars | 20% |
| [Qwen3 0.6B TTS](https://uberllm.dev/models/qwen/tts-qwen3-0-6b) | $0.0875 / 1K chars | $0.06125 / 1K chars | 30% |
| [Qwen3 1.7B TTS](https://uberllm.dev/models/qwen/tts-qwen3-1-7b) | $0.1125 / 1K chars | $0.07312 / 1K chars | 35% |
| [MiniMax Speech 02 HD TTS](https://uberllm.dev/models/minimax/tts-minimax-speech-02-hd) | $0.125 / 1K chars | $0.08125 / 1K chars | 35% |

## Prices under review

The catalog's official price for these 2 models failed a sanity check (see `list_price_review_reason`), so it is left out, with no % below list, until it is checked against the maker's own page. The UberLLM price is still listed.

| Model | Category | Why |
|---|---|---|
| [Llama 3.3 70B Instruct](https://uberllm.dev/models/meta-llama/llama-3.3-70b-instruct) | text | output:input ratio 1.0 vs 3.4 for the maker's other models |
| [Venice TTS 1 (legacy alias)](https://uberllm.dev/models/venice/tts-1) | speech | more than 10x off the median speech price per 1K characters |

## Biggest drops this week (2026-11-10 to 2026-11-17)

From UberLLM's daily catalog snapshots (`GET /api/v1/public/price-changes`). Text: $ per 1M input / output tokens, sorted by the larger of the two moves.

### Official list price cuts

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MMAudio V2 Text-to-Audio (Venice)](https://uberllm.dev/models/venice/mmaudio-v2-text-to-audio) | text | $0.01 / sec | $0.00092 / sec | −91% |
| [ElevenLabs Sound Effects v2 (Venice)](https://uberllm.dev/models/venice/elevenlabs-sound-effects-v2) | text | $0.02 / sec | $0.0023 / sec | −88% |
| [MiMo-V2.5-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.5-pro) | text | $0.48 / $1.80 | $0.435 / $0.87 | in −9% / out −52% |
| [GLM 4.5 Air](https://uberllm.dev/models/z-ai/glm-4.5-air) | text | $0.20 / $1.10 | $0.13 / $0.85 | in −35% / out −23% |
| [GLM-4.7](https://uberllm.dev/models/z-ai/glm-4.7) | text | $0.55 / $2.20 | $0.40 / $1.75 | in −27% / out −20% |
| [Qwen 3.5 397B](https://uberllm.dev/models/qwen/qwen3.5-397b-a17b) | text | $0.60 / $3.60 | $0.45 / $3.00 | in −25% / out −17% |
| [Kimi K2.5](https://uberllm.dev/models/moonshotai/kimi-k2.5) | text | $0.532 / $3.33 | $0.50 / $2.50 | in −6% / out −25% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-multilingual-v2) | text | $0.12 / 1K chars | $0.115 / 1K chars | −4% |
| [ElevenLabs TTS v3 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-v3) | text | $0.12 / 1K chars | $0.115 / 1K chars | −4% |
| [DeepSeek V4 Flash](https://uberllm.dev/models/deepseek/deepseek-v4-flash) | text | $0.091 / $0.182 | $0.09 / $0.18 | −1% |

### UberLLM price drops

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Qwen: Qwen3.8 Omni Flash](https://uberllm.dev/models/qwen/qwen3.8-omni-flash) | text | $0.024 / $0.0752 | $0.0015 / $0.0047 | −94% |
| [Gemini 3.1 Pro](https://uberllm.dev/models/google/gemini-3.1-pro) | text | $1.10 / $6.60 | $0.2196 / $1.32 | −80% |
| [GPT-4o](https://uberllm.dev/models/openai/gpt-4o) | text | $1.75 / $7.00 | $0.45 / $1.80 | −74% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | text | $0.196 / $0.616 | $0.056 / $0.176 | −71% |
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.0675 / $0.825 | $0.0198 / $0.242 | −71% |
| [MiniMax M2.7 Highspeed](https://uberllm.dev/models/minimax/minimax-m2.7-highspeed) | text | $0.09 / $0.36 | $0.03 / $0.12 | −67% |
| [Qwen 3.8 27B](https://uberllm.dev/models/qwen/qwen-3-8-27b) | text | $0.0165 / $0.2062 | $0.006 / $0.075 | −64% |
| [Gemini 3.1 Pro Preview](https://uberllm.dev/models/google/gemini-3.1-pro-preview) | text | $0.64 / $3.84 | $0.24 / $1.44 | −62% |
| [Qwen3.5 Flash](https://uberllm.dev/models/qwen/qwen3.5-flash) | text | $0.025 / $0.10 | $0.01 / $0.04 | −60% |
| [Mistral Large](https://uberllm.dev/models/mistralai/mistral-large) | text | $1.58 / $4.74 | $0.64 / $1.92 | −59% |

Every change, day by day: [`CHANGELOG.md`](CHANGELOG.md).

## Use the data

Plain HTTPS, no key. Raw file URLs:

- JSON: `https://raw.githubusercontent.com/PSA-Team-source/llm-api-prices/main/prices.json`
- CSV: `https://raw.githubusercontent.com/PSA-Team-source/llm-api-prices/main/prices.csv`
- A past day: `https://raw.githubusercontent.com/PSA-Team-source/llm-api-prices/main/history/YYYY-MM-DD.csv`

Python (stdlib):

```python
import json, urllib.request
URL = "https://raw.githubusercontent.com/PSA-Team-source/llm-api-prices/main/prices.json"
data = json.load(urllib.request.urlopen(URL))
chat = [m for m in data["models"] if m["category"] == "text" and m["available"]
        and m["list_output_usd_per_mtok"] and "tools" in m["capabilities"]]
for m in sorted(chat, key=lambda m: m["list_output_usd_per_mtok"])[:10]:
    print(m["id"], m["list_input_usd_per_mtok"], m["list_output_usd_per_mtok"], m["list_price_source"])
```

JavaScript:

```js
const res = await fetch("https://raw.githubusercontent.com/PSA-Team-source/llm-api-prices/main/prices.json");
const { updated_at, models } = await res.json();
const video = models.filter(m => m.category === "video" && m.unit === "second");
console.log(updated_at, video.sort((a, b) => a.uberllm_usd_per_unit - b.uberllm_usd_per_unit).slice(0, 5));
```

jq: `jq '.models[] | select(.maker=="anthropic") | {id, list_input_usd_per_mtok, list_output_usd_per_mtok}' prices.json`

### Fields

| Field | Meaning |
|---|---|
| `id` | Model id, as used in the `model` field of an OpenAI-compatible request to UberLLM |
| `category` | text, image, video, music, speech, transcription, embedding or other (from the output modality) |
| `unit` | `1M tokens` for token-priced models; otherwise what one unit price buys: `image`, `megapixel`, `second`, `job` (one video or track), `minute`, `1K characters` |
| `list_input_usd_per_mtok`, `list_output_usd_per_mtok` | Official list price, USD per 1M tokens |
| `uberllm_input_usd_per_mtok`, `uberllm_output_usd_per_mtok` | UberLLM price a buyer can count on at snapshot time, USD per 1M tokens: per side, the higher of the best live seller and the listed price |
| `list_usd_per_unit`, `uberllm_usd_per_unit` | The same for per-unit (media) prices |
| `pct_below_list_*` | 100 × (1 − UberLLM / list), one decimal; negative = above list; empty = no list price |
| `list_price_source`, `list_price_source_url`, `list_price_checked` | Where the official price comes from (see Sources) |
| `list_price_hosts` | JSON only: the published per-token prices of named hosts (Together AI, Fireworks, Bedrock, ...) for the model |
| `video_rates` | JSON only: every per-second video price by resolution and sound, official and UberLLM |
| `vendor_pricing_page` | The maker's own pricing page, to check a list price against |
| `capabilities` | tools, reasoning, vision, structured_outputs; video: text-to-video, image-to-video, sound |
| `available` | A request can be served right now |
| `nsfw` | Made for adult or unfiltered content (text only; adult image/video/sound models are not listed) |

## Sources

Every number comes from UberLLM's public catalog, read once a day by [`update.py`](update.py):

- `GET https://api.uberllm.dev/api/v1/public/models`: model list, context length, capabilities, official list prices, UberLLM prices.
- `GET https://api.uberllm.dev/api/v1/public/market/live`: the live market board (refreshed every 30 s). The text price published here is, per side, the higher of its best seller and the catalog's listed price, as on uberllm.dev's comparison pages.
- `GET https://api.uberllm.dev/v1/models`: the OpenAI-compatible model list (reasoning flag).
- `GET https://api.uberllm.dev/api/v1/public/price-changes`: the weekly diff used for "Biggest drops this week" and the first CHANGELOG entry.

Official list price, per row:

- `list_price_source` starting "UberLLM catalog list price": the direct (list) price the catalog carries for the model, meant to be the maker's own API price for first-party models (OpenAI, Anthropic, Google, ...) and the host's list price for open-weight models. The public catalog does not record which vendor page that number was read from, so `list_price_source_url` is empty and the source says so. `vendor_pricing_page` is the maker's pricing page to check it against (it is not where the number was read); for open-weight models, `list_price_hosts` has the named hosts' own prices.
- Any other `list_price_source` (for example `OpenRouter`, `Z.ai`, `Fal`, `Kling (Kuaishou)`, `Stability AI`): the catalog had no list of its own, so the price was read from that public page (`list_price_source_url`) on `list_price_checked`.
- `list_price_status`: `ok` = the official price passed the sanity check; `unverified` = it failed it (input under 1/40 of output, an output:input ratio more than 3x off the maker's other models, an input more than 3x off other listings of the same model, or a media price more than 10x off its category median), so the official price and every % below list are left empty until it is checked; `none` = no official price.
- No official price: the field is empty. A media model whose only known official price is not above what UberLLM charges gets no official price, so a saving is never claimed against a number we cannot show.

UberLLM price = the best offer a seller on the UberLLM market makes at snapshot time, fee included. Market prices move during the day; the snapshot is a point in time, and <https://uberllm.dev/models> always has the current one.

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

- Data (`prices.json`, `prices.csv`, `history/`, `CHANGELOG.md`): [CC BY 4.0](LICENSE-DATA). Credit: "LLM API prices, PSA-Team-source/llm-api-prices (UberLLM)" with a link to this repo.
- Code (`update.py`): [MIT](LICENSE).
