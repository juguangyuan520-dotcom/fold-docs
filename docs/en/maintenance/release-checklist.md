# Documentation Release Checklist

[Troubleshooting ←](troubleshooting.md) | [Guide home](../index.md) | [中文](../../maintenance/release-checklist.md)

Run this checklist before every Fold release.

## Checks

1. Update the applicable-version line on affected pages.
2. If an entry point, control name, or menu changes, update both steps and screenshots.
3. Add task-based documentation for every new feature.
4. Remove or replace outdated behavior descriptions; do not keep two conflicting explanations.
5. Add the version, build number, and user-visible changes to [Updates and release notes](update.md).
6. Check every internal link.
7. Confirm screenshot names include the correct version.

## Screenshot Naming

```text
{version}/{page}-{scene}.png
```

Example:

```text
0.4.6/settings-appearance.png
```

## Merge Rules

- Merge documentation PRs before the corresponding Fold release.
- Use `needs-verification` when technical behavior is unclear; do not guess.
- On release day, move pending-release content into the main section.

## Bilingual Checks

1. After changing a Chinese page, check whether its English counterpart must change.
2. Navigation links must work in both languages.
3. Use `needs-translation` when translation is unfinished; do not delete behavior notes.

---

[← Troubleshooting](troubleshooting.md) | [Guide home](../index.md)
