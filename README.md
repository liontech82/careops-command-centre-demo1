# CareOps Command Centre Demo

Static provider-demo dashboard for CareOps Systems / LionTech Innovations.

## Purpose

This is an offline-friendly HTML mockup for in-person care provider demos. It shows how CareOps can surface what is missing, overdue and at risk for a demo provider without changing the provider's current systems.

Demo provider data is fictional and held in `data/mock.json`.

## Run Locally

From this folder:

```powershell
python -m http.server 8765 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:8765/
```

No build step, login, backend, database or integration is required.

## Files

- `index.html` - static command-centre screen and drawer interactions.
- `data/mock.json` - seeded fictional UK care demo data.
- `README.md` - run and handoff notes.

## Demo Rules

- Fictional provider and person records only.
- Red, amber and green status logic only.
- No promised care outcomes.
- No invented proof claims.
- No payment, production data or credentials.
