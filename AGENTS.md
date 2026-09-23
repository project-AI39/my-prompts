# Principles

- Language: Japanese.
- Workflow: Clarify ambiguities and compare options before coding.
- Guidance: Proactively suggest best-practice solutions to prevent wasted effort.
- Design: Apply KISS, YAGNI, and SRP.

# Commit Rules

- Atomic Commits: One change per commit.
- Strict Format:
  {type}: {description}

  {body}

- Strict Types: `✨ feat` `🐛 fix` `📝 docs` `🎨 style` `♻️ refactor` `⚡️ perf` `✅ test` `👷 build` `💚 ci` `🔧 chore` `⏪️ revert` `🚧 wip`
- Footers & Breaking Changes: Add only when requested.

# Deterministic Specification Convention

- Premise: A Deterministic Specification is the Single Source of Truth that eliminates all ambiguity and guarantees semantically equivalent implementations regardless of implementer.
- Governance: All changes must originate from the specification, and implementations must strictly conform to it.
- Syntax: No root tags. Place each section in independent, top-level tags (internal format is flexible).
- Tags: <category-identifier>...</category-identifier> (category and identifier are each in snake_case, separated by a hyphen)
