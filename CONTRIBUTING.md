# Contributing to Vokrenfōma

Thank you for your interest in contributing to Vokrenfōma!

## Proposing a New Word

1. **Open a GitHub Issue**
    - Title: `[dūn/dūnma] <English equivalent>` (e.g., `[namlokat] restaurant`)
    - Use the "New Word Proposal" issue template.
    - Fill out all sections: word type, proposed word, English meaning, breakdown (if dūnma), justification, usage examples, and references.
    - Discuss and refine the proposal in the issue thread until consensus is reached.

## Proposing a Grammar Rule or Change

1. **Open a GitHub Issue**
    - Title: `[Grammar] <Short description>` (e.g., `[Grammar] Pluralization marker`)
    - Use the "Grammar Rule Proposal" issue template.
    - Clearly describe the new rule or change, provide examples, and justify the need for the addition or modification.
    - Discuss and refine the proposal in the issue thread until consensus is reached.

## Proposing a New Dialect

Creating a new, official dialect of Vokrenfōma is a major undertaking. The process is broken into two phases: proposing the concept and then contributing to it.

### Phase 1: Proposing the Dialect Concept

Before any changes are written, the *idea* for a new dialect must be proposed and approved.

1.  **Open a GitHub Issue** using the "Dialect Proposal" template.
2.  The proposal should outline the core principles of the new dialect, its purpose, and examples of the types of changes it would include (e.g., vocabulary, pronunciation, grammar).
3.  This proposal will be discussed by the community. If the concept is approved by a project maintainer, the dialect will become an official variant.

### Phase 2: Contributing to an Approved Dialect

Once a dialect is approved, a new, permanent branch will be created for it in the main repository (e.g., `dialect-high-vokrenfoma`). Contributions can then be made to that dialect.

1.  **Fork the repository** and create a new branch *from the official dialect branch* you wish to contribute to.
2.  Make your changes or additions on your branch.
3.  **Submit a Pull Request** to merge your branch back into the appropriate **dialect branch** (e.g., `your-branch` -> `dialect-high-vokrenfoma`). **Do not target the `main` branch with dialectal changes.**
4.  Your PR will be reviewed, and if approved, merged into the official dialect.

## General Guidelines

- Please check for existing or similar words/rules before proposing new ones.
- Be clear and concise in your proposals.
- Use the provided templates to ensure consistency.
- All discussion and refinement should happen in the issue thread before a pull request is made.

See the structure of existing files and issues for further guidance.

## Approval and Integration

Once a proposal for the main language is approved and consensus is reached in the issue, a project maintainer will add the new word or rule to the official repository. The commit message for this change will link back to the original issue for tracking purposes.