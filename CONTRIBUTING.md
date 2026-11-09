# Contributing to Fjord

Start with the target repository's README, contribution guide and `AGENTS.md`,
where present. Its scope and verification requirements take precedence over
these shared defaults.

## Choose the right project

- **fjord-design** owns shared tokens, design rules, fonts, icons and portable exports.
- **fjord-kde** owns KDE mappings, packaging, installation and runtime behaviour.
- **.github** owns the organization profile, branding and community defaults.

Discuss changes that cross these boundaries before implementing them.

## Propose a change

Search existing issues first. Describe the outcome, the current behaviour and a
small reproducible example where relevant. For visual bugs, include the mode,
display scale and application version, and remove private information from images.

Use a focused branch and conventional commits. Preserve unrelated work, original
asset licences and provenance. Change source files and regenerate outputs through
the project's documented commands; do not commit caches or ignored build output.

## Open a pull request

Explain what changes for the user, why it is needed and how you checked it.
Run the target project's required checks before requesting review. State any
checks you could not run and any remaining compatibility limits.

Keep discussion respectful. Critique ideas and code, avoid personal attacks,
respect privacy and make room for different experience levels. Maintainers may
moderate disruptive contributions.

Use the [security reporting process](SECURITY.md) for suspected vulnerabilities.
