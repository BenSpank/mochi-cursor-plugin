# Mochi for Cursor

Mochi takes your meeting notes. This plugin lets Cursor read them, so it can build what the team actually agreed on and cite the meeting where it was decided.

## What's inside

| | |
|---|---|
| **MCP server** | `https://www.mochimeet.com/api/mcp`, read-only |
| **Skills** | `mochi-recall` (what did we decide?), `mochi-prep` (brief me before a call), `mochi-check` (does this PR match the plan?) |
| **Agent** | `mochi-engineer`, which checks the meetings before choosing an approach |
| **Rule** | `mochi-meeting-context`, which looks things up when a task clearly came from a conversation |
| **Commands** | `/mochi-pr`, `/mochi-brief`, `/mochi-gaps`, `/mochi-followups`, `/mochi-bug-report` |

### Tools

- `query_mochi_meetings`: search notes and summaries
- `list_meetings`: past meetings by date or folder
- `list_meeting_folders`: your private folders and your teams' shared folders
- `get_meetings`: full notes, summary, action items
- `list_upcoming_meetings`: your calendar and booked calls
- `get_meeting_transcript`: word-for-word transcript of a call booked through a Mochi page, while Mochi keeps it
- `get_account_info`: which account is connected

## What Cursor can see

- Your own notes, and the notes in the shared folders of every team you belong to. A teammate's note is marked with who wrote it.
- Summaries of calls booked through your Mochi pages, and their transcripts while Mochi keeps them.
- Notes recorded with the Mochi Mac app keep their audio and transcript on your Mac. Cursor sees their notes and summary only.

Nothing can be changed or deleted through the plugin.

## Connect

1. Install the plugin.
2. In Cursor Settings, open MCP, and click **Connect** next to `mochi`.
3. Mochi opens in your browser. Sign in if you need to, check the app name and the address shown, and click **Allow**.

Cursor keeps itself signed in. To cut it off, go to Mochi, **Account settings**, **Connected apps**, and click **Disconnect**.

## License

MIT
