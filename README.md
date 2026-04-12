# How to Start a Startup — AI Agent Skill

<p align="center">
  <strong>Startup advisor skill powered by Stanford CS183B / Y Combinator's "How to Start a Startup" course</strong>
</p>

<p align="center">
  <a href="https://skills.sh/zhimin-z/solopreneur"><img src="https://img.shields.io/badge/Browse-skills.sh-blue?style=flat-square" alt="Browse on skills.sh"></a>
  <a href="https://code.claude.com/docs/en/plugin-marketplaces"><img src="https://img.shields.io/badge/Claude_Code-Marketplace-orange?style=flat-square&logo=anthropic" alt="Claude Code Marketplace"></a>
  <a href="https://github.com/zhimin-z/solopreneur/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT License"></a>
</p>

<p align="center">
  20 lectures, 1,000+ minutes of startup wisdom from world-class founders and investors.<br>
  <a href="#quick-install">Quick Install</a> · <a href="#whats-inside">What's Inside</a> · <a href="#usage-examples">Usage Examples</a>
</p>

---

## What is This?

This is an **AI agent skill** that gives your coding assistant deep knowledge of Y Combinator's famous startup course. Once installed, your AI agent can answer startup questions by referencing the actual lecture transcripts from Sam Altman, Paul Graham, Peter Thiel, Marc Andreessen, and 15+ other world-class founders.

## What's Inside

One skill with 20 complete lecture transcripts as reference material:

| # | Topic | Speaker(s) |
|---|-------|-----------|
| 1 | How to Start a Startup | Sam Altman, Dustin Moskovitz |
| 2 | Ideas, Products, Teams and Execution II | Sam Altman |
| 3 | Counterintuitive Parts of Startups, How to Have Ideas | Paul Graham |
| 4 | Building Product, Talking to Users, and Growing | Adora Cheung |
| 5 | Business Strategy and Monopoly Theory | Peter Thiel |
| 6 | Growth | Alex Schultz |
| 7 | How to Build Products Users Love I | Kevin Hale |
| 8 | Doing Things That Don't Scale, PR, Getting Started | Walker Williams, Justin Kan |
| 9 | How to Raise Money | Marc Andreessen, Ron Conway |
| 10 | Company Culture and Building a Team I | Alfred Lin, Brian Chesky |
| 11 | Company Culture and Building a Team II | Patrick & John Collison, Ben Silbermann |
| 12 | Building for the Enterprise | Aaron Levie |
| 13 | How To Be A Great Founder | Reid Hoffman |
| 14 | How to Operate | Keith Rabois |
| 15 | How to Manage | Ben Horowitz |
| 16 | How to Run a User Interview | Emmett Shear |
| 17 | How to Build Products Users Love II | Hosain Rahman |
| 18 | Mechanics — Legal, Finance, HR | Kirsty Nathoo, Carolynn Levy |
| 19 | Sales, Marketing, How to Pitch | Tyler Bosmeny, YC Partners |
| 20 | Closing Thoughts and Later-Stage Advice | Sam Altman |

## Quick Install

### Claude Code Plugin Marketplace

```bash
# Add the marketplace
/plugin marketplace add zhimin-z/solopreneur

# Install the skill
/plugin install solopreneur@solopreneur

# List available skills
/plugin marketplace list solopreneur
```

### Universal Installation (16+ AI Tools)

Works with Claude Code, Cursor, Windsurf, Droid, Codex, and more:

```bash
# Install the skill
npx skills add zhimin-z/solopreneur

# Install to a specific agent
npx skills add zhimin-z/solopreneur -a claude
npx skills add zhimin-z/solopreneur -a cursor
npx skills add zhimin-z/solopreneur -a droid
```

Browse and discover skills at **[skills.sh](https://skills.sh/zhimin-z/solopreneur)**

## Usage Examples

Once installed, just ask your AI agent startup questions:

**Evaluating ideas:**
> "How do I know if my startup idea is good?"

Your agent reads Lectures 1 & 3 and responds with Sam Altman's framework ("unpopular but right") and Paul Graham's advice on finding ideas from personal problems.

**Fundraising:**
> "How should I approach raising my seed round?"

Your agent reads Lecture 9 and synthesizes Marc Andreessen's and Ron Conway's advice on timing, amount, and investor selection.

**Hiring & culture:**
> "How do I build company culture as a first-time founder?"

Your agent reads Lectures 10 & 11 and pulls from Brian Chesky (Airbnb), Patrick Collison (Stripe), and Alfred Lin (Zappos) on defining and maintaining culture.

**Growth:**
> "What's the most important metric for growth?"

Your agent reads Lecture 6 and delivers Alex Schultz's framework on retention as the single most important metric.

**Operations:**
> "How do I transition from founder to operator?"

Your agent reads Lectures 14 & 15 and combines Keith Rabois's operating framework with Ben Horowitz's management advice.

## Supported AI Tools

This skill works with 16+ AI coding agents via `npx skills add`:

- **Claude Code** — Anthropic's CLI for Claude
- **Cursor** — AI-first code editor
- **Factory Droid** — AI software engineering agent
- **Windsurf** — AI-powered IDE
- **OpenCode** — Open-source AI coding assistant
- **Codex** — AI code generation tool
- **And more...** — See the [full list](https://github.com/vercel-labs/add-skill#available-agents)

## Course Credits

All lecture content is from **"How to Start a Startup" (CS183B)**, a free course by Sam Altman and Y Combinator at Stanford University.

- Video lectures: [YouTube](https://www.youtube.com/playlist?list=PL5q_lef6zVkaTY_cT1k7qFNF2TidHCe21)

Transcripts sourced from [Genius](https://genius.com).

## Author

**Zhimin Zhao**

## Contributing

1. Fork this repository
2. Submit a pull request with improvements

## License

MIT
