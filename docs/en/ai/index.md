# Fold AI

[Search files and contents ←](../files/search.md) | [Guide home](../index.md) | [Settings →](../settings/index.md) | [中文](../../ai/index.md)

Applies to Fold 0.4.6 and later.

## What It Can Do

- Find files inside the folder bound to the conversation and its subfolders.
- Read text, Markdown, DOCX, PDFs with a text layer, and common image formats.
- Summarize files, folders, or multiple materials.
- Create, read, edit, copy, move, rename, and delete files.
- Execute clear requests directly; generate a preview first for risky or complex text changes.
- Run restricted sandbox Shell commands in the conversation folder.

## Open and Close

| Goal | Action |
| --- | --- |
| Toggle the AI panel | Click the four-leaf icon on the right side of the title bar |
| Invoke globally | `⌃⇧Space`, after enabling global invocation |
| Dismiss the panel | `Esc`, or click outside the panel in the main Fold window |
| New conversation | Click `+` in the panel |
| View history | Expand conversations in the panel |

## Conversation Folder

Fold AI can access only the directory bound to the conversation and its subfolders. Check the scope at the top. After browsing elsewhere, choose Switch to Current Folder.

Deletion moves items to the system Trash. Copying or moving fails on a name conflict instead of overwriting the target.

## Model Configuration

1. Open Settings → AI → Model Configuration.
2. Use a third-party routed free model, or choose a custom API.
3. A custom API must support Chat Completions and tool calls.
4. The API key is stored in the macOS Keychain, not in the settings file.

## File Summaries

Entry point: right-click a file, folder, or empty area and choose AI Assist.

- A single file can be summarized directly.
- A folder can generate summaries for supported files inside it and its subfolders.
- Summary Tasks in the lower left shows completed and waiting counts. You can stop, continue, or remove waiting items.
- Open a completed task to read the summary with sources.

Default local extraction supports TXT, Markdown, CSV, TSV, PDFs with a text layer, and common images. Scanned PDFs cannot be read directly yet.

## Text Editing

1. Ask AI to read the target file.
2. Request a preview or give a clear edit instruction.
3. Review the preview before confirming.
4. Submitted text edits can be undone from the conversation card.

AI reads the original text and checks its version. If another app changes the file, AI stops instead of overwriting the newer content.

## Privacy Boundary

- File search, sampling, and local reading happen on your Mac.
- Candidate metadata and excerpts needed for an answer are sent to the configured model service.
- Conversations, tool activity, pending confirmations, and undo data stay in `~/Library/Application Support/Fold/Agent/Sessions/`.

---

[← Search files and contents](../files/search.md) | [Guide home](../index.md) | [Settings →](../settings/index.md)
