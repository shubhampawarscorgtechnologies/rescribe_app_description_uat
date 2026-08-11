# Rescribe — How the Apps Work (uat)

Functional documentation for the Rescribe hospital apps, written for support teams
and hospital staff. This is the **uat** copy — the app build for uat opens it
from its menu.

| Page | Covers |
|---|---|
| `index.html` | All four, as tabs |
| `whatsnew.html` | Release walkthroughs, newest first |
| `doctor.html` | Doctor app — 5 screens |
| `nurse.html` | Nurse app — 3 screens |
| `paperless.html` | Paperless documentation (Pen Mode), shared by both apps |

Live: https://shubhampawarscorgtechnologies.github.io/rescribe_app_description_uat/

Deep links: `#whatsnew`, `#doctor`, `#nurse`, `#paper`

Source of these pages lives in the app repo under `docs/_src/`; rebuild with
`python3 docs/_src/build.py`, then publish with
`python3 docs/_src/sync_site.py uat`.
