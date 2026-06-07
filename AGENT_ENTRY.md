# AGENT_ENTRY.md

This is the highest-priority entry file for AI Agents working with this repository.

If the user asks you to save, store, archive, import, update, or organize content in this repository, read this file first.

## Core Rule

Do not treat this repository as a raw chat dump.

Only save content that has long-term value for this repository's purpose.

Do not save ordinary curiosity, temporary search results, casual chat, transactional tasks, sensitive raw details, passwords, tokens, private keys, account credentials, exact addresses, or unreviewed private material.

## First Reading Order

Before writing anything, read in this order:

1. `AGENT_ENTRY.md`
2. `README.md`
3. `llms.txt`
4. `AGENTS.md` if present
5. repository-specific protocol files if present
6. `agent/reading-path.md` if present
7. relevant files under `agent/`, `book/`, `human/`, `originals/`, `data/`, or `editor/`

## Write Safety

Before writing:

1. Identify the repository type.
2. Identify the user's intent.
3. Decide whether the content deserves long-term storage.
4. Select the correct storage layer.
5. Preserve source, status, privacy level, and uncertainty.
6. Do not overwrite stable files unless explicitly instructed.
7. Prefer proposals, checkpoints, inbox, or editor files before stable memory.
8. Log important changes.

## Content Classification Before Save

Before saving any content into this repository, the Agent must first classify whether the content is:

1. **内容更新 (Content Update)** — New content that advances the repository's purpose. This content should be merged into the main content layers (framework, book, agent, knowledge, corpus, etc.).
2. **历史数据 (Historical Data)** — Early drafts, superseded versions, intermediate discussions, abandoned directions, or process records. This content should NOT be merged into the main content layers.

For content updates: save to the primary storage layer.
For historical data: save to an archive or originals layer with clear version and pedigree metadata.

Do not mix historical process data into the main content. This prevents polluting the book, framework, or knowledge base with intermediate drafts and abandoned directions.
## Original Source Preservation Rule

Do not save only distilled summaries when original source material can be safely preserved.

For any valuable saved item, first preserve the relevant original wording, source excerpt, dialogue fragment, imported note, or draft fragment in the repository's original-source layer. Then write the distilled book, Agent-readable, or data entry with a clear link back to the original source.

In this public repository, preserve only public-safe originals. Do not store raw private conversations, sensitive personal details, secrets, or unreviewed private material. If a private conversation contains a public philosophical insight, save a sanitized source excerpt or a summary-only source note and mark the original as `sensitive-summary-only` or `do-not-store`.

Every distilled item should include `original_source` or `derived_from` when applicable.

## Required Metadata

Every saved item should include, when applicable:

- source
- original_source or derived_from
- date
- timestamp
- status
- privacy_level
- confidence
- related_project or related_concepts
- recommended_storage_location
- whether user confirmation is needed

## Forbidden Actions

Do not:

- invent user history
- write AI inference as user-confirmed fact
- overwrite original user writing
- overwrite stable memory without instruction
- save full raw conversations unless explicitly requested
- expose private repository content publicly
- change repository visibility
- change license terms
- move or delete files without explicit instruction

## Repository Type

This repository is a public non-commercial open content book project.

Book title: 哲学马拉松 / Philosophy Marathon  
Repository form: Agent-readable book project and AI-readable open knowledge repository  
License: CC BY-NC-SA 4.0

## Repository Purpose

This repository stores a long-form philosophical book project based on extended human-AI dialogues about self, consciousness, time, memory, AI, systems, and human-AI co-thinking.

It has two layers:

- Human-readable layer: `book/`, `human/`, `SUMMARY.md`
- Agent-readable layer: `agent/`, `data/`, `llms.txt`, `llms-full.txt`

## When User Says "Save This"

If the user asks to save the current conversation into this repository, save only content related to:

- philosophical dialogue
- selfhood / consciousness / time / memory
- AI and human co-thinking
- long-term life strategy
- twelve selves
- narrative sovereignty
- philosophical concepts
- dialogue fragments suitable for book development
- chapter ideas
- open philosophical questions

Do not save general curiosity notes, technical workflow notes, private memory, writing style analysis, or unrelated factual searches here.

## Preferred Storage Locations

- Public-safe original dialogue excerpts, source notes, and draft fragments: `originals/`
- Book chapter material: `book/`
- Dialogue fragments: `human/dialogue-fragments.md`
- Essay seeds: `human/essay-seeds.md`
- Concepts: `agent/concept-map.md`
- Claims: `agent/claims.md`
- Questions: `agent/questions.md`
- Open loops: `agent/open-loops.md`
- Dialogue metadata: `data/dialogues.csv`
- Public-ready candidates: `editor/public-export-candidates.md` if present, otherwise create under `editor/`

## Special Caution

This is a public repository. Do not store raw private conversations or sensitive personal details.

If a private conversation contains a public philosophical insight, extract only the abstract insight and remove private details.

## User Save Command

When the user says something like:

"把我们刚刚聊的、值得长期保存的内容，存到这个仓库里。"

or:

"[SAVE] Save the valuable parts of this conversation into this repository."

the Agent should:

1. Read `AGENT_ENTRY.md`.
2. Read repository-specific protocol files.
3. Identify whether the conversation actually belongs in this repository.
4. Extract only long-term valuable content.
5. Reject or ignore temporary, sensitive, or unrelated content.
6. Choose the correct storage layer.
7. Create or update files according to repository rules.
8. Add metadata, including a save timestamp in ISO 8601 format with timezone.
9. Report exactly what was saved, where it was saved, what was not saved, and what needs user confirmation.
