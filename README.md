# generative-ai

## Overview

Generative AI technologies such as ChatGPT, GPT-4, and Stable Diffusion have gained significant attention and made an impact across many aspects of life. This repository assembles projects I have created to demonstrate generative AI capabilities from different perspectives.

**Key Aspects:**

- As there are many existing works utilizing proprietary LLMs like ChatGPT and GPT-4, this repository focuses primarily on open source LLMs.

- Apart from LLMs, other technologies utilized will aim to leverage open source options where possible, such as text-to-speech and vision models.

- The goal is to cover diverse use cases highlighting the capabilities of generative AI LLMs.

## Project/Notebook List

### 1. Chat with Open Source LLM and Audio

This notebook enables conversations with an AI assistant using audio input and output. The assistant is powered by the open source LLM Mistral-7B-Instruct, with the ability to switch models.

### 2. Chat over documents with Open Source LLM

This notebook facilitates conversations with an AI assistant to answer questions about a uploaded PDF. It uses the open source LLM Mistral-7B-Instruct, again with model switching capabilities.

### 3. Fine-tuning Mistral 7B Instruct Model

This notebook demonstrates fine-tuning the Mistral 7B pretrained language model on a medical dataset to create a model that can respond to patient medical queries.

### 4. Autogen Multi-Agent Chat

This notebook illustrates using the Autogen library to efficiently configure conversational scenarios with distinct agents in defined roles. Although Autogen use cases primarily involve resolving issues related to coding or tools, the conversation scenarios presented here aim to demonstrate that by establishing background context and distinct roles for different agents, the dialogue itself can provide end-users with meaningful insights beyond just technical support.

### 5. Create Voice Over for Video using LLaVa and TTS

This notebook uses open source vision model and speech synthesis to automatically create video narration. It extracts frames, generates descriptions with LLaVA, summarizes into a prompt for GPT-4, synthesizes audio with SileroTTS, and combines with the original video.
