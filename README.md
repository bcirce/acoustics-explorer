<div align="center">

<img src="screenshots/icon.svg" width="72" alt="The Acoustics Explorer spiral mark">

# Acoustics Explorer

### The Acoustics Community Hub

Courses, events and jobs in **acoustic engineering**, scattered across hundreds of
universities, societies and companies, gathered onto one interactive world map.

**250+ opportunities · 50+ countries · 170+ cities · every entry traced to an official source**

**[→ Open the live map at acousticsexplorer.com](https://acousticsexplorer.com)**

![The Acoustics Explorer dashboard](screenshots/hero.png)

</div>

---

## Why it exists

If you work or study in acoustics, the next master's programme, congress or job is out
there, but it's spread across society calendars, university pages and company career
sites in a dozen languages. Acoustics Explorer puts it all on one map, checks every entry
against its official source, and keeps it current.

It's built by an acoustic engineer, for acousticians: students looking for a programme,
researchers looking for the next symposium, and engineers looking for their next role.

## What you can do

### See everything on one map

Markers are **shaped** by category (● course, ▲ event, ■ job) and **coloured** by status:
blue *soon*, green *open*, orange *closed*. Nearby entries cluster, and zooming splits them
apart.

### Narrow it down in one tap

<img src="screenshots/filters.png" align="right" width="300" alt="The filters sidebar">

Status, type and field, each with a **live count** of what's there. Nothing selected means
everything; tapping a chip means *show only this*. Counts follow the map as you move it.
Free-text search turns matches into removable chips, and tapping a topic on any card adds it
as a filter.

<br clear="right">

### Open an entry and the map follows

![An entry card open over the map](screenshots/entry-card.png)

The map flies to the city and opens a card with what matters: organiser, location, dates,
deadline, topics, and a link to the official page. Every card says whether a person has
reviewed it (**✓ Human-reviewed**) or it was machine-checked only.

### Explore a country

![The per-country view for Germany](screenshots/country.png)

Pick a country and everything scopes to it: the camera frames it, the results filter to it,
and the address becomes a link you can share.

### Keep your own list, no account needed

Bookmark entries into **My list**. It lives in your browser only; nothing is sent anywhere.

### Suggest an opportunity

Anyone can submit a course, event or job. Paste a link and the form fills itself in; every
submission is reviewed before it appears.

## Seven looks, light and dark

![Four of the seven skins, two dark and two light](screenshots/themes.png)

**Anechoic** (the default: precision lab), **Glasswork**, **Sonar**, **Control Room**,
**Field Atlas**, **Community Board** and **High Contrast**, each in light and dark. They
change typography, panels and the map's palette, never the layout.

## Accessible by design

- Colour-blind-safe status colours ([Okabe–Ito](https://jfly.uni-koeln.de/color/)), and
  status is always written out as a word too.
- A **High Contrast** skin with 19:1+ text and [Atkinson Hyperlegible](https://brailleinstitute.org/freefont).
- Full keyboard and screen-reader support, tested with **VoiceOver** on iPhone.
- **Read aloud** on every entry, in your browser's own voice.
- 44px touch targets on phones, and reduced motion respected everywhere.

The known gaps are listed openly in the [roadmap](ROADMAP.md).

## Trustworthy by rule

An entry is published only when it is a **specific, named opportunity**, confirmed by an
**official page that actually loads**, from a **legitimate organiser**, **in scope** for
acoustics, **placeable** on the map and **not a duplicate**. Anything that would need guessing
is left out: an honest gap beats invented data. [How it works](HOW-IT-WORKS.md) explains the
pipeline.

## Privacy

No ads, no analytics, no tracking. Your filters, theme and list stay on your device. The
only cookie is the sign-in one, and only if you sign in to submit.

## Built with

Next.js · React · TypeScript · Tailwind CSS · MapLibre GL · PostgreSQL (Supabase) · Prisma ·
Vercel. Map data from Natural Earth, CARTO and © OpenStreetMap contributors.

## Get involved

The source code is private, but there's plenty you can do here:

- **Suggest an opportunity or a source** the map is missing
- **Report a bug** or something that looks wrong
- **Share an idea**

Use the [issue templates](../../issues/new/choose), or see [CONTRIBUTING.md](CONTRIBUTING.md).
What's coming next is in the [roadmap](ROADMAP.md), and what changed is in the
[changelog](CHANGELOG.md).

## About

Created by **Bárbara Circe**, acoustic engineer, and developed with Claude (Anthropic).
The first layout started from the M.O.N.K.Y Dashboard community template on v0 by Vercel.

© 2026 Bárbara Circe. All rights reserved. "Acoustics Explorer", "The Acoustics Community
Hub" and the spiral mark are her trademarks. See [LICENSE](LICENSE).
