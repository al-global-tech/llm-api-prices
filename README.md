# LLM API prices

*MartLLM was called UberLLM until November 2026; the `uberllm_*` column names stay as they are.*

An open, daily-updated dataset of AI API prices: the official list price of 560 text, image, video, music and speech models next to the lowest live price on the [MartLLM](https://martllm.com/models) market, how far below list that is, context length and capabilities.

**Updated:** 2026-11-22T10:00:02Z · **Models:** 237 text, 100 image, 183 video, 20 music, 11 speech, 6 transcription, 3 other · **Files:** [`prices.json`](prices.json), [`prices.csv`](prices.csv), [`CHANGELOG.md`](CHANGELOG.md), [`history/`](history/)

Disclosure: this repo is maintained by the team that runs MartLLM. The MartLLM column is our own price; the official column is the maker's price, sourced as described in [Sources](#sources). Live prices: <https://martllm.com/models>.

## Cheapest right now

Lowest MartLLM price per category among models that can be called now. Text: $ per 1M input / output tokens. Full list: [`prices.csv`](prices.csv).

### Text (chat) models

| Model | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | 128K | $0.0725 / $0.25 | $0.001523 / $0.00525 | 97.9% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | 128K | $0.04 / $0.08 | $0.00252 / $0.00504 | 93.7% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | 128K | $0.07 / $0.30 | $0.00147 / $0.0063 | 97.9% |
| [NVIDIA Nemotron Nano 9B v2](https://martllm.com/models/nvidia/nemotron-nano-9b-v2) | 128K | $0.06 / $0.23 | $0.00189 / $0.007245 | 96.9% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | 262K | $0.10 / $0.30 | $0.00315 / $0.00945 | 96.9% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://martllm.com/models/nvidia/nemotron-nano-12b-v2) | 128K | $0.20 / $0.60 | $0.0042 / $0.0126 | 97.9% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | 32K | $0.04 / $0.04 | $0.0126 / $0.0126 | 68.5% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | 128K | $0.045 / $0.09 | $0.00945 / $0.0189 | 79% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | 1000K | $0.15 / $0.47 | $0.007875 / $0.02467 | 94.8% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | 128K | $0.105 / $0.105 | $0.02425 / $0.02425 | 76.9% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | 262K | $0.20 / $2.30 | $0.0042 / $0.0483 | 97.9% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | 32K | $0.12 / $0.40 | $0.01386 / $0.0462 | 88.4–88.5% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | 128K | $0.0625 / $0.1875 | $0.01575 / $0.04725 | 74.8% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | 256K | $0.12 / $0.36 | $0.01638 / $0.04914 | 86.3–86.4% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | 198K | $0.0653 / $0.40 | $0.009599 / $0.0588 | 85.3% |

### Major model makers

<details><summary>OpenAI, Anthropic, Google, DeepSeek, xAI, Qwen, Moonshot, Z.ai, Mistral, Meta (169 models)</summary>

| Model | Maker | Context | Official price | MartLLM price | Below list |
|---|---|---|---|---|---|
| [GPT-5.4 Pro](https://martllm.com/models/openai/gpt-5.4-pro) | openai | 1000K | $30.00 / $180.00 | $17.64 / $105.84 | 41.2% |
| [GPT-5.5 Pro](https://martllm.com/models/openai/gpt-5.5-pro) | openai | 1000K | $30.00 / $180.00 | $20.16 / $120.96 | 32.8% |
| [GPT-6 Astra](https://martllm.com/models/openai/gpt-6-astra) | openai | 1050K | $10.00 / $50.00 | $3.57 / $17.85 | 64.3% |
| [GPT-6.2 Astra](https://martllm.com/models/openai/gpt-6.2-astra) | openai | 1050K | $8.00 / $40.00 | $4.96 / $24.78 | 38% |
| [GPT-6.2 Astra Pro](https://martllm.com/models/openai/gpt-6.2-astra-pro) | openai | 1050K | $8.00 / $40.00 | $6.97 / $34.86 | 12.8–12.9% |
| [GPT-5.5](https://martllm.com/models/openai/gpt-5.5) | openai | 1000K | $5.00 / $30.00 | $3.20 / $19.21 | 35.9–36% |
| [GPT-5.6 Sol](https://martllm.com/models/openai/gpt-5.6-sol) | openai | 1050K | $4.00 / $20.00 | $1.64 / $8.19 | 59.1% |
| [GPT-5.6 Sol Pro](https://martllm.com/models/openai/gpt-5.6-sol-pro) | openai | 1050K | $4.00 / $20.00 | $4.20 / $21.00 | -5% |
| [GPT-5.4](https://martllm.com/models/openai/gpt-5.4) | openai | 1000K | $2.50 / $15.00 | $1.36 / $8.19 | 45.4% |
| [GPT-5.2](https://martllm.com/models/openai/gpt-5.2) | openai | 256K | $1.75 / $14.00 | $1.01 / $8.09 | 42.2% |
| [GPT-5.2 Codex](https://martllm.com/models/openai/gpt-5.2-codex) | openai | 256K | $1.75 / $14.00 | $0.8636 / $6.91 | 50.6% |
| [GPT-5.3 Codex](https://martllm.com/models/openai/gpt-5.3-codex) | openai | 400K | $1.75 / $14.00 | $0.882 / $7.06 | 49.6% |
| [GPT-5.6 Terra](https://martllm.com/models/openai/gpt-5.6-terra) | openai | 1050K | $2.00 / $12.00 | $0.42 / $2.52 | 79% |
| [GPT-5.6 Terra Pro](https://martllm.com/models/openai/gpt-5.6-terra-pro) | openai | 1050K | $2.00 / $12.00 | $2.02 / $12.10 | -0.8% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | openai | 128K | $2.50 / $10.00 | $0.9187 / $3.67 | 63.3% |
| [GPT-6 Sol](https://martllm.com/models/openai/gpt-6-sol) | openai | 1050K | $2.00 / $10.00 | $0.987 / $4.93 | 50.6–50.7% |
| [GPT-6 Sol Pro](https://martllm.com/models/openai/gpt-6-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.72 / $8.61 | 13.9% |
| [GPT-6.1 Sol](https://martllm.com/models/openai/gpt-6.1-sol) | openai | 1050K | $2.00 / $10.00 | $0.819 / $4.09 | 59.1% |
| [OpenAI: GPT-6.1 Sol Pro](https://martllm.com/models/openai/gpt-6.1-sol-pro) | openai | 1050K | $2.00 / $10.00 | $1.72 / $8.61 | 13.9% |
| [GPT-6.2 Sol](https://martllm.com/models/openai/gpt-6.2-sol) | openai | 1050K | $2.00 / $10.00 | $1.13 / $5.67 | 43.3% |
| [GPT-6.2 Sol Pro](https://martllm.com/models/openai/gpt-6.2-sol-pro) | openai | 1050K | $2.00 / $10.00 | $2.02 / $10.08 | -0.8% |
| [OpenAI: GPT-6.1 Terra](https://martllm.com/models/openai/gpt-6.1-terra) | openai | 1050K | $1.00 / $5.00 | $0.5145 / $2.57 | 48.6% |
| [OpenAI: GPT-6.1 Terra Pro](https://martllm.com/models/openai/gpt-6.1-terra-pro) | openai | 1050K | $1.00 / $5.00 | $0.861 / $4.30 | 13.9% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | openai | 400K | $0.75 / $4.50 | $0.1339 / $0.8033 | 82.2% |
| [GPT 5 Mini](https://martllm.com/models/openai/gpt-5-mini) | openai | 400K | $0.25 / $2.00 | $0.063 / $0.504 | 74.8% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | openai | 400K | $0.20 / $1.25 | $0.0504 / $0.315 | 74.8% |
| [GPT-5.6 Luna](https://martllm.com/models/openai/gpt-5.6-luna) | openai | 1050K | $0.20 / $1.20 | $0.105 / $0.63 | 47.5% |
| [GPT-5.6 Luna Pro](https://martllm.com/models/openai/gpt-5.6-luna-pro) | openai | 1050K | $0.20 / $1.20 | $0.1617 / $0.9702 | 19.1% |
| [GPT OSS 120B](https://martllm.com/models/openai/e2ee-gpt-oss-120b-p) | openai | 128K | $0.13 / $0.65 | $0.1092 / $0.546 | 16% |
| [GPT-4o Mini](https://martllm.com/models/openai/gpt-4o-mini) | openai | 128K | $0.15 / $0.60 | $0.0504 / $0.2016 | 66.4% |
| [GPT OSS Safeguard 120B](https://martllm.com/models/openai/gpt-oss-safeguard-120b) | openai | 128K | $0.15 / $0.60 | $0.04095 / $0.1638 | 72.7% |
| [GPT-6 Luna](https://martllm.com/models/openai/gpt-6-luna) | openai | 1050K | $0.10 / $0.50 | $0.0588 / $0.294 | 41.2% |
| [GPT-6 Luna Pro](https://martllm.com/models/openai/gpt-6-luna-pro) | openai | 1050K | $0.10 / $0.50 | $0.0861 / $0.4305 | 13.9% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | openai | 400K | $0.05 / $0.40 | $0.0168 / $0.1344 | 66.4% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | openai | 128K | $0.07 / $0.30 | $0.00147 / $0.0063 | 97.9% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | openai | 128K | $0.0725 / $0.25 | $0.001523 / $0.00525 | 97.9% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | openai | 128K | $0.03 / $0.15 | $0.01606 / $0.08032 | 46.5% |
| [Claude Fable 5](https://martllm.com/models/anthropic/claude-fable-5) | anthropic | 1000K | $10.00 / $50.00 | $6.09 / $30.45 | 39.1% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | anthropic | 1000K | $10.00 / $50.00 | $5.57 / $27.82 | 44.4% |
| [Claude Opus 5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5-fast) | anthropic | 1000K | $10.00 / $50.00 | $8.71 / $43.58 | 12.8–12.9% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | anthropic | 1000K | $8.00 / $40.00 | $6.38 / $31.92 | 20.2% |
| [Claude Opus 4.5](https://martllm.com/models/anthropic/claude-opus-4.5) | anthropic | 198K | $5.00 / $25.00 | $2.68 / $13.39 | 46.4–46.5% |
| [Claude Opus 4.6](https://martllm.com/models/anthropic/claude-opus-4.6) | anthropic | 1000K | $5.00 / $25.00 | $2.62 / $13.12 | 47.5% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | anthropic | 1000K | $5.00 / $25.00 | $2.52 / $12.60 | 49.6% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | anthropic | 1000K | $5.00 / $25.00 | $2.83 / $14.18 | 43.3% |
| [Claude Opus 5](https://martllm.com/models/anthropic/claude-opus-5) | anthropic | 1000K | $5.00 / $25.00 | $2.62 / $13.12 | 47.5% |
| [Claude Opus 5.5](https://martllm.com/models/anthropic/claude-opus-5.5) | anthropic | 1000K | $4.00 / $20.00 | $2.06 / $10.29 | 48.6% |
| [Claude Sonnet 4.5](https://martllm.com/models/anthropic/claude-sonnet-4.5) | anthropic | 198K | $3.00 / $15.00 | $2.80 / $14.02 | 6.6% |
| [Claude Sonnet 4.6](https://martllm.com/models/anthropic/claude-sonnet-4.6) | anthropic | 1000K | $3.00 / $15.00 | $2.14 / $10.71 | 28.6% |
| [Claude Sonnet 5](https://martllm.com/models/anthropic/claude-sonnet-5) | anthropic | 1000K | $2.00 / $10.00 | $1.03 / $5.14 | 48.6% |
| [Claude Sonnet 5.5](https://martllm.com/models/anthropic/claude-sonnet-5.5) | anthropic | 1000K | $2.00 / $10.00 | $1.18 / $5.88 | 41.2% |
| [Claude Haiku 4.5](https://martllm.com/models/anthropic/claude-haiku-4.5) | anthropic | 200K | $1.00 / $5.00 | $1.05 / $5.25 | -5% |
| [Claude Haiku 5.5](https://martllm.com/models/anthropic/claude-haiku-5.5) | anthropic | 1000K | $0.10 / $0.50 | $0.0651 / $0.3255 | 34.9% |
| [Google: Gemini 4 Neon](https://martllm.com/models/google/gemini-4-neon) | google | 1048K | $3.00 / $15.00 | $2.30 / $11.50 | 23.3% |
| [Gemini 3.1 Pro Preview](https://martllm.com/models/google/gemini-3.1-pro-preview) | google | 1000K | $2.00 / $12.00 | $0.63 / $3.78 | 68.5% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | google | 1048K | $2.00 / $10.00 | $0.756 / $3.78 | 62.2% |
| [Google: Gemini 4 Carbon](https://martllm.com/models/google/gemini-4-carbon) | google | 1048K | $2.00 / $10.00 | $0.798 / $3.99 | 60.1% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | google | 1000K | $1.50 / $9.00 | $0.7245 / $4.35 | 51.7% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | google | 1048K | $1.50 / $7.50 | $0.6773 / $3.39 | 54.9% |
| [Gemini 3.6 Flash](https://martllm.com/models/google/gemini-3-6-flash) | google | 1000K | $0.75 / $3.75 | $0.5591 / $2.80 | 25.5% |
| [Gemini 3.7 Flash](https://martllm.com/models/google/gemini-3.7-flash) | google | 1048K | $0.75 / $3.75 | $0.6221 / $3.11 | 17% |
| [Gemini 3.8 Flash](https://martllm.com/models/google/gemini-3.8-flash) | google | 1048K | $0.75 / $3.75 | $0.252 / $1.26 | 66.4% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | google | 256K | $0.50 / $3.00 | $0.084 / $0.504 | 83.2% |
| [Gemini 3.5 Flash Lite](https://martllm.com/models/google/gemini-3-5-flash-lite) | google | 1000K | $0.30 / $2.50 | $0.1071 / $0.8925 | 64.3% |
| [Gemini 3.1 Flash Lite](https://martllm.com/models/google/gemini-3.1-flash-lite) | google | 1048K | $0.25 / $1.50 | $0.1837 / $1.10 | 26.5% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | google | 256K | $0.12 / $0.36 | $0.01638 / $0.04914 | 86.3–86.4% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | google | 262K | $0.12 / $0.36 | $0.09954 / $0.2986 | 17% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | google | 262K | $0.10 / $0.30 | $0.00315 / $0.00945 | 96.9% |
| [Gemma 3 27B](https://martllm.com/models/google/gemma-3-27b-it) | google | 40K | $0.08 / $0.20 | $0.05712 / $0.1428 | 28.6% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | google | 128K | $0.0625 / $0.1875 | $0.01575 / $0.04725 | 74.8% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | google | 128K | $0.045 / $0.09 | $0.00945 / $0.0189 | 79% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | google | 128K | $0.04 / $0.08 | $0.00252 / $0.00504 | 93.7% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | deepseek | 1048K | $1.31 / $3.96 | $0.4402 / $1.33 | 66.4% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | deepseek | 1000K | $1.28 / $2.56 | $0.2957 / $0.5914 | 76.9% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-v3.1) | deepseek | 128K | $0.27 / $1.00 | $0.06237 / $0.231 | 76.9% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | deepseek | 1048K | $0.2695 / $0.8085 | $0.2377 / $0.7131 | 11.8% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | deepseek | 1048K | $0.195 / $0.75 | $0.04095 / $0.1575 | 79% |
| [DeepSeek V4 Flash 0731 Fast](https://martllm.com/models/deepseek/deepseek-v4-flash-0731-fast) | deepseek | 1000K | $0.35 / $0.70 | $0.272 / $0.5439 | 22.3% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | deepseek | 1048K | $0.147 / $0.60 | $0.03087 / $0.126 | 79% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | deepseek | 160K | $0.27 / $0.48 | $0.04253 / $0.0756 | 84.2% |
| [DeepSeek V4 Flash E2EE](https://martllm.com/models/deepseek/e2ee-deepseek-v4-flash) | deepseek | 1000K | $0.182 / $0.373 | $0.1605 / $0.329 | 11.8% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | deepseek | 1000K | $0.12 / $0.27 | $0.0693 / $0.1559 | 42.2% |
| [DeepSeek V4 Flash 0731](https://martllm.com/models/deepseek/deepseek-v4-flash-0731) | deepseek | 1048K | $0.13 / $0.26 | $0.03822 / $0.07644 | 70.6% |
| [Grok 4.5](https://martllm.com/models/x-ai/grok-4.5) | x-ai | 500K | $2.27 / $6.80 | $1.48 / $4.43 | 34.9% |
| [Grok 4.6](https://martllm.com/models/x-ai/grok-4.6) | x-ai | 500K | $2.27 / $6.80 | $1.55 / $4.64 | 31.8% |
| [Grok 4.7](https://martllm.com/models/x-ai/grok-4.7) | x-ai | 500K | $2.00 / $6.00 | $1.43 / $4.28 | 28.6% |
| [Grok 4.20 Beta](https://martllm.com/models/x-ai/grok-4.20-beta) | x-ai | 2000K | $1.42 / $2.83 | $0.7157 / $1.43 | 49.6% |
| [Grok 4.20 Multi-Agent Beta](https://martllm.com/models/x-ai/grok-4.20-multi-agent-beta) | x-ai | 2000K | $1.42 / $2.83 | $0.671 / $1.34 | 52.8% |
| [Grok 4.3](https://martllm.com/models/x-ai/grok-4.3) | x-ai | 1000K | $1.42 / $2.83 | $0.4026 / $0.8023 | 71.6% |
| [Grok Build 0.1](https://martllm.com/models/x-ai/grok-build-0.1) | x-ai | 256K | $1.00 / $2.00 | $1.05 / $2.10 | -5% |
| [Qwen: Qwen3.8 Max Prime](https://martllm.com/models/qwen/qwen3.8-max-prime) | qwen | 1000K | $4.00 / $12.00 | $2.94 / $8.82 | 26.5% |
| [Qwen3.7 Max](https://martllm.com/models/qwen/qwen3.7-max) | qwen | 256K | $2.70 / $8.05 | $2.10 / $6.25 | 22.3% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | qwen | 1000K | $2.50 / $7.50 | $0.2888 / $0.8662 | 88.4–88.5% |
| [Qwen3.8 2.4T A95B](https://martllm.com/models/qwen/qwen3.8-2.4t-a95b) | qwen | 1000K | $2.00 / $6.00 | $0.504 / $1.51 | 74.8% |
| [Qwen: Qwen3.8 Max (0902)](https://martllm.com/models/qwen/qwen3.8-max-0902) | qwen | 1000K | $2.00 / $6.00 | $0.147 / $0.441 | 92.7% |
| [Qwen 4 Max](https://martllm.com/models/qwen/qwen4-max) | qwen | 1000K | $1.43 / $4.28 | $0.3441 / $1.03 | 75.8% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | qwen | 128K | $0.55 / $3.60 | $0.3523 / $2.31 | 36% |
| [Qwen 3 235B A22B Thinking 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-thinking-2507) | qwen | 128K | $0.45 / $3.50 | $0.2646 / $2.06 | 41.2% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | qwen | 256K | $0.3225 / $3.20 | $0.08466 / $0.84 | 73.8% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | qwen | 262K | $0.20 / $2.30 | $0.0042 / $0.0483 | 97.9% |
| [Qwen 3.7 Plus](https://martllm.com/models/qwen/qwen3.7-plus) | qwen | 256K | $0.50 / $2.00 | $0.4462 / $1.78 | 10.8% |
| [Qwen3 VL 235B A22B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-instruct) | qwen | 256K | $0.21 / $1.90 | $0.04851 / $0.4389 | 76.9% |
| [Qwen3 VL 235B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-thinking) | qwen | 256K | $0.21 / $1.90 | $0.1588 / $1.44 | 24.4% |
| [Qwen 3 Coder 480B Turbo](https://martllm.com/models/qwen/qwen3-coder-turbo) | qwen | 256K | $0.35 / $1.50 | $0.3565 / $1.53 | -1.8% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | qwen | 256K | $0.325 / $1.25 | $0.04436 / $0.1706 | 86.3% |
| [Qwen 3.6 35B A3B (E2EE)](https://martllm.com/models/qwen/e2ee-qwen3-6-35b-a3b) | qwen | 128K | $0.182 / $1.18 | $0.151 / $0.9788 | 17% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | qwen | 256K | $0.095 / $1.10 | $0.02693 / $0.3119 | 71.6–71.7% |
| [Qwen 3.6 35B A3B](https://martllm.com/models/qwen/qwen3-6-35b-a3b) | qwen | 262K | $0.10 / $1.00 | $0.04305 / $0.4305 | 57% |
| [Qwen 3.5 35B A3B](https://martllm.com/models/qwen/qwen3.5-35b-a3b) | qwen | 256K | $0.15 / $1.00 | $0.1181 / $0.7875 | 21.3% |
| [Qwen3 VL 30B A3B](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-thinking) | qwen | 128K | $0.25 / $0.90 | $0.2415 / $0.8694 | 3.4% |
| [Qwen3 Coder Next](https://martllm.com/models/qwen/qwen3-coder-next) | qwen | 256K | $0.12 / $0.80 | $0.01764 / $0.1176 | 85.3% |
| [Qwen 3 235B A22B Instruct 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-2507) | qwen | 128K | $0.135 / $0.75 | $0.07796 / $0.4331 | 42.2% |
| [Qwen3 30B A3B](https://martllm.com/models/qwen/qwen3-30b-a3b) | qwen | 256K | $0.12 / $0.50 | $0.0882 / $0.3675 | 26.5% |
| [Qwen3.8 Flash](https://martllm.com/models/qwen/qwen3.8-flash) | qwen | 1000K | $0.15 / $0.47 | $0.04725 / $0.148 | 68.5% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | qwen | 1000K | $0.15 / $0.47 | $0.007875 / $0.02467 | 94.8% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | qwen | 256K | $0.11 / $0.44 | $0.05198 / $0.2079 | 52.8% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | qwen | 32K | $0.12 / $0.40 | $0.01386 / $0.0462 | 88.4–88.5% |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | qwen | 256K | $0.17 / $0.25 | $0.0735 / $0.1103 | 55.9–56.8% |
| [Qwen 2.5 7B](https://martllm.com/models/qwen/e2ee-qwen-2-5-7b-p) | qwen | 32K | $0.05 / $0.13 | $0.0399 / $0.1037 | 20.2% |
| [Qwen: Qwen3.7 Flash](https://martllm.com/models/qwen/qwen3.7-flash) | qwen | 1000K | $0.03 / $0.13 | $0.02205 / $0.09555 | 26.5% |
| [Kimi K3 Fast](https://martllm.com/models/moonshotai/kimi-k3-fast-api) | moonshotai | 1000K | $4.50 / $22.50 | $3.45 / $17.25 | 23.3–23.4% |
| [Kimi K3](https://martllm.com/models/moonshotai/kimi-k3) | moonshotai | 1000K | $3.00 / $15.00 | $0.2993 / $1.57 | 89.5–90% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | moonshotai | 1048K | $2.00 / $10.00 | $0.777 / $3.88 | 61.1–61.2% |
| [Kimi K2.7 Code](https://martllm.com/models/moonshotai/kimi-k2.7-code) | moonshotai | 262K | $0.75 / $3.50 | $0.2205 / $1.03 | 70.6% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | moonshotai | 256K | $0.70 / $3.40 | $0.03675 / $0.1785 | 94.8% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | moonshotai | 256K | $0.57 / $2.85 | $0.1377 / $0.6883 | 75.8% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | moonshotai | 256K | $0.60 / $2.50 | $0.0441 / $0.1837 | 92.7% |
| [Kimi K2](https://martllm.com/models/moonshotai/kimi-k2) | moonshotai | 256K | $0.57 / $2.30 | $0.4549 / $1.84 | 20.2% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | z-ai | 524K | $1.75 / $5.75 | $1.32 / $4.35 | 24.4% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | z-ai | 1000K | $1.68 / $5.28 | $0.07056 / $0.2218 | 95.8% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | z-ai | 1048K | $1.40 / $4.40 | $0.05476 / $0.231 | 94.8–96.1% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | z-ai | 1000K | $1.40 / $4.40 | $0.07497 / $0.2772 | 93.7–94.6% |
| [GLM-5 Turbo](https://martllm.com/models/z-ai/glm-5-turbo) | z-ai | 200K | $1.20 / $4.00 | $0.8316 / $2.77 | 30.7% |
| [GLM 5V Turbo](https://martllm.com/models/z-ai/glm-5v-turbo) | z-ai | 200K | $1.20 / $4.00 | $0.9198 / $3.07 | 23.4% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | z-ai | 200K | $1.26 / $3.96 | $0.5775 / $2.18 | 45–54.2% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | z-ai | 200K | $1.26 / $3.96 | $0.3307 / $1.04 | 73.8% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | z-ai | 198K | $0.975 / $3.04 | $0.5016 / $1.56 | 48.5–48.6% |
| [GLM 4.5](https://martllm.com/models/z-ai/glm-4.5) | z-ai | 128K | $0.60 / $2.20 | $0.378 / $1.39 | 37% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | z-ai | 128K | $0.5002 / $2.06 | $0.2889 / $1.19 | 42.2% |
| [GLM-4.6](https://martllm.com/models/z-ai/glm-4.6) | z-ai | 198K | $0.43 / $1.75 | $0.1806 / $0.735 | 58% |
| [Z.ai: GLM 5.3 FlashX](https://martllm.com/models/z-ai/glm-5.3-flashx) | z-ai | 1048K | $0.37 / $1.25 | $0.2409 / $0.8137 | 34.9% |
| [Z.ai: GLM 5.3 FlashX Legal](https://martllm.com/models/z-ai/glm-5.3-flashx-legal) | z-ai | 1048K | $0.37 / $1.25 | $0.3108 / $1.05 | 16% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | z-ai | 128K | $0.14 / $0.86 | $0.08379 / $0.5147 | 40.1–40.2% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | z-ai | 1048K | $0.13 / $0.50 | $0.03276 / $0.126 | 74.8% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | z-ai | 198K | $0.0653 / $0.40 | $0.009599 / $0.0588 | 85.3% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | mistralai | 128K | $2.00 / $6.00 | $0.168 / $0.504 | 91.6% |
| [Mistral: Pixtral Large 2502](https://martllm.com/models/mistralai/pixtral-large-2502) | mistralai | 128K | $2.00 / $6.00 | $1.49 / $4.47 | 25.4–25.5% |
| [Mistral: Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4-0) | mistralai | 524K | $0.735 / $2.21 | $0.301 / $0.9029 | 59% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | mistralai | 256K | $0.40 / $2.00 | $0.0126 / $0.063 | 96.9% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | mistralai | 256K | $0.525 / $1.57 | $0.0882 / $0.2646 | 83.2% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | mistralai | 128K | $0.50 / $1.50 | $0.05775 / $0.1732 | 88.4–88.5% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-4) | mistralai | 256K | $0.165 / $0.66 | $0.1732 / $0.693 | -5% |
| [Voxtral Small 24B 2507](https://martllm.com/models/mistralai/voxtral-small-24b-2507) | mistralai | 32K | $0.105 / $0.315 | $0.07387 / $0.2216 | 29.6% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | mistralai | 256K | $0.09 / $0.25 | $0.0671 / $0.1864 | 25.4% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | mistralai | 128K | $0.21 / $0.21 | $0.108 / $0.108 | 48.5% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | mistralai | 128K | $0.1575 / $0.1575 | $0.03638 / $0.03638 | 76.9% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | mistralai | 128K | $0.105 / $0.105 | $0.02425 / $0.02425 | 76.9% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | mistralai | 32K | $0.04 / $0.04 | $0.0126 / $0.0126 | 68.5% |
| [Meta: Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder) | meta-llama | 1048K | $4.00 / $20.00 | $2.18 / $10.92 | 45.4% |
| [Meta: Muse Spark 1.1](https://martllm.com/models/meta-llama/muse-spark-1.1) | meta-llama | 1048K | $1.25 / $4.25 | $0.7875 / $2.68 | 37% |
| [Meta: Muse Spark 1.2](https://martllm.com/models/meta-llama/muse-spark-1.2) | meta-llama | 1048K | $1.25 / $4.25 | $0.6825 / $2.32 | 45.4% |
| [Meta: Muse Spark 1.3](https://martllm.com/models/meta-llama/muse-spark-1.3) | meta-llama | 1048K | $1.25 / $4.25 | $0.6956 / $2.37 | 44.4% |
| [Meta: Muse Spark Open](https://martllm.com/models/meta-llama/muse-spark-open) | meta-llama | 1048K | $1.25 / $4.25 | $0.7875 / $2.68 | 37% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | meta-llama | 131K | $0.30 / $1.20 | $0.2205 / $0.882 | 26.5% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | meta-llama | 128K | $0.293 / $0.71 | $0.1108 / $0.2684 | 62.2% |
| [Meta: Muse Ember](https://martllm.com/models/meta-llama/muse-ember) | meta-llama | 1048K | $0.10 / $0.50 | $0.0777 / $0.3885 | 22.3% |
| [Llama 3.2 3B](https://martllm.com/models/meta-llama/llama-3.2-3b-instruct) | meta-llama | 128K | $0.05 / $0.33 | $0.04147 / $0.2737 | 17–17.1% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.07875 / $0.1575 | 21.3% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | meta-llama | 1048K | $0.10 / $0.20 | $0.105 / $0.21 | -5% |

</details>

### Image models (per image)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Z-Image Turbo (Venice)](https://martllm.com/models/venice/z-image-turbo) | $0.01 / image | $0.0042 / image | 58% |
| [Venice SD35](https://martllm.com/models/venice/sd35) | $0.01 / image | $0.006825 / image | 31.8% |
| [Chroma (Venice)](https://martllm.com/models/venice/chroma) | $0.01 / image | $0.00735 / image | 26.5% |
| [GPT Image 2.6 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare) | $0.09 / image | $0.008075 / image | 91% |
| [GPT Image 2.6 Flare (image-to-image)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare-edit) | $0.10 / image | $0.008075 / image | 91.9% |
| [Flux 3 Klein](https://martllm.com/models/black-forest-labs/flux-3-klein) | – | $0.0084 / image | – |
| [Flux 1.1 (Venice, legacy)](https://martllm.com/models/venice/flux-1.1) | $0.01 / image | $0.0084 / image | 16% |
| [Stable Diffusion XL (Venice, legacy)](https://martllm.com/models/venice/sdxl) | $0.01 / image | $0.0084 / image | 16% |
| [Seedream 4.5](https://martllm.com/models/bytedance/seedream-4.5) | $0.04 / image | $0.0126 / image | 68.5% |
| [Qwen Image 2.1 Turbo (Venice)](https://martllm.com/models/qwen/venice-qwen-image-2-1-turbo) | $0.02 / image | $0.0147 / image | 26.5% |

### Image models (per megapixel)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [FLUX.2 Klein 4B](https://martllm.com/models/black-forest-labs/flux.2-klein-4b) | $0.015 / megapixel | $0.01145 / megapixel | 23.7% |
| [FLUX.2 Flex](https://martllm.com/models/black-forest-labs/flux.2-flex) | $0.06 / megapixel | $0.04578 / megapixel | 23.7% |

### Video models (per second)

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Grok Imagine Video 1.5](https://martllm.com/models/x-ai/grok-imagine-1-5-image-to-video) | $0.08 / sec | $0.012 / sec | 85% |
| [Grok Imagine](https://martllm.com/models/x-ai/grok-imagine-image-to-video) | $0.05 / sec | $0.012 / sec | 76% |
| [Seedance 1.0 Pro](https://martllm.com/models/bytedance/seedance-1-0-pro) | – | $0.014 / sec | – |
| [Longcat Distilled (image-to-video)](https://martllm.com/models/meituan/longcat-distilled-image-to-video) | $0.018 / sec | $0.01418 / sec | 21.2% |
| [Hailuo 02 Standard Image to Video](https://martllm.com/models/fal-ai/minimax/hailuo-02/standard/image-to-video) | $0.01619 / sec | $0.015 / sec | 7.3% |
| [MiniMax H3](https://martllm.com/models/minimax/minimax-h3) | $0.04 / sec | $0.01592 / sec | 60.2% |
| [MiniMax H3 Reference](https://martllm.com/models/minimax/minimax-h3-reference-to-video) | $0.04 / sec | $0.01592 / sec | 60.2% |
| [Veo 3.1 Fast Text-to-Video](https://martllm.com/models/google/veo3-1-fast-text-to-video) | $0.165 / sec | $0.0175 / sec | 89.4% |
| [Gemini Omni Flash](https://martllm.com/models/google/gemini-omni-flash) | $0.07875 / sec | $0.01769 / sec | 77.5% |
| [Gemini Omni Flash 1.1](https://martllm.com/models/google/gemini-omni-flash-1-1) | $0.07875 / sec | $0.01769 / sec | 77.5% |

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
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | $0.002875 / sec | $0.002194 / sec | 23.7% |
| [Seed Audio 1.0](https://martllm.com/models/byteplus/seed-audio-1-0) | – | $0.003134 / sec | – |
| [ACE-Step 1.5 (Venice)](https://martllm.com/models/venice/ace-step-15) | $0.03 / track | $0.02125 / track | 29.1% |
| [Venice Music Gen (legacy alias)](https://martllm.com/models/venice/music-gen) | – | $0.0327 / track | – |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | $0.046 / 1K chars | $0.04011 / 1K chars | 12.8% |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | – | $0.0436 / track | – |
| [ElevenLabs TTS v4](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4) | $0.092 / 1K chars | $0.07521 / 1K chars | 18.2% |

### Speech models

| Model | Official price | MartLLM price | Below list |
|---|---|---|---|
| [Kokoro Text to Speech (Venice)](https://martllm.com/models/venice/kokoro-tts) | $0.0035 / 1K chars | $0.003052 / 1K chars | 12.8% |
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | – | $0.003052 / 1K chars | – |
| [Inworld 1.5 Max TTS](https://martllm.com/models/inworld/tts-inworld-1-5-max) | $0.0125 / 1K chars | $0.0109 / 1K chars | 12.8% |
| [xAI v1 TTS](https://martllm.com/models/x-ai/tts-xai-v1) | $0.01875 / 1K chars | $0.01635 / 1K chars | 12.8% |
| [Chatterbox HD TTS](https://martllm.com/models/resemble-ai/tts-chatterbox-hd) | $0.05 / 1K chars | $0.0436 / 1K chars | 12.8% |
| [Orpheus TTS](https://martllm.com/models/canopy-labs/tts-orpheus) | $0.0625 / 1K chars | $0.0545 / 1K chars | 12.8% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://martllm.com/models/venice/elevenlabs-tts-turbo-v2-5) | $0.0625 / 1K chars | $0.0545 / 1K chars | 12.8% |
| [Qwen3 0.6B TTS](https://martllm.com/models/qwen/tts-qwen3-0-6b) | $0.0875 / 1K chars | $0.0763 / 1K chars | 12.8% |
| [Qwen3 1.7B TTS](https://martllm.com/models/qwen/tts-qwen3-1-7b) | $0.1125 / 1K chars | $0.08461 / 1K chars | 24.8% |
| [MiniMax Speech 02 HD TTS](https://martllm.com/models/minimax/tts-minimax-speech-02-hd) | $0.125 / 1K chars | $0.1076 / 1K chars | 13.9% |

## Prices under review

The catalog's official price for these 1 models failed a sanity check (see `list_price_review_reason`), so it is left out, with no % below list, until it is checked against the maker's own page. The MartLLM price is still listed.

| Model | Category | Why |
|---|---|---|
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | speech | more than 10x off the median speech price per 1K characters |

## Biggest drops this week (2026-11-15 to 2026-11-22)

From MartLLM's daily catalog snapshots (`GET /api/v1/public/price-changes`). Text: $ per 1M input / output tokens, sorted by the larger of the two moves.

### Official list price cuts

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | text | $0.70 / $0.71 | $0.293 / $0.71 | in −58% / out 0% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.30 / $1.20 | $0.147 / $0.60 | in −51% / out −50% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | text | $2.80 / $8.80 | $1.68 / $5.28 | −40% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.44 / $1.32 | $0.2695 / $0.8085 | −39% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.30 / $1.20 | $0.195 / $0.75 | in −35% / out −38% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $1.32 / $3.96 | $1.28 / $2.56 | in −3% / out −35% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | text | $0.20 / $1.10 | $0.14 / $0.86 | in −30% / out −22% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.15 / $0.60 | $0.11 / $0.44 | −27% |
| [Particle AI: Particle-1](https://martllm.com/models/particle-ai/particle-1) | text | $0.06 / $0.50 | $0.0525 / $0.375 | in −12% / out −25% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | text | $0.075 / $0.30 | $0.0725 / $0.25 | in −3% / out −17% |

### MartLLM price drops

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MiniMax M2.1](https://martllm.com/models/minimax/minimax-m2.1) | text | $0.315 / $1.26 | $0.003045 / $0.009975 | −99% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://martllm.com/models/nvidia/nemotron-nano-12b-v2) | text | $0.068 / $0.204 | $0.0042 / $0.0126 | −94% |
| [GPT Image 2.6 Flare (image-to-image)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare-edit) | image | $0.10 / image | $0.008075 / image | −92% |
| [GPT Image 2.6 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare) | image | $0.09 / image | $0.008075 / image | −91% |
| [Veo 3.1 Fast Text-to-Video](https://martllm.com/models/google/veo3-1-fast-text-to-video) | video | $0.165 / sec | $0.0175 / sec | −89% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | text | $0.0112 / $0.048 | $0.00147 / $0.0063 | −87% |
| [Wan 3.0 Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-image-to-video) | video | $0.26 / sec | $0.05323 / sec | −80% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | text | $0.06 / $0.30 | $0.0126 / $0.063 | −79% |
| [Nano Banana Pro (image-to-image)](https://martllm.com/models/google/nano-banana-pro-edit) | image | $0.09 / image | $0.019 / image | −79% |
| [Nano Banana Pro (Venice)](https://martllm.com/models/venice/nano-banana-pro) | image | $0.09 / image | $0.019 / image | −79% |

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
