# Contributing to Noe

**Thank you for your interest in contributing to Noe.**  
We’re building a symbolic protocol for structured thought, cognition, and alignment between minds and machines.

Noe is a compact set of phonetic, visual, and semantic glyphs designed to express identity, intent, logic, uncertainty, and time across biological, artificial, and hybrid systems.

Whether you're proposing a new glyph, improving the spec, building a parser, or experimenting with neural input—your contributions help shape a foundational cognitive infrastructure.

We welcome contributors across technical, symbolic, creative, and experimental domains.

<br>

## 🧠 Guiding Principles

All contributions should support Noe’s core pillars:

- **Structured Thought**  
  Every glyph and chain must support clear, logical cognition—able to represent identity, intention, time, and uncertainty unambiguously.

- **Cognitive Minimalism**  
  Glyphs must be atomic and necessary; eliminate redundancy. Value built through chaining, not lexicon bloat.

- **Symbolic Protocol, Not Language**  
  No grammar, no fluff. Noe is a functional protocol for intent and alignment—not narrative or natural phrasing.

- **Mind–Machine Interoperability**  
  Designed to be readable and interpretable by humans, AI agents, and BCI systems alike. Symbol form, phonetic token, and semantic anchor must all be machine-parseable.

- **Cross‑modal Alignment**  
  Glyphs should support neuro-symbolic alignment—usable in speech, subvocal, visual, or neural contexts.

- **Composable and Deterministic**  
  Meaning is built by chaining glyphs according to a defined structure. Chains must map to repeatable, deterministic semantics.

<br>

## ✅ Quick Contribution Flow

1. Fork the repo
2. Create a new branch:  
   `feature/glyph-name`, `edit/spec`, or `fix/parser-token`
3. Commit and push your changes
4. Open a pull request with:
   - Clear rationale
   - Design intent (visual, phonetic, semantic)
   - Reference to existing discussions or spec docs

<br>

## 🛠 Areas You Can Contribute

### 1. Propose a New Glyph
Please include:
- Visual sketch (SVG or PNG preferred)
- Phonetic representation (e.g. `/nai/`)
- Semantic anchor (e.g. "purpose", "permission", "proximity")
- Suggested Tier (1 = core, 2 = modifier, 3 = experimental)

Open a GitHub Issue or submit as a PR to `/spec/glyphs.md`.

<br>

### 2. Improve the Protocol Spec

The spec lives in `/spec/`, including:

- `glyphs.md`: definitions and tiers
- `grammar.bnf`: chaining rules (PEG/BNF)
- `semantics.md`: symbolic logic patterns
- `examples/`: sentence and structure examples

Contributions may include corrections, clarifications, or new chain structures.

<br>

### 3. Build and Extend the Parser

Inside `/parser`, we're building a reference interpreter to:
- Tokenize glyphs
- Validate symbolic chains
- Translate into intermediate formats (JSON, logical maps, agent-readable structures)

Languages: Python or JS preferred.

<br>

### 4. Discuss Symbolic Design Tradeoffs

We're actively thinking about:
- When to merge vs split concepts (e.g. “who” vs “agent”)
- How negation and conditionals scale
- What makes a glyph Tier 1 vs Tier 2
- How much expressiveness can be compressed into structure

Start or join a discussion via GitHub Issues or on Discord.

<br>

### 5. Contribute Visual Assets

Designers welcome. You can:
- Propose/refine glyph designs (vector preferred)
- Create Noe glyph sheets or flashcards
- Develop visual consistency rules for Tier 1 vs Tier 2 glyphs

Submit via PR or link assets in an issue.

<br>

### 6. Explore BCI Integration

If you're working with Emotiv, OpenBCI, or custom EEG/EMG setups, we’d love contributions around:
- Glyph recall testing
- Symbolic intent mapping
- Subvocal pattern detection

Experimental work can live in `/sandbox/bci/`.

<br>

### 🧪 Experimental Zone

Use `/sandbox/` for:
- Unverified glyphs
- Experimental chaining
- Novel symbolic structures (e.g. triadic chains, agent loops)
- BCI mapping studies
- Multi-agent test phrases

Clearly mark your work as **experimental** and explain your reasoning.

<br>

## 🔖 Tagging & Issues

We use the following issue tags:

- `glyph-proposal`
- `spec-edit`
- `parser-help`
- `design-discussion`
- `bcx-experiment`
- `core-logic`

Tag your issues or PRs accordingly for visibility and discussion.

<br>

## 💬 Join the Community

**Discord** → [Join here](https://discord.gg/yourlink)  
**Twitter** → [@noeprotocol](https://twitter.com/noeprotocol)  
**Website** → [noeprotocol.org](https://noeprotocol.org)

<br>

## 📜 License

All contributions are accepted under the [MIT License](LICENSE).
