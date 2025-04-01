---
title: Coderef2 Quick Guide for SPA Agent
version: 1.0.0
date: 2025-04-01
authors:
  - name: Coderef Mentor
tags: ["#guide", "#coderef2", "#spa"]
classification: INTERNAL
description: How to use and inject Coderef2 tags for the docked SPA project.
---

# Coderef2 Quick Guide – SPA Docked Nav

## Format

```text
@Type/path#element
```

| Type | Example | Use |
|------|---------|-----|
| Page | `@Pg/spa/DockedPage#page-1` | Page sections |
| Style | `@S/spa/layout` | CSS files |
| Function | `@Fn/spa/app#initThemeToggle` | JS functions |

## Best Practices

- Add comment blocks at the top of CSS/JS files.
- Annotate key JS functions.
- Each `.md` must include `[agent-directive]` footer.

## Index Example

```md
| Tag | Description |
|-----|-------------|
| @Pg/spa/DockedPage#page-1 | Page 1 Section |
```

[agent-directive]
ref: coderef2-guide-spa
type: training
scope: guide
phase: 1
step: 0
linked-docs: []
instructions: |
  Use this as reference throughout SPA tagging and validation.
