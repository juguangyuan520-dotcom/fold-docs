# Search Files and Contents

[Use the file tray ←](file-tray.md) | [Guide home](../index.md) | [Fold AI →](../ai/index.md) | [中文](../../files/search.md)

Applies to Fold 0.4.6 and later.

## Entry Points

- Keyboard: `⌘F`
- Interface: the search field in the top toolbar

## Search Scope

- Search starts in the current folder.
- Toggle Include Subfolders to search recursively, or Current Level Only to restrict depth.
- File names are searched directly by Fold.
- Content matches depend on macOS Spotlight indexing.
- Previously generated Fold summaries are also searched.

## Steps

1. Open the folder you want to search.
2. Press `⌘F`.
3. Enter a keyword.
4. Review match types and paths in the results.
5. Click a result to see its thumbnail; press Enter or double-click to open it.
6. Right-click a result and choose Reveal in Folder to locate and select it.

## Result Types

| Label | Meaning |
| --- | --- |
| Filename | The keyword matched the file name |
| Content | Indexed file content matched |
| Summary | A saved Fold summary matched |

## If Search Finds Nothing

1. Confirm the current folder.
2. Check whether subfolders must be included.
3. Confirm the file type is indexed by Spotlight.
4. Refresh the folder with `⌘R`.
5. If it still fails, record the file type, path, and keyword, then submit an issue.

---

[← Use the file tray](file-tray.md) | [Guide home](../index.md) | [Fold AI →](../ai/index.md)
