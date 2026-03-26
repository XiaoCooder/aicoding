# AICoding Project Skeleton Design

## Context

The workspace at `/home/claude/aicoding2` is currently empty and is not initialized as a git repository yet. The user wants to create the first version of a public, lab-prioritized resource index project focused on AI coding, vibe coding, and agents.

This design covers only the initial document skeleton. It does not attempt to fully populate resources, build automation, or define contribution workflows beyond lightweight placeholders.

## Goal

Create a minimal, maintainable repository structure that establishes:

- the project's positioning
- the intended audience
- the initial document taxonomy
- clear boundaries for future content expansion

The result should turn the current empty directory into a usable documentation-first project skeleton.

## Scope

This first version will create:

- `README.md`
- `CONTRIBUTING.md`
- `docs/getting-started.md`
- `docs/papers.md`
- `docs/tools.md`
- `docs/benchmarks.md`
- `docs/skills.md`
- `docs/websites.md`
- `docs/research-topics.md`

This version will not create:

- a license file
- CI configuration
- issue templates
- PR templates
- scripts, tooling, or build steps
- large curated resource lists

## Positioning

The repository is positioned as:

> A publicly maintained, lab-prioritized resource index for learning and research on AI coding, vibe coding, and agents.

The key constraint is that it should not present itself as a general-purpose “largest public navigation site.” It should instead prioritize the practical learning and research needs of lab members while remaining open and maintainable in public.

## Information Architecture

### Root documents

`README.md` is the entry point. It should explain:

- what the project is
- who it serves
- what content it includes
- how to navigate it
- how to use it as a lab member

`CONTRIBUTING.md` should define lightweight expectations for future edits, including:

- what kinds of content are welcome
- basic writing and organization principles
- how to propose additions and corrections

### Topic documents

Each file under `docs/` has one clear role:

- `getting-started.md`: entry path for new lab members
- `papers.md`: paper and survey index structure
- `tools.md`: tool and environment index structure
- `benchmarks.md`: benchmark and evaluation index structure
- `skills.md`: workflow, prompt, and practical skill collection structure
- `websites.md`: websites, portals, and tracking entry points
- `research-topics.md`: research questions and topic map for lab use

The topic files should contain lightweight first-version structure instead of exhaustive content. Each file should make its purpose and intended future contents obvious.

## Content Strategy

The repository should be written primarily in Chinese, while preserving English technical terms where they improve accuracy or recognition.

The writing style should be:

- concise
- neutral
- research-oriented
- maintainable

The documents should avoid:

- marketing language
- inflated claims
- long unstructured link dumps
- overly detailed policies too early in the project

## Recommended Content Depth

The initial depth should be intentionally shallow:

- `README.md` should be complete enough for a first public commit
- `CONTRIBUTING.md` should be minimal but actionable
- the seven `docs/` files should provide orientation, suggested sections, and placeholders for later expansion

Among the topic files, the four core areas should receive slightly stronger framing:

- `getting-started.md`
- `papers.md`
- `tools.md`
- `benchmarks.md`

The remaining three should remain clearly defined but lighter:

- `skills.md`
- `websites.md`
- `research-topics.md`

## File-Level Responsibilities

### `README.md`

Responsibilities:

- define project positioning
- explain target readers
- define current content scope
- show repository structure
- link to topic documents
- explain suggested usage paths for different readers

### `CONTRIBUTING.md`

Responsibilities:

- define acceptable contributions
- define simple editorial standards
- define lightweight update expectations

### `docs/*.md`

Responsibilities:

- define the purpose of each topic area
- suggest future section organization
- make future expansion predictable

## Non-Goals

This design explicitly avoids solving later-stage questions such as:

- whether to become a broader public platform
- exact classification standards for all future resources
- how to version or archive outdated resources
- governance model beyond basic contribution guidance

Those should be addressed only after the first structure is in active use.

## Validation

Implementation should verify:

- all planned files exist
- `README.md` links match actual file names
- document naming is consistent
- the structure is understandable without extra explanation

## Risks and Mitigations

### Risk: the first version becomes too content-heavy

Mitigation: keep this iteration focused on structure and framing, not exhaustive curation.

### Risk: overlap between topic documents

Mitigation: define one primary responsibility per file and keep boundaries explicit.

### Risk: README promises more than the repository currently contains

Mitigation: describe the repository as an evolving index and avoid claims of completeness.
