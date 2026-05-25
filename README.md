# Socratic Wealth Coach

A Claude Cowork skill that guides you through building a personalized wealth and investment strategy from first principles — through Socratic dialogue, written principles, and durable artifacts.

## What it does

Most people's portfolios grew organically: a 401(k) here, some stocks there, maybe crypto or real estate along the way. This skill helps you step back and ask: *if I were designing this from scratch, what would I build?*

It walks you through 7 structured phases:

1. **Facts discovery** — establish the key facts and assumptions your strategy will depend on
2. **Principles** — define what wealth means to you and how you intend to invest
3. **Situation analysis** — map the current portfolio against the broader economic picture
4. **Target allocation** — set where you want to be and why
5. **Bridge plan** — design a practical path from here to there
6. **Theses & tasks** — write down the reasoning behind major decisions; build an action tracker
7. **Review rhythms** — commit to how you'll revisit and update the strategy over time

A full engagement takes 2–4 hours, often across more than one session.

## What you walk away with

- A **wealth principles file** — what wealth means to you and how you intend to protect it
- An **investing principles file** — your philosophy for how to invest
- An **investment strategy document** — where you are, where you're going, and how to get there
- A **tasks tracker** — specific, actionable next steps
- **Written theses** for any major decisions

These are documents you own, refer back to, and update over time. The conversation is scaffolding; the artifacts are the point.

## What it isn't

This is a coaching tool for structured thinking — not financial advice. Nothing produced in this process constitutes professional financial advice. Tax implications, jurisdiction-specific rules, and specific investment decisions all benefit from review by a licensed professional.

## Installation

### Option A — Install the `.skill` file (easiest)

Download the latest `.skill` file from [Releases](../../releases) and open it in Claude Cowork. It will install automatically.

### Option B — Clone and install manually

```bash
git clone https://github.com/<your-username>/socratic-wealth-coach.git
```

Then in Claude Cowork, install the skill by pointing to the cloned folder.

## Usage

Once installed, just tell Claude what you want:

> "I want to build a wealth strategy."
> "Help me figure out my asset allocation."
> "I need to rebalance my portfolio — let's do it properly."
> "I want to write down my investing principles."

The skill will guide the rest.

## Templates

The `templates/` folder contains scaffolds used during coaching sessions:

| File | Purpose |
|---|---|
| `wealth-principles-starter.md` | Starting template for your wealth principles file |
| `investing-principles-starter.md` | Starting template for your investing principles file |
| `strategy-doc-template.md` | Investment strategy document scaffold |
| `tasks-tracker-template.md` | Action tracker for next steps |
| `written-thesis-template.md` | Template for writing investment decision theses |
| `registry-of-facts-template.md` | Fact registry to anchor the strategy in verified numbers |
| `belief-register-template.md` | Log of world-view assumptions that shape the strategy |

## License

[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) — free to use and adapt with attribution, but not for commercial purposes.
