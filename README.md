# Content Pipeline Toolkit

A lightweight system to capture video ideas, draft scripts, and track content production from ideation to published.

## Quick Start

```bash
# Generate a new content idea
cd ~/Projects/content-pipeline
./bin/new-content "Why I Stopped Day Trading"

# This creates: content/2026-02-25-why-i-stopped-day-trading.md
```

## What's Included

### Templates (in `templates/`)
1. **content-idea.md** — Capture raw ideas with hooks, angles, audience
2. **video-script.md** — Full script structure (hook, problem, solution, CTA)
3. **weekly-calendar.md** — Track your content pipeline status
4. **thumbnail-guide.md** — Checklist + title formulas for finance niche

### CLI Tools (in `bin/`)
- **new-content** — Generate dated idea files from template

## Workflow

```
1. Capture Idea
   ./bin/new-content "Your Idea Here"
   → Creates file in content/

2. Fill Template
   Edit the generated file with your hook, angle, research

3. Script It
   Copy to video-script.md format when ready to record

4. Track Progress
   Update weekly-calendar.md as you move through pipeline

5. Publish
   Check thumbnail-guide.md before hitting upload
```

## File Organization

```
content-pipeline/
├── bin/
│   └── new-content          # CLI generator
├── templates/
│   ├── content-idea.md      # Idea capture template
│   ├── video-script.md      # Full script template
│   ├── weekly-calendar.md   # Pipeline tracker
│   └── thumbnail-guide.md   # Thumbnail + title formulas
├── content/                 # Your generated ideas live here
│   ├── 2026-02-25-idea-1.md
│   └── 2026-02-26-idea-2.md
└── README.md               # This file
```

## Title Formulas (Finance Niche)

See `templates/thumbnail-guide.md` for complete list.

Quick wins:
- "I wish I knew [X] before [painful outcome]"
- "Stop [common mistake] — do this instead"
- "[Number] signs you're [undesirable state]"

## Status Meanings

| Status | Meaning |
|--------|---------|
| ideation | Raw idea, needs research |
| research | Gathering facts, examples |
| scripting | Writing script |
| ready | Ready to film |
| filmed | Footage captured |
| editing | Post-production |
| published | Live! |

---

Built by Friday for Terry. No dependencies, no cloud, just files.
