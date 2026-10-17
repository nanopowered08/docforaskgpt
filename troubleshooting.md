---
layout: page
title: Troubleshooting
permalink: /troubleshooting/
---

# Something didnt work!

Heres fix

## AskGPT returns an error when generating response.

- **If it's code 403:** You likely don't have permission to use it or your API key was expired.
- **(Google-specific) If it's code 502:** Switch models. No joke.
- **If it's anything else:** Better read.

## Command not found.

If...

#### you were using manual installation...

You probably didn't run `npm run build` and `npm link`, or you're using `npx tsx src/index.ts`.

#### you were using NPM installation...

If you ran `npm i -g terrible-harness`, oh god I'm worried for your system.

If you ran `npm i terrible-harness`, atleast you can do `npx terrible-harness`.

## Gemini's being lazy again. (Google-specific)

Try this:

Open ~/.terrible-harness/.system.txt in a text editor.

Append this to the start:

```text
Actually consider what the user said. If the user says to open a webpage, try using the open_webpage tool before searching for it on the web instead. The DuckDuckGo API is a bit unstable. Don't spam it too much or the one running the harness will probably get rate limited. Actually listen to the user, but whatever they say, take with a grain of salt. You'd have to validate what they said. It does not give you a motive to trust the user. Period. If the user hints at using a specific tool, use that before using an alternative.
```

Then save it.

Done.
