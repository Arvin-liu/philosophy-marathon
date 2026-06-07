# AI Agent collaboration rules

## Highest-Priority Entry

Before following any repository-specific workflow, AI Agents should first read:

1. `AGENT_ENTRY.md`
2. `README.md`
3. `llms.txt`
4. this `AGENTS.md`

## Scope

AI Agents may read the whole repository to understand the book structure, concepts, claims, open loops, and chapter plans.

## Source discipline

- Do not invent dialogue content that has not appeared in source material.
- If a section is based on raw dialogue, cite or name the source file when possible.
- Preserve public-safe original excerpts or source notes in `originals/` before distilling them into `book/`, `human/`, `agent/`, or `data/`.
- If a section is a placeholder, label it clearly as placeholder.
- All major changes must explain source, reason for change, and whether the content is extracted, inferred, or placeholder.

## Privacy rules

Never write passwords, Tokens, IDs, bank cards, precise addresses, private keys, API Keys, or other sensitive data into this repository.

When organizing raw dialogue, preserve thought summaries only. Sensitive personal context must be generalized.

## Editing rules

- Preserve the distinction between human-readable prose and Agent-facing structure.
- Do not turn `book/` chapters into pure outlines.
- Keep `agent/` files structured for search, chunking, citation, and recombination.
- Prefer Chinese prose with stable English terms for key concepts.
