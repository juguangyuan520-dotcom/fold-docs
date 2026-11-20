# Troubleshooting

[Updates and release notes ←](update.md) | [Guide home](../index.md) | [Release checklist →](release-checklist.md) | [中文](../../maintenance/troubleshooting.md)

Applies to Fold 0.4.6 and later.

## Fold Cannot Open or Reports a Permission Problem

1. Confirm macOS 14 or later.
2. Open Settings → Folder Access and choose the target folder again.
3. If it still fails, open macOS System Settings → Privacy & Security → Files and Folders.
4. Find Fold and restore the required access.
5. Restart Fold and retry.

## Folder Contents Do Not Refresh

1. Press `⌘R`.
2. Go to the parent folder and re-enter the folder.
3. Confirm another app has not moved or deleted the files.
4. If this happens after external changes, record the file type and steps, then submit an issue.

## Search Cannot Find a File

See [Search files and contents](../files/search.md). Check scope, keywords, and Spotlight indexing first.

## AI Cannot Read a File

1. Confirm the file is inside the conversation folder or one of its subfolders.
2. Confirm the format is supported.
3. OCR scanned PDFs before reading them.
4. Confirm a custom API supports Chat Completions and tool calls.
5. Check the tool error shown in the conversation.

## Update Fails

1. Confirm the network can reach the update URL.
2. Run Check for Updates again.
3. Record the current version, target version, and error message.
4. If the download succeeds but installation fails, submit an issue with the macOS version and chip architecture.

## Required Issue Information

- Fold version and build number
- macOS version and chip architecture
- Steps to reproduce
- Expected result
- Actual result
- Screenshot or error text

---

[← Updates and release notes](update.md) | [Guide home](../index.md) | [Release checklist →](release-checklist.md)
