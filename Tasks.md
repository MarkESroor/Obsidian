# Tasks

[[Home]] · [Capture today](obsidian://daily?vault=Obsidian) · [[Ideas]] · [[0 Inbox/Inbox|Inbox]]

Tasks are collected from their original notes. Click a checkbox here to complete the original; follow its backlink to edit the wording. On Windows, `Ctrl+Alt+T` opens the task editor on the current line.

Use at most one action tag: `#next` = ready, `#waiting` = blocked or delegated, `#someday` = optional. An untagged task stays in **Needs sorting**. When changing state, replace the old tag.

## Overdue and today

Real deadlines, earliest first. These remain visible even if a task is waiting or has not been sorted.

```tasks
not done
due before tomorrow
sort by due
sort by priority
group by due
```

## Ready next actions

Ready tasks, grouped by their source note. Future start or scheduled dates keep a task out until its time comes.

```tasks
not done
tags include #next
tags do not include #waiting
tags do not include #someday
(no start date) OR (starts before tomorrow)
(no scheduled date) OR (scheduled before tomorrow)
sort by priority
sort by due
group by filename
```

## Coming up

Future deadlines, scheduled work, and start dates. Date lists can show the same task as a state list; both refer to the same original checkbox.

```tasks
not done
((has due date) AND (due after today)) OR ((has scheduled date) AND (scheduled after today)) OR ((has start date) AND (starts after today))
sort by happens
sort by priority
group by filename
```

## Waiting

Write who or what you are waiting for. Use a scheduled date for a follow-up; it will appear on Home when that day arrives.

```tasks
not done
tags include #waiting
sort by scheduled
sort by due
group by filename
```

## Someday

Review weekly. Promote a task by replacing `#someday` with `#next` when you commit to doing it.

```tasks
not done
tags include #someday
sort by priority
group by filename
```

## Needs sorting

Every untagged open task, including captures from previous days. Rewrite vague actions, then choose next, waiting, or someday. Checking a task off also removes it from this list.

```tasks
not done
tags do not include #next
tags do not include #waiting
tags do not include #someday
sort by priority
sort by due
group by filename
```

## Standalone actions

Keep tasks with no project or area here if you want to move them out of a daily note. Moving is optional: all daily-note tasks remain in the dashboard until completed.
