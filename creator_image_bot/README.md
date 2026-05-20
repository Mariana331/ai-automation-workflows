# Creator Image Bot

AI-powered image generation bot built with :contentReference[oaicite:0]{index=0}, Telegram Bot API, AssemblyAI, OpenAI, and DALL·E.

## 📌 Overview

Creator Image Bot allows users to generate AI images directly from voice messages in Telegram.

The user records an audio message describing the desired image, and the workflow automatically:

- uploads the audio file
- extracts audio URL
- sends audio to AssemblyAI for transcription
- processes the generated text with an AI agent
- sends the prompt to DALL·E
- returns the generated image back to Telegram

---

## Workflow Preview

![Workflow](/creator_image_bot/photo_2026-05-20_11-22-38.jpg)

## Demo

![Demo](/creator_image_bot/image.png)

## ⚡ Features

- Voice-to-image AI generation
- Telegram bot integration
- Audio transcription with AssemblyAI
- AI prompt processing
- DALL·E image generation
- Automated Telegram responses
- End-to-end workflow automation

---

## 🔄 Workflow Logic

1. User sends a voice message in Telegram
2. Workflow downloads audio file
3. Audio URL is extracted
4. Audio is sent to AssemblyAI API
5. Speech is converted into text
6. AI agent processes and improves the prompt
7. Prompt is sent to DALL·E
8. Generated image is returned to Telegram

---

## 🧠 AI Processing

The AI agent:

- analyzes transcribed text
- improves image prompts
- structures prompt for better image quality
- prepares data for DALLE generation

---

## 🧰 Tech Stack

- n8n
- Telegram Bot API
- OpenAI API
- DALLE
- AssemblyAI API
- AI Agents

---
