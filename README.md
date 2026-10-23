# song-ranker

Rank an artist's whole discography with head-to-head matchups (merge sort, in the browser).

- Search any artist (picks from several matches if the name is ambiguous)
- Choose albums / singles & EPs, then pick winners — keyboard: `←` `→` pick, `↓` tie, `Z` undo
- Album art and 30s previews so you can actually hear the songs
- Progress is saved automatically; refresh and resume where you left off
- Share top/bottom picks or copy the full ranking

Single static `index.html`, no build step. Catalog data comes from the iTunes Search API.
