# Settings

[Fold AI ←](../ai/index.md) | [Guide home](../index.md) | [Updates and release notes →](../maintenance/update.md) | [中文](../../settings/index.md)

Applies to Fold 0.4.6 and later.

## Entry Points

- Keyboard: `⌘,`
- Interface: Settings in the lower left

## General

| Setting | Effect |
| --- | --- |
| Default folder | Open a chosen folder at startup instead of the Workbench |
| Floating Island | Use the same file tray from the top of the screen |
| AI shortcut | Change the Fold AI invocation shortcut |
| Global invocation | Invoke Fold AI from other apps |

## Appearance

- Configure glass-card colors, cover textures, item count, and hover preview.
- Reduce motion is available.
- The preview area shows changes immediately.
- Defaults can be restored.

## Folder Access

Authorize folders through the macOS file picker. If access was denied earlier, restore it in macOS System Settings → Privacy & Security → Files and Folders.

## AI

- Switch between local extraction and model mode.
- Configure provider, model, user prompt, and tool-call rounds.
- API keys are stored in the macOS Keychain.

## Data Locations

| Data | Location |
| --- | --- |
| Recent items, favorites, appearance, browsing settings | `~/Documents/Fold/settings.json` |
| Summary database | `~/Library/Application Support/Fold/Summaries/summaries.sqlite` |
| AI conversations | `~/Library/Application Support/Fold/Agent/Sessions/` |
| API key | macOS Keychain |

---

[← Fold AI](../ai/index.md) | [Guide home](../index.md) | [Updates and release notes →](../maintenance/update.md)
