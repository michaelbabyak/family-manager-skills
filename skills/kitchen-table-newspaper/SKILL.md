---
name: kitchen-table-newspaper
description: Build a printable one-page kitchen newspaper PDF: schedule at top, cute weather strip, family news left, kid-appropriate world news right. Fonts and layout stay locked.
---

# Kitchen table newspaper

Use when the household wants a printable one-page morning newspaper for the kitchen table.

## Output

Generate a single-page PDF, attach it in chat, and add one short line that the paper is ready to print. Do not dump the newspaper as chat text.

## Fonts (locked — do not switch)

- Headlines and body: Liberation Serif / Georgia
- Kickers, weather, schedule labels: Nunito
- Never introduce a third typeface. Cute weather is layout and doodles, not a font change.

## Layout (do not invert)

US Letter, portrait, white page. Classic newspaper: masthead, column rules, tight margins, fill the whole page. Not cute cards.

**Schedule at the top.** A compact key-events strip under the date line (today, tonight, weekend, coming up). Only the real ones.

**Weather is the one cute section.** Full-width strip under the schedule: sky doodle, kid-voice one-liner, big high/low, pack chips. Same fonts as the rest. Do not make the rest of the paper cutesy.

**Left column (wider): family.** A whole column, not a footer box.
- Today's school day
- A short section per kid by first name (tests, folders, sports news they can read)
- This weekend at our house
- Smaller grown-up don't-forgets at the bottom of the column

**Two full-height right columns, both filled top to bottom.**
- **Left of the two: OUT IN THE WORLD.** 2–3 real kid-appropriate stories (science, space, animals, sports). Match the count to the kids' ages — toddlers get fewer stories, each one worth their limited attention. Keep each body to 2–3 short sentences.
- **Right of the two: AROUND TOWN.** This is the emphasis column: 3–4 local items, each with its own headline (festivals, park events, library story time, school fundraisers, local newspaper news — real and checkable). When local news is thin, a second kid-friendly local angle beats another world story.
- Look them up. Do not invent. A one-line source under each story is enough.
- Local stories with real news value (like the Gazette piece) belong in AROUND TOWN, not the world column.
- Content contract for the renderer: `world_news` = list of {headline, body, source}; `around_town_items` = list of {headline, body, source}. The renderer keeps whatever fits cleanly above the footer — short bodies are what let both columns fill.

## Leave off the page

Therapy, medical details, money stress, work meetings, home address.

## Design

White page. Friendly, not corporate. One page, readable from a few feet. Columns must reach the footer. If it spills to page 2, tighten; if the bottom is empty, add a short real story. When revising, change only what was asked — do not restyle the whole paper.
