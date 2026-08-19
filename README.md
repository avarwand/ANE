# Avarwand Name Editor (ANE)
A **powerful, modern PowerShell-based GUI tool** for **batch editing file and folder names** — and, since v1.9, for **collecting, copying and moving files** across whole folder trees — with precision, speed, and safety.

No command line. No risk. Full control.

---

## What's New in v1.9
- **Selection File Edit** – a new toolbar window that collects files from an entire folder tree and copies or moves them into one destination
- **Find in results** bar in the Live Search window – filter the found items live by name, type, or format
- Cleaner **PREVIEW** button label (it still previews the first 5 affected items)

---

## Main Features
- **Batch rename files and folders** in one operation  
- **Add text to the beginning** of names (based on match rules)  
- **Add text to the end** of names (based on match rules)  
- **Remove specific words or characters** from names  
- **Match by keyword or symbol** (start, end, or anywhere in name)  
- **Preview-safe logic** – no blind renaming  
- **Collect, copy or move files** from all subfolders into one place *(Selection File Edit)*  
- **Standalone file search** with live result filtering *(Live Search)*  
- **Multithreaded operations** for high performance  
- **Dark-mode GUI** with clean layout  
- **Fully GUI-based** – no PowerShell knowledge required  
- **Works on large directories** with hundreds or thousands of items  

---

## Selection File Edit *(new in v1.9)*

Bring together files that are scattered across many subfolders:

- **Copy or Move** files from a parent folder and all of its subfolders into one destination
- **Three transfer modes**:
  - *Files only* – all files placed flat, next to each other
  - *Folders only* – recreate just the folder structure, without files
  - *Both* – files **and** folders, keeping the structure
- **Level control**: `0` = ALL levels down to the deepest subfolder, `1` = only items directly in the source folder, `2` = plus its direct subfolders, and so on
- **Filter by word** – only items containing the word in their name are processed
- **Name-conflict list** shown *before* anything happens: see exactly which names already exist in the destination or collide with each other, then choose **automatic rename** (`file_1`, `file_2`, …), **skip**, or **overwrite**
- Optional cleanup: after a Move, delete the subfolders that became empty
- **SCAN** preview (item count and total size), **Show Conflicts**, progress bar, detailed log, **CLEAR**, and a safe **STOP** button
- Modern Explorer-style folder picker where paths can simply be **pasted**

---

## Live Search

A standalone search window for finding files and folders fast:

- Search any folder for **files, folders, or both**
- Subfolder scope: root only, 1–5 levels, or unlimited
- Case-sensitive or case-insensitive matching
- **Background search** with progress bar – the window never freezes
- Results grid with number, name, type, and full path
- **Find in results** *(new in v1.9)*: type a word to filter the found items live by name, type, or format – matches highlighted, the rest dimmed, with a live counter
- Double-click a result to open it in Explorer; right-click to copy the path
- **Copy to**, **Move to**, or **Delete** selected results (deletion goes to the **Recycle Bin**)
- Export search results to CSV

---

## Supported Operations
- Files only  
- Folders only  
- Files **and** folders together  
- Recursive directory processing (optional)  

---

## System Requirements
- **OS**: Windows 10 / Windows 11  

No external dependencies required.

---

## How to Use

1. Download the desired Version
2. Unzip it > Install it (_for the installer version_)
3. Select a **target folder**
4. Choose the desired **operation**:
5. Define the **match condition** (word or symbol)
6. Choose **files, folders, or both**
7. Click **Start**
8. Watch the progress → **Done!**

Also available from the toolbar:

- **LIVE SEARCH** – open the standalone search window
- **SELECTION FILE EDIT** – collect (copy/move) files from a folder tree into one destination

---

## Safety Notes

* Renaming never deletes anything – original file contents are never modified
* **Every bulk action asks for confirmation first** (rename, copy, move, delete)
* Selection File Edit lists all **name conflicts before it runs** and handles them the way you choose (rename / skip / overwrite); a **STOP** button cancels safely at any time
* Deleting from Live Search results sends items to the **Recycle Bin**, not into nothing
* Designed to minimize accidental changes

---

## Use Cases

* Cleaning downloaded files
* Normalizing media libraries
* **Collecting files scattered over many subfolders into one folder**
* **Flattening deep folder structures**, or mirroring a structure without its files
* Preparing files for backup or archiving
* Bulk renaming technical or log files
* IT administration and automation tasks

---

## Contributing

This project is released as **freeware**.

While primarily maintained by the author, suggestions, bug reports, and improvement ideas are welcome via email.

Pull requests are currently not accepted.

---

## License

This software is released as freeware under the following terms:

**END USER LICENSE AGREEMENT (EULA)**

This software is provided by **P. Avarwand**, free of charge for personal and commercial use.

By installing or using this software, you agree to:

* Use the software in compliance with the EULA
* Not reverse engineer, decompile, or modify the software
* Not redistribute or claim ownership of the software
* Accept the software "as is" without warranties

*For full EULA terms, see the LICENSE file included in the repository.*

---

**Developed by Avarwand Team**
**Initial Release: December 2025**
**Latest Version: August 2026**

---

## Contact

**Avarwand Support Team**
📧 [avarwand@yahoo.com](mailto:avarwand@yahoo.com)
🌐 [github.com/avarwand](https://github.com/avarwand/)

© 2025–2026 Avarwand. All rights reserved.

---