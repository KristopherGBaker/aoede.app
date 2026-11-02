---
title: "Privacy"
description: "What Aoede keeps, what it sends, and where."
summary: "What Aoede keeps, what it sends, and where."
layout: article
---

Aoede has no servers and no accounts of its own. It collects nothing about you, contains no
analytics or advertising, and does not track you.

## What stays on your device

The documents and books you import, your library, reading positions, bookmarks, notes, study
cards, review history and settings are kept in the app's own storage on your device. Speech is
made on your device too, by Apple's voices or by the Kokoro voice, and so is the highlight that
follows it.

## What goes where, and why

Aoede only reaches the network for the things below, and only when you use them.

- **Voice and dictionary downloads.** The first time you choose the Kokoro voice, Aoede downloads
  its model from Hugging Face. The first time you read Japanese, it downloads a reading
  dictionary (Open JTalk's, from GitHub) for furigana and pronunciation. Nothing about you is sent
  with these requests beyond what any download sends.
- **Project Gutenberg.** If you browse free books, your searches go to Gutendex (gutendex.com), a
  public catalogue of Project Gutenberg, and the books and covers you open are downloaded from
  Project Gutenberg.
- **The assistant.** The assistant runs on your device with Apple Intelligence by default, and then
  nothing leaves it. You can instead point it at a local server you run (such as Ollama or LM
  Studio), and requests go only to that server. If you add your own API key for OpenAI,
  OpenRouter or Anthropic, Aoede asks you each time before it sends a passage to that provider,
  and what the provider does with it is covered by its own privacy policy. Your keys are stored
  in the Keychain on this device and are not synced.

## Beta builds

If you test a TestFlight build, Apple shares the crash reports and feedback you choose to send
with the developer, as described in TestFlight's own terms.

## Deleting your data

Deleting the app removes everything it stored on your device.

## Contact

Questions: aoede@krisbaker.com.
