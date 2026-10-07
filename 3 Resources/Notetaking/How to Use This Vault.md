# How to use this vault

[[Home]] · [[Tasks]] · [[Ideas]] · [[0 Inbox/Inbox|Inbox]]

The working loop is **capture → clarify → choose → do → review**. Your folders already provide enough structure. The improvement is a capture habit and a short list you trust.

## Capture in seconds

**Windows, inside Obsidian:** press `Ctrl+Alt+D` to open today's note, then `Ctrl+End` to reach **Capture**. Write one thought per line. Nothing has to be filed or prioritized now.

```markdown
- Try using audio prompts in the VR experiment
- [ ] Email the supervisor about the pilot results
```

For an idea you already know you want to revisit, add `#idea` immediately. Otherwise add it during review. An action needs a checkbox to enter the task dashboard; `Ctrl+L` turns the current line into a task.

**Phone:** pull down from the top of the app to open today's note after the updated settings have synced. Use the toolbar's checkbox button to turn a line into a task. Keyboard dictation is fine: say the thought, then make it a checkbox if it needs action.

**Longer capture or shared link:** create a new note. New notes land in `0 Inbox` automatically. Give it a useful title when you have time.

Do not copy yesterday's unfinished checkboxes into today's note. [[Tasks]] keeps collecting them from the original date until you complete them.

## Sort in five minutes

Open today's captures and [[Tasks#Needs sorting|Needs sorting]]. Make each action specific enough to do: a verb, an object, and enough context to know what finished means.

```markdown
- [ ] Email the supervisor three questions about the pilot [[Masters Thesis]] #next
- [ ] Waiting for feedback from the supervisor on the protocol #waiting
- [ ] Try an alternative room-lighting design [[VRMasters]] #someday
- Audio cues might make landmarks easier to remember [[VRMasters]] #idea
```

Use at most one task state; replace it when the situation changes:

| Marker | Meaning | What to do with it |
|---|---|---|
| `#next` | Ready to do | Choose a few from the ready list |
| `#waiting` | Blocked or delegated | Name who or what; plan a follow-up if needed |
| `#someday` | Optional, no commitment yet | Revisit during the weekly review |
| No state tag | Captured but not clarified | It stays in Needs sorting |
| `#idea` on a thought | Worth revisiting | It appears in Ideas; no action is required |

A project link is optional during capture. Adding `[[Masters Thesis]]`, `[[VRMasters]]`, or `[[Work]]` to a task also shows it in that page's task view, even when the original is in a daily note. Keep the checkbox in one place.

If an action takes about two minutes and you can do it now, do it and check it off. If a capture has stopped being useful, drop it during review.

## File only when a home is useful

A task can stay in its daily note indefinitely. Move longer thinking or references when you will use them again.

| Folder | Decision | Example |
|---|---|---|
| `0 Inbox` | Not clarified yet | A shared article or loose new note |
| `1 Projects` | Has a finish line | Masters Thesis; Wedding Song |
| `2 Areas` | Ongoing responsibility | Work; Choir; Violin; Journal |
| `3 Resources` | Reusable information | A testing technique or mnemonic explanation |
| `4 Archive` | Finished or inactive | A completed project and its supporting notes |
| `5 Daily Notes` | Dated working log | Today's thoughts, actions, and events |
| `6 Templates` | Reusable structure | Daily Note, Project, Knowledge Note, Weekly Review |

**Move a whole note:** `Ctrl+M`, then choose the folder.

**Move only a passage:** select it, press `Ctrl+Shift+E`, and choose an existing destination note. `Enter` appends the passage there. Obsidian replaces the source passage with a link, keeping a trail without copying the task.

To create a new note from a selection, use **Note composer: Extract current selection...** and choose a new title. It starts in Inbox; move it when the destination is clear.

For a new project or useful reference, create a note and use **Templates: Insert template** from `Ctrl+P`. A useful knowledge note explains the idea in your own words, links its source, and says where you can use it. Most quick captures need no template.

Before archiving a project, complete, cancel, or relocate its outstanding actions: tasks in `4 Archive` are excluded from task views. Templates are excluded too. Changing a project's `status` property alone does not archive its tasks.

## Dates and priority

On Windows, place the cursor on a task and press `Ctrl+Alt+T`. On mobile, tap the task editor button in the toolbar. Use **Tasks: Create or edit task** to choose a date without typing emoji.

| Field | Use it for |
|---|---|
| Due, `📅` | A real deadline |
| Scheduled, `⏳` | The day you intend to work, or follow up |
| Start, `🛫` | The earliest day an action becomes available |

Use no dates when none are needed. Start with normal priority; use high priority only for a meaningful consequence. Pick tomorrow as a scheduled date when you intend to do something tomorrow but it has no deadline.

Home shows deadlines and scheduled work for today or earlier, plus ready next actions. Future start or scheduled dates keep a next action out of the ready list until its time comes. **Coming up** still shows it. Waiting and someday remain separate, and **Needs sorting** catches every untagged open task.

Date sections and state sections can both show one task. They are views of one checkbox. Clicking it in a Tasks query updates the source note.

## The small routine

**Morning, 2 minutes:** check Home, pick up to three outcomes, and write them under **Focus** in today's note. Link to existing tasks instead of duplicating their checkboxes.

**During the day:** open today's note, capture, return to what you were doing.

**Evening, 5 minutes:** tag useful ideas, clarify untagged actions, and process loose Inbox notes. Do not reorganize every daily entry.

**Weekly, 15 minutes:** use the Weekly Review template. Check every active project has a clear next action; revisit Ideas and Waiting; look at coming dates; archive completed work.

## Phone setup, once

The desktop vault is configured with normal typing, **Open today's daily note** as its mobile pull-down action, and capture/task commands at the front of the mobile toolbar. Your phone needs the updated vault settings before those changes appear.

If you sync only notes, configure these on the phone: set the mobile Quick Action to **Open today's daily note**; under **Settings → Mobile → Manage toolbar options**, add **Toggle checklist status** and the global command **Tasks: Create or edit task**. If the labels differ, search for the command names.

- **Android:** add an Obsidian **Daily Note** home-screen widget and select this vault.
- **iPhone:** use a daily-note widget if available. In Apple Shortcuts, **Capture to Daily Note** can append typed or dictated text; choose the same vault and append position.
- **Either phone:** bookmark shortcuts to Home, Tasks, Ideas, and Inbox are included in the vault. Tap Bookmarks to open them.

Your vault already has Git configured. Use your existing sync process to transfer these changes; finish syncing one device before editing the same note on the other. I have not changed the sync mechanism. Task collection requires the existing Tasks plugin enabled on the phone as well.

## Windows shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl+Alt+D` | Open today's capture note |
| `Ctrl+End` | Jump to its Capture section at the bottom |
| `Ctrl+L` | Turn the current line into a task / toggle its checkbox |
| `Ctrl+Alt+T` | Open the task editor on the current line |
| `Ctrl+M` | Move the current note to a folder |
| `Ctrl+Shift+E` | Extract a selected passage into another note |
| `Ctrl+Alt+B` | Show Bookmarks |
| `Ctrl+O` | Find a note by title |
| `Ctrl+Shift+F` | Search the vault's content |

Restart Obsidian once after these changes. The startup page is Home. The daily-note link assumes this vault is named `Obsidian`; use the daily-note command or widget if your phone gives it a different name.

Feature references: [Daily notes](https://help.obsidian.md/plugins/daily-notes), [mobile controls](https://help.obsidian.md/mobile), [Android widgets](https://help.obsidian.md/android), [iPhone capture](https://help.obsidian.md/ios), [Note composer](https://help.obsidian.md/plugins/note-composer), [Tasks](https://publish.obsidian.md/tasks/Introduction), [task filters](https://publish.obsidian.md/tasks/Queries/Filters), [embedded search](https://help.obsidian.md/plugins/search).
