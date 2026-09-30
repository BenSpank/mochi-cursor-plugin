---
name: mochi-pr
description: Draft a pull request description that explains the change and the meetings behind it.
---

# mochi-pr

Read the branch: its diff against the base and its commits. Find the meetings where this work was planned with `query_mochi_meetings`, and read them with `get_meetings`.

Write the description as a normal PR: what changed and why. Where a decision came from a meeting, cite it inline with its title and date. End with anything the PR decides that no meeting did, so the reviewer can weigh in.

If the branch doesn't make the topic clear, ask what it's for.
