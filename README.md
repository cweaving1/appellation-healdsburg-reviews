# Appellation Healdsburg — Online Review Dashboard

Single-page review dashboard for Appellation Healdsburg and its outlets (Folia, Andys Beeline Rooftop, Terroir Spa).

- **Hotel** data via the Revinate Porter API (8 channels), with Tripadvisor-sourced owner-response status and competitive indexing vs. the comp set.
- **Restaurants** via OpenTable (exact) + Google.
- Sentiment heat maps, featured best/worst reviews, and management action items per tab.

Hosted via GitHub Pages. Chart.js loaded from CDN; brand logos embedded as data-URIs. Snapshot — auto-refresh pipeline (Revinate + OpenTable re-pull) and Supabase write layer (in-dashboard review replies) planned.
