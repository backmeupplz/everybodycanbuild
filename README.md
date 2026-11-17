# Everybody Can Build

[everybodycanbuild.com](https://everybodycanbuild.com) is a beginner guide for friends and family who want to start building with Claude Code and Opus 5.5. Installing Claude Code is the only manual step. After a few settings commands (Opus 5.5 on high effort, Fable as advisor, auto mode), every step is a prompt you paste into Claude, which then sets up browser use, computer use, a local Vaultwarden vault for secrets, Tailscale + SSH for working from a phone, and our building rules in its memory. Questions go to the Telegram group [t.me/everybodycanbuild](https://t.me/everybodycanbuild).

## How it works

It is two static pages with no build step and no dependencies, served by GitHub Pages from `docs/`: the guide, `docs/index.html`, and `docs/marketing.html` at [/marketing](https://everybodycanbuild.com/marketing), one long prompt that builds Radiant, a marketing autopilot for SEO, app store search and AI answers. Open them in a browser to run them locally.

The share images `docs/og.png` and `docs/og-marketing.png` (1200×630) are rendered from `src/og.html` and `src/og-marketing.html` with headless Chrome (bump `?v=N` in the page when you re-render one).

## License

[MIT](LICENSE)
