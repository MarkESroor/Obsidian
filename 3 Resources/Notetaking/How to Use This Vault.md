# How to Use This Vault

[[Home]] · [[Tasks]] · [[0 Inbox/Inbox|Inbox]]

The system has two jobs:

1. Preserve useful thinking and project context.
2. Show you the right actions before their deadlines.

Do not try to catalogue everything. Capture first, then organize only what proves useful.

## Where things belong

| Place | Put this there |
|---|---|
| `0 Inbox` | Unprocessed thoughts, links, and ideas |
| `1 Projects` | Work with a finish line |
| `2 Areas` | Ongoing responsibilities such as Work, Research, Choir, or Violin |
| `3 Resources` | Reference material and reusable knowledge |
| `4 Archive` | Completed or inactive material |
| `5 Daily Notes` | What happened today, working notes, and quick capture |
| `6 Templates` | Reusable note structures |

## Creating a task

A task can live inside the relevant project note, area note, or daily note. The [[Tasks]] page collects all open tasks automatically.

### Easiest method

1. Write a normal checkbox line.
2. Put the cursor on that line.
3. Open the command palette.
4. Run **Tasks: Create or edit task**.
5. Choose its priority and due date.

On the phone, use the same command from the command palette. If you use it frequently, add the Tasks command to your mobile toolbar.

### Typed format

```markdown
- [ ] Send the supervisor update ⏫ 📅 2026-10-01
```

The checkbox makes it a task, `⏫` makes it high priority, and `📅 2026-10-01` is the deadline.

## Priority

Use priority to describe impact, not anxiety.

| Meaning | Marker | Use |
|---|---:|---|
| Highest | 🔺 | Serious consequence if missed; extremely rare |
| High | ⏫ | Important to a current project or commitment |
| Medium | 🔼 | Useful tie-breaker when normal is insufficient |
| Normal | none | Default for ordinary work |
| Low | 🔽 | Optional or easily deferred |
| Lowest | ⏬ | Someday/maybe |

A task without a priority marker is normal. Most tasks should stay normal.

## Dates

| Date | Marker | Meaning |
|---|---:|---|
| Due | 📅 | The real deadline |
| Scheduled | ⏳ | The day you intend to work on it |
| Start | 🛫 | Do not consider it before this date |

For a simple system, use due dates first. Add scheduled dates only when you start planning work in advance.

Dates must be written as `YYYY-MM-DD`. The Tasks command can translate phrases such as “tomorrow” into the correct format.

## How sorting works

The [[Tasks]] dashboard has four sections:

1. Overdue
2. Due today
3. Upcoming deadlines
4. No deadline

Within deadline sections, earlier due dates appear first. If two tasks share a due date, the more important task appears first. Undated tasks are shown separately and sorted by priority.

## Daily routine — about five minutes

### Morning

1. Open today's daily note.
2. Write up to three outcomes under **Focus**.
3. Open [[Tasks]] and check overdue and due-today items.
4. Schedule your day outside Obsidian if exact times matter.

### During the day

- Action you must remember → create a task.
- Thought you may reuse → write a note.
- Unsure where it belongs → put it in [[0 Inbox/Inbox|Inbox]].
- Project decision → record it in the project page.

### End of day

1. Check off completed tasks.
2. Clarify anything captured in the Inbox.
3. Move useful project context into the correct project note.
4. Do not endlessly reorganize folders.

## Weekly review — about fifteen minutes

Create a note using the **Weekly Review** template and:

1. Process the Inbox.
2. Review every active project.
3. Make sure each active project has one clear next action.
4. Check upcoming deadlines.
5. Remove fake deadlines.
6. Archive completed projects.

## Creating new notes

- New project: create it in `1 Projects` and insert the **Project** template.
- Reusable idea or reference: create it in `3 Resources` and insert the **Knowledge Note** template.
- Quick thought: capture it in the Inbox or today's daily note.
- Ongoing responsibility: add it beneath the appropriate note in `2 Areas`.

## Phone capture

Keep an Obsidian widget for **Daily Note** or **New Note** on the Android home screen. Let new loose notes land in `0 Inbox`; the vault is already configured for that folder.

When using Git sync, pull before editing on another device and allow the previous device to finish pushing. Avoid editing the same note simultaneously on your phone and PC.

