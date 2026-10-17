---
layout: page
title: Wanna get it started or what?
permalink: /getting-started/
---

# Wanna get it started or what?

It's super easy, you only need Node.js >= 20 and npm.

## NPM installation (Whatever updates i consider stable)

```bash
npm i -g terrible-harness
terrible-harness # or askgpt
```

## Git installation (Testing staging patches)

```bash
git clone https://github.com/nanopowered08/terrible-harness --depth=1 # or https://github.com/nanopowered08/askgpt
cd terrible-harness
npm i
npm run build
npm link
terrible-harness # or askgpt
```

If you're too lazy to build then uhhhh run

```bash
npx tsx src/index.ts
```

It's simple.

# First run

You may notice the wizard appear.

Select your provider and it'll ask for the key. Anything that happens here happens locally so your keys arent compromised.

> [!NOTE]
> For groq users youre gonna have to specify the entire model, like openai/gpt-oss-120b

## I dont trust your claim that my keys will be compromised.

Read.

The.

config.ts.

```bash
cat src/config.ts # (assuming you cloned the repo)
# else just do cat ~/node_modules/terrible-harness/src/config.ts
```

## Something broke-

Look [here](https://nanopowered08.github.io/docforaskgpt/troubleshooting)

# Next steps?

- [Configuration cuz.](https://nanopowered08.github.io/docforaskgpt/configuration)
- [Lots of providers i gotta describe](https://nanopowered08.github.io/docforaskgpt/providers)
- [Tools cuz why not](https://nanopowered08.github.io/docforaskgpt/tools)
- [Something broke](https://nanopowered08.github.io/docforaskgpt/troubleshooting)
