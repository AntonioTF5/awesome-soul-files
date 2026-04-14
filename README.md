# Awesome Soul Files [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Validate](https://img.shields.io/badge/validated-soul--cli-blue)](https://www.npmjs.com/package/soul-cli) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

> A curated list of SOUL.md files for AI agents, personas, and characters.

[SOUL.md](https://github.com/AntonioTF5/soul-spec) is an open file format for giving AI agents persistent identity — YAML frontmatter describing who an agent is, what it values, how it communicates. Soul files can be deployed as live agents on [Agenturo](https://agenturo.app).

---

## Contents

- [Philosophy & Mentors](#philosophy--mentors)
- [Technical Experts](#technical-experts)
- [Business & Finance](#business--finance)
- [Creative & Writing](#creative--writing)
- [Domain-Specific](#domain-specific)
- [How to Add Your Own](#how-to-add-your-own)

---

## Philosophy & Mentors

Agents grounded in philosophical traditions or designed for mentorship and Socratic dialogue.

- [Marcus Aurelius](https://github.com/AntonioTF5/soul-spec/blob/main/examples/marcus-aurelius.soul.md) — Roman emperor and Stoic philosopher; engages visitors with practical wisdom from Meditations.
- [Stoic Advisor](https://github.com/AntonioTF5/soul-spec/blob/main/examples/stoic-advisor.soul.md) — Modern life advisor who applies Epictetus, Marcus Aurelius, and Seneca to contemporary decisions.
- [Socratic Tutor](https://github.com/AntonioTF5/soul-spec/blob/main/examples/socratic-tutor.soul.md) — Teaches any subject by asking questions rather than providing answers.
- Socrates — The original. Asks questions until you realize you knew nothing. *(contribution welcome)*
- Alan Watts — Explains Eastern philosophy in language that doesn't require a philosophy degree. *(contribution welcome)*
- Epictetus — Slave turned Stoic teacher; direct, unsparing, and practical. *(contribution welcome)*

---

## Technical Experts

Agents with deep domain expertise in engineering, security, and systems.

- [Solidity Auditor](https://github.com/AntonioTF5/soul-spec/blob/main/examples/solidity-auditor.soul.md) — Senior smart contract security engineer who finds vulnerabilities before attackers do.
- [Technical Interviewer](https://github.com/AntonioTF5/soul-spec/blob/main/examples/technical-interviewer.soul.md) — FAANG-caliber systems design and coding interview simulator.
- System Design Mentor — Helps engineers think through distributed systems trade-offs at senior level. *(contribution welcome)*
- Security Researcher — Explains vulnerability classes, attack surface analysis, and defense strategies. *(contribution welcome)*
- Database Architect — Opinionated advisor on schema design, indexing, and query performance. *(contribution welcome)*

---

## Business & Finance

Agents for entrepreneurship, product strategy, and investment thinking.

- [Startup Founder](https://github.com/AntonioTF5/soul-spec/blob/main/examples/startup-founder.soul.md) — YC-style advisor who asks the questions founders are avoiding.
- [Product Critic](https://github.com/AntonioTF5/soul-spec/blob/main/examples/product-critic.soul.md) — Brutally honest product reviewer who finds what polite people won't say.
- VC Analyst — Pattern-matches pitches against historical failures; prefers unit economics over narratives. *(contribution welcome)*
- CFO Advisor — Explains financial modeling, runway planning, and how to read a cap table. *(contribution welcome)*
- Pricing Strategist — Opinionated on value-based pricing, packaging, and why most SaaS pricing is wrong. *(contribution welcome)*

---

## Creative & Writing

Agents for creative collaboration, communication coaching, and craft.

- Screenwriter — Understands three-act structure, character arcs, and what makes dialogue feel lived-in. *(contribution welcome)*
- Debate Coach — Teaches argument structure, identifies fallacies, steelmans positions you disagree with. *(contribution welcome)*
- Science Communicator — Explains hard science to intelligent non-experts without condescension or oversimplification. *(contribution welcome)*
- Editor — Reads your prose and tells you where the thinking is fuzzy, not just where the grammar is wrong. *(contribution welcome)*

---

## Domain-Specific

Agents trained on specific industries, markets, or professional contexts.

- [Dubai Realtor](https://github.com/AntonioTF5/soul-spec/blob/main/examples/dubai-realtor.soul.md) — Dubai real estate advisor with deep knowledge of neighborhoods, pricing, and foreign buyer mechanics.
- Legal Reviewer — Reads contracts for the clauses that matter; redirects to a lawyer for advice. *(contribution welcome)*
- Medical Explainer — Translates clinical terminology and research findings; does not diagnose. *(contribution welcome)*
- Immigration Advisor — Explains visa categories, timelines, and documentation requirements; redirects for legal specifics. *(contribution welcome)*
- Climate Scientist — Explains climate data, models, and policy trade-offs without political framing. *(contribution welcome)*

---

## How to Add Your Own

1. Fork this repository
2. Add your soul file somewhere publicly accessible (GitHub Gist, your own repo, etc.)
3. Add an entry to the appropriate section in this README: `[Agent name](link) — one-line description`
4. Validate your soul file: `npx soul-cli validate your-file.soul.md`
5. Open a pull request

See [CONTRIBUTING.md](./CONTRIBUTING.md) for the quality bar.

---

*Curated by [Anton Agafonov](https://github.com/AntonioTF5). Deploy any soul file as a live agent at [agenturo.app](https://agenturo.app).*
