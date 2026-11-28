# Changelog

Price changes between daily snapshots of [`prices.json`](prices.json), newest first.
"Official list price" = the model maker's price as carried in the catalog (see [SOURCES](README.md#sources)).
"MartLLM price" = what a buyer can count on at snapshot time (per side, the higher of the best live seller and the listed price); it moves during the day.
Text prices are $ per 1M input / output tokens. Every day's full table is in [`history/`](history/).

## 2026-11-28 (vs 2026-11-27)

**Official list price changes (29)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MiMo-V2.6-Flash-MOPD](https://martllm.com/models/xiaomi/mimo-v2.6-flash-mopd) | text | $0.50 / $1.00 | $0.35 / $0.70 | −30% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.2695 / $0.8085 | $0.2156 / $0.6468 | −20% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.125 / $0.45 | $0.12 / $0.40 | in −4% / out −11% |
| [Thinking Machines: Inkling 2 Mini](https://martllm.com/models/thinking-machines/inkling-2-mini) | text | $0.075 / $0.30 | $0.0675 / $0.27 | −10% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.2112 / $0.84 | $0.21 / $0.78 | in −1% / out −7% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | text | $0.10 / $0.32 | $0.10 / $0.30 | in 0% / out −6% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | text | $0.925 / $2.71 | $0.95 / $2.55 | in +3% / out −6% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | text | $1.33 / $4.18 | $1.26 / $3.96 | −5% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | text | $1.33 / $4.18 | $1.26 / $3.96 | −5% |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | text | $1.19 / $4.29 | $1.16 / $4.29 | in −3% / out 0% |
| [Seedance 1.0 Pro Fast](https://martllm.com/models/bytedance/seedance-1-0-pro-fast-image-to-video) | video | – | $0.018 / sec |  |
| [ElevenLabs Scribe v2 (STT)](https://martllm.com/models/elevenlabs/elevenlabs-scribe-v2) | transcription | – | $0.01002 / minute |  |
| [Ideogram V2](https://martllm.com/models/ideogram/ideogram-v2) | image | – | $0.08 / image |  |
| [Ideogram V2 Turbo](https://martllm.com/models/ideogram/ideogram-v2-turbo) | image | – | $0.05 / image |  |
| [Kling 2.1 Pro](https://martllm.com/models/kling/kling-2-1-pro-image-to-video) | video | – | $0.088 / sec |  |
| [Kling 2.1 Standard](https://martllm.com/models/kling/kling-2-1-standard-image-to-video) | video | – | $0.0505 / sec |  |
| [Kling V3 Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-standard-image-to-video) | video | – | $0.14 / sec |  |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | – | $0.1383 / sec |  |
| [Qwen Image 2.1](https://martllm.com/models/qwen/qwen-image-2-1) | image | – | $0.02 / image |  |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | music | – | $0.002875 / sec |  |
| [Flux 1.1 Pro (Venice, legacy)](https://martllm.com/models/venice/flux-1.1-pro) | image | – | $0.03 / image |  |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | music | – | $0.04 / track |  |
| [Venice Music Gen (legacy alias)](https://martllm.com/models/venice/music-gen) | music | – | $0.03 / track |  |
| [Stable Diffusion XL (Venice, legacy)](https://martllm.com/models/venice/sdxl) | image | – | $0.01 / image |  |
| [xAI Speech to Text v1 (Venice)](https://martllm.com/models/venice/xai-stt-v1) | transcription | – | $0.001889 / minute |  |
| [Vidu Q3 Pro](https://martllm.com/models/vidu/viduq3-pro) | video | – | $0.056 / sec |  |
| [Wan 2.7 Text-to-Video](https://martllm.com/models/wan/wan-2-7-text-to-video) | video | – | $0.11 / sec |  |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | text | $0.70 / $3.41 | $0.70 / $3.42 | 0% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.15 / $0.70 | $0.1575 / $0.71 | in +5% / out +1% |

**New models (496)**

| Model | Category | Official price | MartLLM price |
|---|---|---|---|
| [ACE-Step](https://martllm.com/models/ace-step/ace-step) | music | – | $0.0002 / sec |
| [Molmo 2 Image Captioner](https://martllm.com/models/allenai/molmo-2-image-captioner) | other | – | $0.001904 / request |
| [Molmo 2 Image Content Moderator](https://martllm.com/models/allenai/molmo-2-image-content-moderator) | other | – | $0.002856 / request |
| [Molmo 2 Image Q&A](https://martllm.com/models/allenai/molmo-2-image-qa) | other | – | $0.001904 / request |
| [Molmo 2 Prompt Optimizer](https://martllm.com/models/allenai/molmo-2-prompt-optimizer) | other | – | $0.002856 / request |
| [Molmo 2 Text Content Moderator](https://martllm.com/models/allenai/molmo-2-text-content-moderator) | other | – | $0.002856 / request |
| [Molmo 2 Video Captioner](https://martllm.com/models/allenai/molmo-2-video-captioner) | other | $0.001 / sec | $0.000952 / sec |
| [Molmo 2 Video Content Moderator](https://martllm.com/models/allenai/molmo-2-video-content-moderator) | other | – | $0.002856 / request |
| [Molmo 2 Video Q&A](https://martllm.com/models/allenai/molmo-2-video-qa) | other | $0.001 / sec | $0.000952 / sec |
| [Molmo 2 Video Understanding](https://martllm.com/models/allenai/molmo-2-video-understanding) | other | $0.001 / sec | $0.000952 / sec |
| [Claude Opus 4.6 Fast](https://martllm.com/models/anthropic/claude-opus-4.6-fast) | text | – | $18.90 / $94.50 |
| [Claude Opus 4.7 Fast](https://martllm.com/models/anthropic/claude-opus-4.7-fast) | text | – | $18.90 / $94.50 |
| [PaddleOCR-VL](https://martllm.com/models/baidu/paddleocr-vl) | other | – | $0.00952 / request |
| [FLUX.1 Pro Erase](https://martllm.com/models/black-forest-labs/flux-1-pro-erase) | image | – | $0.08 / image |
| [FLUX 3 Video Extend](https://martllm.com/models/black-forest-labs/flux-3-video-extend) | video | – | $0.43 / sec |
| [FLUX.1 Fill Dev](https://martllm.com/models/black-forest-labs/flux-fill-dev) | image | – | $0.035 / image |
| [FLUX Finetune](https://martllm.com/models/black-forest-labs/flux-finetune) | image | $0.06 / image | $0.05376 / image |
| [FLUX.1 Krea Dev](https://martllm.com/models/black-forest-labs/flux-krea-dev) | image | $0.02 / image | $0.01904 / image |
| [FLUX Pro 1.0 Canny](https://martllm.com/models/black-forest-labs/flux-pro-1-0-canny) | image | $0.075 / image | $0.0672 / image |
| [FLUX Pro 1.0 Fill](https://martllm.com/models/black-forest-labs/flux-pro-1-0-fill) | image | $0.075 / image | $0.0168 / image |
| [FLUX Pro 1.0 Fill Finetuned](https://martllm.com/models/black-forest-labs/flux-pro-1-0-fill-finetuned) | image | $0.12 / image | $0.1075 / image |
| [FLUX Pro Finetuned](https://martllm.com/models/black-forest-labs/flux-pro-finetuned) | image | $0.09 / image | $0.08064 / image |
| [FLUX.1 Redux Dev](https://martllm.com/models/black-forest-labs/flux-redux-dev) | image | – | $0.025 / image |
| [FLUX.1 [schnell]](https://martllm.com/models/black-forest-labs/flux-schnell) | image | – | $0.002856 / image |
| [Bria Eraser](https://martllm.com/models/bria/bria-eraser) | image | – | $0.04 / image |
| [Bria Extract Object](https://martllm.com/models/bria/bria-extract-object) | image | – | $0.02 / image |
| [Bria Generate Background](https://martllm.com/models/bria/bria-generate-background) | image | $0.04 / image | $0.03808 / image |
| [Bria Increase Resolution](https://martllm.com/models/bria/bria-increase-resolution) | image | – | $0.04 / image |
| [Bria Remove Background 3.0](https://martllm.com/models/bria/bria-remove-background-3-0) | image | – | $0.018 / image |
| [Bria Guided Remove Background](https://martllm.com/models/bria/bria-remove-background-guided) | image | – | $0.03 / image |
| [Embed Product](https://martllm.com/models/bria/embed-product) | image | – | $0.04 / image |
| [Eraser](https://martllm.com/models/bria/eraser) | image | – | $0.04 / image |
| [Expand](https://martllm.com/models/bria/expand) | image | – | $0.04 / image |
| [Extract Object](https://martllm.com/models/bria/extract-object) | image | – | $0.02 / image |
| [Fibo Colorize](https://martllm.com/models/bria/fibo-colorize) | image | – | $0.04 / image |
| [Fibo Edit Genfill](https://martllm.com/models/bria/fibo-edit-genfill) | image | $0.04 / image | $0.03808 / image |
| [Fibo Relight](https://martllm.com/models/bria/fibo-relight) | image | – | $0.04 / image |
| [Fibo Reseason](https://martllm.com/models/bria/fibo-reseason) | image | – | $0.04 / image |
| [Fibo Restore](https://martllm.com/models/bria/fibo-restore) | image | – | $0.04 / image |
| [FIBO Video Background Remover](https://martllm.com/models/bria/fibo-video-background-remover) | video | – | $0.05 / sec |
| [Generate Background](https://martllm.com/models/bria/generate-background) | image | – | $0.04 / image |
| [Increase Resolution](https://martllm.com/models/bria/increase-resolution) | image | – | $0.04 / image |
| [Product Dimensions](https://martllm.com/models/bria/product-dimensions) | image | – | $0.04 / image |
| [Product Holding](https://martllm.com/models/bria/product-holding) | image | – | $0.04 / image |
| [Remove Background](https://martllm.com/models/bria/remove-background) | image | – | $0.018 / image |
| [Remove Background 3.0](https://martllm.com/models/bria/remove-background-3-0) | image | – | $0.018 / image |
| [Remove Background Guided](https://martllm.com/models/bria/remove-background-guided) | image | – | $0.03 / image |
| [Bria Video Eraser](https://martllm.com/models/bria/video-eraser-prompt) | video | – | $0.14 / sec |
| [Virtual Try On](https://martllm.com/models/bria/virtual-try-on) | image | – | $0.04 / image |
| [Depth Anything 3](https://martllm.com/models/bytedance/depth-anything-v3-image) | image | – | $0.005 / image |
| [Depth Anything V3 Video](https://martllm.com/models/bytedance/depth-anything-v3-video) | video | – | $0.005 / sec |
| [Depth Anything Video](https://martllm.com/models/bytedance/depth-anything-video) | video | – | $0.005 / sec |
| [DreamActor V2](https://martllm.com/models/bytedance/dreamactor-v2) | video | – | $0.05 / sec |
| [InfiniteYou Face Swap](https://martllm.com/models/bytedance/infinite-you) | image | – | $0.05 / image |
| [LatentSync](https://martllm.com/models/bytedance/latentsync) | video | – | $0.03 / sec |
| [ByteDance Lipsync](https://martllm.com/models/bytedance/lipsync-audio-to-video) | video | – | $0.03 / sec |
| [OmniHuman](https://martllm.com/models/bytedance/omnihuman) | video | – | $0.12 / sec |
| [OmniHuman 1.5](https://martllm.com/models/bytedance/omnihuman-1-5) | video | $0.16 / sec | $0.1512 / sec |
| [Seed Audio 1.0](https://martllm.com/models/bytedance/seed-audio-1-0) | music | $0.002875 / sec | $0.001771 / sec |
| [Seed Audio 1.0 (text to audio)](https://martllm.com/models/bytedance/seed-audio-1-0-text-to-audio) | other | $0.30 / request | $0.2856 / request |
| [Seed Speech TTS 2.0](https://martllm.com/models/bytedance/seed-speech-tts-2-0) | speech | – | $0.06 / 1K chars |
| [Seed3D 2.0 Image to 3D](https://martllm.com/models/bytedance/seed3d-2-0-image-to-3d) | other | $0.40 / request | $0.3808 / request |
| [Seedance 1.5 Pro Fast Video Extend](https://martllm.com/models/bytedance/seedance-1-5-pro-fast-video-extend) | video | – | $0.02 / sec |
| [Seedance 1.5 Pro Video Extend](https://martllm.com/models/bytedance/seedance-1-5-pro-video-extend) | video | – | $0.026 / sec |
| [Seedance 2.0 Fast Turbo (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-fast-reference-to-video-turbo) | video | $0.12 / sec | $0.1142 / sec |
| [Seedance 2.0 Fast Video Extend](https://martllm.com/models/bytedance/seedance-2-0-fast-video-extend) | video | – | $0.20 / sec |
| [Seedance 2.0 Mini Turbo (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-reference-to-video-turbo) | video | $0.08 / sec | $0.07616 / sec |
| [Seedance 2.0 Mini Video Extend](https://martllm.com/models/bytedance/seedance-2-0-mini-video-extend) | video | – | $0.12 / sec |
| [Seedance 2.0 Turbo (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-reference-to-video-turbo) | video | $0.14 / sec | $0.1333 / sec |
| [Seedance 2.0 Video Extend](https://martllm.com/models/bytedance/seedance-2-0-video-extend) | video | – | $0.24 / sec |
| [Seedance 2.5 Flash Motion Control](https://martllm.com/models/bytedance/seedance-2-5-flash-motion-control) | video | – | $0.30 / sec |
| [Seedance 2.5 Flash Turbo (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-5-flash-reference-to-video-turbo) | video | $0.14 / sec | $0.1333 / sec |
| [Seedance 2.5 Flash Talking Avatar](https://martllm.com/models/bytedance/seedance-2-5-flash-talking-avatar) | video | – | $0.15 / sec |
| [Seedance 2.5 Motion Control](https://martllm.com/models/bytedance/seedance-2-5-motion-control) | video | – | $0.44 / sec |
| [Seedance 2.5 Turbo (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-5-reference-to-video-turbo) | video | $0.20 / sec | $0.1904 / sec |
| [Seedance 2.5 Talking Avatar](https://martllm.com/models/bytedance/seedance-2-5-talking-avatar) | video | – | $0.22 / sec |
| [Seedream V5.0 Flash Layer Decomposition](https://martllm.com/models/bytedance/seedream-v5-0-flash-layer-decomposition) | image | – | $0.459 / image |
| [Seedream V5.0 Pro Layer Decomposition](https://martllm.com/models/bytedance/seedream-v5-0-pro-layer-decomposition) | image | – | $0.75 / image |
| [SeedVR2 Image Upscaler](https://martllm.com/models/bytedance/seedvr2-image-upscaler) | image | – | $0.01 / image |
| [Waver 1.0 (image-to-video)](https://martllm.com/models/bytedance/waver-1-0-image-to-video) | video | $0.06 / sec | $0.05712 / sec |
| [Clarity Creative Upscaler](https://martllm.com/models/clarity-ai/clarity-creative-upscaler) | image | – | $0.05 / image |
| [Clarity Crystal Upscaler](https://martllm.com/models/clarity-ai/clarity-crystal-upscaler) | image | – | $0.05 / image |
| [Clarity Flux Upscaler](https://martllm.com/models/clarity-ai/clarity-flux-upscaler) | image | – | $0.20 / image |
| [Clarity Pro Upscaler](https://martllm.com/models/clarity-ai/clarity-pro-upscaler) | image | – | $0.12 / image |
| [Crystal Video Upscaler](https://martllm.com/models/clarity-ai/crystal-video-upscaler) | video | – | $0.20 / sec |
| [BitDance 14B](https://martllm.com/models/community/bitdance-14b) | image | $0.05 / image | $0.0476 / image |
| [Depth Pro 2 Video](https://martllm.com/models/community/depth-pro-2-video) | video | – | $0.01 / sec |
| [Jib Mix Qwen Image](https://martllm.com/models/community/jib-mix-qwen-image) | image | $0.02 / image | $0.01904 / image |
| [OpenJutsu Character Swap](https://martllm.com/models/community/openjutsu-character-swap) | video | – | $0.20 / sec |
| [OpenJutsu Object Swap](https://martllm.com/models/community/openjutsu-object-swap) | video | – | $0.20 / sec |
| [Prefect Pony XL](https://martllm.com/models/community/prefect-pony-xl) | image | $0.015 / image | $0.01428 / image |
| [ElevenLabs Dubbing](https://martllm.com/models/elevenlabs/dubbing) | video | – | $0.01 / sec |
| [Eleven v3 with Timing](https://martllm.com/models/elevenlabs/eleven-v3-with-timing) | other | $0.20 / 1K chars | $0.1904 / 1K chars |
| [ElevenLabs Audio Isolation](https://martllm.com/models/elevenlabs/elevenlabs-audio-isolation) | music | – | $0.001833 / sec |
| [ElevenLabs Forced Alignment](https://martllm.com/models/elevenlabs/elevenlabs-forced-alignment) | other | $0.30 / request | $0.2856 / request |
| [ElevenLabs Scribe v3 (STT)](https://martllm.com/models/elevenlabs/elevenlabs-scribe-v3) | transcription | – | $0.01 / minute |
| [ElevenLabs Sound Effects v3](https://martllm.com/models/elevenlabs/elevenlabs-sound-effects-v3) | music | – | $0.002 / sec |
| [ElevenLabs Voice Changer (your recording)](https://martllm.com/models/elevenlabs/elevenlabs-voice-changer-tool) | music | – | $0.004 / sec |
| [Lyria 3.5](https://martllm.com/models/google-deepmind/lyria-3-5) | music | – | $0.10 / track |
| [Lyria 3 Clip](https://martllm.com/models/google-deepmind/lyria-3-clip) | music | – | $0.04 / track |
| [Gemini 2.5 Flash TTS](https://martllm.com/models/google/gemini-2-5-flash-tts) | speech | – | $0.02 / 1K chars |
| [Gemini 2.5 Pro TTS](https://martllm.com/models/google/gemini-2-5-pro-tts) | speech | – | $0.04 / 1K chars |
| [Gemini 3.8 Flash Lite TTS](https://martllm.com/models/google/gemini-3-8-flash-lite-tts) | speech | – | $0.04 / 1K chars |
| [Gemini 3.8 Flash TTS](https://martllm.com/models/google/gemini-3-8-flash-tts) | speech | – | $0.05 / 1K chars |
| [Veo 3.1 Fast Video Extend](https://martllm.com/models/google/veo-3-1-fast-video-extend) | video | – | $0.1714 / sec |
| [Veo 3.1 Video Extend](https://martllm.com/models/google/veo-3-1-video-extend) | video | – | $0.4571 / sec |
| [Veo 3.1 Lite Text to Video](https://martllm.com/models/google/veo-3.1-lite) | video | $0.02857 / sec | $0.0272 / sec |
| [HappyHorse 1.0 Video Extend](https://martllm.com/models/happyhorse/happyhorse-1-0-video-extend) | video | – | $0.14 / sec |
| [HeartMuLa Music](https://martllm.com/models/heartmula/heartmula-music) | music | – | $0.10 / track |
| [HeartMuLa Transcribe Lyrics](https://martllm.com/models/heartmula/heartmula-transcribe-lyrics) | other | $0.05 / request | $0.0476 / request |
| [HeyGen Avatar 6](https://martllm.com/models/heygen/heygen-avatar-6) | video | – | $0.12 / sec |
| [HeyGen Avatar 6 Turbo](https://martllm.com/models/heygen/heygen-avatar-6-turbo) | video | – | $0.06 / sec |
| [HeyGen Avatar IV](https://martllm.com/models/heygen/heygen-avatar-iv) | video | – | $0.045 / sec |
| [HeyGen Video Translate](https://martllm.com/models/heygen/heygen-video-translate) | video | – | $0.08 / sec |
| [HeyGen Voice](https://martllm.com/models/heygen/heygen-voice) | speech | – | $0.035 / 1K chars |
| [HeyGen Voice Turbo](https://martllm.com/models/heygen/heygen-voice-turbo) | speech | – | $0.005 / 1K chars |
| [Hitem3D 3.0 Image to 3D](https://martllm.com/models/hitem3d/hi3d-3-0-image-to-3d) | other | $2.52 / request | $2.40 / request |
| [Hitem3D 3.0 Multi-View to 3D](https://martllm.com/models/hitem3d/hi3d-3-0-multi-view-to-3d) | other | $2.52 / request | $2.40 / request |
| [Rodin 2.5 Image to 3D](https://martllm.com/models/hyper3d/rodin-2-5-image-to-3d) | other | $0.48 / request | $0.457 / request |
| [Rodin 2.5 Text to 3D](https://martllm.com/models/hyper3d/rodin-2-5-text-to-3d) | other | $0.48 / request | $0.457 / request |
| [Ideogram Remove Background](https://martllm.com/models/ideogram/ideogram-remove-background) | image | – | $0.01 / image |
| [Inworld Realtime TTS 2](https://martllm.com/models/inworld/inworld-realtime-tts-2) | speech | – | $0.05 / 1K chars |
| [Inworld TTS 1.5 Mini](https://martllm.com/models/inworld/tts-inworld-1-5-mini) | speech | – | $0.03 / 1K chars |
| [Kling 1.6 Pro Multi-Image (image-to-video)](https://martllm.com/models/kling/kling-1-6-pro-multi-image-to-video) | video | – | $0.08568 / sec |
| [Kling 1.6 Standard Multi-Image (image-to-video)](https://martllm.com/models/kling/kling-1-6-standard-multi-image-to-video) | video | – | $0.0476 / sec |
| [Kling 2.6 Pro Motion Control](https://martllm.com/models/kling/kling-2-6-pro-motion-control) | video | – | $0.112 / sec |
| [Kling 2.6 Standard Motion Control](https://martllm.com/models/kling/kling-2-6-standard-motion-control) | video | – | $0.07 / sec |
| [Kling Image Expansion](https://martllm.com/models/kling/kling-image-expand) | image | – | $0.02979 / image |
| [Kling Lipsync](https://martllm.com/models/kling/kling-lipsync-audio-to-video) | video | – | $0.03 / sec |
| [Kling Text to Audio](https://martllm.com/models/kling/kling-text-to-audio) | music | – | $0.035 / track |
| [Kling V1 AI Avatar Pro](https://martllm.com/models/kling/kling-v1-ai-avatar-pro) | video | – | $0.20 / sec |
| [Kling V1 AI Avatar Standard](https://martllm.com/models/kling/kling-v1-ai-avatar-standard) | video | – | $0.05 / sec |
| [Kling v2.6 Create Voice](https://martllm.com/models/kling/kling-v2-6-create-voice) | other | $0.035 / request | $0.03332 / request |
| [Kling V2 AI Avatar Pro](https://martllm.com/models/kling/kling-v2-ai-avatar-pro) | video | – | $0.112 / sec |
| [Kling V2 AI Avatar Standard](https://martllm.com/models/kling/kling-v2-ai-avatar-standard) | video | – | $0.056 / sec |
| [Kling 3.0 Pro Motion Control](https://martllm.com/models/kling/kling-v3-pro-motion-control) | video | – | $0.168 / sec |
| [Kling 3.0 Standard Motion Control](https://martllm.com/models/kling/kling-v3-standard-motion-control) | video | – | $0.126 / sec |
| [Kling 4.0 Video Extend](https://martllm.com/models/kling/kling-v4-video-extend) | video | – | $0.157 / sec |
| [LTX 2 19B Lipsync](https://martllm.com/models/lightricks/ltx-2-19b-lipsync) | video | – | $0.015 / sec |
| [LTX 2.3 Fast Image to Video](https://martllm.com/models/lightricks/ltx-2-3-fast-image-to-video) | video | $0.05714 / sec | $0.0544 / sec |
| [LTX 2.3 Fast Text to Video](https://martllm.com/models/lightricks/ltx-2-3-fast-text-to-video) | video | $0.05714 / sec | $0.0544 / sec |
| [LTX 2.3 Lipsync](https://martllm.com/models/lightricks/ltx-2-3-lipsync) | video | – | $0.02 / sec |
| [LTX 2.3 Text to Video](https://martllm.com/models/lightricks/ltx-2-3-text-to-video) | video | $0.07619 / sec | $0.07253 / sec |
| [LTX 2.3 Video Extend](https://martllm.com/models/lightricks/ltx-2-3-video-extend) | video | – | $0.06 / sec |
| [LTX 2 Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-full-text-to-video) | video | – | $0.09275 / sec |
| [LTX Video 0.9.7 (image-to-video)](https://martllm.com/models/lightricks/ltx-video-0-9-7-image-to-video) | video | – | $0.04 / sec |
| [SteadyDancer](https://martllm.com/models/mcg-nju/steadydancer) | video | – | $0.04 / sec |
| [RIFE Video Interpolation](https://martllm.com/models/megvii/rife) | video | – | $0.01 / sec |
| [InfiniteTalk](https://martllm.com/models/meigen-ai/infinitetalk) | video | – | $0.03 / sec |
| [InfiniteTalk Fast](https://martllm.com/models/meigen-ai/infinitetalk-fast) | video | – | $0.015 / sec |
| [InfiniteTalk Video to Video](https://martllm.com/models/meigen-ai/infinitetalk-video-to-video) | video | – | $0.03 / sec |
| [MultiTalk](https://martllm.com/models/meigen-ai/multitalk) | video | – | $0.03 / sec |
| [LongCat Avatar](https://martllm.com/models/meituan/longcat-avatar) | video | – | $0.04 / sec |
| [LongCat Avatar 1.5](https://martllm.com/models/meituan/longcat-avatar-1-5) | video | – | $0.04 / sec |
| [LongCat Avatar 1.6](https://martllm.com/models/meituan/longcat-avatar-1-6) | video | – | $0.04 / sec |
| [Meshy 6 Image to 3D](https://martllm.com/models/meshy/meshy-6-image-to-3d) | other | $1.20 / request | $1.14 / request |
| [Meshy 6 Lite Image to 3D](https://martllm.com/models/meshy/meshy-6-lite-image-to-3d) | other | $0.60 / request | $0.5712 / request |
| [Meshy 6 Lite Multi-Image to 3D](https://martllm.com/models/meshy/meshy-6-lite-multi-image-to-3d) | other | $0.60 / request | $0.5712 / request |
| [Meshy 6 Lite Retexture](https://martllm.com/models/meshy/meshy-6-lite-retexture) | other | $0.40 / request | $0.3808 / request |
| [Meshy 6 Lite Text to 3D](https://martllm.com/models/meshy/meshy-6-lite-text-to-3d) | other | $0.60 / request | $0.5712 / request |
| [Meshy 6 Multi-Image to 3D](https://martllm.com/models/meshy/meshy-6-multi-image-to-3d) | other | $1.20 / request | $1.14 / request |
| [Meshy 6 Retexture](https://martllm.com/models/meshy/meshy-6-retexture) | other | $0.40 / request | $0.3808 / request |
| [Meshy 6 Text to 3D](https://martllm.com/models/meshy/meshy-6-text-to-3d) | other | $1.20 / request | $1.14 / request |
| [Meshy 7.1 Image to 3D](https://martllm.com/models/meshy/meshy-7-1-image-to-3d) | other | $1.20 / request | $1.14 / request |
| [Meshy 7.1 Multi-Image to 3D](https://martllm.com/models/meshy/meshy-7-1-multi-image-to-3d) | other | $1.20 / request | $1.14 / request |
| [Meshy 7.1 Text to 3D](https://martllm.com/models/meshy/meshy-7-1-text-to-3d) | other | $1.20 / request | $1.14 / request |
| [Meshy 7 Image to 3D](https://martllm.com/models/meshy/meshy-7-image-to-3d) | other | $1.20 / request | $1.14 / request |
| [Meshy 7 Multi-Image to 3D](https://martllm.com/models/meshy/meshy-7-multi-image-to-3d) | other | $1.20 / request | $1.14 / request |
| [Meshy 7 Retexture](https://martllm.com/models/meshy/meshy-7-retexture) | other | $0.40 / request | $0.3808 / request |
| [Meshy 7 Text to 3D](https://martllm.com/models/meshy/meshy-7-text-to-3d) | other | $1.20 / request | $1.14 / request |
| [Meshy Animation](https://martllm.com/models/meshy/meshy-animation) | other | $0.32 / request | $0.3046 / request |
| [Meshy Convert](https://martllm.com/models/meshy/meshy-convert) | other | $0.04 / request | $0.03808 / request |
| [Meshy N1 Retexture](https://martllm.com/models/meshy/meshy-n1-retexture) | other | $0.40 / request | $0.3808 / request |
| [Meshy Printability Analysis](https://martllm.com/models/meshy/meshy-print-analyze) | other | $0.04 / request | $0.03808 / request |
| [Meshy Print Multi-Color](https://martllm.com/models/meshy/meshy-print-multi-color) | other | $0.40 / request | $0.3808 / request |
| [Meshy Print Repair](https://martllm.com/models/meshy/meshy-print-repair) | other | $0.40 / request | $0.3808 / request |
| [Meshy Relief](https://martllm.com/models/meshy/meshy-relief) | other | $0.80 / request | $0.7616 / request |
| [Meshy Remesh](https://martllm.com/models/meshy/meshy-remesh) | other | $0.20 / request | $0.1904 / request |
| [Meshy Resize](https://martllm.com/models/meshy/meshy-resize) | other | $0.04 / request | $0.03808 / request |
| [Meshy Rigging](https://martllm.com/models/meshy/meshy-rigging) | other | $0.20 / request | $0.1904 / request |
| [Meshy T2.5 Image to 3D](https://martllm.com/models/meshy/meshy-t2-5-image-to-3d) | other | $0.60 / request | $0.5712 / request |
| [Meshy T2.5 Text to 3D](https://martllm.com/models/meshy/meshy-t2-5-text-to-3d) | other | $0.60 / request | $0.5712 / request |
| [Meshy T2 Image to 3D](https://martllm.com/models/meshy/meshy-t2-image-to-3d) | other | $0.60 / request | $0.5712 / request |
| [Meshy T2 Text to 3D](https://martllm.com/models/meshy/meshy-t2-text-to-3d) | other | $0.60 / request | $0.5712 / request |
| [Meshy UV Unwrap](https://martllm.com/models/meshy/meshy-uv-unwrap) | other | $0.20 / request | $0.1904 / request |
| [SAM 3](https://martllm.com/models/meta/sam3-image) | image | – | $0.005 / image |
| [SAM 3 Image RLE](https://martllm.com/models/meta/sam3-image-rle) | other | – | $0.00476 / request |
| [SAM 3 Video](https://martllm.com/models/meta/sam3-video) | video | – | $0.01 / sec |
| [SAM 3 Video RLE](https://martllm.com/models/meta/sam3-video-rle) | other | $0.01 / sec | $0.00952 / sec |
| [TRELLIS.2 Image to 3D](https://martllm.com/models/microsoft/trellis-2-image-to-3d) | other | $0.20 / request | $0.1904 / request |
| [VibeVoice](https://martllm.com/models/microsoft/vibevoice) | speech | – | $0.12 / request |
| [Hailuo 02 Standard Image to Video](https://martllm.com/models/minimax/hailuo-02-standard-image-to-video) | video | $0.01619 / sec | $0.01541 / sec |
| [Hailuo 02 Standard Text to Video](https://martllm.com/models/minimax/hailuo-02-standard-text-to-video) | video | $0.04286 / sec | $0.028 / sec |
| [MiniMax H3 Video Extend](https://martllm.com/models/minimax/minimax-h3-video-extend) | video | – | $0.08 / sec |
| [MiniMax Lyrics](https://martllm.com/models/minimax/minimax-lyrics) | other | – | $0.01904 / request |
| [MiniMax Music 3.0](https://martllm.com/models/minimax/minimax-music-3-0) | music | – | $0.15 / track |
| [MiniMax Music Cover](https://martllm.com/models/minimax/minimax-music-cover) | music | – | $0.15 / track |
| [MiniMax Video-01](https://martllm.com/models/minimax/minimax-video-01) | video | $0.10 / sec | $0.0952 / sec |
| [MiniMax Voice Clone](https://martllm.com/models/minimax/minimax-voice-clone) | other | $1.60 / request | $1.52 / request |
| [MiniMax Voice Design](https://martllm.com/models/minimax/minimax-voice-design) | other | $3.10 / request | $2.95 / request |
| [MiniMax Speech 02 Turbo](https://martllm.com/models/minimax/speech-02-turbo) | speech | – | $0.06 / 1K chars |
| [MiniMax Speech 2.5 HD Preview](https://martllm.com/models/minimax/speech-2-5-hd-preview) | speech | – | $0.06 / 1K chars |
| [MiniMax Speech 2.5 Turbo Preview](https://martllm.com/models/minimax/speech-2-5-turbo-preview) | speech | – | $0.04 / 1K chars |
| [MiniMax Speech 2.6 HD](https://martllm.com/models/minimax/speech-2-6-hd) | speech | – | $0.10 / 1K chars |
| [MiniMax Speech 2.6 Turbo](https://martllm.com/models/minimax/speech-2-6-turbo) | speech | – | $0.06 / 1K chars |
| [MiniMax Speech 2.8 HD](https://martllm.com/models/minimax/speech-2-8-hd) | speech | – | $0.10 / 1K chars |
| [MiniMax Speech 2.8 Turbo](https://martllm.com/models/minimax/speech-2-8-turbo) | speech | – | $0.06 / 1K chars |
| [Mirelo SFX 1.6](https://martllm.com/models/mirelo-ai/mirelo-sfx-1-6) | music | – | $0.02 / sec |
| [Mirelo SFX 2.0](https://martllm.com/models/mirelo-ai/mirelo-sfx-2-0) | music | – | $0.02 / sec |
| [Moondream 3 Preview Caption](https://martllm.com/models/moondream/moondream3-preview-caption) | other | – | $0.00476 / request |
| [Moondream 3 Preview Detect](https://martllm.com/models/moondream/moondream3-preview-detect) | other | – | $0.000952 / request |
| [Moondream 3 Preview Point](https://martllm.com/models/moondream/moondream3-preview-point) | other | – | $0.000952 / request |
| [Moondream 3 Preview Query](https://martllm.com/models/moondream/moondream3-preview-query) | other | – | $0.00476 / request |
| [Mureka Create Upload ID](https://martllm.com/models/mureka/mureka-create-upload-id) | other | – | $0.00952 / request |
| [Mureka Describe Song](https://martllm.com/models/mureka/mureka-describe-song) | other | $0.15 / request | $0.1428 / request |
| [Mureka Extend Lyrics](https://martllm.com/models/mureka/mureka-extend-lyrics) | other | – | $0.002856 / request |
| [Mureka Lyrics](https://martllm.com/models/mureka/mureka-lyrics) | other | – | $0.01428 / request |
| [Mureka O2 Song](https://martllm.com/models/mureka/mureka-o2-song) | music | – | $0.07 / track |
| [Mureka V7.5 Background Music](https://martllm.com/models/mureka/mureka-v7-5-bgm) | music | – | $0.045 / track |
| [Mureka V7.6 Background Music](https://martllm.com/models/mureka/mureka-v7-6-bgm) | music | – | $0.045 / track |
| [Mureka V7.6 Extend Song](https://martllm.com/models/mureka/mureka-v7-6-extend-song) | other | $0.055 / request | $0.05236 / request |
| [Mureka V7.6 Recognize Song](https://martllm.com/models/mureka/mureka-v7-6-recognize-song) | other | – | $0.01428 / request |
| [Mureka V7.6 Song](https://martllm.com/models/mureka/mureka-v7-6-song) | music | – | $0.045 / track |
| [Mureka V8 Background Music](https://martllm.com/models/mureka/mureka-v8-bgm) | music | – | $0.07 / track |
| [Mureka V8 Extend Song](https://martllm.com/models/mureka/mureka-v8-extend-song) | other | $0.15 / request | $0.1428 / request |
| [Mureka V8 Song](https://martllm.com/models/mureka/mureka-v8-song) | music | – | $0.07 / track |
| [Mureka V9.5 Background Music](https://martllm.com/models/mureka/mureka-v9-5-bgm) | music | – | $0.225 / track |
| [Mureka V9.5 Prompt to Song](https://martllm.com/models/mureka/mureka-v9-5-prompt-to-song) | music | – | $0.75 / track |
| [Mureka V9.5 Song](https://martllm.com/models/mureka/mureka-v9-5-song) | music | – | $0.225 / track |
| [Mureka V9 Background Music](https://martllm.com/models/mureka/mureka-v9-bgm) | music | – | $0.07 / track |
| [Mureka V9 Song](https://martllm.com/models/mureka/mureka-v9-song) | music | – | $0.07 / track |
| [Mureka Vocal Clone](https://martllm.com/models/mureka/mureka-vocal-clone) | other | – | $7.14 / request |
| [Cosmos Predict 2.5 (image-to-video)](https://martllm.com/models/nvidia/cosmos-predict-2-5-image-to-video) | video | $0 / sec | $0 / sec |
| [Cosmos Predict (image-to-video)](https://martllm.com/models/nvidia/cosmos-predict-image-to-video) | video | – | $0.8971 / video |
| [MiniCPM-V 4.5 Image](https://martllm.com/models/openbmb/minicpm-v-image) | other | – | $0.00476 / request |
| [MiniCPM-V 4.5 Video](https://martllm.com/models/openbmb/minicpm-v-video) | other | – | $0.01428 / request |
| [PixVerse Lipsync](https://martllm.com/models/pixverse/pixverse-lipsync) | video | – | $0.04 / sec |
| [PixVerse Mimic Motion Control](https://martllm.com/models/pixverse/pixverse-motion-control-mimic) | video | – | $0.09 / sec |
| [PixVerse Swap](https://martllm.com/models/pixverse/pixverse-swap) | video | – | $0.12 / sec |
| [PixVerse V5.5 Transition](https://martllm.com/models/pixverse/pixverse-v5-5-transition) | video | – | $0.09 / sec |
| [PixVerse V5 Effects](https://martllm.com/models/pixverse/pixverse-v5-effects) | video | – | $0.05355 / sec |
| [PixVerse V5 Transition](https://martllm.com/models/pixverse/pixverse-v5-transition) | video | – | $0.045 / sec |
| [PixVerse V6 Extend](https://martllm.com/models/pixverse/pixverse-v6-extend) | video | – | $0.045 / sec |
| [P-Image Edit LoRA Trainer](https://martllm.com/models/pruna-ai/p-image-edit-trainer) | other | $0.004 / step | $0.003808 / step |
| [P-Image LoRA Trainer](https://martllm.com/models/pruna-ai/p-image-text-to-image-trainer) | other | $0.0018 / step | $0.001714 / step |
| [P-Image Upscale](https://martllm.com/models/pruna-ai/p-image-upscale) | image | – | $0.005 / image |
| [P-Video 2 Pro Avatar](https://martllm.com/models/pruna/p-video-2-pro-avatar) | video | – | $0.02 / sec |
| [P-Video 2 Pro Replace](https://martllm.com/models/pruna/p-video-2-pro-replace) | video | – | $0.10 / sec |
| [P-Video Animate](https://martllm.com/models/pruna/p-video-animate) | video | – | $0.03 / sec |
| [P-Video Avatar](https://martllm.com/models/pruna/p-video-avatar) | video | – | $0.025 / sec |
| [P-Video Replace](https://martllm.com/models/pruna/p-video-replace) | video | – | $0.03 / sec |
| [Qwen3.5 122B A10B](https://martllm.com/models/qwen/e2ee-qwen3-5-122b-a10b) | text | – | $0.2625 / $2.10 |
| [Qwen Image Edit Multiple Angles](https://martllm.com/models/qwen/qwen-image-edit-multiple-angles) | image | – | $0.025 / image |
| [Qwen Image Translate](https://martllm.com/models/qwen/qwen-image-translate) | image | – | $0.012 / image |
| [Qwen3 TTS](https://martllm.com/models/qwen/qwen3-tts) | speech | – | $0.05 / 1K chars |
| [Qwen3 TTS Flash](https://martllm.com/models/qwen/qwen3-tts-flash) | speech | – | $0.05 / 1K chars |
| [Qwen3 TTS Voice Clone](https://martllm.com/models/qwen/qwen3-tts-voice-clone) | other | $0.05 / 1K chars | $0.0476 / 1K chars |
| [Qwen3 TTS Voice Design](https://martllm.com/models/qwen/qwen3-tts-voice-design) | other | $0.05 / 1K chars | $0.0476 / 1K chars |
| [Recraft Creative Upscale](https://martllm.com/models/recraft/recraft-creative-upscale) | image | – | $0.25 / image |
| [Recraft Crisp Upscale](https://martllm.com/models/recraft/recraft-crisp-upscale) | image | – | $0.004 / image |
| [Recraft V3](https://martllm.com/models/recraft/recraft-v3) | image | $0.03809 / image | $0.01344 / image |
| [Chatterbox Speech to Speech](https://martllm.com/models/resemble-ai/chatterbox-speech-to-speech) | music | – | $0.02 / track |
| [Chatterbox TTS](https://martllm.com/models/resemble-ai/chatterbox-tts) | speech | – | $0.03 / 1K chars |
| [Runway Gen-4 Aleph](https://martllm.com/models/runway/runway-gen4-aleph) | video | – | $0.2625 / sec |
| [FLUX.1 ControlNet Union Pro 2.0](https://martllm.com/models/shakker-labs/flux-controlnet-union-pro-2-0) | image | – | $0.03 / image |
| [SkyReels V3 Talking Avatar](https://martllm.com/models/skywork/skyreels-v3-talking-avatar) | video | – | $0.03 / sec |
| [Sonilo Text to Music](https://martllm.com/models/sonilo/sonilo-text-to-music) | music | – | $0.0025 / sec |
| [IDOL Image to 3D Splat](https://martllm.com/models/speridlabs/idol-image-to-3d) | other | $0.05 / request | $0.0476 / request |
| [3D to Video](https://martllm.com/models/studio/3d-to-video) | video | – | $0.10 / sec |
| [AI Age Filter](https://martllm.com/models/studio/ai-age-filter) | image | – | $0.05 / image |
| [AI Breast Expansion](https://martllm.com/models/studio/ai-breast-expansion) | image | – | $0.05 / image |
| [AI Celebrity Look-Alike Finder](https://martllm.com/models/studio/ai-celebrity-look-alike-finder) | other | $0.05 / request | $0.0476 / request |
| [AI Dog Selfie](https://martllm.com/models/studio/ai-dog-selfie) | image | – | $0.05 / image |
| [AI Fat Filter](https://martllm.com/models/studio/ai-fat-filter) | image | – | $0.05 / image |
| [AI Fortune Teller](https://martllm.com/models/studio/ai-fortune-teller) | other | $0.035 / request | $0.03332 / request |
| [AI Gender Swap](https://martllm.com/models/studio/ai-gender-swap) | image | – | $0.05 / image |
| [AI Girl Filter](https://martllm.com/models/studio/ai-girl-filter) | image | – | $0.05 / image |
| [AI Instagram Model](https://martllm.com/models/studio/ai-instagram-model) | image | – | $0.05 / image |
| [AI Math Solver](https://martllm.com/models/studio/ai-math-solver) | other | $0.085 / request | $0.08092 / request |
| [AI Photo Colorizer](https://martllm.com/models/studio/ai-photo-colorizer) | image | – | $0.05 / image |
| [AI Smile Filter](https://martllm.com/models/studio/ai-smile-filter) | image | – | $0.05 / image |
| [AI Story Generator](https://martllm.com/models/studio/ai-story-generator) | other | $0.035 / request | $0.03332 / request |
| [AI Travel Trends](https://martllm.com/models/studio/ai-travel-trends) | image | – | $0.05 / image |
| [AI Video Captioner](https://martllm.com/models/studio/ai-video-captioner) | other | $0.001333 / sec | $0.001269 / sec |
| [Any LLM](https://martllm.com/models/studio/any-llm) | other | – | $0.00952 / request |
| [Any LLM Vision](https://martllm.com/models/studio/any-llm-vision) | other | $0.05 / request | $0.0476 / request |
| [Audio Converter to MP3](https://martllm.com/models/studio/audio-converter-mp3) | music | – | $0.0001 / sec |
| [Cinematic Video Generator](https://martllm.com/models/studio/cinematic-video-generator) | video | – | $0.1523 / sec |
| [Content Moderator Image](https://martllm.com/models/studio/content-moderator-image) | other | – | $0.001904 / request |
| [Content Moderator Text](https://martllm.com/models/studio/content-moderator-text) | other | – | $0.000952 / request |
| [Depth Anything](https://martllm.com/models/studio/depth-anything-image) | image | – | $0.005 / image |
| [Depth Pro 2](https://martllm.com/models/studio/depth-pro-2-image) | image | – | $0.01 / image |
| [Face Enhancer](https://martllm.com/models/studio/face-enhancer-image) | image | – | $0.01 / image |
| [Face Enhancer Video](https://martllm.com/models/studio/face-enhancer-video) | video | – | $0.01 / sec |
| [Female Human Portrait](https://martllm.com/models/studio/female-human) | image | $0.015 / image | $0.01428 / image |
| [FeyNoBg Background Remover](https://martllm.com/models/studio/feynobg) | image | – | $0.001 / image |
| [FLUX Dev LoRA Trainer](https://martllm.com/models/studio/flux-dev-lora-trainer) | other | $0.001 / step | $0.000952 / step |
| [FLUX Dev LoRA Trainer Turbo](https://martllm.com/models/studio/flux-dev-lora-trainer-turbo) | other | $0.00125 / step | $0.00119 / step |
| [FLUX PuLID](https://martllm.com/models/studio/flux-pulid) | image | – | $0.02 / image |
| [Ghibli Style](https://martllm.com/models/studio/ghibli) | image | – | $0.005 / image |
| [AI Ghibli Filter](https://martllm.com/models/studio/ghibli-filter-image) | image | – | $0.05 / image |
| [Ghibli Filter Video](https://martllm.com/models/studio/ghibli-filter-video) | video | $0.06 / sec | $0.05712 / sec |
| [Image Background Remover](https://martllm.com/models/studio/image-background-remover) | image | – | $0.004 / image |
| [Image Body Swap](https://martllm.com/models/studio/image-body-swap) | image | – | $0.05 / image |
| [Image Captioner](https://martllm.com/models/studio/image-captioner) | other | – | $0.000952 / request |
| [Image Converter](https://martllm.com/models/studio/image-converter) | image | – | $0.0005 / image |
| [Image Eraser](https://martllm.com/models/studio/image-eraser) | image | – | $0.025 / image |
| [Image Face Blur](https://martllm.com/models/studio/image-face-blur) | image | – | $0.001 / image |
| [Image Face Swap](https://martllm.com/models/studio/image-face-swap) | image | – | $0.01 / image |
| [Image Face Swap Pro](https://martllm.com/models/studio/image-face-swap-pro) | image | – | $0.025 / image |
| [Image Head Swap](https://martllm.com/models/studio/image-head-swap) | image | – | $0.025 / image |
| [Image Text Remover](https://martllm.com/models/studio/image-text-remover) | image | – | $0.15 / image |
| [Image Translator](https://martllm.com/models/studio/image-translator) | image | – | $0.15 / image |
| [Image Upscaler](https://martllm.com/models/studio/image-upscaler) | image | – | $0.01 / image |
| [Image Watermark Remover](https://martllm.com/models/studio/image-watermark-remover) | image | – | $0.015 / image |
| [Image Zoom Out](https://martllm.com/models/studio/image-zoom-out) | image | – | $0.02 / image |
| [LTX-2 19B IC-LoRA Trainer](https://martllm.com/models/studio/ltx-2-19b-ic-lora-trainer) | other | $0.0075 / step | $0.00714 / step |
| [LTX-2 19B Video LoRA Trainer](https://martllm.com/models/studio/ltx-2-19b-video-lora-trainer) | other | $0.0035 / step | $0.003332 / step |
| [OmniVoice Voice Clone](https://martllm.com/models/studio/omnivoice-voice-clone) | other | $0.05 / 1K chars | $0.0476 / 1K chars |
| [OpenVideo (image-to-video)](https://martllm.com/models/studio/open-video-image-to-video) | video | – | $0.02 / sec |
| [Prompt Optimizer](https://martllm.com/models/studio/prompt-optimizer) | other | – | $0.000952 / request |
| [Qwen Image 2512 LoRA Trainer](https://martllm.com/models/studio/qwen-image-2512-lora-trainer) | other | $0.001 / step | $0.000952 / step |
| [Qwen Image LoRA Trainer](https://martllm.com/models/studio/qwen-image-lora-trainer) | other | $0.001 / step | $0.000952 / step |
| [Short Video Generator](https://martllm.com/models/studio/short-video-generator) | video | – | $0.1523 / sec |
| [Sketch to Video](https://martllm.com/models/studio/sketch-to-video) | video | $0 / sec | $0 / sec |
| [Social Video Generator](https://martllm.com/models/studio/social-video-generator) | video | – | $0.1523 / sec |
| [Subtitle OCR](https://martllm.com/models/studio/subtitle-ocr) | other | $0.002667 / sec | $0.002539 / sec |
| [Talking Photo](https://martllm.com/models/studio/talking-photo) | video | $0 / sec | $0 / sec |
| [UGC Street Interview](https://martllm.com/models/studio/ugc-interview) | video | $0.1375 / sec | $0.1309 / sec |
| [UGC Podcast](https://martllm.com/models/studio/ugc-podcast) | video | $0.1375 / sec | $0.1309 / sec |
| [UGC Ranking Video](https://martllm.com/models/studio/ugc-ranking) | video | $0.1375 / sec | $0.1309 / sec |
| [UGC Talking Video](https://martllm.com/models/studio/ugc-talking) | video | $0.1375 / sec | $0.1309 / sec |
| [UGC Video Generator](https://martllm.com/models/studio/ugc-video-generator) | video | – | $0.1523 / sec |
| [Ultimate Image Upscaler](https://martllm.com/models/studio/ultimate-image-upscaler) | image | – | $0.06 / image |
| [Ultimate Video Upscaler](https://martllm.com/models/studio/ultimate-video-upscaler) | video | – | $0.02 / sec |
| [Video Background Remover](https://martllm.com/models/studio/video-background-remover) | video | – | $0.01 / sec |
| [Video Background Remover Pro](https://martllm.com/models/studio/video-background-remover-pro) | video | – | $0.04 / sec |
| [Video Body Swap](https://martllm.com/models/studio/video-body-swap) | video | – | $0.08 / sec |
| [Video Cleaner](https://martllm.com/models/studio/video-cleaner) | video | – | $0.04 / sec |
| [Video Colorizer](https://martllm.com/models/studio/video-colorizer) | video | – | $0.04 / sec |
| [Video Converter](https://martllm.com/models/studio/video-converter) | video | – | $0.0002 / sec |
| [Video Eraser](https://martllm.com/models/studio/video-eraser) | video | – | $0.02 / sec |
| [Video Face Swap](https://martllm.com/models/studio/video-face-swap) | video | – | $0.01 / sec |
| [Video FPS Increaser](https://martllm.com/models/studio/video-fps-increaser) | video | – | $0.008 / sec |
| [Video Head Swap](https://martllm.com/models/studio/video-head-swap) | video | – | $0.04 / sec |
| [Video Music Remover](https://martllm.com/models/studio/video-music-remover) | video | – | $0.002 / sec |
| [Video Outpainter](https://martllm.com/models/studio/video-outpainter) | video | – | $0.04 / sec |
| [Video Relighter](https://martllm.com/models/studio/video-relighter) | video | – | $0.04 / sec |
| [Video Restorer](https://martllm.com/models/studio/video-restorer) | video | – | $0.04 / sec |
| [Video Upscaler](https://martllm.com/models/studio/video-upscaler) | video | – | $0.005 / sec |
| [Video Upscaler Pro](https://martllm.com/models/studio/video-upscaler-pro) | video | – | $0.02 / sec |
| [Video Watermark Remover](https://martllm.com/models/studio/video-watermark-remover) | video | – | $0.01 / sec |
| [Vocal Isolator](https://martllm.com/models/studio/vocal-isolator) | music | – | $0.001 / sec |
| [VOSR2 Image Upscaler](https://martllm.com/models/studio/vosr2-image) | image | – | $0.01 / image |
| [Wan 2.1 14B LoRA Trainer](https://martllm.com/models/studio/wan-2-1-14b-lora-trainer) | other | $0.00075 / step | $0.000714 / step |
| [Wan 2.2 Image-to-Video LoRA Trainer](https://martllm.com/models/studio/wan-2-2-i2v-lora-trainer) | other | – | $0.0476 / step |
| [Wan 2.2 Image LoRA Trainer](https://martllm.com/models/studio/wan-2-2-image-lora-trainer) | other | $0.0015 / step | $0.001428 / step |
| [Whisper Large v3 Turbo](https://martllm.com/models/studio/whisper-large-v3-turbo) | transcription | – | $0.042 / minute |
| [Whisper Large v3 (from video)](https://martllm.com/models/studio/whisper-large-v3-video) | other | $0.001 / sec | $0.000952 / sec |
| [Z-Image Base LoRA Trainer](https://martllm.com/models/studio/z-image-base-lora-trainer) | other | $0.00125 / step | $0.00119 / step |
| [Z-Image Turbo LoRA Trainer](https://martllm.com/models/studio/z-image-lora-trainer) | other | $0.00125 / step | $0.00119 / step |
| [Lipsync 2](https://martllm.com/models/sync/lipsync-2) | video | – | $0.05 / sec |
| [Lipsync 2 Pro](https://martllm.com/models/sync/lipsync-2-pro) | video | – | $0.084 / sec |
| [Lipsync 3 Avatar](https://martllm.com/models/sync/lipsync-3-avatar) | video | – | $0.135 / sec |
| [React-1](https://martllm.com/models/sync/react-1) | video | – | $0.167 / sec |
| [Hunyuan Avatar](https://martllm.com/models/tencent/hunyuan-avatar) | video | – | $0.03 / sec |
| [Hunyuan Video (text-to-video)](https://martllm.com/models/tencent/hunyuan-video-text-to-video) | video | $0.08 / sec | $0.07616 / sec |
| [Hunyuan3D 3.1 Rapid Image to 3D](https://martllm.com/models/tencent/hunyuan3d-3-1-image-to-3d-rapid) | other | $0.27 / request | $0.257 / request |
| [Hunyuan3D 3.1 Rapid Text to 3D](https://martllm.com/models/tencent/hunyuan3d-3-1-text-to-3d-rapid) | other | $0.27 / request | $0.257 / request |
| [Hunyuan3D 3 Image to 3D](https://martllm.com/models/tencent/hunyuan3d-3-image-to-3d) | other | $0.63 / request | $0.5998 / request |
| [Hunyuan3D 3 Text to 3D](https://martllm.com/models/tencent/hunyuan3d-3-text-to-3d) | other | $0.63 / request | $0.5998 / request |
| [SongGeneration (LeVo)](https://martllm.com/models/tencent/songgeneration-levo) | music | – | $0.05 / track |
| [Z-Image Turbo ControlNet](https://martllm.com/models/tongyi-mai/z-image-turbo-controlnet) | image | – | $0.012 / image |
| [Topaz Image Denoise Max](https://martllm.com/models/topaz-labs/topaz-image-denoise-generative) | image | – | $0.10 / image |
| [Topaz Image Lighting](https://martllm.com/models/topaz-labs/topaz-image-lighting) | image | – | $0.10 / image |
| [Topaz Image Restore](https://martllm.com/models/topaz-labs/topaz-image-restore) | image | – | $0.10 / image |
| [Topaz Image Sharpen](https://martllm.com/models/topaz-labs/topaz-image-sharpen) | image | – | $0.10 / image |
| [Topaz Image Sharpen Generative](https://martllm.com/models/topaz-labs/topaz-image-sharpen-generative) | image | – | $0.10 / image |
| [Topaz Transparent Image Upscale](https://martllm.com/models/topaz-labs/topaz-image-transparent-upscale) | image | – | $0.10 / image |
| [Topaz Image Upscale](https://martllm.com/models/topaz-labs/topaz-image-upscale) | image | – | $0.10 / image |
| [Topaz Image Upscale Creative](https://martllm.com/models/topaz-labs/topaz-image-upscale-creative) | image | – | $0.90 / image |
| [Topaz Image Upscale Generative](https://martllm.com/models/topaz-labs/topaz-image-upscale-generative) | image | – | $0.30 / image |
| [Tripo Animate](https://martllm.com/models/tripo/tripo-animate) | other | $0.42 / request | $0.3998 / request |
| [Tripo Convert](https://martllm.com/models/tripo/tripo-convert) | other | $0.06 / request | $0.05712 / request |
| [Tripo H3.0 Image to 3D](https://martllm.com/models/tripo/tripo-h3-0-image-to-3d) | other | $0.36 / request | $0.3427 / request |
| [Tripo H3.0 Multiview to 3D](https://martllm.com/models/tripo/tripo-h3-0-multiview-to-3d) | other | $0.36 / request | $0.3427 / request |
| [Tripo H3.0 Text to 3D](https://martllm.com/models/tripo/tripo-h3-0-text-to-3d) | other | $0.24 / request | $0.2285 / request |
| [Tripo H3.1 Image to 3D](https://martllm.com/models/tripo/tripo-h3-1-image-to-3d) | other | $0.36 / request | $0.3427 / request |
| [Tripo H3.1 Multiview to 3D](https://martllm.com/models/tripo/tripo-h3-1-multiview-to-3d) | other | $0.36 / request | $0.3427 / request |
| [Tripo H3.1 Text to 3D](https://martllm.com/models/tripo/tripo-h3-1-text-to-3d) | other | $0.24 / request | $0.2285 / request |
| [Tripo Image to 3D Splat](https://martllm.com/models/tripo/tripo-image-to-splat) | other | $0.36 / request | $0.3427 / request |
| [Tripo Mesh Complete](https://martllm.com/models/tripo/tripo-mesh-complete) | other | $1.08 / request | $1.03 / request |
| [Tripo P1 Image to 3D](https://martllm.com/models/tripo/tripo-p1-image-to-3d) | other | $0.60 / request | $0.5712 / request |
| [Tripo P1 Multiview to 3D](https://martllm.com/models/tripo/tripo-p1-multiview-to-3d) | other | $0.60 / request | $0.5712 / request |
| [Tripo P1 Text to 3D](https://martllm.com/models/tripo/tripo-p1-text-to-3d) | other | $0.48 / request | $0.457 / request |
| [Tripo P2 Image to 3D](https://martllm.com/models/tripo/tripo-p2-image-to-3d) | other | $1.32 / request | $1.26 / request |
| [Tripo P2 Multiview to 3D](https://martllm.com/models/tripo/tripo-p2-multiview-to-3d) | other | $1.32 / request | $1.26 / request |
| [Tripo P2 Text to 3D](https://martllm.com/models/tripo/tripo-p2-text-to-3d) | other | $1.32 / request | $1.26 / request |
| [Tripo Retopology](https://martllm.com/models/tripo/tripo-retopology) | other | $0.42 / request | $0.3998 / request |
| [Tripo Rig](https://martllm.com/models/tripo/tripo-rig) | other | $0.30 / request | $0.2856 / request |
| [Tripo Segment](https://martllm.com/models/tripo/tripo-segment) | other | $0.48 / request | $0.457 / request |
| [Tripo Smart Segment from Image](https://martllm.com/models/tripo/tripo-smart-segment-image) | other | $1.02 / request | $0.971 / request |
| [Tripo Smart Segment](https://martllm.com/models/tripo/tripo-smart-segment-model) | other | $0.66 / request | $0.6283 / request |
| [Tripo Smart UV](https://martllm.com/models/tripo/tripo-smart-uv) | other | $0.24 / request | $0.2285 / request |
| [Tripo Texture](https://martllm.com/models/tripo/tripo-texture) | other | $0.12 / request | $0.1142 / request |
| [Tripo v2.5 Image to 3D](https://martllm.com/models/tripo/tripo-v2-5-image-to-3d) | other | $0.324 / request | $0.3084 / request |
| [Tripo v2.5 Multiview to 3D](https://martllm.com/models/tripo/tripo-v2-5-multiview-to-3d) | other | $0.324 / request | $0.3084 / request |
| [VEED Lipsync](https://martllm.com/models/veed/lipsync) | video | – | $0.03 / sec |
| [VEED Lipsync V2](https://martllm.com/models/veed/lipsync-v2) | video | – | $0.075 / sec |
| [VEED Subtitles](https://martllm.com/models/veed/subtitles) | video | – | $0.001833 / sec |
| [Flux 3 (Venice)](https://martllm.com/models/venice/flux-3-image) | image | $0.12 / image | $0.03882 / image |
| [Gemini Omni Flash 1.1 Reference-to-Video](https://martllm.com/models/venice/gemini-omni-flash-1-1-reference-to-video) | video | $0.1167 / sec | $0.02992 / sec |
| [GPT Image 2.5 Flare (Venice)](https://martllm.com/models/venice/gpt-image-2-5-flare) | image | $0.07 / image | $0.0056 / image |
| [GPT Image 2.5 Sunburst (Venice)](https://martllm.com/models/venice/gpt-image-2-5-sunburst) | image | $0.07 / image | $0.0056 / image |
| [GPT Image 2.6 Flare (Venice)](https://martllm.com/models/venice/gpt-image-2-6-flare) | image | $0.09 / image | $0.008592 / image |
| [GPT Image 2.6 Flare (image-to-image)](https://martllm.com/models/venice/gpt-image-2-6-flare-edit) | image | $0.10 / image | $0.008592 / image |
| [GPT Image 2.6 Sunburst (Venice)](https://martllm.com/models/venice/gpt-image-2-6-sunburst) | image | $0.09 / image | $0.0168 / image |
| [GPT Image 2.6 Sunburst (image-to-image)](https://martllm.com/models/venice/gpt-image-2-6-sunburst-edit) | image | $0.10 / image | $0.0168 / image |
| [Grok Imagine 1.5 Lite Text-to-Video](https://martllm.com/models/venice/grok-imagine-1-5-lite-text-to-video) | video | $0.036 / sec | $0.02495 / sec |
| [Ideogram V4 (Venice)](https://martllm.com/models/venice/ideogram-v4) | image | $0.06 / image | $0.04704 / image |
| [Ideogram V4.5 (Venice)](https://martllm.com/models/venice/ideogram-v4-5) | image | $0.26 / image | $0.05712 / image |
| [Kling 4.0 Flash Image-to-Video](https://martllm.com/models/venice/kling-v4-flash-image-to-video) | video | $0.1175 / sec | $0.08949 / sec |
| [Kling 4.0 Flash Reference-to-Video](https://martllm.com/models/venice/kling-v4-flash-reference-to-video) | video | $0.1175 / sec | $0.09212 / sec |
| [Kling 4.0 Flash Text-to-Video](https://martllm.com/models/venice/kling-v4-flash-text-to-video) | video | $0.1175 / sec | $0.0952 / sec |
| [Kling Image 4.0 (image-to-image)](https://martllm.com/models/venice/kling-v4-image-edit) | image | $0.08 / image | $0.05998 / image |
| [Kling Image 4.0](https://martllm.com/models/venice/kling-v4-text-to-image) | image | $0.08 / image | $0.06328 / image |
| [Krea 2 Turbo (Venice)](https://martllm.com/models/venice/krea-2-turbo) | image | $0.04 / image | $0.00924 / image |
| [Krea v2 Large (Venice)](https://martllm.com/models/venice/krea-v2-large) | image | $0.07 / image | $0.03696 / image |
| [Krea v2 Medium (Venice)](https://martllm.com/models/venice/krea-v2-medium) | image | $0.04 / image | $0.03136 / image |
| [Luma Uni-1 (Venice)](https://martllm.com/models/venice/luma-uni-1) | image | $0.05 / image | $0.0392 / image |
| [Luma Uni-1 Max (Venice)](https://martllm.com/models/venice/luma-uni-1-max) | image | $0.12 / image | $0.09408 / image |
| [MiniMax H3 Chili Image-to-Video](https://martllm.com/models/venice/minimax-h3-chili-image-to-video) | video | – | $0.03413 / sec |
| [MiniMax H3 Chili R2V](https://martllm.com/models/venice/minimax-h3-chili-reference-to-video) | video | – | $0.01725 / sec |
| [MiniMax H3 Chili Text-to-Video](https://martllm.com/models/venice/minimax-h3-chili-text-to-video) | video | – | $0.03136 / sec |
| [MiniMax H3 R2V Enhanced](https://martllm.com/models/venice/minimax-h3-enhanced-reference-to-video) | video | – | $0.0784 / sec |
| [MiniMax H3 Enhanced Text-to-Video](https://martllm.com/models/venice/minimax-h3-enhanced-text-to-video) | video | $0.1626 / sec | $0.105 / sec |
| [MiniMax H3 Hyper Image-to-Video](https://martllm.com/models/venice/minimax-h3-hyper-image-to-video) | video | $0.03625 / sec | $0.03241 / sec |
| [MiniMax H3 Hyper R2V](https://martllm.com/models/venice/minimax-h3-hyper-reference-to-video) | video | – | $0.01725 / sec |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/venice/minimax-h3-hyper-text-to-video) | video | – | $0.02772 / sec |
| [MiniMax H3 Image](https://martllm.com/models/venice/minimax-h3-image) | image | $0.04 / image | $0.01008 / image |
| [MiniMax H3 Image (image-to-image)](https://martllm.com/models/venice/minimax-h3-image-edit) | image | $0.06 / image | $0.01008 / image |
| [MiniMax H3 Max Image-to-Video](https://martllm.com/models/venice/minimax-h3-max-image-to-video) | video | $0.072 / sec | $0.03809 / sec |
| [MiniMax H3 Max R2V](https://martllm.com/models/venice/minimax-h3-max-reference-to-video) | video | – | $0.04704 / sec |
| [MiniMax H3 Max Text-to-Video](https://martllm.com/models/venice/minimax-h3-max-text-to-video) | video | $0.072 / sec | $0.03809 / sec |
| [Muse Image](https://martllm.com/models/venice/muse-image) | image | $0.02 / image | $0.004852 / image |
| [Nano Banana 2.1 (Venice)](https://martllm.com/models/venice/nano-banana-2-1) | image | $0.10 / image | $0.01213 / image |
| [Nano Banana 2 Lite (Venice)](https://martllm.com/models/venice/nano-banana-2-lite) | image | $0.06 / image | $0.0112 / image |
| [Qwen Image 2.1 Pro (Venice)](https://martllm.com/models/venice/qwen-image-2-1-pro) | image | $0.05 / image | $0.02834 / image |
| [Qwen Image 2.1 Turbo (Venice)](https://martllm.com/models/venice/qwen-image-2-1-turbo) | image | $0.02 / image | $0.01133 / image |
| [Seedance 2.5 Flash Image-to-Video](https://martllm.com/models/venice/seedance-2-5-flash-image-to-video-basic) | video | $0.189 / sec | $0.08828 / sec |
| [Seedance 2.5 Flash Reference-to-Video](https://martllm.com/models/venice/seedance-2-5-flash-reference-to-video-basic) | video | $0.189 / sec | $0.08828 / sec |
| [Seedance 2.5 Flash Text-to-Video](https://martllm.com/models/venice/seedance-2-5-flash-text-to-video-basic) | video | $0.189 / sec | $0.08828 / sec |
| [Seedance 2.5 Image-to-Video](https://martllm.com/models/venice/seedance-2-5-image-to-video-basic) | video | $0.1287 / sec | $0.08388 / sec |
| [Seedance 2.5 Reference-to-Video](https://martllm.com/models/venice/seedance-2-5-reference-to-video-basic) | video | $0.1287 / sec | $0.08388 / sec |
| [Seedance 2.5 Text-to-Video](https://martllm.com/models/venice/seedance-2-5-text-to-video-basic) | video | $0.1287 / sec | $0.08388 / sec |
| [Seedream V5.5 (Venice)](https://martllm.com/models/venice/seedream-v5-5) | image | $0.0255 / image | $0.02016 / image |
| [Seedream V5.5 (image-to-image)](https://martllm.com/models/venice/seedream-v5-5-edit) | image | $0.0255 / image | $0.02016 / image |
| [Seedream V5 Pro (Venice)](https://martllm.com/models/venice/seedream-v5-pro) | image | $0.06 / image | $0.01512 / image |
| [Venice Video Gen (legacy alias)](https://martllm.com/models/venice/video-gen) | video | – | $0.168 / sec |
| [Wan 3.0 Prime Pro Image-to-Video](https://martllm.com/models/venice/wan-3-0-prime-pro-image-to-video) | video | – | $0.3478 / sec |
| [Wan 3.0 Prime Pro Reference-to-Video](https://martllm.com/models/venice/wan-3-0-prime-pro-reference-to-video) | video | – | $0.3478 / sec |
| [Wan 3.0 Prime Pro Text-to-Video](https://martllm.com/models/venice/wan-3-0-prime-pro-text-to-video) | video | – | $0.3478 / sec |
| [Wan 3.0 Prime Reference-to-Video](https://martllm.com/models/venice/wan-3-0-prime-reference-to-video) | video | $0.364 / sec | $0.05199 / sec |
| [Wan 3.0 Pro Image-to-Video](https://martllm.com/models/venice/wan-3-0-pro-image-to-video) | video | $0.2366 / sec | $0.2236 / sec |
| [Wan 3.0 Pro Reference-to-Video](https://martllm.com/models/venice/wan-3-0-pro-reference-to-video) | video | – | $0.2484 / sec |
| [Wan 3.0 Pro Text-to-Video](https://martllm.com/models/venice/wan-3-0-pro-text-to-video) | video | – | $0.2484 / sec |
| [Wan 3.0 Reference-to-Video](https://martllm.com/models/venice/wan-3-0-reference-to-video) | video | $0.26 / sec | $0.03324 / sec |
| [Vidu 2.0 (image-to-video)](https://martllm.com/models/vidu/vidu-2-0-image-to-video) | video | $0.06 / sec | $0.05712 / sec |
| [Vidu (image-to-video)](https://martllm.com/models/vidu/vidu-image-to-video) | video | $0.04 / sec | $0.03808 / sec |
| [Vidu Q2 Pro Video Extend](https://martllm.com/models/vidu/vidu-q2-pro-video-extend) | video | – | $0.07 / sec |
| [Vidu Q2 Turbo Video Extend](https://martllm.com/models/vidu/vidu-q2-turbo-video-extend) | video | – | $0.035 / sec |
| [Vidu Q3 Turbo Image to Video](https://martllm.com/models/vidu/viduq3-turbo-image-to-video) | video | $0.03333 / sec | $0.03173 / sec |
| [Vidu Q3 Turbo Text to Video](https://martllm.com/models/vidu/viduq3-turbo-text-to-video) | video | $0.03333 / sec | $0.03173 / sec |
| [Wan 2.1 Ditto](https://martllm.com/models/wan/wan-2-1-ditto) | video | – | $0.04 / sec |
| [Wan 2.1 First-Last Frame (image-to-video)](https://martllm.com/models/wan/wan-2-1-first-last-frame-to-video) | video | – | $0.06 / sec |
| [Wan 2.1 MoCha](https://martllm.com/models/wan/wan-2-1-mocha) | video | – | $0.04 / sec |
| [Wan 2.1 Pro Image-to-Video](https://martllm.com/models/wan/wan-2-1-pro-image-to-video) | video | – | $0.154 / sec |
| [Wan 2.2 5B (image-to-video)](https://martllm.com/models/wan/wan-2-2-5b-image-to-video) | video | – | $0.01 / sec |
| [Wan 2.2 5B (text-to-video)](https://martllm.com/models/wan/wan-2-2-5b-text-to-video) | video | – | $0.00952 / sec |
| [Wan 2.2 Animate](https://martllm.com/models/wan/wan-2-2-animate) | video | – | $0.04 / sec |
| [Wan 2.2 Animate 2](https://martllm.com/models/wan/wan-2-2-animate-2) | video | – | $0.04 / sec |
| [Wan 2.2 Fun Control](https://martllm.com/models/wan/wan-2-2-fun-control) | video | – | $0.04 / sec |
| [Wan 2.2 Speech to Video](https://martllm.com/models/wan/wan-2-2-speech-to-video) | video | – | $0.03 / sec |
| [Wan 2.2 (text-to-image)](https://martllm.com/models/wan/wan-2-2-text-to-image) | image | $0.025 / image | $0.0238 / image |
| [Wan 2.2 Spicy Video Extend](https://martllm.com/models/wan/wan-2-2-video-extend-spicy) | video | – | $0.03 / sec |
| [Wan 2.5 Fast Video Extend](https://martllm.com/models/wan/wan-2-5-fast-video-extend) | video | – | $0.068 / sec |
| [Wan 2.5 Video Extend](https://martllm.com/models/wan/wan-2-5-video-extend) | video | – | $0.10 / sec |
| [Wan 2.6 Ultra (image-to-video)](https://martllm.com/models/wan/wan-2-6-ultra-image-to-video) | video | – | $0.315 / sec |
| [Wan 2.6 Video Extend](https://martllm.com/models/wan/wan-2-6-video-extend) | video | – | $0.10 / sec |
| [Wan 3.0 Prime Video Extend](https://martllm.com/models/wan/wan-3-0-prime-video-extend) | video | – | $0.15 / sec |
| [Wan 3.0 Video Extend](https://martllm.com/models/wan/wan-3-0-video-extend) | video | – | $0.10 / sec |
| [Grok Imagine Video Extend](https://martllm.com/models/x-ai/grok-imagine-video-extend) | video | – | $0.07 / sec |
| [Real-ESRGAN](https://martllm.com/models/xinntao/real-esrgan) | image | – | $0.0024 / image |
| [SCAIL](https://martllm.com/models/z-ai/scail) | video | – | $0.04 / sec |
| [SCAIL 2](https://martllm.com/models/z-ai/scail-2) | video | – | $0.04 / sec |
| [Zonos 2 Voice Clone](https://martllm.com/models/zyphra/zonos-2) | other | – | $0.00952 / request |

**No longer listed (181)**: `aion-labs/aion-rp-llama-3.1-8b`, `amazon/nova-2-lite`, `amazon/nova-2-lite-v1`, `amazon/nova-lite-v1`, `amazon/nova-micro-v1`, `amazon/nova-premier-v1`, `amazon/nova-pro-v1`, `anthracite-org/magnum-v4-72b`, `anthropic/claude-opus-4.1`, `baidu/ernie-light-dt-1.0-intl`, `black-forest-labs/venice-flux-3-image`, `bytedance-seed/seed-2.0-lite`, `bytedance-seed/seed-2.0-mini`, `bytedance/ui-tars-1.5-7b`, `bytedance/venice-seedance-2-5-flash-image-to-video-basic`, `bytedance/venice-seedance-2-5-flash-reference-to-video-basic`, `bytedance/venice-seedance-2-5-flash-text-to-video-basic`, `bytedance/venice-seedance-2-5-image-to-video-basic`, `bytedance/venice-seedance-2-5-reference-to-video-basic`, `bytedance/venice-seedance-2-5-text-to-video-basic`, `bytedance/venice-seedream-v5-5`, `bytedance/venice-seedream-v5-5-edit`, `bytedance/venice-seedream-v5-pro`, `bytedance/seed-audio-1-0`, `cohere/command-r-08-2024`, `cohere/command-r-plus-08-2024`, `cohere/command-r7b-12-2024`, `deepseek/deepseek-chat`, `deepseek/deepseek-chat-v3-0324`, `deepseek/deepseek-chat-v3.1`, `deepseek/deepseek-v3.1-terminus`, `deepseek/deepseek-v3.2-exp`, `venice/whisper-large-v3`, `black-forest-labs/flux-schnell`, `lightricks/ltx-2-3-text-to-video`, `minimax/hailuo-02-standard-image-to-video`, `minimax/hailuo-02-standard-text-to-video`, `recraft/recraft-v3`, `google/veo-3.1-lite`, `vidu/viduq3-turbo-image-to-video`, `vidu/viduq3-turbo-text-to-video`, `google/gemini-2.5-pro-preview`, `google/gemini-3-pro-image`, `google/gemini-3-pro-image-preview`, `google/gemini-3.1-flash-image`, `google/gemini-3.1-flash-image-preview`, `google/gemini-3.1-flash-lite-image`, `google/gemini-3.1-pro-preview-customtools`, `google/gemini-nano-banana-2.1`, `google/gemini-omni-1.1-flash`, `google/gemma-2-27b-it`, `google/venice-gemini-omni-flash-1-1-reference-to-video`, `google/venice-nano-banana-2-1`, `google/venice-nano-banana-2-lite`, `gryphe/mythomax-l2-13b`, `ibm-granite/granite-4.2-8b`, `ideogram/venice-ideogram-v4`, `ideogram/venice-ideogram-v4-5`, `inclusionai/ling-3.0-tiny`, `inclusionai/lingsante-3.1-air-vl`, `kling/venice-kling-v4-flash-image-to-video`, `kling/venice-kling-v4-flash-reference-to-video`, `kling/venice-kling-v4-flash-text-to-video`, `kling/venice-kling-v4-image-edit`, `kling/venice-kling-v4-text-to-image`, `krea/venice-krea-2-turbo`, `krea/venice-krea-v2-large`, `krea/venice-krea-v2-medium`, `kt/midm-k-3.0-pro`, `liquid/lfm-3-1.7b`, `luma/venice-luma-uni-1`, `luma/venice-luma-uni-1-max`, `mancer/weaver`, `meta-llama/llama-3.1-70b-instruct`, `meta-llama/llama-3.1-8b-instruct`, `meta-llama/llama-4-scout`, `meta-llama/llama-guard-4-12b`, `meta-llama/venice-muse-image`, `microsoft/phi-4`, `minimax/venice-minimax-h3-chili-image-to-video`, `minimax/venice-minimax-h3-chili-reference-to-video`, `minimax/venice-minimax-h3-chili-text-to-video`, `minimax/venice-minimax-h3-enhanced-reference-to-video`, `minimax/venice-minimax-h3-enhanced-text-to-video`, `minimax/venice-minimax-h3-hyper-image-to-video`, `minimax/venice-minimax-h3-hyper-reference-to-video`, `minimax/venice-minimax-h3-hyper-text-to-video`, `minimax/venice-minimax-h3-image`, `minimax/venice-minimax-h3-image-edit`, `minimax/venice-minimax-h3-max-image-to-video`, `minimax/venice-minimax-h3-max-reference-to-video`, `minimax/venice-minimax-h3-max-text-to-video`, `mistralai/codestral-2508`, `mistralai/devstral-2512`, `mistralai/ministral-14b-2512`, `mistralai/ministral-3b-2512`, `mistralai/ministral-8b-2512`, `mistralai/mistral-large-2407`, `mistralai/mistral-large-2512`, `mistralai/mistral-saba`, `mistralai/mistral-small-24b-instruct-2501`, `mistralai/mistral-small-2603`, `mistralai/mistral-small-3.1-24b-instruct`, `mistralai/mixtral-8x22b-instruct`, `moonshotai/kimi-k2-0905`, `motif-technologies/motif-3`, `nex-agi/nex-n2.5-mini`, `nex-agi/nex-n2.5-pro`, `nex-agi/nex-n2.6`, `nousresearch/hermes-4-405b`, `nvidia/nemotron-3.5-content-safety`, `nvidia/nemotron-3.5-lightning`, `openai/gpt-3.5-turbo-0613`, `openai/gpt-3.5-turbo-16k`, `openai/gpt-4`, `openai/gpt-4o-2024-05-13`, `openai/gpt-6.1-terra-pro:batch`, `openai/gpt-6.1-terra:batch`, `openai/gpt-chat-latest`, `openai/venice-gpt-image-2-5-flare`, `openai/venice-gpt-image-2-5-sunburst`, `openai/venice-gpt-image-2-6-flare`, `openai/venice-gpt-image-2-6-flare-edit`, `openai/venice-gpt-image-2-6-sunburst`, `openai/venice-gpt-image-2-6-sunburst-edit`, `perceptron/perceptron-mk1`, `perceptron/perceptron-mk1.5`, `perplexity/sonar-deep-research`, `perplexity/sonar-pro`, `perplexity/sonar-pro-search`, `perplexity/sonar-reasoning-pro`, `prism-ml/ternary-bonsai-2-27b`, `prism-ml/ternary-bonsai-2-9b`, `qwen/qwen-2.5-coder-32b-instruct`, `qwen/qwen-plus`, `qwen/qwen2.5-72b-instruct`, `qwen/qwen2.5-vl-72b-instruct`, `qwen/qwen3-30b-a3b-instruct-2507`, `qwen/qwen3-coder-flash`, `qwen/qwen3-vl-30b-a3b-instruct`, `qwen/qwen3-vl-8b-instruct`, `qwen/qwen3.5-122b-a10b`, `qwen/qwen3.5-27b`, `qwen/qwen3.5-flash-02-23`, `qwen/qwen3.5-plus-02-15`, `qwen/qwen3.5-plus-20260420`, `qwen/venice-qwen-image-2-1-pro`, `qwen/venice-qwen-image-2-1-turbo`, `qwen/venice-wan-3-0-prime-pro-image-to-video`, `qwen/venice-wan-3-0-prime-pro-reference-to-video`, `qwen/venice-wan-3-0-prime-pro-text-to-video`, `qwen/venice-wan-3-0-prime-reference-to-video`, `qwen/venice-wan-3-0-pro-image-to-video`, `qwen/venice-wan-3-0-pro-reference-to-video`, `qwen/venice-wan-3-0-pro-text-to-video`, `qwen/venice-wan-3-0-reference-to-video`, `radixark/daisyrose-27b`, `rekaai/reka-edge`, `rekaai/reka-flash-3`, `relace/relace-apply-3`, `relace/relace-search`, `ricursiveai/ripple-65b-preview`, `sao10k/l3-lunaris-8b`, `sao10k/l3.1-euryale-70b`, `tencent/hy-mt2-1.8b`, `tencent/hy-mt2-30b-a3b`, `tencent/hy-mt2-7b`, `thedrummer/cydonia-24b-v4.1`, `thedrummer/skyfall-36b-v2`, `thedrummer/unslopnemo-12b`, `thinking-machines/inkling-small`, `tngtech/deepseek-r1t2-chimera`, `undi95/remm-slerp-l2-13b`, `upstage/solar-mini-4-5`, `upstage/solar-mini4`, `upstage/solar-pro-4-contributor`, `upstage/solar-pro4`, `writer/palmyra-x5`, `x-ai/grok-build-0.1`, `x-ai/venice-grok-imagine-1-5-lite-text-to-video`, `z-ai/glm-4.6v`

<details><summary>MartLLM price moves of 10% or more (247)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | text | $0.005985 / $0.02993 | $0.000315 / $0.001575 | −95% |
| [FLUX Dev](https://martllm.com/models/black-forest-labs/flux-dev) | image | $0.0896 / image | $0.01142 / image | −87% |
| [Kling V3 Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-standard-image-to-video) | video | $0.4332 / sec | $0.07317 / sec | −83% |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | $0.4332 / sec | $0.07317 / sec | −83% |
| [Black Forest Labs/FLUX 2 DEV](https://martllm.com/models/black-forest-labs/flux-2-dev) | image | $0.0672 / image | $0.01142 / image | −83% |
| [Stable Diffusion XL (Venice, legacy)](https://martllm.com/models/venice/sdxl) | image | $0.03584 / image | $0.0063 / image | −82% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | text | $0.194 / $0.6098 | $0.03528 / $0.1109 | −82% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | text | $0.243 / $0.5889 | $0.06153 / $0.1491 | −75% |
| [Qwen 3 235B A22B Instruct 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-2507) | text | $0.1006 / $0.5591 | $0.02551 / $0.1417 | −75% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | text | $0.08747 / $0.3155 | $0.02425 / $0.09013 | in −72% / out −71% |
| [MiniMax M2.7 Highspeed](https://martllm.com/models/minimax/minimax-m2.7-highspeed) | text | $0.189 / $0.756 | $0.063 / $0.252 | −67% |
| [Flux 1.1 Pro (Venice, legacy)](https://martllm.com/models/venice/flux-1.1-pro) | image | $0.03584 / image | $0.01344 / image | −62% |
| [MiMo-V2.5-Pro](https://martllm.com/models/xiaomi/mimo-v2.5-pro) | text | $0.504 / $1.89 | $0.3654 / $0.7308 | in −28% / out −61% |
| [Seedance 2.0 Text-to-Video](https://martllm.com/models/bytedance/seedance-2-0-text-to-video) | video | $0.1276 / sec | $0.0593 / sec | −54% |
| [FLUX.1 Kontext Max](https://martllm.com/models/black-forest-labs/flux-kontext-max) | image | $0.056 / image | $0.02688 / image | −52% |
| [FLUX.1 Kontext Pro](https://martllm.com/models/black-forest-labs/flux-kontext-pro) | image | $0.028 / image | $0.01344 / image | −52% |
| [GPT-6.2 Astra](https://martllm.com/models/openai/gpt-6.2-astra) | text | $5.21 / $26.04 | $2.52 / $12.60 | −52% |
| [GPT-6 Astra](https://martllm.com/models/openai/gpt-6-astra) | text | $6.30 / $31.50 | $3.46 / $17.32 | −45% |
| [Seedream 5.0 Flash](https://martllm.com/models/bytedance/seedream-5-0-flash) | image | $0.01456 / image | $0.008064 / image | −45% |
| [Seedance 1.0 Pro Fast](https://martllm.com/models/bytedance/seedance-1-0-pro-fast-image-to-video) | video | $0.02016 / sec | $0.01142 / sec | −43% |
| [DeepSeek V4.1 Flash 1017 Ultrafast](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017-ultrafast) | text | $1.47 / $5.87 | $0.8452 / $3.38 | −42% |
| [Qwen 4 Max](https://martllm.com/models/qwen/qwen4-max) | text | $0.6434 / $1.93 | $0.3741 / $1.12 | −42% |
| [HappyHorse 1.0 Text-to-Video](https://martllm.com/models/happyhorse/happyhorse-1-0-text-to-video) | video | $0.215 / sec | $0.1254 / sec | −42% |
| [Claude Haiku 4.5](https://martllm.com/models/anthropic/claude-haiku-4.5) | text | $1.05 / $5.25 | $0.6195 / $3.10 | −41% |
| [MiniMax M2.5](https://martllm.com/models/minimax/minimax-m2.5) | text | $0.07087 / $0.2494 | $0.04253 / $0.1496 | −40% |
| [Wan 2.6 Text-to-Video](https://martllm.com/models/wan/wan-2-6-text-to-video) | video | $0.1108 / sec | $0.06712 / sec | −39% |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | music | $0.003187 / sec | $0.001932 / sec | −39% |
| [Claude Opus 5.5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5.5-fast) | text | $7.36 / $36.80 | $4.51 / $22.54 | −39% |
| [GPT-6 Sol](https://martllm.com/models/openai/gpt-6-sol) | text | $1.22 / $6.09 | $0.756 / $3.78 | −38% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | text | $1.03 / $5.14 | $0.651 / $3.25 | −37% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.01963 / $0.07854 | $0.0127 / $0.05082 | −35% |
| [Riverflow 2.0 Pro](https://martllm.com/models/sourceful/riverflow-2-0-pro-text-to-image) | image | $0.1428 / image | $0.0924 / image | −35% |
| [GPT Image 2.5 Flare (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-flare-edit) | image | $0.008592 / image | $0.0056 / image | −35% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | text | $0.2756 / $1.65 | $0.1811 / $1.09 | −34% |
| [GPT-5.6 Terra](https://martllm.com/models/openai/gpt-5.6-terra) | text | $1.18 / $7.06 | $0.777 / $4.66 | −34% |
| [GPT-5.6 Sol](https://martllm.com/models/openai/gpt-5.6-sol) | text | $1.97 / $9.87 | $1.34 / $6.72 | −32% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | text | $1.50 / $9.00 | $1.05 / $6.30 | −30% |
| [MiMo-V2.6-Flash-MOPD](https://martllm.com/models/xiaomi/mimo-v2.6-flash-mopd) | text | $0.525 / $1.05 | $0.3675 / $0.735 | −30% |
| [Grok Imagine — Edit (Venice)](https://martllm.com/models/venice/grok-imagine-edit) | image | $0.0224 / image | $0.01575 / image | −30% |
| [Ideogram V2](https://martllm.com/models/ideogram/ideogram-v2) | image | $0.1075 / image | $0.07616 / image | −29% |
| [Ideogram V2 Turbo](https://martllm.com/models/ideogram/ideogram-v2-turbo) | image | $0.0672 / image | $0.0476 / image | −29% |
| [Gemini 3.6 Flash](https://martllm.com/models/google/gemini-3-6-flash) | text | $0.5513 / $2.76 | $0.3937 / $1.97 | −29% |
| [GPT-6.1 Sol](https://martllm.com/models/openai/gpt-6.1-sol) | text | $1.03 / $5.14 | $0.735 / $3.67 | −29% |
| [Seedance 1.5 Pro (image-to-video)](https://martllm.com/models/bytedance/seedance-1-5-pro-image-to-video) | video | $0.0495 / sec | $0.0357 / sec | −28% |
| [GPT-6.2 Sol](https://martllm.com/models/openai/gpt-6.2-sol) | text | $1.09 / $5.46 | $0.819 / $4.09 | −25% |
| [Venice Music Gen (legacy alias)](https://martllm.com/models/venice/music-gen) | music | $0.0336 / track | $0.0252 / track | −25% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.0189 / $0.0882 | $0.01488 / $0.0671 | in −21% / out −24% |
| [Grok 4.5](https://martllm.com/models/x-ai/grok-4.5) | text | $1.45 / $4.36 | $1.12 / $3.36 | −23% |
| [Qwen: Qwen3.7 Flash](https://martllm.com/models/qwen/qwen3.7-flash) | text | $0.02489 / $0.1078 | $0.01921 / $0.08327 | −23% |
| [Claude Sonnet 5.5](https://martllm.com/models/anthropic/claude-sonnet-5.5) | text | $1.30 / $6.51 | $1.01 / $5.04 | −23% |
| [NVIDIA Nemotron 3 Ultra 550B](https://martllm.com/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.2415 / $1.06 | $0.189 / $0.8316 | −22% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | text | $0.399 / $2.00 | $0.315 / $1.57 | −21% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | text | $5.46 / $27.30 | $4.37 / $21.84 | −20% |
| [GPT OSS 20B](https://martllm.com/models/openai/e2ee-gpt-oss-20b-p) | text | $0.02625 / $0.09975 | $0.021 / $0.0798 | −20% |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | music | $0.0448 / track | $0.03584 / track | −20% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | text | $0.5775 / $2.18 | $0.462 / $1.74 | −20% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-multilingual-v2) | music | $0.0966 / 1K chars | $0.07728 / 1K chars | −20% |
| [ElevenLabs TTS v3 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-v3) | music | $0.0966 / 1K chars | $0.07728 / 1K chars | −20% |
| [MiniMax M2.7](https://martllm.com/models/minimax/minimax-m2.7) | text | $0.1614 / $0.6458 | $0.1299 / $0.5198 | −20% |
| [Wan 2.7 Text-to-Video](https://martllm.com/models/wan/wan-2-7-text-to-video) | video | $0.1108 / sec | $0.0896 / sec | −19% |
| [xAI Speech to Text v1 (Venice)](https://martllm.com/models/venice/xai-stt-v1) | transcription | $0.002115 / minute | $0.001713 / minute | −19% |
| [Qwen 3.6 35B A3B](https://martllm.com/models/qwen/qwen3-6-35b-a3b) | text | $0.0777 / $0.777 | $0.063 / $0.63 | −19% |
| [MiMo-V2.6-Pro](https://martllm.com/models/xiaomi/mimo-v2.6-pro) | text | $0.3015 / $0.6029 | $0.2466 / $0.4933 | −18% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | text | $0.1285 / $0.7409 | $0.1053 / $0.6071 | −18% |
| [Qwen3.8 Flash](https://martllm.com/models/qwen/qwen3.8-flash) | text | $0.03623 / $0.1135 | $0.02993 / $0.09377 | −17% |
| [Google: Gemini 4 Carbon](https://martllm.com/models/google/gemini-4-carbon) | text | $0.882 / $4.41 | $0.735 / $3.67 | −17% |
| [Vidu Q3 Pro](https://martllm.com/models/vidu/viduq3-pro) | video | $0.05661 / sec | $0.0476 / sec | −16% |
| [Kling 2.1 Standard](https://martllm.com/models/kling/kling-2-1-standard-image-to-video) | video | $0.05656 / sec | $0.0476 / sec | −16% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | text | $6.30 / $31.50 | $5.36 / $26.77 | −15% |
| [Qwen Image 2.1](https://martllm.com/models/qwen/qwen-image-2-1) | image | $0.0224 / image | $0.01904 / image | −15% |
| [Lyria 3 Pro](https://martllm.com/models/google-deepmind/lyria-3-pro) | music | $0.0784 / track | $0.0672 / track | −14% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | text | $0.01544 / $0.06615 | $0.01323 / $0.0567 | −14% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.2632 / $0.7895 | $0.2264 / $0.6791 | −14% |
| [Kling 2.1 Pro](https://martllm.com/models/kling/kling-2-1-pro-image-to-video) | video | $0.09856 / sec | $0.08568 / sec | −13% |
| [ElevenLabs Scribe v2 (STT)](https://martllm.com/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.01044 / minute | $0.00909 / minute | −13% |
| [Wan 2.5 Preview (image-to-video)](https://martllm.com/models/wan/wan-2-5-preview-image-to-video) | video | $0.06712 / sec | $0.0588 / sec | −12% |
| [GPT-5.6 Luna](https://martllm.com/models/openai/gpt-5.6-luna) | text | $0.0693 / $0.4158 | $0.0609 / $0.3654 | −12% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | text | $0.08069 / $0.1675 | $0.07095 / $0.1473 | −12% |
| [Thinking Machines: Inkling 2 Mini](https://martllm.com/models/thinking-machines/inkling-2-mini) | text | $0.0756 / $0.3024 | $0.06662 / $0.2665 | −12% |
| [Qwen3 VL 235B A22B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-instruct) | text | $0.05475 / $0.4954 | $0.04851 / $0.4389 | −11% |
| [Grok 4.20 Multi-Agent Beta](https://martllm.com/models/x-ai/grok-4.20-multi-agent-beta) | text | $1.15 / $2.29 | $1.03 / $2.05 | −10% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $0.4135 / $0.827 | $0.3707 / $0.7415 | −10% |
| [Z.ai: GLM 5.3 FlashX Legal](https://martllm.com/models/z-ai/glm-5.3-flashx-legal) | text | $0.2642 / $0.8925 | $0.2914 / $0.9844 | +10% |
| [Grok 4.20](https://martllm.com/models/x-ai/grok-4.20) | text | $0.7219 / $1.44 | $0.8002 / $1.59 | in +11% / out +10% |
| [Grok 4.20 Multi-Agent](https://martllm.com/models/x-ai/grok-4.20-multi-agent) | text | $0.7219 / $1.44 | $0.8002 / $1.59 | in +11% / out +10% |
| [Cohere: Command A+](https://martllm.com/models/cohere/command-a-plus) | text | $0.2961 / $1.48 | $0.3307 / $1.65 | +12% |
| [Elorian: Glimpse](https://martllm.com/models/elorian/glimpse) | text | $0.5922 / $2.96 | $0.6615 / $3.31 | +12% |
| [Moondream: Moondream 3.1](https://martllm.com/models/moondream/moondream3.1-9b-a2b) | text | $0.2961 / $2.47 | $0.3307 / $2.76 | +12% |
| [GPT-5.2 Codex](https://martllm.com/models/openai/gpt-5.2-codex) | text | $1.64 / $13.08 | $1.84 / $14.70 | +12% |
| [GPT-4o mini (Fast)](https://martllm.com/models/openai/gpt-4o-mini-fast) | text | $0.23 / $0.92 | $0.2587 / $1.03 | +12% |
| [Nova Lite](https://martllm.com/models/amazon/nova-lite) | text | $0.0552 / $0.2208 | $0.0621 / $0.2484 | +12% |
| [Nova Micro](https://martllm.com/models/amazon/nova-micro) | text | $0.0322 / $0.1288 | $0.03623 / $0.1449 | +12% |
| [Nova Pro](https://martllm.com/models/amazon/nova-pro) | text | $0.736 / $2.94 | $0.828 / $3.31 | +12% |
| [Claude Fable 5.2 (Fast)](https://martllm.com/models/anthropic/claude-fable-5.2-fast) | text | $14.72 / $73.60 | $16.56 / $82.80 | +12% |
| [Claude Opus 4.8 Fast](https://martllm.com/models/anthropic/claude-opus-4.8-fast) | text | $9.20 / $46.00 | $10.35 / $51.75 | +12% |
| [Apex](https://martllm.com/models/callstack/apex) | text | $0.46 / $2.76 | $0.5175 / $3.10 | +12% |
| [DeepSeek V4.1 Flash 1017 Fast](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017-fast) | text | $0.552 / $2.21 | $0.621 / $2.48 | +12% |
| [DeepSeek V4.1 Flash Fast](https://martllm.com/models/deepseek/deepseek-v4.1-flash-fast) | text | $0.552 / $2.21 | $0.621 / $2.48 | +12% |
| [Gemini 4 Neon (Fast)](https://martllm.com/models/google/gemini-4-neon-fast) | text | $4.97 / $24.84 | $5.59 / $27.95 | +12% |
| [Gemini Omni Flash Preview](https://martllm.com/models/google/gemini-omni-flash-preview) | text | $1.38 / $8.28 | $1.55 / $9.31 | +12% |
| [Mercury 3](https://martllm.com/models/inception/mercury-3) | text | $0.092 / $0.322 | $0.1035 / $0.3623 | +12% |
| [Ling 3.0 Flash Fin](https://martllm.com/models/inclusionai/ling-3.0-flash-fin) | text | $0.069 / $0.2024 | $0.07762 / $0.2277 | +12% |
| [Ling 3.0 Flash Sante](https://martllm.com/models/inclusionai/ling-3.0-flash-sante) | text | $0.069 / $0.2024 | $0.07762 / $0.2277 | +12% |
| [Ling 3.1 Flash 1019](https://martllm.com/models/inclusionai/ling-3.1-flash-1019) | text | $0.276 / $0.828 | $0.3105 / $0.9315 | +12% |
| [Interfaze Beta](https://martllm.com/models/interfaze/interfaze-beta) | text | $1.38 / $3.22 | $1.55 / $3.62 | +12% |
| [Meituan: LongCat 2.5](https://martllm.com/models/meituan/longcat-2.5) | text | $0.276 / $1.10 | $0.3105 / $1.24 | +12% |
| [Llama 3.1 70B Instruct](https://martllm.com/models/meta-llama/llama-3.1-70b) | text | $0.6624 / $0.6624 | $0.7452 / $0.7452 | +12% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b) | text | $0.6624 / $0.6624 | $0.7452 / $0.7452 | +12% |
| [Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder-1.0) | text | $3.68 / $18.40 | $4.14 / $20.70 | +12% |
| [Mistral Codestral](https://martllm.com/models/mistralai/codestral) | text | $0.276 / $0.828 | $0.3105 / $0.9315 | +12% |
| [Ministral 14B](https://martllm.com/models/mistralai/ministral-14b) | text | $0.184 / $0.184 | $0.207 / $0.207 | +12% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3b) | text | $0.092 / $0.092 | $0.1035 / $0.1035 | +12% |
| [Ministral 8B](https://martllm.com/models/mistralai/ministral-8b) | text | $0.138 / $0.138 | $0.1552 / $0.1552 | +12% |
| [Mistral Small](https://martllm.com/models/mistralai/mistral-small) | text | $0.138 / $0.552 | $0.1552 / $0.621 | +12% |
| [Toast 1](https://martllm.com/models/mixedbread/toast-1) | text | $0.276 / $0.6624 | $0.3105 / $0.7452 | +12% |
| [Kimi K2.7 Code High Speed](https://martllm.com/models/moonshotai/kimi-k2.7-code-highspeed) | text | $1.75 / $7.36 | $1.97 / $8.28 | +12% |
| [Nvidia Nemotron Nano 12B V2 VL](https://martllm.com/models/nvidia/nemotron-nano-12b-v2-vl) | text | $0.184 / $0.552 | $0.207 / $0.621 | +12% |
| [GPT-4.1 (Fast)](https://martllm.com/models/openai/gpt-4.1-fast) | text | $3.22 / $12.88 | $3.62 / $14.49 | +12% |
| [GPT-4.1 mini (Fast)](https://martllm.com/models/openai/gpt-4.1-mini-fast) | text | $0.644 / $2.58 | $0.7245 / $2.90 | +12% |
| [GPT-5-Codex](https://martllm.com/models/openai/gpt-5-codex) | text | $1.15 / $9.20 | $1.29 / $10.35 | +12% |
| [GPT-5 (Fast)](https://martllm.com/models/openai/gpt-5-fast) | text | $2.30 / $18.40 | $2.59 / $20.70 | +12% |
| [GPT-5 mini (Fast)](https://martllm.com/models/openai/gpt-5-mini-fast) | text | $0.414 / $3.31 | $0.4657 / $3.73 | +12% |
| [GPT 5.1 Thinking (Fast)](https://martllm.com/models/openai/gpt-5.1-thinking-fast) | text | $2.30 / $18.40 | $2.59 / $20.70 | +12% |
| [GPT 5.2 (Fast)](https://martllm.com/models/openai/gpt-5.2-fast) | text | $3.22 / $25.76 | $3.62 / $28.98 | +12% |
| [GPT 5.3 Codex (Fast)](https://martllm.com/models/openai/gpt-5.3-codex-fast) | text | $3.22 / $25.76 | $3.62 / $28.98 | +12% |
| [GPT 5.4 (Fast)](https://martllm.com/models/openai/gpt-5.4-fast) | text | $4.60 / $27.60 | $5.17 / $31.05 | +12% |
| [GPT 5.4 Mini (Fast)](https://martllm.com/models/openai/gpt-5.4-mini-fast) | text | $1.38 / $8.28 | $1.55 / $9.31 | +12% |
| [GPT 5.5 (Fast)](https://martllm.com/models/openai/gpt-5.5-fast) | text | $11.50 / $69.00 | $12.94 / $77.62 | +12% |
| [GPT 5.6 Luna (Fast)](https://martllm.com/models/openai/gpt-5.6-luna-fast) | text | $0.368 / $2.21 | $0.414 / $2.48 | +12% |
| [GPT 5.6 Sol (Fast)](https://martllm.com/models/openai/gpt-5.6-sol-fast) | text | $7.36 / $36.80 | $8.28 / $41.40 | +12% |
| [GPT 5.6 Terra (Fast)](https://martllm.com/models/openai/gpt-5.6-terra-fast) | text | $3.68 / $22.08 | $4.14 / $24.84 | +12% |
| [GPT-6 Astra (Fast)](https://martllm.com/models/openai/gpt-6-astra-fast) | text | $18.40 / $92.00 | $20.70 / $103.50 | +12% |
| [GPT-6 Luna (Fast)](https://martllm.com/models/openai/gpt-6-luna-fast) | text | $0.184 / $0.92 | $0.207 / $1.03 | +12% |
| [GPT-6 Sol (Fast)](https://martllm.com/models/openai/gpt-6-sol-fast) | text | $3.68 / $18.40 | $4.14 / $20.70 | +12% |
| [GPT-6.1 Sol (Fast)](https://martllm.com/models/openai/gpt-6.1-sol-fast) | text | $3.68 / $18.40 | $4.14 / $20.70 | +12% |
| [GPT-6.1 Terra (Fast)](https://martllm.com/models/openai/gpt-6.1-terra-fast) | text | $1.84 / $9.20 | $2.07 / $10.35 | +12% |
| [GPT-6.2 Astra (Fast)](https://martllm.com/models/openai/gpt-6.2-astra-fast) | text | $14.72 / $73.60 | $16.56 / $82.80 | +12% |
| [GPT-6.2 Sol (Fast)](https://martllm.com/models/openai/gpt-6.2-sol-fast) | text | $3.68 / $18.40 | $4.14 / $20.70 | +12% |
| [o1](https://martllm.com/models/openai/o1) | text | $13.80 / $55.20 | $15.53 / $62.10 | +12% |
| [o3 (Fast)](https://martllm.com/models/openai/o3-fast) | text | $3.22 / $12.88 | $3.62 / $14.49 | +12% |
| [o3-mini](https://martllm.com/models/openai/o3-mini) | text | $1.01 / $4.05 | $1.14 / $4.55 | +12% |
| [o4-mini](https://martllm.com/models/openai/o4-mini) | text | $1.01 / $4.05 | $1.14 / $4.55 | +12% |
| [Ultramarine 1 Flash](https://martllm.com/models/paperinstruments/ultramarine-1-flash) | text | $0.138 / $0.46 | $0.1552 / $0.5175 | +12% |
| [Arrow 2](https://martllm.com/models/quiverai/arrow-2) | text | $3.68 / $18.40 | $4.14 / $20.70 | +12% |
| [Arrow 2 Telos](https://martllm.com/models/quiverai/arrow-2-telos) | text | $5.52 / $27.60 | $6.21 / $31.05 | +12% |
| [Qwen3-30B-A3B](https://martllm.com/models/qwen/qwen-3-30b) | text | $0.1104 / $0.46 | $0.1242 / $0.5175 | +12% |
| [Qwen 3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b) | text | $0.138 / $0.552 | $0.1552 / $0.621 | +12% |
| [Qwen3 VL 235B A22B Instruct](https://martllm.com/models/qwen/qwen3-vl-instruct) | text | $0.184 / $0.8096 | $0.207 / $0.9108 | +12% |
| [Sakana Namazu](https://martllm.com/models/sakana/namazu) | text | $0.874 / $3.68 | $0.9832 / $4.14 | +12% |
| [Tencent Hy-MT2-Lite](https://martllm.com/models/tencent/hy-mt2-lite) | text | $0.04048 / $0.1628 | $0.04554 / $0.1832 | +12% |
| [Grok 4.20 Beta Non-Reasoning](https://martllm.com/models/x-ai/grok-4.20-non-reasoning-beta) | text | $1.15 / $2.30 | $1.29 / $2.59 | +12% |
| [Grok 4.20 Beta Reasoning](https://martllm.com/models/x-ai/grok-4.20-reasoning-beta) | text | $1.15 / $2.30 | $1.29 / $2.59 | +12% |
| [GLM 4.7 FlashX](https://martllm.com/models/z-ai/glm-4.7-flashx) | text | $0.0552 / $0.368 | $0.0621 / $0.414 | +12% |
| [Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4) | text | $0.644 / $1.93 | $0.7245 / $2.17 | in +12% / out +13% |
| [Tencent Hy-MT2-Plus](https://martllm.com/models/tencent/hy-mt2-plus) | text | $0.06808 / $0.2714 | $0.07659 / $0.3053 | in +12% / out +13% |
| [Tencent Hy-MT2-Pro](https://martllm.com/models/tencent/hy-mt2-pro) | text | $0.06808 / $0.2714 | $0.07659 / $0.3053 | in +12% / out +13% |
| [Moondream: Moondream 3 Preview](https://martllm.com/models/moondream/moondream3-preview) | text | $0.2929 / $2.44 | $0.3307 / $2.76 | +13% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | text | $0.0189 / $0.0567 | $0.02142 / $0.06426 | +13% |
| [Qwen 3.6 Plus](https://martllm.com/models/qwen/qwen3.6-plus) | text | $0.1877 / $1.13 | $0.2161 / $1.30 | +15% |
| [MiniMax Music 2.6 (Venice)](https://martllm.com/models/venice/minimax-music-v26) | music | $0.1317 / track | $0.1532 / track | +16% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | text | $0.1328 / $0.6641 | $0.1559 / $0.7796 | +17% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | text | $0.03696 / $0.3696 | $0.04368 / $0.4368 | +18% |
| [Qwen3.6 Flash](https://martllm.com/models/qwen/qwen3.6-flash) | text | $0.1083 / $0.6497 | $0.1296 / $0.7775 | +20% |
| [MiniMax M3.1 Flash](https://martllm.com/models/minimax/minimax-m3-1-flash) | text | $0.01575 / $0.063 | $0.0189 / $0.0756 | +20% |
| [Gemma 3 27B](https://martllm.com/models/google/gemma-3-27b-it) | text | $0.02268 / $0.0567 | $0.02772 / $0.0693 | +22% |
| [Mistral: Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4-0) | text | $0.1003 / $0.301 | $0.1235 / $0.3704 | +23% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | text | $0.1974 / $0.8636 | $0.2436 / $1.07 | +23% |
| [Meta: Muse Spark 1.2](https://martllm.com/models/meta-llama/muse-spark-1.2) | text | $0.5381 / $1.83 | $0.6694 / $2.28 | +24% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | text | $0.3242 / $1.35 | $0.4095 / $1.70 | +26% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-v3.1) | text | $0.05387 / $0.1995 | $0.06807 / $0.2521 | +26% |
| [Claude Haiku 5.5](https://martllm.com/models/anthropic/claude-haiku-5.5) | text | $0.063 / $0.315 | $0.0798 / $0.399 | +27% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.02231 / $0.08032 | $0.02898 / $0.0966 | in +30% / out +20% |
| [Meta: Muse Spark 1.3](https://martllm.com/models/meta-llama/muse-spark-1.3) | text | $0.4725 / $1.61 | $0.6169 / $2.10 | +31% |
| [GPT-5](https://martllm.com/models/openai/gpt-5) | text | $0.7219 / $5.78 | $0.945 / $7.56 | +31% |
| [GPT-5.1](https://martllm.com/models/openai/gpt-5.1) | text | $0.7219 / $5.78 | $0.945 / $7.56 | +31% |
| [o3 Pro](https://martllm.com/models/openai/o3-pro) | text | $11.55 / $46.20 | $15.12 / $60.48 | +31% |
| [Gemini 3.1 Flash Lite Preview](https://martllm.com/models/google/gemini-3.1-flash-lite-preview) | text | $0.1444 / $0.8662 | $0.189 / $1.13 | +31% |
| [GPT-4.1](https://martllm.com/models/openai/gpt-4.1) | text | $1.16 / $4.62 | $1.51 / $6.05 | +31% |
| [GPT-4.1 mini](https://martllm.com/models/openai/gpt-4.1-mini) | text | $0.231 / $0.924 | $0.3024 / $1.21 | +31% |
| [GPT-5 pro](https://martllm.com/models/openai/gpt-5-pro) | text | $8.66 / $69.30 | $11.34 / $90.72 | +31% |
| [GPT 5.2](https://martllm.com/models/openai/gpt-5.2-pro) | text | $12.13 / $97.02 | $15.88 / $127.01 | +31% |
| [o3](https://martllm.com/models/openai/o3) | text | $1.16 / $4.62 | $1.51 / $6.05 | +31% |
| [Step 3.7 Flash](https://martllm.com/models/stepfun/step-3.7-flash) | text | $0.1155 / $0.6641 | $0.1512 / $0.8694 | +31% |
| [MMAudio V2 Text-to-Audio (Venice)](https://martllm.com/models/venice/mmaudio-v2-text-to-audio) | music | $0.0007733 / sec | $0.00103 / sec | +33% |
| [FLUX 2 Klein Base 9b Text To Image](https://martllm.com/models/black-forest-labs/flux-2-klein-base-9b-text-to-image) | image | $0.01428 / image | $0.01904 / image | +33% |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | music | $0.03864 / 1K chars | $0.05152 / 1K chars | +33% |
| [Ltx 2 V2.3 Full (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.06925 / sec | $0.09272 / sec | +34% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.05227 / sec | $0.07004 / sec | +34% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | text | $0.2205 / $1.10 | $0.2993 / $1.50 | +36% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | text | $0.00609 / $0.021 | $0.008374 / $0.02888 | +38% |
| [Qwen3 Coder Next](https://martllm.com/models/qwen/qwen3-coder-next) | text | $0.02268 / $0.1512 | $0.03137 / $0.2092 | +38% |
| [NVIDIA Nemotron 3 Nano 30B](https://martllm.com/models/nvidia/nemotron-3-nano-30b-a3b) | text | $0.03071 / $0.1229 | $0.04331 / $0.1732 | +41% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | text | $0.063 / $0.189 | $0.08925 / $0.2677 | +42% |
| [Qwen3 0.6B TTS](https://martllm.com/models/qwen/tts-qwen3-0-6b) | speech | $0.0686 / 1K chars | $0.098 / 1K chars | +43% |
| [GPT-4.1 nano](https://martllm.com/models/openai/gpt-4.1-nano) | text | $0.05775 / $0.231 | $0.084 / $0.336 | +45% |
| [GPT-4o (2024-08-06)](https://martllm.com/models/openai/gpt-4o-2024-08-06) | text | $1.44 / $5.78 | $2.10 / $8.40 | +45% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | text | $0.01512 / $0.0504 | $0.021 / $0.0735 | in +39% / out +46% |
| [MiniMax M2](https://martllm.com/models/minimax/minimax-m2) | text | $0.0252 / $0.1008 | $0.0378 / $0.1512 | +50% |
| [Reflection: Beam 1.0 501B A23B](https://martllm.com/models/reflection/beam-1.0-501b-a23b) | text | $0.3612 / $1.10 | $0.5502 / $1.65 | in +52% / out +50% |
| [NVIDIA Nemotron 3 Super 120B](https://martllm.com/models/nvidia/nemotron-3-super-120b) | text | $0.01181 / $0.063 | $0.01811 / $0.0966 | +53% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | text | $0.2362 / $0.945 | $0.3675 / $1.47 | +56% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | music | $0.001159 / sec | $0.001804 / sec | +56% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.01496 / $0.1732 | $0.02372 / $0.2747 | +59% |
| [OpenAI: GPT-6.1 Terra Pro](https://martllm.com/models/openai/gpt-6.1-terra-pro) | text | $0.987 / $4.93 | $1.57 / $7.88 | +60% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.08427 / $0.3352 | $0.1345 / $0.4996 | in +60% / out +49% |
| [GPT-4o Mini](https://martllm.com/models/openai/gpt-4o-mini) | text | $0.0315 / $0.126 | $0.0504 / $0.2016 | +60% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | text | $0.1207 / $0.7245 | $0.1943 / $1.17 | +61% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | text | $0.07717 / $0.2315 | $0.1307 / $0.3921 | +69% |
| [Llama 4 Maverick](https://martllm.com/models/meta-llama/llama-4-maverick) | text | $0.2021 / $0.5775 | $0.2484 / $1.00 | in +23% / out +74% |
| [Parakeet ASR (Venice)](https://martllm.com/models/venice/parakeet-asr) | transcription | $0.003024 / minute | $0.005376 / minute | +78% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | text | $0.0882 / $0.3675 | $0.1569 / $0.6536 | +78% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | text | $0.0483 / $0.0966 | $0.0861 / $0.1722 | +78% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | text | $0.00588 / $0.01176 | $0.0105 / $0.021 | +79% |
| [Ling 3.0 Flash](https://martllm.com/models/inclusionai/ling-3.0-flash) | text | $0.01213 / $0.03638 | $0.02174 / $0.0652 | +79% |
| [Claude Haiku 5.5 (batch)](https://martllm.com/models/anthropic/claude-haiku-5.5:batch) | text | $0.02888 / $0.1444 | $0.05175 / $0.2587 | +79% |
| [Command A](https://martllm.com/models/cohere/command-a) | text | $1.44 / $5.78 | $2.59 / $10.35 | +79% |
| [Gemini 2.5 Flash Lite](https://martllm.com/models/google/gemini-2.5-flash-lite) | text | $0.05775 / $0.231 | $0.1035 / $0.414 | +79% |
| [Morph V3 Large](https://martllm.com/models/morph/morph-v3-large) | text | $0.5198 / $1.10 | $0.9315 / $1.97 | +79% |
| [GPT-5.1-Codex](https://martllm.com/models/openai/gpt-5.1-codex) | text | $0.7219 / $5.78 | $1.29 / $10.35 | +79% |
| [GPT 5.1 Codex Max](https://martllm.com/models/openai/gpt-5.1-codex-max) | text | $0.7219 / $5.78 | $1.29 / $10.35 | +79% |
| [GPT 5.1 Codex Mini](https://martllm.com/models/openai/gpt-5.1-codex-mini) | text | $0.1444 / $1.16 | $0.2587 / $2.07 | +79% |
| [Gemini 2.5 Flash](https://martllm.com/models/google/gemini-2.5-flash) | text | $0.1732 / $1.44 | $0.3105 / $2.59 | +79% |
| [Schematron V2 Small](https://martllm.com/models/inference-net/schematron-v2-small) | text | $0.02888 / $0.1328 | $0.05175 / $0.2381 | +79% |
| [Schematron V2 Turbo](https://martllm.com/models/inference-net/schematron-v2-turbo) | text | $0.01733 / $0.08662 | $0.03105 / $0.1552 | +79% |
| [Mistral Medium Latest](https://martllm.com/models/mistralai/mistral-medium-3.5) | text | $0.8662 / $4.33 | $1.55 / $7.76 | +79% |
| [Mistral Nemo 12B](https://martllm.com/models/mistralai/mistral-nemo) | text | $0.01675 / $0.01733 | $0.03002 / $0.03105 | +79% |
| [Morph V3 Fast](https://martllm.com/models/morph/morph-v3-fast) | text | $0.462 / $0.693 | $0.828 / $1.24 | +79% |
| [Qwen3-14B](https://martllm.com/models/qwen/qwen-3-14b) | text | $0.0693 / $0.1386 | $0.1242 / $0.2484 | +79% |
| [Fugu Ultra](https://martllm.com/models/sakana/fugu-ultra) | text | $2.89 / $17.32 | $5.17 / $31.05 | +79% |
| [GLM 4.5V](https://martllm.com/models/z-ai/glm-4.5v) | text | $0.3465 / $1.04 | $0.621 / $1.86 | +79% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | text | $0.0463 / $0.0463 | $0.08379 / $0.08379 | +81% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | text | $0.168 / $0.504 | $0.315 / $0.945 | +88% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://martllm.com/models/nvidia/nemotron-nano-12b-v2) | text | $0.0357 / $0.1071 | $0.0714 / $0.2142 | +100% |
| [Qwen 3 235B A22B Thinking 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.1229 / $0.9555 | $0.2599 / $2.02 | +112% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | text | $0.0483 / $0.0966 | $0.105 / $0.21 | +117% |
| [Ling 3.0 Flash VL](https://martllm.com/models/inclusionai/ling-3.0-flash-vl) | text | $0.03465 / $0.104 | $0.07762 / $0.2277 | in +124% / out +119% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | text | $0.01213 / $0.01213 | $0.02756 / $0.02756 | +127% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | text | $0.00735 / $0.02352 | $0.0189 / $0.0567 | in +157% / out +141% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | text | $0.02481 / $0.02481 | $0.06615 / $0.06615 | +167% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | text | $0.0504 / $0.315 | $0.1617 / $1.01 | +221% |
| [Grok Imagine Text-to-Video](https://martllm.com/models/x-ai/grok-imagine-text-to-video) | video | $0.01344 / sec | $0.04725 / sec | +252% |
| [GPT OSS Safeguard 120B](https://martllm.com/models/openai/gpt-oss-safeguard-120b) | text | $0.01103 / $0.0441 | $0.03938 / $0.1575 | +257% |
| [NVIDIA Nemotron 3 Super 120B A12B](https://martllm.com/models/nvidia/nemotron-3-super-120b-a12b) | text | $0.04331 / $0.231 | $0.1552 / $0.6727 | in +258% / out +191% |
| [Sonar](https://martllm.com/models/perplexity/sonar) | text | $0.5775 / $0.5775 | $0.2587 / $2.59 | in −55% / out +348% |
| [Palmyra Vision 7B](https://martllm.com/models/writer/palmyra-vision-7b) | text | $0.00315 / $0.0126 | $0.01733 / $0.0693 | +450% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | text | $0.008531 / $0.02559 | $0.04791 / $0.1437 | +462% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | text | $0.002363 / $0.004725 | $0.04725 / $0.0945 | +1900% |

</details>


## 2026-11-27 (vs 2026-11-26)

**Official list price changes (50)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.13 / $0.50 | $0.125 / $0.45 | in −4% / out −10% |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | text | $1.19 / $4.38 | $1.19 / $4.29 | in 0% / out −2% |
| [FLUX 2 Klein Base 9b Text To Image](https://martllm.com/models/black-forest-labs/flux-2-klein-base-9b-text-to-image) | image | – | $0.015 / image |  |
| [Flux 3 First Last Frame](https://martllm.com/models/black-forest-labs/flux-3-first-last-frame-to-video) | video | – | $0.188 / sec |  |
| [Flux 3 Max](https://martllm.com/models/black-forest-labs/flux-3-max-image-to-video) | video | – | $0.1663 / sec |  |
| [Fibo](https://martllm.com/models/bria/fibo) | image | – | $0.04 / image |  |
| [Text To Image 3.2](https://martllm.com/models/bria/text-to-image-3-2) | image | – | $0.04 / image |  |
| [Seedance 1.5 Pro Text-to-Video](https://martllm.com/models/bytedance/seedance-1-5-pro-text-to-video) | video | – | $0.058 / sec |  |
| [Veo3 Fast (image-to-video)](https://martllm.com/models/google/veo3-fast-image-to-video) | video | – | $0.11 / sec |  |
| [Veo 3 Fast Text-to-Video](https://martllm.com/models/google/veo3-fast-text-to-video) | video | – | $0.165 / sec |  |
| [Veo 3 Full Text-to-Video](https://martllm.com/models/google/veo3-full-text-to-video) | video | – | $0.44 / sec |  |
| [Ideogram V2a](https://martllm.com/models/ideogram/ideogram-v2a) | image | – | $0.04 / image |  |
| [Ideogram V2a Turbo](https://martllm.com/models/ideogram/ideogram-v2a-turbo) | image | – | $0.04 / image |  |
| [Ideogram V3 Generate Transparent](https://martllm.com/models/ideogram/ideogram-v3-generate-transparent) | image | – | $0.085 / image |  |
| [Inworld 1.5 Max TTS](https://martllm.com/models/inworld/tts-inworld-1-5-max) | speech | – | $0.0125 / 1K chars |  |
| [Kling Image O1](https://martllm.com/models/kling/kling-image-o1) | image | – | $0.028 / image |  |
| [Kling O3.4k (reference-to-video)](https://martllm.com/models/kling/kling-o3-4k-reference-to-video) | video | – | $0.4633 / sec |  |
| [Krea 3](https://martllm.com/models/krea/krea-3) | image | – | $0.07 / image |  |
| [Krea V2 Medium Turbo Text To Image](https://martllm.com/models/krea/krea-v2-medium-turbo-text-to-image) | image | – | $0.015 / image |  |
| [LTX Video 2.5 Fast](https://martllm.com/models/lightricks/ltx-2-5-fast-image-to-video) | video | – | $0.09929 / sec |  |
| [LTX Video 2.5 Pro](https://martllm.com/models/lightricks/ltx-2-5-pro-image-to-video) | video | – | $0.1325 / sec |  |
| [LTX 2 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-fast-text-to-video) | video | – | $0.06667 / sec |  |
| [MAI Image 2.7](https://martllm.com/models/microsoft/mai-image-2-7) | image | – | $0.05 / image |  |
| [MAI Image 2.7 Flash](https://martllm.com/models/microsoft/mai-image-2-7-flash) | image | – | $0.02 / image |  |
| [MiniMax H3 Max Multi-Angle](https://martllm.com/models/minimax/minimax-h3-max-multi-angle) | video | – | $0.04571 / sec |  |
| [MiniMax H3 Max Turbo](https://martllm.com/models/minimax/minimax-h3-max-turbo-image-to-video) | video | – | $0.02286 / sec |  |
| [Cosmos 3 Super Text To Image](https://martllm.com/models/nvidia/cosmos-3-super-text-to-image) | image | – | $0.04 / image |  |
| [Qwen Image Text To Image 2512](https://martllm.com/models/qwen/qwen-image-text-to-image-2512) | image | – | $0.02 / image |  |
| [Recraft 20b](https://martllm.com/models/recraft/recraft-20b) | image | – | $0.022 / image |  |
| [Recraft V2](https://martllm.com/models/recraft/recraft-v2) | image | – | $0.022 / image |  |
| [Recraft V4.1](https://martllm.com/models/recraft/recraft-v4-1) | image | – | $0.035 / image |  |
| [Recraft V4.1 Flash](https://martllm.com/models/recraft/recraft-v4-1-flash) | image | – | $0.007 / image |  |
| [Recraft V4.1 Pro Text To Image](https://martllm.com/models/recraft/recraft-v4-1-pro-text-to-image) | image | – | $0.25 / image |  |
| [Recraft V4.1 Utility](https://martllm.com/models/recraft/recraft-v4-1-utility) | image | – | $0.035 / image |  |
| [Recraft V4.1 Utility Pro](https://martllm.com/models/recraft/recraft-v4-1-utility-pro) | image | – | $0.21 / image |  |
| [Runway Gen-4.5](https://martllm.com/models/runway/runway-gen4-5) | video | – | $0.16 / sec |  |
| [MAGI-2 Reference to Video](https://martllm.com/models/sand-ai/magi-2-reference-to-video) | video | – | $0.088 / sec |  |
| [Hunyuan Image 2.1](https://martllm.com/models/tencent/hunyuan-image-2-1) | image | – | $0.025 / image |  |
| [ACE-Step 1.5 (Venice)](https://martllm.com/models/venice/ace-step-15) | music | – | $0.03 / track |  |
| [Reference To Image Q2](https://martllm.com/models/vidu/reference-to-image-q2) | image | – | $0.04 / image |  |
| [Wan 2.1 Text To Image](https://martllm.com/models/wan/wan-2-1-text-to-image) | image | – | $0.02 / image |  |
| [Wan 2.2 A14B Text-to-Video](https://martllm.com/models/wan/wan-2-2-a14b-text-to-video) | video | – | $0.04 / sec |  |
| [Wan 2.2 Enhanced](https://martllm.com/models/wan/wan-2-2-enhanced-image-to-video) | video | – | $0.04 / sec |  |
| [Wan 2.2 Text To Image Realism](https://martllm.com/models/wan/wan-2-2-text-to-image-realism) | image | – | $0.025 / image |  |
| [Wan 2.7 Enhanced](https://martllm.com/models/wan/wan-2-7-enhanced-image-to-video) | video | – | $0.129 / sec |  |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | text | $1.31 / $3.96 | $1.32 / $3.96 | 0% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.15 / $0.666 | $0.15 / $0.70 | in 0% / out +5% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.21 / $0.78 | $0.2112 / $0.84 | in +1% / out +8% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | text | $0.09 / $0.30 | $0.10 / $0.32 | in +11% / out +7% |
| [Venice SD35](https://martllm.com/models/venice/sd35) | image | $0.01 / image | $0.065 / image | +550% |

**New models (229)**

| Model | Category | Official price | MartLLM price |
|---|---|---|---|
| [FLUX.2 Flash](https://martllm.com/models/black-forest-labs/flux-2-flash-text-to-image) | image | $0.025 / image | $0.0238 / image |
| [FLUX.2 [klein] 9B Text to Image](https://martllm.com/models/black-forest-labs/flux-2-klein-9b-text-to-image) | image | $0.01 / image | $0.00952 / image |
| [FLUX.2 [klein] Base 4B Text to Image](https://martllm.com/models/black-forest-labs/flux-2-klein-base-4b-text-to-image) | image | $0.01 / image | $0.00952 / image |
| [FLUX.2 [klein] Base 9B Edit](https://martllm.com/models/black-forest-labs/flux-2-klein-base-9b-edit) | image | $0.021 / image | $0.01999 / image |
| [FLUX.2 Turbo](https://martllm.com/models/black-forest-labs/flux-2-turbo-text-to-image) | image | $0.04 / image | $0.03808 / image |
| [FLUX 3 Klein Base](https://martllm.com/models/black-forest-labs/flux-3-klein-image-base-text-to-image) | image | $0.03 / image | $0.02856 / image |
| [FLUX 3 Klein Distilled](https://martllm.com/models/black-forest-labs/flux-3-klein-image-distilled-text-to-image) | image | $0.01 / image | $0.00952 / image |
| [FLUX 3 Video Edit](https://martllm.com/models/black-forest-labs/flux-3-video-edit) | video | – | $0.03 / sec |
| [FLUX 3 Video Upscale](https://martllm.com/models/black-forest-labs/flux-3-video-upscale) | video | – | $0.83 / sec |
| [FLUX.1 Dev Ultra Fast](https://martllm.com/models/black-forest-labs/flux-dev-ultra-fast) | image | $0.005 / image | $0.00476 / image |
| [FLUX.1 Kontext Dev Ultra Fast](https://martllm.com/models/black-forest-labs/flux-kontext-dev-ultra-fast) | image | $0.02 / image | $0.01904 / image |
| [FIBO 2.0 Text to Image](https://martllm.com/models/bria/fibo-2-0-text-to-image) | image | $0.04 / image | $0.03808 / image |
| [FIBO Generate 1.5](https://martllm.com/models/bria/fibo-generate-1-5-text-to-image) | image | $0.04 / image | $0.03808 / image |
| [Fibo Video Upscaler](https://martllm.com/models/bria/fibo-video-upscaler) | video | – | $0.05 / sec |
| [OmniHuman 2.0](https://martllm.com/models/bytedance/omnihuman-2-0) | video | – | $0.0784 / sec |
| [Seedance 1.0 Lite](https://martllm.com/models/bytedance/seedance-1-0-lite) | video | – | $0.0112 / sec |
| [Seedance 1.0 Pro Fast (text-to-video)](https://martllm.com/models/bytedance/seedance-1-0-pro-fast-text-to-video) | video | – | $0.01142 / sec |
| [Seedance 1.5 Pro Fast (image-to-video)](https://martllm.com/models/bytedance/seedance-1-5-pro-fast-image-to-video) | video | – | $0.01904 / sec |
| [Seedance 1.5 Pro Fast (text-to-video)](https://martllm.com/models/bytedance/seedance-1-5-pro-fast-text-to-video) | video | – | $0.01904 / sec |
| [Seedance 1.5 Pro Spicy (image-to-video)](https://martllm.com/models/bytedance/seedance-1-5-pro-image-to-video-spicy) | video | – | $0.01142 / sec |
| [Seedance 2.0 Fast Spicy (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-fast-image-to-video-spicy) | video | – | $0.0952 / sec |
| [Seedance 2.0 Fast Turbo (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-fast-image-to-video-turbo) | video | – | $0.1142 / sec |
| [Seedance 2.0 Fast Turbo (text-to-video)](https://martllm.com/models/bytedance/seedance-2-0-fast-text-to-video-turbo) | video | – | $0.1142 / sec |
| [Seedance 2.0 Fast Video Edit](https://martllm.com/models/bytedance/seedance-2-0-fast-video-edit) | video | – | $0.13 / sec |
| [Seedance 2.0 Fast Video Edit Turbo](https://martllm.com/models/bytedance/seedance-2-0-fast-video-edit-turbo) | video | – | $0.15 / sec |
| [Seedance 2.0 Spicy (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-image-to-video-spicy) | video | – | $0.1142 / sec |
| [Seedance 2.0 Turbo (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-image-to-video-turbo) | video | – | $0.1333 / sec |
| [Seedance 2.0 Mini Spicy (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-image-to-video-spicy) | video | – | $0.05712 / sec |
| [Seedance 2.0 Mini Turbo (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-image-to-video-turbo) | video | – | $0.07616 / sec |
| [Seedance 2.0 Mini Turbo (text-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-text-to-video-turbo) | video | – | $0.07616 / sec |
| [Seedance 2.0 Mini Video Edit](https://martllm.com/models/bytedance/seedance-2-0-mini-video-edit) | video | – | $0.075 / sec |
| [Seedance 2.0 Mini Video Edit Turbo](https://martllm.com/models/bytedance/seedance-2-0-mini-video-edit-turbo) | video | – | $0.095 / sec |
| [Seedance 2.0 Turbo (text-to-video)](https://martllm.com/models/bytedance/seedance-2-0-text-to-video-turbo) | video | – | $0.1333 / sec |
| [Seedance 2.0 Video Edit](https://martllm.com/models/bytedance/seedance-2-0-video-edit) | video | – | $0.15 / sec |
| [Seedance 2.0 Video Edit Turbo](https://martllm.com/models/bytedance/seedance-2-0-video-edit-turbo) | video | – | $0.17 / sec |
| [Seedance 2.5 Flash Spicy (image-to-video)](https://martllm.com/models/bytedance/seedance-2-5-flash-image-to-video-spicy) | video | – | $0.1142 / sec |
| [Seedance 2.5 Flash Turbo (image-to-video)](https://martllm.com/models/bytedance/seedance-2-5-flash-image-to-video-turbo) | video | – | $0.1333 / sec |
| [Seedance 2.5 Flash Turbo (text-to-video)](https://martllm.com/models/bytedance/seedance-2-5-flash-text-to-video-turbo) | video | – | $0.1333 / sec |
| [Seedance 2.5 Flash Video Edit Turbo](https://martllm.com/models/bytedance/seedance-2-5-flash-video-edit-turbo) | video | – | $0.17 / sec |
| [Seedance 2.5 Spicy (image-to-video)](https://martllm.com/models/bytedance/seedance-2-5-image-to-video-spicy) | video | – | $0.1714 / sec |
| [Seedance 2.5 Turbo (image-to-video)](https://martllm.com/models/bytedance/seedance-2-5-image-to-video-turbo) | video | – | $0.1904 / sec |
| [Seedance 2.5 Turbo (text-to-video)](https://martllm.com/models/bytedance/seedance-2-5-text-to-video-turbo) | video | – | $0.1904 / sec |
| [Seedance 2.5 Video Edit Turbo](https://martllm.com/models/bytedance/seedance-2-5-video-edit-turbo) | video | – | $0.24 / sec |
| [SeedVR2 Video Upscaler](https://martllm.com/models/bytedance/seedvr2-video-upscaler) | video | $0 / sec | $0 / sec |
| [ByteDance Lip Sync](https://martllm.com/models/bytedance/video-lip-sync) | video | – | $0.0448 / sec |
| [ByteDance Video Upscaler](https://martllm.com/models/bytedance/video-upscaler) | video | – | $0.0072 / sec |
| [daVinci-MagiHuman (image-to-video)](https://martllm.com/models/gair/davinci-magihuman-image-to-video) | video | $0 / sec | $0 / sec |
| [daVinci-MagiHuman (text-to-video)](https://martllm.com/models/gair/davinci-magihuman-text-to-video) | video | – | $0.03808 / sec |
| [Gemini Omni 1.2 Flash Video Edit](https://martllm.com/models/google/gemini-omni-flash-1-2-video-to-video) | video | – | $0.048 / sec |
| [Gemini Omni Flash Video Edit](https://martllm.com/models/google/gemini-omni-flash-video-to-video) | video | – | $0.15 / sec |
| [Veo3 Full (image-to-video)](https://martllm.com/models/google/veo3-full-image-to-video) | video | $0.22 / sec | $0.1904 / sec |
| [HeyGen Video 1.0 (image-to-video)](https://martllm.com/models/heygen/heygen-video-1-0-image-to-video) | video | – | $0.0238 / sec |
| [HeyGen Video 1.0 (reference-to-video)](https://martllm.com/models/heygen/heygen-video-1-0-reference-to-video) | video | – | $0.08092 / sec |
| [HeyGen Video 1.0 (text-to-video)](https://martllm.com/models/heygen/heygen-video-1-0-text-to-video) | video | – | $0.0238 / sec |
| [HiDream-E1 Full](https://martllm.com/models/hidream-ai/hidream-e1-full) | image | $0.024 / image | $0.02285 / image |
| [HiDream-I1 Dev](https://martllm.com/models/hidream-ai/hidream-i1-dev) | image | $0.012 / image | $0.01142 / image |
| [HiDream-I1 Full](https://martllm.com/models/hidream-ai/hidream-i1-full) | image | $0.024 / image | $0.02285 / image |
| [HiDream-O1-Image Dev Edit](https://martllm.com/models/hidream-ai/hidream-o1-image-dev-edit) | image | – | $0.02 / image |
| [HiDream-O1-Image Dev](https://martllm.com/models/hidream-ai/hidream-o1-image-dev-text-to-image) | image | $0.02 / image | $0.01904 / image |
| [HiDream-O1-Image Edit](https://martllm.com/models/hidream-ai/hidream-o1-image-edit) | image | – | $0.04 / image |
| [HiDream-O1-Image](https://martllm.com/models/hidream-ai/hidream-o1-image-text-to-image) | image | $0.04 / image | $0.03808 / image |
| [LingSante 3.1 Air VL](https://martllm.com/models/inclusionai/lingsante-3.1-air-vl) | text | $0.06 / $0.18 | $0.03465 / $0.104 |
| [Kling 1.6 Pro (image-to-video)](https://martllm.com/models/kling/kling-1-6-pro-image-to-video) | video | – | $0.08568 / sec |
| [Kling 1.6 Standard (image-to-video)](https://martllm.com/models/kling/kling-1-6-standard-image-to-video) | video | – | $0.0476 / sec |
| [Kling 1.6 Standard (text-to-video)](https://martllm.com/models/kling/kling-1-6-standard-text-to-video) | video | – | $0.04284 / sec |
| [Kling 2.0 Master (image-to-video)](https://martllm.com/models/kling/kling-2-0-master-image-to-video) | video | – | $0.2475 / sec |
| [Kling 2.0 Master (text-to-video)](https://martllm.com/models/kling/kling-2-0-master-text-to-video) | video | – | $0.2475 / sec |
| [Kling 2.1 Master (image-to-video)](https://martllm.com/models/kling/kling-2-1-master-image-to-video) | video | – | $0.2475 / sec |
| [Kling 2.1 Master (text-to-video)](https://martllm.com/models/kling/kling-2-1-master-text-to-video) | video | – | $0.2475 / sec |
| [Kling 2.5 Turbo Standard (image-to-video)](https://martllm.com/models/kling/kling-2-5-turbo-standard-image-to-video) | video | – | $0.03998 / sec |
| [Kling 2.6 Standard (image-to-video)](https://martllm.com/models/kling/kling-2-6-standard-image-to-video) | video | – | $0.03998 / sec |
| [Kling 2.6 Standard (text-to-video)](https://martllm.com/models/kling/kling-2-6-standard-text-to-video) | video | – | $0.03998 / sec |
| [Kling 3.0 Omni Transformation](https://martllm.com/models/kling/kling-3-0-omni-video-to-video) | video | – | $0.1271 / sec |
| [Kling AI Avatar Pro](https://martllm.com/models/kling/kling-ai-avatar-pro) | video | – | $0.1131 / sec |
| [Kling AI Avatar Standard](https://martllm.com/models/kling/kling-ai-avatar-standard) | video | – | $0.05656 / sec |
| [Kling Image O3 Text to Image](https://martllm.com/models/kling/kling-image-o3-text-to-image) | image | $0.028 / image | $0.02666 / image |
| [Kling Image V3 Text to Image](https://martllm.com/models/kling/kling-image-v3-text-to-image) | image | $0.028 / image | $0.02666 / image |
| [Kling O3 4K Video Reference](https://martllm.com/models/kling/kling-o3-4k-video-reference) | video | $0 / sec | $0 / sec |
| [Kling V3 4K Image-to-Video](https://martllm.com/models/kling/kling-v3-4k-image-to-video) | video | – | $0.3998 / sec |
| [Kling V3 Turbo Pro (text-to-video)](https://martllm.com/models/kling/kling-v3-turbo-pro-text-to-video) | video | – | $0.1215 / sec |
| [Kling O1 Standard Video Edit](https://martllm.com/models/kling/kling-video-o1-std-video-edit) | video | – | $0.126 / sec |
| [Kling O1 Video Edit](https://martllm.com/models/kling/kling-video-o1-video-edit) | video | – | $0.168 / sec |
| [Kling O1 Video Edit Fast](https://martllm.com/models/kling/kling-video-o1-video-edit-fast) | video | – | $0.09 / sec |
| [Kling O3 4K Video Edit](https://martllm.com/models/kling/kling-video-o3-4k-video-edit) | video | – | $0.462 / sec |
| [Kling O3 Pro Video Edit](https://martllm.com/models/kling/kling-video-o3-pro-video-edit) | video | – | $0.168 / sec |
| [Kling O3 Standard Video Edit](https://martllm.com/models/kling/kling-video-o3-std-video-edit) | video | – | $0.126 / sec |
| [LTX-2 19B Control (pose)](https://martllm.com/models/lightricks/ltx-2-19b-control) | video | $0 / sec | $0 / sec |
| [LTX 2 19B Video Upscaler](https://martllm.com/models/lightricks/ltx-2-19b-video-upscaler) | video | – | $0.02 / sec |
| [LTX 2.3 (image-to-video)](https://martllm.com/models/lightricks/ltx-2-3-image-to-video) | video | – | $0.01904 / sec |
| [LTX 2.3 Spicy (image-to-video)](https://martllm.com/models/lightricks/ltx-2-3-image-to-video-spicy) | video | – | $0.01904 / sec |
| [LTX 2.5 Fast Audio to Video](https://martllm.com/models/lightricks/ltx-2-5-fast-audio-to-video) | video | – | $0.06048 / sec |
| [LTX 2.5 (image-to-video)](https://martllm.com/models/lightricks/ltx-2-5-image-to-video) | video | – | $0.0952 / sec |
| [LTX 2.5 (text-to-video)](https://martllm.com/models/lightricks/ltx-2-5-text-to-video) | video | – | $0.0952 / sec |
| [LTX-2 Pro (image-to-video)](https://martllm.com/models/lightricks/ltx-2-pro-image-to-video) | video | $0 / sec | $0 / sec |
| [LTX-2 Pro (text-to-video)](https://martllm.com/models/lightricks/ltx-2-pro-text-to-video) | video | $0 / sec | $0 / sec |
| [LTX-2 Retake](https://martllm.com/models/lightricks/ltx-2-retake) | video | $0 / sec | $0 / sec |
| [Photon Flash Modify](https://martllm.com/models/luma/photon-flash-modify) | image | $0.01 / image | $0.00952 / image |
| [Photon Modify](https://martllm.com/models/luma/photon-modify) | image | $0.015 / image | $0.01428 / image |
| [Luma Ray 1.6 (image-to-video)](https://martllm.com/models/luma/ray-1-6-image-to-video) | video | $0 / sec | $0 / sec |
| [Luma Ray 1.6 (text-to-video)](https://martllm.com/models/luma/ray-1-6-text-to-video) | video | – | $0.05712 / sec |
| [Luma Ray 2 Flash (image-to-video)](https://martllm.com/models/luma/ray-2-flash-image-to-video) | video | – | $0.03808 / sec |
| [Luma Ray 2 Flash (text-to-video)](https://martllm.com/models/luma/ray-2-flash-text-to-video) | video | – | $0.03808 / sec |
| [Luma Ray 2 (image-to-video)](https://martllm.com/models/luma/ray-2-image-to-video) | video | – | $0.07616 / sec |
| [Luma Ray 2 (text-to-video)](https://martllm.com/models/luma/ray-2-text-to-video) | video | – | $0.07616 / sec |
| [Luma Ray 3.2 (image-to-video)](https://martllm.com/models/luma/ray-3-2-image-to-video) | video | – | $0.0952 / sec |
| [Luma Ray 3.2 (text-to-video)](https://martllm.com/models/luma/ray-3-2-text-to-video) | video | – | $0.0952 / sec |
| [Ray 3.2 Video Edit](https://martllm.com/models/luma/ray-3-2-video-edit) | video | – | $0.144 / sec |
| [Luma Ray 3.2 Reframe](https://martllm.com/models/luma/ray-3-2-video-reframing) | video | $0 / sec | $0 / sec |
| [MiniMax H3 Image Highspeed](https://martllm.com/models/minimax/h3-image-highspeed-text-to-image) | image | $0.042 / image | $0.03998 / image |
| [Hailuo 02 Fast (image-to-video)](https://martllm.com/models/minimax/hailuo-02-fast-image-to-video) | video | $0 / sec | $0 / sec |
| [Hailuo 2.3 Pro (text-to-video)](https://martllm.com/models/minimax/hailuo-2-3-pro-text-to-video) | video | – | $0.0933 / sec |
| [Hailuo 2.3 Standard (text-to-video)](https://martllm.com/models/minimax/hailuo-2-3-standard-text-to-video) | video | $0 / sec | $0 / sec |
| [MiniMax Image-01](https://martllm.com/models/minimax/image-01-text-to-image) | image | – | $0.003332 / image |
| [MiniMax H3 Highspeed (image-to-video)](https://martllm.com/models/minimax/minimax-h3-highspeed-image-to-video) | video | – | $0.05712 / sec |
| [MiniMax H3 Highspeed (reference-to-video)](https://martllm.com/models/minimax/minimax-h3-highspeed-reference-to-video) | video | – | $0.05712 / sec |
| [MiniMax H3 Highspeed (text-to-video)](https://martllm.com/models/minimax/minimax-h3-highspeed-text-to-video) | video | – | $0.05712 / sec |
| [MiniMax H3 Spicy (image-to-video)](https://martllm.com/models/minimax/minimax-h3-image-to-video-spicy) | video | – | $0.03808 / sec |
| [MiniMax H3 Lite (image-to-video)](https://martllm.com/models/minimax/minimax-h3-lite-image-to-video) | video | – | $0.0238 / sec |
| [MiniMax H3 Lite (reference-to-video)](https://martllm.com/models/minimax/minimax-h3-lite-reference-to-video) | video | – | $0.0238 / sec |
| [MiniMax H3 Lite (text-to-video)](https://martllm.com/models/minimax/minimax-h3-lite-text-to-video) | video | – | $0.0238 / sec |
| [MiniMax H3 Singularity (image-to-video)](https://martllm.com/models/minimax/minimax-h3-singularity-image-to-video) | video | – | $0.0476 / sec |
| [MiniMax H3 Singularity (reference-to-video)](https://martllm.com/models/minimax/minimax-h3-singularity-reference-to-video) | video | – | $0.05141 / sec |
| [MiniMax H3 Video Edit](https://martllm.com/models/minimax/minimax-h3-video-edit) | video | – | $0.10 / sec |
| [MiniMax Video 02](https://martllm.com/models/minimax/minimax-video-02) | video | $0 / sec | $0 / sec |
| [MiniMax H3 Chili R2V](https://martllm.com/models/minimax/venice-minimax-h3-chili-reference-to-video) | video | – | $0.01725 / sec |
| [MiniMax H3 R2V Enhanced](https://martllm.com/models/minimax/venice-minimax-h3-enhanced-reference-to-video) | video | – | $0.0784 / sec |
| [MiniMax H3 Hyper R2V](https://martllm.com/models/minimax/venice-minimax-h3-hyper-reference-to-video) | video | – | $0.01725 / sec |
| [MiniMax H3 Max R2V](https://martllm.com/models/minimax/venice-minimax-h3-max-reference-to-video) | video | – | $0.04704 / sec |
| [Kimi K2 0905](https://martllm.com/models/moonshotai/kimi-k2-0905) | text | $0.60 / $2.50 | $0.3465 / $1.44 |
| [Neta Lumina](https://martllm.com/models/neta-art/neta-lumina) | image | $0.01 / image | $0.00952 / image |
| [Cosmos 3 Super (image-to-video)](https://martllm.com/models/nvidia/cosmos-3-super-image-to-video) | video | – | $0.0476 / sec |
| [Sora 2 (image-to-video)](https://martllm.com/models/openai/sora-2-image-to-video) | video | $0.11 / sec | $0.05867 / sec |
| [Sora 2 Pro (image-to-video)](https://martllm.com/models/openai/sora-2-pro-image-to-video) | video | $0.33 / sec | $0.176 / sec |
| [Sora 2 Pro (text-to-video)](https://martllm.com/models/openai/sora-2-pro-text-to-video) | video | $0 / sec | $0 / sec |
| [Sora 2 (text-to-video)](https://martllm.com/models/openai/sora-2-text-to-video) | video | $0 / sec | $0 / sec |
| [FlashVSR Video Upscaler](https://martllm.com/models/openimaginglab/flashvsr) | video | $0 / sec | $0 / sec |
| [MOSS Image](https://martllm.com/models/openmoss/moss-image-text-to-image) | image | $0.02 / image | $0.01904 / image |
| [Ovi Text-to-Video](https://martllm.com/models/ovi/ovi-text-to-video) | video | – | $0.02856 / sec |
| [Pika 2.0 Turbo (image-to-video)](https://martllm.com/models/pika/pika-2-0-turbo-image-to-video) | video | – | $0.03808 / sec |
| [Pika 2.0 Turbo (text-to-video)](https://martllm.com/models/pika/pika-2-0-turbo-text-to-video) | video | – | $0.03808 / sec |
| [Pika 2.1 (image-to-video)](https://martllm.com/models/pika/pika-2-1-image-to-video) | video | – | $0.03808 / sec |
| [Pika 2.1 (text-to-video)](https://martllm.com/models/pika/pika-2-1-text-to-video) | video | – | $0.03808 / sec |
| [Pika 2.2 (image-to-video)](https://martllm.com/models/pika/pika-2-2-image-to-video) | video | – | $0.03808 / sec |
| [Pika 2.2 (text-to-video)](https://martllm.com/models/pika/pika-2-2-text-to-video) | video | – | $0.03808 / sec |
| [PixVerse V4.5 Fast (image-to-video)](https://martllm.com/models/pixverse/pixverse-v4-5-fast-image-to-video) | video | – | $0.0952 / sec |
| [PixVerse V4.5 Fast (text-to-video)](https://martllm.com/models/pixverse/pixverse-v4-5-fast-text-to-video) | video | – | $0.0952 / sec |
| [PixVerse V4.5 (image-to-video)](https://martllm.com/models/pixverse/pixverse-v4-5-image-to-video) | video | – | $0.0476 / sec |
| [PixVerse V4.5 (text-to-video)](https://martllm.com/models/pixverse/pixverse-v4-5-text-to-video) | video | – | $0.0476 / sec |
| [PixVerse V5.5 (image-to-video)](https://martllm.com/models/pixverse/pixverse-v5-5-image-to-video) | video | – | $0.08568 / sec |
| [PixVerse V5.5 (text-to-video)](https://martllm.com/models/pixverse/pixverse-v5-5-text-to-video) | video | – | $0.08568 / sec |
| [PixVerse V5 (image-to-video)](https://martllm.com/models/pixverse/pixverse-v5-image-to-video) | video | – | $0.04284 / sec |
| [PixVerse V5 (text-to-video)](https://martllm.com/models/pixverse/pixverse-v5-text-to-video) | video | – | $0.04284 / sec |
| [PixVerse V6 Transition](https://martllm.com/models/pixverse/pixverse-v6-transition) | video | – | $0.0238 / sec |
| [P-H3-Image Edit](https://martllm.com/models/pruna-ai/p-h3-image-edit) | image | $0.03 / image | $0.02856 / image |
| [P-H3-Image](https://martllm.com/models/pruna-ai/p-h3-image-text-to-image) | image | $0.02 / image | $0.01904 / image |
| [P-Image Ideogram](https://martllm.com/models/pruna-ai/p-image-ideogram) | image | $0.015 / image | $0.01428 / image |
| [P-Image](https://martllm.com/models/pruna-ai/p-image-text-to-image) | image | $0.005 / image | $0.00476 / image |
| [P-Video Edit](https://martllm.com/models/pruna-ai/p-video-edit) | video | – | $0.045 / sec |
| [Pruna P-Video 2 (image-to-video)](https://martllm.com/models/pruna/p-video-2-image-to-video) | video | – | $0.0238 / sec |
| [Pruna P-Video 2 Pro (image-to-video)](https://martllm.com/models/pruna/p-video-2-pro-image-to-video) | video | – | $0.01904 / sec |
| [Pruna P-Video 2 Pro (reference-to-video)](https://martllm.com/models/pruna/p-video-2-pro-reference-to-video) | video | – | $0.02094 / sec |
| [Pruna P-Video 2 Pro (text-to-video)](https://martllm.com/models/pruna/p-video-2-pro-text-to-video) | video | – | $0.01904 / sec |
| [Pruna P-Video 2 (text-to-video)](https://martllm.com/models/pruna/p-video-2-text-to-video) | video | – | $0.0238 / sec |
| [Pruna P-Video (image-to-video)](https://martllm.com/models/pruna/p-video-image-to-video) | video | – | $0.01904 / sec |
| [Pruna P-Video (text-to-video)](https://martllm.com/models/pruna/p-video-text-to-video) | video | – | $0.01904 / sec |
| [Qwen Image Max](https://martllm.com/models/qwen/qwen-image-max-text-to-image) | image | $0.07 / image | $0.06664 / image |
| [Recraft V4.1 Flash V2](https://martllm.com/models/recraft/recraft-v4-1-flash-v2) | image | $0.007 / image | $0.002352 / image |
| [Runway Gen-4.5 (image-to-video)](https://martllm.com/models/runway/runway-gen4-5-image-to-video) | video | – | $0.1281 / sec |
| [Runway Upscale V1](https://martllm.com/models/runway/upscale-v1) | video | – | $0.022 / sec |
| [Riverflow 2.0 Pro](https://martllm.com/models/sourceful/riverflow-2-0-pro-text-to-image) | image | $0.15 / image | $0.1428 / image |
| [Riverflow V2.5 Fast](https://martllm.com/models/sourceful/riverflow-v2-5-fast) | image | – | $0.0117 / image |
| [Riverflow V2.5 Pro](https://martllm.com/models/sourceful/riverflow-v2-5-pro) | image | – | $0.08008 / image |
| [Riverflow V2.6 Pro](https://martllm.com/models/sourceful/riverflow-v2-6-pro) | image | – | $0.08008 / image |
| [Riverflow V2 Fast](https://martllm.com/models/sourceful/riverflow-v2-fast) | image | – | $0.01232 / image |
| [Stable Diffusion](https://martllm.com/models/stability-ai/stable-diffusion) | image | $0.02 / image | $0.01792 / image |
| [Stable Diffusion 3](https://martllm.com/models/stability-ai/stable-diffusion-3) | image | $0.14 / image | $0.1254 / image |
| [Stable Diffusion 3.5 Large](https://martllm.com/models/stability-ai/stable-diffusion-3-5-large) | image | $0.26 / image | $0.233 / image |
| [Stable Diffusion 3.5 Large Turbo](https://martllm.com/models/stability-ai/stable-diffusion-3-5-large-turbo) | image | $0.16 / image | $0.1434 / image |
| [Stable Diffusion 3.5 Medium](https://martllm.com/models/stability-ai/stable-diffusion-3-5-medium) | image | $0.14 / image | $0.1254 / image |
| [Step1X-Edit](https://martllm.com/models/stepfun/step1x-edit) | image | $0.03 / image | $0.02856 / image |
| [Hunyuan Image 3.0 Instruct](https://martllm.com/models/tencent/hunyuan-image-3-instruct-text-to-image) | image | – | $0.4284 / image |
| [Hunyuan Video 1.5 (image-to-video)](https://martllm.com/models/tencent/hunyuan-video-1-5-image-to-video) | video | – | $0.01904 / sec |
| [Hunyuan Video 1.5 (text-to-video)](https://martllm.com/models/tencent/hunyuan-video-1-5-text-to-video) | video | – | $0.01904 / sec |
| [Hunyuan Video (image-to-video)](https://martllm.com/models/tencent/hunyuan-video-image-to-video) | video | – | $0.07616 / sec |
| [InstantCharacter](https://martllm.com/models/tencent/instant-character) | image | – | $0.30 / image |
| [Z-Image Base](https://martllm.com/models/tongyi-mai/z-image-base) | image | $0.01 / image | $0.00952 / image |
| [Z-Image Turbo Image to Image](https://martllm.com/models/tongyi-mai/z-image-turbo-image-to-image) | image | – | $0.005 / image |
| [Topaz Video Astra](https://martllm.com/models/topaz-labs/topaz-video-astra) | video | $0 / video | $0 / video |
| [Topaz Video Denoise](https://martllm.com/models/topaz-labs/topaz-video-denoise) | video | $0 / video | $0 / video |
| [Topaz Video Precision](https://martllm.com/models/topaz-labs/topaz-video-precision) | video | $0 / video | $0 / video |
| [Topaz Video Starlight](https://martllm.com/models/topaz-labs/topaz-video-starlight) | video | $0 / video | $0 / video |
| [Topaz Video Starlight Fast](https://martllm.com/models/topaz-labs/topaz-video-starlight-fast) | video | $0 / video | $0 / video |
| [Vidu 2.0 (reference-to-video)](https://martllm.com/models/vidu/vidu-2-0-reference-to-video) | video | $0 / sec | $0 / sec |
| [Vidu 2.0 (text-to-video)](https://martllm.com/models/vidu/vidu-2-0-text-to-video) | video | – | $0.05712 / sec |
| [Vidu Q1 (reference-to-video)](https://martllm.com/models/vidu/vidu-q1-reference-to-video) | video | – | $0.07616 / sec |
| [Vidu Q1 (text-to-video)](https://martllm.com/models/vidu/vidu-q1-text-to-video) | video | – | $0.07616 / sec |
| [Vidu Q2 Pro Fast (image-to-video)](https://martllm.com/models/vidu/vidu-q2-pro-fast-image-to-video) | video | – | $0.01523 / sec |
| [Vidu Q2 Pro (image-to-video)](https://martllm.com/models/vidu/vidu-q2-pro-image-to-video) | video | – | $0.0238 / sec |
| [Vidu Q2 (reference-to-video)](https://martllm.com/models/vidu/vidu-q2-reference-to-video) | video | – | $0.03332 / sec |
| [Vidu Q2 (text-to-video)](https://martllm.com/models/vidu/vidu-q2-text-to-video) | video | – | $0.01714 / sec |
| [Vidu Q2 Turbo (image-to-video)](https://martllm.com/models/vidu/vidu-q2-turbo-image-to-video) | video | – | $0.01333 / sec |
| [Vidu Q3 Ad](https://martllm.com/models/vidu/vidu-q3-ad) | video | – | $0.1428 / sec |
| [Vidu Q3 (image-to-video, Pro sizes)](https://martllm.com/models/vidu/vidu-q3-image-to-video-pro) | video | – | $0.08568 / sec |
| [Vidu Q3 Spicy (image-to-video)](https://martllm.com/models/vidu/vidu-q3-image-to-video-spicy) | video | – | $0.06664 / sec |
| [Vidu Q3 (reference-to-video)](https://martllm.com/models/vidu/vidu-q3-reference-to-video) | video | – | $0.08087 / sec |
| [Wan 2.1 (image-to-video)](https://martllm.com/models/wan/wan-2-1-image-to-video) | video | $0 / sec | $0 / sec |
| [Wan 2.1 Synthetic to Real](https://martllm.com/models/wan/wan-2-1-synthetic-to-real) | video | $0 / sec | $0 / sec |
| [Wan 2.1 (text-to-video)](https://martllm.com/models/wan/wan-2-1-text-to-video) | video | – | $0.0238 / sec |
| [Wan 2.1 Video-to-Video](https://martllm.com/models/wan/wan-2-1-video-to-video) | video | – | $0.04 / sec |
| [Wan 2.2 A14B Image-to-Video](https://martllm.com/models/wan/wan-2-2-a14b-image-to-video) | video | – | $0.00952 / sec |
| [Wan 2.2 Spicy (image-to-video)](https://martllm.com/models/wan/wan-2-2-image-to-video-spicy) | video | – | $0.02856 / sec |
| [Wan 2.2 Video Edit](https://martllm.com/models/wan/wan-2-2-video-edit) | video | – | $0.04 / sec |
| [Wan 2.5 Fast (image-to-video)](https://martllm.com/models/wan/wan-2-5-fast-image-to-video) | video | – | $0.06474 / sec |
| [Wan 2.5 Fast (text-to-video)](https://martllm.com/models/wan/wan-2-5-fast-text-to-video) | video | – | $0.06474 / sec |
| [Wan 2.5 Text to Image](https://martllm.com/models/wan/wan-2-5-text-to-image) | image | $0.03 / image | $0.02856 / image |
| [Wan 2.6 Flash (reference-to-video)](https://martllm.com/models/wan/wan-2-6-flash-reference-to-video) | video | – | $0.0476 / sec |
| [Wan 2.6 Pro (image-to-video)](https://martllm.com/models/wan/wan-2-6-image-to-video-pro) | video | – | $0.1333 / sec |
| [Wan 2.6 Spicy (image-to-video)](https://martllm.com/models/wan/wan-2-6-image-to-video-spicy) | video | – | $0.0952 / sec |
| [Wan 2.6 (reference-to-video)](https://martllm.com/models/wan/wan-2-6-reference-to-video) | video | – | $0.08491 / sec |
| [Wan 2.6 Text to Image](https://martllm.com/models/wan/wan-2-6-text-to-image) | image | $0.03 / image | $0.02856 / image |
| [Wan 2.7 Spicy (image-to-video)](https://martllm.com/models/wan/wan-2-7-image-to-video-spicy) | video | – | $0.0952 / sec |
| [Wan 3.0 Spicy (image-to-video)](https://martllm.com/models/wan/wan-3-0-image-to-video-spicy) | video | – | $0.0476 / sec |
| [Wan 3.0 Prime Spicy (image-to-video)](https://martllm.com/models/wan/wan-3-0-prime-image-to-video-spicy) | video | – | $0.0714 / sec |
| [Wan 3.0 Prime Video Edit](https://martllm.com/models/wan/wan-3-0-prime-video-edit) | video | – | $0.15 / sec |
| [Wan 3.0 Video Edit](https://martllm.com/models/wan/wan-3-0-video-edit) | video | – | $0.10 / sec |
| [Grok Imagine Video 1.5 (reference-to-video)](https://martllm.com/models/x-ai/grok-imagine-1-5-reference-to-video) | video | – | $0.0737 / sec |
| [Grok Imagine (reference-to-video)](https://martllm.com/models/x-ai/grok-imagine-reference-to-video) | video | $0 / sec | $0 / sec |
| [Grok Imagine Video Edit](https://martllm.com/models/x-ai/grok-imagine-video-edit-video) | video | – | $0.065 / sec |
| [GLM-Image](https://martllm.com/models/z-ai/glm-image-text-to-image) | image | $0.12 / image | $0.1142 / image |

**No longer listed (18)**: `lightricks/ltx-2-3-fast-image-to-video`, `lightricks/ltx-2-3-fast-text-to-video`, `google/gemini-2.5-pro`, `google/gemini-omni-1.2-flash`, `lightricks/ltx-2-5-fast`, `lightricks/ltx-2-5-pro`, `lightricks/ltx-2-full-text-to-video`, `nvidia/cosmos-predict-image-to-video`, `openai/gpt-4o-fast`, `openai/gpt-image-1-5-high`, `openai/gpt-image-1-5-medium`, `openai/gpt-transcribe`, `runway/runway-gen4-aleph`, `tencent/hy4-preview`, `venice/runway-gen4-5-text`, `venice/video-gen`, `wan/wan-2-1-pro-image-to-video`, `wan/wan-2-6-ultra-image-to-video`

<details><summary>MartLLM price moves of 10% or more (354)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Palmyra Vision 7B](https://martllm.com/models/writer/palmyra-vision-7b) | text | $0.03308 / $0.1323 | $0.00315 / $0.0126 | −90% |
| [GPT Image 2.5 Sunburst (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-sunburst-edit) | image | $0.0315 / image | $0.0056 / image | −82% |
| [Grok Imagine Text-to-Video](https://martllm.com/models/x-ai/grok-imagine-text-to-video) | video | $0.07087 / sec | $0.01344 / sec | −81% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | text | $0.021 / $0.21 | $0.0042 / $0.042 | −80% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | text | $0.008978 / $0.01795 | $0.002363 / $0.004725 | −74% |
| [GPT Image 2.5 Flare (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-flare-edit) | image | $0.0315 / image | $0.008592 / image | −73% |
| [Ideogram V4.5 (image-to-image)](https://martllm.com/models/ideogram/ideogram-v4-5-edit) | image | $0.2047 / image | $0.05712 / image | −72% |
| [GPT OSS Safeguard 120B](https://martllm.com/models/openai/gpt-oss-safeguard-120b) | text | $0.03938 / $0.1575 | $0.01103 / $0.0441 | −72% |
| [Recraft V4.1 Pro Text To Image](https://martllm.com/models/recraft/recraft-v4-1-pro-text-to-image) | image | $0.25 / image | $0.07056 / image | −72% |
| [Muse Image](https://martllm.com/models/meta-llama/venice-muse-image) | image | $0.0168 / image | $0.004852 / image | −71% |
| [Recraft V4.1 Utility Pro](https://martllm.com/models/recraft/recraft-v4-1-utility-pro) | image | $0.238 / image | $0.07056 / image | −70% |
| [Recraft V4.1](https://martllm.com/models/recraft/recraft-v4-1) | image | $0.03808 / image | $0.01176 / image | −69% |
| [Recraft V4.1 Flash](https://martllm.com/models/recraft/recraft-v4-1-flash) | image | $0.007616 / image | $0.002352 / image | −69% |
| [Recraft V4.1 Utility](https://martllm.com/models/recraft/recraft-v4-1-utility) | image | $0.03733 / image | $0.01176 / image | −69% |
| [Recraft V2](https://martllm.com/models/recraft/recraft-v2) | image | $0.02347 / image | $0.007392 / image | −69% |
| [Mistral: Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4-0) | text | $0.301 / $0.9029 | $0.1003 / $0.301 | −67% |
| [GPT Image 1.5 — Edit (Venice)](https://martllm.com/models/venice/gpt-image-1-5-edit) | image | $0.2604 / image | $0.0952 / image | −63% |
| [Krea 3](https://martllm.com/models/krea/krea-3) | image | $0.07333 / image | $0.02856 / image | −61% |
| [Flux 3 (image-to-image)](https://martllm.com/models/black-forest-labs/flux-3-image-edit) | image | $0.1134 / image | $0.0457 / image | −60% |
| [Seedance 1.5 Pro Text-to-Video](https://martllm.com/models/bytedance/seedance-1-5-pro-text-to-video) | video | $0.0609 / sec | $0.02475 / sec | −59% |
| [Veo 3 Full Text-to-Video](https://martllm.com/models/google/veo3-full-text-to-video) | video | $0.462 / sec | $0.1904 / sec | −59% |
| [Meta: Muse Spark 1.3](https://martllm.com/models/meta-llama/muse-spark-1.3) | text | $1.06 / $3.61 | $0.4725 / $1.61 | −56% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | text | $0.105 / $0.21 | $0.0483 / $0.0966 | −54% |
| [PixVerse V5.6 Text-to-Video](https://martllm.com/models/pixverse/pixverse-v5-6-text-to-video) | video | $0.1795 / sec | $0.0833 / sec | −54% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | text | $0.7122 / $2.24 | $0.3491 / $1.10 | −51% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | text | $0.01706 / $0.05119 | $0.008531 / $0.02559 | −50% |
| [Flux 2 Max — Edit (Venice)](https://martllm.com/models/black-forest-labs/flux-2-max-edit) | image | $0.1077 / image | $0.05661 / image | −47% |
| [MiniMax M2](https://martllm.com/models/minimax/minimax-m2) | text | $0.04725 / $0.189 | $0.0252 / $0.1008 | −47% |
| [LTX 2 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-fast-text-to-video) | video | $0.07 / sec | $0.03808 / sec | −46% |
| [Veo 3 Fast Text-to-Video](https://martllm.com/models/google/veo3-fast-text-to-video) | video | $0.1732 / sec | $0.0952 / sec | −45% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | text | $0.02205 / $0.02205 | $0.01213 / $0.01213 | −45% |
| [Kling V3 Pro Text-to-Video](https://martllm.com/models/kling/kling-v3-pro-text-to-video) | video | $0.1739 / sec | $0.09722 / sec | −44% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | text | $0.0105 / $0.021 | $0.00588 / $0.01176 | −44% |
| [Kling V3 Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-pro-image-to-video) | video | $0.1732 / sec | $0.09722 / sec | −44% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | music | $0.002061 / sec | $0.001159 / sec | −44% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | text | $0.01066 / $0.03675 | $0.00609 / $0.021 | −43% |
| [MAI Image 2.7](https://martllm.com/models/microsoft/mai-image-2-7) | image | $0.06664 / image | $0.0392 / image | −41% |
| [Parakeet ASR (Venice)](https://martllm.com/models/venice/parakeet-asr) | transcription | $0.005107 / minute | $0.003024 / minute | −41% |
| [MiniMax M2.7 Highspeed](https://martllm.com/models/minimax/minimax-m2.7-highspeed) | text | $0.315 / $1.26 | $0.189 / $0.756 | −40% |
| [Qwen Image 2 Pro (Venice)](https://martllm.com/models/venice/qwen-image-2-pro) | image | $0.084 / image | $0.05054 / image | −40% |
| [GLM-4.6](https://martllm.com/models/z-ai/glm-4.6) | text | $0.2122 / $0.8636 | $0.1309 / $0.5329 | −38% |
| [Muse Image (image-to-image)](https://martllm.com/models/meta-llama/muse-image-edit) | image | $0.0168 / image | $0.01047 / image | −38% |
| [PixVerse C1 Text-to-Video (Venice)](https://martllm.com/models/venice/pixverse-c1-t2v) | video | $0.04158 / sec | $0.02613 / sec | −37% |
| [Krea v2 Large (Venice)](https://martllm.com/models/krea/venice-krea-v2-large) | image | $0.0588 / image | $0.03696 / image | −37% |
| [Pixverse C1 (image-to-video)](https://martllm.com/models/pixverse/pixverse-c1-image-to-video) | video | $0.04092 / sec | $0.02613 / sec | −36% |
| [Pixverse C1 (reference-to-video)](https://martllm.com/models/pixverse/pixverse-c1-reference-to-video) | video | $0.04092 / sec | $0.02613 / sec | −36% |
| [Pixverse C1 Transition (transition)](https://martllm.com/models/pixverse/pixverse-c1-transition) | video | $0.04092 / sec | $0.02613 / sec | −36% |
| [Runway Gen-4.5](https://martllm.com/models/runway/runway-gen4-5) | video | $0.168 / sec | $0.1075 / sec | −36% |
| [MAI Image 2.7 Flash](https://martllm.com/models/microsoft/mai-image-2-7-flash) | image | $0.0238 / image | $0.01568 / image | −34% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | text | $0.1158 / $0.3473 | $0.07717 / $0.2315 | −33% |
| [Wan 2.2 A14B Text-to-Video](https://martllm.com/models/wan/wan-2-2-a14b-text-to-video) | video | $0.042 / sec | $0.02856 / sec | −32% |
| [Command R7B (12-2024)](https://martllm.com/models/cohere/command-r7b-12-2024) | text | $0.0315 / $0.126 | $0.02166 / $0.08662 | −31% |
| [DaisyRose 27B](https://martllm.com/models/radixark/daisyrose-27b) | text | $0.126 / $1.57 | $0.08662 / $1.08 | −31% |
| [DeepSeek V3](https://martllm.com/models/deepseek/deepseek-chat) | text | $0.2162 / $0.8641 | $0.1486 / $0.5941 | −31% |
| [Aion-RP 1.0 (8B)](https://martllm.com/models/aion-labs/aion-rp-llama-3.1-8b) | text | $0.672 / $1.34 | $0.462 / $0.924 | −31% |
| [Nova 2 Lite](https://martllm.com/models/amazon/nova-2-lite-v1) | text | $0.252 / $2.10 | $0.1732 / $1.44 | −31% |
| [Nova Lite 1.0](https://martllm.com/models/amazon/nova-lite-v1) | text | $0.0504 / $0.2016 | $0.03465 / $0.1386 | −31% |
| [Nova Premier 1.0](https://martllm.com/models/amazon/nova-premier-v1) | text | $2.10 / $10.50 | $1.44 / $7.22 | −31% |
| [Nova Pro 1.0](https://martllm.com/models/amazon/nova-pro-v1) | text | $0.672 / $2.69 | $0.462 / $1.85 | −31% |
| [Magnum v4 72B](https://martllm.com/models/anthracite-org/magnum-v4-72b) | text | $2.10 / $4.20 | $1.44 / $2.89 | −31% |
| [Claude Haiku 5.5 (batch)](https://martllm.com/models/anthropic/claude-haiku-5.5:batch) | text | $0.042 / $0.21 | $0.02888 / $0.1444 | −31% |
| [Claude Opus 4.1](https://martllm.com/models/anthropic/claude-opus-4.1) | text | $12.60 / $63.00 | $8.66 / $43.31 | −31% |
| [ERNIE-Light-DT-1.0](https://martllm.com/models/baidu/ernie-light-dt-1.0-intl) | text | $0.9492 / $3.31 | $0.6526 / $2.28 | −31% |
| [Seed-2.0-Lite](https://martllm.com/models/bytedance-seed/seed-2.0-lite) | text | $0.21 / $1.68 | $0.1444 / $1.16 | −31% |
| [Seed-2.0-Mini](https://martllm.com/models/bytedance-seed/seed-2.0-mini) | text | $0.084 / $0.336 | $0.05775 / $0.231 | −31% |
| [UI-TARS 7B](https://martllm.com/models/bytedance/ui-tars-1.5-7b) | text | $0.084 / $0.168 | $0.05775 / $0.1155 | −31% |
| [Command A](https://martllm.com/models/cohere/command-a) | text | $2.10 / $8.40 | $1.44 / $5.78 | −31% |
| [Command R (08-2024)](https://martllm.com/models/cohere/command-r-08-2024) | text | $0.126 / $0.504 | $0.08662 / $0.3465 | −31% |
| [Command R+ (08-2024)](https://martllm.com/models/cohere/command-r-plus-08-2024) | text | $2.10 / $8.40 | $1.44 / $5.78 | −31% |
| [DeepSeek V3 0324](https://martllm.com/models/deepseek/deepseek-chat-v3-0324) | text | $0.21 / $0.84 | $0.1444 / $0.5775 | −31% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-chat-v3.1) | text | $0.21 / $0.798 | $0.1444 / $0.5486 | −31% |
| [DeepSeek V3.1 Terminus](https://martllm.com/models/deepseek/deepseek-v3.1-terminus) | text | $0.2268 / $0.84 | $0.1559 / $0.5775 | −31% |
| [DeepSeek V3.2 Exp](https://martllm.com/models/deepseek/deepseek-v3.2-exp) | text | $0.2268 / $0.3444 | $0.1559 / $0.2368 | −31% |
| [Gemini 2.5 Flash](https://martllm.com/models/google/gemini-2.5-flash) | text | $0.252 / $2.10 | $0.1732 / $1.44 | −31% |
| [Gemini 2.5 Flash Lite](https://martllm.com/models/google/gemini-2.5-flash-lite) | text | $0.084 / $0.336 | $0.05775 / $0.231 | −31% |
| [Gemini 2.5 Pro Preview 06-05](https://martllm.com/models/google/gemini-2.5-pro-preview) | text | $1.05 / $8.40 | $0.7219 / $5.78 | −31% |
| [Nano Banana Pro (Gemini 3 Pro Image)](https://martllm.com/models/google/gemini-3-pro-image) | text | $1.68 / $10.08 | $1.16 / $6.93 | −31% |
| [Nano Banana Pro (Gemini 3 Pro Image Preview)](https://martllm.com/models/google/gemini-3-pro-image-preview) | text | $1.68 / $10.08 | $1.16 / $6.93 | −31% |
| [Gemini 3.1 Flash Image (Nano Banana 2)](https://martllm.com/models/google/gemini-3.1-flash-image) | text | $0.42 / $2.52 | $0.2888 / $1.73 | −31% |
| [Nano Banana 2 (Gemini 3.1 Flash Image Preview)](https://martllm.com/models/google/gemini-3.1-flash-image-preview) | text | $0.42 / $2.52 | $0.2888 / $1.73 | −31% |
| [Gemini 3.1 Flash Lite Image (Nano Banana 2 Lite)](https://martllm.com/models/google/gemini-3.1-flash-lite-image) | text | $0.21 / $1.26 | $0.1444 / $0.8662 | −31% |
| [Gemini 3.1 Pro Preview Custom Tools](https://martllm.com/models/google/gemini-3.1-pro-preview-customtools) | text | $1.68 / $10.08 | $1.16 / $6.93 | −31% |
| [Gemini Nano Banana 2.1](https://martllm.com/models/google/gemini-nano-banana-2.1) | text | $1.26 / $6.30 | $0.8662 / $4.33 | −31% |
| [Gemini Omni 1.1 Flash](https://martllm.com/models/google/gemini-omni-1.1-flash) | text | $1.26 / $7.56 | $0.8662 / $5.20 | −31% |
| [Gemma 2 27B](https://martllm.com/models/google/gemma-2-27b-it) | text | $0.546 / $0.546 | $0.3754 / $0.3754 | −31% |
| [MythoMax 13B](https://martllm.com/models/gryphe/mythomax-l2-13b) | text | $0.252 / $0.42 | $0.1732 / $0.2888 | −31% |
| [Granite 4.2 8B](https://martllm.com/models/ibm-granite/granite-4.2-8b) | text | $0.0504 / $0.126 | $0.03465 / $0.08662 | −31% |
| [Ling 3.0 Flash VL](https://martllm.com/models/inclusionai/ling-3.0-flash-vl) | text | $0.0504 / $0.1512 | $0.03465 / $0.104 | −31% |
| [Schematron V2 Small](https://martllm.com/models/inference-net/schematron-v2-small) | text | $0.042 / $0.1932 | $0.02888 / $0.1328 | −31% |
| [Schematron V2 Turbo](https://martllm.com/models/inference-net/schematron-v2-turbo) | text | $0.0252 / $0.126 | $0.01733 / $0.08662 | −31% |
| [Mi:dm K 3.0 Pro](https://martllm.com/models/kt/midm-k-3.0-pro) | text | $0.168 / $0.672 | $0.1155 / $0.462 | −31% |
| [LFM3-1.7B](https://martllm.com/models/liquid/lfm-3-1.7b) | text | $0.0672 / $0.168 | $0.0462 / $0.1155 | −31% |
| [Weaver (alpha)](https://martllm.com/models/mancer/weaver) | text | $0.252 / $0.42 | $0.1732 / $0.2888 | −31% |
| [Llama 3.1 70B Instruct](https://martllm.com/models/meta-llama/llama-3.1-70b-instruct) | text | $0.6048 / $0.6048 | $0.4158 / $0.4158 | −31% |
| [Llama 3.1 8B Instruct](https://martllm.com/models/meta-llama/llama-3.1-8b-instruct) | text | $0.042 / $0.0672 | $0.02888 / $0.0462 | −31% |
| [Llama 4 Maverick](https://martllm.com/models/meta-llama/llama-4-maverick) | text | $0.294 / $0.84 | $0.2021 / $0.5775 | −31% |
| [Llama 4 Scout](https://martllm.com/models/meta-llama/llama-4-scout) | text | $0.084 / $0.252 | $0.05775 / $0.1732 | −31% |
| [Llama Guard 4 12B](https://martllm.com/models/meta-llama/llama-guard-4-12b) | text | $0.1512 / $0.1512 | $0.104 / $0.104 | −31% |
| [Codestral 2508](https://martllm.com/models/mistralai/codestral-2508) | text | $0.252 / $0.756 | $0.1732 / $0.5198 | −31% |
| [Devstral 2 2512](https://martllm.com/models/mistralai/devstral-2512) | text | $0.336 / $1.68 | $0.231 / $1.16 | −31% |
| [Ministral 3 14B 2512](https://martllm.com/models/mistralai/ministral-14b-2512) | text | $0.168 / $0.168 | $0.1155 / $0.1155 | −31% |
| [Ministral 3 3B 2512](https://martllm.com/models/mistralai/ministral-3b-2512) | text | $0.084 / $0.084 | $0.05775 / $0.05775 | −31% |
| [Ministral 3 8B 2512](https://martllm.com/models/mistralai/ministral-8b-2512) | text | $0.126 / $0.126 | $0.08662 / $0.08662 | −31% |
| [Mistral Large 2407](https://martllm.com/models/mistralai/mistral-large-2407) | text | $1.68 / $5.04 | $1.16 / $3.46 | −31% |
| [Mistral Large 3 2512](https://martllm.com/models/mistralai/mistral-large-2512) | text | $0.42 / $1.26 | $0.2888 / $0.8662 | −31% |
| [Mistral Medium Latest](https://martllm.com/models/mistralai/mistral-medium-3.5) | text | $1.26 / $6.30 | $0.8662 / $4.33 | −31% |
| [Mistral Nemo 12B](https://martllm.com/models/mistralai/mistral-nemo) | text | $0.02436 / $0.0252 | $0.01675 / $0.01733 | −31% |
| [Saba](https://martllm.com/models/mistralai/mistral-saba) | text | $0.168 / $0.504 | $0.1155 / $0.3465 | −31% |
| [Mistral Small 3](https://martllm.com/models/mistralai/mistral-small-24b-instruct-2501) | text | $0.042 / $0.0672 | $0.02888 / $0.0462 | −31% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-2603) | text | $0.126 / $0.504 | $0.08662 / $0.3465 | −31% |
| [Mixtral 8x22B Instruct](https://martllm.com/models/mistralai/mixtral-8x22b-instruct) | text | $1.68 / $5.04 | $1.16 / $3.46 | −31% |
| [Morph V3 Fast](https://martllm.com/models/morph/morph-v3-fast) | text | $0.672 / $1.01 | $0.462 / $0.693 | −31% |
| [Morph V3 Large](https://martllm.com/models/morph/morph-v3-large) | text | $0.756 / $1.60 | $0.5198 / $1.10 | −31% |
| [Motif 3](https://martllm.com/models/motif-technologies/motif-3) | text | $0.252 / $1.01 | $0.1732 / $0.693 | −31% |
| [Nex-N2.5-Mini](https://martllm.com/models/nex-agi/nex-n2.5-mini) | text | $0.021 / $0.084 | $0.01444 / $0.05775 | −31% |
| [Nex-N2.5-Pro](https://martllm.com/models/nex-agi/nex-n2.5-pro) | text | $0.063 / $0.21 | $0.04331 / $0.1444 | −31% |
| [Nex-N2.6](https://martllm.com/models/nex-agi/nex-n2.6) | text | $0.1008 / $0.336 | $0.0693 / $0.231 | −31% |
| [Hermes 4 405B](https://martllm.com/models/nousresearch/hermes-4-405b) | text | $0.84 / $2.52 | $0.5775 / $1.73 | −31% |
| [NVIDIA Nemotron 3 Super 120B A12B](https://martllm.com/models/nvidia/nemotron-3-super-120b-a12b) | text | $0.063 / $0.336 | $0.04331 / $0.231 | −31% |
| [Nemotron 3.5 Content Safety](https://martllm.com/models/nvidia/nemotron-3.5-content-safety) | text | $0.168 / $0.168 | $0.1155 / $0.1155 | −31% |
| [Nemotron 3.5 Lightning](https://martllm.com/models/nvidia/nemotron-3.5-lightning) | text | $0.0588 / $0.168 | $0.04043 / $0.1155 | −31% |
| [GPT-3.5 Turbo (older v0613)](https://martllm.com/models/openai/gpt-3.5-turbo-0613) | text | $0.84 / $1.68 | $0.5775 / $1.16 | −31% |
| [GPT-3.5 Turbo 16k](https://martllm.com/models/openai/gpt-3.5-turbo-16k) | text | $2.52 / $3.36 | $1.73 / $2.31 | −31% |
| [GPT-4](https://martllm.com/models/openai/gpt-4) | text | $25.20 / $50.40 | $17.32 / $34.65 | −31% |
| [GPT-4.1 nano](https://martllm.com/models/openai/gpt-4.1-nano) | text | $0.084 / $0.336 | $0.05775 / $0.231 | −31% |
| [GPT-4o (2024-05-13)](https://martllm.com/models/openai/gpt-4o-2024-05-13) | text | $4.20 / $12.60 | $2.89 / $8.66 | −31% |
| [GPT-4o (2024-08-06)](https://martllm.com/models/openai/gpt-4o-2024-08-06) | text | $2.10 / $8.40 | $1.44 / $5.78 | −31% |
| [GPT-4o-mini (2024-07-18)](https://martllm.com/models/openai/gpt-4o-mini-2024-07-18) | text | $0.126 / $0.504 | $0.08662 / $0.3465 | −31% |
| [GPT-5.1-Codex](https://martllm.com/models/openai/gpt-5.1-codex) | text | $1.05 / $8.40 | $0.7219 / $5.78 | −31% |
| [GPT 5.1 Codex Max](https://martllm.com/models/openai/gpt-5.1-codex-max) | text | $1.05 / $8.40 | $0.7219 / $5.78 | −31% |
| [GPT 5.1 Codex Mini](https://martllm.com/models/openai/gpt-5.1-codex-mini) | text | $0.21 / $1.68 | $0.1444 / $1.16 | −31% |
| [GPT-6 Astra Pro](https://martllm.com/models/openai/gpt-6-astra-pro) | text | $8.40 / $42.00 | $5.78 / $28.88 | −31% |
| [OpenAI: GPT-6.1 Terra Pro (batch)](https://martllm.com/models/openai/gpt-6.1-terra-pro:batch) | text | $0.42 / $2.10 | $0.2888 / $1.44 | −31% |
| [OpenAI: GPT-6.1 Terra (batch)](https://martllm.com/models/openai/gpt-6.1-terra:batch) | text | $0.42 / $2.10 | $0.2888 / $1.44 | −31% |
| [GPT Chat Latest](https://martllm.com/models/openai/gpt-chat-latest) | text | $4.20 / $25.20 | $2.89 / $17.32 | −31% |
| [Perceptron Mk1](https://martllm.com/models/perceptron/perceptron-mk1) | text | $0.126 / $1.26 | $0.08662 / $0.8662 | −31% |
| [Perceptron Mk1.5](https://martllm.com/models/perceptron/perceptron-mk1.5) | text | $0.126 / $1.26 | $0.08662 / $0.8662 | −31% |
| [Sonar](https://martllm.com/models/perplexity/sonar) | text | $0.84 / $0.84 | $0.5775 / $0.5775 | −31% |
| [Sonar Deep Research](https://martllm.com/models/perplexity/sonar-deep-research) | text | $1.68 / $6.72 | $1.16 / $4.62 | −31% |
| [Sonar Pro](https://martllm.com/models/perplexity/sonar-pro) | text | $2.52 / $12.60 | $1.73 / $8.66 | −31% |
| [Sonar Pro Search](https://martllm.com/models/perplexity/sonar-pro-search) | text | $2.52 / $12.60 | $1.73 / $8.66 | −31% |
| [Sonar Reasoning Pro](https://martllm.com/models/perplexity/sonar-reasoning-pro) | text | $1.68 / $6.72 | $1.16 / $4.62 | −31% |
| [Ternary Bonsai 2 27B](https://martllm.com/models/prism-ml/ternary-bonsai-2-27b) | text | $0.063 / $0.42 | $0.04331 / $0.2888 | −31% |
| [Ternary Bonsai 2 9B](https://martllm.com/models/prism-ml/ternary-bonsai-2-9b) | text | $0.0672 / $0.1092 | $0.0462 / $0.07508 | −31% |
| [Qwen2.5 Coder 32B Instruct](https://martllm.com/models/qwen/qwen-2.5-coder-32b-instruct) | text | $0.5544 / $0.84 | $0.3811 / $0.5775 | −31% |
| [Qwen3-14B](https://martllm.com/models/qwen/qwen-3-14b) | text | $0.1008 / $0.2016 | $0.0693 / $0.1386 | −31% |
| [Qwen-Plus](https://martllm.com/models/qwen/qwen-plus) | text | $0.2184 / $0.6552 | $0.1502 / $0.4505 | −31% |
| [Qwen2.5 72B Instruct](https://martllm.com/models/qwen/qwen2.5-72b-instruct) | text | $0.3024 / $0.336 | $0.2079 / $0.231 | −31% |
| [Qwen2.5 VL 72B Instruct](https://martllm.com/models/qwen/qwen2.5-vl-72b-instruct) | text | $0.672 / $0.84 | $0.462 / $0.5775 | −31% |
| [Qwen3 30B A3B Instruct 2507](https://martllm.com/models/qwen/qwen3-30b-a3b-instruct-2507) | text | $0.084 / $0.252 | $0.05775 / $0.1732 | −31% |
| [Qwen3 VL 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-instruct) | text | $0.126 / $0.504 | $0.08662 / $0.3465 | −31% |
| [Qwen3 VL 8B Instruct](https://martllm.com/models/qwen/qwen3-vl-8b-instruct) | text | $0.21 / $0.63 | $0.1444 / $0.4331 | −31% |
| [Qwen3.5-122B-A10B](https://martllm.com/models/qwen/qwen3.5-122b-a10b) | text | $0.2184 / $1.75 | $0.1502 / $1.20 | −31% |
| [Qwen3.5-27B](https://martllm.com/models/qwen/qwen3.5-27b) | text | $0.2184 / $2.18 | $0.1502 / $1.50 | −31% |
| [Qwen3.5-Flash](https://martllm.com/models/qwen/qwen3.5-flash-02-23) | text | $0.0546 / $0.2184 | $0.03754 / $0.1502 | −31% |
| [Qwen3.5 Plus 2026-02-15](https://martllm.com/models/qwen/qwen3.5-plus-02-15) | text | $0.2184 / $1.31 | $0.1502 / $0.9009 | −31% |
| [Qwen3.5 Plus 2026-04-20](https://martllm.com/models/qwen/qwen3.5-plus-20260420) | text | $0.252 / $1.51 | $0.1732 / $1.04 | −31% |
| [Reka Edge](https://martllm.com/models/rekaai/reka-edge) | text | $0.084 / $0.084 | $0.05775 / $0.05775 | −31% |
| [Reka Flash 3](https://martllm.com/models/rekaai/reka-flash-3) | text | $0.084 / $0.168 | $0.05775 / $0.1155 | −31% |
| [Relace Apply 3](https://martllm.com/models/relace/relace-apply-3) | text | $0.714 / $1.05 | $0.4909 / $0.7219 | −31% |
| [Relace Search](https://martllm.com/models/relace/relace-search) | text | $0.84 / $2.52 | $0.5775 / $1.73 | −31% |
| [Ripple 65B Preview](https://martllm.com/models/ricursiveai/ripple-65b-preview) | text | $0.084 / $0.252 | $0.05775 / $0.1732 | −31% |
| [Fugu Ultra](https://martllm.com/models/sakana/fugu-ultra) | text | $4.20 / $25.20 | $2.89 / $17.32 | −31% |
| [Llama 3 8B Lunaris](https://martllm.com/models/sao10k/l3-lunaris-8b) | text | $0.0336 / $0.042 | $0.0231 / $0.02888 | −31% |
| [Llama 3.1 Euryale 70B v2.2](https://martllm.com/models/sao10k/l3.1-euryale-70b) | text | $0.714 / $0.714 | $0.4909 / $0.4909 | −31% |
| [Hy-MT2-1.8B](https://martllm.com/models/tencent/hy-mt2-1.8b) | text | $0.03696 / $0.1487 | $0.02541 / $0.1022 | −31% |
| [Hy-MT2-30B-A3B](https://martllm.com/models/tencent/hy-mt2-30b-a3b) | text | $0.06216 / $0.2478 | $0.04274 / $0.1704 | −31% |
| [Hy-MT2-7B](https://martllm.com/models/tencent/hy-mt2-7b) | text | $0.06216 / $0.2478 | $0.04274 / $0.1704 | −31% |
| [Cydonia 24B V4.1](https://martllm.com/models/thedrummer/cydonia-24b-v4.1) | text | $0.252 / $0.42 | $0.1732 / $0.2888 | −31% |
| [Skyfall 36B V2](https://martllm.com/models/thedrummer/skyfall-36b-v2) | text | $0.462 / $0.672 | $0.3176 / $0.462 | −31% |
| [UnslopNemo 12B](https://martllm.com/models/thedrummer/unslopnemo-12b) | text | $0.336 / $0.336 | $0.231 / $0.231 | −31% |
| [Inkling Small](https://martllm.com/models/thinking-machines/inkling-small) | text | $0.378 / $1.01 | $0.2599 / $0.693 | −31% |
| [DeepSeek R1T2 Chimera](https://martllm.com/models/tngtech/deepseek-r1t2-chimera) | text | $0.84 / $2.21 | $0.5775 / $1.52 | −31% |
| [ReMM SLERP 13B](https://martllm.com/models/undi95/remm-slerp-l2-13b) | text | $0.252 / $0.42 | $0.1732 / $0.2888 | −31% |
| [Solar Mini 4.5](https://martllm.com/models/upstage/solar-mini-4-5) | text | $0.0084 / $0.0336 | $0.005775 / $0.0231 | −31% |
| [Solar Mini 4](https://martllm.com/models/upstage/solar-mini4) | text | $0.042 / $0.168 | $0.02888 / $0.1155 | −31% |
| [Solar Pro 4 Contributor](https://martllm.com/models/upstage/solar-pro-4-contributor) | text | $0.0756 / $0.3024 | $0.05198 / $0.2079 | −31% |
| [Solar Pro 4](https://martllm.com/models/upstage/solar-pro4) | text | $0.126 / $0.504 | $0.08662 / $0.3465 | −31% |
| [Palmyra X5](https://martllm.com/models/writer/palmyra-x5) | text | $0.504 / $5.04 | $0.3465 / $3.46 | −31% |
| [Grok 4.20](https://martllm.com/models/x-ai/grok-4.20) | text | $1.05 / $2.10 | $0.7219 / $1.44 | −31% |
| [Grok 4.20 Multi-Agent](https://martllm.com/models/x-ai/grok-4.20-multi-agent) | text | $1.05 / $2.10 | $0.7219 / $1.44 | −31% |
| [GLM 4.5V](https://martllm.com/models/z-ai/glm-4.5v) | text | $0.504 / $1.51 | $0.3465 / $1.04 | −31% |
| [GLM 4.6V](https://martllm.com/models/z-ai/glm-4.6v) | text | $0.252 / $0.756 | $0.1732 / $0.5198 | −31% |
| [Nova Micro 1.0](https://martllm.com/models/amazon/nova-micro-v1) | text | $0.0294 / $0.1176 | $0.02021 / $0.08085 | −31% |
| [Phi 4](https://martllm.com/models/microsoft/phi-4) | text | $0.0588 / $0.1176 | $0.04043 / $0.08085 | −31% |
| [Qwen3 Coder Flash](https://martllm.com/models/qwen/qwen3-coder-flash) | text | $0.1638 / $0.819 | $0.1126 / $0.5631 | −31% |
| [Mistral Small 3.1 24B](https://martllm.com/models/mistralai/mistral-small-3.1-24b-instruct) | text | $0.2948 / $0.4662 | $0.2027 / $0.3205 | −31% |
| [Ling 3.0 Flash](https://martllm.com/models/inclusionai/ling-3.0-flash) | text | $0.01764 / $0.05292 | $0.01213 / $0.03638 | −31% |
| [Ling 3.0 Tiny](https://martllm.com/models/inclusionai/ling-3.0-tiny) | text | $0.0126 / $0.0378 | $0.008663 / $0.02599 | −31% |
| [MiniMax M2.5](https://martllm.com/models/minimax/minimax-m2.5) | text | $0.1021 / $0.3591 | $0.07087 / $0.2494 | −31% |
| [Flux 3 First Last Frame](https://martllm.com/models/black-forest-labs/flux-3-first-last-frame-to-video) | video | $0.197 / sec | $0.1375 / sec | −30% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | text | $0.02142 / $0.0714 | $0.01512 / $0.0504 | −29% |
| [Reference To Image Q2](https://martllm.com/models/vidu/reference-to-image-q2) | image | $0.04 / image | $0.02856 / image | −29% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | text | $0.0672 / $0.1344 | $0.0483 / $0.0966 | −28% |
| [Nano Banana 2.1 (image-to-image)](https://martllm.com/models/google/nano-banana-2-1-edit) | image | $0.0165 / image | $0.01213 / image | −26% |
| [Nano Banana 2.1 (Venice)](https://martllm.com/models/google/venice-nano-banana-2-1) | image | $0.0165 / image | $0.01213 / image | −26% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | text | $0.1197 / $0.4988 | $0.0882 / $0.3675 | −26% |
| [Kling O3.4k (reference-to-video)](https://martllm.com/models/kling/kling-o3-4k-reference-to-video) | video | $0.4865 / sec | $0.3633 / sec | −25% |
| [MiniMax H3 Max Multi-Angle](https://martllm.com/models/minimax/minimax-h3-max-multi-angle) | video | $0.04749 / sec | $0.03554 / sec | −25% |
| [Wan 2.2 Enhanced](https://martllm.com/models/wan/wan-2-2-enhanced-image-to-video) | video | $0.0419 / sec | $0.03136 / sec | −25% |
| [LTX Video 2.5 Pro](https://martllm.com/models/lightricks/ltx-2-5-pro-image-to-video) | video | $0.1383 / sec | $0.1035 / sec | −25% |
| [Flux 3 Max](https://martllm.com/models/black-forest-labs/flux-3-max-image-to-video) | video | $0.1739 / sec | $0.1301 / sec | −25% |
| [Wan 2.7 Enhanced](https://martllm.com/models/wan/wan-2-7-enhanced-image-to-video) | video | $0.1348 / sec | $0.1009 / sec | −25% |
| [LTX Video 2.5 Fast](https://martllm.com/models/lightricks/ltx-2-5-fast-image-to-video) | video | $0.1037 / sec | $0.07762 / sec | −25% |
| [MiniMax H3 Max Turbo](https://martllm.com/models/minimax/minimax-h3-max-turbo-image-to-video) | video | $0.02375 / sec | $0.01777 / sec | −25% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | text | $0.03308 / $0.03308 | $0.02481 / $0.02481 | −25% |
| [MiniMax M3](https://martllm.com/models/minimax/minimax-m3) | text | $0.1291 / $0.5166 | $0.09765 / $0.3906 | −24% |
| [Step 3.7 Flash](https://martllm.com/models/stepfun/step-3.7-flash) | text | $0.1458 / $0.8745 | $0.1155 / $0.6641 | in −21% / out −24% |
| [GPT-5 pro](https://martllm.com/models/openai/gpt-5-pro) | text | $11.34 / $90.72 | $8.66 / $69.30 | −24% |
| [GPT 5.2](https://martllm.com/models/openai/gpt-5.2-pro) | text | $15.88 / $127.01 | $12.13 / $97.02 | −24% |
| [Gemini 3.1 Flash Lite Preview](https://martllm.com/models/google/gemini-3.1-flash-lite-preview) | text | $0.189 / $1.13 | $0.1444 / $0.8662 | −24% |
| [GPT-4.1](https://martllm.com/models/openai/gpt-4.1) | text | $1.51 / $6.05 | $1.16 / $4.62 | −24% |
| [GPT-4.1 mini](https://martllm.com/models/openai/gpt-4.1-mini) | text | $0.3024 / $1.21 | $0.231 / $0.924 | −24% |
| [GPT-4o (2024-11-20)](https://martllm.com/models/openai/gpt-4o-2024-11-20) | text | $1.89 / $7.56 | $1.44 / $5.78 | −24% |
| [GPT-5](https://martllm.com/models/openai/gpt-5) | text | $0.945 / $7.56 | $0.7219 / $5.78 | −24% |
| [GPT-5.1](https://martllm.com/models/openai/gpt-5.1) | text | $0.945 / $7.56 | $0.7219 / $5.78 | −24% |
| [o3](https://martllm.com/models/openai/o3) | text | $1.51 / $6.05 | $1.16 / $4.62 | −24% |
| [o3 Pro](https://martllm.com/models/openai/o3-pro) | text | $15.12 / $60.48 | $11.55 / $46.20 | −24% |
| [Ovi Image-to-Video](https://martllm.com/models/ovi/ovi-image-to-video) | video | $0.03696 / sec | $0.02856 / sec | −23% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | text | $0.06143 / $0.2362 | $0.04777 / $0.1837 | −22% |
| [Vidu Q3 Text-to-Video](https://martllm.com/models/vidu/vidu-q3-text-to-video) | video | $0.1827 / sec | $0.1428 / sec | −22% |
| [Vidu Q3 (image-to-video)](https://martllm.com/models/vidu/vidu-q3-image-to-video) | video | $0.08505 / sec | $0.06664 / sec | −22% |
| [Qwen Image 2 Pro (image-to-image)](https://martllm.com/models/qwen/qwen-image-2-pro-edit) | image | $0.084 / image | $0.06664 / image | −21% |
| [Inworld 1.5 Max TTS](https://martllm.com/models/inworld/tts-inworld-1-5-max) | speech | $0.014 / 1K chars | $0.0112 / 1K chars | −20% |
| [MiniMax M2.7](https://martllm.com/models/minimax/minimax-m2.7) | text | $0.2008 / $0.8033 | $0.1614 / $0.6458 | −20% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.02593 / $0.09975 | $0.02231 / $0.08032 | in −14% / out −19% |
| [Krea 2 Turbo (Venice)](https://martllm.com/models/krea/venice-krea-2-turbo) | image | $0.01142 / image | $0.00924 / image | −19% |
| [Claude Fable 5](https://martllm.com/models/anthropic/claude-fable-5) | text | $7.67 / $38.33 | $6.30 / $31.50 | −18% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.06303 / sec | $0.05227 / sec | −17% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | text | $0.008505 / $0.02835 | $0.00735 / $0.02352 | in −14% / out −17% |
| [LongCat Distilled Text-to-Video](https://martllm.com/models/meituan/longcat-distilled-text-to-video) | video | $0.01701 / sec | $0.01411 / sec | −17% |
| [MiniMax H3 Enhanced Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-enhanced-text-to-video) | video | $0.0945 / sec | $0.0784 / sec | −17% |
| [Ltx 2 V2.3 Full (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.08344 / sec | $0.06925 / sec | −17% |
| [Flux 2 Max (Venice)](https://martllm.com/models/venice/flux-2-max) | image | $0.06804 / image | $0.05661 / image | −17% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.01795 / $0.2079 | $0.01496 / $0.1732 | −17% |
| [ACE-Step 1.5 (Venice)](https://martllm.com/models/venice/ace-step-15) | music | $0.03024 / track | $0.0252 / track | −17% |
| [Qwen3.6 Flash](https://martllm.com/models/qwen/qwen3.6-flash) | text | $0.1296 / $0.7775 | $0.1083 / $0.6497 | −16% |
| [LongCat Text-to-Video](https://martllm.com/models/meituan/longcat-text-to-video) | video | $0.04725 / sec | $0.03972 / sec | −16% |
| [Runway Gen-4 Turbo](https://martllm.com/models/runway/runway-gen4-turbo) | video | $0.06468 / sec | $0.05488 / sec | −15% |
| [Gemini Omni Flash (reference-to-video)](https://martllm.com/models/google/gemini-omni-flash-reference-to-video) | video | $0.1047 / sec | $0.08896 / sec | −15% |
| [Flux 3](https://martllm.com/models/black-forest-labs/flux-3-image-to-video) | video | $0.1618 / sec | $0.1375 / sec | −15% |
| [Meta: Muse Spark 1.2](https://martllm.com/models/meta-llama/muse-spark-1.2) | text | $0.63 / $2.14 | $0.5381 / $1.83 | −15% |
| [Veo3 Fast (image-to-video)](https://martllm.com/models/google/veo3-fast-image-to-video) | video | $0.11 / sec | $0.0952 / sec | −13% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | text | $6.30 / $31.50 | $5.46 / $27.30 | −13% |
| [Qwen 3.6 Plus](https://martllm.com/models/qwen/qwen3.6-plus) | text | $0.2161 / $1.30 | $0.1877 / $1.13 | −13% |
| [GPT-4o Mini](https://martllm.com/models/openai/gpt-4o-mini) | text | $0.03623 / $0.1449 | $0.0315 / $0.126 | −13% |
| [MAGI-2 Reference to Video](https://martllm.com/models/sand-ai/magi-2-reference-to-video) | video | $0.0924 / sec | $0.08087 / sec | −12% |
| [Chroma (Venice)](https://martllm.com/models/venice/chroma) | image | $0.008925 / image | $0.00784 / image | −12% |
| [NVIDIA Nemotron 3 Super 120B](https://martllm.com/models/nvidia/nemotron-3-super-120b) | text | $0.01339 / $0.0714 | $0.01181 / $0.063 | −12% |
| [Gemini 3.6 Flash](https://martllm.com/models/google/gemini-3-6-flash) | text | $0.6221 / $3.11 | $0.5513 / $2.76 | −11% |
| [MiniMax H3 Hyper Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-image-to-video) | video | $0.03646 / sec | $0.03241 / sec | −11% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | text | $0.189 / $0.567 | $0.168 / $0.504 | −11% |
| [Grok Imagine Reference To Video Private (reference-to-video)](https://martllm.com/models/x-ai/grok-imagine-reference-to-video-private) | video | $0.05544 / sec | $0.04965 / sec | −10% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | text | $0.0336 / $0.336 | $0.03696 / $0.3696 | +10% |
| [Qwen3.8 2.4T A95B](https://martllm.com/models/qwen/qwen3.8-2.4t-a95b) | text | $1.26 / $3.78 | $1.39 / $4.16 | +10% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | text | $2.52 / $12.60 | $2.78 / $13.91 | +10% |
| [Qwen 3.7 Plus](https://martllm.com/models/qwen/qwen3.7-plus) | text | $0.4515 / $1.81 | $0.4988 / $2.00 | +10% |
| [MiniMax H3 Chili Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-chili-text-to-video) | video | $0.02835 / sec | $0.03136 / sec | +11% |
| [MiniMax M2.1](https://martllm.com/models/minimax/minimax-m2.1) | text | $0.002741 / $0.008978 | $0.003045 / $0.009975 | +11% |
| [ElevenLabs Music v2](https://martllm.com/models/elevenlabs/elevenlabs-music-v2) | music | $0.6955 / track | $0.7728 / track | +11% |
| [Gemini 3.1 Flash Lite](https://martllm.com/models/google/gemini-3.1-flash-lite) | text | $0.189 / $1.13 | $0.21 / $1.26 | +11% |
| [Venice Music Gen (legacy alias)](https://martllm.com/models/venice/music-gen) | music | $0.03024 / track | $0.0336 / track | +11% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | text | $2.68 / $13.39 | $2.99 / $14.96 | +12% |
| [Claude Opus 5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5-fast) | text | $7.35 / $36.75 | $8.29 / $41.48 | +13% |
| [Qwen3.7 Max](https://martllm.com/models/qwen/qwen3.7-max) | text | $2.32 / $6.93 | $2.64 / $7.86 | +13% |
| [Qwen 2.5 7B](https://martllm.com/models/qwen/e2ee-qwen-2-5-7b-p) | text | $0.04095 / $0.1065 | $0.04673 / $0.1215 | +14% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://martllm.com/models/venice/elevenlabs-tts-turbo-v2-5) | speech | $0.049 / 1K chars | $0.056 / 1K chars | +14% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | text | $0.2572 / $1.85 | $0.294 / $2.12 | +14% |
| [Qwen 3 Coder 480B Turbo](https://martllm.com/models/qwen/qwen3-coder-turbo) | text | $0.3087 / $1.32 | $0.3528 / $1.51 | +14% |
| [Kling 2.5 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-2-5-turbo-pro-image-to-video) | video | $0.06143 / sec | $0.07056 / sec | +15% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | text | $0.1155 / $0.5775 | $0.1328 / $0.6641 | +15% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.06143 / $0.1638 | $0.07166 / $0.1911 | +17% |
| [Kling O3 Pro (image-to-video)](https://martllm.com/models/kling/kling-o3-pro-image-to-video) | video | $0.1207 / sec | $0.1411 / sec | +17% |
| [Kling O3 Pro Text-to-Video](https://martllm.com/models/kling/kling-o3-pro-text-to-video) | video | $0.1207 / sec | $0.1411 / sec | +17% |
| [MiniMax H3 Chili Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-chili-image-to-video) | video | $0.03071 / sec | $0.03606 / sec | +17% |
| [Qwen Image 2.1](https://martllm.com/models/qwen/qwen-image-2-1) | image | $0.01904 / image | $0.0224 / image | +18% |
| [xAI v1 TTS](https://martllm.com/models/x-ai/tts-xai-v1) | speech | $0.01764 / 1K chars | $0.02079 / 1K chars | +18% |
| [Qwen3 VL 235B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-thinking) | text | $0.1698 / $1.54 | $0.2007 / $1.82 | +18% |
| [Claude Sonnet 4.5](https://martllm.com/models/anthropic/claude-sonnet-4.5) | text | $2.24 / $11.18 | $2.65 / $13.23 | +18% |
| [LTX 2 v2.3 Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.08347 / sec | $0.09893 / sec | +19% |
| [LTX 2 v2.3 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.063 / sec | $0.07467 / sec | +19% |
| [Kimi K3 Fast](https://martllm.com/models/moonshotai/kimi-k3-fast-api) | text | $3.78 / $18.90 | $4.49 / $22.44 | +19% |
| [Wan 3.0 Prime Pro Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-pro-image-to-video) | video | $0.313 / sec | $0.3724 / sec | +19% |
| [Wan 3.0 Prime Pro Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-pro-reference-to-video) | video | $0.313 / sec | $0.3724 / sec | +19% |
| [Wan 3.0 Prime Pro Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-pro-text-to-video) | video | $0.313 / sec | $0.3724 / sec | +19% |
| [Qwen 3.5 35B A3B](https://martllm.com/models/qwen/qwen3.5-35b-a3b) | text | $0.1244 / $0.8295 | $0.148 / $0.987 | +19% |
| [Qwen3 VL 30B A3B](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-thinking) | text | $0.2205 / $0.7938 | $0.2625 / $0.945 | +19% |
| [Wan 3.0 Pro Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-pro-image-to-video) | video | $0.2236 / sec | $0.2666 / sec | +19% |
| [Wan 3.0 Pro Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-pro-reference-to-video) | video | $0.2236 / sec | $0.2666 / sec | +19% |
| [Wan 3.0 Pro Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-pro-text-to-video) | video | $0.2236 / sec | $0.2666 / sec | +19% |
| [Claude Sonnet 4.6](https://martllm.com/models/anthropic/claude-sonnet-4.6) | text | $1.61 / $8.03 | $1.92 / $9.61 | +20% |
| [Kling O3 Standard Text-to-Video](https://martllm.com/models/kling/kling-o3-standard-text-to-video) | video | $0.0945 / sec | $0.1131 / sec | +20% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | text | $0.042 / $0.2625 | $0.0504 / $0.315 | +20% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | text | $0.147 / $0.462 | $0.1764 / $0.5544 | +20% |
| [Qwen 3.6 35B A3B (E2EE)](https://martllm.com/models/qwen/e2ee-qwen3-6-35b-a3b) | text | $0.151 / $0.9788 | $0.1815 / $1.18 | +20% |
| [GPT OSS 120B](https://martllm.com/models/openai/e2ee-gpt-oss-120b-p) | text | $0.1133 / $0.5665 | $0.1365 / $0.6825 | +20% |
| [Claude Opus 4.5](https://martllm.com/models/anthropic/claude-opus-4.5) | text | $3.36 / $16.80 | $4.09 / $20.48 | +22% |
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | speech | $0.003175 / 1K chars | $0.003881 / 1K chars | +22% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | text | $0.01144 / $0.0756 | $0.01398 / $0.0924 | +22% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | text | $1.47 / $4.83 | $1.82 / $5.98 | +24% |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-text-to-video) | video | $0.0232 / sec | $0.02875 / sec | +24% |
| [Wan 2.7 Pro (image-to-video)](https://martllm.com/models/wan/wan-2-7-pro-image-to-video) | video | $0.1071 / sec | $0.1333 / sec | +24% |
| [Orpheus TTS](https://martllm.com/models/canopy-labs/tts-orpheus) | speech | $0.056 / 1K chars | $0.07 / 1K chars | +25% |
| [Qwen3 1.7B TTS](https://martllm.com/models/qwen/tts-qwen3-1-7b) | speech | $0.1008 / 1K chars | $0.126 / 1K chars | +25% |
| [Chatterbox HD TTS](https://martllm.com/models/resemble-ai/tts-chatterbox-hd) | speech | $0.0448 / 1K chars | $0.056 / 1K chars | +25% |
| [Seed Audio 1.0](https://martllm.com/models/bytedance/seed-audio-1-0) | music | $0.002576 / sec | $0.00322 / sec | +25% |
| [Wan 2.5 Preview (image-to-video)](https://martllm.com/models/wan/wan-2-5-preview-image-to-video) | video | $0.05292 / sec | $0.06712 / sec | +27% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | text | $0.0945 / $0.567 | $0.1207 / $0.7245 | +28% |
| [Grok Imagine Pro (Venice)](https://martllm.com/models/venice/grok-imagine-pro) | image | $0.03675 / image | $0.04704 / image | +28% |
| [DeepSeek V4 Flash E2EE](https://martllm.com/models/deepseek/e2ee-deepseek-v4-flash) | text | $0.1433 / $0.2937 | $0.1854 / $0.3799 | +29% |
| [Seedance 2.5 Flash Image-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-flash-image-to-video-basic) | video | $0.07946 / sec | $0.1036 / sec | +30% |
| [Seedance 2.5 Flash Reference-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-flash-reference-to-video-basic) | video | $0.07946 / sec | $0.1036 / sec | +30% |
| [Seedance 2.5 Flash Text-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-flash-text-to-video-basic) | video | $0.07946 / sec | $0.1036 / sec | +30% |
| [GPT Image 1.5 (Venice)](https://martllm.com/models/venice/gpt-image-1.5) | image | $0.1229 / image | $0.1615 / image | +31% |
| [Luma Uni 1 (image-to-image)](https://martllm.com/models/luma/luma-uni-1-edit) | image | $0.0504 / image | $0.0672 / image | +33% |
| [ElevenLabs Music (Venice)](https://martllm.com/models/venice/elevenlabs-music) | music | $0.5796 / track | $0.7728 / track | +33% |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | music | $0.0336 / track | $0.0448 / track | +33% |
| [Venice SD35](https://martllm.com/models/venice/sd35) | image | $0.0084 / image | $0.0112 / image | +33% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | text | $0.06294 / $0.1888 | $0.08442 / $0.2533 | +34% |
| [Ideogram V2 Turbo](https://martllm.com/models/ideogram/ideogram-v2-turbo) | image | $0.05 / image | $0.0672 / image | +34% |
| [Ideogram V2](https://martllm.com/models/ideogram/ideogram-v2) | image | $0.08 / image | $0.1075 / image | +34% |
| [Google: Gemini 4 Neon](https://martllm.com/models/google/gemini-4-neon) | text | $0.9765 / $4.88 | $1.32 / $6.62 | +35% |
| [Claude Sonnet 5](https://martllm.com/models/anthropic/claude-sonnet-5) | text | $0.882 / $4.41 | $1.20 / $5.99 | +36% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | text | $0.1543 / $0.7519 | $0.2132 / $1.04 | +38% |
| [Grok Imagine 1.5 Lite Text-to-Video](https://martllm.com/models/x-ai/venice-grok-imagine-1-5-lite-text-to-video) | video | $0.02268 / sec | $0.03136 / sec | +38% |
| [Seedance 1.5 Pro (image-to-video)](https://martllm.com/models/bytedance/seedance-1-5-pro-image-to-video) | video | $0.0357 / sec | $0.0495 / sec | +39% |
| [GPT-5.3 Codex](https://martllm.com/models/openai/gpt-5.3-codex) | text | $0.6799 / $5.44 | $0.9555 / $7.64 | +41% |
| [Flux 1.1 Pro (Venice, legacy)](https://martllm.com/models/venice/flux-1.1-pro) | image | $0.0252 / image | $0.03584 / image | +42% |
| [Luma Uni 1 Max (image-to-image)](https://martllm.com/models/luma/luma-uni-1-max-edit) | image | $0.1024 / image | $0.1456 / image | +42% |
| [GPT Image 2.6 Sunburst (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-sunburst) | image | $0.0476 / image | $0.07056 / image | +48% |
| [Hunyuan Image 3.0 (Venice)](https://martllm.com/models/venice/hunyuan-image-v3) | image | $0.04725 / image | $0.07056 / image | +49% |
| [Qwen Image (Venice)](https://martllm.com/models/venice/qwen-image) | image | $0.01575 / image | $0.02352 / image | +49% |
| [Claude Opus 4.6](https://martllm.com/models/anthropic/claude-opus-4.6) | text | $2.78 / $13.91 | $4.20 / $21.00 | +51% |
| [Kimi K2.7 Code](https://martllm.com/models/moonshotai/kimi-k2.7-code) | text | $0.1496 / $0.6983 | $0.2284 / $1.07 | +53% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.0127 / $0.05082 | $0.01963 / $0.07854 | +55% |
| [Stable Audio 2.5 (Venice)](https://martllm.com/models/venice/stable-audio-25) | music | $0.172 / track | $0.2688 / track | +56% |
| [Voxtral Small 24B 2507](https://martllm.com/models/mistralai/voxtral-small-24b-2507) | text | $0.05402 / $0.1621 | $0.08489 / $0.2547 | +57% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | text | $0.01575 / $0.04935 | $0.0252 / $0.07896 | +60% |
| [Wan 2.6 Text-to-Video](https://martllm.com/models/wan/wan-2-6-text-to-video) | video | $0.06693 / sec | $0.1108 / sec | +66% |
| [HappyHorse 1.0 Text-to-Video](https://martllm.com/models/happyhorse/happyhorse-1-0-text-to-video) | video | $0.1232 / sec | $0.215 / sec | +75% |
| [Seedance 1.0 Pro Fast](https://martllm.com/models/bytedance/seedance-1-0-pro-fast-image-to-video) | video | $0.01142 / sec | $0.02016 / sec | +76% |
| [Hailuo 02 Standard Image to Video](https://martllm.com/models/minimax/hailuo-02-standard-image-to-video) | video | $0.01541 / sec | $0.028 / sec | +82% |
| [Wan 2.7 Text-to-Video](https://martllm.com/models/wan/wan-2-7-text-to-video) | video | $0.05775 / sec | $0.1108 / sec | +92% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.0463 / $0.172 | $0.08427 / $0.3352 | in +82% / out +95% |
| [Gemini 3.1 Pro Preview](https://martllm.com/models/google/gemini-3.1-pro-preview) | text | $0.273 / $1.64 | $0.546 / $3.28 | +100% |
| [Seedance 2.0 Text-to-Video](https://martllm.com/models/bytedance/seedance-2-0-text-to-video) | video | $0.05914 / sec | $0.1276 / sec | +116% |
| [Veo3.1 Full (image-to-video)](https://martllm.com/models/google/veo3-1-full-image-to-video) | video | $0.1613 / sec | $0.35 / sec | +117% |
| [Veo 3.1 Full Text-to-Video](https://martllm.com/models/google/veo3-1-full-text-to-video) | video | $0.1613 / sec | $0.35 / sec | +117% |
| [Kling V3 Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-standard-image-to-video) | video | $0.1323 / sec | $0.4332 / sec | +227% |
| [Recraft V3](https://martllm.com/models/recraft/recraft-v3) | image | $0.04 / image | $0.1434 / image | +258% |
| [Stable Diffusion XL (Venice, legacy)](https://martllm.com/models/venice/sdxl) | image | $0.0084 / image | $0.03584 / image | +327% |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | $0.101 / sec | $0.4332 / sec | +329% |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | text | $0.2499 / $0.9207 | $1.11 / $4.01 | in +345% / out +336% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | text | $0.1103 / $0.6615 | $1.50 / $9.00 | +1261% |

</details>


## 2026-11-26 (vs 2026-11-25)

**Official list price changes (36)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MiniMax H3](https://martllm.com/models/minimax/minimax-h3) | video | $0.13 / sec | $0.04 / sec | −69% |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | text | $0.17 / $0.25 | $0.10 / $0.25 | in −41% / out 0% |
| [NVIDIA Nemotron 3 Ultra 550B](https://martllm.com/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.625 / $3.12 | $0.50 / $2.20 | in −20% / out −30% |
| [Thinking Machines: Inkling 2 Mini](https://martllm.com/models/thinking-machines/inkling-2-mini) | text | $0.0975 / $0.40 | $0.075 / $0.30 | in −23% / out −25% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | text | $0.5002 / $2.06 | $0.40 / $1.75 | in −20% / out −15% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.09 / $0.25 | $0.075 / $0.20 | in −17% / out −20% |
| [Tencent: Hy4](https://martllm.com/models/tencent/hy4) | text | $0.834 / $2.50 | $0.7089 / $2.13 | −15% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | text | $0.975 / $3.04 | $0.925 / $2.71 | in −5% / out −11% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | text | $0.26 / $0.42 | $0.26 / $0.38 | in 0% / out −10% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | text | $0.0653 / $0.40 | $0.0605 / $0.40 | in −7% / out 0% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | text | $0.097 / $0.319 | $0.09 / $0.30 | in −7% / out −6% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | text | $0.725 / $3.40 | $0.70 / $3.41 | in −3% / out 0% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | text | $1.35 / $4.29 | $1.33 / $4.18 | in −2% / out −3% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | text | $1.35 / $4.29 | $1.33 / $4.18 | in −2% / out −3% |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-text-to-video) | video | $0.02633 / sec | $0.026 / sec | −1% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | text | $0.3225 / $3.20 | $0.32 / $3.20 | in −1% / out 0% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.15 / $0.668 | $0.15 / $0.666 | 0% |
| [Flux 3](https://martllm.com/models/black-forest-labs/flux-3-image-to-video) | video | – | $0.188 / sec |  |
| [Seedance 1.0 Pro Fast](https://martllm.com/models/bytedance/seedance-1-0-pro-fast-image-to-video) | video | – | $0.018 / sec |  |
| [Ideogram V4.6](https://martllm.com/models/ideogram/ideogram-v4-6) | image | – | $0.13 / image |  |
| [Kling O3 Pro (reference-to-video)](https://martllm.com/models/kling/kling-o3-pro-reference-to-video) | video | – | $0.1533 / sec |  |
| [Kling O3 Standard (reference-to-video)](https://martllm.com/models/kling/kling-o3-standard-reference-to-video) | video | – | $0.1233 / sec |  |
| [Kling Image 4.0 (image-to-image)](https://martllm.com/models/kling/venice-kling-v4-image-edit) | image | – | $0.08 / image |  |
| [LTX 2 19B Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-19b-full-text-to-video) | video | – | $0.088 / sec |  |
| [MiniMax H3 Image (image-to-image)](https://martllm.com/models/minimax/venice-minimax-h3-image-edit) | image | – | $0.06 / image |  |
| [Qwen Image 2.1](https://martllm.com/models/qwen/qwen-image-2-1) | image | – | $0.02 / image |  |
| [MiniMax Music 2.6 (Venice)](https://martllm.com/models/venice/minimax-music-v26) | music | – | $0.24 / track |  |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | text | – / – | $1.19 / $4.38 |  |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | text | $0.13 / $0.275 | $0.1325 / $0.275 | in +2% / out 0% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.205 / $0.79 | $0.21 / $0.78 | in +2% / out −1% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.125 / $0.50 | $0.13 / $0.50 | in +4% / out 0% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | text | $0.1875 / $1.99 | $0.20 / $2.00 | in +7% / out +1% |
| [Thinking Machines: Inkling](https://martllm.com/models/thinking-machines/inkling) | text | $1.10 / $4.53 | $1.20 / $5.00 | in +9% / out +10% |
| [MiniMax H3 Hyper Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-image-to-video) | video | $0.035 / sec | $0.04133 / sec | +18% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | text | $0.14 / $0.86 | $0.17 / $0.98 | in +21% / out +14% |
| [Particle AI: Particle-1](https://martllm.com/models/particle-ai/particle-1) | text | $0.0525 / $0.375 | $0.07 / $0.50 | +33% |

**New models (311)**

| Model | Category | Official price | MartLLM price |
|---|---|---|---|
| [Aion-RP 1.0 (8B)](https://martllm.com/models/aion-labs/aion-rp-llama-3.1-8b) | text | $0.80 / $1.60 | $0.672 / $1.34 |
| [Nova 2 Lite](https://martllm.com/models/amazon/nova-2-lite) | text | – | $0.3036 / $2.53 |
| [Nova 2 Lite](https://martllm.com/models/amazon/nova-2-lite-v1) | text | $0.30 / $2.50 | $0.252 / $2.10 |
| [Nova Lite](https://martllm.com/models/amazon/nova-lite) | text | $0.06 / $0.24 | $0.0552 / $0.2208 |
| [Nova Lite 1.0](https://martllm.com/models/amazon/nova-lite-v1) | text | $0.06 / $0.24 | $0.0504 / $0.2016 |
| [Nova Micro](https://martllm.com/models/amazon/nova-micro) | text | $0.035 / $0.14 | $0.0322 / $0.1288 |
| [Nova Micro 1.0](https://martllm.com/models/amazon/nova-micro-v1) | text | $0.035 / $0.14 | $0.0294 / $0.1176 |
| [Nova Premier 1.0](https://martllm.com/models/amazon/nova-premier-v1) | text | $2.50 / $12.50 | $2.10 / $10.50 |
| [Nova Pro](https://martllm.com/models/amazon/nova-pro) | text | $0.80 / $3.20 | $0.736 / $2.94 |
| [Nova Pro 1.0](https://martllm.com/models/amazon/nova-pro-v1) | text | $0.80 / $3.20 | $0.672 / $2.69 |
| [Magnum v4 72B](https://martllm.com/models/anthracite-org/magnum-v4-72b) | text | $2.50 / $5.00 | $2.10 / $4.20 |
| [Claude Fable 5.2 (Fast)](https://martllm.com/models/anthropic/claude-fable-5.2-fast) | text | – | $14.72 / $73.60 |
| [Claude Haiku 5.5 (batch)](https://martllm.com/models/anthropic/claude-haiku-5.5:batch) | text | – | $0.042 / $0.21 |
| [Claude Opus 4.1](https://martllm.com/models/anthropic/claude-opus-4.1) | text | $15.00 / $75.00 | $12.60 / $63.00 |
| [Claude Opus 4.8 Fast](https://martllm.com/models/anthropic/claude-opus-4.8-fast) | text | – | $9.20 / $46.00 |
| [Claude Opus 5.5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5.5-fast) | text | – | $7.36 / $36.80 |
| [ERNIE-Light-DT-1.0](https://martllm.com/models/baidu/ernie-light-dt-1.0-intl) | text | $1.13 / $3.94 | $0.9492 / $3.31 |
| [FLUX 2 Flash Edit](https://martllm.com/models/black-forest-labs/flux-2-flash-edit) | image | $0.03 / image | $0.02856 / image |
| [FLUX 2 Klein 9b Edit](https://martllm.com/models/black-forest-labs/flux-2-klein-9b-edit) | image | $0.016 / image | $0.01523 / image |
| [FLUX 2 Klein Base 4b Edit](https://martllm.com/models/black-forest-labs/flux-2-klein-base-4b-edit) | image | $0.015 / image | $0.01428 / image |
| [FLUX 2 Klein Base 9b Text To Image](https://martllm.com/models/black-forest-labs/flux-2-klein-base-9b-text-to-image) | image | – | $0.015 / image |
| [FLUX 2 Turbo Edit](https://martllm.com/models/black-forest-labs/flux-2-turbo-edit) | image | $0.048 / image | $0.0457 / image |
| [FLUX 3 Klein Image Base Edit](https://martllm.com/models/black-forest-labs/flux-3-klein-image-base-edit) | image | $0.045 / image | $0.04284 / image |
| [FLUX 3 Klein Image Distilled Edit](https://martllm.com/models/black-forest-labs/flux-3-klein-image-distilled-edit) | image | $0.016 / image | $0.01523 / image |
| [FLUX Kontext Dev](https://martllm.com/models/black-forest-labs/flux-kontext-dev) | image | $0.025 / image | $0.0238 / image |
| [Fibo](https://martllm.com/models/bria/fibo) | image | – | $0.04 / image |
| [Fibo 2.0 Edit](https://martllm.com/models/bria/fibo-2-0-edit) | image | $0.04 / image | $0.03808 / image |
| [Fibo Edit 1.5 Edit](https://martllm.com/models/bria/fibo-edit-1-5-edit) | image | $0.04 / image | $0.03808 / image |
| [Fibo Image Blend](https://martllm.com/models/bria/fibo-image-blend) | image | – | $0.04 / image |
| [Text To Image 3.2](https://martllm.com/models/bria/text-to-image-3-2) | image | – | $0.04 / image |
| [Seed-2.0-Lite](https://martllm.com/models/bytedance-seed/seed-2.0-lite) | text | $0.25 / $2.00 | $0.21 / $1.68 |
| [Seed-2.0-Mini](https://martllm.com/models/bytedance-seed/seed-2.0-mini) | text | $0.10 / $0.40 | $0.084 / $0.336 |
| [Seedance 2.5 Edit](https://martllm.com/models/bytedance/seedance-2-5-edit-video-basic) | video | $0 / sec | $0 / sec |
| [Seedance 2.5 Flash Edit](https://martllm.com/models/bytedance/seedance-2-5-flash-edit-video-basic) | video | $0 / sec | $0 / sec |
| [UI-TARS 7B](https://martllm.com/models/bytedance/ui-tars-1.5-7b) | text | $0.10 / $0.20 | $0.084 / $0.168 |
| [Apex](https://martllm.com/models/callstack/apex) | text | – | $0.46 / $2.76 |
| [Command A](https://martllm.com/models/cohere/command-a) | text | $2.50 / $10.00 | $2.10 / $8.40 |
| [Command R (08-2024)](https://martllm.com/models/cohere/command-r-08-2024) | text | $0.15 / $0.60 | $0.126 / $0.504 |
| [Command R+ (08-2024)](https://martllm.com/models/cohere/command-r-plus-08-2024) | text | $2.50 / $10.00 | $2.10 / $8.40 |
| [Command R7B (12-2024)](https://martllm.com/models/cohere/command-r7b-12-2024) | text | $0.0375 / $0.15 | $0.0315 / $0.126 |
| [DeepSeek V3](https://martllm.com/models/deepseek/deepseek-chat) | text | $0.2574 / $1.03 | $0.2162 / $0.8641 |
| [DeepSeek V3 0324](https://martllm.com/models/deepseek/deepseek-chat-v3-0324) | text | $0.25 / $1.00 | $0.21 / $0.84 |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-chat-v3.1) | text | $0.25 / $0.95 | $0.21 / $0.798 |
| [DeepSeek R1](https://martllm.com/models/deepseek/deepseek-r1) | text | – | $0.4234 / $1.69 |
| [R1 0528](https://martllm.com/models/deepseek/deepseek-r1-0528) | text | $0.571 / $2.29 | $0.3856 / $1.16 |
| [DeepSeek V3.1 Terminus](https://martllm.com/models/deepseek/deepseek-v3.1-terminus) | text | $0.27 / $1.00 | $0.2268 / $0.84 |
| [DeepSeek V3.2 Exp](https://martllm.com/models/deepseek/deepseek-v3.2-exp) | text | $0.27 / $0.41 | $0.2268 / $0.3444 |
| [DeepSeek V4.1 Flash 1017 Fast](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017-fast) | text | – | $0.552 / $2.21 |
| [DeepSeek V4.1 Flash 1017 Ultrafast](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017-ultrafast) | text | – | $1.47 / $5.87 |
| [DeepSeek V4.1 Flash Fast](https://martllm.com/models/deepseek/deepseek-v4.1-flash-fast) | text | – | $0.552 / $2.21 |
| [Eleven Flash v2](https://martllm.com/models/elevenlabs/eleven-flash-v2) | speech | – | $0.04 / 1K chars |
| [Eleven Flash v2.5](https://martllm.com/models/elevenlabs/eleven-flash-v2-5) | speech | – | $0.04 / 1K chars |
| [Storytel v2](https://martllm.com/models/elevenlabs/eleven-storytel-v2) | speech | – | $0.08 / 1K chars |
| [Eleven Turbo v2](https://martllm.com/models/elevenlabs/eleven-turbo-v2) | speech | – | $0.04 / 1K chars |
| [Eleven v3 Conversational](https://martllm.com/models/elevenlabs/eleven-v3-conversational) | speech | – | $0.04 / 1K chars |
| [FLUX.1 [schnell]](https://martllm.com/models/black-forest-labs/flux-schnell) | image | – | $0.003 / image |
| [Recraft V3](https://martllm.com/models/recraft/recraft-v3) | image | – | $0.04 / image |
| [Gemini 2.5 Flash](https://martllm.com/models/google/gemini-2.5-flash) | text | $0.30 / $2.50 | $0.252 / $2.10 |
| [Gemini 2.5 Flash Lite](https://martllm.com/models/google/gemini-2.5-flash-lite) | text | $0.10 / $0.40 | $0.084 / $0.336 |
| [Gemini 2.5 Pro](https://martllm.com/models/google/gemini-2.5-pro) | text | $1.25 / $10.00 | $1.05 / $8.40 |
| [Gemini 2.5 Pro Preview 06-05](https://martllm.com/models/google/gemini-2.5-pro-preview) | text | $1.25 / $10.00 | $1.05 / $8.40 |
| [Gemini 3.1 Flash Lite Image](https://martllm.com/models/google/gemini-3-1-flash-lite-image) | image | – | $0.008 / image |
| [Gemini 3 Flash](https://martllm.com/models/google/gemini-3-flash) | text | $0.50 / $3.00 | $0.42 / $2.52 |
| [Nano Banana Pro (Gemini 3 Pro Image)](https://martllm.com/models/google/gemini-3-pro-image) | text | $2.00 / $12.00 | $1.68 / $10.08 |
| [Nano Banana Pro (Gemini 3 Pro Image Preview)](https://martllm.com/models/google/gemini-3-pro-image-preview) | text | $2.00 / $12.00 | $1.68 / $10.08 |
| [Gemini 3.1 Flash Image (Nano Banana 2)](https://martllm.com/models/google/gemini-3.1-flash-image) | text | $0.50 / $3.00 | $0.42 / $2.52 |
| [Nano Banana 2 (Gemini 3.1 Flash Image Preview)](https://martllm.com/models/google/gemini-3.1-flash-image-preview) | text | $0.50 / $3.00 | $0.42 / $2.52 |
| [Gemini 3.1 Flash Lite Image (Nano Banana 2 Lite)](https://martllm.com/models/google/gemini-3.1-flash-lite-image) | text | $0.25 / $1.50 | $0.21 / $1.26 |
| [Gemini 3.1 Flash Lite Preview](https://martllm.com/models/google/gemini-3.1-flash-lite-preview) | text | $0.25 / $1.50 | $0.189 / $1.13 |
| [Gemini 3.1 Pro Preview Custom Tools](https://martllm.com/models/google/gemini-3.1-pro-preview-customtools) | text | $2.00 / $12.00 | $1.68 / $10.08 |
| [Gemini 4 Neon (Fast)](https://martllm.com/models/google/gemini-4-neon-fast) | text | – | $4.97 / $24.84 |
| [Gemini Nano Banana 2.1](https://martllm.com/models/google/gemini-nano-banana-2.1) | text | $1.50 / $7.50 | $1.26 / $6.30 |
| [Gemini Omni 1.1 Flash](https://martllm.com/models/google/gemini-omni-1.1-flash) | text | $1.50 / $9.00 | $1.26 / $7.56 |
| [Gemini Omni 1.2 Flash](https://martllm.com/models/google/gemini-omni-1.2-flash) | text | $1.50 / $9.00 | $1.26 / $7.56 |
| [Gemini Omni Flash 1.1 Edit](https://martllm.com/models/google/gemini-omni-flash-1-1-video-to-video) | video | $0 / sec | $0 / sec |
| [Gemini Omni Flash Preview](https://martllm.com/models/google/gemini-omni-flash-preview) | text | – | $1.38 / $8.28 |
| [Gemma 2 27B](https://martllm.com/models/google/gemma-2-27b-it) | text | – | $0.546 / $0.546 |
| [Gradium TTS](https://martllm.com/models/gradium/tts-gradium-v1) | speech | – | $0.0475 / 1K chars |
| [MythoMax 13B](https://martllm.com/models/gryphe/mythomax-l2-13b) | text | $0.30 / $0.50 | $0.252 / $0.42 |
| [HappyHorse 1.0 Edit](https://martllm.com/models/happyhorse/happyhorse-1-0-video-to-video) | video | $0 / sec | $0 / sec |
| [Granite 4.2 8B](https://martllm.com/models/ibm-granite/granite-4.2-8b) | text | $0.06 / $0.15 | $0.0504 / $0.126 |
| [Ideogram Character](https://martllm.com/models/ideogram/ideogram-character) | image | – | $0.15 / image |
| [Ideogram V2](https://martllm.com/models/ideogram/ideogram-v2) | image | – | $0.08 / image |
| [Ideogram V2 Turbo](https://martllm.com/models/ideogram/ideogram-v2-turbo) | image | – | $0.05 / image |
| [Ideogram V2a](https://martllm.com/models/ideogram/ideogram-v2a) | image | – | $0.04 / image |
| [Ideogram V2a Turbo](https://martllm.com/models/ideogram/ideogram-v2a-turbo) | image | – | $0.04 / image |
| [Ideogram V3 Generate Transparent](https://martllm.com/models/ideogram/ideogram-v3-generate-transparent) | image | – | $0.085 / image |
| [Mercury 3](https://martllm.com/models/inception/mercury-3) | text | – | $0.092 / $0.322 |
| [Ling 3.0 Flash](https://martllm.com/models/inclusionai/ling-3.0-flash) | text | $0.021 / $0.063 | $0.01764 / $0.05292 |
| [Ling 3.0 Flash Fin](https://martllm.com/models/inclusionai/ling-3.0-flash-fin) | text | – | $0.069 / $0.2024 |
| [Ling 3.0 Flash Sante](https://martllm.com/models/inclusionai/ling-3.0-flash-sante) | text | – | $0.069 / $0.2024 |
| [Ling 3.0 Flash VL](https://martllm.com/models/inclusionai/ling-3.0-flash-vl) | text | $0.06 / $0.18 | $0.0504 / $0.1512 |
| [Ling 3.0 Tiny](https://martllm.com/models/inclusionai/ling-3.0-tiny) | text | $0.015 / $0.045 | $0.0126 / $0.0378 |
| [Ling 3.1 Flash 1019](https://martllm.com/models/inclusionai/ling-3.1-flash-1019) | text | – | $0.276 / $0.828 |
| [Schematron V2 Small](https://martllm.com/models/inference-net/schematron-v2-small) | text | $0.05 / $0.23 | $0.042 / $0.1932 |
| [Schematron V2 Turbo](https://martllm.com/models/inference-net/schematron-v2-turbo) | text | $0.03 / $0.15 | $0.0252 / $0.126 |
| [Interfaze Beta](https://martllm.com/models/interfaze/interfaze-beta) | text | – | $1.38 / $3.22 |
| [Kling 2.1 Pro](https://martllm.com/models/kling/kling-2-1-pro-image-to-video) | video | – | $0.0924 / sec |
| [Kling Image O1](https://martllm.com/models/kling/kling-image-o1) | image | – | $0.028 / image |
| [Kling Image O3 Edit](https://martllm.com/models/kling/kling-image-o3-edit) | image | $0.028 / image | $0.02666 / image |
| [Kling Image V3 Edit](https://martllm.com/models/kling/kling-image-v3-edit) | image | $0.028 / image | $0.02666 / image |
| [Kling 4.0 Flash Edit](https://martllm.com/models/kling/kling-v4-flash-video-to-video) | video | $0 / sec | $0 / sec |
| [Kling 4.0 Edit](https://martllm.com/models/kling/kling-v4-video-to-video) | video | $0 / sec | $0 / sec |
| [Krea V2 Medium Turbo Text To Image](https://martllm.com/models/krea/krea-v2-medium-turbo-text-to-image) | image | – | $0.015 / image |
| [V3 Edit](https://martllm.com/models/krea/v3-edit) | image | $0.03 / image | $0.02856 / image |
| [Mi:dm K 3.0 Pro](https://martllm.com/models/kt/midm-k-3.0-pro) | text | $0.20 / $0.80 | $0.168 / $0.672 |
| [LTX 2.5 Fast](https://martllm.com/models/lightricks/ltx-2-5-fast) | video | – | $0.0567 / sec |
| [LTX 2.5 Pro](https://martllm.com/models/lightricks/ltx-2-5-pro) | video | – | $0.0756 / sec |
| [LFM3-1.7B](https://martllm.com/models/liquid/lfm-3-1.7b) | text | $0.08 / $0.20 | $0.0672 / $0.168 |
| [Photon](https://martllm.com/models/luma/photon) | image | – | $0.015 / image |
| [Photon Flash](https://martllm.com/models/luma/photon-flash) | image | – | $0.005 / image |
| [Uni V1 Edit](https://martllm.com/models/luma/uni-v1-edit) | image | $0.042 / image | $0.03998 / image |
| [Weaver (alpha)](https://martllm.com/models/mancer/weaver) | text | $0.30 / $0.50 | $0.252 / $0.42 |
| [Meituan: LongCat 2.5](https://martllm.com/models/meituan/longcat-2.5) | text | – | $0.276 / $1.10 |
| [Llama 3.1 70B Instruct](https://martllm.com/models/meta-llama/llama-3.1-70b) | text | $0.72 / $0.72 | $0.6624 / $0.6624 |
| [Llama 3.1 70B Instruct](https://martllm.com/models/meta-llama/llama-3.1-70b-instruct) | text | $0.72 / $0.72 | $0.6048 / $0.6048 |
| [Llama 3.1 8B Instruct](https://martllm.com/models/meta-llama/llama-3.1-8b-instruct) | text | $0.05 / $0.08 | $0.042 / $0.0672 |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b) | text | $0.71 / $0.71 | $0.6624 / $0.6624 |
| [Llama 4 Maverick](https://martllm.com/models/meta-llama/llama-4-maverick) | text | $0.35 / $1.00 | $0.294 / $0.84 |
| [Llama 4 Scout](https://martllm.com/models/meta-llama/llama-4-scout) | text | $0.10 / $0.30 | $0.084 / $0.252 |
| [Llama Guard 4 12B](https://martllm.com/models/meta-llama/llama-guard-4-12b) | text | $0.18 / $0.18 | $0.1512 / $0.1512 |
| [Muse Video](https://martllm.com/models/meta-llama/muse-video) | video | – | $0.002352 / sec |
| [Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder-1.0) | text | – | $3.68 / $18.40 |
| [MAI-Transcribe 2](https://martllm.com/models/microsoft/mai-transcribe-2) | transcription | – | $0.001668 / minute |
| [Phi 4](https://martllm.com/models/microsoft/phi-4) | text | $0.07 / $0.14 | $0.0588 / $0.1176 |
| [H3 Image Highspeed Edit](https://martllm.com/models/minimax/h3-image-highspeed-edit) | image | $0.055 / image | $0.05236 / image |
| [Image 01 Image To Image](https://martllm.com/models/minimax/image-01-image-to-image) | image | – | $0.0035 / image |
| [Voxtral Mini Transcribe 3](https://martllm.com/models/mistral/voxtral-mini-transcribe-3) | transcription | – | $0.003501 / minute |
| [Mistral Codestral](https://martllm.com/models/mistralai/codestral) | text | – | $0.276 / $0.828 |
| [Codestral 2508](https://martllm.com/models/mistralai/codestral-2508) | text | $0.30 / $0.90 | $0.252 / $0.756 |
| [Devstral 2 2512](https://martllm.com/models/mistralai/devstral-2512) | text | $0.40 / $2.00 | $0.336 / $1.68 |
| [Ministral 14B](https://martllm.com/models/mistralai/ministral-14b) | text | $0.20 / $0.20 | $0.184 / $0.184 |
| [Ministral 3 14B 2512](https://martllm.com/models/mistralai/ministral-14b-2512) | text | $0.20 / $0.20 | $0.168 / $0.168 |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3b) | text | $0.10 / $0.10 | $0.092 / $0.092 |
| [Ministral 3 3B 2512](https://martllm.com/models/mistralai/ministral-3b-2512) | text | $0.10 / $0.10 | $0.084 / $0.084 |
| [Ministral 8B](https://martllm.com/models/mistralai/ministral-8b) | text | $0.15 / $0.15 | $0.138 / $0.138 |
| [Ministral 3 8B 2512](https://martllm.com/models/mistralai/ministral-8b-2512) | text | $0.15 / $0.15 | $0.126 / $0.126 |
| [Mistral Large 2407](https://martllm.com/models/mistralai/mistral-large-2407) | text | $2.00 / $6.00 | $1.68 / $5.04 |
| [Mistral Large 3 2512](https://martllm.com/models/mistralai/mistral-large-2512) | text | – | $0.42 / $1.26 |
| [Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4) | text | – | $0.644 / $1.93 |
| [Mistral Medium Latest](https://martllm.com/models/mistralai/mistral-medium-3.5) | text | – | $1.26 / $6.30 |
| [Mistral Nemo 12B](https://martllm.com/models/mistralai/mistral-nemo) | text | $0.029 / $0.03 | $0.02436 / $0.0252 |
| [Saba](https://martllm.com/models/mistralai/mistral-saba) | text | $0.20 / $0.60 | $0.168 / $0.504 |
| [Mistral Small](https://martllm.com/models/mistralai/mistral-small) | text | – | $0.138 / $0.552 |
| [Mistral Small 3](https://martllm.com/models/mistralai/mistral-small-24b-instruct-2501) | text | $0.05 / $0.08 | $0.042 / $0.0672 |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-2603) | text | $0.15 / $0.60 | $0.126 / $0.504 |
| [Mistral Small 3.1 24B](https://martllm.com/models/mistralai/mistral-small-3.1-24b-instruct) | text | $0.351 / $0.555 | $0.2948 / $0.4662 |
| [Mixtral 8x22B Instruct](https://martllm.com/models/mistralai/mixtral-8x22b-instruct) | text | $2.00 / $6.00 | $1.68 / $5.04 |
| [Toast 1](https://martllm.com/models/mixedbread/toast-1) | text | – | $0.276 / $0.6624 |
| [Kimi K2.7 Code High Speed](https://martllm.com/models/moonshotai/kimi-k2.7-code-highspeed) | text | – | $1.75 / $7.36 |
| [Morph V3 Fast](https://martllm.com/models/morph/morph-v3-fast) | text | $0.80 / $1.20 | $0.672 / $1.01 |
| [Morph V3 Large](https://martllm.com/models/morph/morph-v3-large) | text | $0.90 / $1.90 | $0.756 / $1.60 |
| [Motif 3](https://martllm.com/models/motif-technologies/motif-3) | text | $0.30 / $1.20 | $0.252 / $1.01 |
| [Nex-N2.5-Mini](https://martllm.com/models/nex-agi/nex-n2.5-mini) | text | $0.025 / $0.10 | $0.021 / $0.084 |
| [Nex-N2.5-Pro](https://martllm.com/models/nex-agi/nex-n2.5-pro) | text | $0.075 / $0.25 | $0.063 / $0.21 |
| [Nex-N2.6](https://martllm.com/models/nex-agi/nex-n2.6) | text | $0.12 / $0.40 | $0.1008 / $0.336 |
| [Hermes 4 405B](https://martllm.com/models/nousresearch/hermes-4-405b) | text | $1.00 / $3.00 | $0.84 / $2.52 |
| [Cosmos 3 Super Text To Image](https://martllm.com/models/nvidia/cosmos-3-super-text-to-image) | image | – | $0.04 / image |
| [NVIDIA Nemotron 3 Super 120B A12B](https://martllm.com/models/nvidia/nemotron-3-super-120b-a12b) | text | $0.075 / $0.40 | $0.063 / $0.336 |
| [Nemotron 3.5 Content Safety](https://martllm.com/models/nvidia/nemotron-3.5-content-safety) | text | – | $0.168 / $0.168 |
| [Nemotron 3.5 Lightning](https://martllm.com/models/nvidia/nemotron-3.5-lightning) | text | $0.07 / $0.20 | $0.0588 / $0.168 |
| [Nvidia Nemotron Nano 12B V2 VL](https://martllm.com/models/nvidia/nemotron-nano-12b-v2-vl) | text | – | $0.184 / $0.552 |
| [DALL-E 3](https://martllm.com/models/openai/dall-e-3) | image | – | $0.032 / image |
| [GPT-3.5 Turbo (older v0613)](https://martllm.com/models/openai/gpt-3.5-turbo-0613) | text | $1.00 / $2.00 | $0.84 / $1.68 |
| [GPT-3.5 Turbo 16k](https://martllm.com/models/openai/gpt-3.5-turbo-16k) | text | – | $2.52 / $3.36 |
| [GPT-4](https://martllm.com/models/openai/gpt-4) | text | $30.00 / $60.00 | $25.20 / $50.40 |
| [GPT-4.1](https://martllm.com/models/openai/gpt-4.1) | text | $2.00 / $8.00 | $1.51 / $6.05 |
| [GPT-4.1 (Fast)](https://martllm.com/models/openai/gpt-4.1-fast) | text | – | $3.22 / $12.88 |
| [GPT-4.1 mini](https://martllm.com/models/openai/gpt-4.1-mini) | text | $0.40 / $1.60 | $0.3024 / $1.21 |
| [GPT-4.1 mini (Fast)](https://martllm.com/models/openai/gpt-4.1-mini-fast) | text | – | $0.644 / $2.58 |
| [GPT-4.1 nano](https://martllm.com/models/openai/gpt-4.1-nano) | text | $0.10 / $0.40 | $0.084 / $0.336 |
| [GPT-4o (2024-05-13)](https://martllm.com/models/openai/gpt-4o-2024-05-13) | text | $5.00 / $15.00 | $4.20 / $12.60 |
| [GPT-4o (2024-08-06)](https://martllm.com/models/openai/gpt-4o-2024-08-06) | text | $2.50 / $10.00 | $2.10 / $8.40 |
| [GPT-4o (2024-11-20)](https://martllm.com/models/openai/gpt-4o-2024-11-20) | text | $2.50 / $10.00 | $1.89 / $7.56 |
| [GPT-4o (Fast)](https://martllm.com/models/openai/gpt-4o-fast) | text | – | $3.91 / $15.64 |
| [GPT-4o-mini (2024-07-18)](https://martllm.com/models/openai/gpt-4o-mini-2024-07-18) | text | $0.15 / $0.60 | $0.126 / $0.504 |
| [GPT-4o mini (Fast)](https://martllm.com/models/openai/gpt-4o-mini-fast) | text | – | $0.23 / $0.92 |
| [GPT-5](https://martllm.com/models/openai/gpt-5) | text | $1.25 / $10.00 | $0.945 / $7.56 |
| [GPT-5-Codex](https://martllm.com/models/openai/gpt-5-codex) | text | – | $1.15 / $9.20 |
| [GPT-5 (Fast)](https://martllm.com/models/openai/gpt-5-fast) | text | – | $2.30 / $18.40 |
| [GPT-5 mini (Fast)](https://martllm.com/models/openai/gpt-5-mini-fast) | text | – | $0.414 / $3.31 |
| [GPT-5 pro](https://martllm.com/models/openai/gpt-5-pro) | text | $15.00 / $120.00 | $11.34 / $90.72 |
| [GPT-5.1](https://martllm.com/models/openai/gpt-5.1) | text | $1.25 / $10.00 | $0.945 / $7.56 |
| [GPT-5.1-Codex](https://martllm.com/models/openai/gpt-5.1-codex) | text | $1.25 / $10.00 | $1.05 / $8.40 |
| [GPT 5.1 Codex Max](https://martllm.com/models/openai/gpt-5.1-codex-max) | text | $1.25 / $10.00 | $1.05 / $8.40 |
| [GPT 5.1 Codex Mini](https://martllm.com/models/openai/gpt-5.1-codex-mini) | text | $0.25 / $2.00 | $0.21 / $1.68 |
| [GPT 5.1 Thinking (Fast)](https://martllm.com/models/openai/gpt-5.1-thinking-fast) | text | – | $2.30 / $18.40 |
| [GPT 5.2 (Fast)](https://martllm.com/models/openai/gpt-5.2-fast) | text | – | $3.22 / $25.76 |
| [GPT 5.2](https://martllm.com/models/openai/gpt-5.2-pro) | text | $21.00 / $168.00 | $15.88 / $127.01 |
| [GPT 5.3 Codex (Fast)](https://martllm.com/models/openai/gpt-5.3-codex-fast) | text | – | $3.22 / $25.76 |
| [GPT 5.4 (Fast)](https://martllm.com/models/openai/gpt-5.4-fast) | text | – | $4.60 / $27.60 |
| [GPT 5.4 Mini (Fast)](https://martllm.com/models/openai/gpt-5.4-mini-fast) | text | – | $1.38 / $8.28 |
| [GPT 5.5 (Fast)](https://martllm.com/models/openai/gpt-5.5-fast) | text | – | $11.50 / $69.00 |
| [GPT 5.6 Luna (Fast)](https://martllm.com/models/openai/gpt-5.6-luna-fast) | text | – | $0.368 / $2.21 |
| [GPT 5.6 Sol (Fast)](https://martllm.com/models/openai/gpt-5.6-sol-fast) | text | – | $7.36 / $36.80 |
| [GPT 5.6 Terra (Fast)](https://martllm.com/models/openai/gpt-5.6-terra-fast) | text | – | $3.68 / $22.08 |
| [GPT-6 Astra (Fast)](https://martllm.com/models/openai/gpt-6-astra-fast) | text | – | $18.40 / $92.00 |
| [GPT-6 Astra Pro](https://martllm.com/models/openai/gpt-6-astra-pro) | text | $10.00 / $50.00 | $8.40 / $42.00 |
| [GPT-6 Luna (Fast)](https://martllm.com/models/openai/gpt-6-luna-fast) | text | – | $0.184 / $0.92 |
| [GPT-6 Sol (Fast)](https://martllm.com/models/openai/gpt-6-sol-fast) | text | – | $3.68 / $18.40 |
| [GPT-6.1 Sol (Fast)](https://martllm.com/models/openai/gpt-6.1-sol-fast) | text | – | $3.68 / $18.40 |
| [GPT-6.1 Terra (Fast)](https://martllm.com/models/openai/gpt-6.1-terra-fast) | text | – | $1.84 / $9.20 |
| [OpenAI: GPT-6.1 Terra Pro (batch)](https://martllm.com/models/openai/gpt-6.1-terra-pro:batch) | text | – | $0.42 / $2.10 |
| [OpenAI: GPT-6.1 Terra (batch)](https://martllm.com/models/openai/gpt-6.1-terra:batch) | text | – | $0.42 / $2.10 |
| [GPT-6.2 Astra (Fast)](https://martllm.com/models/openai/gpt-6.2-astra-fast) | text | – | $14.72 / $73.60 |
| [GPT-6.2 Sol (Fast)](https://martllm.com/models/openai/gpt-6.2-sol-fast) | text | – | $3.68 / $18.40 |
| [GPT Chat Latest](https://martllm.com/models/openai/gpt-chat-latest) | text | $5.00 / $30.00 | $4.20 / $25.20 |
| [GPT Image 1](https://martllm.com/models/openai/gpt-image-1) | image | – | $0.1997 / image |
| [GPT Image 2.6](https://martllm.com/models/openai/gpt-image-2-6) | image | – | $0.0055 / image |
| [GPT Image 2.6 Economy](https://martllm.com/models/openai/gpt-image-2-6-economy) | image | – | $0.02625 / image |
| [GPT Transcribe](https://martllm.com/models/openai/gpt-transcribe) | transcription | – | $0.0045 / minute |
| [o1](https://martllm.com/models/openai/o1) | text | – | $13.80 / $55.20 |
| [o3](https://martllm.com/models/openai/o3) | text | $2.00 / $8.00 | $1.51 / $6.05 |
| [o3 (Fast)](https://martllm.com/models/openai/o3-fast) | text | – | $3.22 / $12.88 |
| [o3-mini](https://martllm.com/models/openai/o3-mini) | text | – | $1.01 / $4.05 |
| [o3 Pro](https://martllm.com/models/openai/o3-pro) | text | $20.00 / $80.00 | $15.12 / $60.48 |
| [o4-mini](https://martllm.com/models/openai/o4-mini) | text | – | $1.01 / $4.05 |
| [Ultramarine 1 Flash](https://martllm.com/models/paperinstruments/ultramarine-1-flash) | text | – | $0.138 / $0.46 |
| [Perceptron Mk1](https://martllm.com/models/perceptron/perceptron-mk1) | text | $0.15 / $1.50 | $0.126 / $1.26 |
| [Perceptron Mk1.5](https://martllm.com/models/perceptron/perceptron-mk1.5) | text | $0.15 / $1.50 | $0.126 / $1.26 |
| [Sonar](https://martllm.com/models/perplexity/sonar) | text | – | $0.84 / $0.84 |
| [Sonar Deep Research](https://martllm.com/models/perplexity/sonar-deep-research) | text | $2.00 / $8.00 | $1.68 / $6.72 |
| [Sonar Pro](https://martllm.com/models/perplexity/sonar-pro) | text | $3.00 / $15.00 | $2.52 / $12.60 |
| [Sonar Pro Search](https://martllm.com/models/perplexity/sonar-pro-search) | text | $3.00 / $15.00 | $2.52 / $12.60 |
| [Sonar Reasoning Pro](https://martllm.com/models/perplexity/sonar-reasoning-pro) | text | $2.00 / $8.00 | $1.68 / $6.72 |
| [Ternary Bonsai 2 27B](https://martllm.com/models/prism-ml/ternary-bonsai-2-27b) | text | $0.075 / $0.50 | $0.063 / $0.42 |
| [Ternary Bonsai 2 9B](https://martllm.com/models/prism-ml/ternary-bonsai-2-9b) | text | $0.08 / $0.13 | $0.0672 / $0.1092 |
| [P Image Edit](https://martllm.com/models/pruna-ai/p-image-edit) | image | $0.01 / image | $0.00952 / image |
| [Arrow 2](https://martllm.com/models/quiverai/arrow-2) | text | – | $3.68 / $18.40 |
| [Arrow 2 Telos](https://martllm.com/models/quiverai/arrow-2-telos) | text | – | $5.52 / $27.60 |
| [Qwen2.5 Coder 32B Instruct](https://martllm.com/models/qwen/qwen-2.5-coder-32b-instruct) | text | $0.66 / $1.00 | $0.5544 / $0.84 |
| [Qwen3-14B](https://martllm.com/models/qwen/qwen-3-14b) | text | – | $0.1008 / $0.2016 |
| [Qwen3-30B-A3B](https://martllm.com/models/qwen/qwen-3-30b) | text | – | $0.1104 / $0.46 |
| [Qwen Image Edit 2509 Multiple Angles](https://martllm.com/models/qwen/qwen-image-edit-2509-multiple-angles) | image | $0.025 / image | $0.0238 / image |
| [Qwen Image Edit 2511](https://martllm.com/models/qwen/qwen-image-edit-2511) | image | $0.02 / image | $0.01904 / image |
| [Qwen Image Edit Plus](https://martllm.com/models/qwen/qwen-image-edit-plus) | image | $0.02 / image | $0.01904 / image |
| [Qwen Image Max Edit](https://martllm.com/models/qwen/qwen-image-max-edit) | image | $0.07 / image | $0.06664 / image |
| [Qwen Image Text To Image 2512](https://martllm.com/models/qwen/qwen-image-text-to-image-2512) | image | – | $0.02 / image |
| [Qwen-Plus](https://martllm.com/models/qwen/qwen-plus) | text | $0.26 / $0.78 | $0.2184 / $0.6552 |
| [Qwen2.5 72B Instruct](https://martllm.com/models/qwen/qwen2.5-72b-instruct) | text | – | $0.3024 / $0.336 |
| [Qwen2.5 VL 72B Instruct](https://martllm.com/models/qwen/qwen2.5-vl-72b-instruct) | text | – | $0.672 / $0.84 |
| [Qwen3 30B A3B Instruct 2507](https://martllm.com/models/qwen/qwen3-30b-a3b-instruct-2507) | text | $0.10 / $0.30 | $0.084 / $0.252 |
| [Qwen 3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b) | text | – | $0.138 / $0.552 |
| [Qwen3 Coder Flash](https://martllm.com/models/qwen/qwen3-coder-flash) | text | $0.195 / $0.975 | $0.1638 / $0.819 |
| [Qwen3 VL 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-vl-30b-a3b-instruct) | text | $0.15 / $0.60 | $0.126 / $0.504 |
| [Qwen3 VL 8B Instruct](https://martllm.com/models/qwen/qwen3-vl-8b-instruct) | text | $0.25 / $0.75 | $0.21 / $0.63 |
| [Qwen3 VL 235B A22B Instruct](https://martllm.com/models/qwen/qwen3-vl-instruct) | text | – | $0.184 / $0.8096 |
| [Qwen3.5-122B-A10B](https://martllm.com/models/qwen/qwen3.5-122b-a10b) | text | $0.26 / $2.08 | $0.2184 / $1.75 |
| [Qwen3.5-27B](https://martllm.com/models/qwen/qwen3.5-27b) | text | $0.26 / $2.60 | $0.2184 / $2.18 |
| [Qwen3.5-Flash](https://martllm.com/models/qwen/qwen3.5-flash-02-23) | text | $0.065 / $0.26 | $0.0546 / $0.2184 |
| [Qwen3.5 Plus 2026-02-15](https://martllm.com/models/qwen/qwen3.5-plus-02-15) | text | $0.26 / $1.56 | $0.2184 / $1.31 |
| [Qwen3.5 Plus 2026-04-20](https://martllm.com/models/qwen/qwen3.5-plus-20260420) | text | $0.30 / $1.80 | $0.252 / $1.51 |
| [Qwen3.6 Flash](https://martllm.com/models/qwen/qwen3.6-flash) | text | $0.1875 / $1.12 | $0.1296 / $0.7775 |
| [Qwen 3.6 Plus](https://martllm.com/models/qwen/qwen3.6-plus) | text | $0.325 / $1.95 | $0.2161 / $1.30 |
| [DaisyRose 27B](https://martllm.com/models/radixark/daisyrose-27b) | text | $0.15 / $1.88 | $0.126 / $1.57 |
| [Recraft 20b](https://martllm.com/models/recraft/recraft-20b) | image | – | $0.022 / image |
| [Recraft V4.1 Pro Text To Image](https://martllm.com/models/recraft/recraft-v4-1-pro-text-to-image) | image | – | $0.25 / image |
| [Reka Edge](https://martllm.com/models/rekaai/reka-edge) | text | $0.10 / $0.10 | $0.084 / $0.084 |
| [Reka Flash 3](https://martllm.com/models/rekaai/reka-flash-3) | text | $0.10 / $0.20 | $0.084 / $0.168 |
| [Relace Apply 3](https://martllm.com/models/relace/relace-apply-3) | text | $0.85 / $1.25 | $0.714 / $1.05 |
| [Relace Search](https://martllm.com/models/relace/relace-search) | text | $1.00 / $3.00 | $0.84 / $2.52 |
| [Ripple 65B Preview](https://martllm.com/models/ricursiveai/ripple-65b-preview) | text | $0.10 / $0.30 | $0.084 / $0.252 |
| [Aleph2](https://martllm.com/models/runway/aleph2) | video | – | $0.28 / sec |
| [Fugu Ultra](https://martllm.com/models/sakana/fugu-ultra) | text | $5.00 / $30.00 | $4.20 / $25.20 |
| [Sakana Namazu](https://martllm.com/models/sakana/namazu) | text | – | $0.874 / $3.68 |
| [MAGI-2](https://martllm.com/models/sand-ai/magi-2) | video | $0.088 / sec | $0.07616 / sec |
| [MAGI-2 Reference to Video](https://martllm.com/models/sand-ai/magi-2-reference-to-video) | video | – | $0.0924 / sec |
| [Llama 3 8B Lunaris](https://martllm.com/models/sao10k/l3-lunaris-8b) | text | $0.04 / $0.05 | $0.0336 / $0.042 |
| [Llama 3.1 Euryale 70B v2.2](https://martllm.com/models/sao10k/l3.1-euryale-70b) | text | $0.85 / $0.85 | $0.714 / $0.714 |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-v1-1-sound-effects) | music | – | $0.00207 / sec |
| [Riverflow 2.0 Pro Edit](https://martllm.com/models/sourceful/riverflow-2-0-pro-edit) | image | $0.15 / image | $0.1428 / image |
| [Step 3.7 Flash](https://martllm.com/models/stepfun/step-3.7-flash) | text | $0.20 / $1.15 | $0.1458 / $0.8745 |
| [Hunyuan Image 2.1](https://martllm.com/models/tencent/hunyuan-image-2-1) | image | – | $0.025 / image |
| [Hunyuan Image 3 Instruct Edit](https://martllm.com/models/tencent/hunyuan-image-3-instruct-edit) | image | $0.45 / image | $0.4284 / image |
| [Hy-MT2-1.8B](https://martllm.com/models/tencent/hy-mt2-1.8b) | text | $0.044 / $0.177 | $0.03696 / $0.1487 |
| [Hy-MT2-30B-A3B](https://martllm.com/models/tencent/hy-mt2-30b-a3b) | text | $0.074 / $0.295 | $0.06216 / $0.2478 |
| [Hy-MT2-7B](https://martllm.com/models/tencent/hy-mt2-7b) | text | $0.074 / $0.295 | $0.06216 / $0.2478 |
| [Tencent Hy-MT2-Lite](https://martllm.com/models/tencent/hy-mt2-lite) | text | – | $0.04048 / $0.1628 |
| [Tencent Hy-MT2-Plus](https://martllm.com/models/tencent/hy-mt2-plus) | text | – | $0.06808 / $0.2714 |
| [Tencent Hy-MT2-Pro](https://martllm.com/models/tencent/hy-mt2-pro) | text | – | $0.06808 / $0.2714 |
| [Tencent: Hy4 preview](https://martllm.com/models/tencent/hy4-preview) | text | $0.834 / $2.50 | $0.613 / $1.84 |
| [Cydonia 24B V4.1](https://martllm.com/models/thedrummer/cydonia-24b-v4.1) | text | $0.30 / $0.50 | $0.252 / $0.42 |
| [Skyfall 36B V2](https://martllm.com/models/thedrummer/skyfall-36b-v2) | text | $0.55 / $0.80 | $0.462 / $0.672 |
| [UnslopNemo 12B](https://martllm.com/models/thedrummer/unslopnemo-12b) | text | $0.40 / $0.40 | $0.336 / $0.336 |
| [Inkling Small](https://martllm.com/models/thinking-machines/inkling-small) | text | – | $0.378 / $1.01 |
| [DeepSeek R1T2 Chimera](https://martllm.com/models/tngtech/deepseek-r1t2-chimera) | text | $1.00 / $2.62 | $0.84 / $2.21 |
| [ReMM SLERP 13B](https://martllm.com/models/undi95/remm-slerp-l2-13b) | text | $0.30 / $0.50 | $0.252 / $0.42 |
| [Solar Mini 4.5](https://martllm.com/models/upstage/solar-mini-4-5) | text | $0.01 / $0.04 | $0.0084 / $0.0336 |
| [Solar Mini 4](https://martllm.com/models/upstage/solar-mini4) | text | $0.05 / $0.20 | $0.042 / $0.168 |
| [Solar Pro 4 Contributor](https://martllm.com/models/upstage/solar-pro-4-contributor) | text | $0.09 / $0.36 | $0.0756 / $0.3024 |
| [Solar Pro 4](https://martllm.com/models/upstage/solar-pro4) | text | $0.15 / $0.60 | $0.126 / $0.504 |
| [Reference To Image Q2](https://martllm.com/models/vidu/reference-to-image-q2) | image | – | $0.04 / image |
| [Wan 2.1 Text To Image](https://martllm.com/models/wan/wan-2-1-text-to-image) | image | – | $0.02 / image |
| [Wan 2.2 Image To Image](https://martllm.com/models/wan/wan-2-2-image-to-image) | image | – | $0.02 / image |
| [Wan 2.2 Text To Image Realism](https://martllm.com/models/wan/wan-2-2-text-to-image-realism) | image | – | $0.025 / image |
| [Wan 2.5 Image Edit](https://martllm.com/models/wan/wan-2-5-image-edit) | image | $0.035 / image | $0.03332 / image |
| [Wan 2.6 Image Edit](https://martllm.com/models/wan/wan-2-6-image-edit) | image | $0.035 / image | $0.03332 / image |
| [Wan 2.7 Edit](https://martllm.com/models/wan/wan-2-7-video-to-video) | video | $0 / sec | $0 / sec |
| [Wan2.7 Videoedit](https://martllm.com/models/wan/wan2-7-videoedit) | video | – | $0.1096 / sec |
| [Palmyra X5](https://martllm.com/models/writer/palmyra-x5) | text | $0.60 / $6.00 | $0.504 / $5.04 |
| [Grok 2 Image](https://martllm.com/models/x-ai/grok-2-image) | image | – | $0.07 / image |
| [Grok 4.20](https://martllm.com/models/x-ai/grok-4.20) | text | $1.25 / $2.50 | $1.05 / $2.10 |
| [Grok 4.20 Multi-Agent](https://martllm.com/models/x-ai/grok-4.20-multi-agent) | text | $1.25 / $2.50 | $1.05 / $2.10 |
| [Grok 4.20 Beta Non-Reasoning](https://martllm.com/models/x-ai/grok-4.20-non-reasoning-beta) | text | – | $1.15 / $2.30 |
| [Grok 4.20 Beta Reasoning](https://martllm.com/models/x-ai/grok-4.20-reasoning-beta) | text | – | $1.15 / $2.30 |
| [Grok STT](https://martllm.com/models/x-ai/grok-stt) | transcription | – | $0.00168 / minute |
| [MiMo-V2.6-Flash-MOPD](https://martllm.com/models/xiaomi/mimo-v2.6-flash-mopd) | text | $0.50 / $1.00 | $0.525 / $1.05 |
| [GLM 4.5V](https://martllm.com/models/z-ai/glm-4.5v) | text | $0.60 / $1.80 | $0.504 / $1.51 |
| [GLM 4.6V](https://martllm.com/models/z-ai/glm-4.6v) | text | $0.30 / $0.90 | $0.252 / $0.756 |
| [GLM 4.7 FlashX](https://martllm.com/models/z-ai/glm-4.7-flashx) | text | – | $0.0552 / $0.368 |
| [Glm Image Edit](https://martllm.com/models/z-ai/glm-image-edit) | image | $0.12 / image | $0.1142 / image |

**No longer listed (12)**: `bytedance/seedance-2-0-enhanced-reference-to-video`, `bytedance/seedance-2-0-mini-enhanced-reference-to-video`, `bytedance/venice-seedance-2-5-us-image-to-video-private`, `bytedance/venice-seedance-2-5-us-reference-to-video-private`, `bytedance/venice-seedance-2-5-us-text-to-video-private`, `google/gemini-3-5-flash-lite`, `google/veo3-full-image-to-video`, `lightricks/ltx-2-full-image-to-video`, `openai/gpt-6-luna-decisions`, `typesafe/jev-1.13`, `typesafe/jev-1.14`, `venice/imagineart-1.5-pro`

<details><summary>MartLLM price moves of 10% or more (186)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GPT Image 2.5 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-flare) | image | $0.06615 / image | $0.0055 / image | −92% |
| [GPT Image 2.5 Sunburst (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-sunburst) | image | $0.055 / image | $0.0055 / image | −90% |
| [Gemini 3.1 Pro](https://martllm.com/models/google/gemini-3.1-pro) | text | $2.06 / $12.35 | $0.2305 / $1.38 | −89% |
| [MiniMax H3 Image (image-to-image)](https://martllm.com/models/minimax/venice-minimax-h3-image-edit) | image | $0.063 / image | $0.00945 / image | −85% |
| [LTX 2 19B Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-19b-full-text-to-video) | video | $0.0924 / sec | $0.01523 / sec | −84% |
| [Wan 2.2 A14B Text-to-Video](https://martllm.com/models/wan/wan-2-2-a14b-text-to-video) | video | $0.218 / sec | $0.042 / sec | −81% |
| [Qwen3.5 Flash](https://martllm.com/models/qwen/qwen3.5-flash) | text | $0.1029 / $0.4116 | $0.02084 / $0.08337 | −80% |
| [Qwen3.5 Plus](https://martllm.com/models/qwen/qwen3.5-plus) | text | $0.2675 / $1.61 | $0.05419 / $0.3251 | −80% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | text | $0.1592 / $1.58 | $0.0336 / $0.336 | −79% |
| [Nano Banana 2 Lite (image-to-image)](https://martllm.com/models/google/nano-banana-2-lite-edit) | image | $0.04347 / image | $0.011 / image | −75% |
| [Ideogram V4.5 (Venice)](https://martllm.com/models/ideogram/venice-ideogram-v4-5) | image | $0.2047 / image | $0.05712 / image | −72% |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | text | $0.882 / $2.77 | $0.2499 / $0.9207 | in −72% / out −67% |
| [MiniMax H3 Image](https://martllm.com/models/minimax/venice-minimax-h3-image) | image | $0.0315 / image | $0.00945 / image | −70% |
| [Krea 2 Turbo (Venice)](https://martllm.com/models/krea/venice-krea-2-turbo) | image | $0.0378 / image | $0.01142 / image | −70% |
| [Seedream V5 Lite (Venice)](https://martllm.com/models/venice/seedream-v5-lite) | image | $0.03675 / image | $0.01176 / image | −68% |
| [Grok Imagine (Venice)](https://martllm.com/models/venice/grok-imagine) | image | $0.01523 / image | $0.0055 / image | −64% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | text | $0.2677 / $1.61 | $0.1103 / $0.6615 | −59% |
| [GPT Image 2.5 Flare (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-flare-edit) | image | $0.0756 / image | $0.0315 / image | −58% |
| [GPT Image 2.5 Sunburst (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-sunburst-edit) | image | $0.0756 / image | $0.0315 / image | −58% |
| [Ideogram V4.6](https://martllm.com/models/ideogram/ideogram-v4-6) | image | $0.1362 / image | $0.05712 / image | −58% |
| [Nano Banana 2 Lite (Venice)](https://martllm.com/models/google/venice-nano-banana-2-lite) | image | $0.04725 / image | $0.021 / image | −56% |
| [Seedream 4.5](https://martllm.com/models/bytedance/seedream-4.5) | image | $0.0294 / image | $0.01344 / image | −54% |
| [Veo 3.1 Full Text-to-Video](https://martllm.com/models/google/veo3-1-full-text-to-video) | video | $0.3465 / sec | $0.1613 / sec | −53% |
| [Runway Gen-4 Aleph](https://martllm.com/models/runway/runway-gen4-aleph) | video | $0.545 / sec | $0.2625 / sec | −52% |
| [Veo3.1 Full (image-to-video)](https://martllm.com/models/google/veo3-1-full-image-to-video) | video | $0.3234 / sec | $0.1613 / sec | −50% |
| [Z-Image Turbo (Venice)](https://martllm.com/models/venice/z-image-turbo) | image | $0.0084 / image | $0.0042 / image | −50% |
| [MiniMax Music 2.6 (Venice)](https://martllm.com/models/venice/minimax-music-v26) | music | $0.2616 / track | $0.1317 / track | −50% |
| [Veo3.1 Fast (image-to-video)](https://martllm.com/models/google/veo3-1-fast-image-to-video) | video | $0.1559 / sec | $0.07875 / sec | −49% |
| [MiniMax H3](https://martllm.com/models/minimax/minimax-h3) | video | $0.05437 / sec | $0.0275 / sec | −49% |
| [MiniMax M2.7 Highspeed](https://martllm.com/models/minimax/minimax-m2.7-highspeed) | text | $0.6174 / $2.47 | $0.315 / $1.26 | −49% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | text | $0.756 / $3.78 | $0.399 / $2.00 | −47% |
| [NVIDIA Nemotron 3 Super 120B](https://martllm.com/models/nvidia/nemotron-3-super-120b) | text | $0.02441 / $0.1302 | $0.01339 / $0.0714 | −45% |
| [GPT OSS 20B](https://martllm.com/models/openai/e2ee-gpt-oss-20b-p) | text | $0.04725 / $0.1795 | $0.02625 / $0.09975 | −44% |
| [Hailuo 2.3 Standard](https://martllm.com/models/minimax/hailuo-2-3-standard-image-to-video) | video | $0.04645 / sec | $0.02625 / sec | −43% |
| [Gemma 3 27B](https://martllm.com/models/google/gemma-3-27b-it) | text | $0.03864 / $0.0966 | $0.02268 / $0.0567 | −41% |
| [Pixverse V5.6 (image-to-video)](https://martllm.com/models/pixverse/pixverse-v5-6-image-to-video) | video | $0.1061 / sec | $0.06664 / sec | −37% |
| [Seedance 1.0 Pro Fast](https://martllm.com/models/bytedance/seedance-1-0-pro-fast-image-to-video) | video | $0.018 / sec | $0.01142 / sec | −37% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.02835 / $0.1263 | $0.0189 / $0.08392 | in −33% / out −34% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | text | $0.04961 / $0.04961 | $0.03308 / $0.03308 | −33% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | text | $0.0756 / $0.378 | $0.0504 / $0.252 | −33% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | text | $0.0945 / $0.2835 | $0.063 / $0.189 | −33% |
| [Qwen3 Coder Next](https://martllm.com/models/qwen/qwen3-coder-next) | text | $0.03402 / $0.2268 | $0.02268 / $0.1512 | −33% |
| [Gemini Omni Flash 1.1](https://martllm.com/models/google/gemini-omni-flash-1-1) | video | $0.0357 / sec | $0.02419 / sec | −32% |
| [GPT Image 2.6 Sunburst (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-sunburst) | image | $0.0693 / image | $0.0476 / image | −31% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.02593 / $0.3003 | $0.01795 / $0.2079 | −31% |
| [GPT Image 1.5 (Venice)](https://martllm.com/models/venice/gpt-image-1.5) | image | $0.1774 / image | $0.1229 / image | −31% |
| [GPT Image 2.6 Sunburst (image-to-image)](https://martllm.com/models/openai/venice-gpt-image-2-6-sunburst-edit) | image | $0.08925 / image | $0.06188 / image | −31% |
| [Kling Image 4.0 (image-to-image)](https://martllm.com/models/kling/venice-kling-v4-image-edit) | image | $0.084 / image | $0.05998 / image | −29% |
| [MiniMax M3.1 Flash](https://martllm.com/models/minimax/minimax-m3-1-flash) | text | $0.02205 / $0.0882 | $0.01575 / $0.063 | −29% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | text | $0.1617 / $0.8085 | $0.1155 / $0.5775 | −29% |
| [Kling O3 Standard (reference-to-video)](https://martllm.com/models/kling/kling-o3-standard-reference-to-video) | video | $0.1295 / sec | $0.0945 / sec | −27% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.01733 / $0.0693 | $0.0127 / $0.05082 | −27% |
| [Seedream V5 Pro (image-to-image)](https://martllm.com/models/bytedance/seedream-v5-pro-edit) | image | $0.03675 / image | $0.0275 / image | −25% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | text | $0.0819 / $0.315 | $0.06143 / $0.2362 | −25% |
| [Kling O3 Pro (reference-to-video)](https://martllm.com/models/kling/kling-o3-pro-reference-to-video) | video | $0.161 / sec | $0.1207 / sec | −25% |
| [Meta: Muse Spark 1.1](https://martllm.com/models/meta-llama/muse-spark-1.1) | text | $0.8006 / $2.72 | $0.6038 / $2.05 | −25% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | text | $0.2889 / $1.19 | $0.2184 / $0.9555 | in −24% / out −20% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | text | $0.1575 / $0.6562 | $0.1197 / $0.4988 | −24% |
| [MiniMax H3 Reference](https://martllm.com/models/minimax/minimax-h3-reference-to-video) | video | $0.05437 / sec | $0.042 / sec | −23% |
| [Meta: Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder) | text | $2.77 / $13.86 | $2.14 / $10.71 | −23% |
| [Gemini 3.1 Flash Lite](https://martllm.com/models/google/gemini-3.1-flash-lite) | text | $0.2415 / $1.45 | $0.189 / $1.13 | −22% |
| [Seedream V5.5 (image-to-image)](https://martllm.com/models/bytedance/venice-seedream-v5-5-edit) | image | $0.0241 / image | $0.0189 / image | −22% |
| [Nano Banana 2.1 (Venice)](https://martllm.com/models/google/venice-nano-banana-2-1) | image | $0.021 / image | $0.0165 / image | −21% |
| [Gemini Omni Flash (image-to-video)](https://martllm.com/models/google/gemini-omni-flash-image-to-video) | video | $0.1047 / sec | $0.08269 / sec | −21% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.0315 / $0.126 | $0.02593 / $0.09975 | in −18% / out −21% |
| [Wan 2.7 Pro (image-to-image)](https://martllm.com/models/wan/wan-2-7-pro-edit) | image | $0.07896 / image | $0.063 / image | −20% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | text | $0.05513 / $0.05513 | $0.0441 / $0.0441 | −20% |
| [Wan 2.7 (Venice)](https://martllm.com/models/venice/wan-2.7) | image | $0.0315 / image | $0.0252 / image | −20% |
| [Palmyra Vision 7B](https://martllm.com/models/writer/palmyra-vision-7b) | text | $0.04095 / $0.1638 | $0.03308 / $0.1323 | −19% |
| [Wan 2.7 (reference-to-video)](https://martllm.com/models/wan/wan-2-7-reference-to-video) | video | $0.104 / sec | $0.084 / sec | −19% |
| [Kling O3 Standard Text-to-Video](https://martllm.com/models/kling/kling-o3-standard-text-to-video) | video | $0.1164 / sec | $0.0945 / sec | −19% |
| [GPT-6 Luna](https://martllm.com/models/openai/gpt-6-luna) | text | $0.04515 / $0.2258 | $0.03675 / $0.1837 | −19% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | text | $0.0819 / $0.1638 | $0.0672 / $0.1344 | −18% |
| [GPT-5.5 Pro](https://martllm.com/models/openai/gpt-5.5-pro) | text | $21.11 / $126.63 | $17.32 / $103.95 | −18% |
| [Flux 3](https://martllm.com/models/black-forest-labs/flux-3-image-to-video) | video | $0.197 / sec | $0.1618 / sec | −18% |
| [Grok Imagine High Quality (Venice)](https://martllm.com/models/venice/grok-imagine-quality) | image | $0.03168 / image | $0.02625 / image | −17% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | text | $0.02268 / $0.06804 | $0.0189 / $0.0567 | −17% |
| [Kling O3 Pro Text-to-Video](https://martllm.com/models/kling/kling-o3-pro-text-to-video) | video | $0.1449 / sec | $0.1207 / sec | −17% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | text | $0.02646 / $0.02646 | $0.02205 / $0.02205 | −17% |
| [Kimi K3](https://martllm.com/models/moonshotai/kimi-k3) | text | $0.3685 / $1.89 | $0.3071 / $1.57 | −17% |
| [MiniMax M2](https://martllm.com/models/minimax/minimax-m2) | text | $0.0567 / $0.2268 | $0.04725 / $0.189 | −17% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | text | $0.0252 / $0.084 | $0.02142 / $0.0714 | −15% |
| [Wan 2.7 Pro (Venice)](https://martllm.com/models/venice/wan-2.7-pro) | image | $0.07383 / image | $0.063 / image | −15% |
| [Seedream V5.5 (Venice)](https://martllm.com/models/bytedance/venice-seedream-v5-5) | image | $0.022 / image | $0.0189 / image | −14% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | text | $1.71 / $5.61 | $1.47 / $4.83 | −14% |
| [FLUX.1 Kontext Max](https://martllm.com/models/black-forest-labs/flux-kontext-max) | image | $0.06092 / image | $0.0525 / image | −14% |
| [FLUX.1 Kontext Pro](https://martllm.com/models/black-forest-labs/flux-kontext-pro) | image | $0.03046 / image | $0.02625 / image | −14% |
| [Meta: Muse Spark 1.2](https://martllm.com/models/meta-llama/muse-spark-1.2) | text | $0.7219 / $2.45 | $0.63 / $2.14 | −13% |
| [Grok Imagine Pro (Venice)](https://martllm.com/models/venice/grok-imagine-pro) | image | $0.0419 / image | $0.03675 / image | −12% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | text | $0.01303 / $0.0798 | $0.01144 / $0.0756 | in −12% / out −5% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.0671 / $0.1864 | $0.06143 / $0.1638 | in −8% / out −12% |
| [Vidu Q4 Reference](https://martllm.com/models/vidu/vidu-q4-reference-to-video) | video | $0.04265 / sec | $0.0378 / sec | −11% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | text | $0.1304 / $0.3911 | $0.1158 / $0.3473 | −11% |
| [GPT-5.2](https://martllm.com/models/openai/gpt-5.2) | text | $0.6615 / $5.29 | $0.588 / $4.70 | −11% |
| [Seedance 2.0 Mini (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-image-to-video) | video | $0.01819 / sec | $0.01626 / sec | −11% |
| [Veo 3.1 Fast Text-to-Video](https://martllm.com/models/google/veo3-1-fast-text-to-video) | video | $0.088 / sec | $0.07875 / sec | −11% |
| [Kling 2.5 Turbo Pro Text-to-Video](https://martllm.com/models/kling/kling-2-5-turbo-pro-text-to-video) | video | $0.07371 / sec | $0.06615 / sec | −10% |
| [NVIDIA Nemotron 3 Ultra 550B](https://martllm.com/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.2166 / $1.08 | $0.2415 / $1.06 | in +12% / out −2% |
| [Seedance 2.0 Fast (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-fast-image-to-video) | video | $0.03593 / sec | $0.04016 / sec | +12% |
| [Seedance 2.0 Fast Text-to-Video (Venice)](https://martllm.com/models/venice/seedance-2-fast-t2v) | video | $0.03593 / sec | $0.04016 / sec | +12% |
| [Nano Banana Pro (image-to-image)](https://martllm.com/models/google/nano-banana-pro-edit) | image | $0.01804 / image | $0.02016 / image | +12% |
| [Nano Banana Pro (Venice)](https://martllm.com/models/venice/nano-banana-pro) | image | $0.01804 / image | $0.02016 / image | +12% |
| [Reflection: Beam 1.0 501B A23B](https://martllm.com/models/reflection/beam-1.0-501b-a23b) | text | $0.3276 / $0.9828 | $0.3612 / $1.10 | in +10% / out +12% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | text | $0.21 / $0.84 | $0.2362 / $0.945 | +12% |
| [xAI Speech to Text v1 (Venice)](https://martllm.com/models/venice/xai-stt-v1) | transcription | $0.001874 / minute | $0.002115 / minute | +13% |
| [Qwen 2.5 7B](https://martllm.com/models/qwen/e2ee-qwen-2-5-7b-p) | text | $0.03623 / $0.09419 | $0.04095 / $0.1065 | +13% |
| [Llama 3.2 3B](https://martllm.com/models/meta-llama/llama-3.2-3b-instruct) | text | $0.03938 / $0.2599 | $0.04462 / $0.2945 | +13% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | text | $0.05544 / $0.1663 | $0.06294 / $0.1888 | +14% |
| [MAI Image 2.7 Flash](https://martllm.com/models/microsoft/mai-image-2-7-flash) | image | $0.02095 / image | $0.0238 / image | +14% |
| [GPT-5.6 Luna](https://martllm.com/models/openai/gpt-5.6-luna) | text | $0.0609 / $0.3654 | $0.0693 / $0.4158 | +14% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | text | $0.4607 / $1.44 | $0.5245 / $1.54 | in +14% / out +7% |
| [NVIDIA: Nemotron 3.5 Super VL](https://martllm.com/models/nvidia/nemotron-3.5-super-vl) | text | $0.1118 / $0.3728 | $0.1276 / $0.4253 | +14% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | text | $2.21 / $11.03 | $2.52 / $12.60 | +14% |
| [Tencent: Hy4 flash](https://martllm.com/models/tencent/hy4-flash) | text | $0.05953 / $0.239 | $0.06835 / $0.2744 | +15% |
| [Qwen3.8 Flash](https://martllm.com/models/qwen/qwen3.8-flash) | text | $0.0315 / $0.0987 | $0.03623 / $0.1135 | +15% |
| [Qwen 3.6 35B A3B](https://martllm.com/models/qwen/qwen3-6-35b-a3b) | text | $0.0672 / $0.672 | $0.0777 / $0.777 | +16% |
| [GPT-5.4 Image 2](https://martllm.com/models/openai/gpt-5.4-image-2) | image | $6.72 / $12.60 | $7.81 / $14.65 | +16% |
| [GLM 5V Turbo](https://martllm.com/models/z-ai/glm-5v-turbo) | text | $1.01 / $3.36 | $1.17 / $3.91 | +16% |
| [Claude Sonnet 5.5](https://martllm.com/models/anthropic/claude-sonnet-5.5) | text | $1.11 / $5.57 | $1.30 / $6.51 | +17% |
| [MiMo-V2.6-Pro](https://martllm.com/models/xiaomi/mimo-v2.6-pro) | text | $0.2558 / $0.5116 | $0.3015 / $0.6029 | +18% |
| [Aion 3.0 Mini](https://martllm.com/models/aion-labs/aion-3-0-mini) | text | $0.5733 / $1.15 | $0.6762 / $1.35 | +18% |
| [MiniMax H3 Hyper Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-image-to-video) | video | $0.03087 / sec | $0.03646 / sec | +18% |
| [Claude Opus 5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5-fast) | text | $6.20 / $30.98 | $7.35 / $36.75 | +19% |
| [GPT-5.6 Terra](https://martllm.com/models/openai/gpt-5.6-terra) | text | $0.987 / $5.92 | $1.18 / $7.06 | +19% |
| [Qwen 4 Max](https://martllm.com/models/qwen/qwen4-max) | text | $0.5386 / $1.62 | $0.6434 / $1.93 | +19% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | text | $5.25 / $26.25 | $6.30 / $31.50 | +20% |
| [Z.ai: GLM 5.3 FlashX](https://martllm.com/models/z-ai/glm-5.3-flashx) | text | $0.2331 / $0.7875 | $0.2797 / $0.945 | +20% |
| [Seed 2.1 Turbo](https://martllm.com/models/bytedance/seed-2-1-turbo) | text | $0.399 / $2.00 | $0.483 / $2.42 | +21% |
| [Grok 4.6](https://martllm.com/models/x-ai/grok-4.6) | text | $1.74 / $5.21 | $2.12 / $6.35 | +22% |
| [Gemini 3.8 Flash](https://martllm.com/models/google/gemini-3.8-flash) | text | $0.1024 / $0.5119 | $0.126 / $0.63 | +23% |
| [Claude Opus 4.6](https://martllm.com/models/anthropic/claude-opus-4.6) | text | $2.26 / $11.29 | $2.78 / $13.91 | +23% |
| [Grok 4.20 Beta](https://martllm.com/models/x-ai/grok-4.20-beta) | text | $0.5666 / $1.13 | $0.7008 / $1.40 | +24% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | text | $2.15 / $10.76 | $2.68 / $13.39 | +24% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | text | $0.462 / $1.74 | $0.5775 / $2.18 | +25% |
| [GPT-6.1 Sol](https://martllm.com/models/openai/gpt-6.1-sol) | text | $0.819 / $4.09 | $1.03 / $5.14 | +26% |
| [Claude Fable 5](https://martllm.com/models/anthropic/claude-fable-5) | text | $6.09 / $30.45 | $7.67 / $38.33 | +26% |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | music | $0.002507 / sec | $0.003187 / sec | +27% |
| [MAI Image 2.7](https://martllm.com/models/microsoft/mai-image-2-7) | image | $0.05238 / image | $0.06664 / image | +27% |
| [Meta: Muse Ember](https://martllm.com/models/meta-llama/muse-ember) | text | $0.07665 / $0.3832 | $0.09765 / $0.4883 | +27% |
| [Qwen: Qwen3.7 Flash](https://martllm.com/models/qwen/qwen3.7-flash) | text | $0.01953 / $0.08463 | $0.02489 / $0.1078 | +27% |
| [Mistral: Pixtral Large 2502](https://martllm.com/models/mistralai/pixtral-large-2502) | text | $1.51 / $4.54 | $1.95 / $5.86 | +29% |
| [Sakana: Fugu Ultra v2](https://martllm.com/models/sakana/fugu-ultra-v2) | text | $3.73 / $22.36 | $4.88 / $29.30 | +31% |
| [Elorian: Glimpse](https://martllm.com/models/elorian/glimpse) | text | $0.4473 / $2.24 | $0.5922 / $2.96 | +32% |
| [Fireworks: Ember-1](https://martllm.com/models/fireworks/ember-1) | text | $2.24 / $11.18 | $2.96 / $14.80 | +32% |
| [Qwen: Qwen3.8 Max Prime](https://martllm.com/models/qwen/qwen3.8-max-prime) | text | $2.98 / $8.95 | $3.95 / $11.84 | +32% |
| [Sakana: Fugu Max](https://martllm.com/models/sakana/fugu-max) | text | $1.49 / $4.47 | $1.97 / $5.92 | +32% |
| [GLM 4.5](https://martllm.com/models/z-ai/glm-4.5) | text | $0.4473 / $1.64 | $0.5922 / $2.17 | +32% |
| [MiMo-V2.6-Pro-UltraSpeed](https://martllm.com/models/xiaomi/mimo-v2.6-pro-ultraspeed) | text | $3.20 / $6.39 | $4.25 / $8.50 | +33% |
| [Aion 2.0](https://martllm.com/models/aion-labs/aion-2.0) | text | $0.588 / $1.18 | $0.7812 / $1.56 | +33% |
| [Moondream: Moondream 3 Preview](https://martllm.com/models/moondream/moondream3-preview) | text | $0.2205 / $1.84 | $0.2929 / $2.44 | +33% |
| [StepFun: Step 5 Preview](https://martllm.com/models/stepfun/step-5-preview) | text | $0.735 / $1.98 | $0.9765 / $2.64 | +33% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.1981 / $0.5942 | $0.2632 / $0.7895 | +33% |
| [Cohere: Command A+](https://martllm.com/models/cohere/command-a-plus) | text | $0.2205 / $1.10 | $0.2961 / $1.48 | +34% |
| [Moondream: Moondream 3.1](https://martllm.com/models/moondream/moondream3.1-9b-a2b) | text | $0.2205 / $1.84 | $0.2961 / $2.47 | +34% |
| [GPT-5 Image](https://martllm.com/models/openai/gpt-5-image) | image | $7.35 / $7.35 | $9.87 / $9.87 | +34% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | text | $0.09555 / $0.5869 | $0.1285 / $0.7409 | in +35% / out +26% |
| [Voxtral Small 24B 2507](https://martllm.com/models/mistralai/voxtral-small-24b-2507) | text | $0.03969 / $0.1191 | $0.05402 / $0.1621 | +36% |
| [FLUX.2 Flex](https://martllm.com/models/black-forest-labs/flux.2-flex) | image | $0.04578 / megapixel | $0.0625 / megapixel | +37% |
| [FLUX.2 Klein 4B](https://martllm.com/models/black-forest-labs/flux.2-klein-4b) | image | $0.01145 / megapixel | $0.01562 / megapixel | +37% |
| [Claude Opus 5](https://martllm.com/models/anthropic/claude-opus-5) | text | $2.15 / $10.76 | $2.94 / $14.70 | +37% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | text | $0.2355 / $0.9781 | $0.3242 / $1.35 | +38% |
| [GPT-6 Sol](https://martllm.com/models/openai/gpt-6-sol) | text | $0.882 / $4.41 | $1.22 / $6.09 | +38% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | text | $0.1058 / $0.4158 | $0.147 / $0.462 | in +39% / out +11% |
| [Pareto 26.9](https://martllm.com/models/unbiased/pareto-26.9) | text | $1.89 / $5.67 | $2.62 / $7.88 | +39% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | text | $0.0105 / $0.084 | $0.0147 / $0.1176 | +40% |
| [Tencent HY3](https://martllm.com/models/tencent/hy3) | text | $0.09563 / $0.3825 | $0.1344 / $0.5378 | +41% |
| [LiquidAI: LFM2.5-24B-A2B](https://martllm.com/models/liquid/lfm-2.5-24b-a2b) | text | $0.03675 / $0.5145 | $0.0525 / $0.735 | +43% |
| [Grok Imagine Text-to-Video](https://martllm.com/models/x-ai/grok-imagine-text-to-video) | video | $0.04725 / sec | $0.07087 / sec | +50% |
| [Qwen: Qwen3.8 Max (0902)](https://martllm.com/models/qwen/qwen3.8-max-0902) | text | $0.273 / $0.819 | $0.42 / $1.26 | +54% |
| [Tencent: Hy4](https://martllm.com/models/tencent/hy4) | text | $0.4729 / $1.42 | $0.7443 / $2.23 | +57% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $0.2567 / $0.5133 | $0.4135 / $0.827 | +61% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | text | $0.1654 / $0.9922 | $0.2756 / $1.65 | +67% |
| [GPT-6.2 Sol](https://martllm.com/models/openai/gpt-6.2-sol) | text | $0.651 / $3.25 | $1.09 / $5.46 | +68% |
| [GPT-6 Astra](https://martllm.com/models/openai/gpt-6-astra) | text | $3.67 / $18.38 | $6.30 / $31.50 | +71% |
| [GPT-6.2 Astra](https://martllm.com/models/openai/gpt-6.2-astra) | text | $3.02 / $15.12 | $5.21 / $26.04 | +72% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | text | $0.003465 / $0.01733 | $0.005985 / $0.02993 | +73% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | text | $0.0525 / $0.1848 | $0.08747 / $0.3222 | in +67% / out +74% |
| [Nano Banana (Gemini 2.5 Flash Image)](https://martllm.com/models/google/gemini-2.5-flash-image) | image | $0.1575 / $15.75 | $0.2835 / $28.35 | +80% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | text | $0.0525 / $0.315 | $0.0945 / $0.567 | +80% |
| [Particle AI: Particle-1](https://martllm.com/models/particle-ai/particle-1) | text | $0.03914 / $0.2796 | $0.07203 / $0.5145 | +84% |
| [Google: Gemini 4 Carbon](https://martllm.com/models/google/gemini-4-carbon) | text | $0.462 / $2.31 | $0.882 / $4.41 | +91% |
| [Claude Haiku 4.5](https://martllm.com/models/anthropic/claude-haiku-4.5) | text | $0.546 / $2.73 | $1.05 / $5.25 | +92% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | text | $0.009844 / $0.1045 | $0.021 / $0.21 | in +113% / out +101% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | text | $0.00588 / $0.0252 | $0.01544 / $0.06615 | +162% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | text | $0.08614 / $0.2087 | $0.243 / $0.5889 | +182% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | text | $0.273 / $1.36 | $1.03 / $5.14 | +277% |

</details>


## 2026-11-25 (vs 2026-11-24)

**Official list price changes (119)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MiniMax H3 Hyper Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-image-to-video) | video | $0.11 / sec | $0.035 / sec | −68% |
| [Grok Imagine Image 2.0](https://martllm.com/models/x-ai/grok-imagine-image-2-0) | image | $0.04 / image | $0.02 / image | −50% |
| [Nano Banana](https://martllm.com/models/google/nano-banana) | image | $0.039 / image | $0.02 / image | −49% |
| [Wan 3.0](https://martllm.com/models/wan/wan-3-0) | video | $0.05 / sec | $0.04 / sec | −20% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | text | $2.50 / $7.50 | $2.00 / $6.00 | −20% |
| [Seedream 4.0](https://martllm.com/models/bytedance/seedream-4-0) | image | $0.03 / image | $0.025 / image | −17% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | text | $0.27 / $0.48 | $0.26 / $0.42 | in −4% / out −12% |
| [Wan 3.0 Prime](https://martllm.com/models/wan/wan-3-0-prime) | video | $0.068 / sec | $0.061 / sec | −10% |
| [PixVerse V6 Max](https://martllm.com/models/pixverse/pixverse-v6-max) | video | $0.02667 / sec | $0.024 / sec | −10% |
| [PixVerse V6](https://martllm.com/models/pixverse/pixverse-v6) | video | $0.02222 / sec | $0.02 / sec | −10% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | text | $0.20 / $2.20 | $0.1875 / $1.99 | in −6% / out −10% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | text | $0.55 / $3.60 | $0.50 / $3.60 | in −9% / out 0% |
| [Tencent HY3](https://martllm.com/models/tencent/hy3) | text | $0.136 / $0.554 | $0.132 / $0.528 | in −3% / out −5% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | text | $0.57 / $2.85 | $0.55 / $2.75 | −4% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | text | $1.32 / $3.96 | $1.31 / $3.96 | 0% |
| [Flux 3 Klein](https://martllm.com/models/black-forest-labs/flux-3-klein) | image | – | $0.008 / image |  |
| [Seedance 2.0 Fast (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-fast-reference-to-video) | video | – | $0.07 / sec |  |
| [Seedance 2.0 (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-reference-to-video) | video | – | $0.088 / sec |  |
| [Seedream 5.0 Flash](https://martllm.com/models/bytedance/seedream-5-0-flash) | image | – | $0.0162 / image |  |
| [Seed Audio 1.0](https://martllm.com/models/bytedance/seed-audio-1-0) | music | – | $0.002875 / sec |  |
| [Orpheus TTS](https://martllm.com/models/canopy-labs/tts-orpheus) | speech | – | $0.0625 / 1K chars |  |
| [ElevenLabs Music v2](https://martllm.com/models/elevenlabs/elevenlabs-music-v2) | music | – | $0.69 / track |  |
| [ElevenLabs TTS v4](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4) | music | – | $0.092 / 1K chars |  |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | music | – | $0.046 / 1K chars |  |
| [Gemini Omni Flash (reference-to-video)](https://martllm.com/models/google/gemini-omni-flash-reference-to-video) | video | – | $0.1425 / sec |  |
| [Imagen 4](https://martllm.com/models/google/imagen-4) | image | – | $0.04 / image |  |
| [Veo3.1 Fast (image-to-video)](https://martllm.com/models/google/veo3-1-fast-image-to-video) | video | – | $0.165 / sec |  |
| [Veo 3.1 Full Text-to-Video](https://martllm.com/models/google/veo3-1-full-text-to-video) | video | – | $0.44 / sec |  |
| [Happyhorse 1.0 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-image-to-video) | video | – | $0.1533 / sec |  |
| [Happyhorse 1.0 (reference-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-reference-to-video) | video | – | $0.1533 / sec |  |
| [HappyHorse 1.0 Text-to-Video](https://martllm.com/models/happyhorse/happyhorse-1-0-text-to-video) | video | – | $0.2633 / sec |  |
| [Happyhorse 1.1 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-1-image-to-video) | video | – | $0.1533 / sec |  |
| [Kling 2.6 Pro (image-to-video)](https://martllm.com/models/kling/kling-2-6-pro-image-to-video) | video | – | $0.154 / sec |  |
| [Kling 2.6 Pro Text-to-Video](https://martllm.com/models/kling/kling-2-6-pro-text-to-video) | video | – | $0.154 / sec |  |
| [Kling O3.4k (image-to-video)](https://martllm.com/models/kling/kling-o3-4k-image-to-video) | video | – | $0.4633 / sec |  |
| [Kling O3 4K Text-to-Video](https://martllm.com/models/kling/kling-o3-4k-text-to-video) | video | – | $0.4633 / sec |  |
| [Kling O3 Standard Text-to-Video](https://martllm.com/models/kling/kling-o3-standard-text-to-video) | video | – | $0.1232 / sec |  |
| [Kling V3 4K Text-to-Video](https://martllm.com/models/kling/kling-v3-4k-text-to-video) | video | – | $0.4633 / sec |  |
| [Kling V3 Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-pro-image-to-video) | video | – | $0.1833 / sec |  |
| [Kling V3 Pro Text-to-Video](https://martllm.com/models/kling/kling-v3-pro-text-to-video) | video | – | $0.184 / sec |  |
| [Kling V3 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-pro-image-to-video) | video | – | $0.1533 / sec |  |
| [Kling 4.0 Flash Reference-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-reference-to-video) | video | – | $0.1175 / sec |  |
| [Kling 4.0 Flash Text-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-text-to-video) | video | – | $0.1175 / sec |  |
| [Kling Image 4.0](https://martllm.com/models/kling/venice-kling-v4-text-to-image) | image | – | $0.08 / image |  |
| [Ltx 2 V2.3 Fast (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | – | $0.0667 / sec |  |
| [LTX 2 v2.3 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | – | $0.06667 / sec |  |
| [Ltx 2 V2.3 Full (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | – | $0.0883 / sec |  |
| [LTX 2 v2.3 Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | – | $0.08833 / sec |  |
| [Luma Uni 1 (image-to-image)](https://martllm.com/models/luma/luma-uni-1-edit) | image | – | $0.06 / image |  |
| [Luma Uni 1 Max (image-to-image)](https://martllm.com/models/luma/luma-uni-1-max-edit) | image | – | $0.13 / image |  |
| [Luma Uni-1 (Venice)](https://martllm.com/models/luma/venice-luma-uni-1) | image | – | $0.05 / image |  |
| [Luma Uni-1 Max (Venice)](https://martllm.com/models/luma/venice-luma-uni-1-max) | image | – | $0.12 / image |  |
| [LongCat Distilled Text-to-Video](https://martllm.com/models/meituan/longcat-distilled-text-to-video) | video | – | $0.018 / sec |  |
| [Longcat (image-to-video)](https://martllm.com/models/meituan/longcat-image-to-video) | video | – | $0.05 / sec |  |
| [LongCat Text-to-Video](https://martllm.com/models/meituan/longcat-text-to-video) | video | – | $0.05 / sec |  |
| [Muse Image](https://martllm.com/models/meta-llama/venice-muse-image) | image | – | $0.02 / image |  |
| [MiniMax H3 Chili Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-chili-image-to-video) | video | – | $0.0325 / sec |  |
| [MiniMax H3 Chili Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-chili-text-to-video) | video | – | $0.03 / sec |  |
| [Cosmos Predict (image-to-video)](https://martllm.com/models/nvidia/cosmos-predict-image-to-video) | video | – | $0.801 / video |  |
| [GPT Image 2.6 Sunburst (image-to-image)](https://martllm.com/models/openai/venice-gpt-image-2-6-sunburst-edit) | image | – | $0.10 / image |  |
| [Ovi Image-to-Video](https://martllm.com/models/ovi/ovi-image-to-video) | video | – | $0.044 / sec |  |
| [Pixverse C1 (image-to-video)](https://martllm.com/models/pixverse/pixverse-c1-image-to-video) | video | – | $0.0433 / sec |  |
| [Pixverse C1 (reference-to-video)](https://martllm.com/models/pixverse/pixverse-c1-reference-to-video) | video | – | $0.0433 / sec |  |
| [Pixverse C1 Transition (transition)](https://martllm.com/models/pixverse/pixverse-c1-transition) | video | – | $0.0433 / sec |  |
| [Pixverse V5.6 (image-to-video)](https://martllm.com/models/pixverse/pixverse-v5-6-image-to-video) | video | – | $0.202 / sec |  |
| [PixVerse V5.6 Text-to-Video](https://martllm.com/models/pixverse/pixverse-v5-6-text-to-video) | video | – | $0.228 / sec |  |
| [PixVerse V6 Fusion](https://martllm.com/models/pixverse/pixverse-v6-reference-to-video) | video | – | $0.02 / sec |  |
| [Qwen Image 2 Pro (image-to-image)](https://martllm.com/models/qwen/qwen-image-2-pro-edit) | image | – | $0.10 / image |  |
| [Qwen3 0.6B TTS](https://martllm.com/models/qwen/tts-qwen3-0-6b) | speech | – | $0.0875 / 1K chars |  |
| [Qwen3 1.7B TTS](https://martllm.com/models/qwen/tts-qwen3-1-7b) | speech | – | $0.1125 / 1K chars |  |
| [Qwen Image 2.1 Pro (Venice)](https://martllm.com/models/qwen/venice-qwen-image-2-1-pro) | image | – | $0.05 / image |  |
| [Wan 3.0 Prime Pro Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-pro-image-to-video) | video | – | $0.3312 / sec |  |
| [Wan 3.0 Prime Pro Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-pro-reference-to-video) | video | – | $0.3312 / sec |  |
| [Wan 3.0 Prime Pro Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-pro-text-to-video) | video | – | $0.3312 / sec |  |
| [Wan 3.0 Pro Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-pro-image-to-video) | video | – | $0.2366 / sec |  |
| [Wan 3.0 Pro Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-pro-reference-to-video) | video | – | $0.2366 / sec |  |
| [Wan 3.0 Pro Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-pro-text-to-video) | video | – | $0.2366 / sec |  |
| [Chatterbox HD TTS](https://martllm.com/models/resemble-ai/tts-chatterbox-hd) | speech | – | $0.05 / 1K chars |  |
| [Runway Gen-4 Turbo](https://martllm.com/models/runway/runway-gen4-turbo) | video | – | $0.07 / sec |  |
| [ElevenLabs Music (Venice)](https://martllm.com/models/venice/elevenlabs-music) | music | – | $0.69 / track |  |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-multilingual-v2) | music | – | $0.115 / 1K chars |  |
| [ElevenLabs TTS v3 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-v3) | music | – | $0.115 / 1K chars |  |
| [GPT Image 1.5 — Edit (Venice)](https://martllm.com/models/venice/gpt-image-1-5-edit) | image | – | $0.36 / image |  |
| [GPT Image 1.5 (Venice)](https://martllm.com/models/venice/gpt-image-1.5) | image | – | $0.26 / image |  |
| [Grok Imagine High Quality (Venice)](https://martllm.com/models/venice/grok-imagine-quality) | image | – | $0.06 / image |  |
| [Hunyuan Image 3.0 (Venice)](https://martllm.com/models/venice/hunyuan-image-v3) | image | – | $0.09 / image |  |
| [MMAudio V2 Text-to-Audio (Venice)](https://martllm.com/models/venice/mmaudio-v2-text-to-audio) | music | – | $0.00092 / sec |  |
| [Venice Music Gen (legacy alias)](https://martllm.com/models/venice/music-gen) | music | – | $0.03 / track |  |
| [Qwen Image (Venice)](https://martllm.com/models/venice/qwen-image) | image | – | $0.03 / image |  |
| [Qwen Image 2 (Venice)](https://martllm.com/models/venice/qwen-image-2) | image | – | $0.05 / image |  |
| [Stable Audio 2.5 (Venice)](https://martllm.com/models/venice/stable-audio-25) | music | – | $0.24 / track |  |
| [Venice Video Gen (legacy alias)](https://martllm.com/models/venice/video-gen) | video | – | $0.16 / sec |  |
| [Wan 2.7 (Venice)](https://martllm.com/models/venice/wan-2.7) | image | – | $0.0375 / image |  |
| [Wan 2.7 Pro (Venice)](https://martllm.com/models/venice/wan-2.7-pro) | image | – | $0.09375 / image |  |
| [Vidu Q3 (image-to-video)](https://martllm.com/models/vidu/vidu-q3-image-to-video) | video | – | $0.09 / sec |  |
| [Vidu Q3 Text-to-Video](https://martllm.com/models/vidu/vidu-q3-text-to-video) | video | – | $0.1933 / sec |  |
| [Wan 2.5 Preview (image-to-video)](https://martllm.com/models/wan/wan-2-5-preview-image-to-video) | video | – | $0.056 / sec |  |
| [Wan 2.5 Preview Text-to-Video](https://martllm.com/models/wan/wan-2-5-preview-text-to-video) | video | – | $0.11 / sec |  |
| [Wan 2.6 (image-to-video)](https://martllm.com/models/wan/wan-2-6-image-to-video) | video | – | $0.11 / sec |  |
| [Wan 2.6 Text-to-Video](https://martllm.com/models/wan/wan-2-6-text-to-video) | video | – | $0.166 / sec |  |
| [Wan 2.7 Pro (image-to-image)](https://martllm.com/models/wan/wan-2-7-pro-edit) | image | – | $0.094 / image |  |
| [Wan 2.7 (reference-to-video)](https://martllm.com/models/wan/wan-2-7-reference-to-video) | video | – | $0.11 / sec |  |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://martllm.com/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | – | $0.09 / sec |  |
| [Grok Imagine Reference To Video Private (reference-to-video)](https://martllm.com/models/x-ai/grok-imagine-reference-to-video-private) | video | – | $0.06 / sec |  |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | $0.1383 / sec | $0.1394 / sec | +1% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | text | $0.70 / $3.40 | $0.725 / $3.40 | in +4% / out 0% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.1485 / $0.64 | $0.15 / $0.668 | in +1% / out +4% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.127 / $0.475 | $0.125 / $0.50 | in −2% / out +5% |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-text-to-video) | video | $0.025 / sec | $0.02633 / sec | +5% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.195 / $0.75 | $0.205 / $0.79 | +5% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $1.28 / $2.56 | $1.36 / $2.72 | +6% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | text | $0.10 / $0.30 | $0.097 / $0.319 | in −3% / out +6% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | text | $1.26 / $3.96 | $1.35 / $4.29 | +8% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | text | $1.26 / $3.96 | $1.35 / $4.29 | +8% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | text | $0.12 / $0.27 | $0.13 / $0.275 | in +8% / out +2% |
| [inclusionAI: Ling 3.1 Flash](https://martllm.com/models/inclusionai/ling-3.1-flash) | text | $0.0675 / $0.2025 | $0.075 / $0.225 | +11% |
| [Thinking Machines: Inkling](https://martllm.com/models/thinking-machines/inkling) | text | $1.00 / $4.05 | $1.10 / $4.53 | in +10% / out +12% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | text | $0.30 / $1.20 | $0.325 / $1.35 | in +8% / out +13% |
| [Tencent: Hy4 flash](https://martllm.com/models/tencent/hy4-flash) | text | $0.035 / $0.1405 | $0.07 / $0.281 | +100% |

**New models (26)**

| Model | Category | Official price | MartLLM price |
|---|---|---|---|
| [Flux 3 First Last Frame](https://martllm.com/models/black-forest-labs/flux-3-first-last-frame-to-video) | video | – | $0.197 / sec |
| [Flux 3](https://martllm.com/models/black-forest-labs/flux-3-image-to-video) | video | – | $0.197 / sec |
| [Flux 3 Max](https://martllm.com/models/black-forest-labs/flux-3-max-image-to-video) | video | – | $0.1739 / sec |
| [FLUX 1.1 Pro Ultra](https://martllm.com/models/black-forest-labs/flux-pro-1-1-ultra) | image | $0.06 / image | $0.0528 / image |
| [Gemini 3.1 Pro](https://martllm.com/models/google/gemini-3.1-pro) | text | – | $2.06 / $12.35 |
| [Gemini Omni Flash 1.2](https://martllm.com/models/google/gemini-omni-flash-1-2) | video | – | $0.02 / sec |
| [Ideogram Character Balanced](https://martllm.com/models/ideogram/ideogram-character-balanced) | image | – | $0.09 / image |
| [Ideogram Character Quality](https://martllm.com/models/ideogram/ideogram-character-quality) | image | – | $0.12 / image |
| [Ideogram Character Turbo](https://martllm.com/models/ideogram/ideogram-character-turbo) | image | – | $0.06 / image |
| [LTX Video 2.5 Fast](https://martllm.com/models/lightricks/ltx-2-5-fast-image-to-video) | video | – | $0.1037 / sec |
| [LTX Video 2.5 Pro](https://martllm.com/models/lightricks/ltx-2-5-pro-image-to-video) | video | – | $0.1383 / sec |
| [MiniMax H3 Max Multi-Angle](https://martllm.com/models/minimax/minimax-h3-max-multi-angle) | video | – | $0.04749 / sec |
| [MiniMax H3 Max Turbo](https://martllm.com/models/minimax/minimax-h3-max-turbo-image-to-video) | video | – | $0.02375 / sec |
| [MiniMax Hailuo 2.3 Fast](https://martllm.com/models/minimax/minimax-hailuo-2-3-fast) | video | $0.0424 / sec | $0.04036 / sec |
| [MiniMax M2.7 Highspeed](https://martllm.com/models/minimax/minimax-m2.7-highspeed) | text | – | $0.6174 / $2.47 |
| [GPT-4o Image](https://martllm.com/models/openai/gpt-4o-image) | image | – | $0.03 / image |
| [Recraft V2](https://martllm.com/models/recraft/recraft-v2) | image | – | $0.02305 / image |
| [Recraft V4.1](https://martllm.com/models/recraft/recraft-v4-1) | image | – | $0.03667 / image |
| [Recraft V4.1 Flash](https://martllm.com/models/recraft/recraft-v4-1-flash) | image | – | $0.007334 / image |
| [Recraft V4.1 Utility](https://martllm.com/models/recraft/recraft-v4-1-utility) | image | – | $0.03667 / image |
| [Recraft V4.1 Utility Pro](https://martllm.com/models/recraft/recraft-v4-1-utility-pro) | image | – | $0.22 / image |
| [Thinking Machines: Inkling 2 Mini](https://martllm.com/models/thinking-machines/inkling-2-mini) | text | $0.0975 / $0.40 | $0.07883 / $0.3234 |
| [Thinking Machines: Inkling 2 Small](https://martllm.com/models/thinking-machines/inkling-2-small) | text | $0.30 / $1.00 | $0.2425 / $0.8085 |
| [Runway Gen-4.5 Text-to-Video (Venice)](https://martllm.com/models/venice/runway-gen4-5-text) | video | $0.16 / sec | $0.1512 / sec |
| [Wan 2.2 Enhanced](https://martllm.com/models/wan/wan-2-2-enhanced-image-to-video) | video | – | $0.0419 / sec |
| [Wan 2.7 Enhanced](https://martllm.com/models/wan/wan-2-7-enhanced-image-to-video) | video | – | $0.1348 / sec |

**No longer listed (4)**: `inception/mercury-2`, `inception/mercury-2.5`, `inception/mercury-3`, `tencent/hy4-preview`

<details><summary>MartLLM price moves of 10% or more (233)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GPT Image 2 (Venice)](https://martllm.com/models/venice/gpt-image-2) | image | $0.0315 / image | $0.0055 / image | −83% |
| [GPT Image 2 — Edit (Venice)](https://martllm.com/models/venice/gpt-image-2-edit) | image | $0.0315 / image | $0.0055 / image | −83% |
| [Grok Imagine 2.0 (image-to-image)](https://martllm.com/models/x-ai/grok-imagine-image-2-0-edit) | image | $0.07702 / image | $0.01428 / image | −81% |
| [MiniMax H3 Chili Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-chili-image-to-video) | video | $0.1365 / sec | $0.03071 / sec | −77% |
| [Topaz Video Upscale](https://martllm.com/models/topaz-labs/topaz-video-upscale) | video | $0.1635 / sec | $0.042 / sec | −74% |
| [MiniMax H3 Hyper Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-image-to-video) | video | $0.09125 / sec | $0.03087 / sec | −66% |
| [Wan 2.6 Text-to-Video](https://martllm.com/models/wan/wan-2-6-text-to-video) | video | $0.1743 / sec | $0.06321 / sec | −64% |
| [Qwen Image 2 (Venice)](https://martllm.com/models/venice/qwen-image-2) | image | $0.0525 / image | $0.01904 / image | −64% |
| [Nano Banana](https://martllm.com/models/google/nano-banana) | image | $0.02 / image | $0.007615 / image | −62% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | text | $0.01544 / $0.06615 | $0.00588 / $0.0252 | −62% |
| [Flux 3 (Venice)](https://martllm.com/models/black-forest-labs/venice-flux-3-image) | image | $0.0945 / image | $0.03655 / image | −61% |
| [Nano Banana 2 (image-to-image)](https://martllm.com/models/google/nano-banana-2-edit) | image | $0.042 / image | $0.0165 / image | −61% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | text | $0.6458 / $3.87 | $0.2677 / $1.61 | −59% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | text | $0.5267 / $1.58 | $0.2209 / $0.6653 | −58% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | text | $0.4988 / $2.00 | $0.21 / $0.84 | −58% |
| [Seedream V5 Pro (Venice)](https://martllm.com/models/bytedance/venice-seedream-v5-pro) | image | $0.03423 / image | $0.01485 / image | −57% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | text | $0.504 / $2.52 | $0.2205 / $1.10 | −56% |
| [HappyHorse 1.0 Text-to-Video](https://martllm.com/models/happyhorse/happyhorse-1-0-text-to-video) | video | $0.2765 / sec | $0.1232 / sec | −55% |
| [Wan 3.0 Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-reference-to-video) | video | $0.06825 / sec | $0.0313 / sec | −54% |
| [Seedance 2.0 Fast Text-to-Video (Venice)](https://martllm.com/models/venice/seedance-2-fast-t2v) | video | $0.0735 / sec | $0.03593 / sec | −51% |
| [Google: Gemini 4 Neon](https://martllm.com/models/google/gemini-4-neon) | text | $1.98 / $9.92 | $0.9765 / $4.88 | −51% |
| [Seedance 2.0 Mini (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-reference-to-video) | video | $0.03465 / sec | $0.01728 / sec | −50% |
| [Pixverse V5.6 (image-to-video)](https://martllm.com/models/pixverse/pixverse-v5-6-image-to-video) | video | $0.2121 / sec | $0.1061 / sec | −50% |
| [Hunyuan Image 3.0 (Venice)](https://martllm.com/models/venice/hunyuan-image-v3) | image | $0.0945 / image | $0.04725 / image | −50% |
| [Qwen Image (Venice)](https://martllm.com/models/venice/qwen-image) | image | $0.0315 / image | $0.01575 / image | −50% |
| [Grok Imagine High Quality (Venice)](https://martllm.com/models/venice/grok-imagine-quality) | image | $0.063 / image | $0.03168 / image | −50% |
| [Seedance 2.0 Fast (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-fast-reference-to-video) | video | $0.0735 / sec | $0.03792 / sec | −48% |
| [Claude Haiku 4.5](https://martllm.com/models/anthropic/claude-haiku-4.5) | text | $1.05 / $5.25 | $0.546 / $2.73 | −48% |
| [Wan 3.0 Prime Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-reference-to-video) | video | $0.09282 / sec | $0.04895 / sec | −47% |
| [Voxtral Small 24B 2507](https://martllm.com/models/mistralai/voxtral-small-24b-2507) | text | $0.07387 / $0.2216 | $0.03969 / $0.1191 | −46% |
| [Wan 2.5 Preview Text-to-Video](https://martllm.com/models/wan/wan-2-5-preview-text-to-video) | video | $0.1155 / sec | $0.06321 / sec | −45% |
| [Wan 2.6 (image-to-video)](https://martllm.com/models/wan/wan-2-6-image-to-video) | video | $0.1155 / sec | $0.06321 / sec | −45% |
| [Gemini 3.5 Flash Lite](https://martllm.com/models/google/gemini-3-5-flash-lite) | text | $0.09135 / $0.7612 | $0.0504 / $0.42 | −45% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | text | $0.09922 / $0.09922 | $0.05513 / $0.05513 | −44% |
| [GPT-6.2 Sol](https://martllm.com/models/openai/gpt-6.2-sol) | text | $1.13 / $5.67 | $0.651 / $3.25 | −43% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | text | $0.3352 / $1.05 | $0.194 / $0.6098 | −42% |
| [GPT-5.6 Luna](https://martllm.com/models/openai/gpt-5.6-luna) | text | $0.105 / $0.63 | $0.0609 / $0.3654 | −42% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | text | $0.0714 / $0.4462 | $0.042 / $0.2625 | −41% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | text | $0.462 / $2.31 | $0.273 / $1.36 | −41% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://martllm.com/models/nvidia/nemotron-nano-12b-v2) | text | $0.063 / $0.189 | $0.0378 / $0.1134 | −40% |
| [GPT-5.5](https://martllm.com/models/openai/gpt-5.5) | text | $3.20 / $19.21 | $1.94 / $11.65 | −39% |
| [GPT-6.2 Astra](https://martllm.com/models/openai/gpt-6.2-astra) | text | $4.96 / $24.78 | $3.02 / $15.12 | −39% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | text | $0.0147 / $0.0441 | $0.009167 / $0.03015 | in −38% / out −32% |
| [Seedance 2.0 (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-reference-to-video) | video | $0.0924 / sec | $0.05852 / sec | −37% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.04934 / $0.1845 | $0.0315 / $0.126 | in −36% / out −32% |
| [Stable Audio 2.5 (Venice)](https://martllm.com/models/venice/stable-audio-25) | music | $0.2616 / track | $0.1674 / track | −36% |
| [GPT Image 1.5 (Venice)](https://martllm.com/models/venice/gpt-image-1.5) | image | $0.273 / image | $0.1774 / image | −35% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | text | $0.08442 / $0.2533 | $0.05544 / $0.1663 | −34% |
| [NVIDIA Nemotron 3 Super 120B](https://martllm.com/models/nvidia/nemotron-3-super-120b) | text | $0.03701 / $0.1974 | $0.02441 / $0.1302 | −34% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | text | $0.07875 / $0.4725 | $0.0525 / $0.315 | −33% |
| [Qwen Image 3 Pro (Venice)](https://martllm.com/models/venice/qwen-image-3-pro) | image | $0.04043 / image | $0.0272 / image | −33% |
| [Kimi K2.7 Code](https://martllm.com/models/moonshotai/kimi-k2.7-code) | text | $0.2205 / $1.03 | $0.1496 / $0.6983 | −32% |
| [Google: Gemini 4 Carbon](https://martllm.com/models/google/gemini-4-carbon) | text | $0.672 / $3.36 | $0.462 / $2.31 | −31% |
| [Wan 2.7 Text-to-Video](https://martllm.com/models/wan/wan-2-7-text-to-video) | video | $0.084 / sec | $0.05775 / sec | −31% |
| [GPT Image 1.5 — Edit (Venice)](https://martllm.com/models/venice/gpt-image-1-5-edit) | image | $0.378 / image | $0.2604 / image | −31% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | text | $0.1365 / $0.4095 | $0.0945 / $0.2835 | −31% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | text | $0.273 / $0.819 | $0.189 / $0.567 | −31% |
| [GPT-5.4](https://martllm.com/models/openai/gpt-5.4) | text | $1.36 / $8.19 | $0.945 / $5.67 | −31% |
| [OpenAI: GPT-6.1 Terra](https://martllm.com/models/openai/gpt-6.1-terra) | text | $0.5145 / $2.57 | $0.357 / $1.78 | −31% |
| [Qwen3 0.6B TTS](https://martllm.com/models/qwen/tts-qwen3-0-6b) | speech | $0.09538 / 1K chars | $0.06676 / 1K chars | −30% |
| [MiniMax M3.1 Flash](https://martllm.com/models/minimax/minimax-m3-1-flash) | text | $0.0315 / $0.126 | $0.02205 / $0.0882 | −30% |
| [GPT-5 Image](https://martllm.com/models/openai/gpt-5-image) | image | $10.50 / $10.50 | $7.35 / $7.35 | −30% |
| [Gemini Omni Flash (reference-to-video)](https://martllm.com/models/google/gemini-omni-flash-reference-to-video) | video | $0.1496 / sec | $0.1047 / sec | −30% |
| [Grok Imagine Image 2.0](https://martllm.com/models/x-ai/grok-imagine-image-2-0) | image | $0.02 / image | $0.01428 / image | −29% |
| [Grok Imagine (Venice)](https://martllm.com/models/venice/grok-imagine) | image | $0.021 / image | $0.01523 / image | −27% |
| [Veo 3.1 Fast Text-to-Video](https://martllm.com/models/google/veo3-1-fast-text-to-video) | video | $0.1213 / sec | $0.088 / sec | −27% |
| [NVIDIA Nemotron 3 Nano 30B](https://martllm.com/models/nvidia/nemotron-3-nano-30b-a3b) | text | $0.0378 / $0.1512 | $0.02756 / $0.1103 | −27% |
| [GPT-5.2](https://martllm.com/models/openai/gpt-5.2) | text | $0.9004 / $7.20 | $0.6615 / $5.29 | −27% |
| [Seedream 4.0](https://martllm.com/models/bytedance/seedream-4-0) | image | $0.025 / image | $0.01856 / image | −26% |
| [Wan 3.0](https://martllm.com/models/wan/wan-3-0) | video | $0.042 / sec | $0.0313 / sec | −25% |
| [Qwen Image 2 (image-to-image)](https://martllm.com/models/qwen/qwen-image-2-edit) | image | $0.03938 / image | $0.0294 / image | −25% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-multilingual-v2) | music | $0.1253 / 1K chars | $0.09401 / 1K chars | −25% |
| [ElevenLabs TTS v3 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-v3) | music | $0.1253 / 1K chars | $0.09401 / 1K chars | −25% |
| [Veo 3.1 Full Text-to-Video](https://martllm.com/models/google/veo3-1-full-text-to-video) | video | $0.462 / sec | $0.3465 / sec | −25% |
| [Kling 2.6 Pro (image-to-video)](https://martllm.com/models/kling/kling-2-6-pro-image-to-video) | video | $0.1617 / sec | $0.1213 / sec | −25% |
| [Luma Uni 1 Max (image-to-image)](https://martllm.com/models/luma/luma-uni-1-max-edit) | image | $0.1365 / image | $0.1024 / image | −25% |
| [PixVerse V5.6 Text-to-Video](https://martllm.com/models/pixverse/pixverse-v5-6-text-to-video) | video | $0.2394 / sec | $0.1795 / sec | −25% |
| [ElevenLabs TTS v4](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4) | music | $0.1003 / 1K chars | $0.07521 / 1K chars | −25% |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | music | $0.05014 / 1K chars | $0.0376 / 1K chars | −25% |
| [Kling O3 4K Text-to-Video](https://martllm.com/models/kling/kling-o3-4k-text-to-video) | video | $0.4865 / sec | $0.3649 / sec | −25% |
| [Kling V3 4K Text-to-Video](https://martllm.com/models/kling/kling-v3-4k-text-to-video) | video | $0.4865 / sec | $0.3649 / sec | −25% |
| [Kling Image 4.0](https://martllm.com/models/kling/venice-kling-v4-text-to-image) | image | $0.084 / image | $0.063 / image | −25% |
| [Luma Uni-1 Max (Venice)](https://martllm.com/models/luma/venice-luma-uni-1-max) | image | $0.126 / image | $0.0945 / image | −25% |
| [GPT-4o Mini](https://martllm.com/models/openai/gpt-4o-mini) | text | $0.0504 / $0.2016 | $0.0378 / $0.1512 | −25% |
| [ElevenLabs Music (Venice)](https://martllm.com/models/venice/elevenlabs-music) | music | $0.7521 / track | $0.5641 / track | −25% |
| [Kling O3.4k (image-to-video)](https://martllm.com/models/kling/kling-o3-4k-image-to-video) | video | $0.4865 / sec | $0.3648 / sec | −25% |
| [Kling V3 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.161 / sec | $0.1207 / sec | −25% |
| [Wan 2.7 Pro (Venice)](https://martllm.com/models/venice/wan-2.7-pro) | image | $0.09844 / image | $0.07383 / image | −25% |
| [MiniMax H3 Max Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-max-image-to-video) | video | $0.04725 / sec | $0.03587 / sec | −24% |
| [MiniMax H3 Max Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-max-text-to-video) | video | $0.04725 / sec | $0.03587 / sec | −24% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | text | $0.01714 / $0.105 | $0.01303 / $0.0798 | −24% |
| [PixVerse V6](https://martllm.com/models/pixverse/pixverse-v6) | video | $0.02 / sec | $0.01523 / sec | −24% |
| [PixVerse V6 Fusion](https://martllm.com/models/pixverse/pixverse-v6-reference-to-video) | video | $0.02 / sec | $0.01523 / sec | −24% |
| [Wan 3.0 Prime](https://martllm.com/models/wan/wan-3-0-prime) | video | $0.06405 / sec | $0.04895 / sec | −24% |
| [Happyhorse 1.0 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-image-to-video) | video | $0.161 / sec | $0.1237 / sec | −23% |
| [Happyhorse 1.0 (reference-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.161 / sec | $0.1237 / sec | −23% |
| [Happyhorse 1.1 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.161 / sec | $0.1237 / sec | −23% |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | $0.1307 / sec | $0.101 / sec | −23% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | text | $0.1058 / $0.4069 | $0.0819 / $0.315 | −23% |
| [Grok 4.20 Beta](https://martllm.com/models/x-ai/grok-4.20-beta) | text | $0.7306 / $1.46 | $0.5666 / $1.13 | −22% |
| [Qwen Image 3 (Venice)](https://martllm.com/models/venice/qwen-image-3) | image | $0.0252 / image | $0.01958 / image | −22% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | text | $0.105 / $0.21 | $0.0819 / $0.1638 | −22% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | text | $0.0966 / $0.483 | $0.0756 / $0.378 | −22% |
| [Nano Banana 2.1 (image-to-image)](https://martllm.com/models/google/nano-banana-2-1-edit) | image | $0.021 / image | $0.0165 / image | −21% |
| [GPT-5.3 Codex](https://martllm.com/models/openai/gpt-5.3-codex) | text | $0.882 / $7.06 | $0.6983 / $5.59 | −21% |
| [Seed Audio 1.0](https://martllm.com/models/bytedance/seed-audio-1-0) | music | $0.003134 / sec | $0.002507 / sec | −20% |
| [Orpheus TTS](https://martllm.com/models/canopy-labs/tts-orpheus) | speech | $0.06813 / 1K chars | $0.0545 / 1K chars | −20% |
| [Kling 4.0 Flash Reference-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-reference-to-video) | video | $0.1234 / sec | $0.0987 / sec | −20% |
| [Kling 4.0 Flash Text-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-text-to-video) | video | $0.1234 / sec | $0.0987 / sec | −20% |
| [Luma Uni 1 (image-to-image)](https://martllm.com/models/luma/luma-uni-1-edit) | image | $0.063 / image | $0.0504 / image | −20% |
| [Luma Uni-1 (Venice)](https://martllm.com/models/luma/venice-luma-uni-1) | image | $0.0525 / image | $0.042 / image | −20% |
| [Longcat (image-to-video)](https://martllm.com/models/meituan/longcat-image-to-video) | video | $0.0525 / sec | $0.042 / sec | −20% |
| [Ovi Image-to-Video](https://martllm.com/models/ovi/ovi-image-to-video) | video | $0.0462 / sec | $0.03696 / sec | −20% |
| [Qwen Image 2 Pro (image-to-image)](https://martllm.com/models/qwen/qwen-image-2-pro-edit) | image | $0.105 / image | $0.084 / image | −20% |
| [Qwen3 1.7B TTS](https://martllm.com/models/qwen/tts-qwen3-1-7b) | speech | $0.1226 / 1K chars | $0.0981 / 1K chars | −20% |
| [Qwen Image 2.1 Pro (Venice)](https://martllm.com/models/qwen/venice-qwen-image-2-1-pro) | image | $0.0525 / image | $0.042 / image | −20% |
| [Chatterbox HD TTS](https://martllm.com/models/resemble-ai/tts-chatterbox-hd) | speech | $0.0545 / 1K chars | $0.0436 / 1K chars | −20% |
| [Wan 2.7 (Venice)](https://martllm.com/models/venice/wan-2.7) | image | $0.03938 / image | $0.0315 / image | −20% |
| [Wan 2.7 Pro (image-to-image)](https://martllm.com/models/wan/wan-2-7-pro-edit) | image | $0.0987 / image | $0.07896 / image | −20% |
| [MMAudio V2 Text-to-Audio (Venice)](https://martllm.com/models/venice/mmaudio-v2-text-to-audio) | music | $0.001003 / sec | $0.0008024 / sec | −20% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | text | $0.01302 / $0.02604 | $0.0105 / $0.021 | −19% |
| [GPT-6 Sol](https://martllm.com/models/openai/gpt-6-sol) | text | $1.09 / $5.46 | $0.882 / $4.41 | −19% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | text | $0.01229 / $0.02457 | $0.009923 / $0.01985 | −19% |
| [GPT-6 Luna](https://martllm.com/models/openai/gpt-6-luna) | text | $0.05565 / $0.2782 | $0.04515 / $0.2258 | −19% |
| [Flux 3 Klein](https://martllm.com/models/black-forest-labs/flux-3-klein) | image | $0.0084 / image | $0.006854 / image | −18% |
| [MiniMax M2](https://martllm.com/models/minimax/minimax-m2) | text | $0.0693 / $0.2772 | $0.0567 / $0.2268 | −18% |
| [Muse Image](https://martllm.com/models/meta-llama/venice-muse-image) | image | $0.021 / image | $0.01744 / image | −17% |
| [Wan 2.6 Flash Image-to-Video](https://martllm.com/models/wan/wan-2-6-flash-image-to-video) | video | $0.03822 / sec | $0.03198 / sec | −16% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.03092 / $0.358 | $0.02593 / $0.3003 | −16% |
| [Seedream 5.0 Flash](https://martllm.com/models/bytedance/seedream-5-0-flash) | image | $0.0162 / image | $0.01371 / image | −15% |
| [PixVerse V6 Max](https://martllm.com/models/pixverse/pixverse-v6-max) | video | $0.024 / sec | $0.02031 / sec | −15% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | text | $6.20 / $30.98 | $5.25 / $26.25 | −15% |
| [Cosmos Predict (image-to-video)](https://martllm.com/models/nvidia/cosmos-predict-image-to-video) | video | $0.8731 / video | $0.7421 / video | −15% |
| [GPT Image 2.6 Sunburst (image-to-image)](https://martllm.com/models/openai/venice-gpt-image-2-6-sunburst-edit) | image | $0.105 / image | $0.08925 / image | −15% |
| [MiniMax M3](https://martllm.com/models/minimax/minimax-m3) | text | $0.1512 / $0.6048 | $0.1291 / $0.5166 | −15% |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | text | $1.03 / $3.23 | $0.882 / $2.77 | −14% |
| [MiMo-V2.6-Pro](https://martllm.com/models/xiaomi/mimo-v2.6-pro) | text | $0.2969 / $0.5938 | $0.2558 / $0.5116 | −14% |
| [Palmyra Vision 7B](https://martllm.com/models/writer/palmyra-vision-7b) | text | $0.04725 / $0.189 | $0.04095 / $0.1638 | −13% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | text | $0.3061 / $2.00 | $0.2677 / $1.93 | in −13% / out −4% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | text | $0.06237 / $0.1109 | $0.06006 / $0.09702 | in −4% / out −13% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | text | $0.189 / $1.13 | $0.1654 / $0.9922 | −12% |
| [Qwen 3 235B A22B Thinking 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.1512 / $1.18 | $0.1323 / $1.03 | −12% |
| [Grok Imagine Reference To Video Private (reference-to-video)](https://martllm.com/models/x-ai/grok-imagine-reference-to-video-private) | video | $0.063 / sec | $0.05544 / sec | −12% |
| [GPT-6 Luna Decisions (OpenAI)](https://martllm.com/models/openai/gpt-6-luna-decisions) | other | $0.0588 / $0 | $0.0525 / $0 | in −11% / out – |
| [Z.ai: GLM 5.3 FlashX](https://martllm.com/models/z-ai/glm-5.3-flashx) | text | $0.2603 / $0.8794 | $0.2331 / $0.7875 | −10% |
| [Qwen: Qwen3.7 Flash](https://martllm.com/models/qwen/qwen3.7-flash) | text | $0.02174 / $0.09419 | $0.01953 / $0.08463 | −10% |
| [Kling O3 Standard Text-to-Video](https://martllm.com/models/kling/kling-o3-standard-text-to-video) | video | $0.1295 / sec | $0.1164 / sec | −10% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | text | $0.84 / $4.20 | $0.756 / $3.78 | −10% |
| [Kling 2.6 Pro Text-to-Video](https://martllm.com/models/kling/kling-2-6-pro-text-to-video) | video | $0.1617 / sec | $0.1455 / sec | −10% |
| [LTX 2 v2.3 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.07 / sec | $0.063 / sec | −10% |
| [LTX 2 v2.3 Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.09275 / sec | $0.08347 / sec | −10% |
| [Wan 3.0 Prime Pro Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-pro-image-to-video) | video | $0.3478 / sec | $0.313 / sec | −10% |
| [Wan 3.0 Prime Pro Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-pro-reference-to-video) | video | $0.3478 / sec | $0.313 / sec | −10% |
| [Wan 3.0 Prime Pro Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-pro-text-to-video) | video | $0.3478 / sec | $0.313 / sec | −10% |
| [Venice Video Gen (legacy alias)](https://martllm.com/models/venice/video-gen) | video | $0.168 / sec | $0.1512 / sec | −10% |
| [Vidu Q3 Text-to-Video](https://martllm.com/models/vidu/vidu-q3-text-to-video) | video | $0.203 / sec | $0.1827 / sec | −10% |
| [Wan 2.7 (reference-to-video)](https://martllm.com/models/wan/wan-2-7-reference-to-video) | video | $0.1155 / sec | $0.104 / sec | −10% |
| [Grok Imagine 1.5 Lite Text-to-Video](https://martllm.com/models/x-ai/venice-grok-imagine-1-5-lite-text-to-video) | video | $0.0252 / sec | $0.02268 / sec | −10% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | text | $0.1095 / $0.462 | $0.1058 / $0.4158 | in −3% / out −10% |
| [Vidu Q4](https://martllm.com/models/vidu/vidu-q4-image-to-video) | video | $0.036 / sec | $0.0396 / sec | +10% |
| [NVIDIA Nemotron 3 Ultra 550B](https://martllm.com/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.1969 / $0.9844 | $0.2166 / $1.08 | +10% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | text | $0.6615 / $2.08 | $0.7256 / $2.30 | in +10% / out +11% |
| [DeepSeek V4 Flash 0731 Fast](https://martllm.com/models/deepseek/deepseek-v4-flash-0731-fast) | text | $0.272 / $0.5439 | $0.3014 / $0.6027 | +11% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | text | $0.2205 / $0.882 | $0.2355 / $0.9781 | in +7% / out +11% |
| [MiniMax M3 Preview](https://martllm.com/models/minimax/minimax-m3-preview) | text | $0.2299 / $0.9198 | $0.2551 / $1.02 | +11% |
| [MiniMax H3 Image (image-to-image)](https://martllm.com/models/minimax/venice-minimax-h3-image-edit) | image | $0.0567 / image | $0.063 / image | +11% |
| [Thinking Machines: Inkling](https://martllm.com/models/thinking-machines/inkling) | text | $0.861 / $3.49 | $0.9471 / $3.90 | in +10% / out +12% |
| [GLM-4.6](https://martllm.com/models/z-ai/glm-4.6) | text | $0.1896 / $0.7718 | $0.2122 / $0.8636 | +12% |
| [xAI v1 TTS](https://martllm.com/models/x-ai/tts-xai-v1) | speech | $0.01533 / 1K chars | $0.01717 / 1K chars | +12% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $0.2285 / $0.457 | $0.2567 / $0.5133 | +12% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | text | $0.01509 / $0.04528 | $0.01706 / $0.05119 | +13% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | music | $0.001755 / sec | $0.002006 / sec | +14% |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-sound-effects-v1-0) | music | $0.001579 / sec | $0.001805 / sec | +14% |
| [Qwen 3.7 Plus](https://martllm.com/models/qwen/qwen3.7-plus) | text | $0.3937 / $1.57 | $0.4515 / $1.81 | +15% |
| [GLM-5 Turbo](https://martllm.com/models/z-ai/glm-5-turbo) | text | $0.8568 / $2.86 | $0.9828 / $3.28 | +15% |
| [Grok 4.3](https://martllm.com/models/x-ai/grok-4.3) | text | $0.4026 / $0.8023 | $0.4622 / $0.9212 | +15% |
| [GPT-5.6 Sol](https://martllm.com/models/openai/gpt-5.6-sol) | text | $1.64 / $8.19 | $1.89 / $9.45 | +15% |
| [GPT-5.4 Image 2](https://martllm.com/models/openai/gpt-5.4-image-2) | image | $5.80 / $10.87 | $6.72 / $12.60 | +16% |
| [Grok Imagine Image To Video Private (image-to-video)](https://martllm.com/models/x-ai/grok-imagine-image-to-video-private) | video | $0.04725 / sec | $0.05481 / sec | +16% |
| [GPT-5 Image Mini](https://martllm.com/models/openai/gpt-5-image-mini) | image | $2.10 / $1.68 | $2.47 / $1.97 | in +17% / out +18% |
| [GLM 5V Turbo](https://martllm.com/models/z-ai/glm-5v-turbo) | text | $0.8568 / $2.86 | $1.01 / $3.36 | +18% |
| [Vidu Q4 Reference](https://martllm.com/models/vidu/vidu-q4-reference-to-video) | video | $0.036 / sec | $0.04265 / sec | +18% |
| [Aion 3.0](https://martllm.com/models/aion-labs/aion-3-0) | text | $2.17 / $4.35 | $2.58 / $5.17 | +19% |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-text-to-video) | video | $0.01969 / sec | $0.0235 / sec | +19% |
| [Kling 4.0 Flash Image-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-image-to-video) | video | $0.08151 / sec | $0.09747 / sec | +20% |
| [MiMo-V2.5](https://martllm.com/models/xiaomi/mimo-v2-5) | text | $0.2982 / $1.49 | $0.357 / $1.78 | +20% |
| [Kling 2.5 Turbo Pro Text-to-Video](https://martllm.com/models/kling/kling-2-5-turbo-pro-text-to-video) | video | $0.06143 / sec | $0.07371 / sec | +20% |
| [Kling V3 Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-standard-image-to-video) | video | $0.1103 / sec | $0.1323 / sec | +20% |
| [Krea 2 Turbo (Venice)](https://martllm.com/models/krea/venice-krea-2-turbo) | image | $0.0315 / image | $0.0378 / image | +20% |
| [GPT Image 2.5 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-flare) | image | $0.05513 / image | $0.06615 / image | +20% |
| [ACE-Step 1.5 (Venice)](https://martllm.com/models/venice/ace-step-15) | music | $0.02453 / track | $0.02943 / track | +20% |
| [Seedance 2.5 Flash Image-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-flash-image-to-video-basic) | video | $0.06621 / sec | $0.07946 / sec | +20% |
| [Qwen3 VL 235B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-thinking) | text | $0.1389 / $1.26 | $0.1698 / $1.54 | +22% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | text | $0.002835 / $0.01418 | $0.003465 / $0.01733 | +22% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | text | $5.04 / $25.20 | $6.30 / $31.50 | +25% |
| [Gemini Omni Flash (image-to-video)](https://martllm.com/models/google/gemini-omni-flash-image-to-video) | video | $0.08269 / sec | $0.1047 / sec | +27% |
| [Seedream V5 Lite (Venice)](https://martllm.com/models/venice/seedream-v5-lite) | image | $0.02888 / image | $0.03675 / image | +27% |
| [MiniMax H3](https://martllm.com/models/minimax/minimax-h3) | video | $0.042 / sec | $0.05437 / sec | +29% |
| [GPT-5.6 Terra](https://martllm.com/models/openai/gpt-5.6-terra) | text | $0.756 / $4.54 | $0.987 / $5.92 | +31% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | text | $0.07875 / $0.1575 | $0.105 / $0.21 | +33% |
| [Venice SD35](https://martllm.com/models/venice/sd35) | image | $0.0063 / image | $0.0084 / image | +33% |
| [DeepSeek V4 Flash 0731](https://martllm.com/models/deepseek/deepseek-v4-flash-0731) | text | $0.05051 / $0.101 | $0.06825 / $0.1365 | +35% |
| [MiniMax H3 Reference](https://martllm.com/models/minimax/minimax-h3-reference-to-video) | video | $0.04 / sec | $0.05437 / sec | +36% |
| [Kimi K2](https://martllm.com/models/moonshotai/kimi-k2) | text | $0.4249 / $1.71 | $0.5985 / $2.42 | +41% |
| [MAI Image 2.7](https://martllm.com/models/microsoft/mai-image-2-7) | image | $0.03675 / image | $0.05238 / image | +43% |
| [Ideogram V4.6](https://martllm.com/models/ideogram/ideogram-v4-6) | image | $0.09555 / image | $0.1362 / image | +43% |
| [Krea 3](https://martllm.com/models/krea/krea-3) | image | $0.05145 / image | $0.07333 / image | +43% |
| [MAI Image 2.7 Flash](https://martllm.com/models/microsoft/mai-image-2-7-flash) | image | $0.0147 / image | $0.02095 / image | +43% |
| [Seedream V5.5 (Venice)](https://martllm.com/models/bytedance/venice-seedream-v5-5) | image | $0.01521 / image | $0.022 / image | +45% |
| [Whisper Large V3 (Venice)](https://martllm.com/models/venice/whisper-large-v3) | transcription | $0.00327 / minute | $0.004774 / minute | +46% |
| [Meta: Muse Spark 1.3](https://martllm.com/models/meta-llama/muse-spark-1.3) | text | $0.7219 / $2.45 | $1.06 / $3.61 | +47% |
| [Qwen3.8 2.4T A95B](https://martllm.com/models/qwen/qwen3.8-2.4t-a95b) | text | $0.819 / $2.46 | $1.26 / $3.78 | +54% |
| [Grok 4.20 Multi-Agent Beta](https://martllm.com/models/x-ai/grok-4.20-multi-agent-beta) | text | $0.6571 / $1.31 | $1.04 / $2.08 | +59% |
| [Qwen Image 2 Pro (Venice)](https://martllm.com/models/venice/qwen-image-2-pro) | image | $0.0525 / image | $0.084 / image | +60% |
| [MiniMax M2.5](https://martllm.com/models/minimax/minimax-m2.5) | text | $0.06237 / $0.2195 | $0.1021 / $0.3591 | +64% |
| [Qwen 3.6 35B A3B](https://martllm.com/models/qwen/qwen3-6-35b-a3b) | text | $0.04095 / $0.4095 | $0.0672 / $0.672 | +64% |
| [Gemini Omni Flash 1.1](https://martllm.com/models/google/gemini-omni-flash-1-1) | video | $0.02162 / sec | $0.0357 / sec | +65% |
| [Whisper Large V3 (STT)](https://martllm.com/models/venice/whisper-large-v3) | transcription | $0.002943 / minute | $0.00497 / minute | +69% |
| [Parakeet ASR (Venice)](https://martllm.com/models/venice/parakeet-asr) | transcription | $0.002943 / minute | $0.00497 / minute | +69% |
| [GPT Image 2.5 Sunburst (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-sunburst) | image | $0.0315 / image | $0.055 / image | +75% |
| [Hailuo 2.3 Standard](https://martllm.com/models/minimax/hailuo-2-3-standard-image-to-video) | video | $0.025 / sec | $0.04645 / sec | +86% |
| [inclusionAI: Ling 3.1 Flash](https://martllm.com/models/inclusionai/ling-3.1-flash) | text | $0.04111 / $0.1233 | $0.07875 / $0.2362 | +92% |
| [Tencent: Hy4 flash](https://martllm.com/models/tencent/hy4-flash) | text | $0.02977 / $0.1195 | $0.05953 / $0.239 | +100% |
| [Whisper 1 (Venice, legacy alias)](https://martllm.com/models/venice/whisper-1) | transcription | $0.002616 / minute | $0.005363 / minute | +105% |
| [Nano Banana 2 Lite (Venice)](https://martllm.com/models/google/venice-nano-banana-2-lite) | image | $0.021 / image | $0.04725 / image | +125% |
| [GPT Image 2.5 Flare (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-flare-edit) | image | $0.0315 / image | $0.0756 / image | +140% |
| [GPT Image 2.5 Sunburst (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-sunburst-edit) | image | $0.0315 / image | $0.0756 / image | +140% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | text | $0.0063 / $0.01974 | $0.01575 / $0.04935 | +150% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | text | $0.5775 / $1.73 | $1.78 / $5.36 | +209% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | text | $0.0441 / $0.2142 | $0.1599 / $0.7508 | in +263% / out +251% |
| [Qwen3.5 Flash](https://martllm.com/models/qwen/qwen3.5-flash) | text | $0.02084 / $0.08337 | $0.1029 / $0.4116 | +394% |
| [Qwen3.5 Plus](https://martllm.com/models/qwen/qwen3.5-plus) | text | $0.05419 / $0.3251 | $0.2675 / $1.61 | +394% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | text | $0.001523 / $0.00525 | $0.01066 / $0.03675 | +600% |

</details>


## 2026-11-24 (vs 2026-11-23)

**Official list price changes (15)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [NVIDIA Nemotron 3 Super 120B](https://martllm.com/models/nvidia/nemotron-3-super-120b) | text | $0.0775 / $0.425 | $0.075 / $0.40 | in −3% / out −6% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.13 / $0.50 | $0.127 / $0.475 | in −2% / out −5% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | text | $0.20 / $2.30 | $0.20 / $2.20 | in 0% / out −4% |
| [Whisper Large V3 (STT)](https://martllm.com/models/venice/whisper-large-v3) | transcription | – | $0.006 / minute |  |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-text-to-video) | video | – | $0.025 / sec |  |
| [MiniMax H3 Image](https://martllm.com/models/minimax/venice-minimax-h3-image) | image | – | $0.04 / image |  |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | music | – | $0.04 / track |  |
| [Grok Imagine Text-to-Video](https://martllm.com/models/x-ai/grok-imagine-text-to-video) | video | $0.0895 / sec | $0.09 / sec | +1% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | text | $1.31 / $3.96 | $1.32 / $3.96 | in +1% / out 0% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.147 / $0.60 | $0.1485 / $0.64 | in +1% / out +7% |
| [inclusionAI: Ling 3.1 Flash](https://martllm.com/models/inclusionai/ling-3.1-flash) | text | $0.06 / $0.18 | $0.0675 / $0.2025 | +13% |
| [MiniMax M2.7](https://martllm.com/models/minimax/minimax-m2.7) | text | $0.375 / $1.32 | $0.375 / $1.50 | in 0% / out +14% |
| [MiniMax H3 Hyper Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-image-to-video) | video | $0.035 / sec | $0.11 / sec | +214% |
| [MiniMax H3](https://martllm.com/models/minimax/minimax-h3) | video | $0.04 / sec | $0.13 / sec | +225% |
| [MiniMax H3 Reference](https://martllm.com/models/minimax/minimax-h3-reference-to-video) | video | $0.04 / sec | $0.13 / sec | +225% |

**New models (20)**

| Model | Category | Official price | MartLLM price |
|---|---|---|---|
| [Black Forest Labs/FLUX 2 DEV](https://martllm.com/models/black-forest-labs/flux-2-dev) | image | $0.075 / image | $0.0612 / image |
| [FLUX Dev](https://martllm.com/models/black-forest-labs/flux-dev) | image | $0.10 / image | $0.0816 / image |
| [FLUX.1 Kontext Max](https://martllm.com/models/black-forest-labs/flux-kontext-max) | image | $0.08 / image | $0.06086 / image |
| [FLUX.1 Kontext Pro](https://martllm.com/models/black-forest-labs/flux-kontext-pro) | image | $0.04 / image | $0.03043 / image |
| [Seedance 1.0 Pro Quality](https://martllm.com/models/bytedance/seedance-1-0-pro-quality) | video | $0.0204 / sec | $0.0194 / sec |
| [Ideogram V4.6](https://martllm.com/models/ideogram/ideogram-v4-6) | image | $0.13 / image | $0.09555 / image |
| [Kling Image](https://martllm.com/models/kling/kling-image) | image | $0.007 / image | $0.006783 / image |
| [Kling multi-image to image](https://martllm.com/models/kling/kling-multi-image2image) | image | $0.056 / image | $0.05426 / image |
| [Kling O1](https://martllm.com/models/kling/kling-o1) | video | $0.0672 / sec | $0.0639 / sec |
| [Krea 3](https://martllm.com/models/krea/krea-3) | image | $0.07 / image | $0.05145 / image |
| [MAI Image 2.7](https://martllm.com/models/microsoft/mai-image-2-7) | image | $0.05 / image | $0.03675 / image |
| [MAI Image 2.7 Flash](https://martllm.com/models/microsoft/mai-image-2-7-flash) | image | $0.02 / image | $0.0147 / image |
| [Gen4-image](https://martllm.com/models/runway/gen4-image) | image | $0.01 / image | $0.00816 / image |
| [Gen4-image-turbo](https://martllm.com/models/runway/gen4-image-turbo) | image | $0.02 / image | $0.01632 / image |
| [SkyReels V4 Fast](https://martllm.com/models/skywork/skyreels-v4-fast) | video | $0.064 / sec | $0.06086 / sec |
| [SkyReels V4 Standard](https://martllm.com/models/skywork/skyreels-v4-std) | video | $0.088 / sec | $0.08368 / sec |
| [Hunyuan Image 3.5 Preview](https://martllm.com/models/tencent/hunyuan-image-3-5-preview) | image | $0.0192 / image | $0.01826 / image |
| [Vidu Q3 Pro](https://martllm.com/models/vidu/viduq3-pro) | video | $0.056 / sec | $0.05325 / sec |
| [Grok Imagine 1.5 Edit](https://martllm.com/models/x-ai/grok-imagine-1-5-edit) | image | $0.015 / image | $0.01426 / image |
| [GLM 5.4](https://martllm.com/models/z-ai/glm-5.4) | text | – | $1.03 / $3.23 |

**No longer listed (36)**: `anthropic/claude-opus-4.6-fast`, `anthropic/claude-opus-4.7-fast`, `bytedance/seedance-2-5`, `kling/kling-video-o3-standard-image-to-video`, `kling/kling-video-o3-standard-text-to-video`, `kling/kling-video-v2-6-pro-image-to-video`, `kling/kling-video-v2-6-pro-text-to-video`, `kling/kling-video-v3-pro-image-to-video`, `kling/kling-video-v3-pro-text-to-video`, `kling/kling-video-v3-standard-image-to-video`, `kling/kling-video-v3-standard-text-to-video`, `google/veo-3.1`, `google/veo-3.1-fast`, `google/veo-3.1-fast-image-to-video`, `google/veo-3.1-image-to-video`, `vidu/viduq3-image-to-video`, `vidu/viduq3-text-to-video`, `wan/wan2-7-image-to-video`, `wan/wan2-7-text-to-video`, `google/gemini-omni-flash`, `google/venice-gemini-omni-flash-1-1-image-to-video`, `google/venice-gemini-omni-flash-1-1-text-to-video`, `happyhorse/happyhorse-1-1`, `kling/kling-3-0-turbo`, `kling/venice-kling-v4-image-to-video`, `kling/venice-kling-v4-reference-to-video`, `kling/venice-kling-v4-text-to-video`, `minimax/venice-minimax-h3-image-to-video`, `minimax/venice-minimax-h3-text-to-video`, `qwen/venice-wan-3-0-image-to-video`, `qwen/venice-wan-3-0-prime-image-to-video`, `qwen/venice-wan-3-0-prime-text-to-video`, `qwen/venice-wan-3-0-text-to-video`, `venice/runway-gen4-5-text`, `venice/seedream-v4`, `z-ai/e2ee-glm-4.7-flash`

<details><summary>MartLLM price moves of 10% or more (183)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | text | $0.01606 / $0.08032 | $0.002835 / $0.01418 | −82% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.05198 / $0.2079 | $0.01848 / $0.07392 | −64% |
| [Gemini 3.8 Flash](https://martllm.com/models/google/gemini-3.8-flash) | text | $0.252 / $1.26 | $0.1024 / $0.5119 | −59% |
| [Whisper Large V3 (STT)](https://martllm.com/models/venice/whisper-large-v3) | transcription | $0.00654 / minute | $0.002943 / minute | −55% |
| [GPT Image 2.5 Sunburst (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-sunburst-edit) | image | $0.0672 / image | $0.0315 / image | −53% |
| [NVIDIA Nemotron 3 Nano 30B](https://martllm.com/models/nvidia/nemotron-3-nano-30b-a3b) | text | $0.07875 / $0.315 | $0.0378 / $0.1512 | −52% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | text | $0.9187 / $3.67 | $0.4988 / $2.00 | −46% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | text | $0.777 / $3.88 | $0.462 / $2.31 | −41% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | text | $0.0126 / $0.0126 | $0.0084 / $0.0084 | −33% |
| [Seedream v4 — Edit (Venice)](https://martllm.com/models/bytedance/seedream-v4-edit) | image | $0.02625 / image | $0.01854 / image | −29% |
| [Gemma 3 27B](https://martllm.com/models/google/gemma-3-27b-it) | text | $0.05712 / $0.1428 | $0.04116 / $0.1029 | −28% |
| [Seedance 2.5 Flash Image-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-flash-image-to-video-basic) | video | $0.08828 / sec | $0.06621 / sec | −25% |
| [MiniMax H3 Image](https://martllm.com/models/minimax/venice-minimax-h3-image) | image | $0.042 / image | $0.0315 / image | −25% |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | music | $0.0436 / track | $0.0327 / track | −25% |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-text-to-video) | video | $0.02625 / sec | $0.01969 / sec | −25% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | text | $0.104 / $0.208 | $0.07875 / $0.1575 | −24% |
| [Qwen Image 2 Pro (Venice)](https://martllm.com/models/venice/qwen-image-2-pro) | image | $0.06825 / image | $0.0525 / image | −23% |
| [Claude Opus 5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5-fast) | text | $8.71 / $43.58 | $6.72 / $33.60 | −23% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $0.2957 / $0.5914 | $0.2285 / $0.457 | −23% |
| [Grok Imagine Text-to-Video](https://martllm.com/models/x-ai/grok-imagine-text-to-video) | video | $0.06108 / sec | $0.04725 / sec | −23% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | text | $0.5775 / $2.18 | $0.462 / $1.74 | −20% |
| [Seedream V5.5 (Venice)](https://martllm.com/models/bytedance/venice-seedream-v5-5) | image | $0.01874 / image | $0.01521 / image | −19% |
| [inclusionAI: Ling 3.1 Flash](https://martllm.com/models/inclusionai/ling-3.1-flash) | text | $0.04977 / $0.1493 | $0.04111 / $0.1233 | −17% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.2377 / $0.7131 | $0.1981 / $0.5942 | −17% |
| [Kling 4.0 Flash Image-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-image-to-video) | video | $0.09747 / sec | $0.08151 / sec | −16% |
| [Claude Opus 5](https://martllm.com/models/anthropic/claude-opus-5) | text | $2.57 / $12.86 | $2.15 / $10.76 | −16% |
| [GPT-5 Image Mini](https://martllm.com/models/openai/gpt-5-image-mini) | image | $2.49 / $2.00 | $2.10 / $1.68 | −16% |
| [Qwen 3 Coder 480B Turbo](https://martllm.com/models/qwen/qwen3-coder-turbo) | text | $0.3565 / $1.53 | $0.3014 / $1.29 | −15% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | text | $0.09954 / $0.2986 | $0.08442 / $0.2533 | −15% |
| [Claude Opus 4.6](https://martllm.com/models/anthropic/claude-opus-4.6) | text | $2.62 / $13.12 | $2.26 / $11.29 | −14% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | text | $0.9764 / $4.88 | $0.84 / $4.20 | −14% |
| [Z.ai: GLM 5.3 FlashX Legal](https://martllm.com/models/z-ai/glm-5.3-flashx-legal) | text | $0.3108 / $1.05 | $0.2681 / $0.9056 | −14% |
| [ElevenLabs Music v2.5](https://martllm.com/models/elevenlabs/elevenlabs-music-v2-5) | music | $0.6017 / track | $0.5189 / track | −14% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | text | $0.3523 / $2.31 | $0.3061 / $2.00 | −13% |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | text | $0.084 / $0.126 | $0.0735 / $0.1103 | in −13% / out −12% |
| [Qwen3 VL 235B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-thinking) | text | $0.1588 / $1.44 | $0.1389 / $1.26 | −12% |
| [Lyria 3 Pro](https://martllm.com/models/google-deepmind/lyria-3-pro) | music | $0.0872 / track | $0.0763 / track | −12% |
| [Gemini 3.5 Flash Lite](https://martllm.com/models/google/gemini-3-5-flash-lite) | text | $0.104 / $0.8662 | $0.09135 / $0.7612 | −12% |
| [DeepSeek V4 Flash E2EE](https://martllm.com/models/deepseek/e2ee-deepseek-v4-flash) | text | $0.1605 / $0.329 | $0.1414 / $0.2898 | −12% |
| [GPT-5.2](https://martllm.com/models/openai/gpt-5.2) | text | $1.01 / $8.09 | $0.9004 / $7.20 | −11% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | text | $0.7245 / $4.35 | $0.6458 / $3.87 | −11% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | text | $0.5016 / $1.56 | $0.4505 / $1.40 | −10% |
| [Qwen 3.5 35B A3B](https://martllm.com/models/qwen/qwen3.5-35b-a3b) | text | $0.1103 / $0.735 | $0.1213 / $0.8085 | +10% |
| [GPT-6 Sol](https://martllm.com/models/openai/gpt-6-sol) | text | $0.987 / $4.93 | $1.09 / $5.46 | +11% |
| [Claude Sonnet 5](https://martllm.com/models/anthropic/claude-sonnet-5) | text | $0.777 / $3.88 | $0.861 / $4.30 | +11% |
| [GPT-6 Luna Pro](https://martllm.com/models/openai/gpt-6-luna-pro) | text | $0.08505 / $0.4253 | $0.0945 / $0.4725 | +11% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | text | $0.02268 / $0.0756 | $0.0252 / $0.084 | +11% |
| [Whisper Large V3 (Venice)](https://martllm.com/models/venice/whisper-large-v3) | transcription | $0.002943 / minute | $0.00327 / minute | +11% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | text | $0.5954 / $1.87 | $0.6615 / $2.08 | +11% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | text | $0.04465 / $0.04465 | $0.04961 / $0.04961 | +11% |
| [Meta: Muse Spark Open](https://martllm.com/models/meta-llama/muse-spark-open) | text | $0.9319 / $3.17 | $1.04 / $3.53 | +11% |
| [Kimi K3 Fast](https://martllm.com/models/moonshotai/kimi-k3-fast-api) | text | $3.54 / $17.72 | $3.97 / $19.84 | +12% |
| [Qwen3.7 Max](https://martllm.com/models/qwen/qwen3.7-max) | text | $2.10 / $6.25 | $2.35 / $7.02 | +12% |
| [Gemini 3.6 Flash](https://martllm.com/models/google/gemini-3-6-flash) | text | $0.5591 / $2.80 | $0.63 / $3.15 | +13% |
| [Kling V3 Turbo Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-standard-image-to-video) | video | $0.09065 / sec | $0.1023 / sec | +13% |
| [Ideogram V4.5 (Venice)](https://martllm.com/models/ideogram/venice-ideogram-v4-5) | image | $0.1911 / image | $0.2157 / image | +13% |
| [Qwen Image 2.1 Turbo (Venice)](https://martllm.com/models/qwen/venice-qwen-image-2-1-turbo) | image | $0.0147 / image | $0.01659 / image | +13% |
| [Recraft V4 Pro (Venice)](https://martllm.com/models/venice/recraft-v4-pro) | image | $0.2132 / image | $0.2406 / image | +13% |
| [MiniMax M2.7](https://martllm.com/models/minimax/minimax-m2.7) | text | $0.2126 / $0.7484 | $0.2126 / $0.8505 | in 0% / out +14% |
| [Aion 3.5 Mini](https://martllm.com/models/aion-labs/aion-3-5-mini) | text | $0.6615 / $1.32 | $0.7534 / $1.51 | +14% |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | music | $0.002195 / sec | $0.002507 / sec | +14% |
| [GPT-6.2 Astra Pro](https://martllm.com/models/openai/gpt-6.2-astra-pro) | text | $6.97 / $34.86 | $7.98 / $39.90 | +14% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | text | $0.0693 / $0.1559 | $0.07938 / $0.1786 | +15% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | text | $1.49 / $4.89 | $1.71 / $5.61 | +15% |
| [OpenAI: GPT-6.1 Sol Pro](https://martllm.com/models/openai/gpt-6.1-sol-pro) | text | $1.68 / $8.40 | $1.93 / $9.66 | +15% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.04095 / $0.1575 | $0.04709 / $0.1811 | +15% |
| [Claude Sonnet 5.5](https://martllm.com/models/anthropic/claude-sonnet-5.5) | text | $0.966 / $4.83 | $1.11 / $5.57 | +15% |
| [ACE-Step 1.5 (Venice)](https://martllm.com/models/venice/ace-step-15) | music | $0.02125 / track | $0.02453 / track | +15% |
| [OpenAI: GPT-6.1 Terra Pro](https://martllm.com/models/openai/gpt-6.1-terra-pro) | text | $0.84 / $4.20 | $0.9765 / $4.88 | +16% |
| [Seed 2.1 Turbo](https://martllm.com/models/bytedance/seed-2-1-turbo) | text | $0.3412 / $1.71 | $0.399 / $2.00 | +17% |
| [LongCat Text-to-Video](https://martllm.com/models/meituan/longcat-text-to-video) | video | $0.04462 / sec | $0.0525 / sec | +18% |
| [Meta: Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder) | text | $2.35 / $11.76 | $2.77 / $13.86 | +18% |
| [Qwen 3 235B A22B Instruct 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-2507) | text | $0.07796 / $0.4331 | $0.09214 / $0.5119 | +18% |
| [Claude Sonnet 4.6](https://martllm.com/models/anthropic/claude-sonnet-4.6) | text | $1.29 / $6.46 | $1.54 / $7.72 | +20% |
| [GPT-6 Sol Pro](https://martllm.com/models/openai/gpt-6-sol-pro) | text | $1.68 / $8.40 | $2.02 / $10.08 | +20% |
| [Seedream V5 Pro (Venice)](https://martllm.com/models/bytedance/venice-seedream-v5-pro) | image | $0.02835 / image | $0.03423 / image | +21% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | text | $0.1377 / $0.6883 | $0.1676 / $0.8379 | +22% |
| [Gemini Omni Flash 1.1](https://martllm.com/models/google/gemini-omni-flash-1-1) | video | $0.01769 / sec | $0.02162 / sec | +22% |
| [Aion 3.5](https://martllm.com/models/aion-labs/aion-3-5) | text | $2.64 / $5.28 | $3.27 / $6.54 | +24% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | text | $1.73 / $8.66 | $2.15 / $10.76 | +24% |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | music | $0.04011 / 1K chars | $0.05014 / 1K chars | +25% |
| [Orpheus TTS](https://martllm.com/models/canopy-labs/tts-orpheus) | speech | $0.0545 / 1K chars | $0.06813 / 1K chars | +25% |
| [Inworld 1.5 Max TTS](https://martllm.com/models/inworld/tts-inworld-1-5-max) | speech | $0.0109 / 1K chars | $0.01362 / 1K chars | +25% |
| [Luma Uni 1 Max (image-to-image)](https://martllm.com/models/luma/luma-uni-1-max-edit) | image | $0.1092 / image | $0.1365 / image | +25% |
| [Chatterbox HD TTS](https://martllm.com/models/resemble-ai/tts-chatterbox-hd) | speech | $0.0436 / 1K chars | $0.0545 / 1K chars | +25% |
| [LTX 2 v2.3 Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.0742 / sec | $0.09275 / sec | +25% |
| [xAI Speech to Text v1 (Venice)](https://martllm.com/models/venice/xai-stt-v1) | transcription | $0.001482 / minute | $0.001874 / minute | +26% |
| [ElevenLabs Music (Venice)](https://martllm.com/models/venice/elevenlabs-music) | music | $0.5942 / track | $0.7521 / track | +27% |
| [Wan 3.0 Pro Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-pro-text-to-video) | video | $0.1938 / sec | $0.2484 / sec | +28% |
| [Qwen Image 3 Pro (Venice)](https://martllm.com/models/venice/qwen-image-3-pro) | image | $0.0315 / image | $0.04043 / image | +28% |
| [Chroma (Venice)](https://martllm.com/models/venice/chroma) | image | $0.00735 / image | $0.00945 / image | +29% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://martllm.com/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.0735 / sec | $0.0945 / sec | +29% |
| [GPT-5.6 Luna Pro](https://martllm.com/models/openai/gpt-5.6-luna-pro) | text | $0.1533 / $0.9198 | $0.1974 / $1.18 | +29% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | text | $0.21 / $0.63 | $0.273 / $0.819 | +30% |
| [ElevenLabs Scribe v2 (STT)](https://martllm.com/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.007537 / minute | $0.009939 / minute | +32% |
| [Kling O3 Pro (reference-to-video)](https://martllm.com/models/kling/kling-o3-pro-reference-to-video) | video | $0.1207 / sec | $0.161 / sec | +33% |
| [ElevenLabs TTS v4](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4) | music | $0.07521 / 1K chars | $0.1003 / 1K chars | +33% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | text | $0.03748 / $0.1386 | $0.04998 / $0.1848 | +33% |
| [Qwen Image 2 (image-to-image)](https://martllm.com/models/qwen/qwen-image-2-edit) | image | $0.0294 / image | $0.03938 / image | +34% |
| [Qwen3.8 2.4T A95B](https://martllm.com/models/qwen/qwen3.8-2.4t-a95b) | text | $0.609 / $1.83 | $0.819 / $2.46 | +34% |
| [Grok Imagine Reference To Video Private (reference-to-video)](https://martllm.com/models/x-ai/grok-imagine-reference-to-video-private) | video | $0.04655 / sec | $0.063 / sec | +35% |
| [Happyhorse 1.1 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.1181 / sec | $0.161 / sec | +36% |
| [Kling O3 Standard (reference-to-video)](https://martllm.com/models/kling/kling-o3-standard-reference-to-video) | video | $0.0945 / sec | $0.1295 / sec | +37% |
| [Kling O3 Standard Text-to-Video](https://martllm.com/models/kling/kling-o3-standard-text-to-video) | video | $0.0945 / sec | $0.1295 / sec | +37% |
| [Wan 2.7 (reference-to-video)](https://martllm.com/models/wan/wan-2-7-reference-to-video) | video | $0.084 / sec | $0.1155 / sec | +38% |
| [Runway Gen-4 Turbo](https://martllm.com/models/runway/runway-gen4-turbo) | video | $0.05145 / sec | $0.07087 / sec | +38% |
| [Kling 2.5 Turbo Pro Text-to-Video](https://martllm.com/models/kling/kling-2-5-turbo-pro-text-to-video) | video | $0.0441 / sec | $0.06143 / sec | +39% |
| [Kling 2.6 Pro (image-to-video)](https://martllm.com/models/kling/kling-2-6-pro-image-to-video) | video | $0.1155 / sec | $0.1617 / sec | +40% |
| [Kling 2.6 Pro Text-to-Video](https://martllm.com/models/kling/kling-2-6-pro-text-to-video) | video | $0.1155 / sec | $0.1617 / sec | +40% |
| [Wan 3.0 Prime Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-reference-to-video) | video | $0.06615 / sec | $0.09282 / sec | +40% |
| [Veo 3.1 Full Text-to-Video](https://martllm.com/models/google/veo3-1-full-text-to-video) | video | $0.3281 / sec | $0.462 / sec | +41% |
| [Longcat (image-to-video)](https://martllm.com/models/meituan/longcat-image-to-video) | video | $0.03724 / sec | $0.0525 / sec | +41% |
| [Runway Gen-4.5](https://martllm.com/models/runway/runway-gen4-5) | video | $0.1191 / sec | $0.168 / sec | +41% |
| [Gemini 3.1 Flash Lite](https://martllm.com/models/google/gemini-3.1-flash-lite) | text | $0.1706 / $1.02 | $0.2415 / $1.45 | +42% |
| [Seedance 2.5 Reference-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-reference-to-video-basic) | video | $0.0611 / sec | $0.08652 / sec | +42% |
| [Happyhorse 1.0 (reference-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.1135 / sec | $0.161 / sec | +42% |
| [Kling V3 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.1135 / sec | $0.161 / sec | +42% |
| [Wan 3.0 Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-reference-to-video) | video | $0.04802 / sec | $0.06825 / sec | +42% |
| [Gemini Omni Flash (reference-to-video)](https://martllm.com/models/google/gemini-omni-flash-reference-to-video) | video | $0.1051 / sec | $0.1496 / sec | +42% |
| [Ltx 2 V2.3 Full (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.06492 / sec | $0.09272 / sec | +43% |
| [Kling O3.4k (image-to-video)](https://martllm.com/models/kling/kling-o3-4k-image-to-video) | video | $0.3406 / sec | $0.4865 / sec | +43% |
| [Kling O3.4k (reference-to-video)](https://martllm.com/models/kling/kling-o3-4k-reference-to-video) | video | $0.3406 / sec | $0.4865 / sec | +43% |
| [Kling O3 4K Text-to-Video](https://martllm.com/models/kling/kling-o3-4k-text-to-video) | video | $0.3406 / sec | $0.4865 / sec | +43% |
| [Kling V3 4K Text-to-Video](https://martllm.com/models/kling/kling-v3-4k-text-to-video) | video | $0.3406 / sec | $0.4865 / sec | +43% |
| [Ovi Image-to-Video](https://martllm.com/models/ovi/ovi-image-to-video) | video | $0.03234 / sec | $0.0462 / sec | +43% |
| [PixVerse C1 Text-to-Video (Venice)](https://martllm.com/models/venice/pixverse-c1-t2v) | video | $0.03234 / sec | $0.0462 / sec | +43% |
| [Wan 2.5 Preview (image-to-video)](https://martllm.com/models/wan/wan-2-5-preview-image-to-video) | video | $0.04116 / sec | $0.0588 / sec | +43% |
| [LTX 2 v2.3 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.049 / sec | $0.07 / sec | +43% |
| [Luma Uni-1 (Venice)](https://martllm.com/models/luma/venice-luma-uni-1) | image | $0.03675 / image | $0.0525 / image | +43% |
| [Luma Uni-1 Max (Venice)](https://martllm.com/models/luma/venice-luma-uni-1-max) | image | $0.0882 / image | $0.126 / image | +43% |
| [Qwen Image 2.1 Pro (Venice)](https://martllm.com/models/qwen/venice-qwen-image-2-1-pro) | image | $0.03675 / image | $0.0525 / image | +43% |
| [Vidu Q3 (image-to-video)](https://martllm.com/models/vidu/vidu-q3-image-to-video) | video | $0.06615 / sec | $0.0945 / sec | +43% |
| [Seed Audio 1.0](https://martllm.com/models/bytedance/seed-audio-1-0) | music | $0.002194 / sec | $0.003134 / sec | +43% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.049 / sec | $0.07004 / sec | +43% |
| [Kling 2.5 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-2-5-turbo-pro-image-to-video) | video | $0.0441 / sec | $0.06615 / sec | +50% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | text | $0.0294 / $0.1428 | $0.0441 / $0.2142 | +50% |
| [Tencent: Hy4 preview](https://martllm.com/models/tencent/hy4-preview) | text | $0.3941 / $1.18 | $0.5955 / $1.79 | +51% |
| [Claude Opus 4.5](https://martllm.com/models/anthropic/claude-opus-4.5) | text | $2.05 / $10.24 | $3.15 / $15.75 | +54% |
| [GPT Image 1.5 (Venice)](https://martllm.com/models/venice/gpt-image-1.5) | image | $0.1774 / image | $0.273 / image | +54% |
| [Hunyuan Image 3.0 (Venice)](https://martllm.com/models/venice/hunyuan-image-v3) | image | $0.06143 / image | $0.0945 / image | +54% |
| [Qwen Image (Venice)](https://martllm.com/models/venice/qwen-image) | image | $0.02048 / image | $0.0315 / image | +54% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | music | $0.001128 / sec | $0.001755 / sec | +56% |
| [Qwen3 1.7B TTS](https://martllm.com/models/qwen/tts-qwen3-1-7b) | speech | $0.07848 / 1K chars | $0.1226 / 1K chars | +56% |
| [Stable Audio 2.5 (Venice)](https://martllm.com/models/venice/stable-audio-25) | music | $0.1674 / track | $0.2616 / track | +56% |
| [Wan 2.7 (Venice)](https://martllm.com/models/venice/wan-2.7) | image | $0.0252 / image | $0.03938 / image | +56% |
| [Wan 2.7 Pro (Venice)](https://martllm.com/models/venice/wan-2.7-pro) | image | $0.063 / image | $0.09844 / image | +56% |
| [Wan 2.7 Pro (image-to-image)](https://martllm.com/models/wan/wan-2-7-pro-edit) | image | $0.063 / image | $0.0987 / image | +57% |
| [Wan 2.6 (image-to-video)](https://martllm.com/models/wan/wan-2-6-image-to-video) | video | $0.0735 / sec | $0.1155 / sec | +57% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.01852 / $0.0756 | $0.02807 / $0.121 | in +52% / out +60% |
| [Kling V3 Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-standard-image-to-video) | video | $0.0686 / sec | $0.1103 / sec | +61% |
| [ElevenLabs TTS v3 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-v3) | music | $0.07521 / 1K chars | $0.1253 / 1K chars | +67% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | text | $1.31 / $6.56 | $2.21 / $11.03 | +68% |
| [GPT Image 2.5 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-5-flare) | image | $0.0315 / image | $0.05513 / image | +75% |
| [GPT-5.2 Codex](https://martllm.com/models/openai/gpt-5.2-codex) | text | $0.882 / $7.06 | $1.56 / $12.49 | +77% |
| [Qwen Image 2 (Venice)](https://martllm.com/models/venice/qwen-image-2) | image | $0.0294 / image | $0.0525 / image | +79% |
| [GPT OSS 20B](https://martllm.com/models/openai/e2ee-gpt-oss-20b-p) | text | $0.02625 / $0.09975 | $0.04725 / $0.1795 | +80% |
| [GPT-5.6 Terra](https://martllm.com/models/openai/gpt-5.6-terra) | text | $0.42 / $2.52 | $0.756 / $4.54 | +80% |
| [Wan 2.5 Preview Text-to-Video](https://martllm.com/models/wan/wan-2-5-preview-text-to-video) | video | $0.063 / sec | $0.1155 / sec | +83% |
| [Seedance 2.0 Fast Text-to-Video (Venice)](https://martllm.com/models/venice/seedance-2-fast-t2v) | video | $0.03984 / sec | $0.0735 / sec | +84% |
| [Pixverse C1 (image-to-video)](https://martllm.com/models/pixverse/pixverse-c1-image-to-video) | video | $0.0245 / sec | $0.04546 / sec | +86% |
| [Pixverse C1 (reference-to-video)](https://martllm.com/models/pixverse/pixverse-c1-reference-to-video) | video | $0.0245 / sec | $0.04546 / sec | +86% |
| [Pixverse C1 Transition (transition)](https://martllm.com/models/pixverse/pixverse-c1-transition) | video | $0.0245 / sec | $0.04546 / sec | +86% |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | $0.0686 / sec | $0.1307 / sec | +91% |
| [MiMo-V2.5-Pro](https://martllm.com/models/xiaomi/mimo-v2.5-pro) | text | $0.2558 / $0.9592 | $0.504 / $1.89 | +97% |
| [Z-Image Turbo (Venice)](https://martllm.com/models/venice/z-image-turbo) | image | $0.0042 / image | $0.008295 / image | +98% |
| [Kimi K3](https://martllm.com/models/moonshotai/kimi-k3) | text | $0.1795 / $0.945 | $0.3591 / $1.89 | +100% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | text | $0.2888 / $0.8662 | $0.5775 / $1.73 | +100% |
| [Kling V3 Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-pro-image-to-video) | video | $0.09065 / sec | $0.1925 / sec | +112% |
| [Kling V3 Pro Text-to-Video](https://martllm.com/models/kling/kling-v3-pro-text-to-video) | video | $0.09065 / sec | $0.1932 / sec | +113% |
| [Qwen: Qwen3.8 Max (0902)](https://martllm.com/models/qwen/qwen3.8-max-0902) | text | $0.126 / $0.378 | $0.273 / $0.819 | +117% |
| [GPT-5 Image](https://martllm.com/models/openai/gpt-5-image) | image | $4.83 / $4.83 | $10.50 / $10.50 | +117% |
| [Veo3.1 Fast (image-to-video)](https://martllm.com/models/google/veo3-1-fast-image-to-video) | video | $0.07875 / sec | $0.1732 / sec | +120% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | text | $0.07111 / $0.7056 | $0.1592 / $1.58 | +124% |
| [HappyHorse 1.0 Text-to-Video](https://martllm.com/models/happyhorse/happyhorse-1-0-text-to-video) | video | $0.1221 / sec | $0.2765 / sec | +126% |
| [Seedream 4.5](https://martllm.com/models/bytedance/seedream-4.5) | image | $0.0126 / image | $0.0294 / image | +133% |
| [Wan 2.6 Text-to-Video](https://martllm.com/models/wan/wan-2-6-text-to-video) | video | $0.0735 / sec | $0.1743 / sec | +137% |
| [Grok Imagine High Quality (Venice)](https://martllm.com/models/venice/grok-imagine-quality) | image | $0.02625 / image | $0.063 / image | +140% |
| [Seedance 2.5 Text-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-text-to-video-basic) | video | $0.03423 / sec | $0.08405 / sec | +146% |
| [MiniMax H3 Reference](https://martllm.com/models/minimax/minimax-h3-reference-to-video) | video | $0.01592 / sec | $0.04 / sec | +151% |
| [MiniMax H3](https://martllm.com/models/minimax/minimax-h3) | video | $0.01592 / sec | $0.042 / sec | +164% |
| [MiniMax H3 Hyper Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-image-to-video) | video | $0.02903 / sec | $0.09125 / sec | +214% |
| [Grok Imagine 2.0 (image-to-image)](https://martllm.com/models/x-ai/grok-imagine-image-2-0-edit) | image | $0.021 / image | $0.07702 / image | +267% |
| [Veo 3.1 Fast Text-to-Video](https://martllm.com/models/google/veo3-1-fast-text-to-video) | video | $0.0175 / sec | $0.1213 / sec | +593% |

</details>


## 2026-11-23 (vs 2026-11-22)

**Official list price changes (59)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Grok Imagine Text-to-Video](https://martllm.com/models/x-ai/grok-imagine-text-to-video) | video | $0.09 / sec | $0.0895 / sec | −1% |
| [Flux 2 Max — Edit (Venice)](https://martllm.com/models/black-forest-labs/flux-2-max-edit) | image | – | $0.19 / image |  |
| [Seedance 2.0 Mini (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-reference-to-video) | video | – | $0.044 / sec |  |
| [Seed Audio 1.0](https://martllm.com/models/bytedance/seed-audio-1-0) | music | – | $0.002875 / sec |  |
| [Gemini Omni Flash (image-to-video)](https://martllm.com/models/google/gemini-omni-flash-image-to-video) | video | – | $0.1425 / sec |  |
| [Gemini Omni Flash (reference-to-video)](https://martllm.com/models/google/gemini-omni-flash-reference-to-video) | video | – | $0.1425 / sec |  |
| [Veo3.1 Full (image-to-video)](https://martllm.com/models/google/veo3-1-full-image-to-video) | video | – | $0.44 / sec |  |
| [Veo 3.1 Full Text-to-Video](https://martllm.com/models/google/veo3-1-full-text-to-video) | video | – | $0.44 / sec |  |
| [Happyhorse 1.0 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-image-to-video) | video | – | $0.1533 / sec |  |
| [Happyhorse 1.0 (reference-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-reference-to-video) | video | – | $0.1533 / sec |  |
| [HappyHorse 1.0 Text-to-Video](https://martllm.com/models/happyhorse/happyhorse-1-0-text-to-video) | video | – | $0.2633 / sec |  |
| [Happyhorse 1.1 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-1-image-to-video) | video | – | $0.1533 / sec |  |
| [Happyhorse 1.1 (reference-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-1-reference-to-video) | video | – | $0.1533 / sec |  |
| [Ideogram V4.5 (image-to-image)](https://martllm.com/models/ideogram/ideogram-v4-5-edit) | image | – | $0.26 / image |  |
| [Kling 2.5 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-2-5-turbo-pro-image-to-video) | video | – | $0.078 / sec |  |
| [Kling 2.5 Turbo Pro Text-to-Video](https://martllm.com/models/kling/kling-2-5-turbo-pro-text-to-video) | video | – | $0.078 / sec |  |
| [Kling 2.6 Pro (image-to-video)](https://martllm.com/models/kling/kling-2-6-pro-image-to-video) | video | – | $0.154 / sec |  |
| [Kling 2.6 Pro Text-to-Video](https://martllm.com/models/kling/kling-2-6-pro-text-to-video) | video | – | $0.154 / sec |  |
| [Kling O3.4k (image-to-video)](https://martllm.com/models/kling/kling-o3-4k-image-to-video) | video | – | $0.4633 / sec |  |
| [Kling O3.4k (reference-to-video)](https://martllm.com/models/kling/kling-o3-4k-reference-to-video) | video | – | $0.4633 / sec |  |
| [Kling O3 4K Text-to-Video](https://martllm.com/models/kling/kling-o3-4k-text-to-video) | video | – | $0.4633 / sec |  |
| [Kling O3 Pro (reference-to-video)](https://martllm.com/models/kling/kling-o3-pro-reference-to-video) | video | – | $0.1533 / sec |  |
| [Kling O3 Pro Text-to-Video](https://martllm.com/models/kling/kling-o3-pro-text-to-video) | video | – | $0.1533 / sec |  |
| [Kling O3 Standard (reference-to-video)](https://martllm.com/models/kling/kling-o3-standard-reference-to-video) | video | – | $0.1233 / sec |  |
| [Kling O3 Standard Text-to-Video](https://martllm.com/models/kling/kling-o3-standard-text-to-video) | video | – | $0.123 / sec |  |
| [Kling V3 4K Text-to-Video](https://martllm.com/models/kling/kling-v3-4k-text-to-video) | video | – | $0.4633 / sec |  |
| [Kling V3 Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-pro-image-to-video) | video | – | $0.1833 / sec |  |
| [Kling V3 Pro Text-to-Video](https://martllm.com/models/kling/kling-v3-pro-text-to-video) | video | – | $0.184 / sec |  |
| [Kling V3 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-pro-image-to-video) | video | – | $0.1533 / sec |  |
| [Kling V3 Turbo Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-standard-image-to-video) | video | – | $0.1233 / sec |  |
| [Kling 4.0 Flash Image-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-image-to-video) | video | – | $0.1175 / sec |  |
| [Ltx 2 V2.3 Fast (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | – | $0.0667 / sec |  |
| [LTX 2 v2.3 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | – | $0.06667 / sec |  |
| [Ltx 2 V2.3 Full (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | – | $0.0883 / sec |  |
| [LTX 2 v2.3 Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | – | $0.08833 / sec |  |
| [Luma Uni 1 Max (image-to-image)](https://martllm.com/models/luma/luma-uni-1-max-edit) | image | – | $0.13 / image |  |
| [Longcat (image-to-video)](https://martllm.com/models/meituan/longcat-image-to-video) | video | – | $0.05 / sec |  |
| [LongCat Text-to-Video](https://martllm.com/models/meituan/longcat-text-to-video) | video | – | $0.05 / sec |  |
| [Ovi Image-to-Video](https://martllm.com/models/ovi/ovi-image-to-video) | video | – | $0.044 / sec |  |
| [Pixverse C1 (image-to-video)](https://martllm.com/models/pixverse/pixverse-c1-image-to-video) | video | – | $0.0433 / sec |  |
| [Pixverse C1 (reference-to-video)](https://martllm.com/models/pixverse/pixverse-c1-reference-to-video) | video | – | $0.0433 / sec |  |
| [Pixverse C1 Transition (transition)](https://martllm.com/models/pixverse/pixverse-c1-transition) | video | – | $0.0433 / sec |  |
| [Wan 3.0 Pro Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-pro-text-to-video) | video | – | $0.2366 / sec |  |
| [Runway Gen-4.5](https://martllm.com/models/runway/runway-gen4-5) | video | – | $0.16 / sec |  |
| [Runway Gen-4 Turbo](https://martllm.com/models/runway/runway-gen4-turbo) | video | – | $0.0675 / sec |  |
| [ElevenLabs Music (Venice)](https://martllm.com/models/venice/elevenlabs-music) | music | – | $0.69 / track |  |
| [ElevenLabs TTS v3 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-v3) | music | – | $0.115 / 1K chars |  |
| [Runway Gen-4.5 Text-to-Video (Venice)](https://martllm.com/models/venice/runway-gen4-5-text) | video | – | $0.16 / sec |  |
| [Vidu Q3 (image-to-video)](https://martllm.com/models/vidu/vidu-q3-image-to-video) | video | – | $0.09 / sec |  |
| [Vidu Q3 Text-to-Video](https://martllm.com/models/vidu/vidu-q3-text-to-video) | video | – | $0.1933 / sec |  |
| [Wan 2.5 Preview (image-to-video)](https://martllm.com/models/wan/wan-2-5-preview-image-to-video) | video | – | $0.056 / sec |  |
| [Wan 2.6 (image-to-video)](https://martllm.com/models/wan/wan-2-6-image-to-video) | video | – | $0.11 / sec |  |
| [Wan 2.6 Text-to-Video](https://martllm.com/models/wan/wan-2-6-text-to-video) | video | – | $0.166 / sec |  |
| [Wan 2.7 (reference-to-video)](https://martllm.com/models/wan/wan-2-7-reference-to-video) | video | – | $0.11 / sec |  |
| [Wan 2.7 Text-to-Video](https://martllm.com/models/wan/wan-2-7-text-to-video) | video | – | $0.11 / sec |  |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://martllm.com/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | – | $0.09 / sec |  |
| [Grok Imagine Image To Video Private (image-to-video)](https://martllm.com/models/x-ai/grok-imagine-image-to-video-private) | video | – | $0.06 / sec |  |
| [Grok Imagine Reference To Video Private (reference-to-video)](https://martllm.com/models/x-ai/grok-imagine-reference-to-video-private) | video | – | $0.06 / sec |  |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | $0.138 / sec | $0.1383 / sec | 0% |

**New models (3)**

| Model | Category | Official price | MartLLM price |
|---|---|---|---|
| [Claude Opus 4.6 Fast](https://martllm.com/models/anthropic/claude-opus-4.6-fast) | text | – | $28.35 / $141.75 |
| [Claude Opus 4.7 Fast](https://martllm.com/models/anthropic/claude-opus-4.7-fast) | text | – | $18.90 / $94.50 |
| [GLM 4.7 Flash E2EE](https://martllm.com/models/z-ai/e2ee-glm-4.7-flash) | text | – | $0.1229 / $0.5198 |

<details><summary>MartLLM price moves of 10% or more (167)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Qwen3.5 Flash](https://martllm.com/models/qwen/qwen3.5-flash) | text | $0.1029 / $0.4116 | $0.02084 / $0.08337 | −80% |
| [Qwen3.5 Plus](https://martllm.com/models/qwen/qwen3.5-plus) | text | $0.2675 / $1.61 | $0.05419 / $0.3251 | −80% |
| [Wan 2.6 Text-to-Video](https://martllm.com/models/wan/wan-2-6-text-to-video) | video | $0.1743 / sec | $0.0735 / sec | −58% |
| [HappyHorse 1.0 Text-to-Video](https://martllm.com/models/happyhorse/happyhorse-1-0-text-to-video) | video | $0.2765 / sec | $0.1221 / sec | −56% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | text | $2.83 / $14.18 | $1.31 / $6.56 | −54% |
| [Gemini 3.1 Pro Preview](https://martllm.com/models/google/gemini-3.1-pro-preview) | text | $0.63 / $3.78 | $0.294 / $1.76 | −53% |
| [Kling V3 Pro Text-to-Video](https://martllm.com/models/kling/kling-v3-pro-text-to-video) | video | $0.1932 / sec | $0.09065 / sec | −53% |
| [Kling V3 Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-pro-image-to-video) | video | $0.1925 / sec | $0.09065 / sec | −53% |
| [Whisper 1 (Venice, legacy alias)](https://martllm.com/models/venice/whisper-1) | transcription | $0.005232 / minute | $0.002616 / minute | −50% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | text | $0.07497 / $0.2772 | $0.03748 / $0.1386 | −50% |
| [Veo3.1 Fast (image-to-video)](https://martllm.com/models/google/veo3-1-fast-image-to-video) | video | $0.1559 / sec | $0.07875 / sec | −49% |
| [Flux 2 Max — Edit (Venice)](https://martllm.com/models/black-forest-labs/flux-2-max-edit) | image | $0.1995 / image | $0.1008 / image | −49% |
| [Kling 2.5 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-2-5-turbo-pro-image-to-video) | video | $0.0819 / sec | $0.0441 / sec | −46% |
| [Kling 2.5 Turbo Pro Text-to-Video](https://martllm.com/models/kling/kling-2-5-turbo-pro-text-to-video) | video | $0.0819 / sec | $0.0441 / sec | −46% |
| [Pixverse C1 (image-to-video)](https://martllm.com/models/pixverse/pixverse-c1-image-to-video) | video | $0.04546 / sec | $0.0245 / sec | −46% |
| [Pixverse C1 (reference-to-video)](https://martllm.com/models/pixverse/pixverse-c1-reference-to-video) | video | $0.04546 / sec | $0.0245 / sec | −46% |
| [Pixverse C1 Transition (transition)](https://martllm.com/models/pixverse/pixverse-c1-transition) | video | $0.04546 / sec | $0.0245 / sec | −46% |
| [Gemini Omni Flash (image-to-video)](https://martllm.com/models/google/gemini-omni-flash-image-to-video) | video | $0.1496 / sec | $0.08269 / sec | −45% |
| [Parakeet ASR (Venice)](https://martllm.com/models/venice/parakeet-asr) | transcription | $0.005232 / minute | $0.002943 / minute | −44% |
| [Qwen 3 235B A22B Thinking 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.2646 / $2.06 | $0.1512 / $1.18 | −43% |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | $0.1159 / sec | $0.0686 / sec | −41% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.03087 / $0.126 | $0.01852 / $0.0756 | −40% |
| [Kimi K3](https://martllm.com/models/moonshotai/kimi-k3) | text | $0.2993 / $1.57 | $0.1795 / $0.945 | −40% |
| [Whisper Large V3 (Venice)](https://martllm.com/models/venice/whisper-large-v3) | transcription | $0.004905 / minute | $0.002943 / minute | −40% |
| [ElevenLabs TTS v3 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-v3) | music | $0.1253 / 1K chars | $0.07521 / 1K chars | −40% |
| [Claude Sonnet 4.6](https://martllm.com/models/anthropic/claude-sonnet-4.6) | text | $2.14 / $10.71 | $1.29 / $6.46 | −40% |
| [Kling V3 Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-standard-image-to-video) | video | $0.1103 / sec | $0.0686 / sec | −38% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | text | $0.0168 / $0.1344 | $0.0105 / $0.084 | −37% |
| [Qwen3.8 Flash](https://martllm.com/models/qwen/qwen3.8-flash) | text | $0.04725 / $0.148 | $0.02993 / $0.09377 | −37% |
| [Wan 2.6 (image-to-video)](https://martllm.com/models/wan/wan-2-6-image-to-video) | video | $0.1155 / sec | $0.0735 / sec | −36% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | music | $0.001755 / sec | $0.001128 / sec | −36% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | text | $2.52 / $12.60 | $1.73 / $8.66 | −31% |
| [LiquidAI: LFM2.5-24B-A2B](https://martllm.com/models/liquid/lfm-2.5-24b-a2b) | text | $0.0525 / $0.735 | $0.03623 / $0.5071 | −31% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.07004 / sec | $0.049 / sec | −30% |
| [Seed Audio 1.0](https://martllm.com/models/bytedance/seed-audio-1-0) | music | $0.003134 / sec | $0.002194 / sec | −30% |
| [Ideogram V4.5 (image-to-image)](https://martllm.com/models/ideogram/ideogram-v4-5-edit) | image | $0.273 / image | $0.1911 / image | −30% |
| [LTX 2 v2.3 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.07 / sec | $0.049 / sec | −30% |
| [Vidu Q3 (image-to-video)](https://martllm.com/models/vidu/vidu-q3-image-to-video) | video | $0.0945 / sec | $0.06615 / sec | −30% |
| [Kling O3 4K Text-to-Video](https://martllm.com/models/kling/kling-o3-4k-text-to-video) | video | $0.4865 / sec | $0.3406 / sec | −30% |
| [Kling V3 4K Text-to-Video](https://martllm.com/models/kling/kling-v3-4k-text-to-video) | video | $0.4865 / sec | $0.3406 / sec | −30% |
| [Ovi Image-to-Video](https://martllm.com/models/ovi/ovi-image-to-video) | video | $0.0462 / sec | $0.03234 / sec | −30% |
| [Wan 2.5 Preview (image-to-video)](https://martllm.com/models/wan/wan-2-5-preview-image-to-video) | video | $0.0588 / sec | $0.04116 / sec | −30% |
| [Kling O3.4k (image-to-video)](https://martllm.com/models/kling/kling-o3-4k-image-to-video) | video | $0.4865 / sec | $0.3406 / sec | −30% |
| [Kling O3.4k (reference-to-video)](https://martllm.com/models/kling/kling-o3-4k-reference-to-video) | video | $0.4865 / sec | $0.3406 / sec | −30% |
| [Kling V3 Turbo Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-standard-image-to-video) | video | $0.1295 / sec | $0.09065 / sec | −30% |
| [Ltx 2 V2.3 Full (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.09272 / sec | $0.06492 / sec | −30% |
| [Seedance 2.5 Text-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-text-to-video-basic) | video | $0.04888 / sec | $0.03423 / sec | −30% |
| [Gemini Omni Flash (reference-to-video)](https://martllm.com/models/google/gemini-omni-flash-reference-to-video) | video | $0.1496 / sec | $0.1051 / sec | −30% |
| [Wan 3.0 Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-reference-to-video) | video | $0.06825 / sec | $0.04802 / sec | −30% |
| [Wan 3.0 Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-text-to-video) | video | $0.06825 / sec | $0.04802 / sec | −30% |
| [Happyhorse 1.0 (reference-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.161 / sec | $0.1135 / sec | −29% |
| [Kling V3 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.161 / sec | $0.1135 / sec | −29% |
| [Runway Gen-4.5](https://martllm.com/models/runway/runway-gen4-5) | video | $0.168 / sec | $0.1191 / sec | −29% |
| [Runway Gen-4.5 Text-to-Video (Venice)](https://martllm.com/models/venice/runway-gen4-5-text) | video | $0.168 / sec | $0.1191 / sec | −29% |
| [Longcat (image-to-video)](https://martllm.com/models/meituan/longcat-image-to-video) | video | $0.0525 / sec | $0.03724 / sec | −29% |
| [Veo3.1 Full (image-to-video)](https://martllm.com/models/google/veo3-1-full-image-to-video) | video | $0.462 / sec | $0.3281 / sec | −29% |
| [Veo 3.1 Full Text-to-Video](https://martllm.com/models/google/veo3-1-full-text-to-video) | video | $0.462 / sec | $0.3281 / sec | −29% |
| [Wan 3.0 Prime Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-image-to-video) | video | $0.09282 / sec | $0.06615 / sec | −29% |
| [Wan 3.0 Prime Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-reference-to-video) | video | $0.09282 / sec | $0.06615 / sec | −29% |
| [Wan 3.0 Prime Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-text-to-video) | video | $0.09282 / sec | $0.06615 / sec | −29% |
| [Kling 2.6 Pro (image-to-video)](https://martllm.com/models/kling/kling-2-6-pro-image-to-video) | video | $0.1617 / sec | $0.1155 / sec | −29% |
| [Kling 2.6 Pro Text-to-Video](https://martllm.com/models/kling/kling-2-6-pro-text-to-video) | video | $0.1617 / sec | $0.1155 / sec | −29% |
| [Runway Gen-4 Turbo](https://martllm.com/models/runway/runway-gen4-turbo) | video | $0.07087 / sec | $0.05145 / sec | −27% |
| [Wan 2.5 Preview Text-to-Video](https://martllm.com/models/wan/wan-2-5-preview-text-to-video) | video | $0.08662 / sec | $0.063 / sec | −27% |
| [Wan 2.7 (reference-to-video)](https://martllm.com/models/wan/wan-2-7-reference-to-video) | video | $0.1155 / sec | $0.084 / sec | −27% |
| [Wan 2.7 Text-to-Video](https://martllm.com/models/wan/wan-2-7-text-to-video) | video | $0.1155 / sec | $0.084 / sec | −27% |
| [Kling O3 Standard (reference-to-video)](https://martllm.com/models/kling/kling-o3-standard-reference-to-video) | video | $0.1295 / sec | $0.0945 / sec | −27% |
| [Kling O3 Standard Text-to-Video](https://martllm.com/models/kling/kling-o3-standard-text-to-video) | video | $0.1291 / sec | $0.0945 / sec | −27% |
| [Happyhorse 1.1 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.161 / sec | $0.1181 / sec | −27% |
| [Happyhorse 1.1 (reference-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-1-reference-to-video) | video | $0.161 / sec | $0.1181 / sec | −27% |
| [GPT-5.4 Image 2](https://martllm.com/models/openai/gpt-5.4-image-2) | image | $7.98 / $14.96 | $5.88 / $11.03 | −26% |
| [Grok Imagine Reference To Video Private (reference-to-video)](https://martllm.com/models/x-ai/grok-imagine-reference-to-video-private) | video | $0.063 / sec | $0.04655 / sec | −26% |
| [Grok Imagine Image To Video Private (image-to-video)](https://martllm.com/models/x-ai/grok-imagine-image-to-video-private) | video | $0.063 / sec | $0.04686 / sec | −26% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | text | $0.6773 / $3.39 | $0.504 / $2.52 | −26% |
| [Seedance 2.0 Mini (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-reference-to-video) | video | $0.0462 / sec | $0.03465 / sec | −25% |
| [Kling O3 Pro Text-to-Video](https://martllm.com/models/kling/kling-o3-pro-text-to-video) | video | $0.161 / sec | $0.1207 / sec | −25% |
| [MiniMax H3 Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-image-to-video) | video | $0.105 / sec | $0.07875 / sec | −25% |
| [NVIDIA Nemotron 3 Ultra 550B](https://martllm.com/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.2625 / $1.31 | $0.1969 / $0.9844 | −25% |
| [Kling 4.0 Reference-to-Video](https://martllm.com/models/kling/venice-kling-v4-reference-to-video) | video | $0.2061 / sec | $0.1546 / sec | −25% |
| [Gemini Omni Flash 1.1 Reference-to-Video](https://martllm.com/models/google/venice-gemini-omni-flash-1-1-reference-to-video) | video | $0.04095 / sec | $0.03071 / sec | −25% |
| [Kling O3 Pro (reference-to-video)](https://martllm.com/models/kling/kling-o3-pro-reference-to-video) | video | $0.161 / sec | $0.1207 / sec | −25% |
| [Claude Sonnet 5](https://martllm.com/models/anthropic/claude-sonnet-5) | text | $1.03 / $5.14 | $0.777 / $3.88 | −24% |
| [MiniMax M3.1 Flash](https://martllm.com/models/minimax/minimax-m3-1-flash) | text | $0.04568 / $0.1827 | $0.03465 / $0.1386 | −24% |
| [Claude Opus 4.5](https://martllm.com/models/anthropic/claude-opus-4.5) | text | $2.68 / $13.39 | $2.05 / $10.24 | −24% |
| [Nano Banana 2 Lite (image-to-image)](https://martllm.com/models/google/nano-banana-2-lite-edit) | image | $0.05418 / image | $0.04158 / image | −23% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://martllm.com/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.0945 / sec | $0.0735 / sec | −22% |
| [Wan 3.0 Pro Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-pro-text-to-video) | video | $0.2484 / sec | $0.1938 / sec | −22% |
| [Kling 4.0 Flash Image-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-image-to-video) | video | $0.1234 / sec | $0.09747 / sec | −21% |
| [ElevenLabs Music (Venice)](https://martllm.com/models/venice/elevenlabs-music) | music | $0.7521 / track | $0.5942 / track | −21% |
| [LTX 2 v2.3 Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.09275 / sec | $0.0742 / sec | −20% |
| [MiMo-V2.5-Pro](https://martllm.com/models/xiaomi/mimo-v2.5-pro) | text | $0.3197 / $1.20 | $0.2558 / $0.9592 | −20% |
| [Luma Uni 1 Max (image-to-image)](https://martllm.com/models/luma/luma-uni-1-max-edit) | image | $0.1365 / image | $0.1092 / image | −20% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | text | $0.03675 / $0.1785 | $0.0294 / $0.1428 | −20% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | text | $0.007875 / $0.02467 | $0.0063 / $0.01974 | −20% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | text | $6.38 / $31.92 | $5.12 / $25.62 | −20% |
| [Claude Sonnet 5.5](https://martllm.com/models/anthropic/claude-sonnet-5.5) | text | $1.18 / $5.88 | $0.966 / $4.83 | −18% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | text | $0.1108 / $0.2684 | $0.0923 / $0.2236 | −17% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | text | $0.08466 / $0.84 | $0.07111 / $0.7056 | −16% |
| [Flux 2 Pro (Venice)](https://martllm.com/models/venice/flux-2-pro) | image | $0.02625 / image | $0.02205 / image | −16% |
| [Google: Gemini 4 Carbon](https://martllm.com/models/google/gemini-4-carbon) | text | $0.798 / $3.99 | $0.672 / $3.36 | −16% |
| [LongCat Text-to-Video](https://martllm.com/models/meituan/longcat-text-to-video) | video | $0.0525 / sec | $0.04462 / sec | −15% |
| [Wan 2.7 (image-to-video)](https://martllm.com/models/wan/wan-2-7-image-to-video) | video | $0.09817 / sec | $0.084 / sec | −14% |
| [Qwen: Qwen3.8 Max (0902)](https://martllm.com/models/qwen/qwen3.8-max-0902) | text | $0.147 / $0.441 | $0.126 / $0.378 | −14% |
| [GPT 5 Mini](https://martllm.com/models/openai/gpt-5-mini) | text | $0.063 / $0.504 | $0.05513 / $0.441 | −12% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://martllm.com/models/venice/elevenlabs-tts-turbo-v2-5) | speech | $0.0545 / 1K chars | $0.04769 / 1K chars | −12% |
| [Claude Sonnet 4.5](https://martllm.com/models/anthropic/claude-sonnet-4.5) | text | $2.80 / $14.02 | $2.46 / $12.29 | −12% |
| [Google: Gemini 4 Neon](https://martllm.com/models/google/gemini-4-neon) | text | $2.30 / $11.50 | $2.02 / $10.08 | −12% |
| [Qwen 3.7 Plus](https://martllm.com/models/qwen/qwen3.7-plus) | text | $0.4462 / $1.78 | $0.3937 / $1.57 | −12% |
| [inclusionAI: Ling 3.1 Flash](https://martllm.com/models/inclusionai/ling-3.1-flash) | text | $0.05607 / $0.1682 | $0.04977 / $0.1493 | −11% |
| [ElevenLabs Music v2.5](https://martllm.com/models/elevenlabs/elevenlabs-music-v2-5) | music | $0.6769 / track | $0.6017 / track | −11% |
| [xAI Speech to Text v1 (Venice)](https://martllm.com/models/venice/xai-stt-v1) | transcription | $0.001667 / minute | $0.001482 / minute | −11% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | text | $5.57 / $27.82 | $6.20 / $30.98 | +11% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | text | $1.32 / $4.35 | $1.49 / $4.89 | in +13% / out +12% |
| [Qwen3 VL 235B A22B](https://martllm.com/models/qwen/qwen3-vl-235b-a22b-instruct) | text | $0.04851 / $0.4389 | $0.05475 / $0.4954 | +13% |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | text | $0.0735 / $0.1103 | $0.084 / $0.126 | +14% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.02693 / $0.3119 | $0.03092 / $0.358 | +15% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | text | $0.08379 / $0.5147 | $0.09849 / $0.605 | +18% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | text | $0.02425 / $0.02425 | $0.02866 / $0.02866 | +18% |
| [MiMo-V2.6-Pro](https://martllm.com/models/xiaomi/mimo-v2.6-pro) | text | $0.2512 / $0.5024 | $0.2969 / $0.5938 | +18% |
| [GLM 4.5](https://martllm.com/models/z-ai/glm-4.5) | text | $0.378 / $1.39 | $0.4473 / $1.64 | +18% |
| [Meta: Muse Spark Open](https://martllm.com/models/meta-llama/muse-spark-open) | text | $0.7875 / $2.68 | $0.9319 / $3.17 | +18% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | text | $0.4402 / $1.33 | $0.5227 / $1.58 | +19% |
| [Qwen3.8 2.4T A95B](https://martllm.com/models/qwen/qwen3.8-2.4t-a95b) | text | $0.504 / $1.51 | $0.609 / $1.83 | +21% |
| [MiniMax M2](https://martllm.com/models/minimax/minimax-m2) | text | $0.0567 / $0.2268 | $0.0693 / $0.2772 | +22% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | text | $0.03638 / $0.03638 | $0.04465 / $0.04465 | +23% |
| [Seedance 2.5 Reference-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-reference-to-video-basic) | video | $0.04888 / sec | $0.0611 / sec | +25% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | text | $0.168 / $0.504 | $0.21 / $0.63 | +25% |
| [Qwen3 0.6B TTS](https://martllm.com/models/qwen/tts-qwen3-0-6b) | speech | $0.0763 / 1K chars | $0.09538 / 1K chars | +25% |
| [Kling Image 4.0](https://martllm.com/models/kling/venice-kling-v4-text-to-image) | image | $0.0672 / image | $0.084 / image | +25% |
| [Muse Image](https://martllm.com/models/meta-llama/venice-muse-image) | image | $0.0168 / image | $0.021 / image | +25% |
| [MiniMax H3 Image](https://martllm.com/models/minimax/venice-minimax-h3-image) | image | $0.0336 / image | $0.042 / image | +25% |
| [GPT OSS 20B](https://martllm.com/models/openai/e2ee-gpt-oss-20b-p) | text | $0.021 / $0.0798 | $0.02625 / $0.09975 | +25% |
| [Flux 3 (image-to-image)](https://martllm.com/models/black-forest-labs/flux-3-image-edit) | image | $0.0882 / image | $0.1134 / image | +29% |
| [DeepSeek V4 Flash 0731](https://martllm.com/models/deepseek/deepseek-v4-flash-0731) | text | $0.03822 / $0.07644 | $0.04914 / $0.09828 | +29% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | text | $0.756 / $3.78 | $0.9764 / $4.88 | +29% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | text | $0.00945 / $0.0189 | $0.01229 / $0.02457 | +30% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | text | $0.07875 / $0.1575 | $0.104 / $0.208 | +32% |
| [Aion 3.0 Mini](https://martllm.com/models/aion-labs/aion-3-0-mini) | text | $0.3896 / $0.7791 | $0.5219 / $1.04 | +34% |
| [MiniMax M3](https://martllm.com/models/minimax/minimax-m3) | text | $0.1103 / $0.441 | $0.1512 / $0.6048 | +37% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | text | $0.04253 / $0.0756 | $0.05953 / $0.1058 | +40% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | text | $0.1339 / $0.8033 | $0.189 / $1.13 | +41% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | text | $0.0504 / $0.315 | $0.0714 / $0.4462 | +42% |
| [Qwen 4 Max](https://martllm.com/models/qwen/qwen4-max) | text | $0.3441 / $1.03 | $0.4938 / $1.48 | +43% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | text | $0.0882 / $0.2646 | $0.1323 / $0.3969 | +50% |
| [Palmyra Vision 7B](https://martllm.com/models/writer/palmyra-vision-7b) | text | $0.0315 / $0.126 | $0.04725 / $0.189 | +50% |
| [NVIDIA Nemotron 3 Super 120B](https://martllm.com/models/nvidia/nemotron-3-super-120b) | text | $0.02441 / $0.1339 | $0.03825 / $0.2097 | +57% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | text | $0.01638 / $0.04914 | $0.02646 / $0.07938 | +62% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.03276 / $0.126 | $0.05323 / $0.2047 | +62% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | text | $0.01386 / $0.0462 | $0.02268 / $0.0756 | +64% |
| [Seedance 2.5](https://martllm.com/models/bytedance/seedance-2-5) | video | $0.04888 / sec | $0.08165 / sec | +67% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | text | $0.009599 / $0.0588 | $0.01714 / $0.105 | +79% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | text | $0.3307 / $1.04 | $0.5954 / $1.87 | +80% |
| [MiniMax M2.5](https://martllm.com/models/minimax/minimax-m2.5) | text | $0.03402 / $0.1197 | $0.06237 / $0.2195 | +83% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | text | $0.05476 / $0.231 | $0.1095 / $0.462 | +100% |
| [GPT Image 2.5 Sunburst (image-to-image)](https://martllm.com/models/openai/gpt-image-2-5-sunburst-edit) | image | $0.0315 / image | $0.0672 / image | +113% |
| [Qwen3 Coder Next](https://martllm.com/models/qwen/qwen3-coder-next) | text | $0.01764 / $0.1176 | $0.0378 / $0.252 | +114% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | text | $0.05775 / $0.1732 | $0.1365 / $0.4095 | +136% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | text | $0.04436 / $0.1706 | $0.1058 / $0.4069 | +138% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | text | $0.0042 / $0.0483 | $0.0105 / $0.1207 | +150% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | text | $0.0441 / $0.1837 | $0.1569 / $0.6536 | +256% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | text | $0.00315 / $0.00945 | $0.0147 / $0.0441 | +367% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | text | $0.07056 / $0.2218 | $0.3352 / $1.05 | +375% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | text | $0.00252 / $0.00504 | $0.01302 / $0.02604 | +417% |
| [NVIDIA Nemotron Nano 9B v2](https://martllm.com/models/nvidia/nemotron-nano-9b-v2) | text | $0.00189 / $0.007245 | $0.0126 / $0.0483 | +567% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | text | $0.0126 / $0.063 | $0.1035 / $0.5177 | +722% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | text | $0.00147 / $0.0063 | $0.01544 / $0.06615 | +950% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://martllm.com/models/nvidia/nemotron-nano-12b-v2) | text | $0.0042 / $0.0126 | $0.063 / $0.189 | +1400% |

</details>


## 2026-11-22 (vs 2026-11-18)

**Official list price changes (126)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MiniMax H3](https://martllm.com/models/minimax/minimax-h3) | video | $0.13 / sec | $0.04 / sec | −69% |
| [MiniMax H3 Reference](https://martllm.com/models/minimax/minimax-h3-reference-to-video) | video | $0.13 / sec | $0.04 / sec | −69% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.30 / $1.20 | $0.147 / $0.60 | in −51% / out −50% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.44 / $1.32 | $0.2695 / $0.8085 | −39% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.30 / $1.20 | $0.195 / $0.75 | in −35% / out −38% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $1.32 / $3.96 | $1.28 / $2.56 | in −3% / out −35% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.15 / $0.60 | $0.11 / $0.44 | −27% |
| [Particle AI: Particle-1](https://martllm.com/models/particle-ai/particle-1) | text | $0.06 / $0.50 | $0.0525 / $0.375 | in −12% / out −25% |
| [Meta: Muse Glimmer 30B](https://martllm.com/models/meta-llama/muse-glimmer-30b) | text | $0.35 / $1.50 | $0.30 / $1.20 | in −14% / out −20% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | text | $0.075 / $0.30 | $0.0725 / $0.25 | in −3% / out −17% |
| [NVIDIA Nemotron 3.5 Lightning 30B](https://martllm.com/models/nvidia/nemotron-3-5-lightning-30b-a3b) | text | $0.07 / $0.20 | $0.06 / $0.20 | in −14% / out 0% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | text | $0.05 / $0.10 | $0.045 / $0.09 | −10% |
| [GLM 5.1 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5.1) | text | $1.40 / $4.40 | $1.26 / $3.96 | −10% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | text | $1.40 / $4.40 | $1.26 / $3.96 | −10% |
| [Gemini 3.8 Flash](https://martllm.com/models/google/gemini-3.8-flash) | text | $0.825 / $4.12 | $0.75 / $3.75 | −9% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.10 / $1.10 | $0.095 / $1.10 | in −5% / out 0% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | text | $1.00 / $3.20 | $0.975 / $3.04 | in −3% / out −5% |
| [Hailuo 02 Standard Image to Video](https://martllm.com/models/minimax/hailuo-02-standard-image-to-video) | video | $0.017 / sec | $0.01619 / sec | −5% |
| [Veo 3.1 Lite Text to Video](https://martllm.com/models/google/veo-3.1-lite) | video | $0.03 / sec | $0.02857 / sec | −5% |
| [Vidu Q3 Turbo Image to Video](https://martllm.com/models/vidu/viduq3-turbo-image-to-video) | video | $0.035 / sec | $0.03333 / sec | −5% |
| [Vidu Q3 Turbo Text to Video](https://martllm.com/models/vidu/viduq3-turbo-text-to-video) | video | $0.035 / sec | $0.03333 / sec | −5% |
| [LTX 2.3 Text to Video](https://martllm.com/models/lightricks/ltx-2-3-text-to-video) | video | $0.08 / sec | $0.07619 / sec | −5% |
| [Hailuo 02 Standard Text to Video](https://martllm.com/models/minimax/hailuo-02-standard-text-to-video) | video | $0.045 / sec | $0.04286 / sec | −5% |
| [Veo 3.1 Text to Video](https://martllm.com/models/google/veo-3.1) | video | $0.20 / sec | $0.1905 / sec | −5% |
| [Veo 3.1 Fast Text to Video](https://martllm.com/models/google/veo-3.1-fast) | video | $0.10 / sec | $0.09524 / sec | −5% |
| [Veo 3.1 Fast Image to Video](https://martllm.com/models/google/veo-3.1-fast-image-to-video) | video | $0.10 / sec | $0.09524 / sec | −5% |
| [Veo 3.1 Image to Video](https://martllm.com/models/google/veo-3.1-image-to-video) | video | $0.20 / sec | $0.1905 / sec | −5% |
| [Wan 2.7 Image to Video](https://martllm.com/models/wan/wan2-7-image-to-video) | video | $0.10 / sec | $0.09524 / sec | −5% |
| [Wan 2.7 Text to Video](https://martllm.com/models/wan/wan2-7-text-to-video) | video | $0.10 / sec | $0.09524 / sec | −5% |
| [Kling O3 Standard Image to Video](https://martllm.com/models/kling/kling-video-o3-standard-image-to-video) | video | $0.084 / sec | $0.08 / sec | −5% |
| [Kling O3 Standard Text to Video](https://martllm.com/models/kling/kling-video-o3-standard-text-to-video) | video | $0.084 / sec | $0.08 / sec | −5% |
| [Kling 3 Standard Image to Video](https://martllm.com/models/kling/kling-video-v3-standard-image-to-video) | video | $0.084 / sec | $0.08 / sec | −5% |
| [Kling 3 Standard Text to Video](https://martllm.com/models/kling/kling-video-v3-standard-text-to-video) | video | $0.084 / sec | $0.08 / sec | −5% |
| [LTX 2.3 Fast Image to Video](https://martllm.com/models/lightricks/ltx-2-3-fast-image-to-video) | video | $0.06 / sec | $0.05714 / sec | −5% |
| [LTX 2.3 Fast Text to Video](https://martllm.com/models/lightricks/ltx-2-3-fast-text-to-video) | video | $0.06 / sec | $0.05714 / sec | −5% |
| [Kling 3 Pro Image to Video](https://martllm.com/models/kling/kling-video-v3-pro-image-to-video) | video | $0.112 / sec | $0.1067 / sec | −5% |
| [Kling 3 Pro Text to Video](https://martllm.com/models/kling/kling-video-v3-pro-text-to-video) | video | $0.112 / sec | $0.1067 / sec | −5% |
| [Kling 2.6 Pro Image to Video](https://martllm.com/models/kling/kling-video-v2-6-pro-image-to-video) | video | $0.07 / sec | $0.06667 / sec | −5% |
| [Kling 2.6 Pro Text to Video](https://martllm.com/models/kling/kling-video-v2-6-pro-text-to-video) | video | $0.07 / sec | $0.06667 / sec | −5% |
| [Vidu Q3 Image to Video](https://martllm.com/models/vidu/viduq3-image-to-video) | video | $0.07 / sec | $0.06667 / sec | −5% |
| [Vidu Q3 Text to Video](https://martllm.com/models/vidu/viduq3-text-to-video) | video | $0.07 / sec | $0.06667 / sec | −5% |
| [Qwen 3 235B A22B Instruct 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-2507) | text | $0.14 / $0.75 | $0.135 / $0.75 | in −4% / out 0% |
| [Llama 3.2 3B](https://martllm.com/models/meta-llama/llama-3.2-3b-instruct) | text | $0.0509 / $0.335 | $0.05 / $0.33 | in −2% / out −1% |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | $0.14 / sec | $0.138 / sec | −1% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | text | $1.32 / $3.96 | $1.31 / $3.96 | in −1% / out 0% |
| [PixVerse C1 Text-to-Video (Venice)](https://martllm.com/models/venice/pixverse-c1-t2v) | video | $0.072 / sec | $0.0715 / sec | −1% |
| [Seedance 2.0 Fast Text-to-Video (Venice)](https://martllm.com/models/venice/seedance-2-fast-t2v) | video | $0.1513 / sec | $0.1513 / sec | 0% |
| [Flux 3 (image-to-image)](https://martllm.com/models/black-forest-labs/flux-3-image-edit) | image | – | $0.12 / image |  |
| [Flux 3 (Venice)](https://martllm.com/models/black-forest-labs/venice-flux-3-image) | image | – | $0.12 / image |  |
| [Seedance 2.5](https://martllm.com/models/bytedance/seedance-2-5) | video | – | $0.14 / sec |  |
| [Seedance 2.5 Image-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-image-to-video-basic) | video | – | $0.1287 / sec |  |
| [Seedance 2.5 Reference-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-reference-to-video-basic) | video | – | $0.1287 / sec |  |
| [Seedance 2.5 Text-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-text-to-video-basic) | video | – | $0.1287 / sec |  |
| [Seedream V5.5 (Venice)](https://martllm.com/models/bytedance/venice-seedream-v5-5) | image | – | $0.0255 / image |  |
| [Seedream V5.5 (image-to-image)](https://martllm.com/models/bytedance/venice-seedream-v5-5-edit) | image | – | $0.0255 / image |  |
| [ElevenLabs Music v2.5](https://martllm.com/models/elevenlabs/elevenlabs-music-v2-5) | music | – | $0.69 / track |  |
| [ElevenLabs TTS v4](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4) | music | – | $0.092 / 1K chars |  |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | music | – | $0.046 / 1K chars |  |
| [Lyria 3 Pro](https://martllm.com/models/google-deepmind/lyria-3-pro) | music | – | $0.10 / track |  |
| [Gemini Omni Flash](https://martllm.com/models/google/gemini-omni-flash) | video | – | $0.07875 / sec |  |
| [Gemini Omni Flash 1.1](https://martllm.com/models/google/gemini-omni-flash-1-1) | video | – | $0.07875 / sec |  |
| [Ideogram V4 (Venice)](https://martllm.com/models/ideogram/venice-ideogram-v4) | image | – | $0.06 / image |  |
| [Ideogram V4.5 (Venice)](https://martllm.com/models/ideogram/venice-ideogram-v4-5) | image | – | $0.26 / image |  |
| [Krea 2 Turbo (Venice)](https://martllm.com/models/krea/venice-krea-2-turbo) | image | – | $0.04 / image |  |
| [Krea v2 Large (Venice)](https://martllm.com/models/krea/venice-krea-v2-large) | image | – | $0.07 / image |  |
| [Krea v2 Medium (Venice)](https://martllm.com/models/krea/venice-krea-v2-medium) | image | – | $0.04 / image |  |
| [Luma Uni-1 (Venice)](https://martllm.com/models/luma/venice-luma-uni-1) | image | – | $0.05 / image |  |
| [Luma Uni-1 Max (Venice)](https://martllm.com/models/luma/venice-luma-uni-1-max) | image | – | $0.12 / image |  |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | text | – / – | $0.293 / $0.71 |  |
| [Muse Image (image-to-image)](https://martllm.com/models/meta-llama/muse-image-edit) | image | – | $0.02 / image |  |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | text | – / – | $2.00 / $10.00 |  |
| [GPT Image 2.6 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare) | image | – | $0.09 / image |  |
| [GPT Image 2.6 Flare (image-to-image)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare-edit) | image | – | $0.10 / image |  |
| [GPT Image 2.6 Sunburst (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-sunburst) | image | – | $0.09 / image |  |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | text | – / – | $0.20 / $2.30 |  |
| [Qwen 3.5 9B](https://martllm.com/models/qwen/qwen3.5-9b) | text | – / – | $0.17 / $0.25 |  |
| [Qwen Image 2.1 Pro (Venice)](https://martllm.com/models/qwen/venice-qwen-image-2-1-pro) | image | – | $0.05 / image |  |
| [Qwen Image 2.1 Turbo (Venice)](https://martllm.com/models/qwen/venice-qwen-image-2-1-turbo) | image | – | $0.02 / image |  |
| [Wan 3.0 Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-image-to-video) | video | – | $0.26 / sec |  |
| [Wan 3.0 Prime Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-image-to-video) | video | – | $0.364 / sec |  |
| [Wan 3.0 Prime Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-reference-to-video) | video | – | $0.364 / sec |  |
| [Wan 3.0 Prime Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-text-to-video) | video | – | $0.364 / sec |  |
| [Wan 3.0 Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-reference-to-video) | video | – | $0.26 / sec |  |
| [Wan 3.0 Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-text-to-video) | video | – | $0.26 / sec |  |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | music | – | $0.002875 / sec |  |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-sound-effects-v1-0) | music | – | $0.00207 / sec |  |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | text | $0.32 / $3.20 | $0.3225 / $3.20 | in +1% / out 0% |
| [Grok Imagine Text-to-Video](https://martllm.com/models/x-ai/grok-imagine-text-to-video) | video | $0.08917 / sec | $0.09 / sec | +1% |
| [Tencent HY3](https://martllm.com/models/tencent/hy3) | text | $0.132 / $0.528 | $0.136 / $0.554 | in +3% / out +5% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | text | $0.20 / $0.20 | $0.21 / $0.21 | +5% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | text | $0.10 / $0.10 | $0.105 / $0.105 | +5% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | text | $0.15 / $0.15 | $0.1575 / $0.1575 | +5% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | text | $0.50 / $1.50 | $0.525 / $1.57 | +5% |
| [Mistral: Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4-0) | text | $0.70 / $2.10 | $0.735 / $2.21 | +5% |
| [NVIDIA Nemotron 3 Super 120B](https://martllm.com/models/nvidia/nemotron-3-super-120b) | text | $0.075 / $0.40 | $0.0775 / $0.425 | in +3% / out +6% |
| [Kimi K2.7 Code](https://martllm.com/models/moonshotai/kimi-k2.7-code) | text | $0.70 / $3.50 | $0.75 / $3.50 | in +7% / out 0% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | text | $0.65 / $3.41 | $0.70 / $3.40 | in +8% / out 0% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | text | $0.13 / $0.85 | $0.14 / $0.86 | in +8% / out +1% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | text | $0.0605 / $0.40 | $0.0653 / $0.40 | in +8% / out 0% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-v3.1) | text | $0.25 / $0.95 | $0.27 / $1.00 | in +8% / out +5% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-4) | text | $0.15 / $0.60 | $0.165 / $0.66 | +10% |
| [Grok 4.5](https://martllm.com/models/x-ai/grok-4.5) | text | $2.00 / $6.00 | $2.27 / $6.80 | in +14% / out +13% |
| [Grok 4.6](https://martllm.com/models/x-ai/grok-4.6) | text | $2.00 / $6.00 | $2.27 / $6.80 | in +14% / out +13% |
| [Grok 4.20 Beta](https://martllm.com/models/x-ai/grok-4.20-beta) | text | $1.25 / $2.50 | $1.42 / $2.83 | in +14% / out +13% |
| [Grok 4.20 Multi-Agent Beta](https://martllm.com/models/x-ai/grok-4.20-multi-agent-beta) | text | $1.25 / $2.50 | $1.42 / $2.83 | in +14% / out +13% |
| [Grok 4.3](https://martllm.com/models/x-ai/grok-4.3) | text | $1.25 / $2.50 | $1.42 / $2.83 | in +14% / out +13% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | text | $0.50 / $2.50 | $0.57 / $2.85 | +14% |
| [Qwen 3.5 397B](https://martllm.com/models/qwen/qwen3.5-397b-a17b) | text | $0.45 / $3.00 | $0.55 / $3.60 | in +22% / out +20% |
| [Gemma 3 12B IT](https://martllm.com/models/google/gemma-3-12b-it) | text | $0.05 / $0.15 | $0.0625 / $0.1875 | +25% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.075 / $0.20 | $0.09 / $0.25 | in +20% / out +25% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | text | $0.30 / $1.00 | $0.325 / $1.25 | in +8% / out +25% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | text | $0.40 / $1.75 | $0.5002 / $2.06 | in +25% / out +18% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | text | $0.26 / $0.38 | $0.27 / $0.48 | in +4% / out +26% |
| [Gemma 4 26B A4B IT](https://martllm.com/models/google/gemma-4-26b-a4b-it) | text | $0.0765 / $0.255 | $0.10 / $0.30 | in +31% / out +18% |
| [inclusionAI: Ling 3.1 Flash](https://martllm.com/models/inclusionai/ling-3.1-flash) | text | $0.045 / $0.135 | $0.06 / $0.18 | +33% |
| [Reflection: Beam 1.0 501B A23B](https://martllm.com/models/reflection/beam-1.0-501b-a23b) | text | $0.30 / $1.00 | $0.40 / $1.20 | in +33% / out +20% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | text | $0.08 / $0.28 | $0.12 / $0.40 | in +50% / out +43% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | text | $0.09 / $0.18 | $0.12 / $0.27 | in +33% / out +50% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | text | $0.018 / $0.09 | $0.03 / $0.15 | +67% |
| [MiniMax M2.7](https://martllm.com/models/minimax/minimax-m2.7) | text | $0.21 / $0.84 | $0.375 / $1.32 | in +79% / out +57% |
| [MiniMax M3.1 Flash](https://martllm.com/models/minimax/minimax-m3-1-flash) | text | $0.075 / $0.30 | $0.15 / $0.60 | +100% |
| [Tencent: Hy4](https://martllm.com/models/tencent/hy4) | text | $0.417 / $1.25 | $0.834 / $2.50 | +100% |
| [MiMo-V2.5-Pro](https://martllm.com/models/xiaomi/mimo-v2.5-pro) | text | $0.435 / $0.87 | $0.48 / $1.80 | in +10% / out +107% |
| [DeepSeek V4 Flash 0731](https://martllm.com/models/deepseek/deepseek-v4-flash-0731) | text | $0.06 / $0.18 | $0.13 / $0.26 | in +117% / out +44% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.0399 / $0.0784 | $0.13 / $0.50 | in +226% / out +538% |
| [Nano Banana (Gemini 2.5 Flash Image)](https://martllm.com/models/google/gemini-2.5-flash-image) | image | $0.30 / $2.50 | $0.30 / $30.00 | in 0% / out +1100% |

**New models (34)**

| Model | Category | Official price | MartLLM price |
|---|---|---|---|
| [Seedance 2.5 Flash Image-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-flash-image-to-video-basic) | video | $0.189 / sec | $0.08828 / sec |
| [Seedance 2.5 Flash Reference-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-flash-reference-to-video-basic) | video | $0.189 / sec | $0.08828 / sec |
| [Seedance 2.5 Flash Text-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-flash-text-to-video-basic) | video | $0.189 / sec | $0.08828 / sec |
| [Google: Gemini 4 Neon](https://martllm.com/models/google/gemini-4-neon) | text | $3.00 / $15.00 | $2.30 / $11.50 |
| [Gemini Omni Flash 1.1 Image-to-Video](https://martllm.com/models/google/venice-gemini-omni-flash-1-1-image-to-video) | video | $0.1167 / sec | $0.04095 / sec |
| [Gemini Omni Flash 1.1 Reference-to-Video](https://martllm.com/models/google/venice-gemini-omni-flash-1-1-reference-to-video) | video | $0.1167 / sec | $0.04095 / sec |
| [Gemini Omni Flash 1.1 Text-to-Video](https://martllm.com/models/google/venice-gemini-omni-flash-1-1-text-to-video) | video | $0.1167 / sec | $0.04095 / sec |
| [Kling 4.0 Flash Image-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-image-to-video) | video | – | $0.1234 / sec |
| [Kling 4.0 Flash Reference-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-reference-to-video) | video | – | $0.1234 / sec |
| [Kling 4.0 Flash Text-to-Video](https://martllm.com/models/kling/venice-kling-v4-flash-text-to-video) | video | – | $0.1234 / sec |
| [Kling Image 4.0 (image-to-image)](https://martllm.com/models/kling/venice-kling-v4-image-edit) | image | $0.08 / image | $0.07896 / image |
| [Kling 4.0 Image-to-Video](https://martllm.com/models/kling/venice-kling-v4-image-to-video) | video | $0.2938 / sec | $0.2061 / sec |
| [Kling 4.0 Reference-to-Video](https://martllm.com/models/kling/venice-kling-v4-reference-to-video) | video | $0.2937 / sec | $0.2061 / sec |
| [Kling Image 4.0](https://martllm.com/models/kling/venice-kling-v4-text-to-image) | image | $0.08 / image | $0.0672 / image |
| [Kling 4.0 Text-to-Video](https://martllm.com/models/kling/venice-kling-v4-text-to-video) | video | $0.2938 / sec | $0.1649 / sec |
| [Muse Image](https://martllm.com/models/meta-llama/venice-muse-image) | image | $0.02 / image | $0.0168 / image |
| [MiniMax H3 Chili Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-chili-image-to-video) | video | – | $0.1365 / sec |
| [MiniMax H3 Chili Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-chili-text-to-video) | video | – | $0.0315 / sec |
| [MiniMax H3 Enhanced Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-enhanced-text-to-video) | video | $0.1626 / sec | $0.105 / sec |
| [MiniMax H3 Hyper Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-image-to-video) | video | $0.035 / sec | $0.02756 / sec |
| [MiniMax H3 Hyper Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-hyper-text-to-video) | video | – | $0.02625 / sec |
| [MiniMax H3 Image](https://martllm.com/models/minimax/venice-minimax-h3-image) | image | $0.04 / image | $0.0336 / image |
| [MiniMax H3 Image (image-to-image)](https://martllm.com/models/minimax/venice-minimax-h3-image-edit) | image | $0.06 / image | $0.05922 / image |
| [MiniMax H3 Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-image-to-video) | video | $0.1626 / sec | $0.105 / sec |
| [MiniMax H3 Max Image-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-max-image-to-video) | video | $0.072 / sec | $0.04725 / sec |
| [MiniMax H3 Max Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-max-text-to-video) | video | $0.072 / sec | $0.04725 / sec |
| [MiniMax H3 Text-to-Video](https://martllm.com/models/minimax/venice-minimax-h3-text-to-video) | video | $0.1626 / sec | $0.084 / sec |
| [Mistral: Pixtral Large 2502](https://martllm.com/models/mistralai/pixtral-large-2502) | text | $2.00 / $6.00 | $1.49 / $4.47 |
| [Voxtral Small 24B 2507](https://martllm.com/models/mistralai/voxtral-small-24b-2507) | text | $0.105 / $0.315 | $0.07387 / $0.2216 |
| [GPT-6.2 Astra](https://martllm.com/models/openai/gpt-6.2-astra) | text | $8.00 / $40.00 | $4.96 / $24.78 |
| [GPT-6.2 Astra Pro](https://martllm.com/models/openai/gpt-6.2-astra-pro) | text | $8.00 / $40.00 | $6.97 / $34.86 |
| [GPT-6.2 Sol](https://martllm.com/models/openai/gpt-6.2-sol) | text | $2.00 / $10.00 | $1.13 / $5.67 |
| [GPT-6.2 Sol Pro](https://martllm.com/models/openai/gpt-6.2-sol-pro) | text | $2.00 / $10.00 | $2.02 / $10.08 |
| [Grok Imagine 1.5 Lite Text-to-Video](https://martllm.com/models/x-ai/venice-grok-imagine-1-5-lite-text-to-video) | video | $0.036 / sec | $0.0252 / sec |

**No longer listed (14)**: `anthropic/claude-haiku-5.5:batch`, `anthropic/claude-opus-4.6-fast`, `anthropic/claude-opus-4.7-fast`, `anthropic/claude-opus-4.8-fast`, `bytedance/seed-2.0-code`, `google/e2ee-gemma-4-31b`, `google/gemini-2.5-flash`, `google/gemini-2.5-pro`, `google/gemini-3.1-pro`, `minimax/minimax-m2.7-highspeed`, `openai/gpt-6.1-terra-pro:batch`, `openai/gpt-6.1-terra:batch`, `qwen/e2ee-qwen3-5-122b-a10b`, `z-ai/e2ee-glm-4.7-flash`

<details><summary>MartLLM price moves of 10% or more (347)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MiniMax M2.1](https://martllm.com/models/minimax/minimax-m2.1) | text | $0.315 / $1.26 | $0.003045 / $0.009975 | −99% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://martllm.com/models/nvidia/nemotron-nano-12b-v2) | text | $0.054 / $0.162 | $0.0042 / $0.0126 | −92% |
| [GPT Image 2.6 Flare (image-to-image)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare-edit) | image | $0.10 / image | $0.008075 / image | −92% |
| [GPT Image 2.6 Flare (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-flare) | image | $0.09 / image | $0.008075 / image | −91% |
| [Z.ai: GLM 5.3 Prime](https://martllm.com/models/z-ai/glm-5.3-prime) | text | $0.4704 / $1.48 | $0.07056 / $0.2218 | −85% |
| [Veo 3.1 Fast Text-to-Video](https://martllm.com/models/google/veo3-1-fast-text-to-video) | video | $0.099 / sec | $0.0175 / sec | −82% |
| [Qwen: Qwen3.8 Max (0902)](https://martllm.com/models/qwen/qwen3.8-max-0902) | text | $0.74 / $2.22 | $0.147 / $0.441 | −80% |
| [Wan 3.0 Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-image-to-video) | video | $0.26 / sec | $0.05323 / sec | −80% |
| [Gemini Omni Flash](https://martllm.com/models/google/gemini-omni-flash) | video | $0.07875 / sec | $0.01769 / sec | −78% |
| [Gemini Omni Flash 1.1](https://martllm.com/models/google/gemini-omni-flash-1-1) | video | $0.07875 / sec | $0.01769 / sec | −78% |
| [Gemma 4 E2B](https://martllm.com/models/google/gemma-4-e2b) | text | $0.0112 / $0.0224 | $0.00252 / $0.00504 | −78% |
| [Wan 3.0 Prime Image-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-image-to-video) | video | $0.364 / sec | $0.09282 / sec | −74% |
| [Wan 3.0 Prime Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-reference-to-video) | video | $0.364 / sec | $0.09282 / sec | −74% |
| [Wan 3.0 Prime Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-prime-text-to-video) | video | $0.364 / sec | $0.09282 / sec | −74% |
| [Devstral 2 123B](https://martllm.com/models/mistralai/devstral-2-123b) | text | $0.048 / $0.24 | $0.0126 / $0.063 | −74% |
| [Wan 3.0 Reference-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-reference-to-video) | video | $0.26 / sec | $0.06825 / sec | −74% |
| [Wan 3.0 Text-to-Video](https://martllm.com/models/qwen/venice-wan-3-0-text-to-video) | video | $0.26 / sec | $0.06825 / sec | −74% |
| [Kimi K2 Thinking](https://martllm.com/models/moonshotai/kimi-k2-thinking) | text | $0.15 / $0.625 | $0.0441 / $0.1837 | −71% |
| [Nano Banana Pro (image-to-image)](https://martllm.com/models/google/nano-banana-pro-edit) | image | $0.063 / image | $0.019 / image | −70% |
| [Nano Banana Pro (Venice)](https://martllm.com/models/venice/nano-banana-pro) | image | $0.063 / image | $0.019 / image | −70% |
| [Voxtral Mini 3B 2507](https://martllm.com/models/mistralai/voxtral-mini-3b-2507) | text | $0.04 / $0.04 | $0.0126 / $0.0126 | −68% |
| [Qwen: Qwen3.8 Omni Flash](https://martllm.com/models/qwen/qwen3.8-omni-flash) | text | $0.024 / $0.0752 | $0.007875 / $0.02467 | −67% |
| [Seedance 2.5](https://martllm.com/models/bytedance/seedance-2-5) | video | $0.14 / sec | $0.04888 / sec | −65% |
| [Seedance 2.5 Reference-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-reference-to-video-basic) | video | $0.14 / sec | $0.04888 / sec | −65% |
| [Seedance 2.5 Text-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-text-to-video-basic) | video | $0.14 / sec | $0.04888 / sec | −65% |
| [Qwen 4 Max](https://martllm.com/models/qwen/qwen4-max) | text | $0.969 / $2.91 | $0.3441 / $1.03 | −64% |
| [NVIDIA Nemotron Nano 9B v2](https://martllm.com/models/nvidia/nemotron-nano-9b-v2) | text | $0.0048 / $0.0184 | $0.00189 / $0.007245 | −61% |
| [MiniMax H3](https://martllm.com/models/minimax/minimax-h3) | video | $0.04 / sec | $0.01592 / sec | −60% |
| [MiniMax H3 Reference](https://martllm.com/models/minimax/minimax-h3-reference-to-video) | video | $0.04 / sec | $0.01592 / sec | −60% |
| [Mistral Large](https://martllm.com/models/mistralai/mistral-large) | text | $0.40 / $1.20 | $0.168 / $0.504 | −58% |
| [GPT-5.2 Codex](https://martllm.com/models/openai/gpt-5.2-codex) | text | $1.75 / $14.00 | $0.8636 / $6.91 | −51% |
| [Kimi K2.5](https://martllm.com/models/moonshotai/kimi-k2.5) | text | $0.275 / $1.38 | $0.1377 / $0.6883 | −50% |
| [GLM 4.7 Flash](https://martllm.com/models/z-ai/glm-4.7-flash) | text | $0.01755 / $0.116 | $0.009599 / $0.0588 | in −45% / out −49% |
| [GPT-4o Mini](https://martllm.com/models/openai/gpt-4o-mini) | text | $0.099 / $0.396 | $0.0504 / $0.2016 | −49% |
| [GPT-5 Image](https://martllm.com/models/openai/gpt-5-image) | image | $9.30 / $9.30 | $4.83 / $4.83 | −48% |
| [GPT-OSS 120B](https://martllm.com/models/openai/gpt-oss-120b) | text | $0.0028 / $0.012 | $0.00147 / $0.0063 | −48% |
| [Magistral Small 2509](https://martllm.com/models/mistralai/magistral-small-2509) | text | $0.105 / $0.315 | $0.05775 / $0.1732 | −45% |
| [Gemma 3 4B IT](https://martllm.com/models/google/gemma-3-4b-it) | text | $0.017 / $0.034 | $0.00945 / $0.0189 | −44% |
| [GPT 5 Nano](https://martllm.com/models/openai/gpt-5-nano) | text | $0.0295 / $0.236 | $0.0168 / $0.1344 | −43% |
| [Gemma 4 31B](https://martllm.com/models/google/gemma-4-31b) | text | $0.0264 / $0.0792 | $0.01638 / $0.04914 | −38% |
| [Seedance 2.5 Image-to-Video](https://martllm.com/models/bytedance/venice-seedance-2-5-image-to-video-basic) | video | $0.14 / sec | $0.08803 / sec | −37% |
| [Seedance 2.0 Text-to-Video](https://martllm.com/models/bytedance/seedance-2-0-text-to-video) | video | $0.095 / sec | $0.0598 / sec | −37% |
| [GPT 5 Mini](https://martllm.com/models/openai/gpt-5-mini) | text | $0.0975 / $0.78 | $0.063 / $0.504 | −35% |
| [Qwen3 32B](https://martllm.com/models/qwen/qwen3-32b) | text | $0.02 / $0.07 | $0.01386 / $0.0462 | in −31% / out −34% |
| [Gemini 3.5 Flash Lite](https://martllm.com/models/google/gemini-3-5-flash-lite) | text | $0.162 / $1.35 | $0.1071 / $0.8925 | −34% |
| [Seedance 2.0 Fast Text-to-Video (Venice)](https://martllm.com/models/venice/seedance-2-fast-t2v) | video | $0.059 / sec | $0.03984 / sec | −32% |
| [Grok 4.3](https://martllm.com/models/x-ai/grok-4.3) | text | $0.5875 / $1.18 | $0.4026 / $0.8023 | in −31% / out −32% |
| [MiniMax M2.5](https://martllm.com/models/minimax/minimax-m2.5) | text | $0.0486 / $0.171 | $0.03402 / $0.1197 | −30% |
| [Qwen3 Coder Next](https://martllm.com/models/qwen/qwen3-coder-next) | text | $0.0252 / $0.168 | $0.01764 / $0.1176 | −30% |
| [Qwen 3 Coder 480b](https://martllm.com/models/qwen/qwen3-coder) | text | $0.063 / $0.21 | $0.04436 / $0.1706 | in −30% / out −19% |
| [Qwen 3.6 27B](https://martllm.com/models/qwen/qwen3.6-27b) | text | $0.1184 / $1.18 | $0.08466 / $0.84 | −29% |
| [Luma Uni-1 (Venice)](https://martllm.com/models/luma/venice-luma-uni-1) | image | $0.05 / image | $0.03675 / image | −27% |
| [Qwen Image 2.1 Pro (Venice)](https://martllm.com/models/qwen/venice-qwen-image-2-1-pro) | image | $0.05 / image | $0.03675 / image | −27% |
| [Flux 3 (image-to-image)](https://martllm.com/models/black-forest-labs/flux-3-image-edit) | image | $0.12 / image | $0.0882 / image | −26% |
| [Flux 3 (Venice)](https://martllm.com/models/black-forest-labs/venice-flux-3-image) | image | $0.12 / image | $0.0882 / image | −26% |
| [Ideogram V4 (Venice)](https://martllm.com/models/ideogram/venice-ideogram-v4) | image | $0.06 / image | $0.0441 / image | −26% |
| [Ideogram V4.5 (Venice)](https://martllm.com/models/ideogram/venice-ideogram-v4-5) | image | $0.26 / image | $0.1911 / image | −26% |
| [Krea 2 Turbo (Venice)](https://martllm.com/models/krea/venice-krea-2-turbo) | image | $0.04 / image | $0.0294 / image | −26% |
| [Krea v2 Large (Venice)](https://martllm.com/models/krea/venice-krea-v2-large) | image | $0.07 / image | $0.05145 / image | −26% |
| [Krea v2 Medium (Venice)](https://martllm.com/models/krea/venice-krea-v2-medium) | image | $0.04 / image | $0.0294 / image | −26% |
| [Luma Uni-1 Max (Venice)](https://martllm.com/models/luma/venice-luma-uni-1-max) | image | $0.12 / image | $0.0882 / image | −26% |
| [GPT Image 2.6 Sunburst (Venice)](https://martllm.com/models/openai/venice-gpt-image-2-6-sunburst) | image | $0.09 / image | $0.06615 / image | −26% |
| [Qwen Image 2.1 Turbo (Venice)](https://martllm.com/models/qwen/venice-qwen-image-2-1-turbo) | image | $0.02 / image | $0.0147 / image | −26% |
| [Seedream V5.5 (Venice)](https://martllm.com/models/bytedance/venice-seedream-v5-5) | image | $0.0255 / image | $0.01874 / image | −26% |
| [Tencent: Hy4 preview](https://martllm.com/models/tencent/hy4-preview) | text | $0.5588 / $1.68 | $0.4116 / $1.23 | −26% |
| [GPT-6.1 Sol](https://martllm.com/models/openai/gpt-6.1-sol) | text | $1.10 / $5.50 | $0.819 / $4.09 | −26% |
| [PixVerse C1 Text-to-Video (Venice)](https://martllm.com/models/venice/pixverse-c1-t2v) | video | $0.0432 / sec | $0.03234 / sec | −25% |
| [Sonilo V1.1 Sound Effects](https://martllm.com/models/sonilo/sonilo-sound-effects-v1-0) | music | $0.00207 / sec | $0.001579 / sec | −24% |
| [Sonilo V1.1 Music](https://martllm.com/models/sonilo/sonilo-music-v1-1) | music | $0.002875 / sec | $0.002194 / sec | −24% |
| [Seedream 4.5](https://martllm.com/models/bytedance/seedream-4.5) | image | $0.0164 / image | $0.0126 / image | −23% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://martllm.com/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.308 / $0.924 | $0.2377 / $0.7131 | −23% |
| [Particle AI: Particle-1](https://martllm.com/models/particle-ai/particle-1) | text | $0.0432 / $0.36 | $0.03914 / $0.2796 | in −9% / out −22% |
| [DeepSeek V3.1](https://martllm.com/models/deepseek/deepseek-v3.1) | text | $0.0775 / $0.2945 | $0.06237 / $0.231 | in −20% / out −22% |
| [Meta: Muse Wonder](https://martllm.com/models/meta-llama/muse-wonder) | text | $2.76 / $13.80 | $2.18 / $10.92 | −21% |
| [Meta: Muse Spark 1.3](https://martllm.com/models/meta-llama/muse-spark-1.3) | text | $0.8712 / $2.96 | $0.6956 / $2.37 | −20% |
| [Mistral Large 3](https://martllm.com/models/mistralai/mistral-large-3) | text | $0.11 / $0.33 | $0.0882 / $0.2646 | −20% |
| [GPT-6 Luna](https://martllm.com/models/openai/gpt-6-luna) | text | $0.073 / $0.365 | $0.0588 / $0.294 | −19% |
| [GPT-6 Luna Decisions (OpenAI)](https://martllm.com/models/openai/gpt-6-luna-decisions) | other | $0.073 / $0 | $0.0588 / $0 | in −19% / out – |
| [MiMo-V2.6-Flash](https://martllm.com/models/xiaomi/mimo-v2.6-flash) | text | $0.14 / $0.28 | $0.1132 / $0.2264 | −19% |
| [Seedream V5 Pro (Venice)](https://martllm.com/models/bytedance/venice-seedream-v5-pro) | image | $0.035 / image | $0.02835 / image | −19% |
| [GPT-6 Astra](https://martllm.com/models/openai/gpt-6-astra) | text | $4.40 / $22.00 | $3.57 / $17.85 | −19% |
| [ElevenLabs TTS v4](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4) | music | $0.092 / 1K chars | $0.07521 / 1K chars | −18% |
| [GPT-5.3 Codex](https://martllm.com/models/openai/gpt-5.3-codex) | text | $1.07 / $8.54 | $0.882 / $7.06 | −17% |
| [Qwen 3 235B A22B Instruct 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-2507) | text | $0.0938 / $0.5025 | $0.07796 / $0.4331 | in −17% / out −14% |
| [MiMo-V2.6-Pro](https://martllm.com/models/xiaomi/mimo-v2.6-pro) | text | $0.3001 / $0.6003 | $0.2512 / $0.5024 | −16% |
| [Gemma 3 27B E2EE](https://martllm.com/models/google/e2ee-gemma-3-27b) | text | $0.07 / $0.25 | $0.0588 / $0.21 | −16% |
| [Muse Image (image-to-image)](https://martllm.com/models/meta-llama/muse-image-edit) | image | $0.02 / image | $0.0168 / image | −16% |
| [GPT OSS 20B](https://martllm.com/models/openai/e2ee-gpt-oss-20b-p) | text | $0.025 / $0.095 | $0.021 / $0.0798 | −16% |
| [Mistral: Mistral Large 4](https://martllm.com/models/mistralai/mistral-large-4-0) | text | $0.357 / $1.07 | $0.301 / $0.9029 | −16% |
| [GLM 5V Turbo](https://martllm.com/models/z-ai/glm-5v-turbo) | text | $1.08 / $3.60 | $0.9198 / $3.07 | −15% |
| [GPT-6 Luna Pro](https://martllm.com/models/openai/gpt-6-luna-pro) | text | $0.10 / $0.50 | $0.0861 / $0.4305 | −14% |
| [Lyria 3 Pro](https://martllm.com/models/google-deepmind/lyria-3-pro) | music | $0.10 / track | $0.0872 / track | −13% |
| [ElevenLabs TTS v4 Turbo](https://martllm.com/models/elevenlabs/elevenlabs-tts-v4-turbo) | music | $0.046 / 1K chars | $0.04011 / 1K chars | −13% |
| [GPT OSS Safeguard 20B](https://martllm.com/models/openai/gpt-oss-safeguard-20b) | text | $0.0015 / $0.006 | $0.001523 / $0.00525 | in +2% / out −12% |
| [MiniMax M3 Preview](https://martllm.com/models/minimax/minimax-m3-preview) | text | $0.21 / $0.84 | $0.2331 / $0.9324 | +11% |
| [Aion 3.0](https://martllm.com/models/aion-labs/aion-3-0) | text | $1.95 / $3.90 | $2.17 / $4.35 | +11% |
| [Wan 2.7 Pro (image-to-image)](https://martllm.com/models/wan/wan-2-7-pro-edit) | image | $0.0564 / image | $0.063 / image | +12% |
| [Kimi K2.6](https://martllm.com/models/moonshotai/kimi-k2.6) | text | $0.0325 / $0.1705 | $0.03675 / $0.1785 | in +13% / out +5% |
| [Qwen Image 2 Pro (Venice)](https://martllm.com/models/venice/qwen-image-2-pro) | image | $0.06 / image | $0.06825 / image | +14% |
| [Kimi K2](https://martllm.com/models/moonshotai/kimi-k2) | text | $0.399 / $1.61 | $0.4549 / $1.84 | +14% |
| [Kimi K3 Fast](https://martllm.com/models/moonshotai/kimi-k3-fast-api) | text | $3.02 / $15.07 | $3.45 / $17.25 | +14% |
| [MiniMax M3](https://martllm.com/models/minimax/minimax-m3) | text | $0.096 / $0.384 | $0.1103 / $0.441 | +15% |
| [NVIDIA Nemotron 3.5 Lightning 30B](https://martllm.com/models/nvidia/nemotron-3-5-lightning-30b-a3b) | text | $0.064 / $0.1829 | $0.064 / $0.21 | in 0% / out +15% |
| [Seedream V5 Lite (Venice)](https://martllm.com/models/venice/seedream-v5-lite) | image | $0.025 / image | $0.02888 / image | +16% |
| [Qwen 3.5 35B A3B](https://martllm.com/models/qwen/qwen3.5-35b-a3b) | text | $0.102 / $0.68 | $0.1181 / $0.7875 | +16% |
| [Claude Fable 5.1](https://martllm.com/models/anthropic/claude-fable-5.1) | text | $4.80 / $24.00 | $5.57 / $27.82 | +16% |
| [Venice TTS 1 (legacy alias)](https://martllm.com/models/venice/tts-1) | speech | $0.002625 / 1K chars | $0.003052 / 1K chars | +16% |
| [Seedance 1.5 Pro (image-to-video)](https://martllm.com/models/bytedance/seedance-1-5-pro-image-to-video) | video | $0.0306 / sec | $0.0357 / sec | +17% |
| [GPT-5.6 Sol](https://martllm.com/models/openai/gpt-5.6-sol) | text | $1.40 / $7.00 | $1.64 / $8.19 | +17% |
| [Aion 2.0](https://martllm.com/models/aion-labs/aion-2.0) | text | $0.488 / $0.976 | $0.5712 / $1.14 | +17% |
| [Claude Fable 5](https://martllm.com/models/anthropic/claude-fable-5) | text | $5.20 / $26.00 | $6.09 / $30.45 | +17% |
| [Grok 4.5](https://martllm.com/models/x-ai/grok-4.5) | text | $1.26 / $3.78 | $1.48 / $4.43 | +17% |
| [Flux 2 Max (Venice)](https://martllm.com/models/venice/flux-2-max) | image | $0.0522 / image | $0.06143 / image | +18% |
| [OpenAI: GPT-6.1 Sol Pro](https://martllm.com/models/openai/gpt-6.1-sol-pro) | text | $1.46 / $7.30 | $1.72 / $8.61 | +18% |
| [Gemini 3.6 Flash](https://martllm.com/models/google/gemini-3-6-flash) | text | $0.4725 / $2.36 | $0.5591 / $2.80 | +18% |
| [GLM-5 Turbo](https://martllm.com/models/z-ai/glm-5-turbo) | text | $0.696 / $2.32 | $0.8316 / $2.77 | +19% |
| [GPT-6 Sol Pro](https://martllm.com/models/openai/gpt-6-sol-pro) | text | $1.44 / $7.20 | $1.72 / $8.61 | +20% |
| [Claude Opus 4.7](https://martllm.com/models/anthropic/claude-opus-4.7) | text | $2.10 / $10.50 | $2.52 / $12.60 | +20% |
| [Nano Banana 2 (image-to-image)](https://martllm.com/models/google/nano-banana-2-edit) | image | $0.035 / image | $0.042 / image | +20% |
| [Nano Banana 2 (Venice)](https://martllm.com/models/venice/nano-banana-2) | image | $0.035 / image | $0.042 / image | +20% |
| [Z.ai: GLM 5.3 FlashX Legal](https://martllm.com/models/z-ai/glm-5.3-flashx-legal) | text | $0.259 / $0.875 | $0.3108 / $1.05 | +20% |
| [DeepSeek V4 Flash E2EE](https://martllm.com/models/deepseek/e2ee-deepseek-v4-flash) | text | $0.1329 / $0.2723 | $0.1605 / $0.329 | +21% |
| [Claude Opus 5 (Fast)](https://martllm.com/models/anthropic/claude-opus-5-fast) | text | $7.20 / $36.00 | $8.71 / $43.58 | +21% |
| [OpenAI: GPT-6.1 Terra Pro](https://martllm.com/models/openai/gpt-6.1-terra-pro) | text | $0.71 / $3.55 | $0.861 / $4.30 | +21% |
| [Ministral 3B](https://martllm.com/models/mistralai/ministral-3-3b-instruct) | text | $0.02 / $0.02 | $0.02425 / $0.02425 | +21% |
| [Ministral 3 8B](https://martllm.com/models/mistralai/ministral-3-8b-instruct) | text | $0.03 / $0.03 | $0.03638 / $0.03638 | +21% |
| [NVIDIA Nemotron 3 Super 120B](https://martllm.com/models/nvidia/nemotron-3-super-120b) | text | $0.02 / $0.1125 | $0.02441 / $0.1339 | in +22% / out +19% |
| [Wan 2.7 Pro (Venice)](https://martllm.com/models/venice/wan-2.7-pro) | image | $0.05156 / image | $0.063 / image | +22% |
| [Firered Image (image-to-image)](https://martllm.com/models/xiaohongshu/firered-image-edit) | image | $0.024 / image | $0.0294 / image | +22% |
| [Tencent: Hy4 flash](https://martllm.com/models/tencent/hy4-flash) | text | $0.02485 / $0.09975 | $0.0305 / $0.1224 | +23% |
| [Grok 4.7](https://martllm.com/models/x-ai/grok-4.7) | text | $1.16 / $3.48 | $1.43 / $4.28 | +23% |
| [Qwen3 Next 80B A3B](https://martllm.com/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.023 / $0.253 | $0.02693 / $0.3119 | in +17% / out +23% |
| [Kling O3 Pro (image-to-video)](https://martllm.com/models/kling/kling-o3-pro-image-to-video) | video | $0.09 / sec | $0.1111 / sec | +23% |
| [GPT OSS 120B](https://martllm.com/models/openai/e2ee-gpt-oss-120b-p) | text | $0.0884 / $0.442 | $0.1092 / $0.546 | +24% |
| [Seedream V4.5 (Venice)](https://martllm.com/models/venice/seedream-v4) | image | $0.0275 / image | $0.03413 / image | +24% |
| [Chatterbox HD TTS](https://martllm.com/models/resemble-ai/tts-chatterbox-hd) | speech | $0.035 / 1K chars | $0.0436 / 1K chars | +25% |
| [Grok 4.6](https://martllm.com/models/x-ai/grok-4.6) | text | $1.24 / $3.72 | $1.55 / $4.64 | +25% |
| [Seedance 2.0 (image-to-video)](https://martllm.com/models/bytedance/seedance-2-0-image-to-video) | video | $0.0528 / sec | $0.066 / sec | +25% |
| [GPT-5.5](https://martllm.com/models/openai/gpt-5.5) | text | $2.55 / $15.30 | $3.20 / $19.21 | +26% |
| [GLM 5.2 E2EE](https://martllm.com/models/z-ai/e2ee-glm-5-2-p) | text | $1.05 / $3.45 | $1.32 / $4.35 | +26% |
| [Meta: Muse Spark 1.2](https://martllm.com/models/meta-llama/muse-spark-1.2) | text | $0.5375 / $1.83 | $0.6825 / $2.32 | +27% |
| [DeepSeek V4 Flash 0731 Fast](https://martllm.com/models/deepseek/deepseek-v4-flash-0731-fast) | text | $0.2135 / $0.427 | $0.272 / $0.5439 | +27% |
| [Qwen3.7 Max](https://martllm.com/models/qwen/qwen3.7-max) | text | $1.65 / $4.91 | $2.10 / $6.25 | +27% |
| [Wan 2.7 Pro (image-to-video)](https://martllm.com/models/wan/wan-2-7-pro-image-to-video) | video | $0.084 / sec | $0.1071 / sec | +27% |
| [Kling O3 Standard (image-to-video)](https://martllm.com/models/kling/kling-o3-standard-image-to-video) | video | $0.07 / sec | $0.08933 / sec | +28% |
| [Claude Haiku 5.5](https://martllm.com/models/anthropic/claude-haiku-5.5) | text | $0.051 / $0.255 | $0.0651 / $0.3255 | +28% |
| [Grok Imagine Pro (Venice)](https://martllm.com/models/venice/grok-imagine-pro) | image | $0.035 / image | $0.04483 / image | +28% |
| [GPT-5.2](https://martllm.com/models/openai/gpt-5.2) | text | $0.77 / $6.16 | $1.01 / $8.09 | +31% |
| [FLUX.2 Flex](https://martllm.com/models/black-forest-labs/flux.2-flex) | image | $0.0348 / megapixel | $0.04578 / megapixel | +32% |
| [DeepSeek V4 Flash 0731](https://martllm.com/models/deepseek/deepseek-v4-flash-0731) | text | $0.0288 / $0.0864 | $0.03822 / $0.07644 | in +33% / out −12% |
| [Aion 3.0 Mini](https://martllm.com/models/aion-labs/aion-3-0-mini) | text | $0.287 / $0.574 | $0.3896 / $0.7791 | +36% |
| [Grok Build 0.1](https://martllm.com/models/x-ai/grok-build-0.1) | text | $0.77 / $1.54 | $1.05 / $2.10 | +36% |
| [Qwen Image (Venice)](https://martllm.com/models/venice/qwen-image) | image | $0.015 / image | $0.02048 / image | +36% |
| [Recraft V4 (Venice)](https://martllm.com/models/venice/recraft-v4) | image | $0.025 / image | $0.03413 / image | +36% |
| [Qwen3 1.7B TTS](https://martllm.com/models/qwen/tts-qwen3-1-7b) | speech | $0.06187 / 1K chars | $0.08461 / 1K chars | +37% |
| [GPT-5.4 Mini](https://martllm.com/models/openai/gpt-5.4-mini) | text | $0.0975 / $0.585 | $0.1339 / $0.8033 | +37% |
| [Flux 1.1 (Venice, legacy)](https://martllm.com/models/venice/flux-1.1) | image | $0.006 / image | $0.0084 / image | +40% |
| [Stable Diffusion XL (Venice, legacy)](https://martllm.com/models/venice/sdxl) | image | $0.006 / image | $0.0084 / image | +40% |
| [GPT 5.4 Nano](https://martllm.com/models/openai/gpt-5.4-nano) | text | $0.036 / $0.225 | $0.0504 / $0.315 | +40% |
| [Grok Imagine (Venice)](https://martllm.com/models/venice/grok-imagine) | image | $0.015 / image | $0.021 / image | +40% |
| [Grok Imagine — Edit (Venice)](https://martllm.com/models/venice/grok-imagine-edit) | image | $0.015 / image | $0.021 / image | +40% |
| [Qwen 3.6 35B A3B (E2EE)](https://martllm.com/models/qwen/e2ee-qwen3-6-35b-a3b) | text | $0.1074 / $0.6962 | $0.151 / $0.9788 | +41% |
| [Claude Opus 4.8](https://martllm.com/models/anthropic/claude-opus-4.8) | text | $2.00 / $10.00 | $2.83 / $14.18 | +42% |
| [Reflection: Beam 1.0 501B A23B](https://martllm.com/models/reflection/beam-1.0-501b-a23b) | text | $0.21 / $0.70 | $0.2982 / $0.8946 | in +42% / out +28% |
| [Claude Sonnet 5](https://martllm.com/models/anthropic/claude-sonnet-5) | text | $0.72 / $3.60 | $1.03 / $5.14 | +43% |
| [MiniMax Speech 02 HD TTS](https://martllm.com/models/minimax/tts-minimax-speech-02-hd) | speech | $0.075 / 1K chars | $0.1076 / 1K chars | +44% |
| [GLM-4.7](https://martllm.com/models/z-ai/glm-4.7) | text | $0.20 / $0.875 | $0.2889 / $1.19 | in +44% / out +36% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://martllm.com/models/venice/elevenlabs-tts-turbo-v2-5) | speech | $0.0375 / 1K chars | $0.0545 / 1K chars | +45% |
| [xAI v1 TTS](https://martllm.com/models/x-ai/tts-xai-v1) | speech | $0.01125 / 1K chars | $0.01635 / 1K chars | +45% |
| [Claude Opus 4.6](https://martllm.com/models/anthropic/claude-opus-4.6) | text | $1.80 / $9.00 | $2.62 / $13.12 | +46% |
| [Qwen 3.7 Plus](https://martllm.com/models/qwen/qwen3.7-plus) | text | $0.305 / $1.22 | $0.4462 / $1.78 | +46% |
| [GPT-5.4 Pro](https://martllm.com/models/openai/gpt-5.4-pro) | text | $12.00 / $72.00 | $17.64 / $105.84 | +47% |
| [Qwen 3 235B A22B Thinking 2507](https://martllm.com/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.18 / $1.40 | $0.2646 / $2.06 | +47% |
| [Chroma (Venice)](https://martllm.com/models/venice/chroma) | image | $0.005 / image | $0.00735 / image | +47% |
| [Hunyuan Image 3.0 (Venice)](https://martllm.com/models/venice/hunyuan-image-v3) | image | $0.045 / image | $0.06615 / image | +47% |
| [Tencent: Hy4](https://martllm.com/models/tencent/hy4) | text | $0.2961 / $0.8879 | $0.4379 / $1.31 | +48% |
| [Claude Sonnet 4.5](https://martllm.com/models/anthropic/claude-sonnet-4.5) | text | $1.89 / $9.45 | $2.80 / $14.02 | +48% |
| [Claude Sonnet 4.6](https://martllm.com/models/anthropic/claude-sonnet-4.6) | text | $1.44 / $7.20 | $2.14 / $10.71 | +49% |
| [Wan 2.7 (Venice)](https://martllm.com/models/venice/wan-2.7) | image | $0.01688 / image | $0.0252 / image | +49% |
| [LTX 2 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-fast-text-to-video) | video | $0.04667 / sec | $0.07 / sec | +50% |
| [Veo 3 Fast Text-to-Video](https://martllm.com/models/google/veo3-fast-text-to-video) | video | $0.1155 / sec | $0.1732 / sec | +50% |
| [LTX 2 19B Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-19b-full-text-to-video) | video | $0.0616 / sec | $0.0924 / sec | +50% |
| [LongCat Text-to-Video](https://martllm.com/models/meituan/longcat-text-to-video) | video | $0.035 / sec | $0.0525 / sec | +50% |
| [Veo 3 Full Text-to-Video](https://martllm.com/models/google/veo3-full-text-to-video) | video | $0.308 / sec | $0.462 / sec | +50% |
| [LiquidAI: LFM2.5-24B-A2B](https://martllm.com/models/liquid/lfm-2.5-24b-a2b) | text | $0.035 / $0.49 | $0.0525 / $0.735 | +50% |
| [Kimi K2.7 Code](https://martllm.com/models/moonshotai/kimi-k2.7-code) | text | $0.147 / $0.735 | $0.2205 / $1.03 | in +50% / out +40% |
| [Wan 2.1 Pro Image-to-Video](https://martllm.com/models/wan/wan-2-1-pro-image-to-video) | video | $0.1027 / sec | $0.154 / sec | +50% |
| [Wan 2.6 Ultra (image-to-video)](https://martllm.com/models/wan/wan-2-6-ultra-image-to-video) | video | $0.21 / sec | $0.315 / sec | +50% |
| [Vidu Q3 Text-to-Video](https://martllm.com/models/vidu/vidu-q3-text-to-video) | video | $0.1353 / sec | $0.203 / sec | +50% |
| [LTX 2 Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-full-text-to-video) | video | $0.06183 / sec | $0.09275 / sec | +50% |
| [Kling V3 Standard Text-to-Video](https://martllm.com/models/kling/kling-v3-standard-text-to-video) | video | $0.077 / sec | $0.1159 / sec | +51% |
| [Venice SD35](https://martllm.com/models/venice/sd35) | image | $0.0045 / image | $0.006825 / image | +52% |
| [DeepSeek V4 Flash](https://martllm.com/models/deepseek/deepseek-v4-flash) | text | $0.0513 / $0.1026 | $0.0693 / $0.1559 | in +35% / out +52% |
| [GLM-5](https://martllm.com/models/z-ai/glm-5) | text | $0.33 / $1.06 | $0.5016 / $1.56 | in +52% / out +48% |
| [ElevenLabs Sound Effects v2 (Venice)](https://martllm.com/models/venice/elevenlabs-sound-effects-v2) | music | $0.00115 / sec | $0.001755 / sec | +53% |
| [Flux 1.1 Pro (Venice, legacy)](https://martllm.com/models/venice/flux-1.1-pro) | image | $0.01633 / image | $0.0252 / image | +54% |
| [Qwen 3 Coder 480B Turbo](https://martllm.com/models/qwen/qwen3-coder-turbo) | text | $0.231 / $0.99 | $0.3565 / $1.53 | +54% |
| [Wan 2.2 A14B Text-to-Video](https://martllm.com/models/wan/wan-2-2-a14b-text-to-video) | video | $0.14 / video | $0.218 / video | +56% |
| [Cosmos Predict (image-to-video)](https://martllm.com/models/nvidia/cosmos-predict-image-to-video) | video | $0.5607 / video | $0.8731 / video | +56% |
| [Runway Gen-4 Aleph](https://martllm.com/models/runway/runway-gen4-aleph) | video | $0.35 / video | $0.545 / video | +56% |
| [MiniMax M3.1 Flash](https://martllm.com/models/minimax/minimax-m3-1-flash) | text | $0.02925 / $0.117 | $0.04568 / $0.1827 | +56% |
| [Stable Audio 2.5 (Venice)](https://martllm.com/models/venice/stable-audio-25) | music | $0.1069 / track | $0.1674 / track | +57% |
| [ACE-Step 1.5 (Venice)](https://martllm.com/models/venice/ace-step-15) | music | $0.0135 / track | $0.02125 / track | +57% |
| [Veo3.1 Fast (image-to-video)](https://martllm.com/models/google/veo3-1-fast-image-to-video) | video | $0.099 / sec | $0.1559 / sec | +57% |
| [Kling V3 Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-standard-image-to-video) | video | $0.07 / sec | $0.1103 / sec | +57% |
| [Wan 2.5 Preview Text-to-Video](https://martllm.com/models/wan/wan-2-5-preview-text-to-video) | video | $0.055 / sec | $0.08662 / sec | +57% |
| [Longcat Distilled (image-to-video)](https://martllm.com/models/meituan/longcat-distilled-image-to-video) | video | $0.009 / sec | $0.01418 / sec | +58% |
| [Orpheus TTS](https://martllm.com/models/canopy-labs/tts-orpheus) | speech | $0.03438 / 1K chars | $0.0545 / 1K chars | +59% |
| [Inworld 1.5 Max TTS](https://martllm.com/models/inworld/tts-inworld-1-5-max) | speech | $0.006875 / 1K chars | $0.0109 / 1K chars | +59% |
| [NVIDIA Nemotron 3 Nano 30B](https://martllm.com/models/nvidia/nemotron-3-nano-30b-a3b) | text | $0.0495 / $0.198 | $0.07875 / $0.315 | +59% |
| [Flux 2 Pro (Venice)](https://martllm.com/models/venice/flux-2-pro) | image | $0.0165 / image | $0.02625 / image | +59% |
| [Claude Fable 5.2](https://martllm.com/models/anthropic/claude-fable-5.2) | text | $4.00 / $20.00 | $6.38 / $31.92 | +60% |
| [Mistral Small 4](https://martllm.com/models/mistralai/mistral-small-4) | text | $0.108 / $0.432 | $0.1732 / $0.693 | +60% |
| [Claude Opus 5.5](https://martllm.com/models/anthropic/claude-opus-5.5) | text | $1.28 / $6.40 | $2.06 / $10.29 | +61% |
| [Seedance 1.5 Pro Text-to-Video](https://martllm.com/models/bytedance/seedance-1-5-pro-text-to-video) | video | $0.0377 / sec | $0.0609 / sec | +62% |
| [Qwen 3.8 Max](https://martllm.com/models/qwen/qwen-3-8-max) | text | $0.175 / $0.525 | $0.2888 / $0.8662 | +65% |
| [DeepSeek V3.2](https://martllm.com/models/deepseek/deepseek-v3.2) | text | $0.0312 / $0.0456 | $0.04253 / $0.0756 | in +36% / out +66% |
| [Claude Haiku 4.5](https://martllm.com/models/anthropic/claude-haiku-4.5) | text | $0.62 / $3.10 | $1.05 / $5.25 | +69% |
| [ElevenLabs Scribe v2 (STT)](https://martllm.com/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.004509 / minute | $0.007755 / minute | +72% |
| [inclusionAI: Ling 3.1 Flash](https://martllm.com/models/inclusionai/ling-3.1-flash) | text | $0.0324 / $0.0972 | $0.05607 / $0.1682 | +73% |
| [Whisper 1 (Venice, legacy alias)](https://martllm.com/models/venice/whisper-1) | transcription | $0.003 / minute | $0.005232 / minute | +74% |
| [Kokoro Text to Speech (Venice)](https://martllm.com/models/venice/kokoro-tts) | speech | $0.00175 / 1K chars | $0.003052 / 1K chars | +74% |
| [Happyhorse 1.0 (reference-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.09198 / sec | $0.161 / sec | +75% |
| [Kling O3 4K Text-to-Video](https://martllm.com/models/kling/kling-o3-4k-text-to-video) | video | $0.278 / sec | $0.4865 / sec | +75% |
| [Kling V3 4K Text-to-Video](https://martllm.com/models/kling/kling-v3-4k-text-to-video) | video | $0.278 / sec | $0.4865 / sec | +75% |
| [Runway Gen-4 Turbo](https://martllm.com/models/runway/runway-gen4-turbo) | video | $0.0405 / sec | $0.07087 / sec | +75% |
| [Seedance 2.0 (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-reference-to-video) | video | $0.0528 / sec | $0.0924 / sec | +75% |
| [Veo3.1 Full (image-to-video)](https://martllm.com/models/google/veo3-1-full-image-to-video) | video | $0.264 / sec | $0.462 / sec | +75% |
| [Veo 3.1 Full Text-to-Video](https://martllm.com/models/google/veo3-1-full-text-to-video) | video | $0.264 / sec | $0.462 / sec | +75% |
| [Kling O3.4k (image-to-video)](https://martllm.com/models/kling/kling-o3-4k-image-to-video) | video | $0.278 / sec | $0.4865 / sec | +75% |
| [Kling O3.4k (reference-to-video)](https://martllm.com/models/kling/kling-o3-4k-reference-to-video) | video | $0.278 / sec | $0.4865 / sec | +75% |
| [Ovi Image-to-Video](https://martllm.com/models/ovi/ovi-image-to-video) | video | $0.0264 / sec | $0.0462 / sec | +75% |
| [Pixverse C1 (reference-to-video)](https://martllm.com/models/pixverse/pixverse-c1-reference-to-video) | video | $0.02598 / sec | $0.04546 / sec | +75% |
| [Pixverse C1 Transition (transition)](https://martllm.com/models/pixverse/pixverse-c1-transition) | video | $0.02598 / sec | $0.04546 / sec | +75% |
| [Pixverse V5.6 (image-to-video)](https://martllm.com/models/pixverse/pixverse-v5-6-image-to-video) | video | $0.1212 / sec | $0.2121 / sec | +75% |
| [Qwen Image 2 Pro (image-to-image)](https://martllm.com/models/qwen/qwen-image-2-pro-edit) | image | $0.06 / image | $0.105 / image | +75% |
| [Runway Gen-4.5](https://martllm.com/models/runway/runway-gen4-5) | video | $0.096 / sec | $0.168 / sec | +75% |
| [Grok Imagine High Quality (Venice)](https://martllm.com/models/venice/grok-imagine-quality) | image | $0.015 / image | $0.02625 / image | +75% |
| [Runway Gen-4.5 Text-to-Video (Venice)](https://martllm.com/models/venice/runway-gen4-5-text) | video | $0.096 / sec | $0.168 / sec | +75% |
| [Wan 2.6 (image-to-video)](https://martllm.com/models/wan/wan-2-6-image-to-video) | video | $0.066 / sec | $0.1155 / sec | +75% |
| [Wan 2.7 Text-to-Video](https://martllm.com/models/wan/wan-2-7-text-to-video) | video | $0.066 / sec | $0.1155 / sec | +75% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://martllm.com/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.054 / sec | $0.0945 / sec | +75% |
| [Grok Imagine Image To Video Private (image-to-video)](https://martllm.com/models/x-ai/grok-imagine-image-to-video-private) | video | $0.036 / sec | $0.063 / sec | +75% |
| [Grok Imagine Reference To Video Private (reference-to-video)](https://martllm.com/models/x-ai/grok-imagine-reference-to-video-private) | video | $0.036 / sec | $0.063 / sec | +75% |
| [Wan 2.7 (image-to-video)](https://martllm.com/models/wan/wan-2-7-image-to-video) | video | $0.055 / sec | $0.09817 / sec | +78% |
| [Kling O3 Pro (reference-to-video)](https://martllm.com/models/kling/kling-o3-pro-reference-to-video) | video | $0.09 / sec | $0.161 / sec | +79% |
| [Llama 3.3 70B Instruct](https://martllm.com/models/meta-llama/llama-3.3-70b-instruct) | text | $0.147 / $0.1491 | $0.1108 / $0.2684 | in −25% / out +80% |
| [Whisper Large V3 (Venice)](https://martllm.com/models/venice/whisper-large-v3) | transcription | $0.0027 / minute | $0.004905 / minute | +82% |
| [Topaz Video Upscale](https://martllm.com/models/topaz-labs/topaz-video-upscale) | video | $0.09 / video | $0.1635 / video | +82% |
| [Venice Music Gen (legacy alias)](https://martllm.com/models/venice/music-gen) | music | $0.018 / track | $0.0327 / track | +82% |
| [GPT-4o](https://martllm.com/models/openai/gpt-4o) | text | $0.50 / $2.00 | $0.9187 / $3.67 | +84% |
| [Kling O3 Pro Text-to-Video](https://martllm.com/models/kling/kling-o3-pro-text-to-video) | video | $0.0874 / sec | $0.161 / sec | +84% |
| [Kling V3 Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-pro-image-to-video) | video | $0.1045 / sec | $0.1925 / sec | +84% |
| [Kling O3 Standard Text-to-Video](https://martllm.com/models/kling/kling-o3-standard-text-to-video) | video | $0.07 / sec | $0.1291 / sec | +84% |
| [Kling V3 Pro Text-to-Video](https://martllm.com/models/kling/kling-v3-pro-text-to-video) | video | $0.1045 / sec | $0.1932 / sec | +85% |
| [Grok 4.20 Beta](https://martllm.com/models/x-ai/grok-4.20-beta) | text | $0.375 / $0.75 | $0.7157 / $1.43 | in +91% / out +90% |
| [LTX 2 v2.3 Fast Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.03667 / sec | $0.07 / sec | +91% |
| [Seedance 2.0 Fast (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-fast-reference-to-video) | video | $0.0385 / sec | $0.0735 / sec | +91% |
| [Happyhorse 1.0 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-0-image-to-video) | video | $0.08432 / sec | $0.161 / sec | +91% |
| [Happyhorse 1.1 (reference-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-1-reference-to-video) | video | $0.08432 / sec | $0.161 / sec | +91% |
| [Kling O3 Standard (reference-to-video)](https://martllm.com/models/kling/kling-o3-standard-reference-to-video) | video | $0.06782 / sec | $0.1295 / sec | +91% |
| [Kling V3.4k (reference-to-video)](https://martllm.com/models/kling/kling-v3-4k-reference-to-video) | video | $0.2548 / sec | $0.4865 / sec | +91% |
| [LongCat Distilled Text-to-Video](https://martllm.com/models/meituan/longcat-distilled-text-to-video) | video | $0.0099 / sec | $0.0189 / sec | +91% |
| [PixVerse V5.6 Text-to-Video](https://martllm.com/models/pixverse/pixverse-v5-6-text-to-video) | video | $0.1254 / sec | $0.2394 / sec | +91% |
| [Wan 2.5 Preview (image-to-video)](https://martllm.com/models/wan/wan-2-5-preview-image-to-video) | video | $0.0308 / sec | $0.0588 / sec | +91% |
| [Seedance 2.0 Mini (reference-to-video)](https://martllm.com/models/bytedance/seedance-2-0-mini-reference-to-video) | video | $0.0242 / sec | $0.0462 / sec | +91% |
| [NVIDIA Nemotron 3 Ultra 550B](https://martllm.com/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.1375 / $0.6875 | $0.2625 / $1.31 | +91% |
| [Wan 2.7 (reference-to-video)](https://martllm.com/models/wan/wan-2-7-reference-to-video) | video | $0.0605 / sec | $0.1155 / sec | +91% |
| [GLM-4.6](https://martllm.com/models/z-ai/glm-4.6) | text | $0.0946 / $0.385 | $0.1806 / $0.735 | +91% |
| [Ltx 2 V2.3 Full (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.04856 / sec | $0.09272 / sec | +91% |
| [Wan 2.6 Flash Image-to-Video](https://martllm.com/models/wan/wan-2-6-flash-image-to-video) | video | $0.02 / sec | $0.03822 / sec | +91% |
| [Qwen3 0.6B TTS](https://martllm.com/models/qwen/tts-qwen3-0-6b) | speech | $0.03938 / 1K chars | $0.0763 / 1K chars | +94% |
| [Kling 2.5 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-2-5-turbo-pro-image-to-video) | video | $0.042 / sec | $0.0819 / sec | +95% |
| [GPT Image 1.5 (Venice)](https://martllm.com/models/venice/gpt-image-1.5) | image | $0.091 / image | $0.1774 / image | +95% |
| [xAI Speech to Text v1 (Venice)](https://martllm.com/models/venice/xai-stt-v1) | transcription | $0.00085 / minute | $0.001667 / minute | +96% |
| [Gemini 3.1 Pro Preview](https://martllm.com/models/google/gemini-3.1-pro-preview) | text | $0.32 / $1.92 | $0.63 / $3.78 | +97% |
| [MiMo-V2.5-Pro](https://martllm.com/models/xiaomi/mimo-v2.5-pro) | text | $0.3045 / $0.609 | $0.3197 / $1.20 | in +5% / out +97% |
| [DeepSeek V4 Pro](https://martllm.com/models/deepseek/deepseek-v4-pro) | text | $0.18 / $0.30 | $0.2957 / $0.5914 | in +64% / out +97% |
| [Gemma 4 31B IT](https://martllm.com/models/google/gemma-4-31b-it) | text | $0.0504 / $0.1512 | $0.09954 / $0.2986 | in +98% / out +97% |
| [GPT-5.6 Luna](https://martllm.com/models/openai/gpt-5.6-luna) | text | $0.052 / $0.312 | $0.105 / $0.63 | +102% |
| [Kling 2.1 Standard](https://martllm.com/models/kling/kling-2-1-standard-image-to-video) | video | $0.025 / sec | $0.0505 / sec | +102% |
| [Mistral Small 3.2 24B Instruct](https://martllm.com/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.0345 / $0.092 | $0.0671 / $0.1864 | in +94% / out +103% |
| [LTX 2 v2.3 Full Text-to-Video](https://martllm.com/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.04417 / sec | $0.09275 / sec | +110% |
| [HappyHorse 1.0 Text-to-Video](https://martllm.com/models/happyhorse/happyhorse-1-0-text-to-video) | video | $0.1317 / sec | $0.2765 / sec | +110% |
| [Kling V3 Turbo Standard (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-standard-image-to-video) | video | $0.06165 / sec | $0.1295 / sec | +110% |
| [Longcat (image-to-video)](https://martllm.com/models/meituan/longcat-image-to-video) | video | $0.025 / sec | $0.0525 / sec | +110% |
| [Happyhorse 1.1 (image-to-video)](https://martllm.com/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.07665 / sec | $0.161 / sec | +110% |
| [Kling 2.5 Turbo Pro Text-to-Video](https://martllm.com/models/kling/kling-2-5-turbo-pro-text-to-video) | video | $0.039 / sec | $0.0819 / sec | +110% |
| [Kling V3 Turbo Pro (image-to-video)](https://martllm.com/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.07665 / sec | $0.161 / sec | +110% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://martllm.com/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.03335 / sec | $0.07004 / sec | +110% |
| [Luma Uni 1 Max (image-to-image)](https://martllm.com/models/luma/luma-uni-1-max-edit) | image | $0.065 / image | $0.1365 / image | +110% |
| [Pixverse C1 (image-to-video)](https://martllm.com/models/pixverse/pixverse-c1-image-to-video) | video | $0.02165 / sec | $0.04546 / sec | +110% |
| [Pixverse V5.6 Transition (transition)](https://martllm.com/models/pixverse/pixverse-v5-6-transition) | video | $0.101 / sec | $0.2121 / sec | +110% |
| [Venice Video Gen (legacy alias)](https://martllm.com/models/venice/video-gen) | video | $0.08 / sec | $0.168 / sec | +110% |
| [Vidu Q3 (image-to-video)](https://martllm.com/models/vidu/vidu-q3-image-to-video) | video | $0.045 / sec | $0.0945 / sec | +110% |
| [DeepSeek V4.1 Flash](https://martllm.com/models/deepseek/deepseek-v4.1-flash) | text | $0.01887 / $0.2098 | $0.04095 / $0.1575 | in +117% / out −25% |
| [MiniMax Music 2.5 (Venice)](https://martllm.com/models/venice/minimax-music-v25) | music | $0.12 / track | $0.2616 / track | +118% |
| [Meta: Muse Spark 1.2 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.2-contributor) | text | $0.035 / $0.07 | $0.07875 / $0.1575 | +125% |
| [Ministral 14B 3.0](https://martllm.com/models/mistralai/ministral-3-14b-instruct) | text | $0.046 / $0.046 | $0.108 / $0.108 | +135% |
| [Flux 2 Max — Edit (Venice)](https://martllm.com/models/black-forest-labs/flux-2-max-edit) | image | $0.084 / image | $0.1995 / image | +138% |
| [Google: Gemini 4 Hydrogen](https://martllm.com/models/google/gemini-4-hydrogen) | text | $0.285 / $1.43 | $0.6773 / $3.39 | +138% |
| [Whisper Large V3 (STT)](https://martllm.com/models/venice/whisper-large-v3) | transcription | $0.0027 / minute | $0.00654 / minute | +142% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-multilingual-v2) | music | $0.05175 / 1K chars | $0.1253 / 1K chars | +142% |
| [ElevenLabs TTS v3 (Venice audio)](https://martllm.com/models/venice/elevenlabs-tts-v3) | music | $0.05175 / 1K chars | $0.1253 / 1K chars | +142% |
| [MiniMax Music 2.6 (Venice)](https://martllm.com/models/venice/minimax-music-v26) | music | $0.108 / track | $0.2616 / track | +142% |
| [MiniMax Music 2.0 (Venice)](https://martllm.com/models/venice/minimax-music-v2) | music | $0.018 / track | $0.0436 / track | +142% |
| [MMAudio V2 Text-to-Audio (Venice)](https://martllm.com/models/venice/mmaudio-v2-text-to-audio) | music | $0.000414 / sec | $0.001003 / sec | +142% |
| [Wan 2.6 Text-to-Video](https://martllm.com/models/wan/wan-2-6-text-to-video) | video | $0.07 / sec | $0.1743 / sec | +149% |
| [Gemini 3.1 Flash TTS](https://martllm.com/models/google/tts-gemini-3-1-flash) | speech | $0.06563 / 1K chars | $0.1635 / 1K chars | +149% |
| [Gemma 3 27B](https://martllm.com/models/google/gemma-3-27b-it) | text | $0.0216 / $0.054 | $0.05712 / $0.1428 | +164% |
| [Nano Banana 2 Lite (image-to-image)](https://martllm.com/models/google/nano-banana-2-lite-edit) | image | $0.02 / image | $0.05418 / image | +171% |
| [Recraft V4 Pro (Venice)](https://martllm.com/models/venice/recraft-v4-pro) | image | $0.0725 / image | $0.1979 / image | +173% |
| [Luma Uni 1 (image-to-image)](https://martllm.com/models/luma/luma-uni-1-edit) | image | $0.0228 / image | $0.063 / image | +176% |
| [Gemini 3.5 Flash](https://martllm.com/models/google/gemini-3.5-flash) | text | $0.255 / $1.53 | $0.7245 / $4.35 | +184% |
| [Meta: Muse Spark 1.3 Contributor](https://martllm.com/models/meta-llama/muse-spark-1.3-contributor) | text | $0.036 / $0.072 | $0.105 / $0.21 | +192% |
| [Kling 2.6 Pro (image-to-video)](https://martllm.com/models/kling/kling-2-6-pro-image-to-video) | video | $0.055 / sec | $0.1617 / sec | +194% |
| [Kling 2.6 Pro Text-to-Video](https://martllm.com/models/kling/kling-2-6-pro-text-to-video) | video | $0.055 / sec | $0.1617 / sec | +194% |
| [Gemini Omni Flash (image-to-video)](https://martllm.com/models/google/gemini-omni-flash-image-to-video) | video | $0.04988 / sec | $0.1496 / sec | +200% |
| [Gemini Omni Flash (reference-to-video)](https://martllm.com/models/google/gemini-omni-flash-reference-to-video) | video | $0.04988 / sec | $0.1496 / sec | +200% |
| [GPT Image 1.5 — Edit (Venice)](https://martllm.com/models/venice/gpt-image-1-5-edit) | image | $0.126 / image | $0.378 / image | +200% |
| [Thinking Machines: Inkling](https://martllm.com/models/thinking-machines/inkling) | text | $0.28 / $1.13 | $0.861 / $3.49 | in +207% / out +208% |
| [Google: Gemini 4 Argon](https://martllm.com/models/google/gemini-4-argon) | text | $0.24 / $1.20 | $0.756 / $3.78 | +215% |
| [GPT-OSS 20B](https://martllm.com/models/openai/gpt-oss-20b) | text | $0.00504 / $0.0252 | $0.01606 / $0.08032 | +219% |
| [MoonshotAI: Kimi K3.1 Pro](https://martllm.com/models/moonshotai/kimi-k3.1-pro) | text | $0.2307 / $8.07 | $0.777 / $3.88 | in +237% / out −52% |
| [Qwen3 Coder 30B A3B Instruct](https://martllm.com/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.015 / $0.06 | $0.05198 / $0.2079 | +247% |
| [Parakeet ASR (Venice)](https://martllm.com/models/venice/parakeet-asr) | transcription | $0.0015 / minute | $0.005232 / minute | +249% |
| [Qwen 3.8 27B](https://martllm.com/models/qwen/qwen-3-8-27b) | text | $0.0012 / $0.044 | $0.0042 / $0.0483 | in +250% / out +10% |
| [GLM 4.5 Air](https://martllm.com/models/z-ai/glm-4.5-air) | text | $0.0221 / $0.1445 | $0.08379 / $0.5147 | in +279% / out +256% |
| [Gemini 3.8 Flash](https://martllm.com/models/google/gemini-3.8-flash) | text | $0.066 / $0.33 | $0.252 / $1.26 | +282% |
| [Qwen3.8 Flash](https://martllm.com/models/qwen/qwen3.8-flash) | text | $0.012 / $0.0376 | $0.04725 / $0.148 | +294% |
| [Qwen3.5 Flash](https://martllm.com/models/qwen/qwen3.5-flash) | text | $0.025 / $0.10 | $0.1029 / $0.4116 | +312% |
| [Qwen3.5 Plus](https://martllm.com/models/qwen/qwen3.5-plus) | text | $0.065 / $0.39 | $0.2675 / $1.61 | +312% |
| [Gemini 3 Flash Preview](https://martllm.com/models/google/gemini-3-flash-preview) | text | $0.02 / $0.12 | $0.084 / $0.504 | +320% |
| [ElevenLabs Music (Venice)](https://martllm.com/models/venice/elevenlabs-music) | music | $0.1725 / track | $0.7521 / track | +336% |
| [Grok Imagine Text-to-Video](https://martllm.com/models/x-ai/grok-imagine-text-to-video) | video | $0.012 / sec | $0.06143 / sec | +412% |
| [DeepSeek V4 Pro 0813](https://martllm.com/models/deepseek/deepseek-v4-pro-0813) | text | $0.06327 / $2.53 | $0.4402 / $1.33 | in +596% / out −47% |
| [DeepSeek V4.1 Flash 1017](https://martllm.com/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.00396 / $0.055 | $0.03087 / $0.126 | in +680% / out +129% |
| [GLM 5.1](https://martllm.com/models/z-ai/glm-5.1) | text | $0.042 / $0.132 | $0.3307 / $1.04 | in +687% / out +688% |
| [GLM 4.5](https://martllm.com/models/z-ai/glm-4.5) | text | $0.036 / $0.132 | $0.378 / $1.39 | +950% |
| [GLM 5.3 Flash](https://martllm.com/models/z-ai/glm-5.3-flash) | text | $0.005985 / $0.01176 | $0.03276 / $0.126 | in +447% / out +971% |
| [Nano Banana (Gemini 2.5 Flash Image)](https://martllm.com/models/google/gemini-2.5-flash-image) | image | $0.15 / $1.25 | $0.1606 / $16.07 | in +7% / out +1185% |
| [Kimi K3](https://martllm.com/models/moonshotai/kimi-k3) | text | $0.016 / $1.28 | $0.2993 / $1.57 | in +1770% / out +23% |
| [GLM 5.3](https://martllm.com/models/z-ai/glm-5.3) | text | $0.003495 / $0.07 | $0.07497 / $0.2772 | in +2045% / out +296% |
| [Gemini 3.1 Flash Lite](https://martllm.com/models/google/gemini-3.1-flash-lite) | text | $0.005 / $0.03 | $0.1837 / $1.10 | +3575% |
| [Gemini 3.7 Flash](https://martllm.com/models/google/gemini-3.7-flash) | text | $0.015 / $0.075 | $0.6221 / $3.11 | +4048% |
| [FLUX.2 Klein 4B](https://martllm.com/models/black-forest-labs/flux.2-klein-4b) | image | $0.00015 / megapixel | $0.01145 / megapixel | +7530% |
| [GLM-5.2](https://martllm.com/models/z-ai/glm-5.2) | text | $0.00042 / $0.264 | $0.05476 / $0.231 | in +12938% / out −12% |

</details>


# Changelog

Price changes between daily snapshots of [`prices.json`](prices.json), newest first.
"Official list price" = the model maker's price as carried in the catalog (see [SOURCES](README.md#sources)).
"UberLLM price" = what a buyer can count on at snapshot time (per side, the higher of the best live seller and the listed price); it moves during the day.
Text prices are $ per 1M input / output tokens. Every day's full table is in [`history/`](history/).

## 2026-11-18 (vs 2026-11-17)

**Official list price changes (10)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | text | $0.075 / $0.30 | $0.018 / $0.09 | in −76% / out −70% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.15 / $0.60 | $0.075 / $0.30 | −50% |
| [Z.ai: GLM 5.3 Prime](https://uberllm.dev/models/z-ai/glm-5.3-prime) | text | $2.80 / $8.80 | $1.68 / $5.28 | −40% |
| [Mistral Small 3.2 24B Instruct](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.0938 / $0.25 | $0.075 / $0.20 | −20% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.09 / $0.30 | $0.0765 / $0.255 | −15% |
| [Grok Imagine Text-to-Video](https://uberllm.dev/models/x-ai/grok-imagine-text-to-video) | video | $0.0895 / sec | $0.08917 / sec | 0% |
| [Tencent: Hy4 flash](https://uberllm.dev/models/tencent/hy4-flash) | text | – / – | $0.035 / $0.1405 |  |
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.09 / $1.10 | $0.10 / $1.10 | in +11% / out 0% |
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | text | $0.60 / $3.50 | $0.70 / $3.50 | in +17% / out 0% |
| [Meta: Muse Glimmer 30B](https://uberllm.dev/models/meta-llama/muse-glimmer-30b) | text | $0.30 / $1.20 | $0.35 / $1.50 | in +17% / out +25% |

**New models (3)**

| Model | Category | Official price | UberLLM price |
|---|---|---|---|
| [Inception: Mercury 2.5](https://uberllm.dev/models/inception/mercury-2.5) | text | – | $0.028 / $0.105 |
| [Voxtral Mini 3B 2507](https://uberllm.dev/models/mistralai/voxtral-mini-3b-2507) | text | $0.04 / $0.04 | $0.04 / $0.04 |
| [GLM 4.7 Flash E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-4.7-flash) | text | – | $0.0975 / $0.4125 |

<details><summary>UberLLM price moves of 10% or more (194)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [FLUX.2 Klein 4B](https://uberllm.dev/models/black-forest-labs/flux.2-klein-4b) | image | $0.00375 / megapixel | $0.00015 / megapixel | −96% |
| [Gemini 3.1 Flash Lite](https://uberllm.dev/models/google/gemini-3.1-flash-lite) | text | $0.0725 / $0.435 | $0.005 / $0.03 | −93% |
| [DeepSeek V4.1 Flash 1017](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.051 / $0.204 | $0.00396 / $0.055 | in −92% / out −73% |
| [Qwen 3.8 27B](https://uberllm.dev/models/qwen/qwen-3-8-27b) | text | $0.006 / $0.075 | $0.0012 / $0.044 | in −80% / out −41% |
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | text | $0.021 / $0.084 | $0.00504 / $0.0252 | in −76% / out −70% |
| [Qwen 3.8 Max](https://uberllm.dev/models/qwen/qwen-3-8-max) | text | $0.55 / $1.65 | $0.175 / $0.525 | −68% |
| [DeepSeek V4.1 Flash](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash) | text | $0.0588 / $0.1764 | $0.01887 / $0.2098 | in −68% / out +19% |
| [ElevenLabs Music (Venice)](https://uberllm.dev/models/venice/elevenlabs-music) | music | $0.483 / track | $0.1725 / track | −64% |
| [GPT-OSS 120B](https://uberllm.dev/models/openai/gpt-oss-120b) | text | $0.0077 / $0.033 | $0.0028 / $0.012 | −64% |
| [Gemini Omni Flash (reference-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-reference-to-video) | video | $0.114 / sec | $0.04988 / sec | −56% |
| [Gemini 3.1 Flash TTS](https://uberllm.dev/models/google/tts-gemini-3-1-flash) | speech | $0.15 / 1K chars | $0.06563 / 1K chars | −56% |
| [Recraft V4 Pro (Venice)](https://uberllm.dev/models/venice/recraft-v4-pro) | image | $0.1595 / image | $0.0725 / image | −55% |
| [Luma Uni 1 (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-edit) | image | $0.048 / image | $0.0228 / image | −52% |
| [GLM-5.2](https://uberllm.dev/models/z-ai/glm-5.2) | text | $0.00084 / $0.528 | $0.00042 / $0.264 | −50% |
| [Tencent: Hy4 flash](https://uberllm.dev/models/tencent/hy4-flash) | text | $0.049 / $0.1967 | $0.02485 / $0.09975 | −49% |
| [GPT Image 1.5 — Edit (Venice)](https://uberllm.dev/models/venice/gpt-image-1-5-edit) | image | $0.248 / image | $0.126 / image | −49% |
| [Kimi K2.6](https://uberllm.dev/models/moonshotai/kimi-k2.6) | text | $0.0585 / $0.3069 | $0.0325 / $0.1705 | −44% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-multilingual-v2) | music | $0.092 / 1K chars | $0.05175 / 1K chars | −44% |
| [ElevenLabs TTS v3 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-v3) | music | $0.092 / 1K chars | $0.05175 / 1K chars | −44% |
| [MMAudio V2 Text-to-Audio (Venice)](https://uberllm.dev/models/venice/mmaudio-v2-text-to-audio) | music | $0.000736 / sec | $0.000414 / sec | −44% |
| [Gemma 3 12B IT](https://uberllm.dev/models/google/gemma-3-12b-it) | text | $0.0265 / $0.0795 | $0.015 / $0.045 | −43% |
| [Meta: Muse Spark 1.2 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.2-contributor) | text | $0.058 / $0.116 | $0.035 / $0.07 | −40% |
| [Kling V3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-standard-image-to-video) | video | $0.112 / sec | $0.07 / sec | −38% |
| [Kling V3 Turbo Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.1226 / sec | $0.07665 / sec | −38% |
| [Kling V3 Turbo Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-standard-image-to-video) | video | $0.09864 / sec | $0.06165 / sec | −38% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.05336 / sec | $0.03335 / sec | −38% |
| [Luma Uni 1 Max (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-max-edit) | image | $0.104 / image | $0.065 / image | −38% |
| [Longcat (image-to-video)](https://uberllm.dev/models/meituan/longcat-image-to-video) | video | $0.04 / sec | $0.025 / sec | −38% |
| [Mistral Large](https://uberllm.dev/models/mistralai/mistral-large) | text | $0.64 / $1.92 | $0.40 / $1.20 | −38% |
| [Chroma (Venice)](https://uberllm.dev/models/venice/chroma) | image | $0.008 / image | $0.005 / image | −38% |
| [ElevenLabs Sound Effects v2 (Venice)](https://uberllm.dev/models/venice/elevenlabs-sound-effects-v2) | music | $0.00184 / sec | $0.00115 / sec | −38% |
| [Qwen Image (Venice)](https://uberllm.dev/models/venice/qwen-image) | image | $0.024 / image | $0.015 / image | −38% |
| [Venice Video Gen (legacy alias)](https://uberllm.dev/models/venice/video-gen) | video | $0.128 / sec | $0.08 / sec | −38% |
| [Pixverse V5.6 Transition (transition)](https://uberllm.dev/models/pixverse/pixverse-v5-6-transition) | video | $0.1616 / sec | $0.101 / sec | −37% |
| [LTX 2 v2.3 Full Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.07067 / sec | $0.04417 / sec | −37% |
| [Gemini Omni Flash (image-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-image-to-video) | video | $0.07875 / sec | $0.04988 / sec | −37% |
| [GPT Image 1.5 (Venice)](https://uberllm.dev/models/venice/gpt-image-1.5) | image | $0.143 / image | $0.091 / image | −36% |
| [ACE-Step 1.5 (Venice)](https://uberllm.dev/models/venice/ace-step-15) | music | $0.021 / track | $0.0135 / track | −36% |
| [MiniMax Music 2.0 (Venice)](https://uberllm.dev/models/venice/minimax-music-v2) | music | $0.028 / track | $0.018 / track | −36% |
| [Venice SD35](https://uberllm.dev/models/venice/sd35) | image | $0.007 / image | $0.0045 / image | −36% |
| [Qwen3 0.6B TTS](https://uberllm.dev/models/qwen/tts-qwen3-0-6b) | speech | $0.06125 / 1K chars | $0.03938 / 1K chars | −36% |
| [GLM 4.5 Air](https://uberllm.dev/models/z-ai/glm-4.5-air) | text | $0.0338 / $0.221 | $0.0221 / $0.1445 | −35% |
| [Flux 1.1 Pro (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1-pro) | image | $0.024 / image | $0.01633 / image | −32% |
| [Happyhorse 1.1 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.1125 / sec | $0.07665 / sec | −32% |
| [Seedream 4.5](https://uberllm.dev/models/bytedance/seedream-4.5) | image | $0.024 / image | $0.0164 / image | −32% |
| [LTX 2 v2.3 Fast Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.05333 / sec | $0.03667 / sec | −31% |
| [Seedance 2.0 Mini (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-reference-to-video) | video | $0.0352 / sec | $0.0242 / sec | −31% |
| [Kling V3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-v3-4k-reference-to-video) | video | $0.3706 / sec | $0.2548 / sec | −31% |
| [Kling V3 Standard Text-to-Video](https://uberllm.dev/models/kling/kling-v3-standard-text-to-video) | video | $0.112 / sec | $0.077 / sec | −31% |
| [Ltx 2 V2.3 Full (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.07064 / sec | $0.04856 / sec | −31% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.0144 / sec | $0.0099 / sec | −31% |
| [xAI Speech to Text v1 (Venice)](https://uberllm.dev/models/venice/xai-stt-v1) | transcription | $0.001228 / minute | $0.00085 / minute | −31% |
| [Whisper Large V3 (STT)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0039 / minute | $0.0027 / minute | −31% |
| [Wan 2.7 (Venice)](https://uberllm.dev/models/venice/wan-2.7) | image | $0.024 / image | $0.01688 / image | −30% |
| [Stable Audio 2.5 (Venice)](https://uberllm.dev/models/venice/stable-audio-25) | music | $0.152 / track | $0.1069 / track | −30% |
| [Gemini 3.5 Flash Lite](https://uberllm.dev/models/google/gemini-3-5-flash-lite) | text | $0.228 / $1.90 | $0.162 / $1.35 | −29% |
| [Gemma 4 31B IT](https://uberllm.dev/models/google/gemma-4-31b-it) | text | $0.0708 / $0.2124 | $0.0504 / $0.1512 | −29% |
| [Kling V3 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-pro-image-to-video) | video | $0.1466 / sec | $0.1045 / sec | −29% |
| [Kling V3 Pro Text-to-Video](https://uberllm.dev/models/kling/kling-v3-pro-text-to-video) | video | $0.1467 / sec | $0.1045 / sec | −29% |
| [Nano Banana Pro (image-to-image)](https://uberllm.dev/models/google/nano-banana-pro-edit) | image | $0.0882 / image | $0.063 / image | −29% |
| [Pixverse C1 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-c1-image-to-video) | video | $0.03031 / sec | $0.02165 / sec | −29% |
| [Hunyuan Image 3.0 (Venice)](https://uberllm.dev/models/venice/hunyuan-image-v3) | image | $0.063 / image | $0.045 / image | −29% |
| [Kokoro Text to Speech (Venice)](https://uberllm.dev/models/venice/kokoro-tts) | speech | $0.00245 / 1K chars | $0.00175 / 1K chars | −29% |
| [Vidu Q3 (image-to-video)](https://uberllm.dev/models/vidu/vidu-q3-image-to-video) | video | $0.063 / sec | $0.045 / sec | −29% |
| [Wan 2.7 (image-to-video)](https://uberllm.dev/models/wan/wan-2-7-image-to-video) | video | $0.077 / sec | $0.055 / sec | −29% |
| [NVIDIA Nemotron Nano 9B v2](https://uberllm.dev/models/nvidia/nemotron-nano-9b-v2) | text | $0.0066 / $0.0253 | $0.0048 / $0.0184 | −27% |
| [Qwen3.8 2.4T A95B](https://uberllm.dev/models/qwen/qwen3.8-2.4t-a95b) | text | $0.66 / $1.98 | $0.48 / $1.44 | −27% |
| [GLM 5.2 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5-2-p) | text | $1.44 / $4.71 | $1.05 / $3.45 | −27% |
| [Happyhorse 1.1 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-reference-to-video) | video | $0.1125 / sec | $0.08432 / sec | −25% |
| [Qwen 3 Coder 480b](https://uberllm.dev/models/qwen/qwen3-coder) | text | $0.084 / $0.28 | $0.063 / $0.21 | −25% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://uberllm.dev/models/venice/elevenlabs-tts-turbo-v2-5) | speech | $0.05 / 1K chars | $0.0375 / 1K chars | −25% |
| [Venice Music Gen (legacy alias)](https://uberllm.dev/models/venice/music-gen) | music | $0.024 / track | $0.018 / track | −25% |
| [Seedance 2.0 (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-reference-to-video) | video | $0.0704 / sec | $0.0528 / sec | −25% |
| [Kling O3.4k (image-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-image-to-video) | video | $0.3706 / sec | $0.278 / sec | −25% |
| [Kling O3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-reference-to-video) | video | $0.3706 / sec | $0.278 / sec | −25% |
| [Flux 1.1 (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1) | image | $0.008 / image | $0.006 / image | −25% |
| [Grok Imagine (Venice)](https://uberllm.dev/models/venice/grok-imagine) | image | $0.02 / image | $0.015 / image | −25% |
| [Grok Imagine — Edit (Venice)](https://uberllm.dev/models/venice/grok-imagine-edit) | image | $0.02 / image | $0.015 / image | −25% |
| [MiniMax Music 2.6 (Venice)](https://uberllm.dev/models/venice/minimax-music-v26) | music | $0.144 / track | $0.108 / track | −25% |
| [Runway Gen-4.5 Text-to-Video (Venice)](https://uberllm.dev/models/venice/runway-gen4-5-text) | video | $0.128 / sec | $0.096 / sec | −25% |
| [Stable Diffusion XL (Venice, legacy)](https://uberllm.dev/models/venice/sdxl) | image | $0.008 / image | $0.006 / image | −25% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.072 / sec | $0.054 / sec | −25% |
| [Firered Image (image-to-image)](https://uberllm.dev/models/xiaohongshu/firered-image-edit) | image | $0.032 / image | $0.024 / image | −25% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | text | $0.056 / $0.176 | $0.042 / $0.132 | −25% |
| [Veo3.1 Full (image-to-video)](https://uberllm.dev/models/google/veo3-1-full-image-to-video) | video | $0.352 / sec | $0.264 / sec | −25% |
| [Happyhorse 1.0 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.1226 / sec | $0.09198 / sec | −25% |
| [PixVerse C1 Text-to-Video (Venice)](https://uberllm.dev/models/venice/pixverse-c1-t2v) | video | $0.0576 / sec | $0.0432 / sec | −25% |
| [Kling O3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-o3-4k-text-to-video) | video | $0.3707 / sec | $0.278 / sec | −25% |
| [Kling V3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-v3-4k-text-to-video) | video | $0.3707 / sec | $0.278 / sec | −25% |
| [Ministral 3B](https://uberllm.dev/models/mistralai/ministral-3-3b-instruct) | text | $0.026 / $0.026 | $0.02 / $0.02 | −23% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.0375 / $0.15 | $0.02925 / $0.117 | −22% |
| [GPT 5 Mini](https://uberllm.dev/models/openai/gpt-5-mini) | text | $0.125 / $1.00 | $0.0975 / $0.78 | −22% |
| [Seedance 2.0 Fast (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-reference-to-video) | video | $0.049 / sec | $0.0385 / sec | −21% |
| [Happyhorse 1.0 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-image-to-video) | video | $0.1073 / sec | $0.08432 / sec | −21% |
| [Inworld 1.5 Max TTS](https://uberllm.dev/models/inworld/tts-inworld-1-5-max) | speech | $0.00875 / 1K chars | $0.006875 / 1K chars | −21% |
| [Wan 2.7 (reference-to-video)](https://uberllm.dev/models/wan/wan-2-7-reference-to-video) | video | $0.077 / sec | $0.0605 / sec | −21% |
| [PixVerse V5.6 Text-to-Video](https://uberllm.dev/models/pixverse/pixverse-v5-6-text-to-video) | video | $0.1596 / sec | $0.1254 / sec | −21% |
| [Wan 2.5 Preview (image-to-video)](https://uberllm.dev/models/wan/wan-2-5-preview-image-to-video) | video | $0.0392 / sec | $0.0308 / sec | −21% |
| [Mistral Small 3.2 24B Instruct](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.04315 / $0.115 | $0.0345 / $0.092 | −20% |
| [Devstral 2 123B](https://uberllm.dev/models/mistralai/devstral-2-123b) | text | $0.06 / $0.30 | $0.048 / $0.24 | −20% |
| [OpenAI: GPT-6.1 Sol Pro](https://uberllm.dev/models/openai/gpt-6.1-sol-pro) | text | $1.80 / $9.00 | $1.46 / $7.30 | −19% |
| [Gemma 4 31B](https://uberllm.dev/models/google/gemma-4-31b) | text | $0.0324 / $0.0972 | $0.0264 / $0.0792 | −19% |
| [Longcat Distilled (image-to-video)](https://uberllm.dev/models/meituan/longcat-distilled-image-to-video) | video | $0.0108 / sec | $0.009 / sec | −17% |
| [MiniMax Music 2.5 (Venice)](https://uberllm.dev/models/venice/minimax-music-v25) | music | $0.144 / track | $0.12 / track | −17% |
| [Recraft V4 (Venice)](https://uberllm.dev/models/venice/recraft-v4) | image | $0.03 / image | $0.025 / image | −17% |
| [GLM 5.3](https://uberllm.dev/models/z-ai/glm-5.3) | text | $0.004194 / $0.084 | $0.003495 / $0.07 | −17% |
| [Orpheus TTS](https://uberllm.dev/models/canopy-labs/tts-orpheus) | speech | $0.04063 / 1K chars | $0.03438 / 1K chars | −15% |
| [Qwen3 1.7B TTS](https://uberllm.dev/models/qwen/tts-qwen3-1-7b) | speech | $0.07312 / 1K chars | $0.06187 / 1K chars | −15% |
| [Seedream V4.5 (Venice)](https://uberllm.dev/models/venice/seedream-v4) | image | $0.0325 / image | $0.0275 / image | −15% |
| [MiniMax M2](https://uberllm.dev/models/minimax/minimax-m2) | text | $0.06375 / $0.255 | $0.054 / $0.216 | −15% |
| [Mistral: Mistral Large 4](https://uberllm.dev/models/mistralai/mistral-large-4-0) | text | $0.42 / $1.26 | $0.357 / $1.07 | −15% |
| [Qwen Image 2 Pro (image-to-image)](https://uberllm.dev/models/qwen/qwen-image-2-pro-edit) | image | $0.07 / image | $0.06 / image | −14% |
| [Grok Imagine Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-image-to-video-private) | video | $0.042 / sec | $0.036 / sec | −14% |
| [Grok Imagine Reference To Video Private (reference-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-reference-to-video-private) | video | $0.042 / sec | $0.036 / sec | −14% |
| [Seedance 2.0 (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-image-to-video) | video | $0.0616 / sec | $0.0528 / sec | −14% |
| [DeepSeek V3.2](https://uberllm.dev/models/deepseek/deepseek-v3.2) | text | $0.0364 / $0.0532 | $0.0312 / $0.0456 | −14% |
| [Veo3.1 Fast (image-to-video)](https://uberllm.dev/models/google/veo3-1-fast-image-to-video) | video | $0.1155 / sec | $0.099 / sec | −14% |
| [Veo 3.1 Fast Text-to-Video](https://uberllm.dev/models/google/veo3-1-fast-text-to-video) | video | $0.1155 / sec | $0.099 / sec | −14% |
| [Ovi Image-to-Video](https://uberllm.dev/models/ovi/ovi-image-to-video) | video | $0.0308 / sec | $0.0264 / sec | −14% |
| [Pixverse C1 (reference-to-video)](https://uberllm.dev/models/pixverse/pixverse-c1-reference-to-video) | video | $0.03031 / sec | $0.02598 / sec | −14% |
| [Pixverse C1 Transition (transition)](https://uberllm.dev/models/pixverse/pixverse-c1-transition) | video | $0.03031 / sec | $0.02598 / sec | −14% |
| [Runway Gen-4.5](https://uberllm.dev/models/runway/runway-gen4-5) | video | $0.112 / sec | $0.096 / sec | −14% |
| [Topaz Video Upscale](https://uberllm.dev/models/topaz-labs/topaz-video-upscale) | video | $0.105 / video | $0.09 / video | −14% |
| [Seedance 2.0 Fast (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-image-to-video) | video | $0.049 / sec | $0.042 / sec | −14% |
| [Veo 3.1 Full Text-to-Video](https://uberllm.dev/models/google/veo3-1-full-text-to-video) | video | $0.308 / sec | $0.264 / sec | −14% |
| [Pixverse V5.6 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-v5-6-image-to-video) | video | $0.1414 / sec | $0.1212 / sec | −14% |
| [Runway Gen-4 Turbo](https://uberllm.dev/models/runway/runway-gen4-turbo) | video | $0.04725 / sec | $0.0405 / sec | −14% |
| [Wan 2.7 Text-to-Video](https://uberllm.dev/models/wan/wan-2-7-text-to-video) | video | $0.077 / sec | $0.066 / sec | −14% |
| [Wan 2.7 Pro (Venice)](https://uberllm.dev/models/venice/wan-2.7-pro) | image | $0.06 / image | $0.05156 / image | −14% |
| [inclusionAI: Ling 3.1 Flash](https://uberllm.dev/models/inclusionai/ling-3.1-flash) | text | $0.03735 / $0.112 | $0.0324 / $0.0972 | −13% |
| [Flux 2 Max — Edit (Venice)](https://uberllm.dev/models/black-forest-labs/flux-2-max-edit) | image | $0.096 / image | $0.084 / image | −12% |
| [Nano Banana 2 (image-to-image)](https://uberllm.dev/models/google/nano-banana-2-edit) | image | $0.04 / image | $0.035 / image | −12% |
| [LongCat Text-to-Video](https://uberllm.dev/models/meituan/longcat-text-to-video) | video | $0.04 / sec | $0.035 / sec | −12% |
| [Chatterbox HD TTS](https://uberllm.dev/models/resemble-ai/tts-chatterbox-hd) | speech | $0.04 / 1K chars | $0.035 / 1K chars | −12% |
| [Nano Banana 2 (Venice)](https://uberllm.dev/models/venice/nano-banana-2) | image | $0.04 / image | $0.035 / image | −12% |
| [Mistral Large 3](https://uberllm.dev/models/mistralai/mistral-large-3) | text | $0.125 / $0.375 | $0.11 / $0.33 | −12% |
| [Grok 4.20 Beta](https://uberllm.dev/models/x-ai/grok-4.20-beta) | text | $0.425 / $0.85 | $0.375 / $0.75 | −12% |
| [MiniMax M2.5](https://uberllm.dev/models/minimax/minimax-m2.5) | text | $0.054 / $0.19 | $0.0486 / $0.171 | −10% |
| [Meta: Muse Spark Open](https://uberllm.dev/models/meta-llama/muse-spark-open) | text | $0.7375 / $2.51 | $0.8125 / $2.76 | +10% |
| [Claude Fable 5](https://uberllm.dev/models/anthropic/claude-fable-5) | text | $4.70 / $23.50 | $5.20 / $26.00 | +11% |
| [Meta: Muse Glimmer 30B](https://uberllm.dev/models/meta-llama/muse-glimmer-30b) | text | $0.21 / $0.84 | $0.217 / $0.93 | in +3% / out +11% |
| [GPT-4o](https://uberllm.dev/models/openai/gpt-4o) | text | $0.45 / $1.80 | $0.50 / $2.00 | +11% |
| [Qwen3 Coder 30B A3B Instruct](https://uberllm.dev/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.0135 / $0.054 | $0.015 / $0.06 | +11% |
| [Kimi K3 Fast](https://uberllm.dev/models/moonshotai/kimi-k3-fast-api) | text | $2.70 / $13.50 | $3.02 / $15.07 | +12% |
| [Gemma 4 E2B](https://uberllm.dev/models/google/gemma-4-e2b) | text | $0.01 / $0.02 | $0.0112 / $0.0224 | +12% |
| [DeepSeek V4 Flash E2EE](https://uberllm.dev/models/deepseek/e2ee-deepseek-v4-flash) | text | $0.1183 / $0.2424 | $0.1329 / $0.2723 | +12% |
| [NVIDIA Nemotron 3 Super 120B](https://uberllm.dev/models/nvidia/nemotron-3-super-120b) | text | $0.01875 / $0.10 | $0.02 / $0.1125 | in +7% / out +12% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.0027 / $0.009 | $0.00306 / $0.0102 | +13% |
| [Aion 3.5 Mini](https://uberllm.dev/models/aion-labs/aion-3-5-mini) | text | $0.5513 / $1.10 | $0.63 / $1.26 | +14% |
| [Claude Fable 5.1](https://uberllm.dev/models/anthropic/claude-fable-5.1) | text | $4.20 / $21.00 | $4.80 / $24.00 | +14% |
| [MiniMax M2.7](https://uberllm.dev/models/minimax/minimax-m2.7) | text | $0.1575 / $0.63 | $0.1827 / $0.7308 | +16% |
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.0198 / $0.242 | $0.023 / $0.253 | in +16% / out +5% |
| [Claude Fable 5.2](https://uberllm.dev/models/anthropic/claude-fable-5.2) | text | $3.44 / $17.20 | $4.00 / $20.00 | +16% |
| [Qwen3 Coder Next](https://uberllm.dev/models/qwen/qwen3-coder-next) | text | $0.0216 / $0.144 | $0.0252 / $0.168 | +17% |
| [Aion 2.0](https://uberllm.dev/models/aion-labs/aion-2.0) | text | $0.416 / $0.832 | $0.488 / $0.976 | +17% |
| [OpenAI: GPT-6.1 Terra](https://uberllm.dev/models/openai/gpt-6.1-terra) | text | $0.40 / $2.00 | $0.47 / $2.35 | in +17% / out +18% |
| [Ministral 3 8B](https://uberllm.dev/models/mistralai/ministral-3-8b-instruct) | text | $0.0255 / $0.0255 | $0.03 / $0.03 | +18% |
| [GPT-6 Sol](https://uberllm.dev/models/openai/gpt-6-sol) | text | $0.76 / $3.80 | $0.90 / $4.50 | +18% |
| [Qwen 2.5 7B](https://uberllm.dev/models/qwen/e2ee-qwen-2-5-7b-p) | text | $0.0325 / $0.0845 | $0.0385 / $0.1001 | +18% |
| [GPT-5.5](https://uberllm.dev/models/openai/gpt-5.5) | text | $2.15 / $12.90 | $2.55 / $15.30 | +19% |
| [GPT-5.6 Terra Pro](https://uberllm.dev/models/openai/gpt-5.6-terra-pro) | text | $1.68 / $10.08 | $2.00 / $12.00 | +19% |
| [GPT-5.4](https://uberllm.dev/models/openai/gpt-5.4) | text | $1.05 / $6.30 | $1.27 / $7.65 | +21% |
| [Qwen 3.7 Plus](https://uberllm.dev/models/qwen/qwen3.7-plus) | text | $0.2497 / $0.999 | $0.305 / $1.22 | +22% |
| [GPT-5.6 Sol Pro](https://uberllm.dev/models/openai/gpt-5.6-sol-pro) | text | $3.24 / $16.20 | $4.00 / $20.00 | +23% |
| [GPT-6 Luna](https://uberllm.dev/models/openai/gpt-6-luna) | text | $0.059 / $0.295 | $0.073 / $0.365 | +24% |
| [Whisper 1 (Venice, legacy alias)](https://uberllm.dev/models/venice/whisper-1) | transcription | $0.002397 / minute | $0.003 / minute | +25% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | text | $0.98 / $2.94 | $1.24 / $3.72 | +27% |
| [MiMo-V2.6-Flash](https://uberllm.dev/models/xiaomi/mimo-v2.6-flash) | text | $0.1092 / $0.2184 | $0.14 / $0.28 | +28% |
| [Grok 4.7](https://uberllm.dev/models/x-ai/grok-4.7) | text | $0.90 / $2.70 | $1.16 / $3.48 | +29% |
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | text | $0.114 / $0.665 | $0.147 / $0.735 | in +29% / out +11% |
| [GPT OSS Safeguard 120B](https://uberllm.dev/models/openai/gpt-oss-safeguard-120b) | text | $0.03 / $0.12 | $0.039 / $0.156 | +30% |
| [Qwen 3 Coder 480B Turbo](https://uberllm.dev/models/qwen/qwen3-coder-turbo) | text | $0.175 / $0.75 | $0.231 / $0.99 | +32% |
| [Gemini 3.1 Pro Preview](https://uberllm.dev/models/google/gemini-3.1-pro-preview) | text | $0.24 / $1.44 | $0.32 / $1.92 | +33% |
| [Nano Banana Pro (Venice)](https://uberllm.dev/models/venice/nano-banana-pro) | image | $0.045 / image | $0.063 / image | +40% |
| [Flux 2 Pro (Venice)](https://uberllm.dev/models/venice/flux-2-pro) | image | $0.0114 / image | $0.0165 / image | +45% |
| [GLM 4.7 Flash](https://uberllm.dev/models/z-ai/glm-4.7-flash) | text | $0.0121 / $0.08 | $0.01755 / $0.116 | +45% |
| [GPT-5.3 Codex](https://uberllm.dev/models/openai/gpt-5.3-codex) | text | $0.735 / $5.88 | $1.07 / $8.54 | +45% |
| [MiniMax M3 Preview](https://uberllm.dev/models/minimax/minimax-m3-preview) | text | $0.141 / $0.564 | $0.21 / $0.84 | +49% |
| [Meta: Muse Spark 1.1](https://uberllm.dev/models/meta-llama/muse-spark-1.1) | text | $0.5375 / $1.83 | $0.825 / $2.81 | +53% |
| [GPT-6 Luna Decisions (OpenAI)](https://uberllm.dev/models/openai/gpt-6-luna-decisions) | other | $0.044 / $0 | $0.073 / $0 | in +66% / out – |
| [Meta: Muse Wonder](https://uberllm.dev/models/meta-llama/muse-wonder) | text | $1.56 / $7.80 | $2.76 / $13.80 | +77% |
| [Meta: Muse Spark 1.3](https://uberllm.dev/models/meta-llama/muse-spark-1.3) | text | $0.4875 / $1.66 | $0.8712 / $2.96 | +79% |
| [Qwen 3 235B A22B Thinking 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.099 / $0.77 | $0.18 / $1.40 | +82% |
| [GPT-6 Astra](https://uberllm.dev/models/openai/gpt-6-astra) | text | $2.30 / $11.50 | $4.40 / $22.00 | +91% |
| [Gemini 3.8 Flash](https://uberllm.dev/models/google/gemini-3.8-flash) | text | $0.033 / $0.165 | $0.066 / $0.33 | +100% |
| [GPT-6.1 Sol](https://uberllm.dev/models/openai/gpt-6.1-sol) | text | $0.54 / $2.70 | $1.10 / $5.50 | +104% |
| [Z.ai: GLM 5.3 Prime](https://uberllm.dev/models/z-ai/glm-5.3-prime) | text | $0.224 / $0.704 | $0.4704 / $1.48 | +110% |
| [Flux 2 Max (Venice)](https://uberllm.dev/models/venice/flux-2-max) | image | $0.0225 / image | $0.0522 / image | +132% |
| [Qwen3.5 Flash](https://uberllm.dev/models/qwen/qwen3.5-flash) | text | $0.01 / $0.04 | $0.025 / $0.10 | +150% |
| [Llama 3.3 70B Instruct](https://uberllm.dev/models/meta-llama/llama-3.3-70b-instruct) | text | $0.049 / $0.0497 | $0.147 / $0.1491 | +200% |
| [MiniMax M2.7 Highspeed](https://uberllm.dev/models/minimax/minimax-m2.7-highspeed) | text | $0.03 / $0.12 | $0.09 / $0.36 | +200% |
| [FLUX.2 Flex](https://uberllm.dev/models/black-forest-labs/flux.2-flex) | image | $0.0036 / megapixel | $0.0348 / megapixel | +867% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://uberllm.dev/models/nvidia/nemotron-nano-12b-v2) | text | $0.004 / $0.012 | $0.054 / $0.162 | +1250% |
| [Qwen: Qwen3.8 Omni Flash](https://uberllm.dev/models/qwen/qwen3.8-omni-flash) | text | $0.0015 / $0.0047 | $0.024 / $0.0752 | +1500% |

</details>


## 2026-11-17 (vs 2026-11-16)

**Official list price changes (4)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GLM 4.5 Air](https://uberllm.dev/models/z-ai/glm-4.5-air) | text | $0.20 / $1.10 | $0.13 / $0.85 | in −35% / out −23% |
| [Qwen 3.5 397B](https://uberllm.dev/models/qwen/qwen3.5-397b-a17b) | text | $0.60 / $3.60 | $0.45 / $3.00 | in −25% / out −17% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.0675 / $0.225 | $0.09 / $0.30 | +33% |
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | text | $0.03 / $0.13 | $0.075 / $0.30 | in +150% / out +131% |

**New models (2)**

| Model | Category | Official price | UberLLM price |
|---|---|---|---|
| [Qwen 4 Max](https://uberllm.dev/models/qwen/qwen4-max) | text | $1.43 / $4.28 | $1.05 / $3.15 |
| [Tencent: Hy4 flash](https://uberllm.dev/models/tencent/hy4-flash) | text | – | $0.049 / $0.1967 |

**No longer listed (2)**: `inception/mercury-2.5`, `z-ai/e2ee-glm-4.7-flash`

<details><summary>UberLLM price moves of 10% or more (187)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://uberllm.dev/models/nvidia/nemotron-nano-12b-v2) | text | $0.068 / $0.204 | $0.004 / $0.012 | −94% |
| [Qwen: Qwen3.8 Omni Flash](https://uberllm.dev/models/qwen/qwen3.8-omni-flash) | text | $0.018 / $0.0564 | $0.0015 / $0.0047 | −92% |
| [Z.ai: GLM 5.3 Prime](https://uberllm.dev/models/z-ai/glm-5.3-prime) | text | $2.27 / $7.13 | $0.224 / $0.704 | −90% |
| [FLUX.2 Flex](https://uberllm.dev/models/black-forest-labs/flux.2-flex) | image | $0.015 / megapixel | $0.0036 / megapixel | −76% |
| [GLM 4.5 Air](https://uberllm.dev/models/z-ai/glm-4.5-air) | text | $0.138 / $0.759 | $0.0338 / $0.221 | in −76% / out −71% |
| [GLM 5.3](https://uberllm.dev/models/z-ai/glm-5.3) | text | $0.00672 / $0.288 | $0.004194 / $0.084 | in −38% / out −71% |
| [MiniMax M2.7 Highspeed](https://uberllm.dev/models/minimax/minimax-m2.7-highspeed) | text | $0.078 / $0.312 | $0.03 / $0.12 | −62% |
| [GLM-5.2](https://uberllm.dev/models/z-ai/glm-5.2) | text | $0.00196 / $1.23 | $0.00084 / $0.528 | −57% |
| [DeepSeek V3.2](https://uberllm.dev/models/deepseek/deepseek-v3.2) | text | $0.06726 / $0.09831 | $0.0364 / $0.0532 | −46% |
| [Google: Gemini 4 Hydrogen](https://uberllm.dev/models/google/gemini-4-hydrogen) | text | $0.495 / $2.48 | $0.285 / $1.43 | −42% |
| [Gemini 2.5 Pro](https://uberllm.dev/models/google/gemini-2.5-pro) | text | $0.2875 / $2.30 | $0.175 / $1.40 | −39% |
| [ElevenLabs Scribe v2 (STT)](https://uberllm.dev/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.007977 / minute | $0.00501 / minute | −37% |
| [GPT-6 Luna Decisions (OpenAI)](https://uberllm.dev/models/openai/gpt-6-luna-decisions) | other | $0.067 / $0 | $0.044 / $0 | in −34% / out – |
| [Whisper 1 (Venice, legacy alias)](https://uberllm.dev/models/venice/whisper-1) | transcription | $0.0036 / minute | $0.002397 / minute | −33% |
| [Gemini 3.7 Flash](https://uberllm.dev/models/google/gemini-3.7-flash) | text | $0.0225 / $0.1125 | $0.015 / $0.075 | −33% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.00405 / $0.0135 | $0.0027 / $0.009 | −33% |
| [Qwen 3.8 27B](https://uberllm.dev/models/qwen/qwen-3-8-27b) | text | $0.009 / $0.1125 | $0.006 / $0.075 | −33% |
| [Qwen3.8 Flash](https://uberllm.dev/models/qwen/qwen3.8-flash) | text | $0.018 / $0.0564 | $0.012 / $0.0376 | −33% |
| [GPT-OSS 120B](https://uberllm.dev/models/openai/gpt-oss-120b) | text | $0.0112 / $0.048 | $0.0077 / $0.033 | −31% |
| [MiMo-V2.5-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.5-pro) | text | $0.435 / $0.87 | $0.3045 / $0.609 | −30% |
| [Mistral: Mistral Large 4](https://uberllm.dev/models/mistralai/mistral-large-4-0) | text | $0.567 / $1.70 | $0.42 / $1.26 | −26% |
| [Moondream: Moondream 3 Preview](https://uberllm.dev/models/moondream/moondream3-preview) | text | $0.27 / $2.25 | $0.21 / $1.75 | −22% |
| [MiMo-V2.6-Pro-UltraSpeed](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro-ultraspeed) | text | $3.92 / $7.83 | $3.04 / $6.09 | −22% |
| [JEV 1.13 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.13) | other | $0.03822 / $0 | $0.02982 / $0 | in −22% / out – |
| [Elorian: Glimpse](https://uberllm.dev/models/elorian/glimpse) | text | $0.534 / $2.67 | $0.42 / $2.10 | −21% |
| [Z.ai: GLM 5.3 FlashX Legal](https://uberllm.dev/models/z-ai/glm-5.3-flashx-legal) | text | $0.3293 / $1.11 | $0.259 / $0.875 | −21% |
| [Meta: Muse Ember](https://uberllm.dev/models/meta-llama/muse-ember) | text | $0.094 / $0.47 | $0.074 / $0.37 | −21% |
| [OpenAI: GPT-6.1 Terra Pro](https://uberllm.dev/models/openai/gpt-6.1-terra-pro) | text | $0.90 / $4.50 | $0.71 / $3.55 | −21% |
| [JEV 1.14 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.14) | other | $0.0378 / $0 | $0.02982 / $0 | in −21% / out – |
| [GLM 5.3 Flash](https://uberllm.dev/models/z-ai/glm-5.3-flash) | text | $0.007581 / $0.0149 | $0.005985 / $0.01176 | −21% |
| [Particle AI: Particle-1](https://uberllm.dev/models/particle-ai/particle-1) | text | $0.0528 / $0.44 | $0.042 / $0.35 | −20% |
| [GPT-6 Sol Pro](https://uberllm.dev/models/openai/gpt-6-sol-pro) | text | $1.80 / $9.00 | $1.44 / $7.20 | −20% |
| [Tencent: Hy4](https://uberllm.dev/models/tencent/hy4) | text | $0.3544 / $1.06 | $0.2836 / $0.8503 | −20% |
| [Gemini 3.8 Flash](https://uberllm.dev/models/google/gemini-3.8-flash) | text | $0.04125 / $0.2062 | $0.033 / $0.165 | −20% |
| [GPT OSS Safeguard 120B](https://uberllm.dev/models/openai/gpt-oss-safeguard-120b) | text | $0.0375 / $0.15 | $0.03 / $0.12 | −20% |
| [Tencent HY3](https://uberllm.dev/models/tencent/hy3) | text | $0.1175 / $0.4699 | $0.09636 / $0.3854 | −18% |
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | text | $0.138 / $0.805 | $0.114 / $0.665 | −17% |
| [Aion 2.0](https://uberllm.dev/models/aion-labs/aion-2.0) | text | $0.496 / $0.992 | $0.416 / $0.832 | −16% |
| [GPT Image 1.5 (Venice)](https://uberllm.dev/models/venice/gpt-image-1.5) | image | $0.169 / image | $0.143 / image | −15% |
| [Qwen Image 2 Pro (Venice)](https://uberllm.dev/models/venice/qwen-image-2-pro) | image | $0.065 / image | $0.055 / image | −15% |
| [xAI v1 TTS](https://uberllm.dev/models/x-ai/tts-xai-v1) | speech | $0.01219 / 1K chars | $0.01031 / 1K chars | −15% |
| [Ministral 14B 3.0](https://uberllm.dev/models/mistralai/ministral-3-14b-instruct) | text | $0.054 / $0.054 | $0.046 / $0.046 | −15% |
| [inclusionAI: Ling 3.1 Flash](https://uberllm.dev/models/inclusionai/ling-3.1-flash) | text | $0.04365 / $0.131 | $0.03735 / $0.112 | −14% |
| [StepFun: Step 5 Preview](https://uberllm.dev/models/stepfun/step-5-preview) | text | $0.81 / $2.19 | $0.6963 / $1.88 | −14% |
| [Whisper Large V3 (STT)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0045 / minute | $0.0039 / minute | −13% |
| [GLM-4.6](https://uberllm.dev/models/z-ai/glm-4.6) | text | $0.1075 / $0.4375 | $0.0946 / $0.385 | −12% |
| [Meta: Muse Glimmer 30B](https://uberllm.dev/models/meta-llama/muse-glimmer-30b) | text | $0.237 / $0.948 | $0.21 / $0.84 | −11% |
| [Grok 4.20 Beta](https://uberllm.dev/models/x-ai/grok-4.20-beta) | text | $0.475 / $0.95 | $0.425 / $0.85 | −11% |
| [GPT 5.4 Nano](https://uberllm.dev/models/openai/gpt-5.4-nano) | text | $0.04 / $0.25 | $0.036 / $0.225 | −10% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://uberllm.dev/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.2772 / $0.8316 | $0.308 / $0.924 | +11% |
| [Qwen3 VL 235B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-thinking) | text | $0.1323 / $1.20 | $0.147 / $1.33 | +11% |
| [Grok Imagine — Edit (Venice)](https://uberllm.dev/models/venice/grok-imagine-edit) | image | $0.018 / image | $0.02 / image | +11% |
| [Claude Sonnet 5.5](https://uberllm.dev/models/anthropic/claude-sonnet-5.5) | text | $1.06 / $5.30 | $1.18 / $5.90 | +11% |
| [Happyhorse 1.1 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.09964 / sec | $0.1125 / sec | +13% |
| [Happyhorse 1.1 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-reference-to-video) | video | $0.09964 / sec | $0.1125 / sec | +13% |
| [Meta: Muse Spark 1.2](https://uberllm.dev/models/meta-llama/muse-spark-1.2) | text | $0.475 / $1.61 | $0.5375 / $1.83 | +13% |
| [Z.ai: GLM 5.3 FlashX](https://uberllm.dev/models/z-ai/glm-5.3-flashx) | text | $0.222 / $0.75 | $0.2516 / $0.85 | +13% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.033 / $0.132 | $0.0375 / $0.15 | +14% |
| [Aion 3.0 Mini](https://uberllm.dev/models/aion-labs/aion-3-0-mini) | text | $0.252 / $0.504 | $0.287 / $0.574 | +14% |
| [MiniMax M3 Preview](https://uberllm.dev/models/minimax/minimax-m3-preview) | text | $0.1234 / $0.4937 | $0.141 / $0.564 | +14% |
| [Cohere: Command A+](https://uberllm.dev/models/cohere/command-a-plus) | text | $0.183 / $0.915 | $0.21 / $1.05 | +15% |
| [Qwen: Qwen3.8 Max Prime](https://uberllm.dev/models/qwen/qwen3.8-max-prime) | text | $2.44 / $7.32 | $2.80 / $8.40 | +15% |
| [MiMo-V2.6-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro) | text | $0.261 / $0.522 | $0.3001 / $0.6003 | +15% |
| [Magistral Small 2509](https://uberllm.dev/models/mistralai/magistral-small-2509) | text | $0.095 / $0.285 | $0.11 / $0.33 | +16% |
| [NVIDIA Nemotron 3 Ultra 550B](https://uberllm.dev/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.1187 / $0.5938 | $0.1375 / $0.6875 | +16% |
| [Claude Haiku 5.5](https://uberllm.dev/models/anthropic/claude-haiku-5.5) | text | $0.044 / $0.22 | $0.051 / $0.255 | +16% |
| [Seed 2.1 Turbo](https://uberllm.dev/models/bytedance/seed-2-1-turbo) | text | $0.275 / $1.38 | $0.32 / $1.60 | +16% |
| [GPT-5.2 Codex](https://uberllm.dev/models/openai/gpt-5.2-codex) | text | $1.36 / $10.92 | $1.59 / $12.74 | +17% |
| [Grok Build 0.1](https://uberllm.dev/models/x-ai/grok-build-0.1) | text | $0.66 / $1.32 | $0.77 / $1.54 | +17% |
| [GPT-5.6 Sol Pro](https://uberllm.dev/models/openai/gpt-5.6-sol-pro) | text | $2.76 / $13.80 | $3.24 / $16.20 | +17% |
| [Claude Fable 5](https://uberllm.dev/models/anthropic/claude-fable-5) | text | $4.00 / $20.00 | $4.70 / $23.50 | +18% |
| [GPT-5.6 Luna Pro](https://uberllm.dev/models/openai/gpt-5.6-luna-pro) | text | $0.1339 / $0.8032 | $0.158 / $0.948 | +18% |
| [DeepSeek V4 Flash](https://uberllm.dev/models/deepseek/deepseek-v4-flash) | text | $0.0432 / $0.0864 | $0.0513 / $0.1026 | +19% |
| [Aion 3.5](https://uberllm.dev/models/aion-labs/aion-3-5) | text | $2.36 / $4.72 | $2.81 / $5.62 | +19% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | text | $0.82 / $2.46 | $0.98 / $2.94 | +20% |
| [Qwen3.7 Max](https://uberllm.dev/models/qwen/qwen3.7-max) | text | $1.38 / $4.11 | $1.65 / $4.91 | +20% |
| [GPT-4o Mini](https://uberllm.dev/models/openai/gpt-4o-mini) | text | $0.0825 / $0.33 | $0.099 / $0.396 | +20% |
| [GPT-5.6 Terra Pro](https://uberllm.dev/models/openai/gpt-5.6-terra-pro) | text | $1.40 / $8.40 | $1.68 / $10.08 | +20% |
| [Qwen 3.6 35B A3B](https://uberllm.dev/models/qwen/qwen3-6-35b-a3b) | text | $0.034 / $0.34 | $0.041 / $0.41 | +21% |
| [Grok 4.7](https://uberllm.dev/models/x-ai/grok-4.7) | text | $0.74 / $2.22 | $0.90 / $2.70 | +22% |
| [Qwen 3 235B A22B Thinking 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.081 / $0.63 | $0.099 / $0.77 | +22% |
| [LTX 2 v2.3 Fast Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.04333 / sec | $0.05333 / sec | +23% |
| [Kling V3 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-pro-image-to-video) | video | $0.1191 / sec | $0.1466 / sec | +23% |
| [Ltx 2 V2.3 Full (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.0574 / sec | $0.07064 / sec | +23% |
| [Luma Uni 1 Max (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-max-edit) | image | $0.0845 / image | $0.104 / image | +23% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.0117 / sec | $0.0144 / sec | +23% |
| [Pixverse V5.6 Transition (transition)](https://uberllm.dev/models/pixverse/pixverse-v5-6-transition) | video | $0.1313 / sec | $0.1616 / sec | +23% |
| [PixVerse C1 Text-to-Video (Venice)](https://uberllm.dev/models/venice/pixverse-c1-t2v) | video | $0.0468 / sec | $0.0576 / sec | +23% |
| [Venice TTS 1 (legacy alias)](https://uberllm.dev/models/venice/tts-1) | speech | $0.002275 / 1K chars | $0.0028 / 1K chars | +23% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.0585 / sec | $0.072 / sec | +23% |
| [Seedance 2.0 Mini (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-reference-to-video) | video | $0.0286 / sec | $0.0352 / sec | +23% |
| [Seedance 2.0 (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-reference-to-video) | video | $0.0572 / sec | $0.0704 / sec | +23% |
| [Gemini Omni Flash (reference-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-reference-to-video) | video | $0.09262 / sec | $0.114 / sec | +23% |
| [Gemini 3.1 Flash TTS](https://uberllm.dev/models/google/tts-gemini-3-1-flash) | speech | $0.1219 / 1K chars | $0.15 / 1K chars | +23% |
| [Veo3.1 Full (image-to-video)](https://uberllm.dev/models/google/veo3-1-full-image-to-video) | video | $0.286 / sec | $0.352 / sec | +23% |
| [Happyhorse 1.0 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.09964 / sec | $0.1226 / sec | +23% |
| [Kling O3.4k (image-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-image-to-video) | video | $0.3011 / sec | $0.3706 / sec | +23% |
| [Kling O3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-reference-to-video) | video | $0.3011 / sec | $0.3706 / sec | +23% |
| [Kling V3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-v3-4k-reference-to-video) | video | $0.3011 / sec | $0.3706 / sec | +23% |
| [Kling V3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-standard-image-to-video) | video | $0.091 / sec | $0.112 / sec | +23% |
| [Kling V3 Standard Text-to-Video](https://uberllm.dev/models/kling/kling-v3-standard-text-to-video) | video | $0.091 / sec | $0.112 / sec | +23% |
| [Kling V3 Turbo Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.09964 / sec | $0.1226 / sec | +23% |
| [Kling V3 Turbo Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-standard-image-to-video) | video | $0.08014 / sec | $0.09864 / sec | +23% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.04335 / sec | $0.05336 / sec | +23% |
| [Luma Uni 1 (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-edit) | image | $0.039 / image | $0.048 / image | +23% |
| [Longcat (image-to-video)](https://uberllm.dev/models/meituan/longcat-image-to-video) | video | $0.0325 / sec | $0.04 / sec | +23% |
| [LongCat Text-to-Video](https://uberllm.dev/models/meituan/longcat-text-to-video) | video | $0.0325 / sec | $0.04 / sec | +23% |
| [Chatterbox HD TTS](https://uberllm.dev/models/resemble-ai/tts-chatterbox-hd) | speech | $0.0325 / 1K chars | $0.04 / 1K chars | +23% |
| [Chroma (Venice)](https://uberllm.dev/models/venice/chroma) | image | $0.0065 / image | $0.008 / image | +23% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-multilingual-v2) | music | $0.07475 / 1K chars | $0.092 / 1K chars | +23% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://uberllm.dev/models/venice/elevenlabs-tts-turbo-v2-5) | speech | $0.04063 / 1K chars | $0.05 / 1K chars | +23% |
| [ElevenLabs TTS v3 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-v3) | music | $0.07475 / 1K chars | $0.092 / 1K chars | +23% |
| [Flux 1.1 (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1) | image | $0.0065 / image | $0.008 / image | +23% |
| [Flux 1.1 Pro (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1-pro) | image | $0.0195 / image | $0.024 / image | +23% |
| [Venice Music Gen (legacy alias)](https://uberllm.dev/models/venice/music-gen) | music | $0.0195 / track | $0.024 / track | +23% |
| [Qwen Image (Venice)](https://uberllm.dev/models/venice/qwen-image) | image | $0.0195 / image | $0.024 / image | +23% |
| [Runway Gen-4.5 Text-to-Video (Venice)](https://uberllm.dev/models/venice/runway-gen4-5-text) | video | $0.104 / sec | $0.128 / sec | +23% |
| [Stable Diffusion XL (Venice, legacy)](https://uberllm.dev/models/venice/sdxl) | image | $0.0065 / image | $0.008 / image | +23% |
| [Venice Video Gen (legacy alias)](https://uberllm.dev/models/venice/video-gen) | video | $0.104 / sec | $0.128 / sec | +23% |
| [Firered Image (image-to-image)](https://uberllm.dev/models/xiaohongshu/firered-image-edit) | image | $0.026 / image | $0.032 / image | +23% |
| [Kling O3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-o3-4k-text-to-video) | video | $0.3012 / sec | $0.3707 / sec | +23% |
| [Kling V3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-v3-4k-text-to-video) | video | $0.3012 / sec | $0.3707 / sec | +23% |
| [Kling V3 Pro Text-to-Video](https://uberllm.dev/models/kling/kling-v3-pro-text-to-video) | video | $0.1192 / sec | $0.1467 / sec | +23% |
| [LTX 2 v2.3 Full Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.05742 / sec | $0.07067 / sec | +23% |
| [GLM 5V Turbo](https://uberllm.dev/models/z-ai/glm-5v-turbo) | text | $0.876 / $2.92 | $1.08 / $3.60 | +23% |
| [DeepSeek V3.1](https://uberllm.dev/models/deepseek/deepseek-v3.1) | text | $0.06 / $0.228 | $0.0743 / $0.2823 | +24% |
| [Reflection: Beam 1.0 501B A23B](https://uberllm.dev/models/reflection/beam-1.0-501b-a23b) | text | $0.168 / $0.56 | $0.21 / $0.70 | +25% |
| [FLUX.2 Klein 4B](https://uberllm.dev/models/black-forest-labs/flux.2-klein-4b) | image | $0.003 / megapixel | $0.00375 / megapixel | +25% |
| [MiniMax M2](https://uberllm.dev/models/minimax/minimax-m2) | text | $0.051 / $0.204 | $0.06375 / $0.255 | +25% |
| [GPT-6 Luna](https://uberllm.dev/models/openai/gpt-6-luna) | text | $0.047 / $0.235 | $0.059 / $0.295 | +26% |
| [Claude Sonnet 4.6](https://uberllm.dev/models/anthropic/claude-sonnet-4.6) | text | $1.14 / $5.70 | $1.44 / $7.20 | +26% |
| [GPT-5.6 Sol](https://uberllm.dev/models/openai/gpt-5.6-sol) | text | $1.04 / $5.20 | $1.32 / $6.60 | +27% |
| [Claude Opus 4.7](https://uberllm.dev/models/anthropic/claude-opus-4.7) | text | $1.65 / $8.25 | $2.10 / $10.50 | +27% |
| [Aion 3.0](https://uberllm.dev/models/aion-labs/aion-3-0) | text | $1.53 / $3.06 | $1.95 / $3.90 | +27% |
| [GPT 5 Nano](https://uberllm.dev/models/openai/gpt-5-nano) | text | $0.0215 / $0.172 | $0.0275 / $0.22 | +28% |
| [Grok 4.5](https://uberllm.dev/models/x-ai/grok-4.5) | text | $0.98 / $2.94 | $1.26 / $3.78 | +29% |
| [Sakana: Sakana Namazu](https://uberllm.dev/models/sakana/sakana-namazu) | text | $0.7315 / $3.08 | $0.95 / $4.00 | +30% |
| [Kimi K2.5](https://uberllm.dev/models/moonshotai/kimi-k2.5) | text | $0.21 / $1.05 | $0.275 / $1.38 | +31% |
| [Claude Sonnet 4.5](https://uberllm.dev/models/anthropic/claude-sonnet-4.5) | text | $1.44 / $7.20 | $1.89 / $9.45 | +31% |
| [Kimi K2 Thinking](https://uberllm.dev/models/moonshotai/kimi-k2-thinking) | text | $0.114 / $0.475 | $0.15 / $0.625 | +32% |
| [Qwen3 32B](https://uberllm.dev/models/qwen/qwen3-32b) | text | $0.0152 / $0.0532 | $0.02 / $0.07 | +32% |
| [Grok 4.20 Multi-Agent Beta](https://uberllm.dev/models/x-ai/grok-4.20-multi-agent-beta) | text | $0.4745 / $0.949 | $0.625 / $1.25 | +32% |
| [Gemini 3 Flash Preview](https://uberllm.dev/models/google/gemini-3-flash-preview) | text | $0.015 / $0.09 | $0.02 / $0.12 | +33% |
| [GPT-5.6 Terra](https://uberllm.dev/models/openai/gpt-5.6-terra) | text | $0.30 / $1.80 | $0.40 / $2.40 | +33% |
| [Llama 3.2 3B](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct) | text | $0.02596 / $0.1709 | $0.03512 / $0.2311 | +35% |
| [Claude Opus 5.5](https://uberllm.dev/models/anthropic/claude-opus-5.5) | text | $1.00 / $5.00 | $1.36 / $6.80 | +36% |
| [Qwen 3.5 397B](https://uberllm.dev/models/qwen/qwen3.5-397b-a17b) | text | $0.276 / $1.66 | $0.342 / $2.28 | in +24% / out +38% |
| [Grok 4.3](https://uberllm.dev/models/x-ai/grok-4.3) | text | $0.45 / $0.90 | $0.6375 / $1.27 | +42% |
| [Claude Opus 4.8](https://uberllm.dev/models/anthropic/claude-opus-4.8) | text | $1.40 / $7.00 | $2.00 / $10.00 | +43% |
| [MiniMax M2.5](https://uberllm.dev/models/minimax/minimax-m2.5) | text | $0.0378 / $0.133 | $0.054 / $0.19 | +43% |
| [DeepSeek V4 Flash 0731](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731) | text | $0.0198 / $0.0594 | $0.0288 / $0.0864 | +45% |
| [Mistral Small 3.2 24B Instruct](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.02908 / $0.0775 | $0.04315 / $0.115 | +48% |
| [Sakana: Fugu Max](https://uberllm.dev/models/sakana/fugu-max) | text | $0.94 / $2.82 | $1.40 / $4.20 | +49% |
| [GPT-6.1 Sol](https://uberllm.dev/models/openai/gpt-6.1-sol) | text | $0.36 / $1.80 | $0.54 / $2.70 | +50% |
| [GPT-5.4 Pro](https://uberllm.dev/models/openai/gpt-5.4-pro) | text | $7.80 / $46.80 | $12.00 / $72.00 | +54% |
| [GPT-5.4](https://uberllm.dev/models/openai/gpt-5.4) | text | $0.675 / $4.05 | $1.05 / $6.30 | +56% |
| [Qwen3 VL 30B A3B](https://uberllm.dev/models/qwen/qwen3-vl-30b-a3b-thinking) | text | $0.1525 / $0.549 | $0.24 / $0.864 | +57% |
| [Claude Opus 4.5](https://uberllm.dev/models/anthropic/claude-opus-4.5) | text | $1.65 / $8.25 | $2.60 / $13.00 | +58% |
| [GPT 5 Mini](https://uberllm.dev/models/openai/gpt-5-mini) | text | $0.0775 / $0.62 | $0.125 / $1.00 | +61% |
| [Claude Opus 5](https://uberllm.dev/models/anthropic/claude-opus-5) | text | $1.50 / $7.50 | $2.45 / $12.25 | +63% |
| [GPT-5.2](https://uberllm.dev/models/openai/gpt-5.2) | text | $0.4375 / $3.50 | $0.7175 / $5.74 | +64% |
| [GPT-5.3 Codex](https://uberllm.dev/models/openai/gpt-5.3-codex) | text | $0.4375 / $3.50 | $0.735 / $5.88 | +68% |
| [NVIDIA Nemotron 3 Nano 30B](https://uberllm.dev/models/nvidia/nemotron-3-nano-30b-a3b) | text | $0.02925 / $0.117 | $0.0495 / $0.198 | +69% |
| [Google: Gemini 4 Carbon](https://uberllm.dev/models/google/gemini-4-carbon) | text | $0.48 / $2.40 | $0.82 / $4.10 | +71% |
| [MiMo-V2.5](https://uberllm.dev/models/xiaomi/mimo-v2-5) | text | $0.156 / $0.78 | $0.268 / $1.34 | +72% |
| [GPT-5.5](https://uberllm.dev/models/openai/gpt-5.5) | text | $1.25 / $7.50 | $2.15 / $12.90 | +72% |
| [MiniMax M3](https://uberllm.dev/models/minimax/minimax-m3) | text | $0.054 / $0.216 | $0.093 / $0.372 | +72% |
| [Fireworks: Ember-1](https://uberllm.dev/models/fireworks/ember-1) | text | $1.23 / $6.15 | $2.13 / $10.65 | +73% |
| [Llama 3.3 70B Instruct](https://uberllm.dev/models/meta-llama/llama-3.3-70b-instruct) | text | $0.028 / $0.04704 | $0.049 / $0.0497 | in +75% / out +6% |
| [Whisper Large V3 (Venice)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0015 / minute | $0.0027 / minute | +80% |
| [Sakana: Fugu Ultra v2](https://uberllm.dev/models/sakana/fugu-ultra-v2) | text | $1.90 / $11.40 | $3.50 / $21.00 | +84% |
| [DeepSeek V4.1 Flash 1017](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.0255 / $0.102 | $0.051 / $0.204 | +100% |
| [DeepSeek V4 Pro 0813](https://uberllm.dev/models/deepseek/deepseek-v4-pro-0813) | text | $0.03108 / $1.24 | $0.06327 / $2.53 | +104% |
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | text | $0.0099 / $0.0429 | $0.021 / $0.084 | in +112% / out +96% |
| [GPT-5.5 Pro](https://uberllm.dev/models/openai/gpt-5.5-pro) | text | $9.30 / $55.80 | $20.40 / $122.40 | +119% |
| [MiniMax M2.7](https://uberllm.dev/models/minimax/minimax-m2.7) | text | $0.0672 / $0.2688 | $0.1575 / $0.63 | +134% |
| [GPT-6 Sol](https://uberllm.dev/models/openai/gpt-6-sol) | text | $0.32 / $1.60 | $0.76 / $3.80 | in +138% / out +137% |
| [DeepSeek V4 Pro](https://uberllm.dev/models/deepseek/deepseek-v4-pro) | text | $0.072 / $0.12 | $0.18 / $0.30 | +150% |
| [DeepSeek V4.1 Flash](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash) | text | $0.02332 / $0.09329 | $0.0588 / $0.1764 | in +152% / out +89% |
| [GPT-6 Astra](https://uberllm.dev/models/openai/gpt-6-astra) | text | $0.90 / $4.50 | $2.30 / $11.50 | +156% |
| [Seedream 4.5](https://uberllm.dev/models/bytedance/seedream-4.5) | image | $0.008 / image | $0.024 / image | +200% |
| [Nano Banana (Gemini 2.5 Flash Image)](https://uberllm.dev/models/google/gemini-2.5-flash-image) | image | $0.045 / $0.375 | $0.15 / $1.25 | +233% |
| [Gemini 3.5 Flash](https://uberllm.dev/models/google/gemini-3.5-flash) | text | $0.075 / $0.45 | $0.255 / $1.53 | +240% |
| [MoonshotAI: Kimi K3.1 Pro](https://uberllm.dev/models/moonshotai/kimi-k3.1-pro) | text | $0.05803 / $2.19 | $0.2283 / $7.98 | in +293% / out +265% |
| [Qwen: Qwen3.8 Max (0902)](https://uberllm.dev/models/qwen/qwen3.8-max-0902) | text | $0.18 / $0.54 | $0.74 / $2.22 | +311% |
| [Flux 2 Pro (Venice)](https://uberllm.dev/models/venice/flux-2-pro) | image | $0.0024 / image | $0.0114 / image | +375% |
| [Gemini 3.1 Flash Lite](https://uberllm.dev/models/google/gemini-3.1-flash-lite) | text | $0.0025 / $0.015 | $0.0725 / $0.435 | +2800% |

</details>


## 2026-11-16 (vs 2026-11-15)

**Official list price changes (7)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GLM-4.7](https://uberllm.dev/models/z-ai/glm-4.7) | text | $0.55 / $2.20 | $0.40 / $1.75 | in −27% / out −20% |
| [DeepSeek V4 Flash 0731](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731) | text | – / – | $0.06 / $0.18 |  |
| [Grok Imagine Text-to-Video](https://uberllm.dev/models/x-ai/grok-imagine-text-to-video) | video | $0.089 / sec | $0.0895 / sec | +1% |
| [PixVerse C1 Text-to-Video (Venice)](https://uberllm.dev/models/venice/pixverse-c1-t2v) | video | $0.07 / sec | $0.072 / sec | +3% |
| [NVIDIA: Nemotron 3.5 Super VL](https://uberllm.dev/models/nvidia/nemotron-3.5-super-vl) | text | $0.15 / $0.47 | $0.15 / $0.50 | in 0% / out +6% |
| [MoonshotAI: Kimi K3.1 Pro](https://uberllm.dev/models/moonshotai/kimi-k3.1-pro) | text | $2.00 / $10.00 | $2.30 / $11.50 | +15% |
| [Particle AI: Particle-1](https://uberllm.dev/models/particle-ai/particle-1) | text | $0.05 / $0.50 | $0.06 / $0.50 | in +20% / out 0% |

**New models (1)**

| Model | Category | Official price | UberLLM price |
|---|---|---|---|
| [Qwen3.5 122B A10B](https://uberllm.dev/models/qwen/e2ee-qwen3-5-122b-a10b) | text | – | $0.35 / $2.80 |

**No longer listed (21)**: `deepseek/deepseek-v4-flash:web`, `deepseek/deepseek-v4-pro:web`, `google/gemma-4-26b-a4b-it:web`, `google/gemma-4-31b-it:web`, `meta-llama/hermes-3-llama-3.1-405b:web`, `meta-llama/llama-3.2-3b-instruct:web`, `meta-llama/llama-3.3-70b-instruct:web`, `minimax/minimax-m2.5:web`, `mistralai/mistral-small-3.2-24b-instruct:web`, `moonshotai/kimi-k2.5:web`, `moonshotai/kimi-k2.6:web`, `moonshotai/kimi-k2.7-code:web`, `openai/gpt-oss-120b:web`, `qwen/qwen3-235b-a22b-2507:web`, `qwen/qwen3-next-80b-a3b-instruct:web`, `z-ai/glm-4.7-thinking`, `z-ai/glm-5.1-non-thinking`, `z-ai/glm-5.1-non-thinking:web`, `z-ai/glm-5.1:web`, `z-ai/glm-5.2:web`, `z-ai/glm-5:web`

<details><summary>UberLLM price moves of 10% or more (141)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Qwen3.5 Flash](https://uberllm.dev/models/qwen/qwen3.5-flash) | text | $0.096 / $0.384 | $0.01 / $0.04 | −90% |
| [MiniMax M2.7 Highspeed](https://uberllm.dev/models/minimax/minimax-m2.7-highspeed) | text | $0.576 / $2.30 | $0.078 / $0.312 | −86% |
| [Gemini 3.1 Pro](https://uberllm.dev/models/google/gemini-3.1-pro) | text | $1.40 / $8.40 | $0.2196 / $1.32 | −84% |
| [Gemini 3.7 Flash](https://uberllm.dev/models/google/gemini-3.7-flash) | text | $0.1425 / $0.7125 | $0.0225 / $0.1125 | −84% |
| [MoonshotAI: Kimi K3.1 Pro](https://uberllm.dev/models/moonshotai/kimi-k3.1-pro) | text | $0.36 / $1.80 | $0.05803 / $2.19 | in −84% / out +21% |
| [Qwen3.5 Plus](https://uberllm.dev/models/qwen/qwen3.5-plus) | text | $0.2496 / $1.50 | $0.065 / $0.39 | −74% |
| [Flux 2 Pro (Venice)](https://uberllm.dev/models/venice/flux-2-pro) | image | $0.0075 / image | $0.0024 / image | −68% |
| [Gemini 3 Flash Preview](https://uberllm.dev/models/google/gemini-3-flash-preview) | text | $0.04 / $0.24 | $0.015 / $0.09 | −62% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.01013 / $0.03375 | $0.00405 / $0.0135 | −60% |
| [Sakana: Fugu Ultra v2](https://uberllm.dev/models/sakana/fugu-ultra-v2) | text | $4.50 / $27.00 | $1.90 / $11.40 | −58% |
| [GLM 4.5](https://uberllm.dev/models/z-ai/glm-4.5) | text | $0.084 / $0.308 | $0.036 / $0.132 | −57% |
| [Whisper Large V3 (Venice)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.00348 / minute | $0.0015 / minute | −57% |
| [GPT-5.5 Pro](https://uberllm.dev/models/openai/gpt-5.5-pro) | text | $19.20 / $115.20 | $9.30 / $55.80 | −52% |
| [MiMo-V2.5](https://uberllm.dev/models/xiaomi/mimo-v2-5) | text | $0.316 / $1.58 | $0.156 / $0.78 | −51% |
| [Sakana: Fugu Max](https://uberllm.dev/models/sakana/fugu-max) | text | $1.80 / $5.40 | $0.94 / $2.82 | −48% |
| [Reflection: Beam 1.0 501B A23B](https://uberllm.dev/models/reflection/beam-1.0-501b-a23b) | text | $0.2625 / $1.05 | $0.168 / $0.56 | in −36% / out −47% |
| [Qwen 3.8 27B](https://uberllm.dev/models/qwen/qwen-3-8-27b) | text | $0.0165 / $0.2062 | $0.009 / $0.1125 | −45% |
| [GPT-5.4 Pro](https://uberllm.dev/models/openai/gpt-5.4-pro) | text | $14.10 / $84.60 | $7.80 / $46.80 | −45% |
| [Gemini 2.5 Pro](https://uberllm.dev/models/google/gemini-2.5-pro) | text | $0.4875 / $3.90 | $0.2875 / $2.30 | −41% |
| [Meta: Muse Spark 1.2 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.2-contributor) | text | $0.096 / $0.192 | $0.058 / $0.116 | −40% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | text | $1.24 / $3.72 | $0.82 / $2.46 | −34% |
| [Llama 3.3 70B Instruct](https://uberllm.dev/models/meta-llama/llama-3.3-70b-instruct) | text | $0.042 / $0.04704 | $0.028 / $0.04704 | in −33% / out 0% |
| [Qwen: Qwen3.8 Max Prime](https://uberllm.dev/models/qwen/qwen3.8-max-prime) | text | $3.60 / $10.80 | $2.44 / $7.32 | −32% |
| [Fireworks: Ember-1](https://uberllm.dev/models/fireworks/ember-1) | text | $1.79 / $8.93 | $1.23 / $6.15 | −31% |
| [Qwen3.8 Flash](https://uberllm.dev/models/qwen/qwen3.8-flash) | text | $0.0255 / $0.0799 | $0.018 / $0.0564 | −29% |
| [Meta: Muse Spark 1.1](https://uberllm.dev/models/meta-llama/muse-spark-1.1) | text | $0.8125 / $2.76 | $0.575 / $1.96 | −29% |
| [Moondream: Moondream 3.1](https://uberllm.dev/models/moondream/moondream3.1-9b-a2b) | text | $0.27 / $2.25 | $0.192 / $1.60 | −29% |
| [Gemini 3.8 Flash](https://uberllm.dev/models/google/gemini-3.8-flash) | text | $0.05775 / $0.2888 | $0.04125 / $0.2062 | −29% |
| [Qwen3 Coder Next](https://uberllm.dev/models/qwen/qwen3-coder-next) | text | $0.03 / $0.20 | $0.0216 / $0.144 | −28% |
| [Meta: Muse Spark 1.2](https://uberllm.dev/models/meta-llama/muse-spark-1.2) | text | $0.6375 / $2.17 | $0.475 / $1.61 | −25% |
| [NVIDIA Nemotron 3 Nano 30B](https://uberllm.dev/models/nvidia/nemotron-3-nano-30b-a3b) | text | $0.039 / $0.156 | $0.02925 / $0.117 | −25% |
| [Qwen 3 235B A22B Thinking 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.108 / $0.84 | $0.081 / $0.63 | −25% |
| [Whisper 1 (Venice, legacy alias)](https://uberllm.dev/models/venice/whisper-1) | transcription | $0.0048 / minute | $0.0036 / minute | −25% |
| [Qwen3 32B](https://uberllm.dev/models/qwen/qwen3-32b) | text | $0.02 / $0.07 | $0.0152 / $0.0532 | −24% |
| [Kimi K2 Thinking](https://uberllm.dev/models/moonshotai/kimi-k2-thinking) | text | $0.1497 / $0.6238 | $0.114 / $0.475 | −24% |
| [Aion 3.0 Mini](https://uberllm.dev/models/aion-labs/aion-3-0-mini) | text | $0.329 / $0.658 | $0.252 / $0.504 | −23% |
| [Sakana: Sakana Namazu](https://uberllm.dev/models/sakana/sakana-namazu) | text | $0.95 / $4.00 | $0.7315 / $3.08 | −23% |
| [GPT-5.4](https://uberllm.dev/models/openai/gpt-5.4) | text | $0.875 / $5.25 | $0.675 / $4.05 | −23% |
| [Qwen3 Coder 30B A3B Instruct](https://uberllm.dev/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.0175 / $0.07 | $0.0135 / $0.054 | −23% |
| [Grok 4.20 Beta](https://uberllm.dev/models/x-ai/grok-4.20-beta) | text | $0.6125 / $1.23 | $0.475 / $0.95 | −22% |
| [MiniMax M3 Preview](https://uberllm.dev/models/minimax/minimax-m3-preview) | text | $0.159 / $0.636 | $0.1234 / $0.4937 | −22% |
| [MiniMax M2.7](https://uberllm.dev/models/minimax/minimax-m2.7) | text | $0.084 / $0.336 | $0.0672 / $0.2688 | −20% |
| [GPT-6 Sol](https://uberllm.dev/models/openai/gpt-6-sol) | text | $0.40 / $2.00 | $0.32 / $1.60 | −20% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | text | $0.07 / $0.22 | $0.056 / $0.176 | −20% |
| [FLUX.2 Klein 4B](https://uberllm.dev/models/black-forest-labs/flux.2-klein-4b) | image | $0.00375 / megapixel | $0.003 / megapixel | −20% |
| [Seedream 4.5](https://uberllm.dev/models/bytedance/seedream-4.5) | image | $0.01 / image | $0.008 / image | −20% |
| [Pareto 26.9](https://uberllm.dev/models/unbiased/pareto-26.9) | text | $2.25 / $6.75 | $1.80 / $5.40 | −20% |
| [MiniMax M2](https://uberllm.dev/models/minimax/minimax-m2) | text | $0.06364 / $0.2546 | $0.051 / $0.204 | −20% |
| [DeepSeek V3.1](https://uberllm.dev/models/deepseek/deepseek-v3.1) | text | $0.07455 / $0.2833 | $0.06 / $0.228 | −20% |
| [Meta: Muse Spark Open](https://uberllm.dev/models/meta-llama/muse-spark-open) | text | $0.85 / $2.89 | $0.6875 / $2.34 | −19% |
| [xAI Speech to Text v1 (Venice)](https://uberllm.dev/models/venice/xai-stt-v1) | transcription | $0.001511 / minute | $0.001228 / minute | −19% |
| [GPT-6.1 Sol](https://uberllm.dev/models/openai/gpt-6.1-sol) | text | $0.44 / $2.20 | $0.36 / $1.80 | −18% |
| [Aion 3.0](https://uberllm.dev/models/aion-labs/aion-3-0) | text | $1.86 / $3.72 | $1.53 / $3.06 | −18% |
| [Grok 4.20 Multi-Agent Beta](https://uberllm.dev/models/x-ai/grok-4.20-multi-agent-beta) | text | $0.575 / $1.15 | $0.4745 / $0.949 | −17% |
| [Grok 4.5](https://uberllm.dev/models/x-ai/grok-4.5) | text | $1.18 / $3.54 | $0.98 / $2.94 | −17% |
| [Gemini 3.5 Flash](https://uberllm.dev/models/google/gemini-3.5-flash) | text | $0.09 / $0.54 | $0.075 / $0.45 | −17% |
| [Seed 2.1 Turbo](https://uberllm.dev/models/bytedance/seed-2-1-turbo) | text | $0.33 / $1.65 | $0.275 / $1.38 | −17% |
| [GPT-OSS 120B](https://uberllm.dev/models/openai/gpt-oss-120b) | text | $0.0133 / $0.057 | $0.0112 / $0.048 | −16% |
| [GPT-4o](https://uberllm.dev/models/openai/gpt-4o) | text | $0.525 / $2.10 | $0.45 / $1.80 | −14% |
| [Meta: Muse Spark 1.3 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.3-contributor) | text | $0.044 / $0.088 | $0.038 / $0.076 | −14% |
| [LiquidAI: LFM2.5-24B-A2B](https://uberllm.dev/models/liquid/lfm-2.5-24b-a2b) | text | $0.045 / $0.63 | $0.039 / $0.546 | −13% |
| [Meta: Muse Glimmer 30B](https://uberllm.dev/models/meta-llama/muse-glimmer-30b) | text | $0.27 / $1.08 | $0.237 / $0.948 | −12% |
| [Qwen3 VL 235B A22B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-instruct) | text | $0.0525 / $0.475 | $0.0462 / $0.418 | −12% |
| [GLM-4.7](https://uberllm.dev/models/z-ai/glm-4.7) | text | $0.209 / $0.836 | $0.184 / $0.805 | in −12% / out −4% |
| [GPT-5.6 Terra](https://uberllm.dev/models/openai/gpt-5.6-terra) | text | $0.34 / $2.04 | $0.30 / $1.80 | −12% |
| [Z.ai: GLM 5.3 FlashX](https://uberllm.dev/models/z-ai/glm-5.3-flashx) | text | $0.2516 / $0.85 | $0.222 / $0.75 | −12% |
| [Tencent: Hy4 preview](https://uberllm.dev/models/tencent/hy4-preview) | text | $0.5588 / $1.68 | $0.5004 / $1.50 | −10% |
| [Mistral Large](https://uberllm.dev/models/mistralai/mistral-large) | text | $0.58 / $1.74 | $0.64 / $1.92 | +10% |
| [Aion 3.5](https://uberllm.dev/models/aion-labs/aion-3-5) | text | $2.14 / $4.28 | $2.36 / $4.72 | +11% |
| [Aion 3.5 Mini](https://uberllm.dev/models/aion-labs/aion-3-5-mini) | text | $0.4988 / $0.9975 | $0.5513 / $1.10 | +11% |
| [Qwen 3 Coder 480b](https://uberllm.dev/models/qwen/qwen3-coder) | text | $0.07497 / $0.2499 | $0.084 / $0.28 | +12% |
| [GPT-6 Astra](https://uberllm.dev/models/openai/gpt-6-astra) | text | $0.80 / $4.00 | $0.90 / $4.50 | +12% |
| [Qwen3 VL 235B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-thinking) | text | $0.1176 / $1.06 | $0.1323 / $1.20 | +12% |
| [Gemma 4 E2B](https://uberllm.dev/models/google/gemma-4-e2b) | text | $0.0088 / $0.0176 | $0.01 / $0.02 | +14% |
| [Devstral 2 123B](https://uberllm.dev/models/mistralai/devstral-2-123b) | text | $0.052 / $0.26 | $0.06 / $0.30 | +15% |
| [GPT-5.6 Luna](https://uberllm.dev/models/openai/gpt-5.6-luna) | text | $0.038 / $0.228 | $0.044 / $0.264 | +16% |
| [Grok 4.3](https://uberllm.dev/models/x-ai/grok-4.3) | text | $0.3875 / $0.775 | $0.45 / $0.90 | +16% |
| [GPT 5 Nano](https://uberllm.dev/models/openai/gpt-5-nano) | text | $0.0185 / $0.148 | $0.0215 / $0.172 | +16% |
| [Kimi K2.5](https://uberllm.dev/models/moonshotai/kimi-k2.5) | text | $0.18 / $0.90 | $0.21 / $1.05 | +17% |
| [Particle AI: Particle-1](https://uberllm.dev/models/particle-ai/particle-1) | text | $0.045 / $0.45 | $0.0528 / $0.44 | in +17% / out −2% |
| [Qwen 2.5 7B](https://uberllm.dev/models/qwen/e2ee-qwen-2-5-7b-p) | text | $0.0295 / $0.0767 | $0.03476 / $0.09038 | +18% |
| [Longcat Distilled (image-to-video)](https://uberllm.dev/models/meituan/longcat-distilled-image-to-video) | video | $0.0099 / sec | $0.0117 / sec | +18% |
| [Qwen3.7 Max](https://uberllm.dev/models/qwen/qwen3.7-max) | text | $1.16 / $3.46 | $1.38 / $4.11 | +19% |
| [NVIDIA Nemotron 3 Ultra 550B](https://uberllm.dev/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.10 / $0.50 | $0.1187 / $0.5938 | +19% |
| [Claude Opus 5 (Fast)](https://uberllm.dev/models/anthropic/claude-opus-5-fast) | text | $5.80 / $29.00 | $6.90 / $34.50 | +19% |
| [Mistral Large 3](https://uberllm.dev/models/mistralai/mistral-large-3) | text | $0.105 / $0.315 | $0.125 / $0.375 | +19% |
| [Google: Gemini 4 Carbon](https://uberllm.dev/models/google/gemini-4-carbon) | text | $0.40 / $2.00 | $0.48 / $2.40 | +20% |
| [MiniMax M3](https://uberllm.dev/models/minimax/minimax-m3) | text | $0.045 / $0.18 | $0.054 / $0.216 | +20% |
| [Claude Opus 4.7 Fast](https://uberllm.dev/models/anthropic/claude-opus-4.7-fast) | text | $14.40 / $72.00 | $17.28 / $86.40 | +20% |
| [GPT OSS 20B](https://uberllm.dev/models/openai/e2ee-gpt-oss-20b-p) | text | $0.02 / $0.076 | $0.024 / $0.0912 | +20% |
| [GLM 5V Turbo](https://uberllm.dev/models/z-ai/glm-5v-turbo) | text | $0.72 / $2.40 | $0.876 / $2.92 | +22% |
| [Claude Fable 5.2](https://uberllm.dev/models/anthropic/claude-fable-5.2) | text | $2.56 / $12.80 | $3.20 / $16.00 | +25% |
| [Claude Haiku 4.5](https://uberllm.dev/models/anthropic/claude-haiku-4.5) | text | $0.53 / $2.65 | $0.67 / $3.35 | +26% |
| [Qwen 3.6 27B](https://uberllm.dev/models/qwen/qwen3.6-27b) | text | $0.096 / $0.96 | $0.1216 / $1.22 | +27% |
| [Qwen3.8 2.4T A95B](https://uberllm.dev/models/qwen/qwen3.8-2.4t-a95b) | text | $0.52 / $1.56 | $0.66 / $1.98 | +27% |
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | text | $0.0078 / $0.0338 | $0.0099 / $0.0429 | +27% |
| [MiniMax M2.5](https://uberllm.dev/models/minimax/minimax-m2.5) | text | $0.0297 / $0.1045 | $0.0378 / $0.133 | +27% |
| [GPT-5.6 Sol Pro](https://uberllm.dev/models/openai/gpt-5.6-sol-pro) | text | $2.16 / $10.80 | $2.76 / $13.80 | +28% |
| [Seedance 1.5 Pro (image-to-video)](https://uberllm.dev/models/bytedance/seedance-1-5-pro-image-to-video) | video | $0.0238 / sec | $0.0306 / sec | +29% |
| [GPT-6 Sol Pro](https://uberllm.dev/models/openai/gpt-6-sol-pro) | text | $1.40 / $7.00 | $1.80 / $9.00 | +29% |
| [OpenAI: GPT-6.1 Sol Pro](https://uberllm.dev/models/openai/gpt-6.1-sol-pro) | text | $1.40 / $7.00 | $1.80 / $9.00 | +29% |
| [OpenAI: GPT-6.1 Terra Pro](https://uberllm.dev/models/openai/gpt-6.1-terra-pro) | text | $0.70 / $3.50 | $0.90 / $4.50 | +29% |
| [Gemini 3.1 Flash TTS](https://uberllm.dev/models/google/tts-gemini-3-1-flash) | speech | $0.09375 / 1K chars | $0.1219 / 1K chars | +30% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.009 / sec | $0.0117 / sec | +30% |
| [Claude Opus 4.8](https://uberllm.dev/models/anthropic/claude-opus-4.8) | text | $1.05 / $5.25 | $1.40 / $7.00 | +33% |
| [Claude Sonnet 4.6](https://uberllm.dev/models/anthropic/claude-sonnet-4.6) | text | $0.84 / $4.20 | $1.14 / $5.70 | +36% |
| [Grok 4.7](https://uberllm.dev/models/x-ai/grok-4.7) | text | $0.54 / $1.62 | $0.74 / $2.22 | +37% |
| [ElevenLabs Scribe v2 (STT)](https://uberllm.dev/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.005812 / minute | $0.007977 / minute | +37% |
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.0144 / $0.176 | $0.0198 / $0.242 | +38% |
| [GLM-5 Turbo](https://uberllm.dev/models/z-ai/glm-5-turbo) | text | $0.444 / $1.48 | $0.636 / $2.12 | +43% |
| [GLM-5](https://uberllm.dev/models/z-ai/glm-5) | text | $0.23 / $0.736 | $0.33 / $1.06 | +43% |
| [GLM 5.2 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5-2-p) | text | $0.9975 / $3.28 | $1.44 / $4.71 | +44% |
| [Magistral Small 2509](https://uberllm.dev/models/mistralai/magistral-small-2509) | text | $0.065 / $0.195 | $0.095 / $0.285 | +46% |
| [GPT-6 Luna](https://uberllm.dev/models/openai/gpt-6-luna) | text | $0.032 / $0.16 | $0.047 / $0.235 | +47% |
| [Grok Imagine — Edit (Venice)](https://uberllm.dev/models/venice/grok-imagine-edit) | image | $0.012 / image | $0.018 / image | +50% |
| [Claude Opus 4.7](https://uberllm.dev/models/anthropic/claude-opus-4.7) | text | $1.10 / $5.50 | $1.65 / $8.25 | +50% |
| [Claude Sonnet 4.5](https://uberllm.dev/models/anthropic/claude-sonnet-4.5) | text | $0.96 / $4.80 | $1.44 / $7.20 | +50% |
| [Ministral 3 8B](https://uberllm.dev/models/mistralai/ministral-3-8b-instruct) | text | $0.0165 / $0.0165 | $0.0255 / $0.0255 | +55% |
| [Trinity Large Thinking](https://uberllm.dev/models/arcee-ai/trinity-large-thinking) | text | $0.216 / $0.72 | $0.3125 / $1.12 | in +45% / out +56% |
| [Gemini 3.5 Flash Lite](https://uberllm.dev/models/google/gemini-3-5-flash-lite) | text | $0.141 / $1.18 | $0.228 / $1.90 | +62% |
| [Claude Opus 5](https://uberllm.dev/models/anthropic/claude-opus-5) | text | $0.90 / $4.50 | $1.50 / $7.50 | +67% |
| [GPT-5.6 Terra Pro](https://uberllm.dev/models/openai/gpt-5.6-terra-pro) | text | $0.8198 / $4.92 | $1.40 / $8.40 | +71% |
| [DeepSeek V4 Pro 0813](https://uberllm.dev/models/deepseek/deepseek-v4-pro-0813) | text | $0.01776 / $0.7104 | $0.03108 / $1.24 | +75% |
| [Claude Sonnet 5](https://uberllm.dev/models/anthropic/claude-sonnet-5) | text | $0.42 / $2.10 | $0.74 / $3.70 | +76% |
| [Claude Fable 5.1](https://uberllm.dev/models/anthropic/claude-fable-5.1) | text | $2.20 / $11.00 | $3.90 / $19.50 | +77% |
| [Qwen: Qwen3.8 Max (0902)](https://uberllm.dev/models/qwen/qwen3.8-max-0902) | text | $0.10 / $0.30 | $0.18 / $0.54 | +80% |
| [Claude Opus 4.6 Fast](https://uberllm.dev/models/anthropic/claude-opus-4.6-fast) | text | $14.40 / $72.00 | $27.00 / $135.00 | +88% |
| [Claude Fable 5](https://uberllm.dev/models/anthropic/claude-fable-5) | text | $2.10 / $10.50 | $4.00 / $20.00 | +90% |
| [Gemma 4 31B](https://uberllm.dev/models/google/gemma-4-31b) | text | $0.0168 / $0.0504 | $0.0324 / $0.0972 | +93% |
| [DeepSeek V3.2](https://uberllm.dev/models/deepseek/deepseek-v3.2) | text | $0.0338 / $0.0494 | $0.06726 / $0.09831 | +99% |
| [Gemini 3.6 Flash](https://uberllm.dev/models/google/gemini-3-6-flash) | text | $0.2325 / $1.16 | $0.4725 / $2.36 | +103% |
| [Claude Opus 5.5](https://uberllm.dev/models/anthropic/claude-opus-5.5) | text | $0.48 / $2.40 | $1.00 / $5.00 | +108% |
| [Claude Sonnet 5.5](https://uberllm.dev/models/anthropic/claude-sonnet-5.5) | text | $0.48 / $2.40 | $1.06 / $5.30 | +121% |
| [Gemma 3 12B IT](https://uberllm.dev/models/google/gemma-3-12b-it) | text | $0.0115 / $0.0345 | $0.0275 / $0.0825 | +139% |
| [DeepSeek V4 Flash 0731](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731) | text | $0.007812 / $0.0468 | $0.0198 / $0.0594 | in +153% / out +27% |
| [Claude Opus 4.6](https://uberllm.dev/models/anthropic/claude-opus-4.6) | text | $0.65 / $3.25 | $1.65 / $8.25 | +154% |
| [GPT-4o Mini](https://uberllm.dev/models/openai/gpt-4o-mini) | text | $0.0315 / $0.126 | $0.0825 / $0.33 | +162% |
| [GPT-5.6 Luna Pro](https://uberllm.dev/models/openai/gpt-5.6-luna-pro) | text | $0.04995 / $0.2997 | $0.1339 / $0.8032 | +168% |
| [Qwen 3.8 Max](https://uberllm.dev/models/qwen/qwen-3-8-max) | text | $0.15 / $0.45 | $0.55 / $1.65 | +267% |
| [DeepSeek V4.1 Flash 1017](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.00342 / $0.045 | $0.0255 / $0.102 | in +646% / out +127% |
| [Gemma 3 4B IT](https://uberllm.dev/models/google/gemma-3-4b-it) | text | $0.0005 / $0.001 | $0.017 / $0.034 | +3300% |

</details>


## 2026-11-15 (vs 2026-11-14)

**Official list price changes (8)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [ElevenLabs Sound Effects v2 (Venice)](https://uberllm.dev/models/venice/elevenlabs-sound-effects-v2) | music | $0.02 / sec | $0.0023 / sec | −88% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.09 / $0.30 | $0.0675 / $0.225 | −25% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-multilingual-v2) | music | $0.12 / 1K chars | $0.115 / 1K chars | −4% |
| [ElevenLabs TTS v3 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-v3) | music | $0.12 / 1K chars | $0.115 / 1K chars | −4% |
| [MMAudio V2 Text-to-Audio (Venice)](https://uberllm.dev/models/venice/mmaudio-v2-text-to-audio) | music | – | $0.00092 / sec |  |
| [GLM 5.1 Non-thinking (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5.1-non-thinking:web) | text | – / – | $1.40 / $4.40 |  |
| [Kling V3 Standard Text-to-Video](https://uberllm.dev/models/kling/kling-v3-standard-text-to-video) | video | $0.139 / sec | $0.14 / sec | +1% |
| [Llama 3.2 3B](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct) | text | $0.05 / $0.33 | $0.0509 / $0.335 | +2% |

**New models (20)**

| Model | Category | Official price | UberLLM price |
|---|---|---|---|
| [Seedance 2.0 Enhanced (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-enhanced-reference-to-video) | video | $0.088 / sec | – |
| [Seedance 2.0 Mini Enhanced (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-enhanced-reference-to-video) | video | $0.044 / sec | – |
| [Seedance 2.5 Image-to-Video (US Private)](https://uberllm.dev/models/bytedance/venice-seedance-2-5-us-image-to-video-private) | video | $0.291 / sec | – |
| [Seedance 2.5 Reference-to-Video (US Private)](https://uberllm.dev/models/bytedance/venice-seedance-2-5-us-reference-to-video-private) | video | $0.2713 / sec | – |
| [Seedance 2.5 Text-to-Video (US Private)](https://uberllm.dev/models/bytedance/venice-seedance-2-5-us-text-to-video-private) | video | $0.291 / sec | – |
| [Ltx 2.19b Full (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-19b-full-image-to-video) | video | $0.088 / sec | – |
| [Ltx 2 Full (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-full-image-to-video) | video | $0.0667 / sec | – |
| [Wan 3.0 Image-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-image-to-video) | video | – | $0.26 / sec |
| [Wan 3.0 Prime Image-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-prime-image-to-video) | video | – | $0.364 / sec |
| [Wan 3.0 Prime Pro Image-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-prime-pro-image-to-video) | video | – | $0.3312 / sec |
| [Wan 3.0 Prime Pro Reference-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-prime-pro-reference-to-video) | video | – | $0.3312 / sec |
| [Wan 3.0 Prime Pro Text-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-prime-pro-text-to-video) | video | – | $0.3312 / sec |
| [Wan 3.0 Prime Reference-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-prime-reference-to-video) | video | – | $0.364 / sec |
| [Wan 3.0 Prime Text-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-prime-text-to-video) | video | – | $0.364 / sec |
| [Wan 3.0 Pro Image-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-pro-image-to-video) | video | – | $0.2366 / sec |
| [Wan 3.0 Pro Reference-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-pro-reference-to-video) | video | – | $0.2366 / sec |
| [Wan 3.0 Pro Text-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-pro-text-to-video) | video | – | $0.2366 / sec |
| [Wan 3.0 Reference-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-reference-to-video) | video | – | $0.26 / sec |
| [Wan 3.0 Text-to-Video](https://uberllm.dev/models/qwen/venice-wan-3-0-text-to-video) | video | – | $0.26 / sec |
| [GLM 5.1 Non-thinking](https://uberllm.dev/models/z-ai/glm-5.1-non-thinking) | text | $1.40 / $4.40 | $1.00 / $3.35 |

**No longer listed (1)**: `z-ai/e2ee-glm-4.7`

<details><summary>UberLLM price moves of 10% or more (157)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MMAudio V2 Text-to-Audio (Venice)](https://uberllm.dev/models/venice/mmaudio-v2-text-to-audio) | music | $0.0065 / sec | $0.000736 / sec | −89% |
| [ElevenLabs Sound Effects v2 (Venice)](https://uberllm.dev/models/venice/elevenlabs-sound-effects-v2) | music | $0.014 / sec | $0.00184 / sec | −87% |
| [DeepSeek V4.1 Flash 1017](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.021 / $0.084 | $0.00342 / $0.045 | in −84% / out −46% |
| [DeepSeek V4.1 Flash](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash) | text | $0.108 / $0.432 | $0.02332 / $0.09329 | −78% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | text | $0.224 / $0.704 | $0.07 / $0.22 | −69% |
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | text | $0.0243 / $0.1053 | $0.0078 / $0.0338 | −68% |
| [GPT-5.6 Luna Pro](https://uberllm.dev/models/openai/gpt-5.6-luna-pro) | text | $0.132 / $0.792 | $0.04995 / $0.2997 | −62% |
| [Seedream 4.5](https://uberllm.dev/models/bytedance/seedream-4.5) | image | $0.024 / image | $0.01 / image | −58% |
| [Ministral 3 8B](https://uberllm.dev/models/mistralai/ministral-3-8b-instruct) | text | $0.039 / $0.039 | $0.0165 / $0.0165 | −58% |
| [Claude Opus 5.5](https://uberllm.dev/models/anthropic/claude-opus-5.5) | text | $1.12 / $5.60 | $0.48 / $2.40 | −57% |
| [DeepSeek V4 Flash 0731](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731) | text | $0.01823 / $0.1092 | $0.007812 / $0.0468 | −57% |
| [Flux 2 Max (Venice)](https://uberllm.dev/models/venice/flux-2-max) | image | $0.0522 / image | $0.0225 / image | −57% |
| [NVIDIA Nemotron 3 Super 120B](https://uberllm.dev/models/nvidia/nemotron-3-super-120b) | text | $0.03975 / $0.212 | $0.018 / $0.096 | −55% |
| [DeepSeek V3.2](https://uberllm.dev/models/deepseek/deepseek-v3.2) | text | $0.06726 / $0.09831 | $0.0338 / $0.0494 | −50% |
| [GPT-5.5](https://uberllm.dev/models/openai/gpt-5.5) | text | $2.60 / $15.60 | $1.35 / $8.10 | −48% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.0189 / $0.063 | $0.01013 / $0.03375 | −46% |
| [Claude Fable 5](https://uberllm.dev/models/anthropic/claude-fable-5) | text | $3.90 / $19.50 | $2.10 / $10.50 | −46% |
| [Claude Opus 5](https://uberllm.dev/models/anthropic/claude-opus-5) | text | $1.65 / $8.25 | $0.90 / $4.50 | −45% |
| [Claude Opus 4.6](https://uberllm.dev/models/anthropic/claude-opus-4.6) | text | $1.15 / $5.75 | $0.65 / $3.25 | −43% |
| [GPT-6 Astra](https://uberllm.dev/models/openai/gpt-6-astra) | text | $1.40 / $7.00 | $0.80 / $4.00 | −43% |
| [GPT-5.3 Codex](https://uberllm.dev/models/openai/gpt-5.3-codex) | text | $0.735 / $5.88 | $0.4375 / $3.50 | −40% |
| [GPT-5.6 Terra Pro](https://uberllm.dev/models/openai/gpt-5.6-terra-pro) | text | $1.32 / $7.92 | $0.8198 / $4.92 | −38% |
| [GPT-5.4 Pro](https://uberllm.dev/models/openai/gpt-5.4-pro) | text | $22.50 / $135.00 | $14.10 / $84.60 | −37% |
| [GPT-5.6 Sol](https://uberllm.dev/models/openai/gpt-5.6-sol) | text | $1.64 / $8.20 | $1.04 / $5.20 | −37% |
| [Claude Fable 5.1](https://uberllm.dev/models/anthropic/claude-fable-5.1) | text | $3.30 / $16.50 | $2.20 / $11.00 | −33% |
| [Claude Sonnet 4.5](https://uberllm.dev/models/anthropic/claude-sonnet-4.5) | text | $1.44 / $7.20 | $0.96 / $4.80 | −33% |
| [Google: Gemini 4 Carbon](https://uberllm.dev/models/google/gemini-4-carbon) | text | $0.60 / $3.00 | $0.40 / $2.00 | −33% |
| [MiniMax M2.7](https://uberllm.dev/models/minimax/minimax-m2.7) | text | $0.126 / $0.504 | $0.084 / $0.336 | −33% |
| [GPT-5.5 Pro](https://uberllm.dev/models/openai/gpt-5.5-pro) | text | $27.60 / $165.60 | $19.20 / $115.20 | −30% |
| [Gemma 3 12B IT](https://uberllm.dev/models/google/gemma-3-12b-it) | text | $0.0165 / $0.0495 | $0.0115 / $0.0345 | −30% |
| [Claude Sonnet 4.6](https://uberllm.dev/models/anthropic/claude-sonnet-4.6) | text | $1.20 / $6.00 | $0.84 / $4.20 | −30% |
| [GPT-5.4](https://uberllm.dev/models/openai/gpt-5.4) | text | $1.25 / $7.50 | $0.875 / $5.25 | −30% |
| [Google: Gemini 4 Hydrogen](https://uberllm.dev/models/google/gemini-4-hydrogen) | text | $0.72 / $3.60 | $0.51 / $2.55 | −29% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.0126 / sec | $0.009 / sec | −29% |
| [GLM-4.6](https://uberllm.dev/models/z-ai/glm-4.6) | text | $0.1548 / $0.63 | $0.1118 / $0.455 | −28% |
| [GPT-5.6 Sol Pro](https://uberllm.dev/models/openai/gpt-5.6-sol-pro) | text | $2.96 / $14.80 | $2.16 / $10.80 | −27% |
| [NVIDIA Nemotron Nano 9B v2](https://uberllm.dev/models/nvidia/nemotron-nano-9b-v2) | text | $0.009 / $0.0345 | $0.0066 / $0.0253 | −27% |
| [Gemini 3.6 Flash](https://uberllm.dev/models/google/gemini-3-6-flash) | text | $0.315 / $1.57 | $0.2325 / $1.16 | −26% |
| [GPT 5 Nano](https://uberllm.dev/models/openai/gpt-5-nano) | text | $0.02499 / $0.20 | $0.0185 / $0.148 | −26% |
| [GLM 4.7 Flash](https://uberllm.dev/models/z-ai/glm-4.7-flash) | text | $0.01633 / $0.108 | $0.0121 / $0.08 | −26% |
| [GPT-6 Luna](https://uberllm.dev/models/openai/gpt-6-luna) | text | $0.042 / $0.21 | $0.032 / $0.16 | −24% |
| [Meta: Muse Wonder](https://uberllm.dev/models/meta-llama/muse-wonder) | text | $2.40 / $12.00 | $1.84 / $9.20 | −23% |
| [Qwen3 VL 30B A3B](https://uberllm.dev/models/qwen/qwen3-vl-30b-a3b-thinking) | text | $0.1825 / $0.657 | $0.14 / $0.504 | −23% |
| [Seedance 1.5 Pro (image-to-video)](https://uberllm.dev/models/bytedance/seedance-1-5-pro-image-to-video) | video | $0.0306 / sec | $0.0238 / sec | −22% |
| [Claude Fable 5.2](https://uberllm.dev/models/anthropic/claude-fable-5.2) | text | $3.28 / $16.40 | $2.56 / $12.80 | −22% |
| [Thinking Machines: Inkling](https://uberllm.dev/models/thinking-machines/inkling) | text | $0.37 / $1.50 | $0.29 / $1.17 | −22% |
| [Grok Imagine Pro (Venice)](https://uberllm.dev/models/venice/grok-imagine-pro) | image | $0.049 / image | $0.0385 / image | −21% |
| [Meta: Muse Spark 1.1](https://uberllm.dev/models/meta-llama/muse-spark-1.1) | text | $1.02 / $3.48 | $0.8125 / $2.76 | −21% |
| [Claude Opus 4.5](https://uberllm.dev/models/anthropic/claude-opus-4.5) | text | $1.95 / $9.75 | $1.55 / $7.75 | −21% |
| [Kimi K3 Fast](https://uberllm.dev/models/moonshotai/kimi-k3-fast-api) | text | $3.10 / $15.53 | $2.48 / $12.38 | −20% |
| [Grok Imagine — Edit (Venice)](https://uberllm.dev/models/venice/grok-imagine-edit) | image | $0.015 / image | $0.012 / image | −20% |
| [GPT-5.6 Terra](https://uberllm.dev/models/openai/gpt-5.6-terra) | text | $0.42 / $2.52 | $0.34 / $2.04 | −19% |
| [Aion 3.0 Mini](https://uberllm.dev/models/aion-labs/aion-3-0-mini) | text | $0.406 / $0.812 | $0.329 / $0.658 | −19% |
| [OpenAI: GPT-6.1 Terra Pro](https://uberllm.dev/models/openai/gpt-6.1-terra-pro) | text | $0.86 / $4.30 | $0.70 / $3.50 | −19% |
| [MiniMax M2.5 (Morpheus Web)](https://uberllm.dev/models/minimax/minimax-m2.5:web) | text | $0.2278 / $0.7973 | $0.187 / $0.6545 | −18% |
| [Kimi K2.5 (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.5:web) | text | $0.3752 / $2.35 | $0.308 / $1.93 | −18% |
| [Kimi K2.6 (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.6:web) | text | $0.5695 / $3.12 | $0.4675 / $2.56 | −18% |
| [GLM 5.1 Non-thinking (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5.1-non-thinking:web) | text | $1.00 / $3.35 | $0.825 / $2.75 | −18% |
| [DeepSeek V4 Flash (Morpheus Web)](https://uberllm.dev/models/deepseek/deepseek-v4-flash:web) | text | $0.1139 / $0.2345 | $0.0935 / $0.1925 | −18% |
| [DeepSeek V4 Pro (Morpheus Web)](https://uberllm.dev/models/deepseek/deepseek-v4-pro:web) | text | $1.16 / $2.54 | $0.9515 / $2.09 | −18% |
| [Gemma 4 31B IT (Morpheus Web)](https://uberllm.dev/models/google/gemma-4-31b-it:web) | text | $0.1172 / $0.335 | $0.09625 / $0.275 | −18% |
| [Llama 3.2 3B (Morpheus Web)](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct:web) | text | $0.1005 / $0.402 | $0.0825 / $0.33 | −18% |
| [Kimi K2.7 Code (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.7-code:web) | text | $0.4556 / $2.28 | $0.374 / $1.88 | −18% |
| [GLM 5 (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5:web) | text | $0.737 / $2.78 | $0.605 / $2.28 | −18% |
| [ElevenLabs TTS v3 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-v3) | music | $0.084 / 1K chars | $0.069 / 1K chars | −18% |
| [GPT-6 Sol Pro](https://uberllm.dev/models/openai/gpt-6-sol-pro) | text | $1.70 / $8.50 | $1.40 / $7.00 | −18% |
| [OpenAI: GPT-6.1 Sol Pro](https://uberllm.dev/models/openai/gpt-6.1-sol-pro) | text | $1.70 / $8.50 | $1.40 / $7.00 | −18% |
| [Claude Sonnet 5.5](https://uberllm.dev/models/anthropic/claude-sonnet-5.5) | text | $0.58 / $2.90 | $0.48 / $2.40 | −17% |
| [Llama 3.2 3B](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct) | text | $0.0305 / $0.2013 | $0.02545 / $0.1675 | −17% |
| [Claude Haiku 5.5](https://uberllm.dev/models/anthropic/claude-haiku-5.5) | text | $0.048 / $0.24 | $0.04 / $0.20 | −17% |
| [Grok 4.3](https://uberllm.dev/models/x-ai/grok-4.3) | text | $0.4625 / $0.925 | $0.3875 / $0.775 | −16% |
| [Fireworks: Ember-1](https://uberllm.dev/models/fireworks/ember-1) | text | $2.13 / $10.65 | $1.79 / $8.93 | −16% |
| [LTX 2 v2.3 Fast Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.04667 / sec | $0.04 / sec | −14% |
| [Inworld 1.5 Max TTS](https://uberllm.dev/models/inworld/tts-inworld-1-5-max) | speech | $0.00875 / 1K chars | $0.0075 / 1K chars | −14% |
| [LongCat Text-to-Video](https://uberllm.dev/models/meituan/longcat-text-to-video) | video | $0.035 / sec | $0.03 / sec | −14% |
| [Chatterbox HD TTS](https://uberllm.dev/models/resemble-ai/tts-chatterbox-hd) | speech | $0.035 / 1K chars | $0.03 / 1K chars | −14% |
| [Qwen 3.8 Max](https://uberllm.dev/models/qwen/qwen-3-8-max) | text | $0.175 / $0.525 | $0.15 / $0.45 | −14% |
| [Hunyuan Image 3.0 (Venice)](https://uberllm.dev/models/venice/hunyuan-image-v3) | image | $0.063 / image | $0.054 / image | −14% |
| [Venice TTS 1 (legacy alias)](https://uberllm.dev/models/venice/tts-1) | speech | $0.00245 / 1K chars | $0.0021 / 1K chars | −14% |
| [Vidu Q3 (image-to-video)](https://uberllm.dev/models/vidu/vidu-q3-image-to-video) | video | $0.063 / sec | $0.054 / sec | −14% |
| [Wan 2.5 Preview (image-to-video)](https://uberllm.dev/models/wan/wan-2-5-preview-image-to-video) | video | $0.0392 / sec | $0.0336 / sec | −14% |
| [Orpheus TTS](https://uberllm.dev/models/canopy-labs/tts-orpheus) | speech | $0.04375 / 1K chars | $0.0375 / 1K chars | −14% |
| [Kling V3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-standard-image-to-video) | video | $0.098 / sec | $0.084 / sec | −14% |
| [Vidu Q3 Text-to-Video](https://uberllm.dev/models/vidu/vidu-q3-text-to-video) | video | $0.1353 / sec | $0.116 / sec | −14% |
| [LTX 2 v2.3 Full Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.06183 / sec | $0.053 / sec | −14% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://uberllm.dev/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.3212 / $0.9636 | $0.2772 / $0.8316 | −14% |
| [Gemini 3.1 Pro Preview](https://uberllm.dev/models/google/gemini-3.1-pro-preview) | text | $0.30 / $1.80 | $0.26 / $1.56 | −13% |
| [GPT-5 Image Mini](https://uberllm.dev/models/openai/gpt-5-image-mini) | image | $2.48 / $1.98 | $2.15 / $1.72 | −13% |
| [Qwen 3.7 Plus](https://uberllm.dev/models/qwen/qwen3.7-plus) | text | $0.27 / $1.08 | $0.235 / $0.94 | −13% |
| [Grok 4.7](https://uberllm.dev/models/x-ai/grok-4.7) | text | $0.62 / $1.86 | $0.54 / $1.62 | −13% |
| [Claude Sonnet 5](https://uberllm.dev/models/anthropic/claude-sonnet-5) | text | $0.48 / $2.40 | $0.42 / $2.10 | −12% |
| [NVIDIA Nemotron 3 Ultra 550B](https://uberllm.dev/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.1125 / $0.5625 | $0.10 / $0.50 | −11% |
| [DeepSeek V4 Flash 0731 Fast](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731-fast) | text | $0.196 / $0.392 | $0.175 / $0.35 | −11% |
| [Qwen 3.6 35B A3B (E2EE)](https://uberllm.dev/models/qwen/e2ee-qwen3-6-35b-a3b) | text | $0.1074 / $0.6962 | $0.09646 / $0.6254 | −10% |
| [Claude Opus 4.7](https://uberllm.dev/models/anthropic/claude-opus-4.7) | text | $1.00 / $5.00 | $1.10 / $5.50 | +10% |
| [GPT-4o Mini](https://uberllm.dev/models/openai/gpt-4o-mini) | text | $0.0285 / $0.114 | $0.0315 / $0.126 | +11% |
| [Gemini 3.5 Flash Lite](https://uberllm.dev/models/google/gemini-3-5-flash-lite) | text | $0.126 / $1.05 | $0.141 / $1.18 | +12% |
| [MiMo-V2.6-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro) | text | $0.2175 / $0.435 | $0.2436 / $0.4872 | +12% |
| [Particle AI: Particle-1](https://uberllm.dev/models/particle-ai/particle-1) | text | $0.0395 / $0.395 | $0.045 / $0.45 | +14% |
| [inclusionAI: Ling 3.1 Flash](https://uberllm.dev/models/inclusionai/ling-3.1-flash) | text | $0.03825 / $0.1148 | $0.04365 / $0.131 | +14% |
| [DeepSeek V4 Pro](https://uberllm.dev/models/deepseek/deepseek-v4-pro) | text | $0.063 / $0.105 | $0.072 / $0.12 | +14% |
| [Sakana: Sakana Namazu](https://uberllm.dev/models/sakana/sakana-namazu) | text | $0.8265 / $3.48 | $0.95 / $4.00 | +15% |
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | text | $0.12 / $0.70 | $0.138 / $0.805 | +15% |
| [Hermes 3 Llama 3.1 405b](https://uberllm.dev/models/nousresearch/hermes-3-llama-3.1-405b) | text | $0.85 / $2.32 | $0.98 / $2.67 | +15% |
| [MiniMax M3](https://uberllm.dev/models/minimax/minimax-m3) | text | $0.039 / $0.156 | $0.045 / $0.18 | +15% |
| [Sakana: Fugu Ultra v2](https://uberllm.dev/models/sakana/fugu-ultra-v2) | text | $3.90 / $23.40 | $4.50 / $27.00 | +15% |
| [ElevenLabs Scribe v2 (STT)](https://uberllm.dev/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.00501 / minute | $0.005812 / minute | +16% |
| [Gemma 4 31B IT](https://uberllm.dev/models/google/gemma-4-31b-it) | text | $0.0564 / $0.1692 | $0.066 / $0.198 | +17% |
| [OpenAI: GPT-6.1 Terra](https://uberllm.dev/models/openai/gpt-6.1-terra) | text | $0.32 / $1.60 | $0.38 / $1.90 | +19% |
| [MiMo-V2.6-Flash](https://uberllm.dev/models/xiaomi/mimo-v2.6-flash) | text | $0.0826 / $0.1652 | $0.0994 / $0.1988 | +20% |
| [JEV 1.14 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.14) | other | $0.03108 / $0 | $0.0378 / $0 | in +22% / out – |
| [Google: Gemini 4 Argon](https://uberllm.dev/models/google/gemini-4-argon) | text | $0.18 / $0.90 | $0.22 / $1.10 | +22% |
| [Qwen: Qwen3.8 Max (0902)](https://uberllm.dev/models/qwen/qwen3.8-max-0902) | text | $0.08 / $0.24 | $0.10 / $0.30 | +25% |
| [Pareto 26.9](https://uberllm.dev/models/unbiased/pareto-26.9) | text | $1.80 / $5.40 | $2.25 / $6.75 | +25% |
| [Elorian: Glimpse](https://uberllm.dev/models/elorian/glimpse) | text | $0.426 / $2.13 | $0.54 / $2.70 | +27% |
| [Qwen: Qwen3.8 Max Prime](https://uberllm.dev/models/qwen/qwen3.8-max-prime) | text | $2.84 / $8.52 | $3.60 / $10.80 | +27% |
| [Happyhorse 1.0 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-image-to-video) | video | $0.08432 / sec | $0.1073 / sec | +27% |
| [Luma Uni 1 (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-edit) | image | $0.033 / image | $0.042 / image | +27% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.0495 / sec | $0.063 / sec | +27% |
| [Longcat (image-to-video)](https://uberllm.dev/models/meituan/longcat-image-to-video) | video | $0.0275 / sec | $0.035 / sec | +27% |
| [Stable Diffusion XL (Venice, legacy)](https://uberllm.dev/models/venice/sdxl) | image | $0.0055 / image | $0.007 / image | +27% |
| [JEV 1.13 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.13) | other | $0.02982 / $0 | $0.03822 / $0 | in +28% / out – |
| [LiquidAI: LFM2.5-24B-A2B](https://uberllm.dev/models/liquid/lfm-2.5-24b-a2b) | text | $0.035 / $0.49 | $0.045 / $0.63 | +29% |
| [Moondream: Moondream 3 Preview](https://uberllm.dev/models/moondream/moondream3-preview) | text | $0.21 / $1.75 | $0.27 / $2.25 | +29% |
| [Moondream: Moondream 3.1](https://uberllm.dev/models/moondream/moondream3.1-9b-a2b) | text | $0.21 / $1.75 | $0.27 / $2.25 | +29% |
| [Sakana: Fugu Max](https://uberllm.dev/models/sakana/fugu-max) | text | $1.40 / $4.20 | $1.80 / $5.40 | +29% |
| [Tencent HY3](https://uberllm.dev/models/tencent/hy3) | text | $0.0924 / $0.3696 | $0.1188 / $0.4752 | +29% |
| [MiMo-V2.6-Pro-UltraSpeed](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro-ultraspeed) | text | $3.04 / $6.09 | $3.92 / $7.83 | +29% |
| [Z.ai: GLM 5.3 FlashX Legal](https://uberllm.dev/models/z-ai/glm-5.3-flashx-legal) | text | $0.259 / $0.875 | $0.333 / $1.12 | +29% |
| [Qwen3 VL 235B A22B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-instruct) | text | $0.0399 / $0.361 | $0.0525 / $0.475 | +32% |
| [Whisper Large V3 (STT)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0036 / minute | $0.0048 / minute | +33% |
| [Qwen: Qwen3.8 Omni Flash](https://uberllm.dev/models/qwen/qwen3.8-omni-flash) | text | $0.0135 / $0.0423 | $0.018 / $0.0564 | +33% |
| [Tencent: Hy4](https://uberllm.dev/models/tencent/hy4) | text | $0.2627 / $0.7878 | $0.3544 / $1.06 | +35% |
| [Kokoro Text to Speech (Venice)](https://uberllm.dev/models/venice/kokoro-tts) | speech | $0.00175 / 1K chars | $0.00245 / 1K chars | +40% |
| [Reflection: Beam 1.0 501B A23B](https://uberllm.dev/models/reflection/beam-1.0-501b-a23b) | text | $0.21 / $0.70 | $0.2625 / $1.05 | in +25% / out +50% |
| [MiniMax M2.5](https://uberllm.dev/models/minimax/minimax-m2.5) | text | $0.0189 / $0.0665 | $0.0297 / $0.1045 | +57% |
| [Qwen 3 235B A22B Instruct 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-2507) | text | $0.0588 / $0.315 | $0.098 / $0.525 | +67% |
| [xAI Speech to Text v1 (Venice)](https://uberllm.dev/models/venice/xai-stt-v1) | transcription | $0.00085 / minute | $0.001511 / minute | +78% |
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.0081 / $0.099 | $0.0144 / $0.176 | +78% |
| [MiniMax M2](https://uberllm.dev/models/minimax/minimax-m2) | text | $0.033 / $0.132 | $0.06364 / $0.2546 | +93% |
| [Qwen: Qwen3.7 Flash](https://uberllm.dev/models/qwen/qwen3.7-flash) | text | $0.0102 / $0.0442 | $0.0198 / $0.0858 | +94% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.0165 / $0.066 | $0.033 / $0.132 | +100% |
| [GLM 5.3](https://uberllm.dev/models/z-ai/glm-5.3) | text | $0.00336 / $0.144 | $0.00672 / $0.288 | +100% |
| [Ministral 14B 3.0](https://uberllm.dev/models/mistralai/ministral-3-14b-instruct) | text | $0.026 / $0.026 | $0.054 / $0.054 | +108% |
| [Qwen3 32B](https://uberllm.dev/models/qwen/qwen3-32b) | text | $0.0096 / $0.0336 | $0.02 / $0.07 | +108% |
| [Whisper Large V3 (Venice)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0015 / minute | $0.00348 / minute | +132% |
| [Z.ai: GLM 5.3 Prime](https://uberllm.dev/models/z-ai/glm-5.3-prime) | text | $0.868 / $2.73 | $2.27 / $7.13 | +161% |
| [GLM 5.3 Flash](https://uberllm.dev/models/z-ai/glm-5.3-flash) | text | $0.002793 / $0.005488 | $0.007581 / $0.0149 | +171% |
| [Kimi K2 Thinking](https://uberllm.dev/models/moonshotai/kimi-k2-thinking) | text | $0.054 / $0.225 | $0.1497 / $0.6238 | +177% |
| [Mistral Large](https://uberllm.dev/models/mistralai/mistral-large) | text | $0.18 / $0.54 | $0.58 / $1.74 | +222% |
| [GLM-5.2](https://uberllm.dev/models/z-ai/glm-5.2) | text | $0.00052 / $0.3269 | $0.00217 / $1.36 | +317% |
| [Magistral Small 2509](https://uberllm.dev/models/mistralai/magistral-small-2509) | text | $0.01 / $0.03 | $0.065 / $0.195 | +550% |
| [Palmyra Vision 7B](https://uberllm.dev/models/writer/palmyra-vision-7b) | text | $0.0045 / $0.018 | $0.03 / $0.12 | +567% |
| [Ministral 3B](https://uberllm.dev/models/mistralai/ministral-3-3b-instruct) | text | $0.002 / $0.002 | $0.025 / $0.025 | +1150% |
| [GPT OSS Safeguard 120B](https://uberllm.dev/models/openai/gpt-oss-safeguard-120b) | text | $0.003 / $0.012 | $0.0375 / $0.15 | +1150% |
| [Devstral 2 123B](https://uberllm.dev/models/mistralai/devstral-2-123b) | text | $0.004 / $0.02 | $0.052 / $0.26 | +1200% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://uberllm.dev/models/nvidia/nemotron-nano-12b-v2) | text | $0.004 / $0.012 | $0.068 / $0.204 | +1600% |

</details>


## 2026-11-14 (vs 2026-11-13)

**Official list price changes (16)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [PixVerse C1 Text-to-Video (Venice)](https://uberllm.dev/models/venice/pixverse-c1-t2v) | video | $0.07133 / sec | $0.07 / sec | −2% |
| [Flux 3 (image-to-image)](https://uberllm.dev/models/black-forest-labs/flux-3-image-edit) | image | – | $0.12 / image |  |
| [Seedream V5 Pro (image-to-image)](https://uberllm.dev/models/bytedance/seedream-v5-pro-edit) | image | – | $0.06 / image |  |
| [Seedream V5 Pro (Venice)](https://uberllm.dev/models/bytedance/venice-seedream-v5-pro) | image | – | $0.06 / image |  |
| [Nano Banana 2.1 (image-to-image)](https://uberllm.dev/models/google/nano-banana-2-1-edit) | image | – | $0.10 / image |  |
| [Nano Banana 2.1 (Venice)](https://uberllm.dev/models/google/venice-nano-banana-2-1) | image | – | $0.10 / image |  |
| [Nano Banana 2 Lite (Venice)](https://uberllm.dev/models/google/venice-nano-banana-2-lite) | image | – | $0.06 / image |  |
| [MoonshotAI: Kimi K3.1 Pro](https://uberllm.dev/models/moonshotai/kimi-k3.1-pro) | text | – / – | $2.00 / $10.00 |  |
| [GPT Image 2.5 Flare (image-to-image)](https://uberllm.dev/models/openai/gpt-image-2-5-flare-edit) | image | – | $0.08 / image |  |
| [GPT Image 2.5 Sunburst (image-to-image)](https://uberllm.dev/models/openai/gpt-image-2-5-sunburst-edit) | image | – | $0.08 / image |  |
| [GPT Image 2.5 Sunburst (Venice)](https://uberllm.dev/models/openai/venice-gpt-image-2-5-sunburst) | image | – | $0.07 / image |  |
| [Qwen Image 3 (Venice)](https://uberllm.dev/models/venice/qwen-image-3) | image | – | $0.04 / image |  |
| [Qwen Image 3 Pro (Venice)](https://uberllm.dev/models/venice/qwen-image-3-pro) | image | – | $0.05 / image |  |
| [Grok Imagine 2.0 (image-to-image)](https://uberllm.dev/models/x-ai/grok-imagine-image-2-0-edit) | image | – | $0.0815 / image |  |
| [Kling V3 Standard Text-to-Video](https://uberllm.dev/models/kling/kling-v3-standard-text-to-video) | video | $0.138 / sec | $0.139 / sec | +1% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.0765 / $0.255 | $0.09 / $0.30 | +18% |

**New models (15)**

| Model | Category | Official price | UberLLM price |
|---|---|---|---|
| [Seedance 2.5 Image-to-Video](https://uberllm.dev/models/bytedance/venice-seedance-2-5-image-to-video-basic) | video | – | $0.14 / sec |
| [Seedance 2.5 Reference-to-Video](https://uberllm.dev/models/bytedance/venice-seedance-2-5-reference-to-video-basic) | video | – | $0.14 / sec |
| [Seedance 2.5 Text-to-Video](https://uberllm.dev/models/bytedance/venice-seedance-2-5-text-to-video-basic) | video | – | $0.14 / sec |
| [DeepSeek V4 Pro (Morpheus Web)](https://uberllm.dev/models/deepseek/deepseek-v4-pro:web) | text | $1.32 / $3.96 | $1.16 / $2.54 |
| [Gemma 4 26B A4B IT (Morpheus Web)](https://uberllm.dev/models/google/gemma-4-26b-a4b-it:web) | text | – | $0.1089 / $0.335 |
| [Gemma 4 31B IT (Morpheus Web)](https://uberllm.dev/models/google/gemma-4-31b-it:web) | text | $0.12 / $0.36 | $0.1172 / $0.335 |
| [Hermes 3 Llama 3.1 405b (Morpheus Web)](https://uberllm.dev/models/meta-llama/hermes-3-llama-3.1-405b:web) | text | – | $0.737 / $2.01 |
| [MiniMax M2.5 (Morpheus Web)](https://uberllm.dev/models/minimax/minimax-m2.5:web) | text | $0.27 / $0.95 | $0.2278 / $0.7973 |
| [Pixverse C1 (reference-to-video)](https://uberllm.dev/models/pixverse/pixverse-c1-reference-to-video) | video | $0.0433 / sec | $0.03031 / sec |
| [Qwen 3 Next 80b (Morpheus Web)](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct:web) | text | – | $0.2345 / $1.27 |
| [GLM 4.7 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-4.7) | text | – | $2.20 / $8.30 |
| [GLM 5.1 Non-thinking (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5.1-non-thinking:web) | text | – | $1.00 / $3.35 |
| [GLM 5.1 (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5.1:web) | text | $1.40 / $4.40 | $1.17 / $3.69 |
| [GLM 5.2 (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5.2:web) | text | $1.40 / $4.40 | $0.804 / $2.75 |
| [GLM 5 (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5:web) | text | $1.00 / $3.20 | $0.737 / $2.78 |

<details><summary>UberLLM price moves of 10% or more (213)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Devstral 2 123B](https://uberllm.dev/models/mistralai/devstral-2-123b) | text | $0.06 / $0.30 | $0.004 / $0.02 | −93% |
| [GPT Image 2 — Edit (Venice)](https://uberllm.dev/models/venice/gpt-image-2-edit) | image | $0.342 / image | $0.03 / image | −91% |
| [GPT OSS Safeguard 120B](https://uberllm.dev/models/openai/gpt-oss-safeguard-120b) | text | $0.0285 / $0.114 | $0.003 / $0.012 | −89% |
| [Gemma 3 4B IT](https://uberllm.dev/models/google/gemma-3-4b-it) | text | $0.0045 / $0.009 | $0.0005 / $0.001 | −89% |
| [Palmyra Vision 7B](https://uberllm.dev/models/writer/palmyra-vision-7b) | text | $0.03 / $0.12 | $0.0045 / $0.018 | −85% |
| [Nano Banana 2.1 (image-to-image)](https://uberllm.dev/models/google/nano-banana-2-1-edit) | image | $0.10 / image | $0.02 / image | −80% |
| [Nano Banana 2.1 (Venice)](https://uberllm.dev/models/google/venice-nano-banana-2-1) | image | $0.10 / image | $0.02 / image | −80% |
| [GPT Image 2 (Venice)](https://uberllm.dev/models/venice/gpt-image-2) | image | $0.135 / image | $0.03 / image | −78% |
| [Grok Imagine 2.0 (image-to-image)](https://uberllm.dev/models/x-ai/grok-imagine-image-2-0-edit) | image | $0.0815 / image | $0.02 / image | −75% |
| [Magistral Small 2509](https://uberllm.dev/models/mistralai/magistral-small-2509) | text | $0.03 / $0.09 | $0.01 / $0.03 | −67% |
| [Nano Banana 2 Lite (Venice)](https://uberllm.dev/models/google/venice-nano-banana-2-lite) | image | $0.06 / image | $0.02 / image | −67% |
| [GPT Image 2.5 Flare (image-to-image)](https://uberllm.dev/models/openai/gpt-image-2-5-flare-edit) | image | $0.08 / image | $0.03 / image | −62% |
| [GPT Image 2.5 Sunburst (image-to-image)](https://uberllm.dev/models/openai/gpt-image-2-5-sunburst-edit) | image | $0.08 / image | $0.03 / image | −62% |
| [GPT-6.1 Sol](https://uberllm.dev/models/openai/gpt-6.1-sol) | text | $1.06 / $5.30 | $0.44 / $2.20 | −58% |
| [Mistral Large 3](https://uberllm.dev/models/mistralai/mistral-large-3) | text | $0.25 / $0.75 | $0.105 / $0.315 | −58% |
| [GPT Image 2.5 Sunburst (Venice)](https://uberllm.dev/models/openai/venice-gpt-image-2-5-sunburst) | image | $0.07 / image | $0.03 / image | −57% |
| [Wan 2.6 Text-to-Video](https://uberllm.dev/models/wan/wan-2-6-text-to-video) | video | $0.1577 / sec | $0.07 / sec | −56% |
| [Kling 2.6 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-2-6-pro-image-to-video) | video | $0.1232 / sec | $0.055 / sec | −55% |
| [Seedance 2.0 Mini (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-image-to-video) | video | $0.0418 / sec | $0.019 / sec | −55% |
| [Kimi K2 Thinking](https://uberllm.dev/models/moonshotai/kimi-k2-thinking) | text | $0.114 / $0.475 | $0.054 / $0.225 | −53% |
| [Google: Gemini 4 Carbon](https://uberllm.dev/models/google/gemini-4-carbon) | text | $1.22 / $6.10 | $0.60 / $3.00 | −51% |
| [Z-Image Turbo (Venice)](https://uberllm.dev/models/venice/z-image-turbo) | image | $0.008 / image | $0.00396 / image | −50% |
| [Gemini 3.1 Flash Lite](https://uberllm.dev/models/google/gemini-3.1-flash-lite) | text | $0.005 / $0.03 | $0.0025 / $0.015 | −50% |
| [Nano Banana 2 (image-to-image)](https://uberllm.dev/models/google/nano-banana-2-edit) | image | $0.08 / image | $0.04 / image | −50% |
| [Whisper Large V3 (Venice)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.003 / minute | $0.0015 / minute | −50% |
| [Claude Opus 4.7](https://uberllm.dev/models/anthropic/claude-opus-4.7) | text | $1.90 / $9.50 | $1.00 / $5.00 | −47% |
| [Claude Opus 4.6 Fast](https://uberllm.dev/models/anthropic/claude-opus-4.6-fast) | text | $27.00 / $135.00 | $14.40 / $72.00 | −47% |
| [Seedance 2.0 Text-to-Video](https://uberllm.dev/models/bytedance/seedance-2-0-text-to-video) | video | $0.171 / sec | $0.095 / sec | −44% |
| [Claude Opus 4.8](https://uberllm.dev/models/anthropic/claude-opus-4.8) | text | $1.80 / $9.00 | $1.05 / $5.25 | −42% |
| [Seedream V5 Pro (image-to-image)](https://uberllm.dev/models/bytedance/seedream-v5-pro-edit) | image | $0.06 / image | $0.035 / image | −42% |
| [Seedream V5 Pro (Venice)](https://uberllm.dev/models/bytedance/venice-seedream-v5-pro) | image | $0.06 / image | $0.035 / image | −42% |
| [Claude Sonnet 5](https://uberllm.dev/models/anthropic/claude-sonnet-5) | text | $0.82 / $4.10 | $0.48 / $2.40 | −41% |
| [GPT-6 Sol](https://uberllm.dev/models/openai/gpt-6-sol) | text | $0.68 / $3.40 | $0.40 / $2.00 | −41% |
| [Wan 2.6 Flash Image-to-Video](https://uberllm.dev/models/wan/wan-2-6-flash-image-to-video) | video | $0.0336 / sec | $0.02 / sec | −40% |
| [Mistral Large](https://uberllm.dev/models/mistralai/mistral-large) | text | $0.30 / $0.90 | $0.18 / $0.54 | −40% |
| [Qwen Image 3 (Venice)](https://uberllm.dev/models/venice/qwen-image-3) | image | $0.04 / image | $0.024 / image | −40% |
| [Kling O3 Pro Text-to-Video](https://uberllm.dev/models/kling/kling-o3-pro-text-to-video) | video | $0.1457 / sec | $0.09 / sec | −38% |
| [Gemma 4 31B](https://uberllm.dev/models/google/gemma-4-31b) | text | $0.02682 / $0.08046 | $0.0168 / $0.0504 | −37% |
| [OpenAI: GPT-6.1 Terra](https://uberllm.dev/models/openai/gpt-6.1-terra) | text | $0.51 / $2.55 | $0.32 / $1.60 | −37% |
| [Qwen Image 3 Pro (Venice)](https://uberllm.dev/models/venice/qwen-image-3-pro) | image | $0.05 / image | $0.032 / image | −36% |
| [Kimi K2.6](https://uberllm.dev/models/moonshotai/kimi-k2.6) | text | $0.091 / $0.4774 | $0.0585 / $0.3069 | −36% |
| [xAI Speech to Text v1 (Venice)](https://uberllm.dev/models/venice/xai-stt-v1) | transcription | $0.001322 / minute | $0.00085 / minute | −36% |
| [Gemini 3.6 Flash](https://uberllm.dev/models/google/gemini-3-6-flash) | text | $0.4875 / $2.44 | $0.315 / $1.57 | −35% |
| [Ministral 14B 3.0](https://uberllm.dev/models/mistralai/ministral-3-14b-instruct) | text | $0.04 / $0.04 | $0.026 / $0.026 | −35% |
| [Hailuo 02 Standard Text to Video](https://uberllm.dev/models/minimax/hailuo-02-standard-text-to-video) | video | $0.03814 / sec | $0.025 / sec | −34% |
| [GPT-6 Astra](https://uberllm.dev/models/openai/gpt-6-astra) | text | $2.10 / $10.50 | $1.40 / $7.00 | −33% |
| [Nano Banana 2 Lite (image-to-image)](https://uberllm.dev/models/google/nano-banana-2-lite-edit) | image | $0.03 / image | $0.02 / image | −33% |
| [Kling 2.5 Turbo Pro (image-to-video)](https://uberllm.dev/models/kling/kling-2-5-turbo-pro-image-to-video) | video | $0.0624 / sec | $0.042 / sec | −33% |
| [NVIDIA Nemotron Nano 9B v2](https://uberllm.dev/models/nvidia/nemotron-nano-9b-v2) | text | $0.0132 / $0.0506 | $0.009 / $0.0345 | −32% |
| [MiMo-V2.6-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro) | text | $0.3175 / $0.6351 | $0.2175 / $0.435 | −32% |
| [Claude Opus 5](https://uberllm.dev/models/anthropic/claude-opus-5) | text | $2.40 / $12.00 | $1.65 / $8.25 | −31% |
| [Luma Uni 1 (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-edit) | image | $0.048 / image | $0.033 / image | −31% |
| [Luma Uni 1 Max (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-max-edit) | image | $0.104 / image | $0.0715 / image | −31% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.024 / $0.096 | $0.0165 / $0.066 | −31% |
| [Stable Diffusion XL (Venice, legacy)](https://uberllm.dev/models/venice/sdxl) | image | $0.008 / image | $0.0055 / image | −31% |
| [Longcat Distilled (image-to-video)](https://uberllm.dev/models/meituan/longcat-distilled-image-to-video) | video | $0.0144 / sec | $0.0099 / sec | −31% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.072 / sec | $0.0495 / sec | −31% |
| [Gemini Omni Flash (image-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-image-to-video) | video | $0.114 / sec | $0.07875 / sec | −31% |
| [Claude Fable 5.2](https://uberllm.dev/models/anthropic/claude-fable-5.2) | text | $4.72 / $23.60 | $3.28 / $16.40 | −31% |
| [Qwen Image 2 (image-to-image)](https://uberllm.dev/models/qwen/qwen-image-2-edit) | image | $0.04 / image | $0.028 / image | −30% |
| [MiMo-V2.6-Flash](https://uberllm.dev/models/xiaomi/mimo-v2.6-flash) | text | $0.1176 / $0.2352 | $0.0826 / $0.1652 | −30% |
| [Kling O3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-o3-standard-image-to-video) | video | $0.09867 / sec | $0.07 / sec | −29% |
| [Qwen: Qwen3.8 Max Prime](https://uberllm.dev/models/qwen/qwen3.8-max-prime) | text | $3.92 / $11.76 | $2.84 / $8.52 | −28% |
| [Gemini 3.1 Pro](https://uberllm.dev/models/google/gemini-3.1-pro) | text | $1.92 / $11.52 | $1.40 / $8.40 | −27% |
| [Kling O3 Standard (reference-to-video)](https://uberllm.dev/models/kling/kling-o3-standard-reference-to-video) | video | $0.09248 / sec | $0.06782 / sec | −27% |
| [Longcat (image-to-video)](https://uberllm.dev/models/meituan/longcat-image-to-video) | video | $0.0375 / sec | $0.0275 / sec | −27% |
| [Kling O3 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-o3-pro-image-to-video) | video | $0.1227 / sec | $0.09 / sec | −27% |
| [LTX 2 v2.3 Fast Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.06333 / sec | $0.04667 / sec | −26% |
| [Seedance 2.0 Fast (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-reference-to-video) | video | $0.0665 / sec | $0.049 / sec | −26% |
| [Gemini 3.5 Flash Lite](https://uberllm.dev/models/google/gemini-3-5-flash-lite) | text | $0.171 / $1.43 | $0.126 / $1.05 | −26% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.06337 / sec | $0.04669 / sec | −26% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.0171 / sec | $0.0126 / sec | −26% |
| [Vidu Q3 (image-to-video)](https://uberllm.dev/models/vidu/vidu-q3-image-to-video) | video | $0.0855 / sec | $0.063 / sec | −26% |
| [Wan 2.5 Preview (image-to-video)](https://uberllm.dev/models/wan/wan-2-5-preview-image-to-video) | video | $0.0532 / sec | $0.0392 / sec | −26% |
| [Seedance 2.0 Mini (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-reference-to-video) | video | $0.0418 / sec | $0.0308 / sec | −26% |
| [Veo3.1 Fast (image-to-video)](https://uberllm.dev/models/google/veo3-1-fast-image-to-video) | video | $0.1568 / sec | $0.1155 / sec | −26% |
| [Veo 3.1 Fast Text-to-Video](https://uberllm.dev/models/google/veo3-1-fast-text-to-video) | video | $0.1568 / sec | $0.1155 / sec | −26% |
| [Veo3.1 Full (image-to-video)](https://uberllm.dev/models/google/veo3-1-full-image-to-video) | video | $0.418 / sec | $0.308 / sec | −26% |
| [Veo 3.1 Full Text-to-Video](https://uberllm.dev/models/google/veo3-1-full-text-to-video) | video | $0.418 / sec | $0.308 / sec | −26% |
| [Happyhorse 1.0 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.1456 / sec | $0.1073 / sec | −26% |
| [Happyhorse 1.1 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.1456 / sec | $0.1073 / sec | −26% |
| [Happyhorse 1.1 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-reference-to-video) | video | $0.1456 / sec | $0.1073 / sec | −26% |
| [Pixverse C1 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-c1-image-to-video) | video | $0.04113 / sec | $0.03031 / sec | −26% |
| [Runway Gen-4.5](https://uberllm.dev/models/runway/runway-gen4-5) | video | $0.152 / sec | $0.112 / sec | −26% |
| [Topaz Video Upscale](https://uberllm.dev/models/topaz-labs/topaz-video-upscale) | video | $0.1425 / video | $0.105 / video | −26% |
| [Wan 2.7 (reference-to-video)](https://uberllm.dev/models/wan/wan-2-7-reference-to-video) | video | $0.1045 / sec | $0.077 / sec | −26% |
| [Kling O3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-o3-4k-text-to-video) | video | $0.4402 / sec | $0.3243 / sec | −26% |
| [Vidu Q3 Text-to-Video](https://uberllm.dev/models/vidu/vidu-q3-text-to-video) | video | $0.1837 / sec | $0.1353 / sec | −26% |
| [LTX 2 v2.3 Full Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.08392 / sec | $0.06183 / sec | −26% |
| [Kling V3 Standard Text-to-Video](https://uberllm.dev/models/kling/kling-v3-standard-text-to-video) | video | $0.1311 / sec | $0.0973 / sec | −26% |
| [LiquidAI: LFM2.5-24B-A2B](https://uberllm.dev/models/liquid/lfm-2.5-24b-a2b) | text | $0.047 / $0.658 | $0.035 / $0.49 | −26% |
| [Sakana: Fugu Max](https://uberllm.dev/models/sakana/fugu-max) | text | $1.88 / $5.64 | $1.40 / $4.20 | −26% |
| [Qwen 3 235B A22B Thinking 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.144 / $1.12 | $0.108 / $0.84 | −25% |
| [Trinity Large Thinking](https://uberllm.dev/models/arcee-ai/trinity-large-thinking) | text | $0.30 / $1.00 | $0.225 / $0.7538 | −25% |
| [GPT-5.6 Luna](https://uberllm.dev/models/openai/gpt-5.6-luna) | text | $0.056 / $0.336 | $0.042 / $0.252 | −25% |
| [Tencent: Hy4](https://uberllm.dev/models/tencent/hy4) | text | $0.3503 / $1.05 | $0.2627 / $0.7878 | −25% |
| [Reflection: Beam 1.0 501B A23B](https://uberllm.dev/models/reflection/beam-1.0-501b-a23b) | text | $0.279 / $0.93 | $0.21 / $0.70 | −25% |
| [MiMo-V2.6-Pro-UltraSpeed](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro-ultraspeed) | text | $4.05 / $8.09 | $3.04 / $6.09 | −25% |
| [JEV 1.13 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.13) | other | $0.03948 / $0 | $0.02982 / $0 | in −24% / out – |
| [Elorian: Glimpse](https://uberllm.dev/models/elorian/glimpse) | text | $0.564 / $2.82 | $0.426 / $2.13 | −24% |
| [Qwen3 VL 235B A22B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-instruct) | text | $0.05237 / $0.4738 | $0.0399 / $0.361 | −24% |
| [JEV 1.14 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.14) | other | $0.04074 / $0 | $0.03108 / $0 | in −24% / out – |
| [Ministral 3 8B](https://uberllm.dev/models/mistralai/ministral-3-8b-instruct) | text | $0.051 / $0.051 | $0.039 / $0.039 | −24% |
| [Claude Haiku 4.5](https://uberllm.dev/models/anthropic/claude-haiku-4.5) | text | $0.69 / $3.45 | $0.53 / $2.65 | −23% |
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | text | $0.156 / $0.91 | $0.12 / $0.70 | −23% |
| [Gemini 3.1 Flash TTS](https://uberllm.dev/models/google/tts-gemini-3-1-flash) | speech | $0.1219 / 1K chars | $0.09375 / 1K chars | −23% |
| [Seedance 2.0 Fast Text-to-Video (Venice)](https://uberllm.dev/models/venice/seedance-2-fast-t2v) | video | $0.07567 / sec | $0.059 / sec | −22% |
| [Kling O3 Pro (reference-to-video)](https://uberllm.dev/models/kling/kling-o3-pro-reference-to-video) | video | $0.115 / sec | $0.09 / sec | −22% |
| [Happyhorse 1.0 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-image-to-video) | video | $0.1073 / sec | $0.08432 / sec | −21% |
| [Cohere: Command A+](https://uberllm.dev/models/cohere/command-a-plus) | text | $0.267 / $1.33 | $0.21 / $1.05 | −21% |
| [Qwen 3 Coder 480B Turbo](https://uberllm.dev/models/qwen/qwen3-coder-turbo) | text | $0.2205 / $0.945 | $0.175 / $0.75 | −21% |
| [Moondream: Moondream 3.1](https://uberllm.dev/models/moondream/moondream3.1-9b-a2b) | text | $0.264 / $2.20 | $0.21 / $1.75 | −20% |
| [Wan 2.7 Pro (image-to-image)](https://uberllm.dev/models/wan/wan-2-7-pro-edit) | image | $0.0752 / image | $0.06 / image | −20% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | text | $0.28 / $0.88 | $0.224 / $0.704 | −20% |
| [Aion 2.0](https://uberllm.dev/models/aion-labs/aion-2.0) | text | $0.68 / $1.36 | $0.544 / $1.09 | −20% |
| [Moondream: Moondream 3 Preview](https://uberllm.dev/models/moondream/moondream3-preview) | text | $0.261 / $2.17 | $0.21 / $1.75 | −20% |
| [GPT-5.4](https://uberllm.dev/models/openai/gpt-5.4) | text | $1.55 / $9.30 | $1.25 / $7.50 | −19% |
| [Fireworks: Ember-1](https://uberllm.dev/models/fireworks/ember-1) | text | $2.64 / $13.20 | $2.13 / $10.65 | −19% |
| [Pareto 26.9](https://uberllm.dev/models/unbiased/pareto-26.9) | text | $2.23 / $6.67 | $1.80 / $5.40 | −19% |
| [GPT-6 Luna Decisions (OpenAI)](https://uberllm.dev/models/openai/gpt-6-luna-decisions) | other | $0.085 / $0 | $0.069 / $0 | in −19% / out – |
| [MMAudio V2 Text-to-Audio (Venice)](https://uberllm.dev/models/venice/mmaudio-v2-text-to-audio) | music | $0.008 / track | $0.0065 / track | −19% |
| [Qwen Image 2 Pro (Venice)](https://uberllm.dev/models/venice/qwen-image-2-pro) | image | $0.08 / image | $0.065 / image | −19% |
| [Seedream V4.5 (Venice)](https://uberllm.dev/models/venice/seedream-v4) | image | $0.04 / image | $0.0325 / image | −19% |
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.0099 / $0.121 | $0.0081 / $0.099 | −18% |
| [DeepSeek V4 Flash 0731](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731) | text | $0.02213 / $0.1326 | $0.01823 / $0.1092 | −18% |
| [Gemini 3.1 Pro Preview](https://uberllm.dev/models/google/gemini-3.1-pro-preview) | text | $0.36 / $2.16 | $0.30 / $1.80 | −17% |
| [GLM-4.6](https://uberllm.dev/models/z-ai/glm-4.6) | text | $0.1849 / $0.7525 | $0.1548 / $0.63 | −16% |
| [Mistral Small 3.2 24B Instruct](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.03564 / $0.095 | $0.03002 / $0.08 | −16% |
| [Qwen 3.6 27B](https://uberllm.dev/models/qwen/qwen3.6-27b) | text | $0.1056 / $1.06 | $0.0896 / $0.896 | −15% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://uberllm.dev/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.3784 / $1.14 | $0.3212 / $0.9636 | −15% |
| [inclusionAI: Ling 3.1 Flash](https://uberllm.dev/models/inclusionai/ling-3.1-flash) | text | $0.045 / $0.135 | $0.03825 / $0.1148 | −15% |
| [Claude Sonnet 5.5](https://uberllm.dev/models/anthropic/claude-sonnet-5.5) | text | $0.68 / $3.40 | $0.58 / $2.90 | −15% |
| [ElevenLabs Scribe v2 (STT)](https://uberllm.dev/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.005812 / minute | $0.00501 / minute | −14% |
| [Sakana: Fugu Ultra v2](https://uberllm.dev/models/sakana/fugu-ultra-v2) | text | $4.50 / $27.00 | $3.90 / $23.40 | −13% |
| [Chroma (Venice)](https://uberllm.dev/models/venice/chroma) | image | $0.0075 / image | $0.0065 / image | −13% |
| [Grok Imagine (Venice)](https://uberllm.dev/models/venice/grok-imagine) | image | $0.0225 / image | $0.0195 / image | −13% |
| [Particle AI: Particle-1](https://uberllm.dev/models/particle-ai/particle-1) | text | $0.0455 / $0.455 | $0.0395 / $0.395 | −13% |
| [Kling V3 Turbo Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-standard-image-to-video) | video | $0.09867 / sec | $0.08631 / sec | −13% |
| [Kling V3 Turbo Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.1227 / sec | $0.1073 / sec | −13% |
| [Kling V3 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-pro-image-to-video) | video | $0.1467 / sec | $0.1283 / sec | −13% |
| [Kling V3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-v3-4k-reference-to-video) | video | $0.3707 / sec | $0.3243 / sec | −13% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://uberllm.dev/models/venice/elevenlabs-tts-turbo-v2-5) | speech | $0.05 / 1K chars | $0.04375 / 1K chars | −13% |
| [Gemini Omni Flash (reference-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-reference-to-video) | video | $0.114 / sec | $0.09975 / sec | −12% |
| [Kling V3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-standard-image-to-video) | video | $0.112 / sec | $0.098 / sec | −12% |
| [MiniMax M2.5](https://uberllm.dev/models/minimax/minimax-m2.5) | text | $0.0216 / $0.076 | $0.0189 / $0.0665 | −12% |
| [GPT-5.4 Mini](https://uberllm.dev/models/openai/gpt-5.4-mini) | text | $0.12 / $0.72 | $0.105 / $0.63 | −12% |
| [Ovi Image-to-Video](https://uberllm.dev/models/ovi/ovi-image-to-video) | video | $0.0352 / sec | $0.0308 / sec | −12% |
| [Flux 1.1 (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1) | image | $0.008 / image | $0.007 / image | −12% |
| [MiniMax Music 2.0 (Venice)](https://uberllm.dev/models/venice/minimax-music-v2) | music | $0.032 / track | $0.028 / track | −12% |
| [Firered Image (image-to-image)](https://uberllm.dev/models/xiaohongshu/firered-image-edit) | image | $0.032 / image | $0.028 / image | −12% |
| [Z.ai: GLM 5.3 FlashX Legal](https://uberllm.dev/models/z-ai/glm-5.3-flashx-legal) | text | $0.296 / $1.00 | $0.259 / $0.875 | −12% |
| [Inworld 1.5 Max TTS](https://uberllm.dev/models/inworld/tts-inworld-1-5-max) | speech | $0.01 / 1K chars | $0.00875 / 1K chars | −12% |
| [Qwen Image 2 Pro (image-to-image)](https://uberllm.dev/models/qwen/qwen-image-2-pro-edit) | image | $0.08 / image | $0.07 / image | −12% |
| [Chatterbox HD TTS](https://uberllm.dev/models/resemble-ai/tts-chatterbox-hd) | speech | $0.04 / 1K chars | $0.035 / 1K chars | −12% |
| [Hunyuan Image 3.0 (Venice)](https://uberllm.dev/models/venice/hunyuan-image-v3) | image | $0.072 / image | $0.063 / image | −12% |
| [Seedream v4 — Edit (Venice)](https://uberllm.dev/models/bytedance/seedream-v4-edit) | image | $0.0285 / image | $0.025 / image | −12% |
| [Aion 3.0 Mini](https://uberllm.dev/models/aion-labs/aion-3-0-mini) | text | $0.462 / $0.924 | $0.406 / $0.812 | −12% |
| [Qwen 3 235B A22B Instruct 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-2507) | text | $0.0658 / $0.3525 | $0.0588 / $0.315 | −11% |
| [Qwen 3.5 397B](https://uberllm.dev/models/qwen/qwen3.5-397b-a17b) | text | $0.288 / $1.73 | $0.258 / $1.55 | −10% |
| [GPT-5.2 Codex](https://uberllm.dev/models/openai/gpt-5.2-codex) | text | $1.35 / $10.78 | $1.49 / $11.90 | +10% |
| [Z.ai: GLM 5.3 FlashX](https://uberllm.dev/models/z-ai/glm-5.3-flashx) | text | $0.2257 / $0.7625 | $0.2516 / $0.85 | +11% |
| [Qwen Image 2 (Venice)](https://uberllm.dev/models/venice/qwen-image-2) | image | $0.025 / image | $0.028 / image | +12% |
| [GPT-5.2](https://uberllm.dev/models/openai/gpt-5.2) | text | $0.4025 / $3.22 | $0.455 / $3.64 | +13% |
| [Gemini 3 Flash Preview](https://uberllm.dev/models/google/gemini-3-flash-preview) | text | $0.035 / $0.21 | $0.04 / $0.24 | +14% |
| [Kimi K3](https://uberllm.dev/models/moonshotai/kimi-k3) | text | $0.01344 / $1.12 | $0.01536 / $1.28 | +14% |
| [Wan 2.7 (Venice)](https://uberllm.dev/models/venice/wan-2.7) | image | $0.02063 / image | $0.024 / image | +16% |
| [ACE-Step 1.5 (Venice)](https://uberllm.dev/models/venice/ace-step-15) | music | $0.018 / track | $0.021 / track | +17% |
| [ElevenLabs Music (Venice)](https://uberllm.dev/models/venice/elevenlabs-music) | music | $0.414 / track | $0.483 / track | +17% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.01606 / $0.05355 | $0.0189 / $0.063 | +18% |
| [Recraft V4 (Venice)](https://uberllm.dev/models/venice/recraft-v4) | image | $0.025 / image | $0.03 / image | +20% |
| [Qwen3.8 Flash](https://uberllm.dev/models/qwen/qwen3.8-flash) | text | $0.021 / $0.0658 | $0.0255 / $0.0799 | +21% |
| [Seed 2.1 Turbo](https://uberllm.dev/models/bytedance/seed-2-1-turbo) | text | $0.27 / $1.35 | $0.33 / $1.65 | +22% |
| [Flux 2 Pro (Venice)](https://uberllm.dev/models/venice/flux-2-pro) | image | $0.006 / image | $0.0075 / image | +25% |
| [Meta: Muse Spark 1.2 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.2-contributor) | text | $0.075 / $0.15 | $0.096 / $0.192 | +28% |
| [DeepSeek V3.2](https://uberllm.dev/models/deepseek/deepseek-v3.2) | text | $0.052 / $0.076 | $0.06726 / $0.09831 | +29% |
| [GPT-4o Mini](https://uberllm.dev/models/openai/gpt-4o-mini) | text | $0.021 / $0.084 | $0.0285 / $0.114 | +36% |
| [Pixverse V5.6 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-v5-6-image-to-video) | video | $0.101 / sec | $0.1414 / sec | +40% |
| [Grok Imagine Pro (Venice)](https://uberllm.dev/models/venice/grok-imagine-pro) | image | $0.035 / image | $0.049 / image | +40% |
| [Wan 2.7 Text-to-Video](https://uberllm.dev/models/wan/wan-2-7-text-to-video) | video | $0.055 / sec | $0.077 / sec | +40% |
| [Flux 1.1 Pro (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1-pro) | image | $0.015 / image | $0.021 / image | +40% |
| [Mistral: Mistral Large 4](https://uberllm.dev/models/mistralai/mistral-large-4-0) | text | $0.378 / $1.13 | $0.532 / $1.60 | +41% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | text | $0.86 / $2.58 | $1.24 / $3.72 | +44% |
| [GPT 5 Nano](https://uberllm.dev/models/openai/gpt-5-nano) | text | $0.017 / $0.136 | $0.02499 / $0.20 | +47% |
| [Qwen3 Coder Next](https://uberllm.dev/models/qwen/qwen3-coder-next) | text | $0.0204 / $0.136 | $0.03 / $0.20 | +47% |
| [Qwen 3 Coder 480b](https://uberllm.dev/models/qwen/qwen3-coder) | text | $0.051 / $0.17 | $0.075 / $0.25 | +47% |
| [Qwen: Qwen3.7 Flash](https://uberllm.dev/models/qwen/qwen3.7-flash) | text | $0.0069 / $0.0299 | $0.0102 / $0.0442 | +48% |
| [Qwen3.8 2.4T A95B](https://uberllm.dev/models/qwen/qwen3.8-2.4t-a95b) | text | $0.34 / $1.02 | $0.52 / $1.56 | +53% |
| [GPT-OSS 120B](https://uberllm.dev/models/openai/gpt-oss-120b) | text | $0.0084 / $0.036 | $0.0133 / $0.057 | +58% |
| [Nano Banana 2 (Venice)](https://uberllm.dev/models/venice/nano-banana-2) | image | $0.025 / image | $0.04 / image | +60% |
| [DeepSeek V4 Pro](https://uberllm.dev/models/deepseek/deepseek-v4-pro) | text | $0.03821 / $0.07642 | $0.063 / $0.105 | in +65% / out +37% |
| [Qwen3 Coder 30B A3B Instruct](https://uberllm.dev/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.0105 / $0.042 | $0.0175 / $0.07 | +67% |
| [Tencent HY3](https://uberllm.dev/models/tencent/hy3) | text | $0.05412 / $0.2165 | $0.0924 / $0.3696 | +71% |
| [Z.ai: GLM 5.3 Prime](https://uberllm.dev/models/z-ai/glm-5.3-prime) | text | $0.476 / $1.50 | $0.868 / $2.73 | +82% |
| [Qwen 3.8 27B](https://uberllm.dev/models/qwen/qwen-3-8-27b) | text | $0.009 / $0.1125 | $0.0165 / $0.2062 | +83% |
| [Gemini 3.5 Flash](https://uberllm.dev/models/google/gemini-3.5-flash) | text | $0.045 / $0.27 | $0.09 / $0.54 | +100% |
| [Kokoro Text to Speech (Venice)](https://uberllm.dev/models/venice/kokoro-tts) | speech | $0.000875 / 1K chars | $0.00175 / 1K chars | +100% |
| [MiniMax M2](https://uberllm.dev/models/minimax/minimax-m2) | text | $0.015 / $0.06 | $0.033 / $0.132 | +120% |
| [GLM 4.5](https://uberllm.dev/models/z-ai/glm-4.5) | text | $0.036 / $0.132 | $0.084 / $0.308 | +133% |
| [Whisper Large V3 (STT)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0015 / minute | $0.0036 / minute | +140% |
| [Wan 2.7 Pro (Venice)](https://uberllm.dev/models/venice/wan-2.7-pro) | image | $0.02344 / image | $0.06 / image | +156% |
| [Venice SD35](https://uberllm.dev/models/venice/sd35) | image | $0.0025 / image | $0.0065 / image | +160% |
| [MiniMax Speech 02 HD TTS](https://uberllm.dev/models/minimax/tts-minimax-speech-02-hd) | speech | $0.03125 / 1K chars | $0.0875 / 1K chars | +180% |
| [Qwen3 1.7B TTS](https://uberllm.dev/models/qwen/tts-qwen3-1-7b) | speech | $0.02813 / 1K chars | $0.07875 / 1K chars | +180% |
| [GPT Image 1.5 (Venice)](https://uberllm.dev/models/venice/gpt-image-1.5) | image | $0.065 / image | $0.182 / image | +180% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-multilingual-v2) | music | $0.03 / track | $0.084 / track | +180% |
| [ElevenLabs TTS v3 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-v3) | music | $0.03 / track | $0.084 / track | +180% |
| [Qwen Image (Venice)](https://uberllm.dev/models/venice/qwen-image) | image | $0.0075 / image | $0.021 / image | +180% |
| [Flux 2 Max (Venice)](https://uberllm.dev/models/venice/flux-2-max) | image | $0.018 / image | $0.0522 / image | +190% |
| [MoonshotAI: Kimi K3.1 Pro](https://uberllm.dev/models/moonshotai/kimi-k3.1-pro) | text | $0.08 / $2.83 | $0.36 / $1.80 | in +350% / out −36% |
| [Gemini 3.7 Flash](https://uberllm.dev/models/google/gemini-3.7-flash) | text | $0.03 / $0.15 | $0.1425 / $0.7125 | +375% |
| [StepFun: Step 5 Preview](https://uberllm.dev/models/stepfun/step-5-preview) | text | $0.10 / $0.27 | $0.76 / $2.05 | +660% |
| [DeepSeek V4.1 Flash](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash) | text | $0.00792 / $0.144 | $0.108 / $0.432 | in +1264% / out +200% |
| [Nano Banana (Gemini 2.5 Flash Image)](https://uberllm.dev/models/google/gemini-2.5-flash-image) | image | $0.003 / $0.025 | $0.048 / $0.40 | +1500% |

</details>


## 2026-11-13 (vs 2026-11-12)

**Official list price changes (4)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [MiMo-V2.5-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.5-pro) | text | $0.48 / $1.80 | $0.435 / $0.87 | in −9% / out −52% |
| [Kimi K2.5](https://uberllm.dev/models/moonshotai/kimi-k2.5) | text | $0.532 / $3.33 | $0.50 / $2.50 | in −6% / out −25% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | – / – | $0.0765 / $0.255 |  |
| [Wan 2.5 Preview (image-to-video)](https://uberllm.dev/models/wan/wan-2-5-preview-image-to-video) | video | – | $0.056 / sec |  |

**New models (24)**

| Model | Category | Official price | UberLLM price |
|---|---|---|---|
| [Seedream V5.5 (Venice)](https://uberllm.dev/models/bytedance/venice-seedream-v5-5) | image | $0.0255 / image | – |
| [Seedream V5.5 (image-to-image)](https://uberllm.dev/models/bytedance/venice-seedream-v5-5-edit) | image | $0.0255 / image | – |
| [DeepSeek V4 Flash (Morpheus Web)](https://uberllm.dev/models/deepseek/deepseek-v4-flash:web) | text | – | $0.1139 / $0.2345 |
| [Google: Gemini 4 Hydrogen](https://uberllm.dev/models/google/gemini-4-hydrogen) | text | $1.50 / $7.50 | $0.7481 / $3.74 |
| [Veo3.1 Fast (image-to-video)](https://uberllm.dev/models/google/veo3-1-fast-image-to-video) | video | $0.165 / sec | $0.1568 / sec |
| [Veo3.1 Full (image-to-video)](https://uberllm.dev/models/google/veo3-1-full-image-to-video) | video | $0.44 / sec | $0.418 / sec |
| [Llama 3.2 3B (Morpheus Web)](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct:web) | text | – | $0.1005 / $0.402 |
| [Llama 3.3 70B (Morpheus Web)](https://uberllm.dev/models/meta-llama/llama-3.3-70b-instruct:web) | text | – | $0.469 / $1.88 |
| [Mistral Small 3.2 24B Instruct (Morpheus Web)](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct:web) | text | $0.0938 / $0.25 | $0.06281 / $0.1675 |
| [Kimi K2.5 (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.5:web) | text | $0.50 / $2.50 | $0.3752 / $2.35 |
| [Kimi K2.6 (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.6:web) | text | $0.65 / $3.41 | $0.5695 / $3.12 |
| [Kimi K2.7 Code (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.7-code:web) | text | $0.60 / $3.50 | $0.4556 / $2.28 |
| [OpenAI GPT OSS 120B (Morpheus Web)](https://uberllm.dev/models/openai/gpt-oss-120b:web) | text | $0.07 / $0.30 | $0.0469 / $0.201 |
| [GPT Image 2.6 Flare (Venice)](https://uberllm.dev/models/openai/venice-gpt-image-2-6-flare) | image | $0.09 / image | – |
| [GPT Image 2.6 Flare (image-to-image)](https://uberllm.dev/models/openai/venice-gpt-image-2-6-flare-edit) | image | $0.10 / image | – |
| [GPT Image 2.6 Sunburst (Venice)](https://uberllm.dev/models/openai/venice-gpt-image-2-6-sunburst) | image | $0.09 / image | – |
| [GPT Image 2.6 Sunburst (image-to-image)](https://uberllm.dev/models/openai/venice-gpt-image-2-6-sunburst-edit) | image | $0.10 / image | – |
| [Pixverse C1 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-c1-image-to-video) | video | $0.0433 / sec | $0.04113 / sec |
| [Pixverse C1 Transition (transition)](https://uberllm.dev/models/pixverse/pixverse-c1-transition) | video | $0.0433 / sec | $0.03247 / sec |
| [Pixverse V5.6 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-v5-6-image-to-video) | video | $0.202 / sec | $0.101 / sec |
| [Pixverse V5.6 Transition (transition)](https://uberllm.dev/models/pixverse/pixverse-v5-6-transition) | video | $0.202 / sec | $0.1515 / sec |
| [Qwen 3 235B A22B Instruct 2507 (Morpheus Web)](https://uberllm.dev/models/qwen/qwen3-235b-a22b-2507:web) | text | $0.14 / $0.75 | $0.1005 / $0.5025 |
| [StepFun: Step 5 Preview](https://uberllm.dev/models/stepfun/step-5-preview) | text | $1.00 / $2.70 | $0.10 / $0.27 |
| [Vidu Q3 (image-to-video)](https://uberllm.dev/models/vidu/vidu-q3-image-to-video) | video | $0.09 / sec | $0.0855 / sec |

**No longer listed (3)**: `bytedance/venice-seedance-2-5-image-to-video-basic`, `bytedance/venice-seedance-2-5-reference-to-video-basic`, `bytedance/venice-seedance-2-5-text-to-video-basic`

<details><summary>UberLLM price moves of 10% or more (164)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.0675 / $0.825 | $0.0099 / $0.121 | −85% |
| [Mistral Large](https://uberllm.dev/models/mistralai/mistral-large) | text | $1.58 / $4.74 | $0.30 / $0.90 | −81% |
| [GPT-4o](https://uberllm.dev/models/openai/gpt-4o) | text | $1.75 / $7.00 | $0.50 / $2.00 | −71% |
| [MiniMax Speech 02 HD TTS](https://uberllm.dev/models/minimax/tts-minimax-speech-02-hd) | speech | $0.10 / 1K chars | $0.03125 / 1K chars | −69% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-multilingual-v2) | music | $0.096 / track | $0.03 / track | −69% |
| [ElevenLabs TTS v3 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-v3) | music | $0.096 / track | $0.03 / track | −69% |
| [Kokoro Text to Speech (Venice)](https://uberllm.dev/models/venice/kokoro-tts) | speech | $0.0028 / 1K chars | $0.000875 / 1K chars | −69% |
| [Qwen Image (Venice)](https://uberllm.dev/models/venice/qwen-image) | image | $0.024 / image | $0.0075 / image | −69% |
| [Venice SD35](https://uberllm.dev/models/venice/sd35) | image | $0.008 / image | $0.0025 / image | −69% |
| [Flux 2 Max (Venice)](https://uberllm.dev/models/venice/flux-2-max) | image | $0.0522 / image | $0.018 / image | −66% |
| [Whisper Large V3 (STT)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0042 / minute | $0.0015 / minute | −64% |
| [Qwen3 1.7B TTS](https://uberllm.dev/models/qwen/tts-qwen3-1-7b) | speech | $0.07312 / 1K chars | $0.02813 / 1K chars | −62% |
| [Ministral 14B 3.0](https://uberllm.dev/models/mistralai/ministral-3-14b-instruct) | text | $0.098 / $0.098 | $0.04 / $0.04 | −59% |
| [MiMo-V2.5-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.5-pro) | text | $0.4608 / $1.73 | $0.3958 / $0.7917 | in −14% / out −54% |
| [Llama 3.3 70B Instruct](https://uberllm.dev/models/meta-llama/llama-3.3-70b-instruct) | text | $0.091 / $0.0923 | $0.042 / $0.04704 | in −54% / out −49% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.0495 / $0.198 | $0.024 / $0.096 | −52% |
| [Nano Banana Pro (image-to-image)](https://uberllm.dev/models/google/nano-banana-pro-edit) | image | $0.171 / image | $0.09043 / image | −47% |
| [GPT Image 1.5 (Venice)](https://uberllm.dev/models/venice/gpt-image-1.5) | image | $0.117 / image | $0.065 / image | −44% |
| [Wan 2.7 Pro (Venice)](https://uberllm.dev/models/venice/wan-2.7-pro) | image | $0.04219 / image | $0.02344 / image | −44% |
| [DeepSeek V4.1 Flash 1017](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.036 / $0.144 | $0.021 / $0.084 | −42% |
| [Nano Banana 2 Lite (image-to-image)](https://uberllm.dev/models/google/nano-banana-2-lite-edit) | image | $0.048 / image | $0.03 / image | −38% |
| [Flux 1.1 Pro (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1-pro) | image | $0.024 / image | $0.015 / image | −38% |
| [Qwen Image 2 (Venice)](https://uberllm.dev/models/venice/qwen-image-2) | image | $0.04 / image | $0.025 / image | −38% |
| [Qwen: Qwen3.7 Flash](https://uberllm.dev/models/qwen/qwen3.7-flash) | text | $0.0108 / $0.0468 | $0.0069 / $0.0299 | −36% |
| [Kimi K2.5](https://uberllm.dev/models/moonshotai/kimi-k2.5) | text | $0.2181 / $1.36 | $0.18 / $0.90 | in −17% / out −34% |
| [Gemini 3.1 Flash Lite](https://uberllm.dev/models/google/gemini-3.1-flash-lite) | text | $0.0075 / $0.045 | $0.005 / $0.03 | −33% |
| [Qwen3.7 Max](https://uberllm.dev/models/qwen/qwen3.7-max) | text | $1.70 / $5.07 | $1.19 / $3.54 | −30% |
| [MiniMax M2](https://uberllm.dev/models/minimax/minimax-m2) | text | $0.021 / $0.084 | $0.015 / $0.06 | −29% |
| [Seedream V5 Lite (Venice)](https://uberllm.dev/models/venice/seedream-v5-lite) | image | $0.035 / image | $0.025 / image | −29% |
| [Llama 3.2 3B](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct) | text | $0.0425 / $0.2805 | $0.0305 / $0.2013 | −28% |
| [Claude Sonnet 4.5](https://uberllm.dev/models/anthropic/claude-sonnet-4.5) | text | $2.04 / $10.20 | $1.50 / $7.50 | −26% |
| [Mistral Small 3.2 24B Instruct](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.04784 / $0.1275 | $0.03564 / $0.095 | −25% |
| [Qwen 3 235B A22B Instruct 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-2507) | text | $0.0868 / $0.465 | $0.0658 / $0.3525 | −24% |
| [GLM-5](https://uberllm.dev/models/z-ai/glm-5) | text | $0.29 / $0.928 | $0.22 / $0.704 | −24% |
| [Qwen 3.8 Max](https://uberllm.dev/models/qwen/qwen-3-8-max) | text | $0.225 / $0.675 | $0.175 / $0.525 | −22% |
| [Tencent: Hy4 preview](https://uberllm.dev/models/tencent/hy4-preview) | text | $0.6755 / $2.03 | $0.5254 / $1.58 | −22% |
| [Aion 3.5](https://uberllm.dev/models/aion-labs/aion-3-5) | text | $3.00 / $6.00 | $2.40 / $4.80 | −20% |
| [GPT OSS 20B](https://uberllm.dev/models/openai/e2ee-gpt-oss-20b-p) | text | $0.025 / $0.095 | $0.02 / $0.076 | −20% |
| [Claude Opus 4.7 Fast](https://uberllm.dev/models/anthropic/claude-opus-4.7-fast) | text | $18.00 / $90.00 | $14.40 / $72.00 | −20% |
| [Qwen3 VL 30B A3B](https://uberllm.dev/models/qwen/qwen3-vl-30b-a3b-thinking) | text | $0.225 / $0.81 | $0.1825 / $0.657 | −19% |
| [Orpheus TTS](https://uberllm.dev/models/canopy-labs/tts-orpheus) | speech | $0.05 / 1K chars | $0.04063 / 1K chars | −19% |
| [Qwen3 30B A3B](https://uberllm.dev/models/qwen/qwen3-30b-a3b) | text | $0.1128 / $0.47 | $0.0924 / $0.385 | −18% |
| [GPT-6 Luna](https://uberllm.dev/models/openai/gpt-6-luna) | text | $0.052 / $0.26 | $0.043 / $0.215 | −17% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | text | $1.04 / $3.12 | $0.86 / $2.58 | −17% |
| [Claude Opus 4.6](https://uberllm.dev/models/anthropic/claude-opus-4.6) | text | $1.45 / $7.25 | $1.20 / $6.00 | −17% |
| [Claude Fable 5.1](https://uberllm.dev/models/anthropic/claude-fable-5.1) | text | $4.10 / $20.50 | $3.40 / $17.00 | −17% |
| [Recraft V4 (Venice)](https://uberllm.dev/models/venice/recraft-v4) | image | $0.03 / image | $0.025 / image | −17% |
| [DeepSeek V4 Flash](https://uberllm.dev/models/deepseek/deepseek-v4-flash) | text | $0.0531 / $0.1062 | $0.045 / $0.09 | −15% |
| [Grok 4.20 Multi-Agent Beta](https://uberllm.dev/models/x-ai/grok-4.20-multi-agent-beta) | text | $0.75 / $1.50 | $0.6375 / $1.27 | −15% |
| [Aion 3.0](https://uberllm.dev/models/aion-labs/aion-3-0) | text | $2.22 / $4.44 | $1.89 / $3.78 | −15% |
| [GPT-5.2 Codex](https://uberllm.dev/models/openai/gpt-5.2-codex) | text | $1.57 / $12.60 | $1.35 / $10.78 | −14% |
| [Wan 2.6 Flash Image-to-Video](https://uberllm.dev/models/wan/wan-2-6-flash-image-to-video) | video | $0.0392 / sec | $0.0336 / sec | −14% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://uberllm.dev/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.44 / $1.32 | $0.3784 / $1.14 | −14% |
| [GPT OSS 120B](https://uberllm.dev/models/openai/e2ee-gpt-oss-120b-p) | text | $0.0767 / $0.3835 | $0.0663 / $0.3315 | −14% |
| [Aion 3.5 Mini](https://uberllm.dev/models/aion-labs/aion-3-5-mini) | text | $0.6125 / $1.23 | $0.5337 / $1.07 | −13% |
| [Meta: Muse Spark 1.2](https://uberllm.dev/models/meta-llama/muse-spark-1.2) | text | $0.80 / $2.72 | $0.70 / $2.38 | −13% |
| [Wan 2.7 Text-to-Video](https://uberllm.dev/models/wan/wan-2-7-text-to-video) | video | $0.0627 / sec | $0.055 / sec | −12% |
| [Fireworks: Ember-1](https://uberllm.dev/models/fireworks/ember-1) | text | $3.00 / $15.00 | $2.64 / $13.20 | −12% |
| [Wan 2.5 Preview (image-to-video)](https://uberllm.dev/models/wan/wan-2-5-preview-image-to-video) | video | $0.06 / sec | $0.0532 / sec | −11% |
| [GPT-5.4 Mini](https://uberllm.dev/models/openai/gpt-5.4-mini) | text | $0.135 / $0.81 | $0.12 / $0.72 | −11% |
| [OpenAI: GPT-6.1 Terra](https://uberllm.dev/models/openai/gpt-6.1-terra) | text | $0.57 / $2.85 | $0.51 / $2.55 | −11% |
| [Claude Opus 5 (Fast)](https://uberllm.dev/models/anthropic/claude-opus-5-fast) | text | $5.90 / $29.50 | $5.30 / $26.50 | −10% |
| [Pareto 26.9](https://uberllm.dev/models/unbiased/pareto-26.9) | text | $2.48 / $7.42 | $2.23 / $6.67 | −10% |
| [Grok Imagine (Venice)](https://uberllm.dev/models/venice/grok-imagine) | image | $0.02 / image | $0.0225 / image | +12% |
| [Gemini 2.5 Pro](https://uberllm.dev/models/google/gemini-2.5-pro) | text | $0.45 / $3.60 | $0.5125 / $4.10 | +14% |
| [Gemini Omni Flash (image-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-image-to-video) | video | $0.09975 / sec | $0.114 / sec | +14% |
| [Gemini Omni Flash (reference-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-reference-to-video) | video | $0.09975 / sec | $0.114 / sec | +14% |
| [Kling 2.5 Turbo Pro (image-to-video)](https://uberllm.dev/models/kling/kling-2-5-turbo-pro-image-to-video) | video | $0.0546 / sec | $0.0624 / sec | +14% |
| [Luma Uni 1 (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-edit) | image | $0.042 / image | $0.048 / image | +14% |
| [Luma Uni 1 Max (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-max-edit) | image | $0.091 / image | $0.104 / image | +14% |
| [Seedream V4.5 (Venice)](https://uberllm.dev/models/venice/seedream-v4) | image | $0.035 / image | $0.04 / image | +14% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.063 / sec | $0.072 / sec | +14% |
| [MiniMax M2.7](https://uberllm.dev/models/minimax/minimax-m2.7) | text | $0.1092 / $0.4368 | $0.126 / $0.504 | +15% |
| [ElevenLabs Scribe v2 (STT)](https://uberllm.dev/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.00501 / minute | $0.005812 / minute | +16% |
| [Kimi K3](https://uberllm.dev/models/moonshotai/kimi-k3) | text | $0.01152 / $0.96 | $0.01344 / $1.12 | +17% |
| [Meta: Muse Spark 1.2 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.2-contributor) | text | $0.063 / $0.126 | $0.075 / $0.15 | +19% |
| [Meta: Muse Spark Open](https://uberllm.dev/models/meta-llama/muse-spark-open) | text | $0.7875 / $2.68 | $0.9375 / $3.19 | +19% |
| [Wan 2.7 (Venice)](https://uberllm.dev/models/venice/wan-2.7) | image | $0.01688 / image | $0.02063 / image | +22% |
| [Wan 2.6 (image-to-video)](https://uberllm.dev/models/wan/wan-2-6-image-to-video) | video | $0.0627 / sec | $0.077 / sec | +23% |
| [Wan 2.7 (image-to-video)](https://uberllm.dev/models/wan/wan-2-7-image-to-video) | video | $0.0627 / sec | $0.077 / sec | +23% |
| [Seedance 2.0 Fast (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-image-to-video) | video | $0.0399 / sec | $0.049 / sec | +23% |
| [Seedance 2.0 (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-image-to-video) | video | $0.05016 / sec | $0.0616 / sec | +23% |
| [Happyhorse 1.0 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-image-to-video) | video | $0.08738 / sec | $0.1073 / sec | +23% |
| [Seedance 2.0 Fast Text-to-Video (Venice)](https://uberllm.dev/models/venice/seedance-2-fast-t2v) | video | $0.059 / sec | $0.07567 / sec | +28% |
| [Google: Gemini 4 Argon](https://uberllm.dev/models/google/gemini-4-argon) | text | $0.14 / $0.70 | $0.18 / $0.90 | +29% |
| [DeepSeek V3.1](https://uberllm.dev/models/deepseek/deepseek-v3.1) | text | $0.0575 / $0.2185 | $0.0748 / $0.2842 | +30% |
| [Qwen3 Coder Next](https://uberllm.dev/models/qwen/qwen3-coder-next) | text | $0.0156 / $0.104 | $0.0204 / $0.136 | +31% |
| [Seedance 2.0 (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-reference-to-video) | video | $0.05016 / sec | $0.066 / sec | +32% |
| [Kling O3.4k (image-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-image-to-video) | video | $0.2641 / sec | $0.3475 / sec | +32% |
| [Kling O3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-reference-to-video) | video | $0.2641 / sec | $0.3475 / sec | +32% |
| [Kling O3 Pro (reference-to-video)](https://uberllm.dev/models/kling/kling-o3-pro-reference-to-video) | video | $0.08738 / sec | $0.115 / sec | +32% |
| [Kling V3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-v3-4k-text-to-video) | video | $0.2641 / sec | $0.3475 / sec | +32% |
| [Kling O3 Standard (reference-to-video)](https://uberllm.dev/models/kling/kling-o3-standard-reference-to-video) | video | $0.07028 / sec | $0.09248 / sec | +32% |
| [Kling V3 Pro Text-to-Video](https://uberllm.dev/models/kling/kling-v3-pro-text-to-video) | video | $0.1045 / sec | $0.1375 / sec | +32% |
| [Ltx 2 V2.3 Full (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.05033 / sec | $0.06623 / sec | +32% |
| [DeepSeek V4.1 Flash](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash) | text | $0.00594 / $0.108 | $0.00792 / $0.144 | +33% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.0126 / sec | $0.0171 / sec | +36% |
| [GPT Image 2 — Edit (Venice)](https://uberllm.dev/models/venice/gpt-image-2-edit) | image | $0.252 / image | $0.342 / image | +36% |
| [Chroma (Venice)](https://uberllm.dev/models/venice/chroma) | image | $0.0055 / image | $0.0075 / image | +36% |
| [Qwen3 VL 235B A22B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-instruct) | text | $0.0378 / $0.342 | $0.05237 / $0.4738 | +39% |
| [NVIDIA Nemotron 3 Super 120B](https://uberllm.dev/models/nvidia/nemotron-3-super-120b) | text | $0.0285 / $0.152 | $0.03975 / $0.212 | +39% |
| [Qwen Image 2 (image-to-image)](https://uberllm.dev/models/qwen/qwen-image-2-edit) | image | $0.0285 / image | $0.04 / image | +40% |
| [Qwen Image 2 Pro (image-to-image)](https://uberllm.dev/models/qwen/qwen-image-2-pro-edit) | image | $0.057 / image | $0.08 / image | +40% |
| [Wan 2.7 Pro (image-to-image)](https://uberllm.dev/models/wan/wan-2-7-pro-edit) | image | $0.05358 / image | $0.0752 / image | +40% |
| [Firered Image (image-to-image)](https://uberllm.dev/models/xiaohongshu/firered-image-edit) | image | $0.0228 / image | $0.032 / image | +40% |
| [Kling 2.6 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-2-6-pro-image-to-video) | video | $0.08778 / sec | $0.1232 / sec | +40% |
| [Kling V3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-standard-image-to-video) | video | $0.0798 / sec | $0.112 / sec | +40% |
| [Kling V3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-v3-4k-reference-to-video) | video | $0.2641 / sec | $0.3707 / sec | +40% |
| [Kling V3 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-pro-image-to-video) | video | $0.1045 / sec | $0.1467 / sec | +40% |
| [Kling O3 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-o3-pro-image-to-video) | video | $0.08738 / sec | $0.1227 / sec | +40% |
| [Kling V3 Turbo Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.08738 / sec | $0.1227 / sec | +40% |
| [Kling O3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-o3-standard-image-to-video) | video | $0.07028 / sec | $0.09867 / sec | +40% |
| [Kling V3 Turbo Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-standard-image-to-video) | video | $0.07028 / sec | $0.09867 / sec | +40% |
| [NVIDIA Nemotron 3 Nano 30B](https://uberllm.dev/models/nvidia/nemotron-3-nano-30b-a3b) | text | $0.0285 / $0.114 | $0.0405 / $0.162 | +42% |
| [Gemini 3.5 Flash](https://uberllm.dev/models/google/gemini-3.5-flash) | text | $0.03 / $0.18 | $0.045 / $0.27 | +50% |
| [Hailuo 02 Standard Text to Video](https://uberllm.dev/models/minimax/hailuo-02-standard-text-to-video) | video | $0.025 / sec | $0.03814 / sec | +53% |
| [xAI Speech to Text v1 (Venice)](https://uberllm.dev/models/venice/xai-stt-v1) | transcription | $0.00085 / minute | $0.001322 / minute | +56% |
| [Qwen Image 3 Pro (Venice)](https://uberllm.dev/models/venice/qwen-image-3-pro) | image | $0.032 / image | $0.05 / image | +56% |
| [Seedance 2.0 Text-to-Video](https://uberllm.dev/models/bytedance/seedance-2-0-text-to-video) | video | $0.1083 / sec | $0.171 / sec | +58% |
| [Gemma 4 31B](https://uberllm.dev/models/google/gemma-4-31b) | text | $0.0168 / $0.0504 | $0.02682 / $0.08046 | +60% |
| [LTX 2 v2.3 Full Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.05035 / sec | $0.08392 / sec | +67% |
| [Kling O3 Pro Text-to-Video](https://uberllm.dev/models/kling/kling-o3-pro-text-to-video) | video | $0.0874 / sec | $0.1457 / sec | +67% |
| [Kling O3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-o3-4k-text-to-video) | video | $0.2641 / sec | $0.4402 / sec | +67% |
| [Topaz Video Upscale](https://uberllm.dev/models/topaz-labs/topaz-video-upscale) | video | $0.0855 / video | $0.1425 / video | +67% |
| [Seedance 2.0 Mini (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-image-to-video) | video | $0.02508 / sec | $0.0418 / sec | +67% |
| [Seedance 2.0 Mini (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-reference-to-video) | video | $0.02508 / sec | $0.0418 / sec | +67% |
| [Happyhorse 1.0 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.08738 / sec | $0.1456 / sec | +67% |
| [Happyhorse 1.1 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.08738 / sec | $0.1456 / sec | +67% |
| [Happyhorse 1.1 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-reference-to-video) | video | $0.08738 / sec | $0.1456 / sec | +67% |
| [Wan 2.7 (reference-to-video)](https://uberllm.dev/models/wan/wan-2-7-reference-to-video) | video | $0.0627 / sec | $0.1045 / sec | +67% |
| [Seedance 2.0 Fast (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-reference-to-video) | video | $0.0399 / sec | $0.0665 / sec | +67% |
| [Kling V3 Standard Text-to-Video](https://uberllm.dev/models/kling/kling-v3-standard-text-to-video) | video | $0.07866 / sec | $0.1311 / sec | +67% |
| [Qwen Image 3 (Venice)](https://uberllm.dev/models/venice/qwen-image-3) | image | $0.024 / image | $0.04 / image | +67% |
| [Wan 2.6 Text-to-Video](https://uberllm.dev/models/wan/wan-2-6-text-to-video) | video | $0.09462 / sec | $0.1577 / sec | +67% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.03802 / sec | $0.06337 / sec | +67% |
| [LTX 2 v2.3 Fast Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.038 / sec | $0.06333 / sec | +67% |
| [Seedream V5 Pro (image-to-image)](https://uberllm.dev/models/bytedance/seedream-v5-pro-edit) | image | $0.035 / image | $0.06 / image | +71% |
| [Seedream V5 Pro (Venice)](https://uberllm.dev/models/bytedance/venice-seedream-v5-pro) | image | $0.035 / image | $0.06 / image | +71% |
| [Gemma 4 31B IT](https://uberllm.dev/models/google/gemma-4-31b-it) | text | $0.0324 / $0.0972 | $0.0564 / $0.1692 | +74% |
| [Gemini 3.1 Pro](https://uberllm.dev/models/google/gemini-3.1-pro) | text | $1.10 / $6.60 | $1.92 / $11.52 | +75% |
| [Mistral Large 3](https://uberllm.dev/models/mistralai/mistral-large-3) | text | $0.1247 / $0.3743 | $0.25 / $0.75 | +100% |
| [Qwen: Qwen3.8 Omni Flash](https://uberllm.dev/models/qwen/qwen3.8-omni-flash) | text | $0.006 / $0.0188 | $0.0135 / $0.0423 | +125% |
| [Seedream 4.5](https://uberllm.dev/models/bytedance/seedream-4.5) | image | $0.01 / image | $0.0232 / image | +132% |
| [GPT Image 2.5 Sunburst (Venice)](https://uberllm.dev/models/openai/venice-gpt-image-2-5-sunburst) | image | $0.03 / image | $0.07 / image | +133% |
| [Recraft V4 Pro (Venice)](https://uberllm.dev/models/venice/recraft-v4-pro) | image | $0.0725 / image | $0.174 / image | +140% |
| [MoonshotAI: Kimi K3.1 Pro](https://uberllm.dev/models/moonshotai/kimi-k3.1-pro) | text | $0.03325 / $1.18 | $0.08 / $2.83 | +141% |
| [Z.ai: GLM 5.3 Prime](https://uberllm.dev/models/z-ai/glm-5.3-prime) | text | $0.196 / $0.616 | $0.476 / $1.50 | +143% |
| [Gemma 4 E2B](https://uberllm.dev/models/google/gemma-4-e2b) | text | $0.0036 / $0.0072 | $0.0092 / $0.0184 | +156% |
| [GLM 5.3](https://uberllm.dev/models/z-ai/glm-5.3) | text | $0.002796 / $0.056 | $0.00336 / $0.144 | in +20% / out +157% |
| [GPT Image 2.5 Flare (image-to-image)](https://uberllm.dev/models/openai/gpt-image-2-5-flare-edit) | image | $0.03 / image | $0.08 / image | +167% |
| [GPT Image 2.5 Sunburst (image-to-image)](https://uberllm.dev/models/openai/gpt-image-2-5-sunburst-edit) | image | $0.03 / image | $0.08 / image | +167% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.0144 / $0.018 | $0.01606 / $0.05355 | in +12% / out +198% |
| [Nano Banana 2 Lite (Venice)](https://uberllm.dev/models/google/venice-nano-banana-2-lite) | image | $0.02 / image | $0.06 / image | +200% |
| [GLM 4.5](https://uberllm.dev/models/z-ai/glm-4.5) | text | $0.012 / $0.044 | $0.036 / $0.132 | +200% |
| [Flux 2 Pro (Venice)](https://uberllm.dev/models/venice/flux-2-pro) | image | $0.0018 / image | $0.006 / image | +233% |
| [Qwen3.5 Flash](https://uberllm.dev/models/qwen/qwen3.5-flash) | text | $0.025 / $0.10 | $0.096 / $0.384 | +284% |
| [Qwen3.5 Plus](https://uberllm.dev/models/qwen/qwen3.5-plus) | text | $0.065 / $0.39 | $0.2496 / $1.50 | +284% |
| [Qwen: Qwen3.8 Max (0902)](https://uberllm.dev/models/qwen/qwen3.8-max-0902) | text | $0.02 / $0.06 | $0.08 / $0.24 | +300% |
| [Grok Imagine 2.0 (image-to-image)](https://uberllm.dev/models/x-ai/grok-imagine-image-2-0-edit) | image | $0.02 / image | $0.0815 / image | +308% |
| [GPT Image 2 (Venice)](https://uberllm.dev/models/venice/gpt-image-2) | image | $0.03 / image | $0.135 / image | +350% |
| [Nano Banana 2.1 (image-to-image)](https://uberllm.dev/models/google/nano-banana-2-1-edit) | image | $0.02 / image | $0.10 / image | +400% |
| [Nano Banana 2.1 (Venice)](https://uberllm.dev/models/google/venice-nano-banana-2-1) | image | $0.02 / image | $0.10 / image | +400% |
| [MiniMax M2.7 Highspeed](https://uberllm.dev/models/minimax/minimax-m2.7-highspeed) | text | $0.03 / $0.12 | $0.576 / $2.30 | +1820% |
| [GLM 4.5 Air](https://uberllm.dev/models/z-ai/glm-4.5-air) | text | $0.002 / $0.011 | $0.14 / $0.77 | +6900% |

</details>


## 2026-11-12 (vs 2026-11-12)

**Official list price changes (3)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Seedance 2.0 Mini (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-image-to-video) | video | – | $0.044 / sec |  |
| [GLM 5.1 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5.1) | text | $1.33 / $4.18 | $1.40 / $4.40 | +5% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | text | $1.33 / $4.18 | $1.40 / $4.40 | +5% |

**New models (2)**

| Model | Category | Official price | UberLLM price |
|---|---|---|---|
| [Seedance 2.0 Mini (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-reference-to-video) | video | $0.044 / sec | $0.02508 / sec |
| [Inception: Mercury 2.5](https://uberllm.dev/models/inception/mercury-2.5) | text | – | $0.028 / $0.105 |

**No longer listed (24)**: `deepseek/deepseek-v4-flash:web`, `deepseek/deepseek-v4-pro:web`, `google/gemma-4-26b-a4b-it:web`, `google/gemma-4-31b-it:web`, `google/veo3-1-full-image-to-video`, `meta-llama/hermes-3-llama-3.1-405b:web`, `meta-llama/llama-3.2-3b-instruct:web`, `meta-llama/llama-3.3-70b-instruct:web`, `minimax/minimax-m2.5:web`, `mistralai/mistral-small-3.2-24b-instruct:web`, `moonshotai/kimi-k2.5:web`, `moonshotai/kimi-k2.6:web`, `moonshotai/kimi-k2.7-code:web`, `openai/gpt-oss-120b:web`, `pixverse/pixverse-c1-image-to-video`, `pixverse/pixverse-v5-6-image-to-video`, `pixverse/pixverse-v5-6-transition`, `qwen/qwen3-235b-a22b-2507:web`, `qwen/qwen3-next-80b-a3b-instruct:web`, `z-ai/glm-5.1-non-thinking`, `z-ai/glm-5.1-non-thinking:web`, `z-ai/glm-5.1:web`, `z-ai/glm-5.2:web`, `z-ai/glm-5:web`

<details><summary>UberLLM price moves of 10% or more (278)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Ministral 3B](https://uberllm.dev/models/mistralai/ministral-3-3b-instruct) | text | $0.025 / $0.025 | $0.002 / $0.002 | −92% |
| [Flux 2 Pro (Venice)](https://uberllm.dev/models/venice/flux-2-pro) | image | $0.0075 / image | $0.0018 / image | −76% |
| [Recraft V4 Pro (Venice)](https://uberllm.dev/models/venice/recraft-v4-pro) | image | $0.174 / image | $0.0725 / image | −58% |
| [ElevenLabs Scribe v2 (STT)](https://uberllm.dev/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.007977 / minute | $0.00501 / minute | −37% |
| [Seedance 2.0 Fast (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-reference-to-video) | video | $0.063 / sec | $0.0399 / sec | −37% |
| [Happyhorse 1.0 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.138 / sec | $0.08738 / sec | −37% |
| [Kling V3 Pro Text-to-Video](https://uberllm.dev/models/kling/kling-v3-pro-text-to-video) | video | $0.165 / sec | $0.1045 / sec | −37% |
| [Kling V3 Standard Text-to-Video](https://uberllm.dev/models/kling/kling-v3-standard-text-to-video) | video | $0.1242 / sec | $0.07866 / sec | −37% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.06003 / sec | $0.03802 / sec | −37% |
| [Kling V3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-v3-4k-text-to-video) | video | $0.417 / sec | $0.2641 / sec | −37% |
| [Chroma (Venice)](https://uberllm.dev/models/venice/chroma) | image | $0.008 / image | $0.0055 / image | −31% |
| [Whisper Large V3 (Venice)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.004311 / minute | $0.002997 / minute | −30% |
| [Wan 2.7 (Venice)](https://uberllm.dev/models/venice/wan-2.7) | image | $0.024 / image | $0.01688 / image | −30% |
| [Wan 2.7 Pro (Venice)](https://uberllm.dev/models/venice/wan-2.7-pro) | image | $0.06 / image | $0.04219 / image | −30% |
| [Kling V3 Turbo Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.1227 / sec | $0.08738 / sec | −29% |
| [Kling V3 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-pro-image-to-video) | video | $0.1467 / sec | $0.1045 / sec | −29% |
| [Kling V3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-v3-4k-reference-to-video) | video | $0.3707 / sec | $0.2641 / sec | −29% |
| [LTX 2 v2.3 Fast Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.05333 / sec | $0.038 / sec | −29% |
| [Kling V3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-standard-image-to-video) | video | $0.112 / sec | $0.0798 / sec | −29% |
| [Kling V3 Turbo Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-standard-image-to-video) | video | $0.09864 / sec | $0.07028 / sec | −29% |
| [Kling O3.4k (image-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-image-to-video) | video | $0.3706 / sec | $0.2641 / sec | −29% |
| [Kling O3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-reference-to-video) | video | $0.3706 / sec | $0.2641 / sec | −29% |
| [Ltx 2 V2.3 Full (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.07064 / sec | $0.05033 / sec | −29% |
| [Firered Image (image-to-image)](https://uberllm.dev/models/xiaohongshu/firered-image-edit) | image | $0.032 / image | $0.0228 / image | −29% |
| [Kling O3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-o3-4k-text-to-video) | video | $0.3707 / sec | $0.2641 / sec | −29% |
| [LTX 2 v2.3 Full Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.07067 / sec | $0.05035 / sec | −29% |
| [ElevenLabs Music (Venice)](https://uberllm.dev/models/venice/elevenlabs-music) | music | $0.6279 / track | $0.4485 / track | −29% |
| [Qwen3 VL 235B A22B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-instruct) | text | $0.0525 / $0.475 | $0.0378 / $0.342 | −28% |
| [Seedance 2.0 (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-reference-to-video) | video | $0.06864 / sec | $0.05016 / sec | −27% |
| [Qwen Image 2 Pro (image-to-image)](https://uberllm.dev/models/qwen/qwen-image-2-pro-edit) | image | $0.075 / image | $0.057 / image | −24% |
| [Happyhorse 1.1 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.1125 / sec | $0.08738 / sec | −22% |
| [Happyhorse 1.1 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-reference-to-video) | video | $0.1125 / sec | $0.08738 / sec | −22% |
| [Wan 2.7 (reference-to-video)](https://uberllm.dev/models/wan/wan-2-7-reference-to-video) | video | $0.08 / sec | $0.0627 / sec | −22% |
| [Wan 2.7 Text-to-Video](https://uberllm.dev/models/wan/wan-2-7-text-to-video) | video | $0.08 / sec | $0.0627 / sec | −22% |
| [Gemini 3.1 Flash TTS](https://uberllm.dev/models/google/tts-gemini-3-1-flash) | speech | $0.15 / 1K chars | $0.1219 / 1K chars | −19% |
| [Qwen3 1.7B TTS](https://uberllm.dev/models/qwen/tts-qwen3-1-7b) | speech | $0.09 / 1K chars | $0.07312 / 1K chars | −19% |
| [Seedance 2.0 Fast (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-image-to-video) | video | $0.049 / sec | $0.0399 / sec | −19% |
| [Seedance 2.0 (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-image-to-video) | video | $0.0616 / sec | $0.05016 / sec | −19% |
| [Happyhorse 1.0 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-image-to-video) | video | $0.1073 / sec | $0.08738 / sec | −19% |
| [Wan 2.7 (image-to-video)](https://uberllm.dev/models/wan/wan-2-7-image-to-video) | video | $0.077 / sec | $0.0627 / sec | −19% |
| [Sakana: Sakana Namazu](https://uberllm.dev/models/sakana/sakana-namazu) | text | $0.95 / $4.00 | $0.817 / $3.44 | −14% |
| [Gemini Omni Flash (reference-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-reference-to-video) | video | $0.114 / sec | $0.09975 / sec | −12% |
| [Luma Uni 1 (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-edit) | image | $0.048 / image | $0.042 / image | −12% |
| [Luma Uni 1 Max (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-max-edit) | image | $0.104 / image | $0.091 / image | −12% |
| [Longcat (image-to-video)](https://uberllm.dev/models/meituan/longcat-image-to-video) | video | $0.04 / sec | $0.035 / sec | −12% |
| [LongCat Text-to-Video](https://uberllm.dev/models/meituan/longcat-text-to-video) | video | $0.04 / sec | $0.035 / sec | −12% |
| [Wan 2.7 Pro (image-to-image)](https://uberllm.dev/models/wan/wan-2-7-pro-edit) | image | $0.06 / image | $0.05358 / image | −11% |
| [Wan 2.6 (image-to-video)](https://uberllm.dev/models/wan/wan-2-6-image-to-video) | video | $0.07 / sec | $0.0627 / sec | −10% |
| [GLM 4.7 Flash](https://uberllm.dev/models/z-ai/glm-4.7-flash) | text | $0.01815 / $0.12 | $0.01633 / $0.108 | −10% |
| [Grok Build 0.1](https://uberllm.dev/models/x-ai/grok-build-0.1) | text | $0.60 / $1.20 | $0.66 / $1.32 | +10% |
| [Claude Opus 4.8 Fast](https://uberllm.dev/models/anthropic/claude-opus-4.8-fast) | text | $5.69 / $28.47 | $6.30 / $31.50 | +11% |
| [Mercury 2](https://uberllm.dev/models/inception/mercury-2) | text | $0.1975 / $0.5925 | $0.2188 / $0.6562 | +11% |
| [Whisper 1 (Venice, legacy alias)](https://uberllm.dev/models/venice/whisper-1) | transcription | $0.004311 / minute | $0.0048 / minute | +11% |
| [Seed 2.1 Turbo](https://uberllm.dev/models/bytedance/seed-2-1-turbo) | text | $0.25 / $1.25 | $0.28 / $1.40 | +12% |
| [Qwen 2.5 7B](https://uberllm.dev/models/qwen/e2ee-qwen-2-5-7b-p) | text | $0.02498 / $0.06494 | $0.028 / $0.0728 | +12% |
| [Seedance 2.0 Text-to-Video](https://uberllm.dev/models/bytedance/seedance-2-0-text-to-video) | video | $0.095 / sec | $0.1083 / sec | +14% |
| [Seedream v4 — Edit (Venice)](https://uberllm.dev/models/bytedance/seedream-v4-edit) | image | $0.025 / image | $0.0285 / image | +14% |
| [Venice SD35](https://uberllm.dev/models/venice/sd35) | image | $0.007 / image | $0.008 / image | +14% |
| [Kimi K3 Fast](https://uberllm.dev/models/moonshotai/kimi-k3-fast-api) | text | $2.70 / $13.50 | $3.10 / $15.53 | +15% |
| [Qwen 3.5 35B A3B](https://uberllm.dev/models/qwen/qwen3.5-35b-a3b) | text | $0.08991 / $0.5994 | $0.1035 / $0.69 | +15% |
| [GPT-5.2](https://uberllm.dev/models/openai/gpt-5.2) | text | $0.3432 / $2.75 | $0.4025 / $3.22 | +17% |
| [Qwen 3.6 35B A3B (E2EE)](https://uberllm.dev/models/qwen/e2ee-qwen3-6-35b-a3b) | text | $0.091 / $0.59 | $0.1074 / $0.6962 | +18% |
| [GPT OSS 120B](https://uberllm.dev/models/openai/e2ee-gpt-oss-120b-p) | text | $0.06494 / $0.3247 | $0.0767 / $0.3835 | +18% |
| [Qwen3 VL 235B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-thinking) | text | $0.1049 / $0.949 | $0.126 / $1.14 | +20% |
| [GLM 5.2 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5-2-p) | text | $0.8741 / $2.87 | $1.05 / $3.45 | +20% |
| [Meta: Muse Spark Open](https://uberllm.dev/models/meta-llama/muse-spark-open) | text | $0.6473 / $2.20 | $0.7875 / $2.68 | +22% |
| [GPT-6 Luna Decisions (OpenAI)](https://uberllm.dev/models/openai/gpt-6-luna-decisions) | other | $0.06881 / $0 | $0.085 / $0 | in +24% / out – |
| [GPT 5 Mini](https://uberllm.dev/models/openai/gpt-5-mini) | text | $0.06058 / $0.4847 | $0.075 / $0.60 | +24% |
| [Gemma 3 27B E2EE](https://uberllm.dev/models/google/e2ee-gemma-3-27b) | text | $0.056 / $0.20 | $0.07 / $0.25 | +25% |
| [Gemma 4 31B (E2EE)](https://uberllm.dev/models/google/e2ee-gemma-4-31b) | text | $0.10 / $0.30 | $0.125 / $0.375 | +25% |
| [NVIDIA Nemotron 3.5 Lightning 30B](https://uberllm.dev/models/nvidia/nemotron-3-5-lightning-30b-a3b) | text | $0.064 / $0.16 | $0.07 / $0.20 | in +9% / out +25% |
| [GLM 5.1 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5.1) | text | $0.44 / $1.66 | $0.55 / $2.08 | +25% |
| [Gemini Omni Flash (image-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-image-to-video) | video | $0.07875 / sec | $0.09975 / sec | +27% |
| [Seedream V5 Lite (Venice)](https://uberllm.dev/models/venice/seedream-v5-lite) | image | $0.0275 / image | $0.035 / image | +27% |
| [Kling 2.5 Turbo Pro (image-to-video)](https://uberllm.dev/models/kling/kling-2-5-turbo-pro-image-to-video) | video | $0.042 / sec | $0.0546 / sec | +30% |
| [Kling 2.5 Turbo Pro Text-to-Video](https://uberllm.dev/models/kling/kling-2-5-turbo-pro-text-to-video) | video | $0.042 / sec | $0.0546 / sec | +30% |
| [Kimi K2](https://uberllm.dev/models/moonshotai/kimi-k2) | text | $0.342 / $1.38 | $0.4446 / $1.79 | +30% |
| [NVIDIA: Nemotron 3.5 Super VL](https://uberllm.dev/models/nvidia/nemotron-3.5-super-vl) | text | $0.09 / $0.282 | $0.117 / $0.3666 | +30% |
| [Seedance 2.0 Mini (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-image-to-video) | video | $0.019 / sec | $0.02508 / sec | +32% |
| [MiMo-V2.5](https://uberllm.dev/models/xiaomi/mimo-v2-5) | text | $0.24 / $1.20 | $0.32 / $1.60 | +33% |
| [Grok Imagine (Venice)](https://uberllm.dev/models/venice/grok-imagine) | image | $0.015 / image | $0.02 / image | +33% |
| [Wan 2.6 Text-to-Video](https://uberllm.dev/models/wan/wan-2-6-text-to-video) | video | $0.07 / sec | $0.09462 / sec | +35% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.009 / sec | $0.0126 / sec | +40% |
| [Seedream V4.5 (Venice)](https://uberllm.dev/models/venice/seedream-v4) | image | $0.025 / image | $0.035 / image | +40% |
| [Z.ai: GLM 5.3 FlashX Legal](https://uberllm.dev/models/z-ai/glm-5.3-flashx-legal) | text | $0.222 / $0.75 | $0.3108 / $1.05 | +40% |
| [Qwen Image 2 (Venice)](https://uberllm.dev/models/venice/qwen-image-2) | image | $0.028 / image | $0.04 / image | +43% |
| [Trinity Large Thinking](https://uberllm.dev/models/arcee-ai/trinity-large-thinking) | text | $0.2094 / $0.7538 | $0.30 / $1.00 | in +43% / out +33% |
| [Moondream: Moondream 3 Preview](https://uberllm.dev/models/moondream/moondream3-preview) | text | $0.18 / $1.50 | $0.267 / $2.23 | +48% |
| [NVIDIA Nemotron 3 Ultra 550B](https://uberllm.dev/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.07512 / $0.3756 | $0.1125 / $0.5625 | +50% |
| [Moondream: Moondream 3.1](https://uberllm.dev/models/moondream/moondream3.1-9b-a2b) | text | $0.18 / $1.50 | $0.27 / $2.25 | +50% |
| [Cohere: Command A+](https://uberllm.dev/models/cohere/command-a-plus) | text | $0.18 / $0.90 | $0.276 / $1.38 | +53% |
| [Particle AI: Particle-1](https://uberllm.dev/models/particle-ai/particle-1) | text | $0.03 / $0.30 | $0.0465 / $0.465 | +55% |
| [Qwen3 30B A3B](https://uberllm.dev/models/qwen/qwen3-30b-a3b) | text | $0.072 / $0.30 | $0.1128 / $0.47 | +57% |
| [Reflection: Beam 1.0 501B A23B](https://uberllm.dev/models/reflection/beam-1.0-501b-a23b) | text | $0.18 / $0.60 | $0.282 / $0.94 | +57% |
| [LiquidAI: LFM2.5-24B-A2B](https://uberllm.dev/models/liquid/lfm-2.5-24b-a2b) | text | $0.03 / $0.42 | $0.047 / $0.658 | +57% |
| [MiMo-V2.6-Pro-UltraSpeed](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro-ultraspeed) | text | $2.61 / $5.22 | $4.09 / $8.18 | +57% |
| [GPT-5.6 Terra Pro](https://uberllm.dev/models/openai/gpt-5.6-terra-pro) | text | $0.84 / $5.04 | $1.32 / $7.92 | +57% |
| [JEV 1.13 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.13) | other | $0.0252 / $0 | $0.0399 / $0 | in +58% / out – |
| [GPT-5.6 Luna Pro](https://uberllm.dev/models/openai/gpt-5.6-luna-pro) | text | $0.084 / $0.504 | $0.134 / $0.804 | +60% |
| [Kling 2.6 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-2-6-pro-image-to-video) | video | $0.055 / sec | $0.08778 / sec | +60% |
| [Kling 2.6 Pro Text-to-Video](https://uberllm.dev/models/kling/kling-2-6-pro-text-to-video) | video | $0.055 / sec | $0.08778 / sec | +60% |
| [Hunyuan Image 3.0 (Venice)](https://uberllm.dev/models/venice/hunyuan-image-v3) | image | $0.045 / image | $0.072 / image | +60% |
| [Qwen Image (Venice)](https://uberllm.dev/models/venice/qwen-image) | image | $0.015 / image | $0.024 / image | +60% |
| [MiMo-V2.5-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.5-pro) | text | $0.288 / $1.08 | $0.4608 / $1.73 | +60% |
| [MiniMax M3 Preview](https://uberllm.dev/models/minimax/minimax-m3-preview) | text | $0.12 / $0.4799 | $0.192 / $0.768 | +60% |
| [Elorian: Glimpse](https://uberllm.dev/models/elorian/glimpse) | text | $0.36 / $1.80 | $0.582 / $2.91 | +62% |
| [Sakana: Fugu Max](https://uberllm.dev/models/sakana/fugu-max) | text | $1.20 / $3.60 | $1.94 / $5.82 | +62% |
| [Sakana: Fugu Ultra v2](https://uberllm.dev/models/sakana/fugu-ultra-v2) | text | $3.00 / $18.00 | $4.85 / $29.10 | +62% |
| [JEV 1.14 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.14) | other | $0.0252 / $0 | $0.04074 / $0 | in +62% / out – |
| [Qwen: Qwen3.8 Max Prime](https://uberllm.dev/models/qwen/qwen3.8-max-prime) | text | $2.40 / $7.20 | $3.92 / $11.76 | +63% |
| [Pareto 26.9](https://uberllm.dev/models/unbiased/pareto-26.9) | text | $1.50 / $4.50 | $2.48 / $7.42 | +65% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://uberllm.dev/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.264 / $0.792 | $0.44 / $1.32 | +67% |
| [inclusionAI: Ling 3.1 Flash](https://uberllm.dev/models/inclusionai/ling-3.1-flash) | text | $0.027 / $0.081 | $0.045 / $0.135 | +67% |
| [Fireworks: Ember-1](https://uberllm.dev/models/fireworks/ember-1) | text | $1.80 / $9.00 | $3.00 / $15.00 | +67% |
| [Llama 3.2 3B](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct) | text | $0.025 / $0.165 | $0.0425 / $0.2805 | +70% |
| [Qwen3.7 Max](https://uberllm.dev/models/qwen/qwen3.7-max) | text | $1.00 / $3.00 | $1.70 / $5.07 | in +70% / out +69% |
| [Claude Sonnet 4.5](https://uberllm.dev/models/anthropic/claude-sonnet-4.5) | text | $1.18 / $5.92 | $2.04 / $10.20 | +72% |
| [GPT-5.4 Mini](https://uberllm.dev/models/openai/gpt-5.4-mini) | text | $0.07493 / $0.4496 | $0.135 / $0.81 | +80% |
| [GLM 5.3 Flash](https://uberllm.dev/models/z-ai/glm-5.3-flash) | text | $0.0015 / $0.005 | $0.002793 / $0.005488 | in +86% / out +10% |
| [GPT-5.6 Sol Pro](https://uberllm.dev/models/openai/gpt-5.6-sol-pro) | text | $1.58 / $7.90 | $2.96 / $14.80 | +87% |
| [Nano Banana Pro (image-to-image)](https://uberllm.dev/models/google/nano-banana-pro-edit) | image | $0.09 / image | $0.171 / image | +90% |
| [Qwen 3 Coder 480B Turbo](https://uberllm.dev/models/qwen/qwen3-coder-turbo) | text | $0.1153 / $0.4943 | $0.2205 / $0.945 | +91% |
| [Wan 2.6 Flash Image-to-Video](https://uberllm.dev/models/wan/wan-2-6-flash-image-to-video) | video | $0.02 / sec | $0.0392 / sec | +96% |
| [Z-Image Turbo (Venice)](https://uberllm.dev/models/venice/z-image-turbo) | image | $0.004 / image | $0.0079 / image | +98% |
| [Gemini 2.5 Flash](https://uberllm.dev/models/google/gemini-2.5-flash) | text | $0.0015 / $0.0125 | $0.003 / $0.025 | +100% |
| [Nano Banana (Gemini 2.5 Flash Image)](https://uberllm.dev/models/google/gemini-2.5-flash-image) | image | $0.0015 / $0.0125 | $0.003 / $0.025 | +100% |
| [Nano Banana 2 (image-to-image)](https://uberllm.dev/models/google/nano-banana-2-edit) | image | $0.04 / image | $0.08 / image | +100% |
| [GPT OSS 20B](https://uberllm.dev/models/openai/e2ee-gpt-oss-20b-p) | text | $0.0125 / $0.0475 | $0.025 / $0.095 | +100% |
| [NVIDIA Nemotron Nano 12B v2 VL BF16](https://uberllm.dev/models/nvidia/nemotron-nano-12b-v2) | text | $0.001995 / $0.005985 | $0.004 / $0.012 | +101% |
| [Qwen 3.8 Max](https://uberllm.dev/models/qwen/qwen-3-8-max) | text | $0.1114 / $0.3341 | $0.225 / $0.675 | +102% |
| [GLM 4.5](https://uberllm.dev/models/z-ai/glm-4.5) | text | $0.00588 / $0.02156 | $0.012 / $0.044 | +104% |
| [GPT-5.3 Codex](https://uberllm.dev/models/openai/gpt-5.3-codex) | text | $0.4051 / $3.24 | $0.84 / $6.72 | +107% |
| [Meta: Muse Spark 1.2 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.2-contributor) | text | $0.03 / $0.06 | $0.063 / $0.126 | +110% |
| [Meta: Muse Spark 1.3 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.3-contributor) | text | $0.02 / $0.04 | $0.042 / $0.084 | +110% |
| [Gemini 3.5 Flash Lite](https://uberllm.dev/models/google/gemini-3-5-flash-lite) | text | $0.087 / $0.725 | $0.183 / $1.52 | +110% |
| [Mistral Small 4](https://uberllm.dev/models/mistralai/mistral-small-4) | text | $0.04688 / $0.1875 | $0.099 / $0.396 | +111% |
| [Z.ai: GLM 5.3 FlashX](https://uberllm.dev/models/z-ai/glm-5.3-flashx) | text | $0.1036 / $0.35 | $0.2257 / $0.7625 | +118% |
| [GPT-5.5](https://uberllm.dev/models/openai/gpt-5.5) | text | $1.31 / $7.84 | $2.85 / $17.10 | +118% |
| [Qwen3 VL 30B A3B](https://uberllm.dev/models/qwen/qwen3-vl-30b-a3b-thinking) | text | $0.10 / $0.45 | $0.225 / $0.81 | in +125% / out +80% |
| [GPT 5 Nano](https://uberllm.dev/models/openai/gpt-5-nano) | text | $0.007499 / $0.05999 | $0.017 / $0.136 | +127% |
| [Flux 2 Max (Venice)](https://uberllm.dev/models/venice/flux-2-max) | image | $0.0225 / image | $0.0522 / image | +132% |
| [GPT-4o Mini](https://uberllm.dev/models/openai/gpt-4o-mini) | text | $0.009 / $0.036 | $0.021 / $0.084 | +133% |
| [Gemini 3.6 Flash](https://uberllm.dev/models/google/gemini-3-6-flash) | text | $0.2175 / $1.09 | $0.51 / $2.55 | +134% |
| [Claude Opus 5 (Fast)](https://uberllm.dev/models/anthropic/claude-opus-5-fast) | text | $2.50 / $12.49 | $5.90 / $29.50 | +136% |
| [Nano Banana 2 Lite (image-to-image)](https://uberllm.dev/models/google/nano-banana-2-lite-edit) | image | $0.02 / image | $0.048 / image | +140% |
| [Claude Fable 5.2](https://uberllm.dev/models/anthropic/claude-fable-5.2) | text | $1.96 / $9.82 | $4.96 / $24.80 | +153% |
| [Qwen 3.5 9B](https://uberllm.dev/models/qwen/qwen3.5-9b) | text | $0.025 / $0.075 | $0.07 / $0.105 | in +180% / out +40% |
| [Meta: Muse Spark 1.1](https://uberllm.dev/models/meta-llama/muse-spark-1.1) | text | $0.375 / $1.27 | $1.06 / $3.61 | +183% |
| [Gemini 2.5 Pro](https://uberllm.dev/models/google/gemini-2.5-pro) | text | $0.1576 / $1.26 | $0.45 / $3.60 | +185% |
| [Google: Gemini 4 Carbon](https://uberllm.dev/models/google/gemini-4-carbon) | text | $0.3792 / $1.90 | $1.22 / $6.10 | +222% |
| [GPT-5.4](https://uberllm.dev/models/openai/gpt-5.4) | text | $0.4753 / $2.85 | $1.55 / $9.30 | +226% |
| [MiniMax M3](https://uberllm.dev/models/minimax/minimax-m3) | text | $0.01239 / $0.04958 | $0.042 / $0.168 | +239% |
| [Gemini 3.1 Pro Preview](https://uberllm.dev/models/google/gemini-3.1-pro-preview) | text | $0.1062 / $0.6371 | $0.36 / $2.16 | +239% |
| [Tencent: Hy4](https://uberllm.dev/models/tencent/hy4) | text | $0.1021 / $0.306 | $0.3503 / $1.05 | +243% |
| [Mistral Small 3.2 24B Instruct](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.0135 / $0.036 | $0.04784 / $0.1275 | +254% |
| [GPT-5.2 Codex](https://uberllm.dev/models/openai/gpt-5.2-codex) | text | $0.4375 / $3.50 | $1.57 / $12.60 | +260% |
| [Grok 4.20 Beta](https://uberllm.dev/models/x-ai/grok-4.20-beta) | text | $0.175 / $0.35 | $0.6375 / $1.27 | +264% |
| [MiMo-V2.6-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro) | text | $0.08248 / $0.165 | $0.3175 / $0.6351 | +285% |
| [DeepSeek V4.1 Flash](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash) | text | $0.002491 / $0.0277 | $0.00594 / $0.108 | in +138% / out +290% |
| [GPT-5.5 Pro](https://uberllm.dev/models/openai/gpt-5.5-pro) | text | $7.22 / $43.35 | $28.50 / $171.00 | +294% |
| [GPT-5 Image](https://uberllm.dev/models/openai/gpt-5-image) | image | $2.50 / $2.50 | $9.90 / $9.90 | +296% |
| [GPT-5 Image Mini](https://uberllm.dev/models/openai/gpt-5-image-mini) | image | $0.625 / $0.50 | $2.48 / $1.98 | +296% |
| [Gemini 3.5 Flash](https://uberllm.dev/models/google/gemini-3.5-flash) | text | $0.0075 / $0.045 | $0.03 / $0.18 | +300% |
| [GLM 5.3](https://uberllm.dev/models/z-ai/glm-5.3) | text | $0.000669 / $0.0134 | $0.002796 / $0.056 | +318% |
| [GPT-5.4 Pro](https://uberllm.dev/models/openai/gpt-5.4-pro) | text | $5.40 / $32.39 | $22.80 / $136.80 | +322% |
| [Grok 4.20 Multi-Agent Beta](https://uberllm.dev/models/x-ai/grok-4.20-multi-agent-beta) | text | $0.175 / $0.35 | $0.75 / $1.50 | +329% |
| [Kimi K2.6](https://uberllm.dev/models/moonshotai/kimi-k2.6) | text | $0.02083 / $0.1093 | $0.091 / $0.4774 | +337% |
| [Hermes 3 Llama 3.1 405b](https://uberllm.dev/models/nousresearch/hermes-3-llama-3.1-405b) | text | $0.50 / $0.50 | $0.85 / $2.32 | in +70% / out +364% |
| [GPT-4o](https://uberllm.dev/models/openai/gpt-4o) | text | $0.374 / $1.50 | $1.75 / $7.00 | +368% |
| [Meta: Muse Spark 1.3](https://uberllm.dev/models/meta-llama/muse-spark-1.3) | text | $0.1125 / $0.3825 | $0.55 / $1.87 | +389% |
| [Gemini 3.1 Pro](https://uberllm.dev/models/google/gemini-3.1-pro) | text | $0.2196 / $1.32 | $1.10 / $6.60 | +401% |
| [Mistral Large 3](https://uberllm.dev/models/mistralai/mistral-large-3) | text | $0.02475 / $0.07425 | $0.1247 / $0.3743 | +404% |
| [Claude Opus 4.7](https://uberllm.dev/models/anthropic/claude-opus-4.7) | text | $0.3675 / $1.84 | $1.90 / $9.50 | +417% |
| [Grok Imagine Text-to-Video](https://uberllm.dev/models/x-ai/grok-imagine-text-to-video) | video | $0.012 / sec | $0.0623 / sec | +419% |
| [Mistral: Mistral Large 4](https://uberllm.dev/models/mistralai/mistral-large-4-0) | text | $0.07 / $0.21 | $0.378 / $1.13 | +440% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | text | $0.1898 / $0.5695 | $1.04 / $3.12 | +448% |
| [MoonshotAI: Kimi K3.1 Pro](https://uberllm.dev/models/moonshotai/kimi-k3.1-pro) | text | $0.04231 / $0.2115 | $0.03325 / $1.18 | in −21% / out +457% |
| [Meta: Muse Wonder](https://uberllm.dev/models/meta-llama/muse-wonder) | text | $0.40 / $2.00 | $2.28 / $11.40 | +470% |
| [Claude Opus 4.5](https://uberllm.dev/models/anthropic/claude-opus-4.5) | text | $0.37 / $1.85 | $2.15 / $10.75 | +481% |
| [Claude Fable 5](https://uberllm.dev/models/anthropic/claude-fable-5) | text | $0.7376 / $3.69 | $4.30 / $21.50 | +483% |
| [DeepSeek V4 Flash](https://uberllm.dev/models/deepseek/deepseek-v4-flash) | text | $0.0091 / $0.0182 | $0.0531 / $0.1062 | +484% |
| [MiMo-V2.6-Flash](https://uberllm.dev/models/xiaomi/mimo-v2.6-flash) | text | $0.02096 / $0.04191 | $0.1246 / $0.2492 | +495% |
| [Claude Haiku 5.5](https://uberllm.dev/models/anthropic/claude-haiku-5.5) | text | $0.008 / $0.04 | $0.048 / $0.24 | +500% |
| [Gemini 3.1 Flash Lite](https://uberllm.dev/models/google/gemini-3.1-flash-lite) | text | $0.001248 / $0.007485 | $0.0075 / $0.045 | +501% |
| [Magistral Small 2509](https://uberllm.dev/models/mistralai/magistral-small-2509) | text | $0.004988 / $0.01496 | $0.03 / $0.09 | +501% |
| [Claude Fable 5.1](https://uberllm.dev/models/anthropic/claude-fable-5.1) | text | $0.67 / $3.35 | $4.10 / $20.50 | +512% |
| [Llama 3.3 70B Instruct](https://uberllm.dev/models/meta-llama/llama-3.3-70b-instruct) | text | $0.0147 / $0.04704 | $0.091 / $0.0923 | in +519% / out +96% |
| [Qwen3 Coder Next](https://uberllm.dev/models/qwen/qwen3-coder-next) | text | $0.0024 / $0.016 | $0.0156 / $0.104 | +550% |
| [Claude Opus 4.8](https://uberllm.dev/models/anthropic/claude-opus-4.8) | text | $0.2765 / $1.38 | $1.80 / $9.00 | +551% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.007403 / $0.02961 | $0.0495 / $0.198 | +569% |
| [Meta: Muse Spark 1.2](https://uberllm.dev/models/meta-llama/muse-spark-1.2) | text | $0.1125 / $0.3825 | $0.80 / $2.72 | +611% |
| [Gemini 3.7 Flash](https://uberllm.dev/models/google/gemini-3.7-flash) | text | $0.004117 / $0.02058 | $0.03 / $0.15 | +629% |
| [Qwen 3.6 27B](https://uberllm.dev/models/qwen/qwen3.6-27b) | text | $0.01435 / $0.1435 | $0.1056 / $1.06 | +636% |
| [Z.ai: GLM 5.3 Prime](https://uberllm.dev/models/z-ai/glm-5.3-prime) | text | $0.02526 / $0.07938 | $0.196 / $0.616 | +676% |
| [DeepSeek V4 Pro 0813](https://uberllm.dev/models/deepseek/deepseek-v4-pro-0813) | text | $0.00222 / $0.0888 | $0.01776 / $0.7104 | +700% |
| [MiniMax M2.5](https://uberllm.dev/models/minimax/minimax-m2.5) | text | $0.002621 / $0.009222 | $0.0216 / $0.076 | +724% |
| [GPT Image 2 — Edit (Venice)](https://uberllm.dev/models/venice/gpt-image-2-edit) | image | $0.03 / image | $0.252 / image | +740% |
| [GLM-5 Turbo](https://uberllm.dev/models/z-ai/glm-5-turbo) | text | $0.06 / $0.20 | $0.504 / $1.68 | +740% |
| [Qwen 3.6 35B A3B](https://uberllm.dev/models/qwen/qwen3-6-35b-a3b) | text | $0.004215 / $0.04215 | $0.037 / $0.37 | +778% |
| [Claude Opus 5.5](https://uberllm.dev/models/anthropic/claude-opus-5.5) | text | $0.136 / $0.68 | $1.20 / $6.00 | +782% |
| [Qwen: Qwen3.7 Flash](https://uberllm.dev/models/qwen/qwen3.7-flash) | text | $0.001216 / $0.005268 | $0.0108 / $0.0468 | +788% |
| [Kimi K3](https://uberllm.dev/models/moonshotai/kimi-k3) | text | $0.001286 / $0.1072 | $0.01152 / $0.96 | +796% |
| [Gemma 4 E2B](https://uberllm.dev/models/google/gemma-4-e2b) | text | $0.000399 / $0.000798 | $0.0036 / $0.0072 | +802% |
| [MiniMax M2](https://uberllm.dev/models/minimax/minimax-m2) | text | $0.002318 / $0.009271 | $0.021 / $0.084 | +806% |
| [Claude Haiku 4.5](https://uberllm.dev/models/anthropic/claude-haiku-4.5) | text | $0.0745 / $0.3725 | $0.69 / $3.45 | +826% |
| [Claude Sonnet 5](https://uberllm.dev/models/anthropic/claude-sonnet-5) | text | $0.088 / $0.44 | $0.82 / $4.10 | +832% |
| [Qwen: Qwen3.8 Max (0902)](https://uberllm.dev/models/qwen/qwen3.8-max-0902) | text | $0.0021 / $0.0063 | $0.02 / $0.06 | +852% |
| [Claude Sonnet 5.5](https://uberllm.dev/models/anthropic/claude-sonnet-5.5) | text | $0.07 / $0.35 | $0.68 / $3.40 | +871% |
| [Tencent: Hy4 preview](https://uberllm.dev/models/tencent/hy4-preview) | text | $0.06746 / $0.2023 | $0.6755 / $2.03 | +901% |
| [GPT-5.6 Terra](https://uberllm.dev/models/openai/gpt-5.6-terra) | text | $0.03996 / $0.2398 | $0.42 / $2.52 | +951% |
| [MiniMax M2.7](https://uberllm.dev/models/minimax/minimax-m2.7) | text | $0.01023 / $0.04091 | $0.1092 / $0.4368 | +968% |
| [GPT-6 Luna](https://uberllm.dev/models/openai/gpt-6-luna) | text | $0.004462 / $0.02231 | $0.052 / $0.26 | +1065% |
| [NVIDIA Nemotron Nano 9B v2](https://uberllm.dev/models/nvidia/nemotron-nano-9b-v2) | text | $0.001117 / $0.004281 | $0.0132 / $0.0506 | +1082% |
| [GPT-5.4 Image 2](https://uberllm.dev/models/openai/gpt-5.4-image-2) | image | $0.64 / $1.20 | $7.92 / $14.85 | +1138% |
| [Qwen3 32B](https://uberllm.dev/models/qwen/qwen3-32b) | text | $0.000792 / $0.002772 | $0.0104 / $0.0364 | +1213% |
| [GPT-5.6 Luna](https://uberllm.dev/models/openai/gpt-5.6-luna) | text | $0.00416 / $0.02496 | $0.056 / $0.336 | +1246% |
| [Gemini 3 Flash Preview](https://uberllm.dev/models/google/gemini-3-flash-preview) | text | $0.002495 / $0.01497 | $0.035 / $0.21 | +1303% |
| [Google: Gemini 4 Argon](https://uberllm.dev/models/google/gemini-4-argon) | text | $0.00998 / $0.0499 | $0.14 / $0.70 | +1303% |
| [Gemini 3.8 Flash](https://uberllm.dev/models/google/gemini-3.8-flash) | text | $0.004001 / $0.02001 | $0.05775 / $0.2888 | +1343% |
| [Claude Opus 5](https://uberllm.dev/models/anthropic/claude-opus-5) | text | $0.165 / $0.825 | $2.40 / $12.00 | +1355% |
| [DeepSeek V3.2](https://uberllm.dev/models/deepseek/deepseek-v3.2) | text | $0.003524 / $0.00653 | $0.052 / $0.076 | in +1376% / out +1064% |
| [Devstral 2 123B](https://uberllm.dev/models/mistralai/devstral-2-123b) | text | $0.00399 / $0.01995 | $0.06 / $0.30 | +1404% |
| [Qwen3 Coder 30B A3B Instruct](https://uberllm.dev/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.000693 / $0.002772 | $0.0105 / $0.042 | +1415% |
| [Qwen3.8 Flash](https://uberllm.dev/models/qwen/qwen3.8-flash) | text | $0.00147 / $0.004606 | $0.0225 / $0.0705 | +1431% |
| [GLM 4.5 Air](https://uberllm.dev/models/z-ai/glm-4.5-air) | text | $0.000129 / $0.000842 | $0.002 / $0.011 | in +1450% / out +1206% |
| [Gemma 3 4B IT](https://uberllm.dev/models/google/gemma-3-4b-it) | text | $0.000463 / $0.000579 | $0.0045 / $0.009 | in +872% / out +1454% |
| [Mistral Large](https://uberllm.dev/models/mistralai/mistral-large) | text | $0.0928 / $0.2784 | $1.58 / $4.74 | +1603% |
| [Claude Opus 4.6](https://uberllm.dev/models/anthropic/claude-opus-4.6) | text | $0.0845 / $0.4225 | $1.45 / $7.25 | +1616% |
| [Qwen 3 Coder 480b](https://uberllm.dev/models/qwen/qwen3-coder) | text | $0.002963 / $0.009875 | $0.051 / $0.17 | in +1621% / out +1622% |
| [Tencent HY3](https://uberllm.dev/models/tencent/hy3) | text | $0.003275 / $0.0131 | $0.05676 / $0.227 | +1633% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.0008 / $0.001 | $0.0144 / $0.018 | +1700% |
| [Qwen 3.5 397B](https://uberllm.dev/models/qwen/qwen3.5-397b-a17b) | text | $0.01671 / $0.1003 | $0.306 / $1.84 | +1731% |
| [Gemma 4 31B](https://uberllm.dev/models/google/gemma-4-31b) | text | $0.000912 / $0.002736 | $0.0168 / $0.0504 | +1742% |
| [GPT-6 Sol](https://uberllm.dev/models/openai/gpt-6-sol) | text | $0.0398 / $0.199 | $0.74 / $3.70 | +1759% |
| [GPT OSS Safeguard 120B](https://uberllm.dev/models/openai/gpt-oss-safeguard-120b) | text | $0.001497 / $0.005988 | $0.0285 / $0.114 | +1804% |
| [Kimi K2 Thinking](https://uberllm.dev/models/moonshotai/kimi-k2-thinking) | text | $0.00594 / $0.02475 | $0.114 / $0.475 | +1819% |
| [NVIDIA Nemotron 3 Super 120B](https://uberllm.dev/models/nvidia/nemotron-3-super-120b) | text | $0.001457 / $0.008197 | $0.0285 / $0.152 | in +1856% / out +1754% |
| [Palmyra Vision 7B](https://uberllm.dev/models/writer/palmyra-vision-7b) | text | $0.001496 / $0.005985 | $0.03 / $0.12 | +1905% |
| [GPT OSS Safeguard 20B](https://uberllm.dev/models/openai/gpt-oss-safeguard-20b) | text | $0.000074 / $0.000297 | $0.0015 / $0.006 | in +1927% / out +1920% |
| [GPT-6 Astra](https://uberllm.dev/models/openai/gpt-6-astra) | text | $0.10 / $0.50 | $2.10 / $10.50 | +2000% |
| [DeepSeek V4 Pro](https://uberllm.dev/models/deepseek/deepseek-v4-pro) | text | $0.001784 / $0.003568 | $0.03821 / $0.07642 | +2042% |
| [GPT-5.6 Sol](https://uberllm.dev/models/openai/gpt-5.6-sol) | text | $0.07952 / $0.3976 | $1.76 / $8.80 | +2113% |
| [Qwen 3 235B A22B Thinking 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.05 / $0.05 | $0.144 / $1.12 | in +188% / out +2140% |
| [DeepSeek V3.1](https://uberllm.dev/models/deepseek/deepseek-v3.1) | text | $0.002475 / $0.009405 | $0.0575 / $0.2185 | +2223% |
| [Claude Sonnet 4.6](https://uberllm.dev/models/anthropic/claude-sonnet-4.6) | text | $0.0534 / $0.267 | $1.26 / $6.30 | +2260% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | text | $0.01087 / $0.03415 | $0.28 / $0.88 | +2477% |
| [Qwen3.8 2.4T A95B](https://uberllm.dev/models/qwen/qwen3.8-2.4t-a95b) | text | $0.01394 / $0.04182 | $0.36 / $1.08 | +2482% |
| [GPT-6.1 Sol](https://uberllm.dev/models/openai/gpt-6.1-sol) | text | $0.0398 / $0.199 | $1.06 / $5.30 | +2563% |
| [Ministral 3 8B](https://uberllm.dev/models/mistralai/ministral-3-8b-instruct) | text | $0.001723 / $0.001723 | $0.051 / $0.051 | +2860% |
| [OpenAI: GPT-6.1 Terra](https://uberllm.dev/models/openai/gpt-6.1-terra) | text | $0.018 / $0.09 | $0.57 / $2.85 | +3067% |
| [Gemma 3 12B IT](https://uberllm.dev/models/google/gemma-3-12b-it) | text | $0.000494 / $0.001481 | $0.0165 / $0.0495 | in +3240% / out +3242% |
| [Grok 4.3](https://uberllm.dev/models/x-ai/grok-4.3) | text | $0.01238 / $0.02475 | $0.475 / $0.95 | +3738% |
| [NVIDIA Nemotron 3 Nano 30B](https://uberllm.dev/models/nvidia/nemotron-3-nano-30b-a3b) | text | $0.000741 / $0.002963 | $0.0285 / $0.114 | in +3746% / out +3747% |
| [Thinking Machines: Inkling](https://uberllm.dev/models/thinking-machines/inkling) | text | $0.009403 / $0.04009 | $0.37 / $1.50 | in +3835% / out +3638% |
| [Qwen: Qwen3.8 Omni Flash](https://uberllm.dev/models/qwen/qwen3.8-omni-flash) | text | $0.000146 / $0.000456 | $0.006 / $0.0188 | in +4010% / out +4023% |
| [GLM-4.6](https://uberllm.dev/models/z-ai/glm-4.6) | text | $0.004162 / $0.01694 | $0.1849 / $0.7525 | +4343% |
| [Grok 4.7](https://uberllm.dev/models/x-ai/grok-4.7) | text | $0.01384 / $0.04151 | $0.62 / $1.86 | +4381% |
| [Qwen 3.8 27B](https://uberllm.dev/models/qwen/qwen-3-8-27b) | text | $0.000191 / $0.002381 | $0.009 / $0.1125 | in +4612% / out +4625% |
| [Ministral 14B 3.0](https://uberllm.dev/models/mistralai/ministral-3-14b-instruct) | text | $0.001995 / $0.001995 | $0.098 / $0.098 | +4812% |
| [Gemma 4 31B IT](https://uberllm.dev/models/google/gemma-4-31b-it) | text | $0.0006 / $0.0018 | $0.0324 / $0.0972 | +5300% |
| [Aion 3.0 Mini](https://uberllm.dev/models/aion-labs/aion-3-0-mini) | text | $0.007 / $0.014 | $0.462 / $0.924 | +6500% |
| [Kimi K2.5](https://uberllm.dev/models/moonshotai/kimi-k2.5) | text | $0.003176 / $0.01985 | $0.2181 / $1.36 | +6768% |
| [Aion 3.5 Mini](https://uberllm.dev/models/aion-labs/aion-3-5-mini) | text | $0.00875 / $0.0175 | $0.6125 / $1.23 | +6900% |
| [DeepSeek V4 Flash 0731](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731) | text | $0.000901 / $0.001802 | $0.02213 / $0.1326 | in +2357% / out +7258% |
| [Aion 3.0](https://uberllm.dev/models/aion-labs/aion-3-0) | text | $0.03 / $0.06 | $2.22 / $4.44 | +7300% |
| [GLM-5](https://uberllm.dev/models/z-ai/glm-5) | text | $0.00387 / $0.01238 | $0.29 / $0.928 | +7394% |
| [Aion 3.5](https://uberllm.dev/models/aion-labs/aion-3-5) | text | $0.0375 / $0.075 | $3.00 / $6.00 | +7900% |
| [Aion 2.0](https://uberllm.dev/models/aion-labs/aion-2.0) | text | $0.008 / $0.016 | $0.688 / $1.38 | +8500% |
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.00078 / $0.009529 | $0.0675 / $0.825 | in +8554% / out +8558% |
| [GLM-5.2](https://uberllm.dev/models/z-ai/glm-5.2) | text | $0.00052 / $0.00352 | $0.00052 / $0.3269 | in 0% / out +9186% |
| [GPT-OSS 120B](https://uberllm.dev/models/openai/gpt-oss-120b) | text | $0.000069 / $0.000297 | $0.0084 / $0.036 | in +12074% / out +12021% |
| [Grok 4.5](https://uberllm.dev/models/x-ai/grok-4.5) | text | $0.008322 / $0.02497 | $1.10 / $3.30 | +13118% |
| [GLM-4.7](https://uberllm.dev/models/z-ai/glm-4.7) | text | $0.00154 / $0.00616 | $0.209 / $0.836 | +13471% |
| [Qwen 3 235B A22B Instruct 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-2507) | text | $0.000633 / $0.003389 | $0.0868 / $0.465 | in +13612% / out +13621% |
| [DeepSeek V4.1 Flash 1017](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.000239 / $0.01992 | $0.036 / $0.144 | in +14963% / out +623% |
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | text | $0.000975 / $0.005686 | $0.156 / $0.91 | in +15900% / out +15904% |
| [MiniMax M2.1](https://uberllm.dev/models/minimax/minimax-m2.1) | text | $0.000356 / $0.001426 | $0.315 / $1.26 | in +88383% / out +88259% |
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | text | $0.000018 / $0.000078 | $0.0243 / $0.1053 | +134900% |

</details>


# Changelog

Price changes between daily snapshots of [`prices.json`](prices.json), newest first.
"Official list price" = the model maker's price as carried in the catalog (see [SOURCES](README.md#sources)).
"UberLLM price" = the best live offer on the UberLLM market at snapshot time; it moves during the day.
Text prices are $ per 1M input / output tokens. Every day's full table is in [`history/`](history/).

## 2026-11-12 (vs 2026-11-11)

**Official list price changes (26)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GLM 5.1 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5.1) | text | $1.40 / $4.40 | $1.33 / $4.18 | −5% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | text | $1.40 / $4.40 | $1.33 / $4.18 | −5% |
| [DeepSeek V4 Flash](https://uberllm.dev/models/deepseek/deepseek-v4-flash) | text | $0.091 / $0.182 | $0.09 / $0.18 | −1% |
| [Flux 3 (Venice)](https://uberllm.dev/models/black-forest-labs/venice-flux-3-image) | image | – | $0.12 / image |  |
| [ElevenLabs Music v2](https://uberllm.dev/models/elevenlabs/elevenlabs-music-v2) | music | – | $0.69 / track |  |
| [ElevenLabs Music v2.5](https://uberllm.dev/models/elevenlabs/elevenlabs-music-v2-5) | music | – | $0.69 / track |  |
| [ElevenLabs Voice Changer](https://uberllm.dev/models/elevenlabs/elevenlabs-voice-changer) | music | – | $0.35 / track |  |
| [Veo3.1 Full (image-to-video)](https://uberllm.dev/models/google/veo3-1-full-image-to-video) | video | – | $0.44 / sec |  |
| [Veo 3.1 Full Text-to-Video](https://uberllm.dev/models/google/veo3-1-full-text-to-video) | video | – | $0.44 / sec |  |
| [Krea 2 Turbo (Venice)](https://uberllm.dev/models/krea/venice-krea-2-turbo) | image | – | $0.04 / image |  |
| [LongCat Text-to-Video](https://uberllm.dev/models/meituan/longcat-text-to-video) | video | – | $0.05 / sec |  |
| [Pixverse C1 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-c1-image-to-video) | video | – | $0.0433 / sec |  |
| [PixVerse V5.6 Text-to-Video](https://uberllm.dev/models/pixverse/pixverse-v5-6-text-to-video) | video | – | $0.228 / sec |  |
| [Pixverse V5.6 Transition (transition)](https://uberllm.dev/models/pixverse/pixverse-v5-6-transition) | video | – | $0.202 / sec |  |
| [Runway Gen-4.5](https://uberllm.dev/models/runway/runway-gen4-5) | video | – | $0.16 / sec |  |
| [Runway Gen-4 Turbo](https://uberllm.dev/models/runway/runway-gen4-turbo) | video | – | $0.0675 / sec |  |
| [ACE-Step 1.5 (Venice)](https://uberllm.dev/models/venice/ace-step-15) | music | – | $0.03 / track |  |
| [Venice Music Gen (legacy alias)](https://uberllm.dev/models/venice/music-gen) | music | – | $0.03 / track |  |
| [Runway Gen-4.5 Text-to-Video (Venice)](https://uberllm.dev/models/venice/runway-gen4-5-text) | video | – | $0.16 / sec |  |
| [Venice Video Gen (legacy alias)](https://uberllm.dev/models/venice/video-gen) | video | – | $0.16 / sec |  |
| [Vidu Q3 Text-to-Video](https://uberllm.dev/models/vidu/vidu-q3-text-to-video) | video | – | $0.1933 / sec |  |
| [Wan 2.5 Preview (image-to-video)](https://uberllm.dev/models/wan/wan-2-5-preview-image-to-video) | video | – | $0.056 / sec |  |
| [Grok Imagine Text-to-Video](https://uberllm.dev/models/x-ai/grok-imagine-text-to-video) | video | $0.0885 / sec | $0.089 / sec | +1% |
| [Tencent: Hy4 preview](https://uberllm.dev/models/tencent/hy4-preview) | text | $0.7506 / $2.25 | $0.834 / $2.50 | +11% |
| [Tencent HY3](https://uberllm.dev/models/tencent/hy3) | text | $0.0825 / $0.33 | $0.132 / $0.528 | +60% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.075 / $0.30 | $0.15 / $0.60 | +100% |

**New models (15)**

| Model | Category | Official price | UberLLM price |
|---|---|---|---|
| [Hermes 3 Llama 3.1 405b (Morpheus Web)](https://uberllm.dev/models/meta-llama/hermes-3-llama-3.1-405b:web) | text | – | $0.737 / $2.01 |
| [Llama 3.2 3B (Morpheus Web)](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct:web) | text | – | $0.1005 / $0.402 |
| [Llama 3.3 70B (Morpheus Web)](https://uberllm.dev/models/meta-llama/llama-3.3-70b-instruct:web) | text | – | $0.469 / $1.88 |
| [MiniMax M2.5 (Morpheus Web)](https://uberllm.dev/models/minimax/minimax-m2.5:web) | text | $0.27 / $0.95 | $0.2278 / $0.7973 |
| [Mistral Small 3.2 24B Instruct (Morpheus Web)](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct:web) | text | $0.0938 / $0.25 | $0.06281 / $0.1675 |
| [Kimi K2.5 (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.5:web) | text | $0.532 / $3.33 | $0.3752 / $2.35 |
| [Kimi K2.6 (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.6:web) | text | $0.65 / $3.41 | $0.5695 / $3.12 |
| [Kimi K2.7 Code (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.7-code:web) | text | $0.60 / $3.50 | $0.4556 / $2.28 |
| [OpenAI GPT OSS 120B (Morpheus Web)](https://uberllm.dev/models/openai/gpt-oss-120b:web) | text | $0.07 / $0.30 | $0.0469 / $0.201 |
| [Qwen 3 235B A22B Instruct 2507 (Morpheus Web)](https://uberllm.dev/models/qwen/qwen3-235b-a22b-2507:web) | text | $0.14 / $0.75 | $0.1005 / $0.5025 |
| [Qwen 3 Next 80b (Morpheus Web)](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct:web) | text | – | $0.2345 / $1.27 |
| [GLM 5.1 Non-thinking](https://uberllm.dev/models/z-ai/glm-5.1-non-thinking) | text | $1.40 / $4.40 | $1.00 / $3.35 |
| [GLM 5.1 Non-thinking (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5.1-non-thinking:web) | text | $1.40 / $4.40 | $1.00 / $3.35 |
| [GLM 5.1 (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5.1:web) | text | $1.33 / $4.18 | $1.17 / $3.69 |
| [GLM 5 (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5:web) | text | $1.00 / $3.20 | $0.737 / $2.78 |

**No longer listed (6)**: `bytedance/seedance-2-0-mini-reference-to-video`, `google/veo3-1-fast-image-to-video`, `inception/mercury-2.5`, `pixverse/pixverse-c1-reference-to-video`, `pixverse/pixverse-c1-transition`, `vidu/vidu-q3-image-to-video`

<details><summary>UberLLM price moves of 10% or more (127)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | text | $0.009788 / $0.0571 | $0.000975 / $0.005686 | −90% |
| [GPT OSS Safeguard 20B](https://uberllm.dev/models/openai/gpt-oss-safeguard-20b) | text | $0.000525 / $0.0021 | $0.000074 / $0.000297 | −86% |
| [Meta: Muse Spark 1.2](https://uberllm.dev/models/meta-llama/muse-spark-1.2) | text | $0.375 / $1.27 | $0.1125 / $0.3825 | −70% |
| [GPT-5.4 Image 2](https://uberllm.dev/models/openai/gpt-5.4-image-2) | image | $2.00 / $3.75 | $0.64 / $1.20 | −68% |
| [Flux 2 Max (Venice)](https://uberllm.dev/models/venice/flux-2-max) | image | $0.063 / image | $0.0225 / image | −64% |
| [Google: Gemini 4 Carbon](https://uberllm.dev/models/google/gemini-4-carbon) | text | $1.00 / $5.00 | $0.3792 / $1.90 | −62% |
| [Seedream 4.5](https://uberllm.dev/models/bytedance/seedream-4.5) | image | $0.024 / image | $0.01 / image | −58% |
| [MoonshotAI: Kimi K3.1 Pro](https://uberllm.dev/models/moonshotai/kimi-k3.1-pro) | text | $0.10 / $0.50 | $0.04231 / $0.2115 | −58% |
| [Tencent HY3](https://uberllm.dev/models/tencent/hy3) | text | $0.007431 / $0.02972 | $0.003275 / $0.0131 | −56% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.01782 / sec | $0.009 / sec | −49% |
| [GPT-6 Luna](https://uberllm.dev/models/openai/gpt-6-luna) | text | $0.008695 / $0.04348 | $0.004462 / $0.02231 | −49% |
| [Gemini 3.5 Flash Lite](https://uberllm.dev/models/google/gemini-3-5-flash-lite) | text | $0.1677 / $1.40 | $0.087 / $0.725 | −48% |
| [Grok 4.5](https://uberllm.dev/models/x-ai/grok-4.5) | text | $0.01557 / $0.04671 | $0.008322 / $0.02497 | −47% |
| [Claude Opus 5 (Fast)](https://uberllm.dev/models/anthropic/claude-opus-5-fast) | text | $4.00 / $20.00 | $2.50 / $12.49 | −38% |
| [GPT Image 1.5 (Venice)](https://uberllm.dev/models/venice/gpt-image-1.5) | image | $0.208 / image | $0.13 / image | −38% |
| [Hunyuan Image 3.0 (Venice)](https://uberllm.dev/models/venice/hunyuan-image-v3) | image | $0.072 / image | $0.045 / image | −38% |
| [Qwen Image (Venice)](https://uberllm.dev/models/venice/qwen-image) | image | $0.024 / image | $0.015 / image | −38% |
| [Cohere: Command A+](https://uberllm.dev/models/cohere/command-a-plus) | text | $0.258 / $1.29 | $0.18 / $0.90 | −30% |
| [Elorian: Glimpse](https://uberllm.dev/models/elorian/glimpse) | text | $0.516 / $2.58 | $0.36 / $1.80 | −30% |
| [Moondream: Moondream 3 Preview](https://uberllm.dev/models/moondream/moondream3-preview) | text | $0.258 / $2.15 | $0.18 / $1.50 | −30% |
| [Moondream: Moondream 3.1](https://uberllm.dev/models/moondream/moondream3.1-9b-a2b) | text | $0.258 / $2.15 | $0.18 / $1.50 | −30% |
| [Reflection: Beam 1.0 501B A23B](https://uberllm.dev/models/reflection/beam-1.0-501b-a23b) | text | $0.258 / $0.86 | $0.18 / $0.60 | −30% |
| [MiMo-V2.5-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.5-pro) | text | $0.4128 / $1.55 | $0.288 / $1.08 | −30% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://uberllm.dev/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.3784 / $1.14 | $0.264 / $0.792 | −30% |
| [inclusionAI: Ling 3.1 Flash](https://uberllm.dev/models/inclusionai/ling-3.1-flash) | text | $0.0387 / $0.1161 | $0.027 / $0.081 | −30% |
| [LiquidAI: LFM2.5-24B-A2B](https://uberllm.dev/models/liquid/lfm-2.5-24b-a2b) | text | $0.043 / $0.602 | $0.03 / $0.42 | −30% |
| [Particle AI: Particle-1](https://uberllm.dev/models/particle-ai/particle-1) | text | $0.043 / $0.43 | $0.03 / $0.30 | −30% |
| [Qwen: Qwen3.8 Max Prime](https://uberllm.dev/models/qwen/qwen3.8-max-prime) | text | $3.44 / $10.32 | $2.40 / $7.20 | −30% |
| [Sakana: Fugu Max](https://uberllm.dev/models/sakana/fugu-max) | text | $1.72 / $5.16 | $1.20 / $3.60 | −30% |
| [Sakana: Fugu Ultra v2](https://uberllm.dev/models/sakana/fugu-ultra-v2) | text | $4.30 / $25.80 | $3.00 / $18.00 | −30% |
| [JEV 1.13 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.13) | other | $0.03612 / $0 | $0.0252 / $0 | in −30% / out – |
| [JEV 1.14 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.14) | other | $0.03612 / $0 | $0.0252 / $0 | in −30% / out – |
| [Pareto 26.9](https://uberllm.dev/models/unbiased/pareto-26.9) | text | $2.15 / $6.45 | $1.50 / $4.50 | −30% |
| [Claude Sonnet 5.5](https://uberllm.dev/models/anthropic/claude-sonnet-5.5) | text | $0.0995 / $0.4975 | $0.07 / $0.35 | −30% |
| [MiMo-V2.6-Pro-UltraSpeed](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro-ultraspeed) | text | $3.61 / $7.22 | $2.61 / $5.22 | −28% |
| [Claude Fable 5.2](https://uberllm.dev/models/anthropic/claude-fable-5.2) | text | $2.71 / $13.55 | $1.96 / $9.82 | −28% |
| [Grok Imagine (Venice)](https://uberllm.dev/models/venice/grok-imagine) | image | $0.02 / image | $0.015 / image | −25% |
| [xAI Speech to Text v1 (Venice)](https://uberllm.dev/models/venice/xai-stt-v1) | transcription | $0.001228 / minute | $0.000944 / minute | −23% |
| [Seedream V4.5 (Venice)](https://uberllm.dev/models/venice/seedream-v4) | image | $0.0325 / image | $0.025 / image | −23% |
| [LongCat Text-to-Video](https://uberllm.dev/models/meituan/longcat-text-to-video) | video | $0.05 / sec | $0.04 / sec | −20% |
| [NVIDIA: Nemotron 3.5 Super VL](https://uberllm.dev/models/nvidia/nemotron-3.5-super-vl) | text | $0.105 / $0.35 | $0.09 / $0.282 | in −14% / out −19% |
| [LTX 2 Full Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-full-text-to-video) | video | $0.07508 / sec | $0.06183 / sec | −18% |
| [Veo 3 Fast Text-to-Video](https://uberllm.dev/models/google/veo3-fast-text-to-video) | video | $0.1403 / sec | $0.1155 / sec | −18% |
| [Veo 3 Full Text-to-Video](https://uberllm.dev/models/google/veo3-full-text-to-video) | video | $0.374 / sec | $0.308 / sec | −18% |
| [LTX 2 19B Full Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-19b-full-text-to-video) | video | $0.0748 / sec | $0.0616 / sec | −18% |
| [Runway Gen-4 Aleph](https://uberllm.dev/models/runway/runway-gen4-aleph) | video | $0.425 / video | $0.35 / video | −18% |
| [Wan 2.1 Pro Image-to-Video](https://uberllm.dev/models/wan/wan-2-1-pro-image-to-video) | video | $0.1247 / sec | $0.1027 / sec | −18% |
| [Wan 2.2 A14B Text-to-Video](https://uberllm.dev/models/wan/wan-2-2-a14b-text-to-video) | video | $0.17 / video | $0.14 / video | −18% |
| [LTX 2 Fast Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-fast-text-to-video) | video | $0.05667 / sec | $0.04667 / sec | −18% |
| [Seedance 2.0 Fast (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-image-to-video) | video | $0.059 / sec | $0.049 / sec | −17% |
| [DeepSeek V4.1 Flash 1017](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash-1017) | text | $0.000287 / $0.02392 | $0.000239 / $0.01992 | −17% |
| [MiniMax M3](https://uberllm.dev/models/minimax/minimax-m3) | text | $0.01474 / $0.05895 | $0.01239 / $0.04958 | −16% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.0792 / sec | $0.0675 / sec | −15% |
| [Kimi K2](https://uberllm.dev/models/moonshotai/kimi-k2) | text | $0.399 / $1.61 | $0.342 / $1.38 | −14% |
| [Qwen3 30B A3B](https://uberllm.dev/models/qwen/qwen3-30b-a3b) | text | $0.084 / $0.35 | $0.072 / $0.30 | −14% |
| [Z.ai: GLM 5.3 FlashX Legal](https://uberllm.dev/models/z-ai/glm-5.3-flashx-legal) | text | $0.259 / $0.875 | $0.222 / $0.75 | −14% |
| [Fireworks: Ember-1](https://uberllm.dev/models/fireworks/ember-1) | text | $2.10 / $10.49 | $1.80 / $9.00 | −14% |
| [Grok Imagine Pro (Venice)](https://uberllm.dev/models/venice/grok-imagine-pro) | image | $0.04069 / image | $0.035 / image | −14% |
| [Seedance 2.0 (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-reference-to-video) | video | $0.0792 / sec | $0.06864 / sec | −13% |
| [Venice SD35](https://uberllm.dev/models/venice/sd35) | image | $0.008 / image | $0.007 / image | −12% |
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | text | $0.000018 / $0.000089 | $0.000018 / $0.000078 | in 0% / out −12% |
| [Claude Opus 5.5](https://uberllm.dev/models/anthropic/claude-opus-5.5) | text | $0.1517 / $0.7585 | $0.136 / $0.68 | −10% |
| [Whisper Large V3 (STT)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0048 / minute | $0.004311 / minute | −10% |
| [Qwen 2.5 7B](https://uberllm.dev/models/qwen/e2ee-qwen-2-5-7b-p) | text | $0.02248 / $0.05844 | $0.02498 / $0.06494 | +11% |
| [Mistral: Mistral Large 4](https://uberllm.dev/models/mistralai/mistral-large-4-0) | text | $0.063 / $0.189 | $0.07 / $0.21 | +11% |
| [Wan 2.6 (image-to-video)](https://uberllm.dev/models/wan/wan-2-6-image-to-video) | video | $0.0627 / sec | $0.07 / sec | +12% |
| [Wan 2.7 Pro (image-to-image)](https://uberllm.dev/models/wan/wan-2-7-pro-edit) | image | $0.05358 / image | $0.06 / image | +12% |
| [GPT-5.4 Pro](https://uberllm.dev/models/openai/gpt-5.4-pro) | text | $4.79 / $28.76 | $5.40 / $32.39 | +13% |
| [Claude Haiku 4.5](https://uberllm.dev/models/anthropic/claude-haiku-4.5) | text | $0.0653 / $0.3265 | $0.0745 / $0.3725 | +14% |
| [Meta: Muse Glimmer 30B](https://uberllm.dev/models/meta-llama/muse-glimmer-30b) | text | $0.258 / $1.03 | $0.297 / $1.19 | +15% |
| [Ministral 3 8B](https://uberllm.dev/models/mistralai/ministral-3-8b-instruct) | text | $0.001496 / $0.001496 | $0.001723 / $0.001723 | +15% |
| [Claude Haiku 5.5](https://uberllm.dev/models/anthropic/claude-haiku-5.5) | text | $0.006889 / $0.03445 | $0.008 / $0.04 | +16% |
| [Whisper 1 (Venice, legacy alias)](https://uberllm.dev/models/venice/whisper-1) | transcription | $0.0036 / minute | $0.004311 / minute | +20% |
| [Pixverse V5.6 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-v5-6-image-to-video) | video | $0.1515 / sec | $0.1818 / sec | +20% |
| [ByteDance Seed: Seed-2.0-Code](https://uberllm.dev/models/bytedance/seed-2.0-code) | text | $0.43 / $2.58 | $0.525 / $3.15 | +22% |
| [Grok Imagine — Edit (Venice)](https://uberllm.dev/models/venice/grok-imagine-edit) | image | $0.01228 / image | $0.015 / image | +22% |
| [Wan 2.7 (image-to-video)](https://uberllm.dev/models/wan/wan-2-7-image-to-video) | video | $0.0627 / sec | $0.077 / sec | +23% |
| [Seedance 2.0 (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-image-to-video) | video | $0.05016 / sec | $0.0616 / sec | +23% |
| [Happyhorse 1.0 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-image-to-video) | video | $0.08738 / sec | $0.1073 / sec | +23% |
| [Tencent: Hy4 preview](https://uberllm.dev/models/tencent/hy4-preview) | text | $0.05411 / $0.1623 | $0.06746 / $0.2023 | +25% |
| [Wan 2.7 Text-to-Video](https://uberllm.dev/models/wan/wan-2-7-text-to-video) | video | $0.0627 / sec | $0.08 / sec | +28% |
| [Happyhorse 1.1 (image-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-image-to-video) | video | $0.08738 / sec | $0.1125 / sec | +29% |
| [Happyhorse 1.1 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-1-reference-to-video) | video | $0.08738 / sec | $0.1125 / sec | +29% |
| [Chroma (Venice)](https://uberllm.dev/models/venice/chroma) | image | $0.006 / image | $0.008 / image | +33% |
| [Gemma 3 4B IT](https://uberllm.dev/models/google/gemma-3-4b-it) | text | $0.000346 / $0.000693 | $0.000463 / $0.000579 | in +34% / out −16% |
| [Kimi K3](https://uberllm.dev/models/moonshotai/kimi-k3) | text | $0.001727 / $0.07805 | $0.001286 / $0.1072 | in −26% / out +37% |
| [LTX 2 v2.3 Full Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-text-to-video) | video | $0.05035 / sec | $0.07067 / sec | +40% |
| [Kling O3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-o3-4k-text-to-video) | video | $0.2641 / sec | $0.3707 / sec | +40% |
| [Ltx 2 V2.3 Full (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-full-image-to-video) | video | $0.05033 / sec | $0.07064 / sec | +40% |
| [Kling O3.4k (image-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-image-to-video) | video | $0.2641 / sec | $0.3706 / sec | +40% |
| [Kling O3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-reference-to-video) | video | $0.2641 / sec | $0.3706 / sec | +40% |
| [Kling V3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-standard-image-to-video) | video | $0.0798 / sec | $0.112 / sec | +40% |
| [LTX 2 v2.3 Fast Text-to-Video](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-text-to-video) | video | $0.038 / sec | $0.05333 / sec | +40% |
| [Kling V3.4k (reference-to-video)](https://uberllm.dev/models/kling/kling-v3-4k-reference-to-video) | video | $0.2641 / sec | $0.3707 / sec | +40% |
| [Kling V3 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-pro-image-to-video) | video | $0.1045 / sec | $0.1467 / sec | +40% |
| [Kling V3 Turbo Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-pro-image-to-video) | video | $0.08738 / sec | $0.1227 / sec | +40% |
| [Meta: Muse Ember](https://uberllm.dev/models/meta-llama/muse-ember) | text | $0.07 / $0.35 | $0.099 / $0.495 | +41% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | text | $0.1217 / $0.3652 | $0.1898 / $0.5695 | +56% |
| [Seedance 2.0 Fast (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-reference-to-video) | video | $0.0399 / sec | $0.063 / sec | +58% |
| [Happyhorse 1.0 (reference-to-video)](https://uberllm.dev/models/happyhorse/happyhorse-1-0-reference-to-video) | video | $0.08738 / sec | $0.138 / sec | +58% |
| [Kling V3 4K Text-to-Video](https://uberllm.dev/models/kling/kling-v3-4k-text-to-video) | video | $0.2641 / sec | $0.417 / sec | +58% |
| [Ltx 2 V2.3 Fast (image-to-video)](https://uberllm.dev/models/lightricks/ltx-2-v2-3-fast-image-to-video) | video | $0.03802 / sec | $0.06003 / sec | +58% |
| [Kling V3 Pro Text-to-Video](https://uberllm.dev/models/kling/kling-v3-pro-text-to-video) | video | $0.1045 / sec | $0.165 / sec | +58% |
| [Kling V3 Standard Text-to-Video](https://uberllm.dev/models/kling/kling-v3-standard-text-to-video) | video | $0.07866 / sec | $0.1242 / sec | +58% |
| [GPT-5.2](https://uberllm.dev/models/openai/gpt-5.2) | text | $0.2151 / $1.72 | $0.3432 / $2.75 | +60% |
| [Kokoro Text to Speech (Venice)](https://uberllm.dev/models/venice/kokoro-tts) | speech | $0.00175 / 1K chars | $0.0028 / 1K chars | +60% |
| [Firered Image (image-to-image)](https://uberllm.dev/models/xiaohongshu/firered-image-edit) | image | $0.0198 / image | $0.032 / image | +62% |
| [GLM 5.3 Flash](https://uberllm.dev/models/z-ai/glm-5.3-flash) | text | $0.001525 / $0.002996 | $0.0015 / $0.005 | in −2% / out +67% |
| [DeepSeek V3.2](https://uberllm.dev/models/deepseek/deepseek-v3.2) | text | $0.0026 / $0.0038 | $0.003524 / $0.00653 | in +36% / out +72% |
| [NVIDIA Nemotron Nano 9B v2](https://uberllm.dev/models/nvidia/nemotron-nano-9b-v2) | text | $0.000599 / $0.002294 | $0.001117 / $0.004281 | in +86% / out +87% |
| [DeepSeek V4 Pro](https://uberllm.dev/models/deepseek/deepseek-v4-pro) | text | $0.000955 / $0.001911 | $0.001784 / $0.003568 | +87% |
| [Claude Sonnet 4.5](https://uberllm.dev/models/anthropic/claude-sonnet-4.5) | text | $0.5886 / $2.94 | $1.18 / $5.92 | +101% |
| [Qwen3 Coder Next](https://uberllm.dev/models/qwen/qwen3-coder-next) | text | $0.001185 / $0.0079 | $0.0024 / $0.016 | +103% |
| [NVIDIA Nemotron 3 Super 120B](https://uberllm.dev/models/nvidia/nemotron-3-super-120b) | text | $0.000748 / $0.00399 | $0.001457 / $0.008197 | in +95% / out +105% |
| [Claude Opus 4.7](https://uberllm.dev/models/anthropic/claude-opus-4.7) | text | $0.161 / $0.805 | $0.3675 / $1.84 | +128% |
| [Tencent: Hy4](https://uberllm.dev/models/tencent/hy4) | text | $0.04375 / $0.1312 | $0.1021 / $0.306 | +133% |
| [Whisper Large V3 (Venice)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0015 / minute | $0.004311 / minute | +187% |
| [GPT-5.3 Codex](https://uberllm.dev/models/openai/gpt-5.3-codex) | text | $0.1405 / $1.12 | $0.4051 / $3.24 | +188% |
| [Mistral Large 3](https://uberllm.dev/models/mistralai/mistral-large-3) | text | $0.005 / $0.015 | $0.02475 / $0.07425 | +395% |
| [GPT-5.5](https://uberllm.dev/models/openai/gpt-5.5) | text | $0.2445 / $1.47 | $1.31 / $7.84 | +435% |
| [MiMo-V2.5](https://uberllm.dev/models/xiaomi/mimo-v2-5) | text | $0.07 / $0.14 | $0.24 / $1.20 | in +243% / out +757% |
| [DeepSeek V4 Flash](https://uberllm.dev/models/deepseek/deepseek-v4-flash) | text | $0.001044 / $0.002088 | $0.0091 / $0.0182 | +772% |
| [DeepSeek V4.1 Flash](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash) | text | $0.000179 / $0.001374 | $0.002491 / $0.0277 | in +1292% / out +1916% |
| [Ministral 3B](https://uberllm.dev/models/mistralai/ministral-3-3b-instruct) | text | $0.000997 / $0.000997 | $0.025 / $0.025 | +2408% |
| [Gemma 3 27B](https://uberllm.dev/models/google/gemma-3-27b-it) | text | $0.000792 / $0.00198 | $0.02 / $0.05 | +2425% |
| [Qwen3 VL 235B A22B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-instruct) | text | $0.002074 / $0.01876 | $0.0525 / $0.475 | in +2431% / out +2432% |
| [GLM 4.7 Flash](https://uberllm.dev/models/z-ai/glm-4.7-flash) | text | $0.000312 / $0.002065 | $0.01815 / $0.12 | in +5717% / out +5711% |

</details>


## 2026-11-11 (vs 2026-11-10)

**Official list price changes (13)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [GLM 5.3 Flash](https://uberllm.dev/models/z-ai/glm-5.3-flash) | text | $0.15 / $0.50 | $0.0399 / $0.0784 | in −73% / out −84% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.15 / $0.60 | $0.075 / $0.30 | −50% |
| [Tencent HY3](https://uberllm.dev/models/tencent/hy3) | text | $0.132 / $0.528 | $0.0825 / $0.33 | −38% |
| [Tencent: Hy4 preview](https://uberllm.dev/models/tencent/hy4-preview) | text | $0.834 / $2.50 | $0.7506 / $2.25 | −10% |
| [DeepSeek V4 Pro](https://uberllm.dev/models/deepseek/deepseek-v4-pro) | text | – / – | $1.32 / $3.96 |  |
| [DeepSeek V4 Pro 0813](https://uberllm.dev/models/deepseek/deepseek-v4-pro-0813) | text | – / – | $1.32 / $3.96 |  |
| [DeepSeek V4 Pro (Morpheus Web)](https://uberllm.dev/models/deepseek/deepseek-v4-pro:web) | text | – / – | $1.32 / $3.96 |  |
| [DeepSeek V4.1 Flash](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash) | text | – / – | $0.30 / $1.20 |  |
| [DeepSeek V4.1 Flash 1017](https://uberllm.dev/models/deepseek/deepseek-v4.1-flash-1017) | text | – / – | $0.30 / $1.20 |  |
| [Kimi K3](https://uberllm.dev/models/moonshotai/kimi-k3) | text | – / – | $3.00 / $15.00 |  |
| [GLM-5.2](https://uberllm.dev/models/z-ai/glm-5.2) | text | – / – | $1.40 / $4.40 |  |
| [GLM 5.2 (Morpheus Web)](https://uberllm.dev/models/z-ai/glm-5.2:web) | text | – / – | $1.40 / $4.40 |  |
| [GLM 5.3](https://uberllm.dev/models/z-ai/glm-5.3) | text | – / – | $1.40 / $4.40 |  |

**New models (2)**

| Model | Category | Official price | UberLLM price |
|---|---|---|---|
| [Google: Gemini 4 Carbon](https://uberllm.dev/models/google/gemini-4-carbon) | text | $2.00 / $10.00 | $1.00 / $5.00 |
| [Inception: Mercury 2.5](https://uberllm.dev/models/inception/mercury-2.5) | text | – | $0.028 / $0.105 |

**No longer listed (15)**: `meta-llama/hermes-3-llama-3.1-405b:web`, `meta-llama/llama-3.2-3b-instruct:web`, `meta-llama/llama-3.3-70b-instruct:web`, `minimax/minimax-m2.5:web`, `mistralai/mistral-small-3.2-24b-instruct:web`, `moonshotai/kimi-k2.5:web`, `moonshotai/kimi-k2.6:web`, `moonshotai/kimi-k2.7-code:web`, `openai/gpt-oss-120b:web`, `qwen/qwen3-235b-a22b-2507:web`, `qwen/qwen3-next-80b-a3b-instruct:web`, `z-ai/glm-5.1-non-thinking`, `z-ai/glm-5.1-non-thinking:web`, `z-ai/glm-5.1:web`, `z-ai/glm-5:web`

<details><summary>UberLLM price moves of 10% or more (147)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Aion 2.0](https://uberllm.dev/models/aion-labs/aion-2.0) | text | $0.64 / $1.28 | $0.008 / $0.016 | −99% |
| [Aion 3.5 Mini](https://uberllm.dev/models/aion-labs/aion-3-5-mini) | text | $0.525 / $1.05 | $0.00875 / $0.0175 | −98% |
| [Aion 3.0](https://uberllm.dev/models/aion-labs/aion-3-0) | text | $1.78 / $3.56 | $0.03 / $0.06 | −98% |
| [Qwen3 32B](https://uberllm.dev/models/qwen/qwen3-32b) | text | $0.0104 / $0.0364 | $0.00079 / $0.002765 | −92% |
| [Ministral 14B 3.0](https://uberllm.dev/models/mistralai/ministral-3-14b-instruct) | text | $0.026 / $0.026 | $0.001996 / $0.001996 | −92% |
| [GPT OSS Safeguard 120B](https://uberllm.dev/models/openai/gpt-oss-safeguard-120b) | text | $0.0195 / $0.078 | $0.001497 / $0.005988 | −92% |
| [DeepSeek V4 Flash](https://uberllm.dev/models/deepseek/deepseek-v4-flash) | text | $0.009091 / $0.01818 | $0.001044 / $0.002088 | −89% |
| [DeepSeek V4 Flash 0731](https://uberllm.dev/models/deepseek/deepseek-v4-flash-0731) | text | $0.00212 / $0.0127 | $0.000901 / $0.001802 | in −57% / out −86% |
| [MiniMax M2.7 Highspeed](https://uberllm.dev/models/minimax/minimax-m2.7-highspeed) | text | $0.174 / $0.696 | $0.03 / $0.12 | −83% |
| [MiniMax M2.5](https://uberllm.dev/models/minimax/minimax-m2.5) | text | $0.0135 / $0.0475 | $0.002621 / $0.009222 | −81% |
| [Aion 3.0 Mini](https://uberllm.dev/models/aion-labs/aion-3-0-mini) | text | $0.035 / $0.07 | $0.007 / $0.014 | −80% |
| [Mistral Large 3](https://uberllm.dev/models/mistralai/mistral-large-3) | text | $0.02475 / $0.07425 | $0.005 / $0.015 | −80% |
| [GPT-5.3 Codex](https://uberllm.dev/models/openai/gpt-5.3-codex) | text | $0.3871 / $3.10 | $0.1405 / $1.12 | −64% |
| [Grok 4.7](https://uberllm.dev/models/x-ai/grok-4.7) | text | $0.03309 / $0.09928 | $0.01442 / $0.04326 | −56% |
| [Grok 4.5](https://uberllm.dev/models/x-ai/grok-4.5) | text | $0.03564 / $0.1069 | $0.01557 / $0.04671 | −56% |
| [Qwen 3 235B A22B Instruct 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-2507) | text | $0.0014 / $0.0075 | $0.000633 / $0.003389 | −55% |
| [Whisper Large V3 (Venice)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0033 / minute | $0.0015 / minute | −55% |
| [Gemini 3.1 Flash Lite](https://uberllm.dev/models/google/gemini-3.1-flash-lite) | text | $0.00242 / $0.01452 | $0.001213 / $0.007275 | −50% |
| [Meta: Muse Spark 1.1](https://uberllm.dev/models/meta-llama/muse-spark-1.1) | text | $0.7015 / $2.39 | $0.375 / $1.27 | −47% |
| [Gemini 3.6 Flash](https://uberllm.dev/models/google/gemini-3-6-flash) | text | $0.3937 / $1.97 | $0.2175 / $1.09 | −45% |
| [DeepSeek V4 Pro](https://uberllm.dev/models/deepseek/deepseek-v4-pro) | text | $0.001626 / $0.003252 | $0.000955 / $0.001911 | −41% |
| [Gemini 2.5 Flash](https://uberllm.dev/models/google/gemini-2.5-flash) | text | $0.0024 / $0.02 | $0.0015 / $0.0125 | in −37% / out −38% |
| [Claude Opus 4.7 Fast](https://uberllm.dev/models/anthropic/claude-opus-4.7-fast) | text | $27.00 / $135.00 | $18.00 / $90.00 | −33% |
| [Meta: Muse Spark 1.3 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.3-contributor) | text | $0.03 / $0.06 | $0.02 / $0.04 | −33% |
| [Qwen 3 235B A22B Thinking 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.075 / $0.075 | $0.05 / $0.05 | −33% |
| [Claude Opus 4.7](https://uberllm.dev/models/anthropic/claude-opus-4.7) | text | $0.2268 / $1.13 | $0.161 / $0.805 | −29% |
| [Claude Sonnet 5.5](https://uberllm.dev/models/anthropic/claude-sonnet-5.5) | text | $0.139 / $0.6951 | $0.0995 / $0.4975 | −28% |
| [Magistral Small 2509](https://uberllm.dev/models/mistralai/magistral-small-2509) | text | $0.00693 / $0.02079 | $0.00499 / $0.01497 | −28% |
| [GLM 5.3 Flash](https://uberllm.dev/models/z-ai/glm-5.3-flash) | text | $0.001245 / $0.00415 | $0.001525 / $0.002996 | in +22% / out −28% |
| [GPT-5.6 Terra Pro](https://uberllm.dev/models/openai/gpt-5.6-terra-pro) | text | $1.11 / $6.65 | $0.80 / $4.80 | −28% |
| [Gemma 3 4B IT](https://uberllm.dev/models/google/gemma-3-4b-it) | text | $0.000463 / $0.000579 | $0.000346 / $0.000693 | in −25% / out +20% |
| [GPT-5.6 Luna Pro](https://uberllm.dev/models/openai/gpt-5.6-luna-pro) | text | $0.1034 / $0.6202 | $0.08 / $0.48 | −23% |
| [Tencent HY3](https://uberllm.dev/models/tencent/hy3) | text | $0.009441 / $0.03776 | $0.007431 / $0.02972 | −21% |
| [MiniMax M3 Preview](https://uberllm.dev/models/minimax/minimax-m3-preview) | text | $0.1499 / $0.5998 | $0.12 / $0.48 | −20% |
| [Tencent: Hy4 preview](https://uberllm.dev/models/tencent/hy4-preview) | text | $0.0676 / $0.2027 | $0.05411 / $0.1623 | −20% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | text | $0.1517 / $0.455 | $0.1217 / $0.3652 | −20% |
| [Gemma 4 31B](https://uberllm.dev/models/google/gemma-4-31b) | text | $0.0009 / $0.0034 | $0.000912 / $0.002736 | in +1% / out −20% |
| [Claude Opus 5 (Fast)](https://uberllm.dev/models/anthropic/claude-opus-5-fast) | text | $4.96 / $24.80 | $4.00 / $20.00 | −19% |
| [Fireworks: Ember-1](https://uberllm.dev/models/fireworks/ember-1) | text | $2.57 / $12.86 | $2.10 / $10.49 | −18% |
| [Sakana: Fugu Max](https://uberllm.dev/models/sakana/fugu-max) | text | $2.10 / $6.30 | $1.72 / $5.16 | −18% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.008951 / $0.0358 | $0.007443 / $0.02977 | −17% |
| [Qwen 3.5 9B](https://uberllm.dev/models/qwen/qwen3.5-9b) | text | $0.03 / $0.09 | $0.025 / $0.075 | −17% |
| [Kokoro Text to Speech (Venice)](https://uberllm.dev/models/venice/kokoro-tts) | speech | $0.0021 / 1K chars | $0.00175 / 1K chars | −17% |
| [GPT-5.6 Luna](https://uberllm.dev/models/openai/gpt-5.6-luna) | text | $0.00497 / $0.02982 | $0.004143 / $0.02486 | −17% |
| [Grok Imagine — Edit (Venice)](https://uberllm.dev/models/venice/grok-imagine-edit) | image | $0.0147 / image | $0.01228 / image | −16% |
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | text | $0.01151 / $0.06713 | $0.009788 / $0.0571 | −15% |
| [Claude Opus 4.8](https://uberllm.dev/models/anthropic/claude-opus-4.8) | text | $0.337 / $1.69 | $0.29 / $1.45 | −14% |
| [ByteDance Seed: Seed-2.0-Code](https://uberllm.dev/models/bytedance/seed-2.0-code) | text | $0.495 / $2.97 | $0.43 / $2.58 | −13% |
| [Elorian: Glimpse](https://uberllm.dev/models/elorian/glimpse) | text | $0.594 / $2.97 | $0.516 / $2.58 | −13% |
| [inclusionAI: Ling 3.1 Flash](https://uberllm.dev/models/inclusionai/ling-3.1-flash) | text | $0.04455 / $0.1336 | $0.0387 / $0.1161 | −13% |
| [LiquidAI: LFM2.5-24B-A2B](https://uberllm.dev/models/liquid/lfm-2.5-24b-a2b) | text | $0.0495 / $0.693 | $0.043 / $0.602 | −13% |
| [Qwen: Qwen3.8 Max Prime](https://uberllm.dev/models/qwen/qwen3.8-max-prime) | text | $3.96 / $11.88 | $3.44 / $10.32 | −13% |
| [Sakana: Fugu Ultra v2](https://uberllm.dev/models/sakana/fugu-ultra-v2) | text | $4.95 / $29.70 | $4.30 / $25.80 | −13% |
| [Pareto 26.9](https://uberllm.dev/models/unbiased/pareto-26.9) | text | $2.48 / $7.42 | $2.15 / $6.45 | −13% |
| [Meta: Muse Glimmer 30B](https://uberllm.dev/models/meta-llama/muse-glimmer-30b) | text | $0.297 / $1.19 | $0.258 / $1.03 | −13% |
| [Reflection: Beam 1.0 501B A23B](https://uberllm.dev/models/reflection/beam-1.0-501b-a23b) | text | $0.297 / $0.99 | $0.258 / $0.86 | −13% |
| [JEV 1.14 (TypeSafe)](https://uberllm.dev/models/typesafe/jev-1.14) | other | $0.04158 / $0 | $0.03612 / $0 | in −13% / out – |
| [Qwen3.8 Flash](https://uberllm.dev/models/qwen/qwen3.8-flash) | text | $0.001692 / $0.005301 | $0.00147 / $0.004606 | −13% |
| [Meta: Muse Spark Open](https://uberllm.dev/models/meta-llama/muse-spark-open) | text | $0.6966 / $2.37 | $0.6162 / $2.10 | −12% |
| [Claude Opus 5.5](https://uberllm.dev/models/anthropic/claude-opus-5.5) | text | $0.1703 / $0.8515 | $0.1517 / $0.7585 | −11% |
| [Claude Haiku 4.5](https://uberllm.dev/models/anthropic/claude-haiku-4.5) | text | $0.0592 / $0.296 | $0.0653 / $0.3265 | +10% |
| [GPT-5.4 Pro](https://uberllm.dev/models/openai/gpt-5.4-pro) | text | $4.35 / $26.07 | $4.79 / $28.76 | +10% |
| [Grok Imagine (Venice)](https://uberllm.dev/models/venice/grok-imagine) | image | $0.018 / image | $0.02 / image | +11% |
| [Claude Opus 4.5](https://uberllm.dev/models/anthropic/claude-opus-4.5) | text | $0.3549 / $1.77 | $0.40 / $2.00 | +13% |
| [GPT-6 Luna Decisions (OpenAI)](https://uberllm.dev/models/openai/gpt-6-luna-decisions) | other | $0.06093 / $0 | $0.06878 / $0 | in +13% / out – |
| [GPT Image 1.5 — Edit (Venice)](https://uberllm.dev/models/venice/gpt-image-1-5-edit) | image | $0.216 / image | $0.248 / image | +15% |
| [Wan 2.7 (Venice)](https://uberllm.dev/models/venice/wan-2.7) | image | $0.02063 / image | $0.024 / image | +16% |
| [Grok Imagine Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-image-to-video-private) | video | $0.036 / sec | $0.042 / sec | +17% |
| [Grok Imagine Reference To Video Private (reference-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-reference-to-video-private) | video | $0.036 / sec | $0.042 / sec | +17% |
| [Chroma (Venice)](https://uberllm.dev/models/venice/chroma) | image | $0.005 / image | $0.006 / image | +20% |
| [Tencent: Hy4](https://uberllm.dev/models/tencent/hy4) | text | $0.03642 / $0.1092 | $0.04375 / $0.1312 | +20% |
| [Flux 2 Max (Venice)](https://uberllm.dev/models/venice/flux-2-max) | image | $0.0522 / image | $0.063 / image | +21% |
| [Wan 2.7 (reference-to-video)](https://uberllm.dev/models/wan/wan-2-7-reference-to-video) | video | $0.066 / sec | $0.08 / sec | +21% |
| [Seedance 2.0 Mini (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-mini-reference-to-video) | video | $0.0264 / sec | $0.033 / sec | +25% |
| [Kling V3 Turbo Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-turbo-standard-image-to-video) | video | $0.07398 / sec | $0.09248 / sec | +25% |
| [Pixverse V5.6 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-v5-6-image-to-video) | video | $0.1212 / sec | $0.1515 / sec | +25% |
| [xAI v1 TTS](https://uberllm.dev/models/x-ai/tts-xai-v1) | speech | $0.01125 / 1K chars | $0.01406 / 1K chars | +25% |
| [Meta: Muse Ember](https://uberllm.dev/models/meta-llama/muse-ember) | text | $0.055 / $0.275 | $0.07 / $0.35 | +27% |
| [Grok Imagine Pro (Venice)](https://uberllm.dev/models/venice/grok-imagine-pro) | image | $0.03169 / image | $0.04069 / image | +28% |
| [PixVerse C1 Text-to-Video (Venice)](https://uberllm.dev/models/venice/pixverse-c1-t2v) | video | $0.0428 / sec | $0.05707 / sec | +33% |
| [Whisper Large V3 (STT)](https://uberllm.dev/models/venice/whisper-large-v3) | transcription | $0.0036 / minute | $0.0048 / minute | +33% |
| [Gemini Omni Flash (reference-to-video)](https://uberllm.dev/models/google/gemini-omni-flash-reference-to-video) | video | $0.0855 / sec | $0.114 / sec | +33% |
| [Gemini 3.1 Flash TTS](https://uberllm.dev/models/google/tts-gemini-3-1-flash) | speech | $0.1125 / 1K chars | $0.15 / 1K chars | +33% |
| [Luma Uni 1 Max (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-max-edit) | image | $0.078 / image | $0.104 / image | +33% |
| [Longcat Distilled (image-to-video)](https://uberllm.dev/models/meituan/longcat-distilled-image-to-video) | video | $0.0108 / sec | $0.0144 / sec | +33% |
| [Flux 1.1 (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1) | image | $0.006 / image | $0.008 / image | +33% |
| [GPT Image 1.5 (Venice)](https://uberllm.dev/models/venice/gpt-image-1.5) | image | $0.156 / image | $0.208 / image | +33% |
| [Hunyuan Image 3.0 (Venice)](https://uberllm.dev/models/venice/hunyuan-image-v3) | image | $0.054 / image | $0.072 / image | +33% |
| [MiniMax Music 2.6 (Venice)](https://uberllm.dev/models/venice/minimax-music-v26) | music | $0.108 / track | $0.144 / track | +33% |
| [Venice SD35](https://uberllm.dev/models/venice/sd35) | image | $0.006 / image | $0.008 / image | +33% |
| [Stable Diffusion XL (Venice, legacy)](https://uberllm.dev/models/venice/sdxl) | image | $0.006 / image | $0.008 / image | +33% |
| [Luma Uni 1 (image-to-image)](https://uberllm.dev/models/luma/luma-uni-1-edit) | image | $0.036 / image | $0.048 / image | +33% |
| [Longcat (image-to-video)](https://uberllm.dev/models/meituan/longcat-image-to-video) | video | $0.03 / sec | $0.04 / sec | +33% |
| [MiniMax Speech 02 HD TTS](https://uberllm.dev/models/minimax/tts-minimax-speech-02-hd) | speech | $0.075 / 1K chars | $0.10 / 1K chars | +33% |
| [Ovi Image-to-Video](https://uberllm.dev/models/ovi/ovi-image-to-video) | video | $0.0264 / sec | $0.0352 / sec | +33% |
| [Qwen Image 2 Pro (image-to-image)](https://uberllm.dev/models/qwen/qwen-image-2-pro-edit) | image | $0.06 / image | $0.08 / image | +33% |
| [Chatterbox HD TTS](https://uberllm.dev/models/resemble-ai/tts-chatterbox-hd) | speech | $0.03 / 1K chars | $0.04 / 1K chars | +33% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://uberllm.dev/models/venice/elevenlabs-tts-turbo-v2-5) | speech | $0.0375 / 1K chars | $0.05 / 1K chars | +33% |
| [Flux 1.1 Pro (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1-pro) | image | $0.018 / image | $0.024 / image | +33% |
| [Qwen Image 2 Pro (Venice)](https://uberllm.dev/models/venice/qwen-image-2-pro) | image | $0.06 / image | $0.08 / image | +33% |
| [Venice TTS 1 (legacy alias)](https://uberllm.dev/models/venice/tts-1) | speech | $0.0021 / 1K chars | $0.0028 / 1K chars | +33% |
| [GPT-5.2](https://uberllm.dev/models/openai/gpt-5.2) | text | $0.1593 / $1.27 | $0.2151 / $1.72 | +35% |
| [Seedance 2.0 Fast (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-fast-image-to-video) | video | $0.042 / sec | $0.059 / sec | +40% |
| [Stable Audio 2.5 (Venice)](https://uberllm.dev/models/venice/stable-audio-25) | music | $0.108 / track | $0.152 / track | +41% |
| [Orpheus TTS](https://uberllm.dev/models/canopy-labs/tts-orpheus) | speech | $0.03438 / 1K chars | $0.05 / 1K chars | +45% |
| [Inworld 1.5 Max TTS](https://uberllm.dev/models/inworld/tts-inworld-1-5-max) | speech | $0.006875 / 1K chars | $0.01 / 1K chars | +45% |
| [Qwen3 1.7B TTS](https://uberllm.dev/models/qwen/tts-qwen3-1-7b) | speech | $0.06187 / 1K chars | $0.09 / 1K chars | +45% |
| [ElevenLabs Sound Effects v2 (Venice)](https://uberllm.dev/models/venice/elevenlabs-sound-effects-v2) | music | $0.011 / track | $0.016 / track | +45% |
| [Qwen Image (Venice)](https://uberllm.dev/models/venice/qwen-image) | image | $0.0165 / image | $0.024 / image | +45% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.054 / sec | $0.0792 / sec | +47% |
| [Seedance 2.0 (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-reference-to-video) | video | $0.0528 / sec | $0.0792 / sec | +50% |
| [ElevenLabs Scribe v2 (STT)](https://uberllm.dev/models/elevenlabs/elevenlabs-scribe-v2) | transcription | $0.00501 / minute | $0.008016 / minute | +60% |
| [Veo 3.1 Fast Text-to-Video](https://uberllm.dev/models/google/veo3-1-fast-text-to-video) | video | $0.099 / sec | $0.1633 / sec | +65% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.0108 / sec | $0.01782 / sec | +65% |
| [Vidu Q3 Text-to-Video](https://uberllm.dev/models/vidu/vidu-q3-text-to-video) | video | $0.116 / sec | $0.1933 / sec | +67% |
| [Veo3.1 Full (image-to-video)](https://uberllm.dev/models/google/veo3-1-full-image-to-video) | video | $0.264 / sec | $0.44 / sec | +67% |
| [Veo 3.1 Full Text-to-Video](https://uberllm.dev/models/google/veo3-1-full-text-to-video) | video | $0.264 / sec | $0.44 / sec | +67% |
| [Pixverse C1 (image-to-video)](https://uberllm.dev/models/pixverse/pixverse-c1-image-to-video) | video | $0.02598 / sec | $0.0433 / sec | +67% |
| [Pixverse C1 Transition (transition)](https://uberllm.dev/models/pixverse/pixverse-c1-transition) | video | $0.02598 / sec | $0.0433 / sec | +67% |
| [Veo3.1 Fast (image-to-video)](https://uberllm.dev/models/google/veo3-1-fast-image-to-video) | video | $0.099 / sec | $0.165 / sec | +67% |
| [LongCat Text-to-Video](https://uberllm.dev/models/meituan/longcat-text-to-video) | video | $0.03 / sec | $0.05 / sec | +67% |
| [PixVerse V5.6 Text-to-Video](https://uberllm.dev/models/pixverse/pixverse-v5-6-text-to-video) | video | $0.1368 / sec | $0.228 / sec | +67% |
| [Pixverse V5.6 Transition (transition)](https://uberllm.dev/models/pixverse/pixverse-v5-6-transition) | video | $0.1212 / sec | $0.202 / sec | +67% |
| [Runway Gen-4.5](https://uberllm.dev/models/runway/runway-gen4-5) | video | $0.096 / sec | $0.16 / sec | +67% |
| [Venice Music Gen (legacy alias)](https://uberllm.dev/models/venice/music-gen) | music | $0.018 / track | $0.03 / track | +67% |
| [Venice Video Gen (legacy alias)](https://uberllm.dev/models/venice/video-gen) | video | $0.096 / sec | $0.16 / sec | +67% |
| [Wan 2.5 Preview (image-to-video)](https://uberllm.dev/models/wan/wan-2-5-preview-image-to-video) | video | $0.0336 / sec | $0.056 / sec | +67% |
| [Qwen3 0.6B TTS](https://uberllm.dev/models/qwen/tts-qwen3-0-6b) | speech | $0.03938 / 1K chars | $0.07 / 1K chars | +78% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-multilingual-v2) | music | $0.054 / track | $0.096 / track | +78% |
| [ElevenLabs TTS v3 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-v3) | music | $0.054 / track | $0.096 / track | +78% |
| [MiniMax Music 2.0 (Venice)](https://uberllm.dev/models/venice/minimax-music-v2) | music | $0.018 / track | $0.032 / track | +78% |
| [MMAudio V2 Text-to-Audio (Venice)](https://uberllm.dev/models/venice/mmaudio-v2-text-to-audio) | music | $0.0045 / track | $0.008 / track | +78% |
| [Pixverse C1 (reference-to-video)](https://uberllm.dev/models/pixverse/pixverse-c1-reference-to-video) | video | $0.02381 / sec | $0.0433 / sec | +82% |
| [Vidu Q3 (image-to-video)](https://uberllm.dev/models/vidu/vidu-q3-image-to-video) | video | $0.0495 / sec | $0.09 / sec | +82% |
| [Runway Gen-4 Turbo](https://uberllm.dev/models/runway/runway-gen4-turbo) | video | $0.03712 / sec | $0.0675 / sec | +82% |
| [Runway Gen-4.5 Text-to-Video (Venice)](https://uberllm.dev/models/venice/runway-gen4-5-text) | video | $0.088 / sec | $0.16 / sec | +82% |
| [GPT-5.5](https://uberllm.dev/models/openai/gpt-5.5) | text | $0.125 / $0.75 | $0.2445 / $1.47 | +96% |
| [Gemma 4 26B A4B IT](https://uberllm.dev/models/google/gemma-4-26b-a4b-it) | text | $0.00038 / $0.00114 | $0.0008 / $0.001 | in +111% / out −12% |
| [ACE-Step 1.5 (Venice)](https://uberllm.dev/models/venice/ace-step-15) | music | $0.0135 / track | $0.03 / track | +122% |
| [Kimi K2.6](https://uberllm.dev/models/moonshotai/kimi-k2.6) | text | $0.008257 / $0.04332 | $0.01977 / $0.1037 | +139% |
| [GPT-6 Luna](https://uberllm.dev/models/openai/gpt-6-luna) | text | $0.002956 / $0.01478 | $0.008695 / $0.04348 | +194% |
| [Claude Fable 5.2](https://uberllm.dev/models/anthropic/claude-fable-5.2) | text | $0.7152 / $3.58 | $2.71 / $13.55 | +279% |
| [ElevenLabs Music (Venice)](https://uberllm.dev/models/venice/elevenlabs-music) | music | $0.1725 / track | $0.6555 / track | +280% |
| [Gemini 3.8 Flash](https://uberllm.dev/models/google/gemini-3.8-flash) | text | $0.000799 / $0.003995 | $0.003992 / $0.01996 | +400% |
| [GPT OSS Safeguard 20B](https://uberllm.dev/models/openai/gpt-oss-safeguard-20b) | text | $0.000075 / $0.0003 | $0.000525 / $0.0021 | +600% |
| [GPT-5.4](https://uberllm.dev/models/openai/gpt-5.4) | text | $0.0625 / $0.375 | $0.4753 / $2.85 | +660% |
| [Seedream 4.5](https://uberllm.dev/models/bytedance/seedream-4.5) | image | $0.0004 / image | $0.024 / image | +5900% |

</details>


## 2026-11-03 to 2026-11-10 (UberLLM daily catalog snapshots, before this repo started)

From `GET https://api.uberllm.dev/api/v1/public/price-changes`. Text prices are $ per 1M input / output tokens.

**Official list price changes (18)**

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [NVIDIA Nemotron 3 Super 120B](https://uberllm.dev/models/nvidia/nemotron-3-super-120b) | text | $0.30 / $2.40 | $0.075 / $0.40 | in −75% / out −83% |
| [inclusionAI: Ling 3.1 Flash](https://uberllm.dev/models/inclusionai/ling-3.1-flash) | text | $0.075 / $0.225 | $0.045 / $0.135 | −40% |
| [MiniMax M2.7](https://uberllm.dev/models/minimax/minimax-m2.7) | text | $0.30 / $1.20 | $0.21 / $0.84 | −30% |
| [Qwen3 Next 80B A3B](https://uberllm.dev/models/qwen/qwen3-next-80b-a3b-instruct) | text | $0.10 / $1.10 | $0.09 / $1.10 | in −10% / out 0% |
| [NVIDIA: Nemotron 3.5 Super VL](https://uberllm.dev/models/nvidia/nemotron-3.5-super-vl) | text | $0.15 / $0.50 | $0.15 / $0.47 | in 0% / out −6% |
| [Llama 3.2 3B](https://uberllm.dev/models/meta-llama/llama-3.2-3b-instruct) | text | $0.0509 / $0.335 | $0.05 / $0.33 | in −2% / out −1% |
| [PixVerse C1 Text-to-Video (Venice)](https://uberllm.dev/models/venice/pixverse-c1-t2v) | video | $0.07 / sec | $0.07133 / sec | +2% |
| [MiniMax M2](https://uberllm.dev/models/minimax/minimax-m2) | text | $0.255 / $1.02 | $0.30 / $1.20 | +18% |
| [Qwen 3.6 27B](https://uberllm.dev/models/qwen/qwen3.6-27b) | text | $0.325 / $2.70 | $0.32 / $3.20 | in −2% / out +19% |
| [Qwen 3.5 397B](https://uberllm.dev/models/qwen/qwen3.5-397b-a17b) | text | $0.50 / $3.60 | $0.60 / $3.60 | in +20% / out 0% |
| [Reflection: Beam 1.0 501B A23B](https://uberllm.dev/models/reflection/beam-1.0-501b-a23b) | text | $0.25 / $1.00 | $0.30 / $1.00 | in +20% / out 0% |
| [Mistral Small 3.2 24B Instruct](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct) | text | $0.075 / $0.20 | $0.0938 / $0.25 | +25% |
| [Mistral Small 3.2 24B Instruct (Morpheus Web)](https://uberllm.dev/models/mistralai/mistral-small-3.2-24b-instruct:web) | text | $0.075 / $0.20 | $0.0938 / $0.25 | +25% |
| [Kimi K2.5](https://uberllm.dev/models/moonshotai/kimi-k2.5) | text | $0.50 / $2.50 | $0.532 / $3.33 | in +6% / out +33% |
| [Kimi K2.5 (Morpheus Web)](https://uberllm.dev/models/moonshotai/kimi-k2.5:web) | text | $0.50 / $2.50 | $0.532 / $3.33 | in +6% / out +33% |
| [GLM 4.5 Air](https://uberllm.dev/models/z-ai/glm-4.5-air) | text | $0.13 / $0.85 | $0.20 / $1.10 | in +54% / out +29% |
| [DeepSeek: DeepSeek V4 Flash Vision Exp](https://uberllm.dev/models/deepseek/deepseek-v4-flash-vision-exp) | text | $0.2156 / $0.6468 | $0.44 / $1.32 | +104% |
| [GLM 5.3 Flash](https://uberllm.dev/models/z-ai/glm-5.3-flash) | text | $0.0285 / $0.0923 | $0.15 / $0.50 | in +426% / out +442% |

**New models (4)**: [Claude Fable 5.2](https://uberllm.dev/models/anthropic/claude-fable-5.2), [Meta: Muse Ember](https://uberllm.dev/models/meta-llama/muse-ember), [Tencent: Hy4](https://uberllm.dev/models/tencent/hy4), [Tencent: Hy4 preview](https://uberllm.dev/models/tencent/hy4-preview)

**No longer listed (2)**: `deepseek/deepseek-r1`, `x-ai/grok-imagine-quality-edit`

<details><summary>UberLLM price moves of 10% or more (164)</summary>

| Model | Category | Before | After | Change |
|---|---|---|---|---|
| [Gemini 3.5 Flash](https://uberllm.dev/models/google/gemini-3.5-flash) | text | $0.39 / $2.34 | $0.015 / $0.09 | −96% |
| [Nano Banana (Gemini 2.5 Flash Image)](https://uberllm.dev/models/google/gemini-2.5-flash-image) | image | $0.075 / $0.625 | $0.003 / $0.025 | −96% |
| [MiniMax M2.7 Highspeed](https://uberllm.dev/models/minimax/minimax-m2.7-highspeed) | text | $0.54 / $2.16 | $0.03 / $0.12 | −94% |
| [Gemini 3.8 Flash](https://uberllm.dev/models/google/gemini-3.8-flash) | text | $0.2805 / $1.40 | $0.02475 / $0.1237 | −91% |
| [Gemini 3.1 Flash Lite](https://uberllm.dev/models/google/gemini-3.1-flash-lite) | text | $0.08 / $0.48 | $0.0075 / $0.045 | −91% |
| [Gemini 2.5 Flash](https://uberllm.dev/models/google/gemini-2.5-flash) | text | $0.027 / $0.225 | $0.003 / $0.025 | −89% |
| [GLM-5.2](https://uberllm.dev/models/z-ai/glm-5.2) | text | $0.00084 / $0.616 | $0.00012 / $0.088 | −86% |
| [Qwen3.5 Flash](https://uberllm.dev/models/qwen/qwen3.5-flash) | text | $0.09 / $0.36 | $0.014 / $0.056 | −84% |
| [Qwen3.5 Plus](https://uberllm.dev/models/qwen/qwen3.5-plus) | text | $0.234 / $1.40 | $0.0364 / $0.2184 | −84% |
| [Qwen: Qwen3.8 Max (0902)](https://uberllm.dev/models/qwen/qwen3.8-max-0902) | text | $0.22 / $0.66 | $0.04 / $0.12 | −82% |
| [Mistral: Mistral Large 4](https://uberllm.dev/models/mistralai/mistral-large-4-0) | text | $0.637 / $1.91 | $0.126 / $0.378 | −80% |
| [NVIDIA Nemotron 3 Ultra 550B](https://uberllm.dev/models/nvidia/nemotron-3-ultra-550b-a55b) | text | $0.4562 / $2.28 | $0.1062 / $0.5312 | −77% |
| [Google: Gemini 4 Argon](https://uberllm.dev/models/google/gemini-4-argon) | text | $1.00 / $5.00 | $0.24 / $1.20 | −76% |
| [Gemini 3.7 Flash](https://uberllm.dev/models/google/gemini-3.7-flash) | text | $0.3375 / $1.69 | $0.09 / $0.45 | −73% |
| [Kimi K2.6](https://uberllm.dev/models/moonshotai/kimi-k2.6) | text | $0.1885 / $0.9889 | $0.052 / $0.2728 | −72% |
| [Qwen: Qwen3.7 Flash](https://uberllm.dev/models/qwen/qwen3.7-flash) | text | $0.0297 / $0.1287 | $0.0096 / $0.0416 | −68% |
| [Grok 4.7](https://uberllm.dev/models/x-ai/grok-4.7) | text | $1.58 / $4.74 | $0.64 / $1.92 | −59% |
| [MiniMax M3.1 Flash](https://uberllm.dev/models/minimax/minimax-m3-1-flash) | text | $0.069 / $0.276 | $0.0285 / $0.114 | −59% |
| [Gemini 3 Flash Preview](https://uberllm.dev/models/google/gemini-3-flash-preview) | text | $0.105 / $0.63 | $0.045 / $0.27 | −57% |
| [GPT-5.6 Terra](https://uberllm.dev/models/openai/gpt-5.6-terra) | text | $1.32 / $7.92 | $0.60 / $3.60 | −55% |
| [Mistral Large](https://uberllm.dev/models/mistralai/mistral-large) | text | $0.42 / $1.26 | $0.20 / $0.60 | −52% |
| [Qwen3.8 Flash](https://uberllm.dev/models/qwen/qwen3.8-flash) | text | $0.03 / $0.094 | $0.015 / $0.047 | −50% |
| [Z.ai: GLM 5.3 FlashX](https://uberllm.dev/models/z-ai/glm-5.3-flashx) | text | $0.37 / $1.25 | $0.185 / $0.625 | −50% |
| [Kimi K2.7 Code](https://uberllm.dev/models/moonshotai/kimi-k2.7-code) | text | $0.306 / $1.79 | $0.168 / $0.98 | −45% |
| [MiniMax M3](https://uberllm.dev/models/minimax/minimax-m3) | text | $0.09 / $0.36 | $0.051 / $0.204 | −43% |
| [GPT Image 1.5 (Venice)](https://uberllm.dev/models/venice/gpt-image-1.5) | image | $0.26 / image | $0.156 / image | −40% |
| [Gemini 3.1 Pro](https://uberllm.dev/models/google/gemini-3.1-pro) | text | $1.80 / $10.80 | $1.10 / $6.60 | −39% |
| [Qwen 3.5 35B A3B](https://uberllm.dev/models/qwen/qwen3.5-35b-a3b) | text | $0.1562 / $1.00 | $0.0975 / $0.65 | in −38% / out −35% |
| [xAI Speech to Text v1 (Venice)](https://uberllm.dev/models/venice/xai-stt-v1) | text | $0.00153 / minute | $0.000963 / minute | −37% |
| [Qwen 3.6 35B A3B](https://uberllm.dev/models/qwen/qwen3-6-35b-a3b) | text | $0.063 / $0.63 | $0.04 / $0.40 | −37% |
| [Mistral Small 4](https://uberllm.dev/models/mistralai/mistral-small-4) | text | $0.15 / $0.60 | $0.096 / $0.384 | −36% |
| [Qwen 3.6 35B A3B (E2EE)](https://uberllm.dev/models/qwen/e2ee-qwen3-6-35b-a3b) | text | $0.182 / $1.18 | $0.1165 / $0.7552 | −36% |
| [Grok 4.3](https://uberllm.dev/models/x-ai/grok-4.3) | text | $0.3625 / $0.725 | $0.2375 / $0.475 | −34% |
| [Qwen 3 Coder 480B Turbo](https://uberllm.dev/models/qwen/qwen3-coder-turbo) | text | $0.2975 / $1.27 | $0.196 / $0.84 | −34% |
| [GPT-5.6 Luna](https://uberllm.dev/models/openai/gpt-5.6-luna) | text | $0.088 / $0.528 | $0.058 / $0.348 | −34% |
| [Devstral 2 123B](https://uberllm.dev/models/mistralai/devstral-2-123b) | text | $0.012 / $0.06 | $0.008 / $0.04 | −33% |
| [Claude Sonnet 5.5](https://uberllm.dev/models/anthropic/claude-sonnet-5.5) | text | $0.86 / $4.30 | $0.58 / $2.90 | −33% |
| [Seedance 2.0 (reference-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-reference-to-video) | video | $0.0792 / sec | $0.05368 / sec | −32% |
| [Qwen 3.8 Max](https://uberllm.dev/models/qwen/qwen-3-8-max) | text | $0.65 / $1.95 | $0.45 / $1.35 | −31% |
| [Inception: Mercury 2.5](https://uberllm.dev/models/inception/mercury-2.5) | text | $0.04 / $0.15 | $0.028 / $0.105 | −30% |
| [Gemini 3.1 Pro Preview](https://uberllm.dev/models/google/gemini-3.1-pro-preview) | text | $0.90 / $5.40 | $0.64 / $3.84 | −29% |
| [Veo3.1 Fast (image-to-video)](https://uberllm.dev/models/google/veo3-1-fast-image-to-video) | video | $0.165 / sec | $0.1188 / sec | −28% |
| [Claude Opus 5.5](https://uberllm.dev/models/anthropic/claude-opus-5.5) | text | $1.56 / $7.80 | $1.16 / $5.80 | −26% |
| [Grok Imagine Pro (Venice)](https://uberllm.dev/models/venice/grok-imagine-pro) | image | $0.0525 / image | $0.0392 / image | −25% |
| [Claude Sonnet 4.6](https://uberllm.dev/models/anthropic/claude-sonnet-4.6) | text | $1.80 / $9.00 | $1.35 / $6.75 | −25% |
| [Trinity Large Thinking](https://uberllm.dev/models/arcee-ai/trinity-large-thinking) | text | $0.30 / $1.00 | $0.225 / $0.7538 | −25% |
| [Claude Opus 5](https://uberllm.dev/models/anthropic/claude-opus-5) | text | $2.70 / $13.50 | $2.05 / $10.25 | −24% |
| [GPT-6 Luna Decisions (OpenAI)](https://uberllm.dev/models/openai/gpt-6-luna-decisions) | text | $0.10 / $0 | $0.076 / $0 | in −24% / out – |
| [Aion 3.0 Mini](https://uberllm.dev/models/aion-labs/aion-3-0-mini) | text | $0.658 / $1.32 | $0.504 / $1.01 | −23% |
| [Vidu Q3 Text-to-Video](https://uberllm.dev/models/vidu/vidu-q3-text-to-video) | video | $0.1933 / sec | $0.1547 / sec | −20% |
| [Qwen3 1.7B TTS](https://uberllm.dev/models/qwen/tts-qwen3-1-7b) | audio | $0.1125 / 1K chars | $0.09 / 1K chars | −20% |
| [Chatterbox HD TTS](https://uberllm.dev/models/resemble-ai/tts-chatterbox-hd) | audio | $0.05 / 1K chars | $0.04 / 1K chars | −20% |
| [Hunyuan Image 3.0 (Venice)](https://uberllm.dev/models/venice/hunyuan-image-v3) | image | $0.09 / image | $0.072 / image | −20% |
| [Seedance 2.0 (image-to-video)](https://uberllm.dev/models/bytedance/seedance-2-0-image-to-video) | video | $0.088 / sec | $0.0704 / sec | −20% |
| [Longcat Distilled (image-to-video)](https://uberllm.dev/models/meituan/longcat-distilled-image-to-video) | video | $0.018 / sec | $0.0144 / sec | −20% |
| [LongCat Distilled Text-to-Video](https://uberllm.dev/models/meituan/longcat-distilled-text-to-video) | video | $0.018 / sec | $0.0144 / sec | −20% |
| [Ministral 3B](https://uberllm.dev/models/mistralai/ministral-3-3b-instruct) | text | $0.005 / $0.005 | $0.004 / $0.004 | −20% |
| [Flux 1.1 Pro (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1-pro) | image | $0.03 / image | $0.024 / image | −20% |
| [Stable Diffusion XL (Venice, legacy)](https://uberllm.dev/models/venice/sdxl) | image | $0.01 / image | $0.008 / image | −20% |
| [Inworld 1.5 Max TTS](https://uberllm.dev/models/inworld/tts-inworld-1-5-max) | audio | $0.0125 / 1K chars | $0.01013 / 1K chars | −19% |
| [Qwen3 0.6B TTS](https://uberllm.dev/models/qwen/tts-qwen3-0-6b) | audio | $0.0875 / 1K chars | $0.07087 / 1K chars | −19% |
| [Kling O3.4k (image-to-video)](https://uberllm.dev/models/kling/kling-o3-4k-image-to-video) | video | $0.4633 / sec | $0.3753 / sec | −19% |
| [DeepSeek V4 Flash E2EE](https://uberllm.dev/models/deepseek/e2ee-deepseek-v4-flash) | text | $0.1456 / $0.2984 | $0.1183 / $0.2424 | −19% |
| [Thinking Machines: Inkling](https://uberllm.dev/models/thinking-machines/inkling) | text | $0.49 / $1.98 | $0.40 / $1.62 | −18% |
| [Firered Image (image-to-image)](https://uberllm.dev/models/xiaohongshu/firered-image-edit) | image | $0.034 / image | $0.028 / image | −18% |
| [Wan 2.7 (image-to-video)](https://uberllm.dev/models/wan/wan-2-7-image-to-video) | video | $0.08 / sec | $0.066 / sec | −17% |
| [MiMo-V2.6-Pro](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro) | text | $0.3001 / $0.6003 | $0.248 / $0.4959 | −17% |
| [Gemma 4 E2B](https://uberllm.dev/models/google/gemma-4-e2b) | text | $0.0024 / $0.0048 | $0.002 / $0.004 | −17% |
| [MiMo-V2.6-Flash](https://uberllm.dev/models/xiaomi/mimo-v2.6-flash) | text | $0.1176 / $0.2352 | $0.098 / $0.196 | −17% |
| [Aion 3.0](https://uberllm.dev/models/aion-labs/aion-3-0) | text | $2.55 / $5.10 | $2.13 / $4.26 | −16% |
| [DeepSeek V4 Flash](https://uberllm.dev/models/deepseek/deepseek-v4-flash) | text | $0.07826 / $0.1565 | $0.06643 / $0.1329 | −15% |
| [FLUX.2 Klein 4B](https://uberllm.dev/models/black-forest-labs/flux.2-klein-4b) | image | $0.015 / megapixel | $0.01275 / megapixel | −15% |
| [Meta: Muse Spark Open](https://uberllm.dev/models/meta-llama/muse-spark-open) | text | $1.09 / $3.70 | $0.925 / $3.15 | −15% |
| [GPT-5.5 Pro](https://uberllm.dev/models/openai/gpt-5.5-pro) | text | $24.90 / $149.40 | $21.60 / $129.60 | −13% |
| [FLUX.2 Flex](https://uberllm.dev/models/black-forest-labs/flux.2-flex) | image | $0.0594 / megapixel | $0.0516 / megapixel | −13% |
| [GPT-5.6 Luna Pro](https://uberllm.dev/models/openai/gpt-5.6-luna-pro) | text | $0.168 / $1.01 | $0.146 / $0.876 | −13% |
| [Kimi K3 Fast](https://uberllm.dev/models/moonshotai/kimi-k3-fast-api) | text | $3.82 / $19.12 | $3.33 / $16.65 | −13% |
| [Qwen 3 235B A22B Thinking 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-thinking-2507) | text | $0.1395 / $1.08 | $0.1215 / $0.945 | −13% |
| [Gemini 2.5 Pro](https://uberllm.dev/models/google/gemini-2.5-pro) | text | $0.40 / $3.20 | $0.35 / $2.80 | −13% |
| [Claude Fable 5.1](https://uberllm.dev/models/anthropic/claude-fable-5.1) | text | $6.50 / $32.50 | $5.70 / $28.50 | −12% |
| [Mercury 2](https://uberllm.dev/models/inception/mercury-2) | text | $0.225 / $0.675 | $0.1975 / $0.5925 | −12% |
| [Grok Imagine 1.5 Image To Video Private (image-to-video)](https://uberllm.dev/models/x-ai/grok-imagine-1-5-image-to-video-private) | video | $0.09 / sec | $0.0792 / sec | −12% |
| [GPT-5.4 Pro](https://uberllm.dev/models/openai/gpt-5.4-pro) | text | $20.10 / $120.60 | $17.70 / $106.20 | −12% |
| [Grok 4.6](https://uberllm.dev/models/x-ai/grok-4.6) | text | $1.78 / $5.34 | $1.58 / $4.74 | −11% |
| [GLM 5.2 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5-2-p) | text | $1.57 / $5.17 | $1.40 / $4.60 | −11% |
| [Qwen Image 2 Pro (image-to-image)](https://uberllm.dev/models/qwen/qwen-image-2-pro-edit) | image | $0.09 / image | $0.08 / image | −11% |
| [ElevenLabs Turbo v2.5 TTS (Venice)](https://uberllm.dev/models/venice/elevenlabs-tts-turbo-v2-5) | audio | $0.05625 / 1K chars | $0.05 / 1K chars | −11% |
| [Flux 1.1 (Venice, legacy)](https://uberllm.dev/models/venice/flux-1.1) | image | $0.009 / image | $0.008 / image | −11% |
| [MiMo-V2.6-Pro-UltraSpeed](https://uberllm.dev/models/xiaomi/mimo-v2.6-pro-ultraspeed) | text | $4.31 / $8.61 | $3.83 / $7.66 | −11% |
| [Claude Opus 4.8 Fast](https://uberllm.dev/models/anthropic/claude-opus-4.8-fast) | text | $7.50 / $37.50 | $6.70 / $33.50 | −11% |
| [GPT-5.6 Sol](https://uberllm.dev/models/openai/gpt-5.6-sol) | text | $1.92 / $9.60 | $1.72 / $8.60 | −10% |
| [GPT-6 Sol Pro](https://uberllm.dev/models/openai/gpt-6-sol-pro) | text | $1.92 / $9.60 | $1.72 / $8.60 | −10% |
| [OpenAI: GPT-6.1 Sol Pro](https://uberllm.dev/models/openai/gpt-6.1-sol-pro) | text | $1.92 / $9.60 | $1.72 / $8.60 | −10% |
| [GPT OSS 120B](https://uberllm.dev/models/openai/e2ee-gpt-oss-120b-p) | text | $0.1001 / $0.5005 | $0.0897 / $0.4485 | −10% |
| [Venice TTS 1 (legacy alias)](https://uberllm.dev/models/venice/tts-1) | audio | $0.00315 / 1K chars | $0.002835 / 1K chars | −10% |
| [Kling V3 Pro (image-to-video)](https://uberllm.dev/models/kling/kling-v3-pro-image-to-video) | video | $0.165 / sec | $0.1833 / sec | +11% |
| [Veo 3.1 Fast Text-to-Video](https://uberllm.dev/models/google/veo3-1-fast-text-to-video) | video | $0.1485 / sec | $0.165 / sec | +11% |
| [Kling V3 Standard (image-to-video)](https://uberllm.dev/models/kling/kling-v3-standard-image-to-video) | video | $0.126 / sec | $0.14 / sec | +11% |
| [Qwen3.8 2.4T A95B](https://uberllm.dev/models/qwen/qwen3.8-2.4t-a95b) | text | $0.18 / $0.54 | $0.20 / $0.60 | +11% |
| [MiniMax Music 2.6 (Venice)](https://uberllm.dev/models/venice/minimax-music-v26) | text | $0.216 / request | $0.24 / request | +11% |
| [Qwen Image (Venice)](https://uberllm.dev/models/venice/qwen-image) | image | $0.027 / image | $0.03 / image | +11% |
| [GLM-5 Turbo](https://uberllm.dev/models/z-ai/glm-5-turbo) | text | $0.588 / $1.96 | $0.66 / $2.20 | +12% |
| [Flux 2 Max — Edit (Venice)](https://uberllm.dev/models/black-forest-labs/flux-2-max-edit) | image | $0.1615 / image | $0.19 / image | +18% |
| [GPT Image 1.5 — Edit (Venice)](https://uberllm.dev/models/venice/gpt-image-1-5-edit) | image | $0.306 / image | $0.36 / image | +18% |
| [MMAudio V2 Text-to-Audio (Venice)](https://uberllm.dev/models/venice/mmaudio-v2-text-to-audio) | text | $0.0085 / request | $0.01 / request | +18% |
| [Wan 2.7 Pro (image-to-video)](https://uberllm.dev/models/wan/wan-2-7-pro-image-to-video) | video | $0.102 / sec | $0.12 / sec | +18% |
| [Recraft V4 (Venice)](https://uberllm.dev/models/venice/recraft-v4) | image | $0.04 / image | $0.0475 / image | +19% |
| [Grok 4.20 Multi-Agent Beta](https://uberllm.dev/models/x-ai/grok-4.20-multi-agent-beta) | text | $0.95 / $1.90 | $1.14 / $2.27 | +20% |
| [MoonshotAI: Kimi K3.1 Pro](https://uberllm.dev/models/moonshotai/kimi-k3.1-pro) | text | $0.40 / $2.00 | $0.48 / $2.40 | +20% |
| [Claude Haiku 5.5](https://uberllm.dev/models/anthropic/claude-haiku-5.5) | text | $0.056 / $0.28 | $0.069 / $0.345 | +23% |
| [Gemma 3 27B E2EE](https://uberllm.dev/models/google/e2ee-gemma-3-27b) | text | $0.056 / $0.20 | $0.07 / $0.25 | +25% |
| [Gemma 4 31B (E2EE)](https://uberllm.dev/models/google/e2ee-gemma-4-31b) | text | $0.10 / $0.30 | $0.125 / $0.375 | +25% |
| [ElevenLabs TTS Multilingual v2 (Venice audio)](https://uberllm.dev/models/venice/elevenlabs-tts-multilingual-v2) | text | $0.096 / request | $0.12 / request | +25% |
| [GLM 5.1 E2EE](https://uberllm.dev/models/z-ai/e2ee-glm-5.1) | text | $0.44 / $1.66 | $0.55 / $2.08 | +25% |
| [OpenAI: GPT-6.1 Terra](https://uberllm.dev/models/openai/gpt-6.1-terra) | text | $0.47 / $2.35 | $0.59 / $2.95 | +26% |
| [GLM 5.1](https://uberllm.dev/models/z-ai/glm-5.1) | text | $0.154 / $0.484 | $0.196 / $0.616 | +27% |
| [GPT-5.3 Codex](https://uberllm.dev/models/openai/gpt-5.3-codex) | text | $0.63 / $5.04 | $0.805 / $6.44 | +28% |
| [Claude Opus 4.7](https://uberllm.dev/models/anthropic/claude-opus-4.7) | text | $1.95 / $9.75 | $2.55 / $12.75 | +31% |
| [Gemini 3.5 Flash Lite](https://uberllm.dev/models/google/gemini-3-5-flash-lite) | text | $0.15 / $1.25 | $0.198 / $1.65 | +32% |
| [Qwen: Qwen3.8 Omni Flash](https://uberllm.dev/models/qwen/qwen3.8-omni-flash) | text | $0.018 / $0.0564 | $0.024 / $0.0752 | +33% |
| [GLM 4.5](https://uberllm.dev/models/z-ai/glm-4.5) | text | $0.018 / $0.066 | $0.024 / $0.088 | +33% |
| [Meta: Muse Wonder](https://uberllm.dev/models/meta-llama/muse-wonder) | text | $2.04 / $10.20 | $2.80 / $14.00 | +37% |
| [Recraft V4 Pro (Venice)](https://uberllm.dev/models/venice/recraft-v4-pro) | image | $0.203 / image | $0.29 / image | +43% |
| [Qwen Image 2 Pro (Venice)](https://uberllm.dev/models/venice/qwen-image-2-pro) | image | $0.07 / image | $0.10 / image | +43% |
| [Ministral 14B 3.0](https://uberllm.dev/models/mistralai/ministral-3-14b-instruct) | text | $0.04 / $0.04 | $0.058 / $0.058 | +45% |
| [Magistral Small 2509](https://uberllm.dev/models/mistralai/magistral-small-2509) | text | $0.01 / $0.03 | $0.015 / $0.045 | +50% |
| [Gemma 4 31B](https://uberllm.dev/models/google/gemma-4-31b) | text | $0.0024 / $0.0072 | $0.0036 / $0.0108 | +50% |
| [Gemini 3.6 Flash](https://uberllm.dev/models/google/gemini-3-6-flash) | text | $0.3975 / $1.99 | $0.60 / $3.00 | +51% |
| [Claude Opus 4.6](https://uberllm.dev/models/anthropic/claude-opus-4.6) | text | $1.60 / $8.00 | $2.45 / $12.25 | +53% |
| [Orpheus TTS](https://uberllm.dev/models/canopy-labs/tts-orpheus) | audio | $0.03125 / 1K chars | $0.05 / 1K chars | +60% |
| [GPT-6.1 Sol](https://uberllm.dev/models/openai/gpt-6.1-sol) | text | $0.78 / $3.90 | $1.28 / $6.40 | +64% |
| [GPT-4o Mini](https://uberllm.dev/models/openai/gpt-4o-mini) | text | $0.0105 / $0.042 | $0.018 / $0.072 | +71% |
| [GPT-4o](https://uberllm.dev/models/openai/gpt-4o) | text | $0.35 / $1.40 | $0.60 / $2.40 | +71% |
| [Ministral 3 8B](https://uberllm.dev/models/mistralai/ministral-3-8b-instruct) | text | $0.003 / $0.003 | $0.006 / $0.006 | +100% |
| [GPT OSS Safeguard 20B](https://uberllm.dev/models/openai/gpt-oss-safeguard-20b) | text | $0.00075 / $0.003 | $0.0015 / $0.006 | +100% |
| [Qwen 3.8 27B](https://uberllm.dev/models/qwen/qwen-3-8-27b) | text | $0.009 / $0.1125 | $0.0195 / $0.2437 | +117% |
| [Meta: Muse Spark 1.2](https://uberllm.dev/models/meta-llama/muse-spark-1.2) | text | $0.275 / $0.935 | $0.6375 / $2.17 | +132% |
| [MiniMax M2.5](https://uberllm.dev/models/minimax/minimax-m2.5) | text | $0.0162 / $0.057 | $0.0378 / $0.133 | +133% |
| [GPT-OSS 120B](https://uberllm.dev/models/openai/gpt-oss-120b) | text | $0.0035 / $0.015 | $0.0084 / $0.036 | +140% |
| [Gemma 3 27B](https://uberllm.dev/models/google/gemma-3-27b-it) | text | $0.0064 / $0.016 | $0.016 / $0.04 | +150% |
| [Mistral Large 3](https://uberllm.dev/models/mistralai/mistral-large-3) | text | $0.03 / $0.09 | $0.075 / $0.225 | +150% |
| [Meta: Muse Spark 1.1](https://uberllm.dev/models/meta-llama/muse-spark-1.1) | text | $0.3625 / $1.23 | $0.9125 / $3.10 | +152% |
| [Palmyra Vision 7B](https://uberllm.dev/models/writer/palmyra-vision-7b) | text | $0.006 / $0.024 | $0.0165 / $0.066 | +175% |
| [GLM-4.7](https://uberllm.dev/models/z-ai/glm-4.7) | text | $0.0825 / $0.33 | $0.2365 / $0.946 | +187% |
| [Qwen3 Coder 30B A3B Instruct](https://uberllm.dev/models/qwen/qwen3-coder-30b-a3b-instruct) | text | $0.003 / $0.012 | $0.009 / $0.036 | +200% |
| [Qwen3 32B](https://uberllm.dev/models/qwen/qwen3-32b) | text | $0.0016 / $0.0056 | $0.0056 / $0.0196 | +250% |
| [DeepSeek V3.2](https://uberllm.dev/models/deepseek/deepseek-v3.2) | text | $0.0078 / $0.0114 | $0.0286 / $0.0418 | +267% |
| [NVIDIA Nemotron Nano 9B v2](https://uberllm.dev/models/nvidia/nemotron-nano-9b-v2) | text | $0.0018 / $0.0069 | $0.0066 / $0.0253 | +267% |
| [Qwen 3 235B A22B Instruct 2507](https://uberllm.dev/models/qwen/qwen3-235b-a22b-2507) | text | $0.0056 / $0.03 | $0.02187 / $0.1172 | +291% |
| [Qwen 3 Coder 480b](https://uberllm.dev/models/qwen/qwen3-coder) | text | $0.006 / $0.02 | $0.024 / $0.08 | +300% |
| [Qwen3 VL 235B A22B](https://uberllm.dev/models/qwen/qwen3-vl-235b-a22b-instruct) | text | $0.0042 / $0.038 | $0.0189 / $0.171 | +350% |
| [Meta: Muse Spark 1.3 Contributor](https://uberllm.dev/models/meta-llama/muse-spark-1.3-contributor) | text | $0.007 / $0.014 | $0.036 / $0.072 | +414% |
| [Gemma 4 31B IT](https://uberllm.dev/models/google/gemma-4-31b-it) | text | $0.0156 / $0.0468 | $0.084 / $0.252 | +438% |
| [Qwen3 Coder Next](https://uberllm.dev/models/qwen/qwen3-coder-next) | text | $0.0024 / $0.016 | $0.0132 / $0.088 | +450% |
| [GPT OSS Safeguard 120B](https://uberllm.dev/models/openai/gpt-oss-safeguard-120b) | text | $0.0045 / $0.018 | $0.0255 / $0.102 | +467% |
| [Meta: Muse Spark 1.3](https://uberllm.dev/models/meta-llama/muse-spark-1.3) | text | $0.10 / $0.34 | $0.6125 / $2.08 | +512% |
| [GLM-4.6](https://uberllm.dev/models/z-ai/glm-4.6) | text | $0.0172 / $0.07 | $0.1591 / $0.6475 | +825% |
| [GLM 4.7 Flash](https://uberllm.dev/models/z-ai/glm-4.7-flash) | text | $0.001815 / $0.012 | $0.01694 / $0.112 | +833% |
| [DeepSeek V3.1](https://uberllm.dev/models/deepseek/deepseek-v3.1) | text | $0.0075 / $0.0285 | $0.075 / $0.285 | +900% |
| [NVIDIA Nemotron 3 Nano 30B](https://uberllm.dev/models/nvidia/nemotron-3-nano-30b-a3b) | text | $0.0015 / $0.006 | $0.01725 / $0.069 | +1050% |
| [Kimi K2 Thinking](https://uberllm.dev/models/moonshotai/kimi-k2-thinking) | text | $0.012 / $0.05 | $0.15 / $0.625 | +1150% |
| [GPT-OSS 20B](https://uberllm.dev/models/openai/gpt-oss-20b) | text | $0.0003 / $0.0013 | $0.0039 / $0.0169 | +1200% |
| [Gemma 3 12B IT](https://uberllm.dev/models/google/gemma-3-12b-it) | text | $0.001 / $0.003 | $0.0215 / $0.0645 | +2050% |
| [MiniMax M2.1](https://uberllm.dev/models/minimax/minimax-m2.1) | text | $0.003 / $0.012 | $0.315 / $1.26 | +10400% |

</details>

