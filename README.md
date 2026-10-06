# Élections Québec 2026

A bilingual (French and English) dashboard for following Quebec's 2026 provincial election.

## Open the app

Open the app via a local web server for the full PWA experience, such as:

```bash
cd /path/to/elections
python3 -m http.server 8000
```

Then visit `http://localhost:8000/` in a modern browser. The app is installable as a PWA on supported browsers and loads cached shell assets offline after the first visit. An internet connection is still needed for live results.

## Live results

The dashboard reads preliminary results directly from Élections Québec's public results feed and refreshes every 60 seconds. The feed may be cached for up to two minutes. Candidate leads are preliminary and are not certified winners; consult the official results page for authoritative updates.

- [English live results](https://www.electionsquebec.qc.ca/en/results-and-statistics/provincial-general-elections-live-results/)
- [Résultats en français](https://www.electionsquebec.qc.ca/resultats-et-statistiques/resultats-elections-generales-provinciales-en-direct/)

The language toggle defaults to French and remembers the selected language in the browser.
