---
name: media-list-builder
description: Build a starter media list for a specific organization and story angle by researching who has recently covered that beat, then returning journalists and outlets with linked evidence for why each one fits. Trigger this when the user names an organization or story and asks who to pitch, for a media list, a press list, or which reporters cover a topic. Not for verified email addresses or phone numbers, media monitoring, press release distribution, or writing the pitch itself.
---

# Media List Builder

Paid PR platforms sell a maintained journalist database. This skill has no database. It does the research a person would do by hand: find recent coverage of a beat, identify who wrote it, and explain why that person might care about the user's story. Every name comes with a linked article so the user can verify it before pitching.

## Workflow

1. **Get the inputs.** Ask for whatever is missing, one question at a time: the organization, the story angle in a sentence or two, and the geography or outlet type that matters (national, a specific city or state, trade press, local TV). If the angle is vague, ask what is actually new or newsworthy about it before searching.

2. **Search for recent coverage, not journalist profiles.** Search the angle's topic and the geography, using the actual current date to judge recency. Look for articles from roughly the last 12 months, and favor the last 3 to 6. Run separate searches per sub-beat and per outlet type rather than one combined query. Reporters are found through their recent bylines, not through directory pages.

3. **Build the list from evidence.** For each candidate, capture the reporter's name, outlet, one specific recent article (linked), and a one-sentence reason the angle fits their coverage. Aim for 8 to 15 candidates, mixing outlet types where the user's goal calls for it. Include fewer if the evidence is thin. Do not pad.

4. **Check that each person is still there.** Where the search results show a byline that looks old, or the outlet has restructured, mark the entry "verify current role" instead of listing it as current.

5. **Contact information rules.** Point to the outlet's own contact or tips page and the reporter's public author page when one appears in the search results. Do not guess or construct email addresses from naming patterns, and do not compile personal phone numbers or social accounts. If the user asks for direct emails, explain that this skill does not provide verified contact data and suggest an outlet's masthead, a journalist's own public bio, or a paid database.

6. **Rate confidence honestly.** Mark each entry High, Medium, or Low: High means two or more recent relevant articles, Medium means one strong recent article, Low means adjacent coverage only. Say plainly when a beat has few identifiable reporters.

7. **Self-check before delivering:**
   - Every name traces to an article actually found in this session, with a link
   - No article is described beyond what the search result shows
   - No quotations longer than a few words from any article; paraphrase instead
   - No invented emails, titles, or beats
   - No em dashes
   - If searches returned little, say "I cannot confirm more names from public search" instead of filling the list

## Output format

Open with one sentence restating the angle and geography as searched.

Then a table with these columns:

| Reporter | Outlet | Recent piece | Why it fits | Confidence |

After the table:

- **Gaps:** outlet types or sub-beats where search found nothing useful
- **Verify before pitching:** entries flagged for a current-role check, plus a reminder to read each linked piece once
- **Next step:** one line offering to draft a pitch angle for the top three, if the user wants it

## Notes

- This is a starting list, not a database. Local and niche reporters are easy for search to miss, so encourage the user to add names from their own reading.
- Reporters change beats and outlets often. The linked articles are the evidence; treat the list as a snapshot dated the day it was run, and put that date in the output.
- Coverage monitoring, distribution, and pitch tracking are separate jobs. If the user wants to track pitches and responses over time, point them to a contact tracker rather than extending this skill.
