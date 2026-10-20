# Spec Changelog — maintained compatibility fork

Four read-only commands report requirement changes from feature-scoped Git history:
`speckit.changelog.generate`, `.release`, `.diff`, and `.notify` (same prefix).
Codex skills integration registers them as `$speckit-changelog-generate`,
`$speckit-changelog-release`, `$speckit-changelog-diff`, and `$speckit-changelog-notify`.
They generate text; none sends notifications, modifies files or publishes a release.

The 3pepe3 fork adapts upstream commit f5a8ee6bf55e17ec036cb885067e01d47951a30d:
structured extension command objects, supported `speckit_version` requirement,
native feature-path resolution, actual `specs/<feature>` history and evidence limits.
It removes the incomplete automatic hook and mandatory invented effort estimates.
Compatibility is verified through installation and registration with Spec Kit1.2.1
and its Codex skills integration; other agent execution is not claimed tested.

Install a reviewed immutable fork revision with `specify extension add changelog
--from https://github.com/3pepe3/spec-kit-changelog/archive/<commit>.zip`.
Custom URL installation asks for source trust. No hooks are installed.
Read each command's Markdown for its reporting scope and parameters in natural
language. Native environment selection or `.specify/feature.json` selects a feature.

Upstream: https://github.com/Quratulain-bilal/spec-kit-changelog .
The upstream manifest declares MIT. See LICENSE and NOTICE for attribution.
