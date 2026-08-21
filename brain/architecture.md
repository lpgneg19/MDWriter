---
slug: architecture
title: System architecture
role: system architecture
updated: "2026-08-21T06:38:34"
---

# System architecture

```mermaid
graph TD
    App[MDWriter macOS App] --> Doc[Document & Workspace Manager]
    App --> Editor[MDEditorKit Editor Surface]
    App --> AI[AI Writing Assistant / Chat]
    App --> Export[Export Engine PDF / HTML / EPUB]
    App --> Sparkle[Sparkle Update Service]
```
