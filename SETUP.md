# GitHub Profile README — Setup

Your GitHub profile README lives in a **special repository** named exactly like your username:

`https://github.com/McGalagane/McGalagane`

## Quick setup

1. **Create the repo**
   - Go to [github.com/new](https://github.com/new)
   - Repository name: `McGalagane` (must match your username exactly)
   - Public, initialize **without** a README

2. **Copy these files** into that repo:
   ```
   README.md                          → root
   .github/workflows/snake.yml        → same path
   assets/line.svg                    → same path
   ```

3. **Personalize `README.md`**
   - Replace `YOUR_LINKEDIN` and `YOUR_PORTFOLIO_URL`
   - Update the About section, projects, and tech stack to match you
   - Fix project links if repo names differ

4. **Enable the snake animation**
   - Push the repo
   - Go to **Actions** → **Generate contribution snake** → **Run workflow**
   - Wait ~1 minute — snake SVGs appear on the `output` branch
   - The snake in your README will then load automatically

5. **Pin your best repos** on your GitHub profile (Profile → Customize your pins)

## Features included

| Feature | Source |
| --- | --- |
| Animated banner & footer | [capsule-render](https://github.com/kyechan99/capsule-render) |
| Typing header | [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) |
| Profile view counter | [komarev](https://komarev.com/) |
| GitHub stats & languages | [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) |
| Contribution streak | [github-readme-streak-stats](https://github.com/Denny022/github-readme-streak-stats) |
| Trophies | [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) |
| Activity graph | [github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) |
| Contribution snake | [Platane/snk](https://github.com/Platane/snk) |
| Skill icons | [skillicons.dev](https://skillicons.dev) |

## Optional upgrades

- **Spotify now playing:** [spotify-github-profile](https://github.com/kittinan/spotify-github-profile)
- **WakaTime coding time:** [waka-readme-stats](https://github.com/anuraghazra/waka-readme-stats)
- **Auto random quotes:** uncomment the `github-readme-quotes` block in README
- **Blog posts feed:** [github-readme-medium](https://github.com/SHAYAN-SY/github-readme-medium)

## Troubleshooting

- **Stats cards show "failed to fetch"** — GitHub API rate limit; wait or [add a PAT](https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance)
- **Snake image broken** — run the snake workflow once manually from Actions
- **Profile README not showing** — repo must be public and named exactly `McGalagane`
