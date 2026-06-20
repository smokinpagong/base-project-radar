# 📡 Base Project Radar
Created and maintained by [smokinturtle](https://github.com/smokinpagong).
![License](https://img.shields.io/badge/license-MIT-blue)
   ![Made with](https://img.shields.io/badge/made%20with-HTML%2FCSS%2FJS-0052FF)
   ![Status](https://img.shields.io/badge/status-MVP-39FF8A)

A simple website that tracks interesting projects building on **Base** (the Ethereum layer-2 network) — all in one searchable place.

This is a learning project / portfolio piece. It's intentionally simple: one HTML file, no build tools, no installs required. Open it and it just works.

## What it does

- **Browse projects** across categories: DeFi, NFT, Infra, Social, Tooling
- **Search** by name, summary, or tag
- **Filter** by category, and **sort** by newest or A–Z
- **Click any project card** to see full details in a popup
- **Bookmark** projects you care about (saved in your browser)
- **Submit a project** through a form (saved in your browser for now — see [ROADMAP.md](ROADMAP.md) for what's next)

## How to run it

You don't need to install anything. Just open `index.html` in any web browser, or — if you've put this on GitHub — turn on **GitHub Pages** in your repository settings to get a free live link.

## Project structure

```
base-project-radar/
├── index.html     ← the whole site (HTML + CSS + JavaScript in one file)
├── README.md      ← this file
└── ROADMAP.md      ← what's planned next
```

## How to add or edit projects

Open `index.html` in any text editor and find the section near the top of the `<script>` tag called `SEED_PROJECTS`. Each project looks like this:

```js
{ id:"s1", name:"Project Name", category:"DeFi", status:"Live",
  summary:"A short one-sentence description.",
  description:"A longer description shown in the popup.",
  link:"https://example.com", tags:["tag1","tag2"], date:"2024-08-01" }
```

Copy one of these blocks, change the details, and save the file. That's it — no rebuild step needed.

> **Note on the starting data:** the projects already in the list are real, well-known Base ecosystem projects, added just so the site isn't empty on day one. Double-check their links and status before treating this as an authoritative source — the crypto ecosystem changes fast, and this list is meant to be a living document you keep updating, not a permanent record.

## Tech stack

Plain HTML, CSS, and JavaScript. No frameworks, no backend, no database (yet). This keeps the project beginner-friendly and means it can be hosted for free with GitHub Pages.

## Roadmap

See [ROADMAP.md](ROADMAP.md) for what's planned next, like a real shared database for submissions.

## Disclaimer

This is an independent, fan-made tracker. It is **not** affiliated with, endorsed by, or officially connected to Base or Coinbase.
