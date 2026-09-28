# Media List Builder

A Claude Skill that builds a starter media list for your organization and story angle. It finds who has recently covered your beat and gives you a linked article as evidence for every name, so you can verify each one before you pitch.

Built by [Plain Speaking Communications](https://plainspeakingcomms.com). Free.

## What it does

- Asks for your organization, your story angle, and the geography or outlet type that matters
- Searches for recent coverage of that beat and identifies who wrote it
- Returns a table with the reporter, outlet, a linked recent piece, why it fits your angle, and a confidence rating (High, Medium, or Low)
- Flags entries where the reporter's current role needs checking, and lists gaps where search found nothing useful

## What it does not do

- Provide verified email addresses or phone numbers. It points to outlet contact pages and public author pages only, and it never guesses emails.
- Tell you journalists' pitching preferences or who is actively requesting sources
- Monitor coverage, distribute press releases, or track pitches
- Replace a paid media database. It is a starting list, not a maintained directory.

## How to use it

1. Download `SKILL.md` from this repo.
2. Add it as a skill in your Claude account.
3. Ask Claude for a media list, for example:

> Build a media list for [organization]. Story angle: [one or two sentences on what is new or newsworthy]. Focus on [national, a city or state, or trade] outlets.

## Good to know

- The skill relies on web search, so local and niche reporters are easy to miss. Add names from your own reading.
- Read each linked article once before you pitch, and confirm the reporter is still on that beat.
- Every list is a snapshot dated the day it was run. Reporters change beats and outlets often.

## More from PSC

More free tools and Claude Skills for nonprofit communicators: [plainspeakingcomms.com/psc-tools](https://plainspeakingcomms.com/psc-tools)
