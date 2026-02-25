# Collaboration Policy

## Overview

BBXDOO is developed through a hybrid Human + AI collaboration model. This policy establishes expectations for how human contributors and AI assistants work together within this repository.

## Principles

1. **Transparency** — All AI-assisted contributions must be disclosed in the relevant PR, commit message, or evidence log.
2. **Human Accountability** — A human contributor must review, approve, and take responsibility for any AI-generated content before it is merged.
3. **Auditability** — Collaboration events are recorded in the [Evidence Log](EVIDENCE_LOG.md) to maintain a clear, append-only audit trail.
4. **Consistency** — All contributors (human and AI) must follow the standards defined in [CONTRIBUTING.md](../.github/CONTRIBUTING.md) and the [Code of Conduct](../.github/CODE_OF_CONDUCT.md).
5. **Minimal Footprint** — Changes should be targeted and purposeful. Avoid unnecessary file modifications.

## AI Tool Usage

AI tools (e.g., GitHub Copilot, ChatGPT, Gemini, Grok, DeepSeek) may be used to:

- Draft documentation
- Suggest code changes
- Perform analysis and summarization

AI tools **must not** be used to:

- Commit or merge changes autonomously without human review
- Override governance or security policies
- Generate content that violates the Code of Conduct

## Evidence Requirements

Any significant collaboration event (e.g., AI-assisted PR, policy decision, major documentation change) must be logged in [`EVIDENCE_LOG.md`](EVIDENCE_LOG.md) using the format defined in [`docs/templates/evidence_record_template.md`](../templates/evidence_record_template.md).

Artifact classification follows [`EVIDENCE_CLASSIFICATION.md`](EVIDENCE_CLASSIFICATION.md).
