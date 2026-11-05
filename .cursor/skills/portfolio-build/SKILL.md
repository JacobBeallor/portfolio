---
name: portfolio-build
description: Build a greenfield portfolio site from one design brief, using the shared recipe. Use when the user asks to build Jacob Beallor's portfolio, follow the recipe, or run a design attempt.
---

# Portfolio build

The parent chat is the coordinator. It plans, splits the work, and checks each result. It does not write the page.

Delegate each chunk to the implementer. Delegate scoring to the reviewer. One implementer invocation is one task. Do not hand an implementer the whole site, the whole plan, or a list of tasks.

This attempt is one entry in a bake-off. Other agents are building other sites from other briefs, using these same facts. Make this the site a person would actually publish. A recognizable point of view beats a louder page. The hard checks still have to pass.

Read `recipe/content.md`, `recipe/constraints.md`, `recipe/rubric.md`, and the one brief named in the launch prompt before any other work.

## 1. Plan

Write `design/reviews/<slug>.md` with:

- Stack, and why it fits the brief and the Vercel constraint
- Skills to install, at project scope only
- Page structure
- Where placeholders go
- The one signature motion
- An ordered task list
- A stop, if the brief fights the constraints

Do not install a skill that would choose a different art direction than the brief.

A task is one outcome. Examples: install the named skills and scaffold the app, build one section, add the signature motion, fix one hard failure, address one taste note. A task is not "build the site" and not "polish the page."

Each task names:

- The outcome
- The files it may create or edit
- The files it must leave alone
- How the coordinator will know it is done

Run tasks in order. Tasks with no shared files may run at the same time. Tasks that touch the same files run one after another.

## 2. Build

For each task, call the implementer with that task only. When it returns, check the done condition before starting a task that depends on it. If the chunk missed the outcome, send that same task back once with what is missing. If it misses again, write the block in the review note and replan that chunk. Do not widen the task into the rest of the site.

The last build task leaves `dev` and `build` succeeding. Placeholders are listed in the review note.

## 3. Review

Hand the running site to the reviewer. The reviewer looks at the page in a browser, on desktop and a phone width, and returns two lists: hard failures and taste notes. It also runs the accessibility check, Impeccable `critique` and `audit`, and `review-animations` on the signature motion, once those tools are installed.

## 4. Hard checks

Turn each hard failure into its own task. Send those tasks to the implementer. Then call the reviewer again. Repeat until `recipe/rubric.md` hard checks pass. If the same hard failure comes back unchanged, stop and write that the attempt is stuck. Do not start taste revisions on a broken site.

## 5. Taste

After the hard checks pass, run four revision rounds. Each round, turn the taste notes into discrete tasks, one note or one tightly related group per task. The implementer addresses those tasks. The reviewer looks again. Taste notes come from the brief, the critique, and the motion review. After the fourth round, stop and write the score in `design/reviews/<slug>.md`, including screenshot paths and the placeholder list.
