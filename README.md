# research.co3lho22.com

Source for **[research.co3lho22.com](https://research.co3lho22.com)** — security research, PhD work, and vulnerability research.

Built with Jekyll, hosted on GitHub Pages, domain via Namecheap.

## Related repos

| Repo | Site |
|---|---|
| `Co3lho22/co3lho22.github.io` | [co3lho22.com](https://co3lho22.com) |
| `Co3lho22/research.co3lho22.com` ← this one | [research.co3lho22.com](https://research.co3lho22.com) |
| `Co3lho22/ctf.co3lho22.com` | [ctf.co3lho22.com](https://ctf.co3lho22.com) |

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000`.

## Adding a research project

Create a file in `_projects/slug.md`:

```yaml
---
title: "Project Title"
status: ongoing
tags: [tag1, tag2]
excerpt: "Short description shown on the homepage."
---

Content here in markdown.
```
