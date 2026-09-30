---
name: mochi-recall
description: Answer "what did we decide about X" from the person's Mochi meetings. Use when someone asks about a past discussion, a decision, or who said what.
---

# mochi-recall

Find the answer in Mochi and give it back short enough to use mid-task.

1. Search with `query_mochi_meetings` using the few words that matter. Try a second phrasing if the first finds nothing.
2. For "last week", "in August" and the like, use `list_meetings` with `from` and `to`.
3. Read the best one to three matches with `get_meetings`.

Answer with the decision itself, then the meeting title, date and the people in it. If the topic came up more than once, say whether the decision held or changed. For the exact wording of a booked call, use `get_meeting_transcript`.

If Mochi has nothing on it, say so; don't fill the gap with a guess.
