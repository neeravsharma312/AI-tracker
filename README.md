# ORF AI Signal

A daily AI-landscape intelligence feed (launches, open-weight models, India AI,
governance, funding/geopolitics) for ORF.

- **index.html** — the page. Host it once (e.g. on spatialmind.in). It reads
  `data.json` live on every visit, so it never needs re-uploading.
- **data.json** — the signals. Refreshed automatically each morning (IST) by a
  scheduled task that commits a new version here. The page fetches this file
  from the repo's raw URL, so updating it updates the live site.

Data is assembled from public sources with confidence tags
(Confirmed / Reported / Projected); verify before citing.
