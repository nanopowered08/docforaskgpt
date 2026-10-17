---
layout: page
title: Configuration cuz.
permalink: /configuration/
---

Some dudes want to know what is inside the configuration. I can't be more transparent so I have to do this.

## The model provider.

For terrible-harness to identify your provider and hit the correct endpoint we check what provider you use.

If the provider is custom-made, I'd bet you have to modify the config.json.

When your model provider is selected, we either use the Vercel AI SDK or the Gen AI SDK. (Google-specific)

## The API key.

Yes, it's in config.json. You don't pass around config.json you see.

It's to authenticate AskGPT with your model provider every time you ask it a question.

## The chat template. (applies to custom models)

This is special. It's the payload sent to the server when you make a custom API request.

The original Gemini implementation was made this way, by the way
