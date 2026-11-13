# MemeMap frontend showcase

This repository contains the static frontend showcase in `mememap-frontend`.

- `index.html`: bilingual landing, demo login and profile.
- `landing.html`: MapLibre map, pins, profiles, leaderboard and demo admin UI.
- `assets/css/`: shared, home, map and admin styling.
- `assets/js/api.js`: browser-only session adapter. No server API or database is used.

| Document | Contents | Vietnamese counterpart |
## Demo accounts

| Username | Password | Role |
| --- | --- | --- |
| `guest` | `guest123` | Demo user |
| `admin-demo` | `admin123` | Demo admin |

State is stored in `sessionStorage` for the current browser tab. Do not use these credentials for production.

## Run

```sh
python3 -m http.server 6767
```

Open `http://localhost:6767`. The full-stack Python/SQLite application is maintained separately in the `mememap` repository. Historical notes remain under `docs/en/history/`.
