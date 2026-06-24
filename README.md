# Socratic Wealth Coach

A Claude Cowork skill that guides you through building a personalized wealth strategy from first principles — across all five pillars of wealth, through Socratic dialogue, written principles, and durable artifacts.

## The five pillars

Wealth has five levers worth building deliberately:

| Pillar | What it covers |
|---|---|
| **Earning Power** | Your income capacity as both a durable asset (skills, reputation, leverage) and a current flow |
| **Cost Optimization** | The mirror of earning — spending has a stock (lifestyle infrastructure) and a flow (monthly rate) |
| **Wealth Management** | The deliberate deployment and compounding of banked capital |
| **Tax Strategy** | Structural positioning across entity type, account types, asset location, and estate |
| **Protection** | Insurance, legal structure, estate documents, and reserves — what keeps the other pillars from going to zero |

## What it does

The engagement starts with shared foundations, then focuses on the pillar where deliberate attention will have the most impact:

1. **Facts discovery** — establish the key facts and assumptions the strategy will depend on
2. **Wealth principles** — define what wealth means to you across all five pillars
3. **Situation overview & pillar selection** — map the full economic picture and choose where to focus
4. **Deep dive** — pillar-specific methodology (full methodology for Wealth Management; Socratic approach for all others)

A full engagement takes 2–4 hours, often across more than one session.

## What you walk away with

- A **wealth principles file** — what wealth means to you and how you intend to build it
- A **strategy document** for the pillar you tackled
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
git clone https://github.com/manupanizo/socratic-wealth-coach.git
```

Then in Claude Cowork, install the skill by pointing to the cloned folder.

## Usage

Once installed, just tell Claude what you want:

> "I want to build a wealth strategy."
> "Help me figure out my asset allocation."
> "I need to rebalance my portfolio — let's do it properly."
> "I want to write down my investing principles."
> "Am I paying too much in taxes?"
> "Do I have enough insurance?"
> "How do I grow my income?"

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
