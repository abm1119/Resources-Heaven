# Voice, Speech, and Audio AI Tools and Models

## Quick Navigation Menu

- [1. Ultra-Light CPU & Edge TTS (<200M)](#1-ultra-light-cpu--edge-tts-200m)
- [2. Open-Source Expressive TTS](#2-open-source-expressive-tts)
- [3. Proprietary Cloud TTS](#3-proprietary-cloud-tts)
- [4. Speech-to-Speech & Voice Foundation Models](#4-speech-to-speech--voice-foundation-models)
- [5. STT / ASR - Edge & Tiny](#5-stt--asr---edge--tiny)
- [6. STT / ASR - Multilingual Open Models](#6-stt--asr---multilingual-open-models)
- [7. STT / ASR - Proprietary Enterprise APIs](#7-stt--asr---proprietary-enterprise-apis)
- [8. Voice Agent Platforms & Orchestrators](#8-voice-agent-platforms--orchestrators)

---

### 1. Ultra-Light CPU & Edge TTS (<200M)
- **[KittenTTS v0.8](https://github.com/KittenML/KittenTTS)** : Sub-25MB voice model used for real-time speech generation on low-power CPUs and Raspberry Pi.
- **[MOSS-TTS-Nano-100M](https://github.com/OpenMOSS/MOSS-TTS-Nano)** : 100M-parameter CPU model used for multilingual voice cloning and local browser text readers.
- **[Pocket TTS - Kyutai](https://github.com/kyutai-labs/pocket-tts)** : 100M-parameter speech engine used for fast offline voice cloning on consumer laptops and devices.
- **[Pocket-TTS Generate CLI](https://github.com/kyutai-labs/pocket-tts)** : Standalone command-line tool used to generate cloned speech locally from your terminal without the cloud.
- **[Kokoro 82M](https://huggingface.co/hexgrad/Kokoro-82M)** : 82M-parameter open model used for lightweight, high-quality English voice synthesis on CPUs.
- **[Piper TTS](https://github.com/rhasspy/piper)** : Fast, compact VITS engine used for local, offline voice synthesis in smart homes and embedded systems.
- **[Soprano TTS (SuproTTS v1.5)](https://github.com/ekwek1/soprano)** : 80M-parameter engine used for 20x real-time speech generation on regular CPUs without a GPU.
- **[Soprano-Factory](https://github.com/ekwek1/soprano-factory)** : Open-source toolkit used to train and fine-tune custom lightweight Soprano TTS models on your own audio.
- **[NeuTTS](https://github.com/neuphonic/neutts)** : Lightweight neural speech engine used for private on-device voice synthesis and voice replication.
- **[NeuTTS Air](https://github.com/neuphonic/neutts-air)** : 0.5B-parameter GGUF model used for fast 3-second voice cloning on phones, laptops, and Raspberry Pi.

---

### 2. Open-Source Expressive TTS
- **[Hume TADA-1B](https://huggingface.co/HumeAI/tada-1b)** : 1B-parameter model using 1:1 token alignment to synthesize speech without audio hallucinations.
- **[Hume TADA-3B-ml + TADA-Codec](https://huggingface.co/HumeAI/tada-3b-ml)** : 3B multilingual model used for high-fidelity speech generation across 9 languages.
- **[Fish Audio S2-Pro / OpenAudio S2](https://github.com/fishaudio/fish-speech)** : 4.4B-parameter model used for zero-shot voice cloning and emotion control across 80+ languages.
- **[OpenAudio S1 (Fish Speech S1)](https://github.com/fishaudio/fish-speech)** : Dual-AR foundation model used for multilingual voice cloning and emotion-tagged speech synthesis.
- **[Qwen3-TTS 0.6B/1.7B](https://github.com/QwenLM/Qwen3-TTS)** : Autoregressive speech model used for custom voice design, voice cloning, and low-latency streaming.
- **[MOSS-TTS 8B](https://github.com/OpenMOSS/MOSS-TTS)** : Large 8B voice model used for long-form speech generation with syllable-level duration control.
- **[MOSS-TTSD](https://github.com/OpenMOSS/MOSS-TTSD)** : Multi-speaker dialogue model used to generate natural, back-and-forth spoken conversations up to 16 minutes.
- **[Higgs Audio v3 / Chroma 4B](https://huggingface.co/bosonai/higgs-audio-v3-tts-4b)** : 4B conversational audio model used to generate empathetic, natural speech instead of robotic reading.
- **[Chatterbox](https://github.com/resemble-ai/chatterbox)** : Open-source production TTS toolkit used for natural voice synthesis with built-in audio watermarking.
- **[MisoTTS 8B](https://github.com/MisoLabsAI/MisoTTS)** : 8B expressive speech model used for dramatic character acting, storytelling, and intense emotions.
- **[Alibaba CosyVoice 3](https://github.com/FunAudioLLM/CosyVoice)** : Fast streaming model used for cross-lingual voice cloning and low-latency voice agent backends.
- **[Spark-TTS / VoxCPM2](https://github.com/SparkAudio/Spark-TTS)** : Tokenizer-free speech model used for flexible voice design and realistic acoustic cloning.
- **[Orpheus TTS 3B](https://github.com/canopyai/Orpheus-TTS)** : Llama-based audio model used to stream conversational speech at ~200ms latency via vLLM.
- **[Dia 1.6B - Nari Labs](https://github.com/nari-labs/dia)** : Two-speaker dialogue model used to synthesize natural conversations with unscripted laughs and sighs.
- **[IndexTTS2](https://github.com/index-tts/index-tts)** : 1B+ expressive Chinese/English model used for precise duration control and emotion-prompted voice synthesis.
- **[Coqui TTS & XTTS-v2](https://github.com/coqui-ai/TTS)** : Classic open toolkit used for zero-shot voice cloning and offline speech synthesis in 17+ languages.
- **[Kani TTS](https://github.com/nineninesix-ai/kani-tts)** : 450M-parameter local model used for low-latency, expressive speech generation on consumer GPUs.

---

### 3. Proprietary Cloud TTS
- **[Voxtral TTS - Mistral](https://mistral.ai/news/voxtral)** : Compact 9-language voice model from Mistral used as a fast speech generator for conversational assistants.
- **[ElevenLabs Turbo v2.5 / Flash v2.5](https://elevenlabs.io)** : Industry-standard cloud TTS platform used for studio-grade voice cloning, dubbing, and low-latency audio.
- **[Cartesia Sonic 3](https://cartesia.ai)** : Ultra-fast cloud speech API used for human-like voice agents requiring near-instant (16ms) response times.
- **[OpenAI gpt-4o-mini-tts / gpt-realtime-2](https://platform.openai.com/docs/guides/text-to-speech)** : Native multimodal voice API used for conversational agents with natural tone, tool calling, and barge-in support.
- **[Google Chirp 3 / Gemini TTS](https://cloud.google.com/text-to-speech)** : Cloud enterprise speech engine used for studio-quality long-form audiobooks across 30+ languages.
- **[Minimax T2A-01-HD / Speech-02](https://www.minimax.io/audio)** : High-definition 44.1kHz audio API used for emotionally rich Chinese and English speech generation.
- **[Hume Octave 2 / EVI](https://www.hume.ai)** : Empathic voice service used to generate speech with fine-grained control over 9 emotional dimensions.
- **[Fish.audio](https://fish.audio/)** : Commercial cloud platform used for instant voice cloning, narration, and custom voice character creation.
- **[Voice Killer](https://voicekiller.com/)** : Web voice generator used to create expressive character audio using plain-text acting instructions.

---

### 4. Speech-to-Speech & Voice Foundation Models
- **[Kyutai Moshi 1.1](https://github.com/kyutai-labs/moshi)** : 7B full-duplex speech model used for continuous, two-way spoken conversation with 80ms latency.
- **[Sesame CSM-1B](https://github.com/SesameAILab/csm)** : 1B conversational model used to generate speech with natural pauses, fillers, and contextual laughter.
- **[Meta Spirit LM / Spirit LM Expressive](https://github.com/facebookresearch/spirit-lm)** : 7B speech-text foundation model used to produce expressive vocal inflections and speaking styles.
- **[OpenAI GPT-Live-1 / Live Mini](https://openai.com/index/introducing-gpt-live/)** : End-to-end voice model used for real-time conversation with simultaneous listening, speaking, and reasoning.
- **[Google Gemini Live API](https://ai.google.dev/gemini-api/docs/live)** : Bidirectional multimodal API used for voice agents that support interruptions, screen vision, and tool use.
- **[Hume AI EVI Demo](https://demo.hume.ai/)** : Interactive web sandbox used to test empathic, emotionally aware speech-to-speech conversations.

---

### 5. STT / ASR - Edge & Tiny
- **[Moonshine Tiny / Base](https://huggingface.co/UsefulSensors/moonshine-tiny)** : Lightweight speech-to-text models used for fast, variable-length transcription on edge devices.
- **[Moonshine v2 (Tiny / Small / Medium / Streaming)](https://github.com/moonshine-ai/moonshine)** : Streaming ASR models used for low-latency, bounded-memory transcription on edge hardware.
- **[GigaAM v3 (CTC / RNN-T / E2E)](https://huggingface.co/ai-sage/GigaAM-v3)** : 220M-parameter Russian speech models used for high-accuracy CPU transcription with ONNX.
- **[SenseVoice Small](https://github.com/FunAudioLLM/SenseVoice)** : 234M model used for ultra-fast transcription, language detection, emotion recognition, and audio event tagging.
- **[Whisper Large v3 Turbo / Distil-Whisper v3.5](https://github.com/openai/whisper)** : Fast multilingual speech-to-text models used for accurate transcription and subtitling with lower VRAM.

---

### 6. STT / ASR - Multilingual Open Models
- **[NVIDIA Parakeet TDT 0.6B v3](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3)** : FastConformer model used for ultra-fast (3380 RTFx) transcription across 25 European languages.
- **[NVIDIA Canary 1B v2](https://huggingface.co/nvidia/canary-1b-v2)** : 1B-parameter model used for high-accuracy multilingual transcription and translation with word timestamps.
- **[NVIDIA Canary-Qwen 2.5B](https://huggingface.co/nvidia/canary-qwen-2.5b)** : Qwen-based speech model used for context-aware transcription and direct audio reasoning.
- **[Cohere Transcribe 03-2026](https://huggingface.co/CohereLabs/cohere-transcribe-03-2026)** : 2B Conformer model used for benchmark-topping transcription across 14 enterprise languages.
- **[Voxtral Mini 3B / Small 24B / Mini Transcribe](https://huggingface.co/mistralai/Voxtral-Mini-3B-2507)** : Audio models from Mistral used for transcription, audio summarization, and direct voice function calls.
- **[Qwen3-ASR 0.6B/1.7B + Qwen2-Audio](https://github.com/QwenLM/Qwen2-Audio)** : Multilingual audio-language models used for transcription across 52 languages and audio understanding.
- **[IBM Granite Speech 3.3 2B/8B](https://huggingface.co/ibm-granite/granite-speech-3.3-8b)** : Open speech-LLMs used to combine accurate transcription with direct spoken reasoning for AI agents.
- **[Kyutai STT 2.6B en](https://huggingface.co/kyutai/stt-2.6b-en)** : 2.6B streaming speech recognition model used for low-latency English voice agent pipelines.

---

### 7. STT / ASR - Proprietary Enterprise APIs
- **[Deepgram Nova-3 / Flux](https://deepgram.com)** : Enterprise speech-to-text API used for accurate, ultra-low-latency real-time voice agent transcription.
- **[AssemblyAI Universal-2 / Conformer-2](https://www.assemblyai.com)** : Enterprise transcription API used for speaker diarization, PII redaction, and audio summarization.
- **[Gladia](https://www.gladia.io)** : Real-time audio API used for meeting transcription, live translation, and complex language switching.
- **[Speechmatics Ursa 2](https://www.speechmatics.com/)** : Cloud speech engine used for accurate real-time transcription across diverse regional accents and languages.
- **[Soniox](https://soniox.com/)** : Enterprise voice API used for high-accuracy transcription of technical jargon and multi-speaker meetings.
- **[Rev AI Fusion](https://www.rev.ai)** : Enterprise speech API used for accurate English transcription, meeting notes, and human review workflows.

---

### 8. Voice Agent Platforms & Orchestrators
- **[Google AI Studio](https://aistudio.google.com/)** : Web developer console used to test, prototype, and build live bidirectional voice apps with Gemini.
- **[ElevenLabs Conversational AI / ElevenAgents](https://elevenlabs.io/conversational-ai)** : Turnkey platform used to build, customize, and deploy interactive voice bots with phone support.
- **[LiveKit Agents](https://docs.livekit.io/agents/)** : Open-source framework used to build real-time voice agents over WebRTC with turn-taking and interruption handling.
- **[VoiceStudio (formerly OmniVoice Studio)](https://voicestudio.sh/)** : Fully local desktop app used to run 25+ speech models for private voice cloning, dubbing, and audiobooks.
- **[Vapi](https://vapi.ai)** : Developer voice platform used to build and deploy low-latency inbound and outbound phone calling agents.
- **[Retell AI](https://www.retellai.com/)** : Voice API platform used to deploy ultra-fast conversational telephone agents connected to business software.
- **[Synthflow AI](https://synthflow.ai/)** : No-code voice builder used by businesses to create telephone bots for appointment booking and customer care.
- **[Bland AI](https://www.bland.ai)** : Telephony infrastructure platform used to programmatically send and receive millions of automated AI phone calls.

---

### 9. Inference Providers & Hubs
- **[Together AI](https://www.together.ai/)** : Cloud inference provider used to host and serve open-source audio and language models at scale.
- **[Groq](https://groq.com/)** : Ultra-fast LPU hardware platform used to run Whisper speech-to-text with near-instant speeds.
- **[Fal.ai](https://fal.ai/)** : Cloud media inference platform used for real-time generative audio pipelines and streaming TTS.
- **[Replicate](https://replicate.com/)** : Serverless platform used to run open-source voice and audio models through simple cloud API endpoints.
- **[Modal](https://modal.com/)** : Serverless cloud compute used to build and scale custom Python voice pipelines and batch audio workers.
- **[Baseten](https://www.baseten.co/)** : Model deployment platform used to deploy and auto-scale open speech models like Whisper on dedicated GPUs.
- **[Hugging Face Inference & Hub](https://huggingface.co/models?pipeline_tag=automatic-speech-recognition)** : Central community hub used to find, test, and host thousands of open-source speech models.