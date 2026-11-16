# Everybody Can Build

[everybodycanbuild.com](https://everybodycanbuild.com) is a beginner guide for friends and family who want to start building with Claude Code and Opus 5.5. Installing Claude Code is the only manual step. Every later step is a prompt you paste into Claude, which then sets up browser use, computer use, a Bitwarden vault for secrets, and Tailscale + SSH for working from a phone. Questions go to the Telegram group [t.me/everybodycanbuild](https://t.me/everybodycanbuild).

## How it works

It is a single static page, `docs/index.html`, with no build step and no dependencies, served by GitHub Pages from `docs/`. Open it in a browser to run it locally.

The share image `docs/og.png` (1200×630) is rendered from `src/og.html` with headless Chrome (bump `og.png?v=N` in the page when you re-render it).

## License

[MIT](LICENSE)
