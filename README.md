# Aperture

A personal pattern interpreter. Aperture surfaces behavioral insights 
from your transaction and location data — not to optimize you, but to 
help you see yourself more clearly.

**Core belief:** Repetition isn't bad. Narrowness without awareness is.

---

## What it does

Aperture looks at where you spend your time and money and surfaces 
patterns you might not have noticed. It doesn't tell you what to do 
about them. Action is optional.

Three things generate insights:
- **Repetition Beyond Chance** — same merchant 3x in 4 weeks
- **Range Compression** — your diversity drops significantly over time
- **Cultural/Social Scarcity** — minimal cultural activity relative 
  to overall volume

What it deliberately doesn't do: tell you what you're missing, 
compare you to others, assign scores, set goals, or suggest you 
should change anything.

---

## Privacy architecture

Raw location coordinates are discarded at parse time. Locations are 
stored as geohash-7 (~150m precision) — specific enough to visualize 
neighborhoods, not specific enough to identify a building.

No transaction amounts are stored. Only merchant names and timestamps.

Insights are observations, not recommendations.

---

## Stack

Python · FastAPI · PostgreSQL · React · TypeScript · Vite  
Google OAuth · Supabase · Netlify

---

## Status

Active development. Not yet in public beta.
