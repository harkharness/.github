<div align="center">

<img src="https://raw.githubusercontent.com/harkharness/hark/main/docs/img/icon.png" width="84" alt="Hark">

## One voice for every coding agent.

Hark is a voice-first cockpit that sits on top of the agent CLIs you already pay
for. Ask what you were working on and hear the answer. Dispatch real work into
your existing sessions — by voice or by text, across every project on your disk.

**[harkharness.web.app](https://harkharness.web.app)** &nbsp;·&nbsp;
**[Download](https://harkharness.web.app/download)** &nbsp;·&nbsp;
**[Docs](https://github.com/harkharness/hark/blob/main/docs/USAGE.md)** &nbsp;·&nbsp;
**[The plugin plan](https://github.com/harkharness/hark/blob/main/docs/PLUGINS.md)**

<img src="profile/hero.png" width="760" alt="The Hark mother window: an orb, a work chat, and every project at a glance">

</div>

### What lives here

| Repository | What it is |
|---|---|
| **[hark](https://github.com/harkharness/hark)** | Releases: the macOS builds, checksums, and all the documentation. Start here. |
| _the agent contract_ | Coming: the event vocabulary a plugin implements. |
| _hark-plugin-claude_ | Coming: the Claude Code backend, as its own repository. |

### The idea

An editor does not reimplement every compiler — it speaks one protocol, and
every language gets the same experience. Hark does that for coding agents.

The cockpit is neutral: the voice loop, the windows, the board, the permission
floor and the cost ledger belong to you. Which agent CLI runs underneath is a
plugin behind a small contract — an event vocabulary plus a capability sheet the
interface degrades against. Claude Code ships today; Gemini CLI is in
development.

That is why the plugins are what go public first. Your workflow should travel
with you, across companies and across vendors, and the cost ledger should be the
one ruler that means the same thing everywhere.

### What it will never do

Hark drives the CLI you already installed and authenticated. It has no API key,
opens no second bill, and makes no network calls of its own. Speech recognition
runs locally; the index and the ledger stay on your disk. No telemetry, no
account, nothing phones home.

<div align="center">
<sub>Free while in beta · macOS, Apple Silicon and Intel</sub>
</div>
