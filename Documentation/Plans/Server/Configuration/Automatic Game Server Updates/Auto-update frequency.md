---
created: 2026-04-10
modified: 2026-04-19
tags:
  - Plans/Server/Configuration
aliases:
  - update schedule
---
How often the server automatically restarts with this schedule to install new mods (if needed).
Automatic updates will only include mods that have either been auto-approved or manually approved. The CollabPack server admin can also simply allow all mods.

Only 1 update can run per day, choosing the least frequent and most impactful update across the different schedules.
## Daily
Will update the server on a daily basis at a specified time, unless a less frequent schedule would also run that day.
### Time of Day
The time at which the server updates. Stored in UTC and shown in both UTC and local time zone. If this difference causes a difference in day, also show this.

Default to UTC midnight.
## Weekly
Will update the server on a weekly basis, on a specified day. If a daily schedule exists, it'll use the time specified there (and show it in the UI). Otherwise, it'll reuse the input field of the daily schedule.
### Day of Week
Which day of the week it'll update.

Default to Sunday.
### Time of Day
If a daily schedule exists, it uses those settings, otherwise gives the options here.
## Monthly
Will update the server on a monthly basis. Option for first day of month or first time a weekly update would trigger.
### Subschedule
Whether to use the daily or weekly schedule
#### Day of Month
N-th day of month, or N-th last day of month when "last" checkbox ticked
minimum 1 for first day of the month (and default)
Suggestion of toggling "last" when going over 15.
Major warning going over 28 or under -28 (because February)
absolute maximum 31
#### Week of Month
When positive, N-th (day of week) of month.
If weekly schedule exists, use that [[#Day of Week]], otherwise give settings here.

## Yearly
