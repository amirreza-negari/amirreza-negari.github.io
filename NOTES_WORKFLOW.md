# Notes Workflow

Create a new English note with:

```bash
hugo new notes/my-note-title.md
```

Then edit:

```text
content/en/notes/my-note-title.md
```

Set `draft = false` when you want it to appear on the site.

For Persian notes, create a file in:

```text
content/fa/notes/
```

Use this front matter:

```toml
+++
title = "عنوان یادداشت"
date = "2026-05-08T00:00:00-04:00"
draft = true
description = ""
tags = []
+++
```
