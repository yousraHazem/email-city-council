# Write Your Ward

A static page that finds your Mississauga ward from your postal code, lists that ward's 2026 councillor candidates (and optionally the mayoral candidates), and drafts an email about the threats sent to Islamic schools.

## Run

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Refresh candidate and ward data

```sh
python3 scripts/update_data.py
```

This regenerates `data/candidates.js` from the list on [Mississauga Votes: Who's running](https://mississaugavotes.ca/2026-municipal-election/for-voters/whos-running/) and `data/wards.js` from [Mississauga Open Data](https://data.mississauga.ca/datasets/ward-boundaries).
