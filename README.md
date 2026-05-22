# pipane

A clean web interface for the **pi coding agent**. Open any pi conversation in pipane, open any pipane conversation in pi -- full interop.

`pipane` runs a local backend that launches `pi` in RPC mode and streams agent messages to a browser UI over WebSocket.

## Walkthrough

Hero shot:

![pipane walkthrough hero](e2e/screenshots/walkthrough-hero.png)

Walkthrough (GIF):

![pipane walkthrough](e2e/videos/walkthrough.gif)

---

## Quickstarts

```bash
npm install -g pipane
```

If `pi` is missing, install it like this:

```bash
npm install -g @mariozechner/pi-coding-agent
```

---

## What you get

- Session list and clean UI for `pi`
- Real-time tool calls and streaming output, nicely crafted
- A nice session picker
- A large amount high quality "vibe-code".

## Server auth

Remote access is protected by an auth URL by default. Set `PIPANE_AUTH_TOKEN` to use a fixed token.

If pipane is running behind a reverse proxy that handles authentication, set `PIPANE_AUTH_DISABLED=1` to disable pipane's built-in HTTP and WebSocket auth checks.

---

## License

[MIT](LICENSE)
