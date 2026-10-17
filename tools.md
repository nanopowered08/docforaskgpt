---
layout: page
title: Tools cus why not
permalink: /tools/
---

# Tools cus why not

Based on your AI provider your model of choice may be able to use the tools or are too lazy to use it.

## For Gemini Flash-Lite users...

If the model is being lazy with tools, you're using a custom system prompt, maybe. To stop this, you can apply the patch inside of [troubleshooting.](https://poweredbywhat.github.io/troubleshooting)

## Tools.

We have:

- read_file: Reads a file. Obviously.
- write_file: Writes a file. What about it?
- search_web: Lets the model search on DuckDuckGo.
- open_webpage (New!): Lets the model open the webpage with the User-Agent set to AskGPT/1.0.
- execute_command: Lets the model execute the command after asking for your permission. 

## Security.

- **Do back up your files before asking AI to sed the fuck out of it.** Antigravity asks you to approve it instead.
- **Don't embed your secrets.** I learned this the hard way when Antigravity took my Groq API key.
- **Treat anything the AI does with a grain of salt.** Literally.
