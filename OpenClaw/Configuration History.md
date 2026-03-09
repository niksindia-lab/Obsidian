# OpenClaw Configuration History

## Identity
- **Name**: Jarvis (changed from Audi on Feb 28, 2026)
- **Role**: AI chief of staff

## Telegram Setup
- Bot was set up for communication
- Family member approval: Pooja (approved)
- Chat ID for Nikhil: 5292769291
- Inline buttons implemented for quick responses (reading_yes, reading_no)

## Model Configuration
- Claude (Anthropic) - primary for complex tasks
- Ollama local models - for simpler requests (requested Feb 28, 2026)
- Model switching implemented to save Claude usage

## Cron Jobs Active
| Job Name | Schedule | Purpose |
|----------|----------|---------|
| morning-reading | 8:00 AM | Daily reading reminder |
| reading-checkin | 8:20 AM | Follow-up check |
| reading-reminder-noon | 12:00 PM | Midday reminder |
| reading-reminder-4pm | 4:00 PM | Afternoon reminder |
| reading-reminder-8pm | 8:00 PM | Evening reminder |
| badminton-book-monday | Sun 7:30 PM | Book Monday session |
| badminton-check-monday | Monday AM | Day-of check |
| badminton-nudge-monday | Monday 7:15 PM | Pre-session reminder |
| rrsp-* | Mar 2, 2026 | Multiple reminders |

## Webchat
- Dashboard URL required for browser access
- Token authentication needed
- If "gateway down" or "unauthorized" errors: use `openclaw dashboard --no-open` to get new tokenized URL

## Notes
- OpenClaw TUI (terminal UI) used as primary interface
- Webchat secondary for browser access
- Connection issues experienced March 1-5, 2026

---