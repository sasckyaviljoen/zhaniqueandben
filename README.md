# Zhanique & Ben — wedding website

Saturday 16 January 2027 · Chocolat Bistro, Durbanville, Cape Town

Live site: https://sasckyaviljoen.github.io/zhaniqueandben/

## What's here

| File | What it is |
|---|---|
| `index.html` | The whole website: envelope intro, details, colour scheme and RSVP form |
| `rsvp.sql` | One-time Supabase setup that creates the `wedding_rsvps` table |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Changing details

Names, date, time and RSVP deadline are in the `WEDDING` settings near the bottom of `index.html`.

## RSVPs

Replies are saved in Supabase. Guests can only add a reply; they can't read anyone else's.

1. **Setup (once):** Supabase dashboard → SQL Editor → New query → paste `rsvp.sql` → Run.
2. **See replies:** Supabase dashboard → Table Editor → `wedding_rsvps`. Export to CSV from there.

## Hosting

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
