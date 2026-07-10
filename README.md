# Spine Hyperbook

A curriculum-mapped spine surgery reference for UK orthopaedic and neurosurgical trainees. Independent project.

**Live site:** 

## Preview changes locally

```bash
python3 -m mkdocs serve
```

Open http://127.0.0.1:8000, edits to any file in `docs/` refresh the browser automatically.

## Publish changes

```bash
git add .
git commit -m "describe what you changed"
git push
```

Pushing to `main` rebuilds and redeploys the live site automatically, usually live within a minute or two.

## Adding a new page

New files need adding to the `nav:` section in `mkdocs.yml` as well as creating in `docs/`, otherwise they won't appear in the site menu.
