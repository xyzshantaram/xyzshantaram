### Hi, I'm Siddharth. Most people online call me shantaram.

I build across the whole stack: protocols, runtimes, firmware, circuit boards,
and web products. Six years of contract work, most of it as the only engineer on
the problem. Based in Bangalore, working remote across US and EU hours.

📄 [Résumé](https://xyzshantaram.github.io/resume/) &nbsp;·&nbsp;
✉️ [me@shantaram.xyz](mailto:me@shantaram.xyz) &nbsp;·&nbsp;
🌐 [shantaram.xyz](https://shantaram.xyz) &nbsp;·&nbsp;
🦊 [GitLab](https://gitlab.com/xyzshantaram)

### What I'm building now

- [**nostr-canvas**](https://github.com/xyzshantaram/nostr-canvas): a runtime
  that lets any compatible Nostr client run untrusted third-party mini-apps with
  no client-side code change. Plugins are sandboxed Lua programs published as
  Nostr events, and the same plugin renders in three independent clients that
  share no UI code. The core is a 19k-line Rust crate compiled to WebAssembly.
  Capability grants are enforced in Rust, so revoking one takes effect inside
  the running worker. I wrote the runtime, the plugin specification, and the
  Rust core.
  [Talk at bitcoin++ Nairobi, 2026](https://www.youtube.com/watch?v=PO1lggcj-Ic).
- [**aidos**](https://github.com/xyzshantaram/aidos): a coding-agent harness
  built on DeepSeek Harness. Work becomes tickets, and a ticket moves state only
  when the required proof exists. The agent cannot mark its own work done.

### Hardware

PCB design+fabrication, firmware, and parametric CAD (OpenSCAD) work for various
hardware projects.

- **cardea** — a Trezor Model 1 recreation moved to USB-C, on the STM32F205,
  with ESD and overcurrent protection on the USB input.
- [**soapbox-signer**](https://github.com/xyzshantaram/soapbox-signer): an
  ESP32 NIP-46 signing device with a 2.4-inch display and a six-button pad, so
  every signature is approved on the device. I wrote its firmware too.
- [**The Attention Button**](https://theattentionbutton.in): an IoT desk toy for
  people who are far apart. I designed it, built it, and sold it: enclosure CAD,
  the board, the firmware, the backend, the website, and the leaflet in the box.
  [Source](https://github.com/theattentionbutton).
- [**nostr-lora**](https://github.com/xyzshantaram/nostr-lora): a specification
  and reference implementation that carries Nostr events over LoRa mesh.

### Libraries and tools

- [**campfire**](https://campfire.js.org): a reactive web framework. Chainable
  DOM builder, reactive stores, no build step, no virtual DOM. Maintained since
  2021.
- [**luacheck-ts**](https://jsr.io/@xyzshantaram/luacheck-ts): a 22k-line Lua
  static analyzer ported to TypeScript, so it runs in the browser, Deno, and Node
  from one codebase.
- [**stupid-simple-kv**](https://github.com/xyzshantaram/stupid-simple-kv): a
  Rust key-value crate with order-preserving binary tuple keys and pluggable
  backends.
- [**ink-editor**](https://github.com/xyzshantaram/ink-editor): a WYSIWYG
  Markdown editor on CodeMirror 6.
- [**etu**](https://github.com/xyzshantaram/etu): a time-clock and invoicing CLI
  for freelancers. I have billed my own contract work with it daily since 2024.
- [**colle**](https://github.com/xyzshantaram/colle): a pastebin with syntax
  highlighting, Markdown rendering, and image previews.
- [**macrolight**](https://github.com/xyzshantaram/macrolight): a tiny syntax
  highlighter, a TypeScript rewrite of asvd's microlight.
- [**wizardkit**](https://jsr.io/@xyzshantaram/wizardkit): build a step-by-step
  wizard as a Deno script, served as HTML so the same script runs in a browser or
  a desktop window.
- [**cf-alert**](https://github.com/xyzshantaram/cf-alert) and
  [**worker-sqlite**](https://github.com/xyzshantaram/worker-sqlite): dialogs
  built with Campfire, and async SQLite through a Web Worker.

### Earlier work I still like

- [**Writers Jam**](https://writersjam.shantaram.xyz): a weekly writing exercise
  and anti-social network. 361 posts and over 102,000 views so far.
  [Source](https://github.com/xyzshantaram/writers-jam).
- [**COVID-19 Resources**](https://xyzshantaram.github.io/covid19-resource-site):
  a live-updating resource finder built during India's second wave in 2021,
  backed by a Google Sheet so non-technical volunteers could keep it current.
  [Source](https://github.com/xyzshantaram/covid19-resource-site).
- [**rite**](https://github.com/xyzshantaram/rite) and
  [**rite-cloud**](https://github.com/xyzshantaram/rite-cloud): a
  distraction-free Markdown editor with a Rust sync service behind it.
- [**pseudows**](https://xyzshantaram.github.io/pseudows/): a Windows 98 style
  desktop environment in the browser, with a real window manager and a handful
  of working applications. [Source](https://github.com/xyzshantaram/pseudows).

---

To get in touch, [email me](mailto:me@shantaram.xyz) or see
[my contact page](https://shantaram.xyz/contact/).
If you would like to support my work,
[donation options](https://shantaram.xyz/contact/donate.html) are listed there.
