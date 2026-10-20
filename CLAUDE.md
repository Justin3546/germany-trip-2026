# Trip journal site

Public, noindex page for friends and family to follow the October 2026 Germany and Switzerland trip.
During the trip a pipeline on Justin's Mac published each day into `index.html`, `photos/dayN/` and
`video/dayN.*`; it ended 10/18 (launchd job unloaded). Since 10/19 (card #1089) `index.html` is the
scrolling map version: `geo.js` holds the map data, and `media/` holds what the page loads
(`dN/imgK.jpg` lightbox photos, `dN/t/` 520 px thumbnails, `dayN.mp4`/`dayN.jpg` re-encoded videos
and posters, `relief-*.webp`). `photos/` and `video/` are the original full-size files, kept but unused.
Source and speed test: `~/Claude/Firm/Board-Work/1089/`.

- Videos never autoplay; they start only on tap.
- Keep the noindex meta tags and `robots.txt`.
- Never add a surname, anyone's age or grade, or where we are staying.
- Each published day's timeline shows what we actually did, in past tense, added and removed to match (Justin 10/16). Photos use small square tiles (no wide gallery).
